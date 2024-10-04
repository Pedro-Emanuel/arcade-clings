# L4 - A @porta Matemática

![_](cover.jpg)

## Motivação

Pedrinho precisa encontrar a sua sala onde terá sua aula de matemática.

Disseram para Pedrinho: A sala de matemática tem em sua porta um número de identificação, que misteriosamente se altera conforme as portas que estão próximas a ela, mas segue sempre uma regra: a porta matemática é aquela que possui dentre as outras, o número que gera a maior sequência da conjectura de collatz e que é um quadrado perfeito.

Pedrinho tem uma sequência de números de possíveis portas, ajude ele a identificar a porta matemática. Observações:

- Quadrado Perfeito: [Saiba
sobre](https://www.todamateria.com.br/quadrado-perfeito)
- Conjectura de Collatz: [Saiba
sobre](https://pt.wikipedia.org/wiki/Conjectura_de_Collatz)

## Ação

Faça um programa que dado um conjunto de portas retorne a porta matemática.

### Entrada

- 1 Inteiro N seguido de N Inteiros.

## Saída

- O número que representa a porta matemática.
- Ou \"a porta nao existe\", caso a porta não exista

### Exemplos

``` py
#INPUT
6
1 2 4 7 8 5
#OUTPUT
4
#END
```

```py
#INPUT
2
49 81
#OUTPUT
49
#END
```

```py
#INPUT
2
5 6
#OUTPUT
a porta nao existe
#END
```
