# Atividade Python - Escola da Nuvem

Esta atividade contém quatro pequenos programas desenvolvidos em Python, propostos como parte do curso da Escola da Nuvem (EDN). Cada programa visa treinar conceitos básicos de programação.

---

## 1. Programa de Saudação

**Objetivo:** Imprimir uma mensagem simples na tela.

```python
print("Olá, mundo!")
```

## 2. Calculadora de Soma

* Objetivo: Somar dois números definidos no código e exibir o resultado.

```python
numero1 = 12
numero2 = 14
soma = numero1 + numero2
print(f"A soma de {numero1} e {numero2} é: {soma}")
```

## 3. Calculadora de Volume

* Objetivo: Calcular o volume de uma caixa retangular usando as dimensões:

```python
comprimento = 12  # cm
largura = 14      # cm
altura = 20       # cm

volume = comprimento * largura * altura
print(f"O volume da caixa é: {volume} cm³")
```

* Fórmula usada:
- volume = comprimento * largura * altura

## 4. Calculadora de Preço Total

* Objetivo: Calcular o custo total de uma compra com base nas seguintes informações:

```python
nome_produto = "Cadeira Infantil"
preco_unitario = 12.40
quantidade = 3

preco_total = preco_unitario * quantidade

print("Produto:", nome_produto)
print("Preço unitário: R$", preco_unitario)
print("Quantidade:", quantidade)
print("Preço total da compra: R$", round(preco_total, 2))
```

Cálculo:
preco_total = preco_unitario * quantidade

O programa exibe o nome do produto, preço unitário, quantidade comprada e o total a pagar.