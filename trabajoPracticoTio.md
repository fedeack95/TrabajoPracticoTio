# TrabajoPracticoTio
##Introducción 


Python es un lenguaje de programación poderoso y fácil de aprender. Cuenta con estructuras de datos eficientes y de alto nivel y un enfoque simple pero efectivo a la programación orientada a objetos. La elegante sintaxis de Python y su tipado dinámico, junto con su naturaleza interpretada, hacen de éste un lenguaje ideal para scripting y desarrollo rápido de aplicaciones en diversas áreas y sobre la mayoría de las plataformas. El intérprete de Python y la extensa biblioteca estándar están a libre disposición en forma binaria y de código fuente para las principales plataformas desde el sitio web de Python, https://www.python.org/, y puede distribuirse libremente. El mismo sitio contiene también distribuciones y enlaces de muchos módulos libres de Python de terceros, programas y herramientas, y documentación adicional. El intérprete de Python puede extenderse fácilmente con nuevas funcionalidades y tipos de datos implementados en C o C++ (u otros lenguajes accesibles desde C). Python también puede usarse como un lenguaje de extensiones para aplicaciones personalizables. Este tutorial introduce de manera informal al lector a los conceptos y características básicas del lenguaje y el sistema de Python. Es bueno tener un intérprete de Python a mano para experimentar, sin embargo todos los ejemplos están aislados, por lo tanto el tutorial puede leerse estando desconectado. Para una descripción de los objetos y módulos estándar, mirá La referencia de la biblioteca. La referencia de la biblioteca provee una definición más formal del lenguaje. Para escribir extensiones en C o C++, leé Extendiendo e Integrando el Intérprete de Python y la Referencia de la API Python/C. Hay también numerosos libros que tratan a Python en profundidad. Este tutorial no pretende ser exhaustivo ni tratar cada una de las características, o siquiera las características más usadas. En cambio, introduce la mayoría de las características más notables de Python, y te dará una buena idea del gusto y estilo del lenguaje. Luego de leerlo, serás capaz de leer y escribir módulos y programas en Python, y estarás listo para aprender más de los variados módulos de la biblioteca de Python descritos en La referencia de la biblioteca.


##La sentencia
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

