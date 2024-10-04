# L2 - @soldados em Posição

![_](https://raw.githubusercontent.com/qxcodefup/arcade/master/base/soldados/cover.jpg)

## Motivação

Os soldados se colocaram em formação no quartel. Na formação, eles formaram uma matriz 3x3.

Cada soldado tem uma numeração na sua farda, logo o Comandante querendo tripudiar de você, mandou você contar quantas vezes um soldado com numeração de fardamento menor está atrás de um maior.

## Ação

Faça um programa que conte quantos soldados com numeração de fardamento menor está atrás de um maior.

**Obs**: Você tem que conferir as numerações verticalmente.

### Entrada

* Uma matriz de tamanho qualquer contendo os valores que representam os soldados.
  * linha 1: nl e nc
  * linhas seguintes a matriz

Saída

* Quantas vezes foram encontrados.

## Exemplos

``` py
#INPUT
2 1
2
3
#OUTPUT
0
#END
```

```py
#INPUT
2 1
4
3
#OUTPUT
1
#END
```

```py
#INPUT
3 3
2 4 6
3 8 9
1 0 5
#OUTPUT
3
#END
```

```py
#INPUT
3 3
5 1 9
3 8 4
7 3 2
#OUTPUT
4
#END
```

```py
#INPUT
3 3
6 2 3
5 4 9
1 8 7
#OUTPUT
3
#END
```

```py
#INPUT
4 4
6 2 3 5
5 4 9 4
1 8 7 3
1 8 9 2
#OUTPUT
6
#END
```

```py
#INPUT
5 4
6 2 3 5
5 4 9 4
1 8 7 3
1 8 9 2
0 7 9 1
#OUTPUT
9
#END

```
