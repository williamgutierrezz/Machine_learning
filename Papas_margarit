import numpy as np

can = []
ref = []
total = []
dia = [] 
T = 3
D = 2 
venta_mayor = 0
venta_menor = 0
producto_max = 0
producto_min = 0

def inicializar ():
    day = input('Ingrese el dia: ')
    dia.append(day)
    for i in range(T):
        can.append(0)
        ref.append(0)
        total.append(0)
    print(can)

#Solicita datos al usuario para la cantidad
def captura():
    for i in range(D):
     for i in range(T):
      can[i]= int(input("Escriba la cantidad de ventas de la referencia de papas fritas: "))
    return (can)
print(can)
  

# Solicita el valor al usuario por referencia
def reference():
    for i in range(D):
     for i in range(T):
        ref[i]= int(input("Escriba el valor de venta de la referencia de papas fritas: "))
    return ref
print(can, ref)

# Funcion para calcular los costos
def costos(can, ref):
    for i in range(T):
        total[i] = can[i] * ref[i]
    return total

# calculos
def mostrar (can, ref, total):
    tgc=0
    tgv=0
    print(can)
    print(ref)
    print(total)
    for i in range(T):
        tgc = tgc + can[i]
    for i in range(T):
        tgv = tgv + total[i]
    print("ventas en unidades de papas fritas es de:  ", tgc)
    print("ventas totales en dinero de papas fritas es de: ", tgv)     

# muestra el valor maximo y minimo vendido en el dia
def venta_max (total):
    for i in range(T):
        venta_mayor = print(f'la venta mayor del dia fue: {max (total)} ' + str(dia) )
        venta_menor = print(f'la venta menor del dia fue: {min (total)}' + str(dia))
        return venta_mayor, venta_menor

# la referencia del producto mas vendido
def Producto_cantidad (ref):
    for i in range(T):
        producto_max = print(f'El producto del dia mas vendido fue: {max (ref)} ' + str(dia))
        producto_min = print(f'El producto del dia menos vendido fue: {min (ref)}' + str(dia))
        return producto_max, producto_min

# orden de ejecucion de la aplicacion
def main():
    encabezado()
    inicializar()
    can = captura()
    ref = reference()
    total = costos(can,ref)
    mostrar (can,ref,total)
    venta_max(total)
    Producto_cantidad(ref)
    leave()

# mostrar titulo aplicativo
def encabezado():
    print("Bienvenido al aplicativo de la empresa margarita")

# mesaje de despedida
def leave():
    print("Gracias por utilizar nuestro aplicativo")

# Bloque principal
main()    
