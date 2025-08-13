# 💵 Conversor de Dólar para Real

Este é um simples programa em Python que converte valores de **dólar (US$)** para **real (R$)** utilizando uma taxa de câmbio fixa.

## 📜 Como funciona
O programa:
1. Solicita ao usuário um valor em dólares.
2. Multiplica esse valor pela taxa de câmbio definida no código (`5.40`).
3. Exibe o resultado formatado.

## 📂 Código
```python
valor_usd = float(input("Digite o valor em dólar (US$): "))

valor_brl = 5.40 * valor_usd
print(f"US${valor_usd:.2f} equivalem a R${valor_brl:.2f}")
