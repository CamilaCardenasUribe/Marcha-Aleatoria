# Marcha-Aleatoria

La simulación busca resolver los siguientes enunciados:

Escribir un programa de computador que simule una marcha aleatoria (en una, dos o tresdimensiones, como prefiera) de N pasos en donde N sea un parámetro que se entra en el computador. El programa debe dar la posición r después de los N pasos. Para N fijo perogrande correr el programa un número importante de veces para poder construir un histograma (posición final en función del número de veces que se repite) y comparar con la ley de probabilidad predicha por el teorema central límite.

Para varios valores de N correr el programa muchas veces y calcular para cada N el promedio⟨r⟩ y ⟨r^2 ⟩. Verificar que ⟨r^2⟩ es proporcional a N y determinar numéricamente la constante dedifusión.

De esta forma, se aconseja al usuario no modificar la entrada de las librerias y correrlas como esta indicada dentro del código. Si estas no son importadas con éxito, será necesario que el usuario ingrese al panel de librerias ya sea en JupiterNotebook, Spider o cualquier otro traductor del lenguaje Python.

En la segunda entrada el usuario encontrará la sección de variables, estas pueden ser modificadas sin afectar las funciones de las siguinetes entradas. Se recomienda al usuario mantener ests variables o modificarlas teniendo en cuenta la estructura y coherencia de las funciones para calcular la marcha aleatoria y los resultados estadísticos (n, promedio, varianza) de la muestra de su elección.

Para replicar los datos obtenidos dentro de la lista que guarda las posiciones (final_position) serecomienda al usuario correr la entrada definida por la finción (random_step) sin modificarla. Se recuerda que esta retorno a una tupla con la lista de las posiciones y el intervalo de pasos a considerar dentro de la construcción del histograma.

La función (histogram_graphic) podrá ser modificada a voluntad del usuario el cual puede alterar el diseño del gráfico agregando una nueva paleta de color, nombres para los ejes, la generación de una leyenda con los datos representados, etc. Recuerde que el histograma representa la frecuencia con la cual se repite una posición por ende el llamado a la función (random_step) no podrá ser modificada.

Para el calculo de n, promedio y varianza, se implementaron funciones pertenecientes a la libreria (Numpy) por lo cual se suguiere no alterar la función (average_distribution). Si desea modificar la forma como se reportan los datos se sugiere remitirse a la sección de las variables y alterar las listas que recibe como parámetro esta función.

En la última entrada, únicamente se esta tabulando los resultados de la función (average_distribution) por lo cual si el usuario lo desea puede eliminar esta sección y conformarse con el retorno de esta.
