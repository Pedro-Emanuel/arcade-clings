# @c005variaveis

Neste exercício, você vai praticar a declaração e inicialização de variáveis em C.

## Contexto

Em C, para armazenar diferentes tipos de dados, utilizamos variáveis de diferentes tipos. Cada tipo de dado tem características próprias:

- int: utilizado para armazenar números inteiros, como 1, 2, 3, etc.
- float: usado para armazenar números decimais, como 1.75, 3.14, etc. É importante lembrar que ao imprimir um número decimal com printf, podemos controlar o número de casas decimais a serem exibidas utilizando %.2f (onde o 2 indica o número de casas após o ponto decimal).
- char: utilizado para armazenar um único caractere. Os caracteres em C são representados entre aspas simples, como 'A'.

As variáveis são fundamentais para armazenar e manipular dados durante a execução de um programa. Neste exercício, você vai declarar variáveis desses três tipos, inicializá-las com valores específicos e imprimir seus valores utilizando a função printf.

## Objetivos

- Declarar variáveis de três tipos diferentes: `int`, `float` e `char`.
- Inicializar essas variáveis com valores específicos.
- Imprimir os valores das variáveis usando a função `printf` e seus respectivos especificadores de formato.

## Testes

```py
>>>>>>>> INSERT
======== EXPECT
Idade: 20
Altura: 1.75
Letra inicial: A
<<<<<<<< FINISH
```

## Dicas

- Para declarar uma variável do tipo int: int idade = 20;.
- Para declarar uma variável do tipo float: float altura = 1.75;.
- Para declarar uma variável do tipo char: char letra_inicial = 'A';.
- Use printf("Idade: %d\n", idade); para imprimir a variável int.
- Use printf("Altura: %.2f\n", altura); para imprimir a variável float com duas casas decimais.
- Use printf("Letra inicial: %c\n", letra_inicial); para imprimir a variável char.
