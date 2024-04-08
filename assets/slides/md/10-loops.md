---
marp: true
theme: neubrutalism
---

<!-- _class: dark cover -->

# Loops

---

<!-- _class: center -->

# Conceito

**Loops** ou **laços de repetição** são estruturas que permitem executar um bloco de código várias vezes. Os principais tipos são o laço `for`, que é uma **iteração**, e o laço `while`, que repete até que uma condição mude. Desse jeito, simplificamos o código ao evitar repetições manuais

---

# Quando usar loops?

Vamos imaginar que estamos criando um programa que conta até 10 e mostra uma mensagem. Sem laços de repetição este código ficaria assim:

```python
print(1)
print(2)
print(3)
print(4)
print(5)
print(6)
print(7)
print(8)
print(9)
print(10)
print("Hello World!")
```

Até que fica fácil de ler, mas e se tivermos que contar até 1 mil, 10 mil, 1 milhão? 🤔

---

# Loop `for`

Este laço de repetição **itera** sobre um conjunto. Esta é uma repetição **definida**, pois sabemos quantas vezes irá repetir

```python
# Criando a lista cores
cores = ["amarela", "vermelha", "azul"]

# Para cada cor dentro da lista cores, repita...
for cor in cores:
  print("Eu gosto da cor", cor)

# Resultado
>>> "Eu gosto da cor amarela"
>>> "Eu gosto da cor vermelha"
>>> "Eu gosto da cor azul"
```

> Iteração significa repetir a mesma coisa várias vezes, passo a passo, até chegar no final de um conjunto de elementos

---

# Loop `while`

Este laço de repetição depende de uma **condição** para repetir. Enquanto a condição for verdadeira, o código irá repetir. Esta é uma repetição **indefinida**, pois não podemos afirmar com certeza quantas vezes irá repetir

```python
# Variável para armazenar o estado atual da chuva
estaChovendo = True

# Enquanto estiver chovendo, repita...
while estaChovendo:
  print("Utilizar o guarda-chuva")

  # Verificar se continua chovendo...
  estaChovendo = input("Continua chovendo?")
```

Enquanto a variável `estaChovendo` for verdadeira, o código repetirá. No momento em que se tornar falsa, o código irá parar de repetir.

> Você sabe quando vai parar de chover?

---

<!-- _class: dark center -->

# Na prática

Voltando no primeiro exemplo deste slide:

Como você contaria até 10 usando os laços de repetição `for` e `while`?