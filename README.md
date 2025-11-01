# 🎮 Flappy Tetris

Ein innovatives Tetris-Spiel mit Flappy Bird Mechaniken – steuere fallende Tetris-Steine durch Gravitation und lass sie wie Vögel fliegen! 🐦

## 🕹️ [Jetzt spielen!](https://grzlprmpf.github.io/flappy-tetris)

---

## ✨ Features

- **Physik-basierte Steuerung**: Steine fallen mit echter Gravitation
- **Flappy-Mechanik**: Drücke Rotations-Taste für einen Aufwärtsschub
- **Momentum-Steuerung**: Steine bewegen sich mit Trägheit – wie beim Jonglieren!
- **Flügel-Animation**: Jeder Stein hat kleine Flügel, die beim Fliegen flattern
- **Ghost-Preview**: Siehst genau, wo dein Stein landen wird
- **Dark/Light Mode**: Wähle zwischen dunklem und hellem Theme 🌙☀️
- **Responsive Design**: Spielt sich perfekt auf Desktop und Tablet

## 🎯 Spielmechanik

Anders als beim klassischen Tetris fallen die Steine hier **nicht automatisch** – du musst sie aktiv in der Luft halten!

- Steine starten außerhalb des Spielfelds und fliegen herein
- Ohne Eingabe fallen sie durch Gravitation nach unten
- Rotiere, um einen Schub nach oben zu bekommen
- Bewege horizontal mit Momentum-Steuerung
- Sobald ein Stein komplett im Feld ist, kann er nicht mehr nach oben herausfliegen

## 🎮 Steuerung

| Taste | Aktion |
|-------|--------|
| **← →** | Horizontal bewegen (mit Momentum) |
| **↑** | Drehen + Aufwärtsschub |
| **P** | Pause |
| **Backspace** | Neues Spiel |

## 🛠️ Technologien

- **HTML5 Canvas** – für flüssiges Rendering
- **Vanilla JavaScript** – keine Frameworks, pure Performance
- **CSS3 Variables** – für dynamisches Theming
- **Physics Engine** – custom Gravitations- und Kollisionssystem

## 📊 Spielsystem

- **Score**: Punkte für gelöschte Zeilen
  - 1 Zeile = 100 Punkte × Level
  - 2 Zeilen = 300 Punkte × Level  
  - 3 Zeilen = 500 Punkte × Level
  - 4 Zeilen = 800 Punkte × Level (Tetris!)

- **Level**: Steigt alle 10 gelöschten Zeilen

## 🎨 Features im Detail

### Physik-System
- Realistische Gravitation (0.25 px/frame²)
- Maximale Fall-Geschwindigkeit begrenzt
- Reibung für horizontale Bewegung
- Wall-Kick-Rotation an den Rändern

### Visuals
- Animierte Flügel, die beim Fliegen schneller schlagen
- Transparente Landezone-Vorschau
- Smooth Transitions zwischen Themes
- Grid-Overlay für bessere Orientierung

## 🚀 Lokal spielen

```bash
# Repository klonen
git clone https://github.com/grzlprmpf/flappy-tetris.git

# In Verzeichnis wechseln
cd flappy-tetris

# Mit einem lokalen Server öffnen, z.B.:
python -m http.server 8000
# oder
npx serve
```

Dann öffne `http://localhost:8000` im Browser!

Oder einfach `index.html` direkt im Browser öffnen – keine Installation nötig! 🎉

## 📝 Lizenz

MIT License – feel free to fork und eigene Versionen erstellen!

## 🤝 Contributing

Ideen und Pull Requests sind willkommen! Einige Ideen für zukünftige Features:

- [ ] Sound Effects & Musik
- [ ] Highscore-System mit localStorage
- [ ] Power-Ups und Special Blocks
- [ ] Multiplayer-Modus
- [ ] Mobile Touch-Steuerung
- [ ] Verschiedene Schwierigkeitsgrade

---

⭐ **Gefällt dir das Spiel?** Gib dem Projekt einen Stern auf GitHub!

🐛 **Bug gefunden?** Erstelle ein [Issue](https://github.com/grzlprmpf/flappy-tetris/issues)

Made with 💙 and lots of ☕
