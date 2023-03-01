# Conversao-de-Reais-em-Dolares.
Este código solicita ao usuário que insira a quantidade de reais em sua carteira e, em seguida, converte esse valor em dólares usando uma taxa de conversão fixa de 4,77.

v1 = (input('Digite aqui quantos reais(R$) você tem em sua carteira:')): Esta linha solicita ao usuário que insira a quantidade de reais em sua carteira. O valor digitado é armazenado na variável v1 como uma string.

dolar = float 4.77: Esta linha define a taxa de conversão fixa de 4,77 como uma variável float chamada dolar.

conversão = v1 * dolar: Nesta linha, o valor de v1 é multiplicado pelo valor de dolar para calcular a conversão de reais em dólares. O resultado é armazenado na variável conversão.

print(f'Você pode comparar: $',conversão): Por fim, o resultado é impresso na tela com a mensagem "Você pode comparar: $" seguido do valor da conversão. O f antes das aspas duplas indica que a string é formatada e permite que a variável conversão seja inserida na string usando chaves {} para mostrar o resultado.
