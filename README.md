# TP02 — Variáveis e Tipos de Dados

**Disciplina:** Programação e Sistemas de Informação (PSI) — Módulo 3
**Trabalho Prático:** 02
**Turma:** 1.º I — N.º 14785
**Ano Letivo:** 2025/2026

Trabalho com variáveis numéricas, conversão de tipos (`int`, `float`) e operadores aritméticos fundamentais.

---

## Ficheiros

| Ficheiro | Enunciado |
|---|---|
| `01.py` | Somar dois números inteiros inseridos pelo utilizador |
| `02.py` | Converter temperatura de Celsius para Fahrenheit |
| `03.py` | Calculadora com as 4 operações básicas |

---

## Exercícios

### 01.py — Soma de Dois Números

Enunciado: Criar um programa que pergunte dois números e mostre a soma.

```python
opA = int(input("Indica o valor de A: "))
print("Valor de A introduzido: ", opA)
print("---")
opB = int(input("Indica o valor de B: "))
print("Valor de B introduzido: ", opB)
print("---")
soma = opA + opB
print(f"A soma entre {opA} e {opB} e: {soma}")
```

Nota: sem `int()`, a expressão `"5" + "3"` resultaria em `"53"` (concatenação de strings) e não em `8` (soma numérica).

---

### 02.py — Celsius para Fahrenheit

Enunciado: Implementar a fórmula de conversão de temperatura.

Fórmula: graus F = (graus C × 9/5) + 32

```python
celsius = float(input("Indica a temperatura em graus Celsius: "))
celsius = int(celsius)
print(f"Temperatura em graus Celsius: {celsius}")
print("---")
fahrenheit = (celsius * 9/5) + 32
print(f"Temperatura em graus Fahrenheit: {fahrenheit}")
```

---

### 03.py — Calculadora Simples

Enunciado: Sistema que pede dois números e apresenta o resultado das quatro operações.

```python
num1 = float(input("Introduza o primeiro numero: "))
num2 = float(input("Introduza o segundo numero: "))

soma          = num1 + num2
subtracao     = num1 - num2
multiplicacao = num1 * num2
divisao       = num1 / num2

print("---")
print(f"O resultado da soma e: {soma}")
print(f"O resultado da subtracao e: {subtracao}")
print(f"O resultado da multiplicacao e: {multiplicacao}")
print(f"O resultado da divisao e: {divisao}")
```

---

## Conceitos Abordados

| Conceito | Descrição |
|---|---|
| `int()` | Converte string para inteiro |
| `float()` | Converte string para decimal |
| `+` `-` `*` `/` | Operadores aritméticos |
| f-strings | `f"texto {variavel}"` — formatação de saída |
| Conversão de tipos | `str` para `int`, `str` para `float`, `float` para `int` |

---

## Como Executar

```bash
git clone https://github.com/a14785-oficina/variaveis-e-tipos-de-dados.git
cd variaveis-e-tipos-de-dados
python3 01.py
```

---

## Navegação — Módulo 3

| Posição | Repositório |
|---|---|
| Anterior | [TP01 — Introdução ao Python](https://github.com/a14785-oficina/introducao-ao-python) |
| Seguinte | [TP03 — Operadores](https://github.com/a14785-oficina/operadores) |
| Portfólio | [oficina-jpc](https://github.com/a14785-oficina/oficina-jpc) |

---

*PSI — Módulo 3 — Programação Estruturada — OFICINA — 2025/2026*
