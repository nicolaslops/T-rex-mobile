# T-REX-MOBILE

## Sobre o Projeto

Este projeto consiste em uma adaptação interativa e responsiva do clássico jogo do dinossauro (T-Rex Game), desenvolvida especificamente com foco na experiência de dispositivos móveis. A aplicação utiliza HTML, CSS e a biblioteca **p5.js** para criar uma jogabilidade fluida diretamente nos navegadores de smartphones e tablets, contando com sistemas de toque, animações dinâmicas e efeitos sonoros em tempo real.

A interface foi projetada para se ajustar perfeitamente a telas menores, utilizando o JavaScript para gerenciar os eventos de toque (touch) para o pulo do personagem, além de controlar a física do jogo, a geração infinita de obstáculos e o estado de Game Over.

---

## Funcionalidades

* Controle do personagem (T-Rex) otimizado para telas sensíveis ao toque (Mobile Touch Events).
* Layout e canvas totalmente responsivos, adaptando-se a diferentes resoluções e orientações de tela.
* Geração dinâmica e aleatória de múltiplos tipos de obstáculos e elementos de cenário.
* Sistema de colisão preciso entre o personagem e os obstáculos utilizando `p5.play`.
* Efeitos sonoros integrados para ações específicas (pular, checkpoint e colisão) via `p5.sound`.
* Tela de Game Over com botão de reinicialização (Restart) de fácil interação em dispositivos móveis.

---

## Tecnologias Utilizadas

* **HTML5**
* **CSS3**
* **p5.js** (e extensões: p5.dom, p5.play, p5.sound)

---

## Objetivo

O principal objetivo deste projeto é estender a lógica de desenvolvimento de jogos web com p5.js para o ambiente mobile. O foco está na aplicação de técnicas de design responsivo, otimização de performance para navegadores móveis e substituição dos eventos de teclado por manipuladores de eventos de toque em telas digitais.

---

## Aprendizados

Durante o desenvolvimento deste projeto, foram aplicados conceitos como:

* Mapeamento e tratamento de eventos de toque (`touches[]` ou `touchStarted`) na biblioteca p5.js.
* Ajuste dinâmico do tamanho do canvas do jogo com base nas dimensões da janela do dispositivo (`windowWidth` e `windowHeight`).
* Técnicas de otimização de renderização e carregamento assíncrono (`preload`) de assets para melhor performance em hardware mobile.
* Manipulação e controle de áudio digital adaptado para as restrições de reprodução de som em navegadores móveis.
* Ajustes de CSS para desabilitar comportamentos indesejados em dispositivos móveis (como zoom ao duplo toque ou rolagem acidental da página).

---

## Como Executar

1. Clone este repositório:
```bash
git clone [https://github.com/seu-usuario/T-REX-MOBILE.git](https://github.com/seu-usuario/T-REX-MOBILE.git)
```

2. Acesse a pasta do projeto:

```bash
cd T-REX-MOBILE
```

3. Abra o arquivo index.html em seu navegador ou simule um dispositivo móvel utilizando o Modo de Inspeção (F12) do seu navegador de preferência.

--- 

## Estrutura do Projeto

```text
T-REX-MOBILE/
│
├── assets/
│   ├── img/
│   │   ├── cloud.png
│   │   ├── gameOver.png
│   │   ├── ground1.png
│   │   ├── ground2.png
│   │   ├── obstacle1.png
│   │   ├── obstacle2.png
│   │   ├── obstacle3.png
│   │   ├── obstacle4.png
│   │   ├── obstacle5.png
│   │   ├── obstacle6.png
│   │   ├── restart.png
│   │   ├── trex_collided.png
│   │   ├── trex1.png
│   │   ├── trex3.png
│   │   └── trex4.png
│   └── mp3/
│       ├── checkPoint.mp3
│       ├── die.mp3
│       └── jump.mp3
│
├── scripts/
│   ├── p5.dom.min.js
│   ├── p5.js
│   ├── p5.play.js
│   ├── p5.sound.min.js
│   └── sketch.js
│
├── style/
│   └── style.css
│
├── index.html
└── README.md
```
---

## Licença
Este projeto foi desenvolvido exclusivamente para fins educacionais e de aprendizado.

Desenvolvido como prática de desenvolvimento web focado em dispositivos móveis, recriando o clássico T-Rex Game com controles de toque usando a biblioteca p5.js.
