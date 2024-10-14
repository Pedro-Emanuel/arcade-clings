# @c006constantes

Neste exercício, você aprenderá a usar duas maneiras principais de definir constantes em C: a diretiva do pré-processador `#define` e a palavra-chave `const`.

## Contexto

Em C, uma constante é um valor que não pode ser alterado durante a execução do programa. Elas são úteis quando você precisa garantir que um valor permaneça fixo em todo o código.

Existem duas formas principais de definir constantes:

- **`#define`**: Essa é uma diretiva do pré-processador que cria um "apelido" para um valor. Não possui tipo e é substituída diretamente pelo valor em tempo de compilação.
  
  Exemplo: `#define GRAVIDADE 9.8`

- **`const`**: Utiliza-se a palavra-chave `const` para criar uma constante com um tipo de dado específico. Diferente do `#define`, o `const` respeita os tipos de dados e a variável pode ser usada com verificações de tipo em tempo de compilação.

  Exemplo: `const float PI = 3.14159;`

## Objetivos

- Definir uma constante usando a diretiva `#define`.
- Definir uma constante usando a palavra-chave `const`.
- Imprimir os valores das constantes utilizando a função `printf`.

## Testes

```py
>>>>>>>> INSERT
======== EXPECT
Gravidade: 9.8
Valor de PI: 3.14159
<<<<<<<< FINISH
```

## Dicas

- #define não usa ponto e vírgula no final da linha.
- const segue a mesma sintaxe de declaração de variáveis, mas com a palavra-chave const no início.
- Lembre-se de que o printf pode usar %f para imprimir valores do tipo float e %lf para double.
