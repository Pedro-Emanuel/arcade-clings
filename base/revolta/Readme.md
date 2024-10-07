# @revolta em Portugal

![_](cover.jpg)

## Motivação

Um grupo de portugueses planejava fazer uma revolução armada.

* Pois, pois Manoel, como pretendes tomar de assalto a praça?
* Ora, bolas Joaquim, estamos nós a chegar por lá. Vamos estar a retirar nossas espadas de nossas bainhas e espada-lo-emos todos!
* Ótima ideia. Vamos pois, ora bolas!

## Ação

Verifique se o grupo de Manoel ou de Joaquim conseguirá vencer essa batalha. Dado um vetor de números, os números ímpares representam os soldados e os números pares representam os rebeldes infiltrados. Some as forças e descubra qual dos dois grupos é mais forte.

### Entrada

* 1ª linha: tamanho do vetor (1 a 50)

* Próximas linhas: valor dos números, cada número entre 1 e 50.

## Saída

* "soldados" se os soldados(impares) somados são mais fortes.

* "rebeldes" se os rebeldes(pares) somados são mais fortes.

* "empate" se ambas forças são iguais e todos morrerão.

### Exemplos

``` py
>>>>>>>> INSERT
2
1
2
======== EXPECT
rebeldes
<<<<<<<< FINISH
```

```py
>>>>>>>> INSERT
3
1
2
1
======== EXPECT
empate
<<<<<<<< FINISH
```

```py
>>>>>>>> INSERT
2
2
3
======== EXPECT
soldados
<<<<<<<< FINISH
```

```py
>>>>>>>> INSERT
4
1
2
3
1
======== EXPECT
soldados
<<<<<<<< FINISH
```

```py
>>>>>>>> INSERT
5
1
2
3
1
4
======== EXPECT
rebeldes
<<<<<<<< FINISH
```
