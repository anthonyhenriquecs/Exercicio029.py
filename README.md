# Exercicio029.py
#Escreva um programa que leia a velocidade de um carro. Se ele ultrapassar 80Km/h, mostre uma mensagem dizendo que ele foi multado. A multa vai custar R$7,00 por cada Km acima do limite.

velocidade = float(input('qual sua velocidade? '))
if velocidade > 80:
    print('Multado')
    r = (velocidade - 80)*7
    print('valor da multa: {:.2f}'.format(r))
print('tenha um bom dia')
