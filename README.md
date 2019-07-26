# CSS Grid Layout Crash Course (Traversy Media)

# Exemplo 1

![screenshot_1](https://github.com/guiemi-learning-center/tutorial-grid-layout-traversy/blob/master/media/example_1.png)

Nesse screenshot, o `grid-template-columns` está setado em `70% 30%`, ou seja, a 1ª coluna ocupa 70% do grid e a 2ª ocupa os outros 30%.

# Exemplo 2

![screenshot_2](https://github.com/guiemi-learning-center/tutorial-grid-layout-traversy/blob/master/media/example_2.png)

Neste screenshot, foi setada a função `repeat(3, 1fr);` no `grid-template-columns` , fazendo com que três colunas, cada uma com `1fr` de tamanho, alinhem-se.

A 3ª coluna tem a classe `.nested`. Nela, o `grid-template-columns` está setado para desenhar 3 colunas, através do `repeat(3, auto);`.

# Exemplo 3

![screenshot_3](https://github.com/guiemi-learning-center/tutorial-grid-layout-traversy/blob/master/media/example_3.png)

No exemplo 3, cada caixa tem seu tamanho e alinhamento definidos por intervalos de linhas, usando as sintaxes: `grid-column: x/y;`e `grid-row: x/y;`, sendo a barra ("/") um delimitador de intervalo.

# Bibliografia

CSS Grid Layout Crash Course: https://www.youtube.com/watch?v=jV8B24rSN5o

[![image-20190726124003605](/Users/guiemi/Library/Application Support/typora-user-images/image-20190726124003605.png)](https://www.youtube.com/watch?v=jV8B24rSN5o)