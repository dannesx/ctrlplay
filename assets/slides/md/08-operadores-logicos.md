---
marp: true
theme: neubrutalism
---

<!-- _class: dark cover -->

# Operadores Lógicos

---

<!-- _class: center -->

# Conceito

Operadores lógicos `AND`, `OR` e `NOT` são utilizados quando queremos **combinar ou inverter** condições, nos permitindo utilizar mais de uma expressão lógica ao mesmo tempo, simplificando a lógica complexa

---

# Operador AND `&&`

O resultado de `A AND B` será verdadeiro apenas quando `A` e `B` forem condições verdadeiras. Na maiorida das linguagens, seu símbolo é `&&`.
**Exemplo:** *Vou para a praia se estiver calor `E` for feriado*

| Está calor? | É feriado? | Vou para a praia? |
| :-: | :-: | :---------: |
| ❌ | ❌ | ❌ |
| ❌ | ✅ | ❌ |
| ✅ | ❌ | ❌ |
| ✅ | ✅ | ✅ |

---

# Operador OR `||`

O resultado de `A OR B` será verdadeiro quando `A` ou `B` forem condições verdadeiras. Na maiorida das linguagens, seu símbolo é `||`.
**Exemplo:** *Vou para o shopping se eu tiver dinheiro `OU` for fim de semana*

| Tenho dinheiro? | É fim de semana? | Vou para o shopping? |
| :-: | :-: | :---------: |
| ❌ | ❌ | ❌ |
| ❌ | ✅ | ✅ |
| ✅ | ❌ | ✅ |
| ✅ | ✅ | ✅ |

---

# Operador NOT `!`

O resultado de `NOT A` será verdadeiro quando `A` for falso, e vice-versa. Na maiorida das linguagens, seu símbolo é `!`
**Exemplo:** *Vou para escola se `NÃO` estiver de férias*

| Estou de férias? | Vou para a escola? |
| :-: | :-: |
| ❌ | ✅ |
| ✅ | ❌ |

---

<!-- _class: dark center -->

# Na prática

Estamos desenvolvendo um sistema de irrigação para um agricultor. Ele pediu para que o sistema funcione da seguinte forma:

 _O sistema será ativado se: for de manhã `E` a previsão for de tempo seco `OU` se `NÃO` choveu na noite anterior._

Vamos fazer com a ajuda do professor