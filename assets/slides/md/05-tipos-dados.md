---
marp: true
theme: neubrutalism
---

<!-- _class: dark cover -->

# Tipos de Dados

---

<!-- _class: center -->

# Conceito

Dados são a matéria-prima da informação, o conhecimento bruto que quando trabalhados geram informação. Os dados possuem diversos tipos: **Kleber** é um texto, **42** é um número e **verdadeiro** é um valor lógico. 

Sendo assim, trabalhamos com vários tipos diferentes quando estamos programando. Vamos explorar os principais tipos de dados:
`numéricos`, `textuais` e `lógicos`

---

# Tipos Numéricos

Na programação em geral, os números podem ser divididos em duas categorias: os números **inteiros** e os números **reais** (com vírgula). Estes sãos os tipos `int` e `float` da maioria das linguagens de programação

- **int** vem da palavra **integer**, que é inteiro em inglês. Exemplo: `0`, `4`, `9`, `16`, `458`, `-56`, `-8`
- **float** quer dizer flutuante, ou melhor, ponto flutuante (é assim que chamamos os números reais em inglês). Exemplo: `0.5`, `3.14`, `7.5`, `-9.98`

**Observação:** Os números reais são escritos com ponto final `.` ao invés da vírgula `,` como estamos acostumados. Este detalhe pode gerar bugs em nosso código

---

# Tipos Textuais

Normalmente os textos são divididos em duas categorias na programação: os **caracteres** e as **cadeias de caracteres**. Estes são os tipos `char` e `String` (ou `str`) da maioria das linguages de programação

- **char** são os caracteres individuais, definidos com áspas simples. Exemplo: `'a'`, `'B'`, `'c'`, `'#'`, `'$'`, `'7'`
- **String (ou str)** são um conjunto de caracteres (frases, palavras etc.), definidos com áspas duplas. Exemplo: `"Olá, mundo!"`, `"escada"`, `"Eu amo programar!"`, `"58909"`

**Observação:** Quando um caractere está entre áspas (simples ou duplas) ele se torna um **texto**

---

# Tipos Lógicos

Os tipos lógicos normalmente se resumem em cenários opostos: verdadeiro ou falso, sim e não, alto e baixo etc. O principal tipo lógico presente nas linguagens de programação é o tipo `boolean` (ou `bool`)

- **boolean (ou bool)** representa um estado com apenas duas possibilidades: `true` (verdadeiro) ou `false` (falso). Exemplo: `estaChovendo = false`, `gosta_de_tomate = true`, `ferias = false`

**Observação:** Os tipos lógicos também podem ser representados no sistema binário como `0` sendo falso e `1` sendo verdadeiro

---

# Na prática

<!-- _class: dark center -->

Você está fazendo o cadastro dos alunos de uma escola. Quais tipos de informações encontraremos em sua ficha?

---

# Exemplo

Veja abaixo algumas variáveis utilizando diversos tipos de dados diferentes, escrito na linguagem Python


```python
nome = "Renato"

sobrenome = "Silva Teixeira"

genero = 'M'

idade = 16

altura = 1.78 

filho_unico = True
```

Este exemplo mostra como os tipos de dados podem ser utilizados para criar a ficha de cadastro de uma pessoa.
