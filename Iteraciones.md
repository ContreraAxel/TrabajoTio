# Iteraciones en Python #

Se denominará iteración a aquel conjunto de instrucciones que se encuentran acotadas por un bloque repetivo de acciones indicadas a través de comandos en el lenguaje **Python**. Las instrucciones por excelencia en este lenguaje pertenecen a los bloques **FOR** y **WHILE**. Estos bloques poseen identación para reconocer  el bloque como tal.

## Uso de la instrucción for ##

La instrucción **FOR** es utilizada para acotar un bloque de sentencias que tendrán una condición a evaluar para permitir la repetición de las mismas. Su sintáxis es:

- **Instrucción de inicio del bloque**: Se utiliza  la línea de código _"for variable  in rango_de_variable:"_. Los dos puntos no se deben omitir son parte de la sintáxis.

- **Cuerpo del bloque**: Corresponde a un conjunto de sentencias que poseen un sangrado porpia del bloque.

### Ejemplos: ###
**A)** Escribiendo un bloque que calcula la suma de número que van desde 2 hasta 10, asumiendo que el valor inicial de la variable que guarda el resultado es cero.

resultado = 0

for i in range(2,11):

resultado +=i

print("La suma dá " + str(resultado))


## Instrucción while ##
La instrucción **WHILE** es utilizada para controlar un ciclo repetivo de instrucciones, bajo un sistema de condicional. Su sintaxis es:

-**Línea cabecera o de inicio  del bloque**: Está línea inicia con la instrucción **WHILE** y debe tener un término condicional a la par, al final del término se coloca dos puntos , como _" while (condicional):"_.

-**Cuerpo del bloque**: Son un conjunto de sentencias marcadas por un sangrado que se repiten hasta que la instrucción condicional de la cabecera sea falsa.

### Ejemplos: ###
**A)** Genere un bloque  que utilice la instrucción while para sumar los números enteros desde el 2 hasta el 10. Su ponga que inicialmente el valor de la variable que guardará el resultado vale 0.

resultado = 0

i = 2}

while (i<11):

resultado +=i

i +=1

print("La suma dá " + str(resultado))
