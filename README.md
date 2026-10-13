# MotionVerse

![JavaScript](https://img.shields.io/badge/JavaScript-B99000?style=flat-square&logo=javascript&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![MediaPipe](https://img.shields.io/badge/MediaPipe-00897B?style=flat-square)

**A 2D adventure connecting games and gesture interaction.** A main portfolio project developed collaboratively at Senac Santana. This repository is a fork of [CesarZanelatto/MotionVerse](https://github.com/CesarZanelatto/MotionVerse).

## Features

- JavaScript game with characters, environments, inventory, and levels.
- Hand tracking with MediaPipe and camera integration.
- Level editor with file persistence through a Node.js server.
- Presentation website, registration, ranking, and team pages.
- Text-to-speech features on the presentation page.

## Run locally

With Node.js and npm installed:

```sh
git clone https://github.com/Kleber720/MotionVerse.git
cd MotionVerse
npm start
```

- **Presentation:** http://localhost:3000/frontEnd/index.html
- **Game:** http://localhost:3000/jogo/Marcacao/inicio.html
- **Editor:** http://localhost:3000/jogo/Marcacao/editor.html

Hand tracking requires a camera and camera permission in the browser. MediaPipe loads external resources and requires an internet connection.

## Repository structure

- `frontEnd/` — project presentation and team pages.
- `jogo/Marcacao/` — game pages and editor.
- `jogo/Script/` — game logic, editor, and gesture controls.
- `jogo/Data/` — level data and level registry.
- `jogo/Imagem/` and `jogo/som/` — visual and audio assets.
- `server.js` — local server and file-saving operations.

The editor saves `jogo/Data/<level>.js`, `jogo/Marcacao/<level>.html`, and `jogo/Script/<level-script>.js`, then updates `jogo/Data/faseRegistry.js`.

## Skills applied

Game programming, JavaScript events and animation, hand-tracking integration, level editing, and team collaboration.


---

[Kleber Amaro’s portfolio](https://github.com/Kleber720) · [All repositories](https://github.com/Kleber720?tab=repositories)
