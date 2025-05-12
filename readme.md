# 🧠 Projetos Avaliativos – Programação Web I

Repositório contendo os projetos desenvolvidos durante o curso de **Programação Web I**, com foco em **JavaScript, DOM, eventos, manipulação de elementos HTML/CSS**, e lógica de programação sem uso de frameworks.

## 👥 Integrantes do Grupo

- Vitor Da Silva Harthmann
- Bruno Da rosa Soares
- Otavio Martins Da Rosa Neto

---

## 📁 Projeto 1: Controle de Luz – Simulador de Interruptor

### 📌 Descrição

Simulador de um interruptor digital. Ao clicar no botão, uma lâmpada virtual é ligada ou desligada. A imagem e o texto do botão são alterados dinamicamente.

### ✅ Funcionalidades

- [x] Alternar imagem da lâmpada (ligada/desligada)
- [x] Botão com texto dinâmico ("Ligar" / "Desligar")
- [x] Estilização básica com CSS

### 📸 Imagem/GIF

*(Adicione imagem ou gif aqui)*

### 🌟 Melhorias Futuras

- [ ] Fade-in/fade-out ao trocar imagens
- [x] Mudança do fundo da página
- [x] Contador de vezes que a luz foi ligada

---

## 📁 Projeto 2: Cofrinho Digital

### 📌 Descrição

Simulador de cofre onde o usuário pode inserir valores fictícios de moedas e acompanhar o total acumulado em tempo real.

### ✅ Funcionalidades

- [x] Botões para inserir R$0,10 / R$0,25 / R$0,50 / R$1,00
- [x] Atualização dinâmica do valor total
- [x] Botão "Esvaziar Cofre"
- [x] Formatação com `toFixed(2)` e `Intl.NumberFormat`

### 📸 Imagem/GIF

*(Adicione imagem ou gif aqui)*

### 🌟 Melhorias Futuras

- [x] Exibir a quantidade de cada tipo de moeda
- [ ] Armazenar valores com `localStorage`
- [x] Mostrar cofre visualmente “enchendo”

---

## 📁 Projeto 3: Pomodoro – Cronômetro de Estudo

### 📌 Descrição

Cronômetro baseado na técnica Pomodoro (25 minutos de foco + pausas). Ajuda a manter concentração nos estudos.

### ✅ Funcionalidades

- [x] Timer regressivo de 25:00 minutos
- [x] Botões: Iniciar, Pausar e Resetar
- [x] Atualização do tempo por segundo
- [x] Layout claro e objetivo

### 📸 Imagem/GIF

*(Adicione imagem ou gif aqui)*

### 🌟 Melhorias Futuras

- [x] Sons de alarme ao terminar o tempo
- [x] Modo escuro com botão toggle
- [ ] Permitir configuração do tempo de foco/pausa

---

## 📁 Projeto Coringa: Teclado Virtual Musical

### 📌 Descrição

Teclado musical virtual com 7 teclas (Dó a Si). Ao clicar com o mouse ou pressionar teclas físicas, um som é reproduzido e a tecla se destaca visualmente.

### ✅ Funcionalidades

- [x] 7 teclas musicais criadas com HTML e CSS
- [x] Reprodução de som ao clique ou tecla
- [x] Destaque visual da tecla pressionada
- [x] Sons `.mp3` ou `.wav`

### 📸 Imagem/GIF

*(Adicione imagem ou gif aqui)*

### 🌟 Melhorias Futuras

- [ ] Teclas com oitava adicional
- [x] Animações visuais
- [ ] Gravar e reproduzir sequência de notas
- [x] Modo escuro/claro

---

## 📂 Organização do Repositório

```bash
/
├── Mainpage/
│   └──index.html, style.css, script.js]
│      
├── economias/
│   └──img, sound, economia.html, style.css, script.js
│      │    └──tok.mp3
│      └──trouxa1.png, trouxa2.png, trouxa3.png, trouxa4.png
├── luz/
│   └──img, sound, luz.html, style.css, script.js
│      │    └──
│      └──lampMine.png, lampMineOn.png, plate.png, steve.png
├── pomodoro/
│   └──img, sound, pomodoro.html, style.css, script.js
│      │    └──
│      └──
├── coringa/
│   └──img, sound, coringa.html, style.css, script.js
│      │    └──
│      └──
└── README.md
