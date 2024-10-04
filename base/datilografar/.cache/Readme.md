# L3 - Máquina de @datilografar Quebrada

![_](https://raw.githubusercontent.com/qxcodefup/arcade/master/base/datilografar/cover.jpg)

## Motivação

Durante anos, todos os contratos da Associação de Contratos da Modernolândia (ACM) foram datilografados em uma velha máquina de datilografia.

Recentemente Sr. Miranda, um dos contadores da ACM, percebeu que a máquina apresentava falha em um, e apenas um, dos dígitos numéricos.  
Mais especificamente, o dígito falho, quando datilografado, não é impresso na folha, como se a tecla correspondente não tivesse sido pressionada.  
Ele percebeu que isso poderia ter alterado os valores numéricos representados nos contratos e, preocupado com a contabilidade, quer saber, a partir dos valores originais negociados nos contratos, que ele mantinha em anotações manuscritas, quais os valores de fato representados nos contratos.

Por exemplo, se a máquina apresenta falha no dígito 5, o valor 1500 seria datilografado no contrato como 100, pois o 5 não seria impresso.  
Note que o Sr. Miranda quer saber o valor numérico representado no contrato, ou seja, nessa mesma máquina, o número 5000 corresponde ao valor numérico 0, e não 000 (como ele de fato aparece impresso).

Maratona de Programação da SBC 2010.  

## Ação

Faça um programa que dado um numero representando a tecla quebrada e o numero negociado inicialmente, imprima o numero representado no contrato.

### Entrada

* A primeira um digito entre 1 e 9 representando a tecla quebrada
* A segunda o número que foi negociado inicialmente, com até 100 dígitos.

## Saída

* Você deve imprimir uma linha contendo um único inteiro V, o valor numérico representado de fato no contrato.

## Exemplos

``` py
#INPUT
5
5000000
#OUTPUT
0
#END
```

```py
#INPUT
5
5004000
#OUTPUT
4000
#END
```

```py
#INPUT
3
123456
#OUTPUT
12456
#END
```

```py
#INPUT
9
99999999991999999
#OUTPUT
1
#END
```

```py
#INPUT
7
777
#OUTPUT
0
#END
```
