# Conceptos basicos #

## Operadores y funcion return ##

Python permite utilizar los operadores basicos (Suma, resta, division y multiplicacion). La sintaxis es la convencional, y se pueden usar paréntesis para modificar el orden de asociación natural de las operaciones (potenciación, producto/división, suma/resta).

Una funcion que se usa mucho es **return**, que  se lo utiliza en funciones para devolver *un solo valor*. Return detiene la ejecución de la función y devuelve el resultado indicado:
ej:**def cuadrado(x):
return x*x
print cuadrado(2)
El resultado sera: 4**

## Impresion por pantalla en Python ##

Para imprimir por pantalla vamos a usar la funcion: **Print("_Texto a mostrar_")** .
Ej: *Texto a mostrar*

Admite varios argumentos seguidos. Estos deben estar separados por una coma. Se muestran en el mismo orden y en la misma línea, separados por espacios: **Print("_Texto a mostrar_", "_Otro texto a mostrar_")**.
Ej: **Texto a mostrar" "Otro texto a mostrar**

Tambien se puede no escribir coma entre ellas, pero quedara sin espacio entre ellas: **Print("_Texto a mostrar_" "_Otro texto a mostrar_")**.
Ej: **Texto a mostrarOtro texto a mostrar**

Al terminar cada **Print()** Python hace un salto de linea:
**Print("_Texto a mostrar_")**.
**Print("_Otro texto a mostrar_")**.
Ej:**Texto a mostrar
   Otro texto a mostrar**
