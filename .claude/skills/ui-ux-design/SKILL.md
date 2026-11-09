---
name: ui-ux-design
description: UI/UX-Design-Grundlagen für Webseiten und Apps: Nutzerflows, Informationsarchitektur, Layout, Typografie, Farbe, Komponenten, Barrierefreiheit, Responsive. Nutzen beim Entwerfen oder Überarbeiten von Oberflächen, vor dem Coden.
---

# UI/UX Design

## Vorgehen
1. **Ziel klären**: Wer nutzt es, welche Hauptaufgabe, welche Erfolgsmetrik (z. B. Anfrage senden, Kauf)?
2. **Flow skizzieren**: Der kürzeste Weg zum Ziel. Pro Screen eine primäre Aktion.
3. **Struktur**: Informationshierarchie, Navigation (max. 5–7 Punkte), klare Seitenabschnitte.
4. **Visuelles System festlegen** (vor dem ersten Screen):
   - Typo: 1–2 Schriften, Skala (z. B. 14/16/20/28/40/56), Zeilenlänge 45–75 Zeichen.
   - Farbe: 1 Primärfarbe, Neutrals, Semantikfarben (Erfolg/Warnung/Fehler). Kontrast mind. 4,5:1 (Text), 3:1 (UI-Elemente).
   - Abstände: 4/8-px-Raster. Radien, Schatten und Rahmen konsistent.
5. **Komponenten**: Buttons (primär/sekundär/Text), Formulare, Karten, Navigation, Modals, Tabellen. Zustände immer mitdenken: Default, Hover, Focus, Active, Disabled, Loading, Empty, Error.
6. **Responsive**: Mobile first, Breakpoints bei ~640/768/1024/1280. Touch-Ziele mind. 44×44 px.
7. **Barrierefreiheit**: Semantisches HTML, sichtbarer Focus, Alt-Texte, Labels an Inputs, Tastaturbedienung, `prefers-reduced-motion` beachten.
8. **Prüfen**: Mit dem Skill `heuristic-evaluation` gegen Nielsens 10 Heuristiken prüfen, mit `web-design-guidelines` gegen die Web Interface Guidelines.

## Typische Fehler vermeiden
- Mehrere gleichwertige Call-to-Actions pro Screen.
- Platzhalter statt Labels, graue Schrift mit zu wenig Kontrast.
- Fehlende Leer-, Lade- und Fehlerzustände.
- Layout, das nur auf Desktop getestet wurde.
- Dekoration ohne Funktion (Animationen, Verläufe), die vom Inhalt ablenkt.

## Ergebnis
Liefere kurz: Zielgruppe und Ziel, Flow, Design-Tokens (Farben, Typo, Abstände), Komponentenliste, offene Fragen.
