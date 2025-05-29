## Pythonic Snake

## Resumo do Jogo

Bem-vindo ao "Pythonic Snake"! Neste jogo clássico de cobrinha com um toque especial, você controla a Python Amarela e compete contra a Python Azul, controlada por uma inteligência artificial. O objetivo é fazer a sua Python crescer o máximo possível comendo os alimentos que aparecem na tela, enquanto evita colisões. O jogo não tem fim; o desafio é alcançar o maior comprimento!

## Como Jogar

### Controles

*   **Python Amarela (Jogador):** Use as **teclas de seta** (Cima, Baixo, Esquerda, Direita) para direcionar a sua Python.
    *   A Python move-se continuamente na direção escolhida.
    *   Não é possível inverter a direção em 180 graus (por exemplo, ir para baixo quando se desloca para cima).

### Objetivo

*   Fazer a sua Python (Amarela) crescer o máximo possível.
*   Competir com a Python Azul (IA) para ver quem alcança o maior comprimento.

### Mecânicas do Jogo

1.  **Movimento:**
    *   Ambas as Pythons movem-se a uma velocidade constante.
    *   As Pythons podem girar 90 graus em relação à sua direção atual.
2.  **Alimento:**
    *   Pequenos quadrados vermelhos (alimentos) aparecem aleatoriamente na tela.
    *   Os alimentos desaparecem após 5 segundos se não forem comidos.
    *   Quando uma Python come um alimento, o seu comprimento aumenta em 5% do seu tamanho atual (adicionando pelo menos 1 novo segmento).
3.  **Colisões:**
    *   Se a cabeça de uma Python colidir com:
        *   Os limites da área de jogo (paredes).
        *   O seu próprio corpo.
        *   O corpo ou a cabeça da outra Python.
    *   ... a Python que colidiu **não perde vidas**, mas sim **retorna ao seu tamanho e posição inicial**. O jogo continua imediatamente.
4.  **Python Azul (IA):**
    *   A Python Azul move-se autonomamente.
    *   A IA tentará evitar colisões com as paredes, com o seu próprio corpo e com a Python Amarela.
    *   A IA também tentará apanhar alimentos quando for seguro fazê-lo.
5.  **Fim do Jogo:**
    *   O jogo **não tem um final definido**. É uma competição contínua para ver qual Python consegue o maior comprimento.
    *   Os comprimentos atuais de ambas as Pythons são sempre visíveis na tela.

### Dicas

*   Planeje os seus movimentos com antecedência, especialmente quando a sua Python estiver comprida.
*   Tente encurralar a Python Azul ou cortar-lhe o caminho para a comida (com cuidado para não colidir!).
*   Aproveite cada alimento para aumentar a sua vantagem!

Divirta-se a jogar Pythonic Snake!


Game gerado com [Gemini](https://gemini.google.com/share/17e038b317f4)
