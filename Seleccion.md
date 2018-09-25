# Ordenamiento en Python #

En **Python** hay formas para ordenar listas, existen clases diferentes y/o conocidas para ordenar listas las cuales son: **Ordenamiento por Seleccion** y **Ordenamiento por Inserccion** , estas "funciones" o formas de ordenamientos se utilizan para ordenar listas de menor a mayor, o de mayor a menor.

## Por Selección ##

El ordenamiento por selección, es uno de los más sencillos, pero es bastante ineficiente, se basa en la idea de buscar el máximo en una secuencia, ubicarlo al final y seguir analizando la secuencia sin el último elemento.

Para hacer esto, un **ordenamiento por selección** busca el valor mayor a medida que hace una pasada y, después de completar la pasada, lo pone en la ubicación correcta. Al igual que con un ordenamiento burbuja, después de la primera pasada, el ítem mayor está en la ubicación correcta. Después de la segunda pasada, el siguiente mayor está en su ubicación. Este proceso continúa y requiere n−1 pasadas para ordenar los **n** ítems, ya que el ítem final debe estar en su lugar después de la **(n−1)-ésima** pasada.

## Por Insercion ##

Se basa en la idea de ir insertando ordenadamente, en cada paso se considera la inserción de un elemento más de secuencia y la inserción se empieza a hacer desde el final de los datos ya ordenados. Tiene como ventaja que en el caso de tener los datos ya ordenados no hace ningún intercambio (y hace sólo N − 1 comparaciones). Si bien es un algoritmo ineficiente, para secuencias cortas, el tiempo de ejecución es bastante bueno.

Funciona de una manera ligeramente diferente. Siempre mantiene una sublista ordenada en las posiciones inferiores de la lista. Cada ítem nuevo se “inserta” de vuelta en la sublista previa de manera que la sublista ordenada sea un ítem más larga.

En cada pasada, una para cada ítem desde 1 hasta n−1, el ítem actual se comparara contra los de la sublista ya ordenada. A medida que revisamos en la sublista ya ordenada, desplazamos a la derecha los ítems que sean mayores. Cuando llegamos a un ítem menor o al final de la sublista, se puede insertar el ítem actual.
