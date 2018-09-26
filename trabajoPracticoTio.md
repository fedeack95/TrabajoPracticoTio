# TrabajoPracticoTio

## ¿Que es Python?


Python es un lenguaje de programación poderoso y fácil de aprender. Cuenta con estructuras de datos eficientes y de alto nivel, como también un enfoque simple pero efectivo a la programación orientada a objetos. La elegante sintaxis de Python y su tipado dinámico, junto con su naturaleza interpretada, hacen de éste un lenguaje ideal para scripting y desarrollo rápido de aplicaciones en diversas áreas y sobre la mayoría de las plataformas. El intérprete de Python y la extensa biblioteca estándar están a libre disposición en forma binaria y de código fuente para las principales plataformas desde el sitio web de Python, https://www.python.org/, y puede distribuirse libremente. El mismo sitio contiene también distribuciones y enlaces de muchos módulos libres de Python de terceros, programas y herramientas, y documentación adicional.. Este informe introduce de manera informal al lector a los conceptos y características básicas del lenguaje . Para una descripción de los objetos y módulos estándar, mirá la referencia de la biblioteca esta provee una definición más formal del lenguaje.


## La sentencia


Tal vez el tipo más conocido de sentencia sea el if. Por ejemplo:

~~~
>>> x = int(input("Ingresa un entero, por favor: "))
Ingresa un entero, por favor: 42
>>> if x < 0:
... x = 0
... print('Negativo cambiado a cero')
... elif x == 0:
... print('Cero')
... elif x == 1:
... print('Simple')
... else:
... print('Más')
...
'Mas'

~~~

~~~
print("DIVISOR DE NÚMEROS")
dividendo = int(input("Escriba el dividendo: "))
divisor = int(input("Escriba el divisor: "))

if dividendo % divisor == 0:
    print(f"La división es exacta. Cociente: {dividendo // divisor}")
else:
    print(f"La división no es exacta. Cociente: {dividendo // divisor} "
          f"Resto: {dividendo % divisor}")


~~~

## Iteraciones


Se denominará iteración a aquel conjunto de instrucciones que se encuentran 

acotadas por un bloque repetitivo de acciones indicadas a través de comandos en el 

lenguaje python. Las instrucciones por excelencia en este lenguaje pertenecen a los 

bloques for y while. Estos bloques poseen identación para reconocer  el bloque como 

tal. 



Uso de la instrucción for
La instrucción for es utilizada para acotar un bloque de sentencias que tendrán una 

condición a evaluar para permitir la repetición de las mismas. Su sintaxis es:
Instrucción de inicio del bloque: Se utiliza  la línea de código "for variable  in 

rango_de_variable:". Los dos puntos no se deben omitir son parte de la sintaxis.

Cuerpo del bloque: Corresponde a un conjunto de sentencias que poseen un sangrado 

propia del bloque.

Ejemplos:

a) Escribiendo un bloque que calcula la suma de número que van desde 2 hasta 10, 

asumiendo que el valor inicial de la variable que guarda el resultado es cero.

~~~
resultado = 0
for i in range(2,11):
resultado +=i
   
print("La suma dá " + str(resultado))


~~~

otro ejemplo:
~~~
print("Comienzo")
for i in [3, 4, 5]:
    print(f"Hola. Ahora i vale {i} y su cuadrado {i ** 2}")
print("Final")

imprime:

Comienzo
Hola. Ahora i vale 3 y su cuadrado 9
Hola. Ahora i vale 4 y su cuadrado 16
Hola. Ahora i vale 5 y su cuadrado 25
Final

~~~




Instrucción while:

La instrucción while es utilizada para controlar un ciclo repetitivo de 

instrucciones, bajo un sistema de condicional. Su sintaxis es:
Línea cabecera o de inicio  del bloque: Está línea inicia con la instrucción while 

y debe tener un término condicional a la par, al final del término se coloca dos 

puntos , como " while (condicional):".
Cuerpo del bloque: Son un conjunto de sentencias marcadas por un sangrado que se 

repiten hasta que la instrucción condicional de la cabecera sea falsa.

Ejemplo:

~~~
resultado = 0
i = 2
while (i<11):
resultado +=i
i +=1
   
print("La suma dá " + str(resultado))
~~~

