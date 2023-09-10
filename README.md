# Manual de usuario
Esta herramienta permite entender de manera visual, textual y experimental la manera que funcionan los algoritmos de ordenamiento cubiertos.

Los algoritmos desarrollados son:
- Quick Sort
- Bubble Sort
- Heap Sort
- Merge Sort
- Selection Sort
- Insertion Sort

## Modo de ejecución
  La herramienta proporciona a los usuarios dos modos de ejecución distintos:
- **Modo de ejecución manual:** En este modo, el usuario tiene el control total sobre la ejecución del algoritmo. El mismo puede avanzar paso a paso a través del algoritmo presionando un botón para cada paso, lo que le brinda la posibilidad de analizar detalladamente cada cambio y comprender cómo se desarrolla el proceso de ordenamiento. El hecho de que el progreso del proceso de ordenamiento se encuentre bajo el control del usuario lo transforma en el método idóneo a utilizar a la hora de buscar explicarlo en el contexto de una clase.
- **Modo de ejecución automático:** En este modo, el algoritmo se ejecuta de manera automática sin la intervención del usuario. Una vez que el usuario selecciona este modo y ajusta la velocidad deseada, la herramienta inicia el proceso de ordenamiento de forma continua hasta el final. 

## Parámetros modificables
Los parámetros que el usuario puede personalizar son los siguientes:
- **Modo de generación:** Este parámetro permite al usuario seleccionar el modo mediante el cual se generará el array para observar el comportamiento del algoritmo de ordenamiento en diferentes situaciones iniciales. Se ofrecen cuatro modos disponibles:
  - Random: La generación de valores del array se realiza de manera aleatoria.
  - Nearly sorted: La generación de valores del array se realiza de manera tal que el algoritmo se encuentre por la mayor parte ordenado de manera incremental. Esto implica que, a excepción de algunos elementos, el resto se encuentran ordenados.
  - Reversed: La generación de valores del array se realiza de manera que el array se encuentre ordenado de forma decreciente.
  - Few unique: La generación de valores del array se realiza de manera tal que el mismo se encuentre compuesto solo por una serie de valores que se repiten muchas veces.
- **Tamaño del array:** A través de un slider, el usuario puede definir el tamaño del array a generar. El tamaño del array está limitado entre un mínimo de 4 y un máximo de 100 elementos.
- **Velocidad:** Este parámetro determina el tiempo de retraso entre cada paso del algoritmo durante la ejecución automática. A medida que se incrementa la velocidad, disminuye el retraso entre cada paso del algoritmo. Se cuentan con cinco velocidades, en donde el retraso asociado a cada una de ellas es el siguiente:
  - Velocidad 1: 500 ms
  - Velocidad 2: 250 ms
  - Velocidad 3: 100 ms
  - Velocidad 4: 60 ms
  - Velocidad 5: 30 ms
- **Activar temporizador:** Esta opción activa un temporizador que inicia y finaliza su ejecución simultáneamente con el algoritmo que se está ejecutando.

## Estructura del código
El código puede ser activado por el usuario a través de la presión del botón “Código”  ubicado en el apartado inferior derecho de la configuración.

Una vez presionado el botón, se abre una ventana modal en el centro de la pantalla que contiene el código realizado en Python correspondiente al algoritmo seleccionado.

El usuario tiene la posibilidad de:
- **Copiar el código:** Existe un botón en la esquina superior derecha de la modal que permite al usuario copiar el código mostrado en la misma.
- **Cambiar el theme:** Permite al usuario alternar entre una “Light Theme” y “Dark Theme”, en función de ajustarse a las preferencias visuales del usuario.
