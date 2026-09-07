# 🕵️ MacroCrime: Dossiê Metrópole

Um jogo web de investigação criminal inspirado em *MicroMacro: Crime City*. O jogador assume o papel de um detetive, analisando mapas de uma cidade caótica para desvendar crimes a partir de pequenos detalhes visuais e de comportamento na multidão.

O projeto dispensa menus tradicionais em favor de uma interface imersiva baseada em objetos de escritório.

## 🎮 Como Jogar
1. Leia a pista na pasta de arquivo lateral.
2. Explore o mapa dando zoom e rastreando suspeitos na multidão.
3. Clique no local exato onde o evento descrito está acontecendo para encerrar o caso.

## ✨ Funcionalidades Principais
* **Seleção Dinâmica:** Os casos são sorteados e carregados aleatoriamente a cada partida.
* **Interface:** UI construída para simular a mesa de um detetive.
* **Coordenadas:** Sistema de clique que calcula porcentagens relativas de `X` e `Y`, com margem de tolerância ajustável para validar se o jogador encontrou a pista correta.
* **Design Responsivo:** Lógica estruturada para manter as coordenadas precisas independentemente do tamanho da tela do jogador.

## 🛠️ Tecnologias Utilizadas
* **HTML5:** Estrutura da interface de jogo.
* **CSS3:** Animações nativas, flexbox e estilização.
* **JavaScript (Vanilla):** Lógica central do ciclo de jogo, controle de arrays de casos e cálculos de área clicável.

## 🚀 Como rodar o código localmente
1. Clone este repositório: `git clone https://github.com/luizr-lima/macro-crime.git`
2. Abra a pasta raiz do projeto.
3. Abra o arquivo `index.html` em um navegador web. Nenhum servidor local ou instalação de pacotes é necessário.
