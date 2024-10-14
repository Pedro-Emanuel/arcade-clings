# @c007tiposdedados

Neste exercício, você vai trabalhar com os tipos de dados primitivos e seus modificadores em C.

## Contexto

Em C, os tipos de dados primitivos são os blocos de construção básicos que definem o tipo de valor que uma variável pode armazenar. Entre os principais tipos estão:

- **int**: Para armazenar números inteiros.
- **float**: Para armazenar números com ponto flutuante (decimais de menor precisão).
- **double**: Para armazenar números com ponto flutuante, mas com maior precisão.
- **char**: Para armazenar um único caractere.

Além desses tipos básicos, podemos utilizar modificadores que alteram o comportamento do tipo, tais como:

- **unsigned**: Indica que a variável só pode armazenar números positivos.
- **long**: Indica que a variável pode armazenar números maiores que os tipos padrão.

Por exemplo:

- `unsigned int`: Pode armazenar números inteiros não negativos maiores que o `int` padrão.
- `long int`: Pode armazenar números inteiros maiores que o `int` comum.

## Objetivos

- Declarar variáveis utilizando modificadores como `unsigned` e `long`.
- Imprimir os valores dessas variáveis utilizando os especificadores de formato adequados no `printf`.

## Testes

```py
>>>>>>>> INSERT
======== EXPECT
Idade: 25
Distância: 150000
Precisão: 0.0000025
<<<<<<<< FINISH
```

## Dicas

- Use %u para imprimir valores do tipo unsigned int.
- Use %ld para imprimir valores do tipo long int.
- Use %f ou %lf para imprimir valores do tipo double, dependendo da precisão desejada.
- Para double, você pode especificar o número de casas decimais que deseja exibir no printf, como %.7f.
