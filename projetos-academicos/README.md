[main.py](https://github.com/user-attachments/files/27938657/main.py)# Projetos Acadêmicos
Espaço reservado para os trabalhos da faculdade.

[Uplosoma_pares = 0
soma_impares = 0
qtd_pares = 0
qtd_impares = 0
soma_total = 0
qtd_total = 0

print("--- Calculadora de Médias (Digite 0 para sair) ---")

while True:
    num = int(input("Digite um número inteiro: "))

    # Condição de saída
    if num == 0:
        break

    # Atualiza totais gerais
    soma_total += num
    qtd_total += 1

    # Verifica se é par ou ímpar
    if num % 2 == 0:
        soma_pares += num
        qtd_pares += 1
    else:
        soma_impares += num
        qtd_impares += 1

print("\n--- Resultados ---")
print(f"Quantidade total de números digitados: {qtd_total}")
print(f"Soma total de números digitados: {soma_total}")

# Validações para evitar divisão por zero (caso o usuário não digite pares ou ímpares)
if qtd_pares > 0:
    media_pares = soma_pares / qtd_pares
    print(f"Média aritmética dos números pares: {media_pares:.2f}")
else:
    print("Nenhum número par foi digitado.")

if qtd_impares > 0:
    media_impares = soma_impares / qtd_impares
    print(f"Média aritmética dos números ímpares: {media_impares:.2f}")
else:
    print("Nenhum número ímpar foi digitado.")ading main.py…]()


    

