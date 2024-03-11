---
marp: true
theme: neubrutalism
---

<!-- _class: dark cover -->

# Operadores Relacionais

---

<!-- _class: center -->

# Conceito

Operadores relacionais são usados para **comparar valores**, resultando em `verdadeiro` ou `falso`. Eles são utilizados principalmente em estruturas condicionais e loops

---

# Igualdade

O operador de igualdade é o `==`.
Quando usado, comparamos se um elemento é **igual** ao outro

```python
# Comparando números inteiros
3 == 4 : False

# Comparando números reais
8.9 == 8.9 : True

# Comparando strings
"Oi" == "Tudo bem?" : False

# Valores de tipos diferentes não são iguais
3 == "3" : False
```

---

# Desigualdade

O operador de desigualdade é o `!=`
Quando usado, comparamos se um elemento é **desigual** ao outro

```python
# Comparando números inteiros
3 != 4 : True

# Comparando números reais
8.9 != 8.9 : False

# Comparando strings
"Oi" != "Tudo bem?" : True

# Valores de tipos diferentes não são iguais
3 != "3" : True
```

---

# Maiores

Os operadores maiores são `>` _(maior)_ e `>=` _(maior ou igual)_
Quando usado, comparamos se um elemento é **maior** que outro.

```python
# Quando A é maior que B
7 > 4  : True
7 >= 4 : True

# Quando B é maior que A
9 > 12  : False
9 >= 12 : False

# Quando A é igual a B
10 > 10  : False
10 >= 10 : True
```

---

# Menores

Os operadores menores são `<` _(menor)_ e `<=` _(menor ou igual)_
Quando usado, comparamos se um elemento é **menor** que outro.

```python
# Quando A é maior que B
7 < 4  : False
7 <= 4 : False

# Quando B é maior que A
9 < 12  : True
9 <= 12 : True

# Quando A é igual a B
10 < 10  : False
10 <= 10 : True
```

---

<!-- _class: dark center -->

# Na prática

Explique a diferença dos seguintes pares de operadores:

`== e !=`, `> e >=`, `< e <=`
