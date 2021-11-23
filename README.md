# TAREAS


print("----EJERCICIO 1----")
numero = 5
cor = 0
numero2=1

for numeros in numero:

    for x in range(numero2):
        print("*")
    numero2=numero2+1
    print("\n")      


print("---EJERCICO 2----")
print("Ingrese un numero")
if numero < 0:
    print("numero incorrecto")
if numero > 0:
    for x in range(0,numero +1):
        print(x, end="  ")


print("---EJERCICIO 3----")
for x in range(1,numero):
    if numero % x == 0:
        cor = cor + 1

if cor > 2:
    print("el numero no es primo")
