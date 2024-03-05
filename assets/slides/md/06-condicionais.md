---
marp: true
theme: neubrutalism
---

<!-- _class: dark cover -->

# Estruturas Condicionais

---

<!-- _class: center -->

# Conceito

As estruturas condicionais são usadas para **controlar o fluxo do programa** com base em condições específicas. Elas permitem que o código execute diferentes blocos de código dependendo se uma condição é verdadeira ou falsa.

---

<!-- _class: center -->

# O que é uma condição ?

Uma condição é uma **expressão** que pode ser verdadeira ou falsa (`boolean`).

Ex: `Hoje está frio`, `Sou aluno Ctrl+Play`, `5 é maior que 10` etc.

---

# IF

A palavra `if` quer dizer **se** em inglês. Se uma condição for **verdadeira**, o bloco de código `if` será executado

```python
idade = 18

if idade >= 18:
    print("Você é maior de idade")
```

---

# ELSE

A palavra `else` quer dizer **senão** em inglês. Se uma condição for **verdadeira**, o bloco de código `if` será executado, mas se for **falsa**, o bloco de código `else` será executado em seu lugar

```python
nota = 7.5

if nota >= 6:
    print("Parabéns, você passou!")
else:
    print("Oh não, você reprovou")
```

---

# ELSE IF (ELIF)

`else if` significa **senão se** em inglês. Se você tiver mais de uma condição, precisará utilizar o `else if`, ou `elif` na linguagem Python. Veja o exemplo:

```python
temperatura = 25

if temperatura > 100:
    print("A água evaporou!")
elif temperatura < 0:
    print("A água congelou!")
else:
    print("A água está normal")
```
---

<!-- _class: dark center -->

# Na prática

Pense em pelo menos 3 aplicações práticas para o uso de _estruturas condicionais_ no nosso cotidiano