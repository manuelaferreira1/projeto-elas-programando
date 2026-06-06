# Projeto 08: Jogo da Topeira 

Este projeto foi desenvolvido dentro do projeto de extensão **Elas Programando**. Trata-se de uma versão mobile do clássico jogo "Whack-a-Mole", onde o objetivo do jogador é tocar na topeira que surge em posições aleatórias da tela antes que ela mude de lugar, acumulando o máximo de pontos possível.

## Demonstração do App
Como este vídeo é super leve e rápido, você pode assistir ao funcionamento do jogo diretamente no player abaixo:

<video src="./topeira_game.mp4" controls width="300px"></video>

---

## Funcionalidades
* **Movimentação Aleatória Automatizada:** A topeira altera sua posição na tela em intervalos de tempo definidos por um temporizador invisível.
* **Sistema de Pontuação Dinâmica:** O placar (`SCORE`) adiciona +1 ponto automaticamente a cada clique bem-sucedido sobre o personagem.
* **Botão de Reinicialização (Reset):** Função para zerar o placar atual e reiniciar a partida do zero a qualquer momento.

---

## Conceitos de Programação Aprendidos
* **Componente de Animação (Canvas e ImageSprite):** Uso do cenário gráfico (`Canvas`) para delimitar a área do jogo e controle do personagem (`ImageSprite`) para manipulação de imagens que se movem.
* **Coordenadas Cartesianas ($X$ e $Y$):** Entendimento prático de como posicionar elementos na tela do telemóvel alterando aleatoriamente as propriedades de largura ($X$) e altura ($Y$) dentro dos limites do Canvas.
* **Temporizadores (`Clock`):** Utilização do sensor de relógio para disparar eventos cíclicos repetidas vezes (fazendo a topeira "pular" de tempos em tempos).
* **Variáveis Globais e Acumuladores:** Criação de variáveis para armazenar a pontuação do jogador e fazer o incremento lógico matemático (`Score = Score + 1`).
