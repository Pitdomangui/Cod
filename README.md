# Função para somar todos os números pares de uma lista
def soma_pares(lista):
    soma = 0
    for numero in lista:
        if numero % 2 == 0:
            soma += numero
    return soma

# Exemplo de uso
numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
resultado = soma_pares(numeros)
print(f"A soma dos números pares na lista é: {resultado}")
