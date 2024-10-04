# L3 - Jason e @krueguer - Busca de maior ocorrência

![_](cover.jpg)

## Motivação

* As pessoas perderam a fé na sexta feira 13. Diz Jason por trás da máscara.
* A vida tá ficando difícil mesmo. Fala Freddy Krueguer com o dedo enfiado numa nota de 50.
* O jeito é estudar pra concurso então.
* Mas pra onde a gente vai?
* Ouví falar de um canto que paga muito bem, não precisa de qualificação nenhuma e só tem gente assustadora.
* Qual cargo?
* 12.800 pra motorista, garçom e assessorista lá no tribunal de contas em Brasília.
* Boa, vamos lá.

Algum tempo depois...

* Duas vogais juntas é o que? Fala Jason.
* Ditongo!!! Grita Freddy.
* Ieie, pegadinha do malandro. Caiu na casca de banana: vogais juntas são um encontro vocálico, que pode ser ditongo ou hiato, dependendo se estão ou não na mesma sílaba.

## Ação

Faça um programa que dada uma string retorne uma linha contendo o subtexto com a maior quantidade de vogais juntas.

### Entrada

* 1a linha: a quantidade de casos de teste(1 a 50). Uma linha por caso de teste contendo uma frase de até 50 caracteres, apenas com minuscula.

### Saida

* Para cada de teste retorne uma linha contendo o subtexto com a maior quantidade de vogais juntas. Se existir empate, retorne o que aparece primeiro no texto.

## Exemplos

``` py
#INPUT
1
aeb
#OUTPUT
ae
#END
```

```py
#INPUT
1
aebeiocdu
#OUTPUT
eio
#END
```

```py
#INPUT
2
abdeiuofaoi
xaeioux
#OUTPUT
eiuo
aeiou
#END
```

```py
#INPUT
3
aebaibaobaub
baeoxuoiazzz
oxau
#OUTPUT
ae
uoia
au
#END
```
