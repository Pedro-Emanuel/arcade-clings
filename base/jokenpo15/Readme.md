# L3 - @jokenpo15

## Motivação

O jokenpo é emocionante. Normalmente, as crianças aprendem a jogar jokenpo antes de aprenderem par ou ímpar pois é mais fácil aprender que pedra quebra tesoura do que somar números e descobrir se par ou ímpar. Existem várias variações. Uma interessante com 15 níveis é a seguir. Cada elemento ganha de 7 elementos a sua frente e perder de 7 elementos que estão antes dele.

![_](cover.jpg)

Vamos fazer do Human o número 0, Tree será 1 e assim sucessivamente. O número 3 (sponje) ganha de (4, 5, 6, 7, 8, 9, 10) e perde de (11, 12, 13, 14, 0, 1, 2).

### Entrada

- Dois números, A, B um por linha indicando as escolhas do primeiro e do segundo jogador.

## Saída

- "Empate", "Jogador 1", "Jogador 2"

## Restrições

- 0 ≤ A, B, C ≤ 14

## Exemplos

``` py
#INPUT
1
0
#OUTPUT
Jogador 2
#END
#INPUT
5
9
#OUTPUT
Jogador 1
#END
```

```py
#INPUT
0
0
#OUTPUT
Empate
#END
```
