# Practicas
'''''''''''''''practica 4'''''''''


#Ejercicio 1: Multiplicar todos los elementos por 3
#Dada una lista de números, multiplica todos los elementos por 3.
numeros = [1, 2, 3, 4, 5]
resultado = [num * 3 for num in numeros]
print(resultado)

#Ejercicio 2: Filtrar números mayores a 10
#Dada una lista de números, filtra los números que son mayores a 10.
numeros = [5, 10, 15, 20, 25]
resultado = [num for num in numeros if num > 10]
print(resultado)

#Ejercicio 3: Convertir una lista de palabras a mayúsculas
#Dada una lista de palabras, conviértelas todas a mayúsculas.
palabras = ["hola", "mundo", "python"]
resultado = [palabra.upper() for palabra in palabras]
print(resultado)


#Ejercicio 4: Filtrar palabras que empiezan con 'p'
#Dada una lista de palabras, filtra aquellas que comienzan con la letra 'p'.
palabras = ["hola", "mundo", "python", "programacion"]
resultado = [palabra for palabra in palabras if palabra.startswith('p')]
print(resultado)


#Ejercicio 5: Calcular la longitud de cada palabra
#Dada una lista de palabras, calcula la longitud de cada una.
palabras = ["hola", "mundo", "python"]
resultado = [len(palabra) for palabra in palabras]
print(resultado)


#Ejercicio 6: Filtrar palabras con longitud mayor a 4
#Dada una lista de palabras, filtra aquellas que tienen una longitud mayor a 4.
palabras = ["hola", "mundo", "python", "hi"]
resultado = [palabra for palabra in palabras if len(palabra) > 4]
print(resultado)


#Ejercicio 7: Convertir una lista de temperaturas de Celsius a Fahrenheit
#Dada una lista de temperaturas en Celsius, conviértelas a Fahrenheit.
celsius = [0, 20, 37, 100]
resultado = [(temp * 9/5) + 32 for temp in celsius]
print(resultado)

#Ejercicio 8: Filtrar temperaturas mayores a 50 grados Fahrenheit
#Dada una lista de temperaturas en Fahrenheit, filtra aquellas que son mayores a 50 grados.
fahrenheit = [32.0, 68.0, 98.6, 212.0]
resultado = [temp for temp in fahrenheit if temp > 50]
print(resultado)

#Ejercicio 9: Sumar 5 a todos los elementos de una lista
#Dada una lista de números, suma 5 a cada uno de ellos.
numeros = [1, 2, 3, 4, 5]
resultado = [num + 5 for num in numeros]
print(resultado)


#Ejercicio 10: Filtrar palabras que contienen la letra 'a'
#Dada una lista de palabras, filtra aquellas que contienen la letra 'a'.
palabras = ["hola", "mundo", "python", "vida"]
resultado = [palabra for palabra in palabras if 'a' in palabra]
print(resultado)




