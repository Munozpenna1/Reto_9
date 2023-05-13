# Reto_9
escogemos los 3 

codigo 1


```x= int (input("inserte un numero:"))
if x>=97 and x<=122: 
    print ("el numero presentado pertenece a una letra o vocal minuscula en el codigo ASCII")
elif x< 97 and x>122:
    print ("el numero presentado no pertenece a una letra o vocal minuscula del codigo ASCII")
```

codigo 2
```
a = input("Ingrese una longitud por favor: ")
y = ord(a[0])

if y % 2 == 0:
    print("El código ASCII de la primera letra es par.")
else:
    print("El código ASCII de la primera letra es impar.")
```


codigo 3

```
x=input("Escriba en el siguiente espacio por favor:")
if x>= '0' and x<='9':
    print("es un digito")
else:
    print ("no es un digito")

   
```

 y los escribimos en lambdas

lambdas 1

```validar_ascii = lambda x: "el numero presentado pertenece a una letra o vocal minuscula en el codigo ASCII" if x >= 97 and x <= 122 else "el numero presentado no pertenece a una letra o vocal minuscula del codigo ASCII"

x = int(input("Inserte un numero: "))
print(validar_ascii(x))
```

lambdas 2

``` es_par = lambda x: "par" if x % 2 == 0 else "impar"

a = input("Ingrese una longitud por favor: ")
y = ord(a[0])

print(f"El código ASCII de la primera letra es {es_par(y)}.")
```

lambdas 3

``` s_digito = lambda x: "es un digito" if x >= '0' and x <= '9' else "no es un digito"

x = input("Escriba en el siguiente espacio por favor:")
print(es_digito(x))  
```

arg 1

``` def es_letra_ascii(*args):
    for x in args:
        if ord(x[0]) >= 97 and ord(x[0]) <= 122:
            print(f"{x} pertenece a una letra o vocal minúscula en el código ASCII")
        else:
            print(f"{x} no pertenece a una letra o vocal minúscula en el código ASCII")

x = input("Ingrese un valor: ")
es_letra_ascii(x)
```

arg 2

``` def es_par_ascii(*args):
    for a in args: 
        y = ord(a[0])
        if y % 2 == 0:
            print(f"El código ASCII de la primera letra de '{a}' es par.")
        else:
            print(f"El código ASCII de la primera letra de '{a}' es impar.")


a = input("Ingrese un valor: ")
es_par_ascii(a)
```

arg 3

```def es_digito(*args):
    for x in args:
        if x >= '0' and x <= '9':
            print("lo ingresado es un dígito.")
        else:
            print("lo ingresado no es un dígito.")

valores = input("Ingrese algo : ").split()
es_digito(*valores)
```



3. Escriba una función recursiva para calcular la operación de la potencia.

¿Como asi?

4. Utilice la siguiente plantilla de code para contar el tiempo:
```
import time

start_time = time.time()
# instrucciones sobre las cuales se quiere medir tiempo de ejecución
end_time = time.time()

timer = end_time - start_time
print(timer)
```

Respuesta







...


![asi.png](asi.png "Usuario creado" )

Linkedin 
https://uy.linkedin.com/in/diego-alejandro-mu%C3%B1oz-penna-5164ba151

# Fin
