# Iteraciones en Python #

Se denominará iteración a aquel conjunto de instrucciones que se encuentran acotadas por un bloque repetivo de acciones indicadas a través de comandos en el lenguaje **Python**. Las instrucciones por excelencia en este lenguaje pertenecen a los bloques **FOR** y **WHILE**. Estos bloques poseen identación para reconocer  el bloque como tal.

## Uso de la instrucción for ##

La instrucción **FOR** es utilizada para acotar un bloque de sentencias que tendrán una condición a evaluar para permitir la repetición de las mismas. Su sintáxis es:

:Wink: **Instrucción de inicio del bloque**: Se utiliza  la línea de código _"for variable  in rango_de_variable:"_. Los dos puntos no se deben omitir son parte de la sintáxis.
:Wink: **Cuerpo del bloque**: Corresponde a un conjunto de sentencias que poseen un sangrado porpia del bloque.

### Ejemplos: ###
**A)** Escribiendo un bloque que calcula la suma de número que van desde 2 hasta 10, asumiendo que el valor inicial de la variable que guarda el resultado es cero.

resultado = 0
for i in range(2,11):
resultado +=i
   
print("La suma dá " + str(resultado))
