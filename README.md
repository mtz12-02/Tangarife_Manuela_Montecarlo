# Simulación del juego Yahtzee con Monte Carlo

# Manuela Tangarife Zapata

## Descripción

Este proyecto consiste en la simulación del juego de dados Yahtzee utilizando Python y el método Monte Carlo. Se desarrolló de manera individual 

El proyecto incluye una versión del juego para dos jugadores y varios experimentos para estudiar la probabilidad de obtener Yahtzee, comparar estrategias de lanzamiento y analizar el efecto de utilizar dados justos y dados cargados.

## Objetivos

- Simular una partida de Yahtzee para dos jugadores.
- Aplicar el método Monte Carlo para estimar probabilidades.
- Comparar estrategias para conseguir cinco dados iguales.
- Observar cómo cambia la probabilidad al modificar la distribución de los dados.
- Relacionar los resultados con la ley de los grandes números.

## Fases del proyecto

### USA

Se implementó una estrategia automática que conserva los dados con la cara más frecuente y vuelve a lanzar los restantes, con un máximo de tres lanzamientos.

### MODIFICA

Se modificó la distribución de los dados para aumentar la probabilidad de obtener un seis y se compararon los resultados con los obtenidos usando dados justos.

### CREA

Se desarrolló un experimento para comparar dos estrategias a partir de una tercia inicial: conservar los dados iguales o volver a lanzar los cinco dados.

## Herramientas utilizadas

- Python
- Google Colab
- Matplotlib
- Biblioteca `random`
- Biblioteca `collections`

## Resultados

Los experimentos permitieron comparar probabilidades estimadas, analizar diferentes estrategias y observar el comportamiento de las simulaciones al aumentar el número de iteraciones.

En la fase CREA, conservar la tercia inicial produjo una mayor probabilidad estimada de obtener Yahtzee que volver a lanzar los cinco dados, tanto con dados justos como con dados cargados.

## Cómo se puede ejecutar el proyecto

1. Abrir el notebook de la actividad en Google Colab.
2. Ejecutar las celdas en orden.
3. Seguir las instrucciones de las celdas para jugar o revisar los experimentos.
4. Consultar las tablas y gráficas para analizar los resultados.
