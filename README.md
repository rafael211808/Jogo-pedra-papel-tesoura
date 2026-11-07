# ✊✋✌️ Rock Paper Scissors (Pedra, Papel e Tesoura)

Um jogo interativo e moderno de **Pedra, Papel e Tesoura** desenvolvido com **HTML5**, **CSS3** e **JavaScript vanilla**, apresentando animações visuais com emojis, sistema de pontuação persistente e recursos avançados como modo automático e atalhos de teclado.

---

## 🚀 Funcionalidades

* **Modo de Jogo Interativo:** Escolha entre Pedra, Papel ou Tesoura clicando nos botões estilizados com ícones[cite: 15, 16].
* **Placar Persistente (`localStorage`):** O jogo acompanha e salva automaticamente suas vitórias, derrotas e empates no navegador, mantendo o histórico mesmo após atualizar a página[cite: 16].
* **Modo Automático ("Auto Play"):** Recurso de jogo automatizado onde o computador joga contra ele mesmo a cada intervalo de tempo[cite: 16].
* **Atalhos de Teclado:** 
  * Tecla `r`: Escolhe Pedra[cite: 16]
  * Tecla `p`: Escolhe Papel[cite: 16]
  * Tecla `s`: Escolhe Tesoura[cite: 16]
  * Tecla `a`: Ativa/Desativa o modo Auto Play[cite: 16]
  * Tecla `Backspace`: Reseta o placar (com confirmação na tela)[cite: 16]
* **Confirmação de Reset:** Sistema de segurança com botões de confirmação (Sim/Não) para evitar que o placar seja zerado acidentalmente[cite: 16].

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura da interface, botões de jogada e elementos de exibição de resultado[cite: 15].
* **CSS3:** Estilização visual em tema escuro, alinhamento flexbox e design customizado dos botões e ícones[cite: 17].
* **JavaScript:** Lógica de escolha aleatória do computador, manipulação do DOM, eventos de clique/teclado, gerenciamento de intervalos e armazenamento local (`localStorage`)[cite: 16].

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
