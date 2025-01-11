# Manual de usuario
Esta herramienta proporciona una experiencia visual, textual y práctica para comprender el funcionamiento de diversos algoritmos de ordenamiento.

## Algoritmos incluidos
Los algoritmos implementados en esta herramienta son los siguientes:
- Quick Sort
- Bubble Sort
- Heap Sort
- Merge Sort
- Selection Sort
- Insertion Sort

## Modo de ejecución
La herramienta ofrece dos modos de ejecución diseñados para adaptarse a diferentes necesidades de aprendizaje y demostración:

### 1. Modo manual
En este modo, el usuario tiene control total sobre el progreso del algoritmo. Puede avanzar paso a paso presionando un botón para cada iteración, lo que le permite observar en detalle cómo se realizan los cambios en el proceso de ordenamiento. Este modo es ideal para entornos educativos, ya que facilita una explicación pausada y detallada de cada paso.

### 2. Modo automático
En este modo, el algoritmo se ejecuta de forma continua y automática sin intervención del usuario. El usuario puede seleccionar la velocidad de ejecución antes de comenzar. Una vez configurado, el proceso se realiza de principio a fin de manera fluida.

## Parámetros Personalizables
La herramienta permite ajustar los siguientes parámetros para personalizar la experiencia:

### 1. Modo de Generación del Array
El usuario puede elegir cómo generar los datos iniciales del array, lo que permite observar el comportamiento del algoritmo en diferentes escenarios:
  - **Random:** Los valores del array se generan de forma aleatoria.
  - **Nearly sorted:** El array se genera casi completamente ordenado, con algunos valores desordenados.
  - **Reversed:** El array se genera en orden decreciente.
  - **Few unique:**  El array contiene un número limitado de valores que se repiten con frecuencia.
    
### 2. Tamaño del Array
El tamaño del array es configurable mediante un deslizador, con un rango que varía entre 4 y 100 elementos.

### 3. Velocidad de Ejecución
La velocidad del algoritmo en modo automático es ajustable y afecta el retraso entre cada paso del proceso. Las opciones disponibles son:
  - **Velocidad 1:** 500 ms
  - **Velocidad 2:** 250 ms
  - **Velocidad 3: **100 ms
  - **Velocidad 4:** 60 ms
  - **Velocidad 5:** 30 ms

### 4. Temporizador
El usuario puede activar un temporizador que se inicia y finaliza junto con la ejecución del algoritmo, permitiendo medir la duración total del proceso.

## Visualización del Código
El usuario puede visualizar el código fuente del algoritmo seleccionado directamente en la herramienta. Para hacerlo, debe presionar el botón "Código", ubicado en la esquina inferior derecha de la sección de configuración.

### Funcionalidades Disponibles en la Vista de Código
Una vez presionado el botón, se abre una ventana modal en el centro de la pantalla que contiene el código realizado en Python correspondiente al algoritmo seleccionado.

El usuario tiene la posibilidad de:
- **Copiar el código:** Un botón ubicado en la esquina superior derecha permite copiar el código al portapapeles de forma rápida.
- **Cambiar el theme:** El usuario puede alternar entre los modos de visualización "Light Theme" y "Dark Theme" según sus preferencias visuales.
