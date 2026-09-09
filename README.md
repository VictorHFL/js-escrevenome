# 🎨 js-escrevenome

Experimento criativo com p5.js: desenho interativo com o mouse.

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![p5.js](https://img.shields.io/badge/p5.js-ED225D.svg?style=for-the-badge&logo=p5.js&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## 📑 Sumário

- [Sobre](#sobre)
- [Como funciona](#como-funciona)
- [Tecnologias](#tecnologias)
- [Como executar](#como-executar)
- [Estrutura](#estrutura)
- [Licença](#licença)

## 📖 Sobre

Sketch que cria um canvas 600x600 e desenha retângulos vermelhos com contorno azul onde o mouse é pressionado. Projeto inicial para aprender `setup()` e `draw()` do p5.js.

## ⚙️ Como funciona

```javascript
function setup() {
  createCanvas(600, 600);
  background("white");
}

function draw() {
  stroke("blue");
  fill("red");
  if (mouseIsPressed) {
    rect(mouseX, mouseY, 20, 35);
  }
}
```

> [!NOTE]
> O p5.js é carregado via CDN no `index.html`. Sem internet o canvas não inicializa.

## 🛠️ Tecnologias

- JavaScript
- p5.js (CDN)
- HTML5 / CSS3

## 🚀 Como executar

```bash
git clone https://github.com/VictorHFL/js-escrevenome.git
cd js-escrevenome
# abra index.html no navegador e clique/arraste no canvas
```

## 📁 Estrutura

```text
js-escrevenome/
├── index.html
├── sketch.js
├── style.css
└── README.md
```

## 📄 Licença

Distribuído sob a licença MIT. Veja [LICENSE](LICENSE) para detalhes.

