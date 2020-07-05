#Calculadora

print('BIENVENIDO A TU CALCULADORA')

print('Que operacion matematica deseas realizar? :')

print('1: Suma')

print('2: Resta')

print('3: Multiplicación')

print('4: División')


operacion = float(input('Selecciona tu opción: '))

if operacion == 1:

    operador_1 = float(input('Introduce el primer numero: \n'))
    
    
    operador_2 = float(input('Introduce el segúndo numero: \n'))
    
    
    resultado = operador_1 + operador_2
    
    
    print(f'El resultado de la suma es: {resultado}')
    
elif operacion == 2:

     operador_1 = float(input('Introduce el primer numero: \n'))
     
     operador_2 = float(input('Introduce el segúndo numero: \n'))
     
     resultado = operador_1 - operador_2
     
     print(f'El resultado de la resta es: {resultado}')

elif operacion == 3:

     operador_1 = float(input('Introduce el primer numero: \n'))
     
     operador_2 = float(input('Introduce el segúndo numero: \n'))
     
     resultado = operador_1 * operador_2
     
     print(f'El resultado de la multiplicación es: {resultado}')

elif operacion == 4:
     
     operador_1 = float(input('Introduce el primer numero: \n'))
     
     operador_2 = float(input('Introduce el segúndo numero: \n'))
     
     if (operador_2 == 0):
         
         print('No se puede dividir en 0')
     
     else:
         
         resultado = operador_1 / operador_2
         
         print(f'El resultado de la división es: {resultado}')

else:
    
    print('Coloca la opción correcta Kchon')

