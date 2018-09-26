# TrabajoPracticoTio

## �Que es Python?


Python es un lenguaje de programaci�n poderoso y f�cil de aprender. Cuenta con estructuras de datos eficientes y de alto nivel, como tambi�n un enfoque simple pero efectivo a la programaci�n orientada a objetos. La elegante sintaxis de Python y su tipado din�mico, junto con su naturaleza interpretada, hacen de �ste un lenguaje ideal para scripting y desarrollo r�pido de aplicaciones en diversas �reas y sobre la mayor�a de las plataformas. El int�rprete de Python y la extensa biblioteca est�ndar est�n a libre disposici�n en forma binaria y de c�digo fuente para las principales plataformas desde el sitio web de Python, https://www.python.org/, y puede distribuirse libremente. El mismo sitio contiene tambi�n distribuciones y enlaces de muchos m�dulos libres de Python de terceros, programas y herramientas, y documentaci�n adicional.. Este informe introduce de manera informal al lector a los conceptos y caracter�sticas b�sicas del lenguaje . Para una descripci�n de los objetos y m�dulos est�ndar, mir� la referencia de la biblioteca esta provee una definici�n m�s formal del lenguaje.


## La sentencia


Tal vez el tipo m�s conocido de sentencia sea el if. Por ejemplo:

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
... print('M�s')
...
'Mas'

~~~

~~~
print("DIVISOR DE N�MEROS")
dividendo = int(input("Escriba el dividendo: "))
divisor = int(input("Escriba el divisor: "))

if dividendo % divisor == 0:
    print(f"La divisi�n es exacta. Cociente: {dividendo // divisor}")
else:
    print(f"La divisi�n no es exacta. Cociente: {dividendo // divisor} "
          f"Resto: {dividendo % divisor}")


~~~

## Iteraciones


Se denominar� iteraci�n a aquel conjunto de instrucciones que se encuentran 

acotadas por un bloque repetitivo de acciones indicadas a trav�s de comandos en el 

lenguaje python. Las instrucciones por excelencia en este lenguaje pertenecen a los 

bloques for y while. Estos bloques poseen identaci�n para reconocer  el bloque como 

tal. 



Uso de la instrucci�n for
La instrucci�n for es utilizada para acotar un bloque de sentencias que tendr�n una 

condici�n a evaluar para permitir la repetici�n de las mismas. Su sintaxis es:
Instrucci�n de inicio del bloque: Se utiliza  la l�nea de c�digo "for variable  in 

rango_de_variable:". Los dos puntos no se deben omitir son parte de la sintaxis.

Cuerpo del bloque: Corresponde a un conjunto de sentencias que poseen un sangrado 

propia del bloque.

Ejemplos:

a) Escribiendo un bloque que calcula la suma de n�mero que van desde 2 hasta 10, 

asumiendo que el valor inicial de la variable que guarda el resultado es cero.

~~~
resultado = 0
for i in range(2,11):
resultado +=i
   
print("La suma d� " + str(resultado))


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




Instrucci�n while:

La instrucci�n while es utilizada para controlar un ciclo repetitivo de 

instrucciones, bajo un sistema de condicional. Su sintaxis es:
L�nea cabecera o de inicio  del bloque: Est� l�nea inicia con la instrucci�n while 

y debe tener un t�rmino condicional a la par, al final del t�rmino se coloca dos 

puntos , como " while (condicional):".
Cuerpo del bloque: Son un conjunto de sentencias marcadas por un sangrado que se 

repiten hasta que la instrucci�n condicional de la cabecera sea falsa.

Ejemplo:

~~~
resultado = 0
i = 2
while (i<11):
resultado +=i
i +=1
   
print("La suma d� " + str(resultado))
~~~

