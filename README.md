# ✊✋✌️ Rock Paper Scissors (Pedra, Papel e Tesoura)

Um jogo interativo e moderno de **Pedra, Papel e Tesoura** desenvolvido com **HTML5**, **CSS3** e **JavaScript vanilla**, apresentando animações visuais com emojis, sistema de pontuação persistente e recursos avançados como modo automático e atalhos de teclado.

---

## 🚀 Funcionalidades

* **Modo de Jogo Interativo:** Escolha entre Pedra, Papel ou Tesoura clicando nos botões estilizados com ícones.
* **Placar Persistente (`localStorage`):** O jogo acompanha e salva automaticamente suas vitórias, derrotas e empates no navegador, mantendo o histórico mesmo após atualizar a página.
* **Modo Automático ("Auto Play"):** Recurso de jogo automatizado onde o computador joga contra ele mesmo a cada intervalo de tempo.
* **Atalhos de Teclado:** 
  * Tecla `r`: Escolhe Pedra.
  * Tecla `p`: Escolhe Papel.
  * Tecla `s`: Escolhe Tesoura.
  * Tecla `a`: Ativa/Desativa o modo Auto Play.
  * Tecla `Backspace`: Reseta o placar (com confirmação na tela).
* **Confirmação de Reset:** Sistema de segurança com botões de confirmação (Sim/Não) para evitar que o placar seja zerado acidentalmente.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura da interface, botões de jogada e elementos de exibição de resultado.
* **CSS3:** Estilização visual em tema escuro, alinhamento flexbox e design customizado dos botões e ícones.
* **JavaScript:** Lógica de escolha aleatória do computador, manipulação do DOM, eventos de clique/teclado, gerenciamento de intervalos e armazenamento local (`localStorage`).

---

## 📂 Estrutura de Pastas

```text
Rock-Paper-Scissors/
│
├── rock-paper-scissors.html    # Página principal do jogo
│
├── styles/
│   └── rock-paper-scissors.css # Estilização e layout visual
│
├── scripts/
│   └── rock-paper-scissors.js  # Lógica de pontuação, eventos e regras do jogo
│
└── images/
    ├── rock-emoji.png          # Ícone de pedra
    ├── paper-emoji.png         # Ícone de papel
    └── scissors-emoji.png      # Ícone de tesoura
