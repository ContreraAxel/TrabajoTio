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

Ej: **Texto a mostrar**

Admite varios argumentos seguidos. Estos deben estar separados por una coma. Se muestran en el mismo orden y en la misma línea, separados por espacios: **Print("_Texto a mostrar_", "_Otro texto a mostrar_")**.

Ej: **Texto a mostrar Otro texto a mostrar**

Tambien se puede no escribir coma entre ellas, pero quedara sin espacio entre ellas: **Print("_Texto a mostrar_" "_Otro texto a mostrar_")**.

Ej: **Texto a mostrarOtro texto a mostrar**

Al terminar cada **Print()** Python hace un salto de linea:
**Print("_Texto a mostrar_")**.
**Print("_Otro texto a mostrar_")**.

Ej:**Texto a mostrar

   Otro texto a mostrar**

## Expresion de comparacion ##

Ademas de los numeros y textos, Python introduce las constantes true y false

Algunas de sus expresiones son:

a == b ||	a es igual a b

a != b ||	a es distinto de b

a < b	|| a es menor que b

a <= b ||	a es menor o igual que b

a > b	|| a es mayor que b

a >= b ||	a es mayor o igual que b

## Operadores logicos ##

Como se puede operar entre números mediante las operaciones de suma, resta, etc., también existen tres operadores lógicos para combinar expresiones booleanas: and (y), or (o) y not (no).


Algunos ejemplos:

a and b  || 	El resultado es True solamente si a es True y b es True de lo contrario el resultado es False

a or b  ||	 El resultado es True si a es True o b es True de lo contrario el resultado es False

not a	 ||  El resultado es True si a es False de lo contrario el resultado es False
