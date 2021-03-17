# promedio-y-sumatotalx = 1
suma = 0
while x <= 100:
    valor = int(input("numero "+str(x)+" "))
    suma = suma + valor
    x = x + 1
    if valor == 0:
        break
x = x - 2
promedio = suma/x
print("la suma total es: "+str(suma))
print("el promedio total es: "+str(promedio))
print("el numero de datos ingresados son: "+str(x))
