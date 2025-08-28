# Calculo_IMC

peso = float(input('Digite o seu peso (kg): '))
altura = float(input('Digite a sua altura (m): '))

calculo_imc = peso / (altura ** 2)
print('Seu IMC é:', calculo_imc)

if calculo_imc < 18.5:
    print('Você está abaixo do peso.')
elif calculo_imc < 25:
    print('Você está com o peso normal!')
else:
    print('Você está acima do peso.')
