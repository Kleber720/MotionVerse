# MotionVerse

![JavaScript](https://img.shields.io/badge/JavaScript-B99000?style=flat-square&logo=javascript&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![MediaPipe](https://img.shields.io/badge/MediaPipe-00897B?style=flat-square)

**Uma aventura 2D que conecta jogos e interação por gestos.** Projeto desenvolvido em turma no Senac Santana; este repositório é um fork de [CesarZanelatto/MotionVerse](https://github.com/CesarZanelatto/MotionVerse).

## O que você encontra

- Jogo em JavaScript com personagens, cenários, inventário e fases.
- Rastreamento de mãos com MediaPipe e integração com a câmera.
- Editor de fases com salvamento de arquivos pelo servidor Node.js.
- Site de apresentação, cadastro, ranking e páginas da equipe.
- Recursos de leitura por voz na página de apresentação.

## Executar localmente

Com Node.js e npm instalados:

```sh
git clone https://github.com/Kleber720/MotionVerse.git
cd MotionVerse
npm start
```

- **Apresentação:** http://localhost:3000/frontEnd/index.html
- **Jogo:** http://localhost:3000/jogo/Marcacao/inicio.html
- **Editor:** http://localhost:3000/jogo/Marcacao/editor.html

Para o rastreamento de mãos, use uma câmera e autorize seu uso no navegador. O MediaPipe carrega recursos externos e precisa de conexão com a internet.

## Organização

- `frontEnd/` — apresentação do projeto e páginas da equipe.
- `jogo/Marcacao/` — páginas do jogo e editor.
- `jogo/Script/` — lógica do jogo, editor e controle por gestos.
- `jogo/Data/` — dados das fases e registro de fases.
- `jogo/Imagem/` e `jogo/som/` — recursos visuais e sonoros.
- `server.js` — servidor local e operações de salvamento.

O editor salva `jogo/Data/<fase>.js`, `jogo/Marcacao/<fase>.html` e `jogo/Script/<script-da-fase>.js`, atualizando `jogo/Data/faseRegistry.js`.

## Competências praticadas

Programação de jogos, eventos e animação em JavaScript, integração com rastreamento de mãos, edição de fases e colaboração em equipe.


---

[← Portfólio de Kleber Amaro](https://github.com/Kleber720) · [Todos os repositórios](https://github.com/Kleber720?tab=repositories)
