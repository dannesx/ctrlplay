---
marp: true
theme: neubrutalism
---

<!-- _class: dark cover -->

# Listas

---

<!-- _class: center -->

# Conceito

Uma lista é uma estrutura de dados que armazena uma **coleção de elementos**. Esses elementos são geralmente do mesmo tipo e são acessíveis por meio de índices. Esta é uma forma eficiente de armazenar valores parecidos em apenas uma variável

---

# Quando usar listas?

Vamos imaginar que estamos fazendo um programa para uma feira, e queremos cadastrar as frutas que o seu Zé está vendendo. Sem listas, este código ficaria parecido com isso: 

```python
fruta = "Maçã"
outraFruta = "Banana"
frutaAmarela = "Abacaxi"
frutaGrande = "Melancia"
frutaPequena = "Uva"
fruta2 = "Framboesa"
```

Percebeu que precisamos criar uma variável para cada fruta? Além de termos várias variáveis, o que nos garante que a `frutaAmarela` é o abacaxi, e não a banana ou melão?

---

# Utilizando listas

Veja agora o exemplo anterior, porém utilizando uma lista ao invés de variáveis simples:

```python
frutas = ["Maçã", "Banana", "Abacaxi", "Melancia", "Uva", "Framboesa", "Melão", "Abacate"]
```
Desta vez temos apenas uma variável que armazena uma coleção de itens do tipo `String`, deixando nosso código muito mais organizado e eficiente.

---

# Acessando itens de uma lista

Ainda no mesmo exemplo, se quisermos saber qual item está na primeira posição, nós só precisamos escrever o nome de nossa variável junto de colchetes `[]` e seu índice. Veja:

```python
# Armazenando o valor em uma variável temporária
frutaEscolhida = frutas[0]

# Imprimindo o valor da variável frutaEscolhida
print(frutaEscolhida)
>>> "Maçã"
```

**OBS: Os índices das listas começam com zero!** Sendo assim, o item com índice 0 é o primeiro elemento, com índice 1 é o segundo e assim por diante

---

# Percorrendo uma lista

E se quisermos mostrar todos os itens dentro de uma lista? Para isso utilizamos os **laços de repetição**, que veremos nos próximos slides. Veja um exemplo:

```python
# Para cada 'item' dentro da lista 'frutas' ...
for item in frutas:
  print(item) # ... imprima no terminal
```

Assim, o código conseguirá acessar item por item, dentro da lista `frutas`, na ordem em que estão dispostos. Damos um nome para essa ação de repetir para cada valor, chamado **iteração**

---

<!-- _class: dark center -->

# Na prática

Como você acessaria apenas o último elemento de uma lista, não importando o seu tamanho e seus valores?