# Linguagem-de-Progamacao
Códigos em Python
uso do if,else e da linguagem for: 
vl_inicio = float(input("Digite o valor inicial de Fahrenheit: "))
vl_final = float(input("Digite o valor final de Fahrenheit: "))
if vl_inicio <= vl_final:
    passo = 1
else:
    passo = -1
print(f"{'Fahrenheit':>12} | {'Celsius':>10}")
print('-' * 25)
for f in range(int(vl_inicio),int( vl_final)+ passo,passo):
    c = (5) * (f - 32)/9
    print(f"{f:>12} | {c:>10.2f}")
