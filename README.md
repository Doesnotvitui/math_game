# Jogo de Matemática

O **Jogo de Matemática** é um projeto desenvolvido em Python que testa como habilidades matemáticas dos jogadores em operações básicas como adição, subtração, multiplicação e divisão. O jogo oferece dois modos: **Jogador único** (um jogador) e **Multijogador** (dois jogadores), com três nomes de dificuldade: Fácil, Médio e Difícil. O objetivo é resolver as operações corretamente no menor tempo possível para obter a maior pontuação.

## Funcionalidades

- **Modo Singleplayer**:
  - O jogador escolhe uma dificuldade (Fácil, Médio ou Difícil).
  - Resolver quatro óperas matemáticas (adição, subtração, multiplicação e divisão).
  - Recebe uma pontuação baseada na precisão e no tempo gasto.
  - O jogo informa se o tempo foi esgotado ou se todas como respostas foram erradas.

- **Modo Multijogador**:
  - Dois jogadores competem entre si.
  - Cada jogador resolver como mesmas operações matemáticas, mas com números gerados aleatoriamente.
  - O jogo compara as pontuações e declara o vencedor ou se houve empate.

- **Dificuldades**:
  - **Fácil**: Números entre -10 e 10.
  - **Médio**: Números entre -100 e 100.
  - **Difícil**: Números entre -1000 e 1000.

- **Pontuação**:
  - Uma pontuação é calculada com base no tempo gasto e na precisão das respostas.
  - Respostas corretas dentro de 5 segundos recebem uma pontuação máxima (10 pontos).
  - Respostas corretas após 5 segundos permanentes pontos proporcionais ao tempo gasto.
  - Respostas erradas ou tempo esgotado resultam em 0 pontos para a operação.
