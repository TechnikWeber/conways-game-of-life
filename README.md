# Conway's Game of Life

Eine interaktive Browser-Umsetzung von John Conways berühmtem zellulären Automaten – komplett in HTML, CSS und JavaScript.

## 🎮 Live-Demo

👉 **[Hier ausprobieren](https://technikweber.github.io/Conways-game-of-life/)**

Einfach den Link öffnen – das Spiel läuft direkt im Browser, keine Installation nötig.

## Was ist Game of Life?

Game of Life ist kein Spiel im klassischen Sinn, sondern ein zellulärer Automat: ein Gitter aus Zellen, die entweder *lebendig* oder *tot* sind. Aus wenigen einfachen Regeln entstehen erstaunlich komplexe Muster – Gleiter, Oszillatoren, ganze "Maschinen", die sich selbst reproduzieren.

## Die Regeln

In jeder Generation wird für jede Zelle anhand ihrer acht Nachbarn entschieden, was als Nächstes passiert:

1. **Unterbevölkerung:** Eine lebende Zelle mit weniger als 2 lebenden Nachbarn stirbt.
2. **Überleben:** Eine lebende Zelle mit 2 oder 3 lebenden Nachbarn bleibt am Leben.
3. **Überbevölkerung:** Eine lebende Zelle mit mehr als 3 lebenden Nachbarn stirbt.
4. **Fortpflanzung:** Eine tote Zelle mit genau 3 lebenden Nachbarn wird lebendig.

## Funktionen

- Zellen per Klick setzen und löschen
- Simulation starten, pausieren und zurücksetzen
- Anpassbare Geschwindigkeit
- *(weitere Features hier ergänzen)*

## Bedienung

- **Linksklick** auf eine Zelle, um sie zu (de)aktivieren
- **Start/Pause** steuert die Simulation
- **Reset** leert das Gitter

## Lokal ausführen

Da es sich um reines Frontend handelt, reicht es, die Datei direkt zu öffnen:

```bash
git clone https://github.com/technikweber/Conways-game-of-life.git
cd Conways-game-of-life
```

Dann einfach die `index.html` im Browser öffnen.

## Technik

- HTML5 Canvas *(falls verwendet)*
- Vanilla JavaScript
- CSS

## Lizenz

[MIT](LICENSE).
