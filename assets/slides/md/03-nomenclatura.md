---
marp: true
theme: neubrutalism
---

<!-- _class: dark cover -->

# Nomeando Variáveis

---

# Conceito

As chamadas **convenções de nomenclatura** são regras utilizadas quando precisamos nomear variáveis em nosso código. Isso acontece pois estes nomes:

- Não podem começar com um número.
- Não podem ter espaços `" "`.
- Não podem ter acentuações
- Não podem ser uma palavra reservada da linguagem.

Pensando nisso, programadores de todo o mundo entraram em um concenso: uma forma de escrever nomes padronizados. 

Elas são importantes para que o código seja mais legível e fácil de entender, tanto para quem o escreveu quanto para quem o lê.

---

<!-- _class: center -->

# Camel Case

O **camel case**, ou **caso do camelo** tem esse nome pois o formato das palavras lembra um camelo: sua cabeça é pequena e suas corcovas são grandes. Observe o exemplo `"Era uma vez um gato xadrez"`.

### **eraUmaVezUmGatoXadrez**

A primeira letra da primeira palavra será sempre **minúscula**.
Após a primeira palavra, toda próxima palavra terá a primeira letra **maiúscula**. O **camel case** é o caso de nomenclatura mais comumente usado em linguagens de programação.

---

<!-- _class: center -->

# Snake Case

Assim como o camel case, **snake case** ou **caso da cobra** tem esse nome pois o formato das palavras lembram uma cobra. Observe o mesmo exemplo, mas agora escrito em **snake case**

### **era_uma_vez_um_gato_xadrez**

Todas as palavras são em minúsculo, e os espaços são substituídos pelo caractere `"_"`. Ainda é possível encontrarmos casos com dois traços, ficando desse jeito: `"era__uma__vez__um__gato__xadrez"`. O **snake case** é uma alternativa ao camel case que também é comumente usado em linguagens de programação.

---

<!-- _class: center -->

# Kebab Case

**Kebab case** ou o **caso kebab** tem esse nome pois o formato das palavras lembram um espeto kebab, uma comída típica árabe (Podemos pensar em um espetinho de churrasco). Veja o exemplo em **kebab case**

### **era-uma-vez-um-gato-xadrez**

As palavras são escritas em minúsculo que lembram os pedaços de carne, e são separadas pelo caractere `"-"` que lembra o espeto. O **kebab case** é um caso de nomenclatura menos comumente usado em linguagens de programação.

---

<!-- _class: center dark -->

# Na prática

Escreva seu nome completo nos 3 casos:
`camelCase`, `snake_case` e `kebab-case`

---

# Exemplo

A seguir, podemos observar um exemplo um pouco mais real quando falamos de código, utilizado na linguagem Python

```python
nome_completo = "Luísa Silva Reis"

data-de-nascimento = "26/07/2005"

corFavorita = "Vermelho"
```

Normalmente, adotamos apenas um caso de uso dentro do código. Os mais comuns são `camelCase` e `snake_case`. Este é apenas um exemplo para aplicar os diferentes casos de nomenclatura estudados