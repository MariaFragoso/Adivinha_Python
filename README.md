# Adivinha_Python
print('******************************')
print('*				Jogo	da	adivinhação					*')
print('******************************')

numero_secreto = 42
chute = int(input('Digite	o	seu	número:	'))
print('Você	digitou:	', chute)
if (numero_secreto == chute):
    print('Você	acertou!')
else:
    print('Você	errou!')

if (numero_secreto == chute):
    print('Você	acertou!')
elif (chute > numero_secreto):
    print('Você	errou!	O	seu	chute	foi	maior	que	o	número	secreto')
elif (chute < numero_secreto):
    print('Você	errou!	O	seu	chute	foi	menor	que	o	número	secreto')

    acertou = chute == numero_secreto
    maior = chute > numero_secreto
    menor = chute < numero_secreto
    if (acertou):
        print('Você	acertou!')
    elif (maior):
        print('Você	errou!	O	seu	chute	foi	maior	que	o	número	secreto')
    elif (menor):
        print('Você	errou!	O	seu	chute	foi	menor	que	o	número	secreto')
