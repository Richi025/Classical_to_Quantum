# De lo Clásico a lo Cuántico.

Esta biblioteca de Python proporciona funciones para realizar simulaciones de varios experimentos cuánticos. Además, incluye una biblioteca de operaciones con números complejos que permite el manejo de números complejos y, por lo tanto, facilita la implementación de estas simulaciones.
## Operaciones(Simulaciones) Soportadas en la libreria

La biblioteca incluye las siguientes funciones para operar con vectores y matrices complejas. Los números complejos dentro de cada vector o matriz se representan utilizando el tipo "complex" de la biblioteca numpy de Python, donde la primera parte corresponde a la parte real y la segunda parte a la parte imaginaria.

1. **Magnitud de una matriz de imaginarios:** `final_matrix(matrix)`
2. **Simulacón de un sistema probabilistico clasico:** `sistema_probabilistico(matrix, vectIni, clicks)`
3. **Simulacón de un sistema probabilistico cuantico:** `sistema_probabilistico_quantico(matrix, vectIni, clicks)`
4. **Simulación del experimento de canicas con coeficientes booleanos:** `canicas_booleanas(clicks, booleanMatrix, vectIni)`
4. **Simulación del experimento de multiples rendijas clásico:** `multiple_rendija_clasico(matrix, vectIni, clicks)`
5. **Simulación del experimento de multiples rendijas cuántico:** `multiple_rendija_cuantico(matrix, vectIni, clicks)`
6. **Gráfico de barras que represente las probabilidades en forma de porcentaje de un vector de estado, y además, es posible guardar este gráfico como una imagen en tu ordenador.:** `Diagrama(vector)`

## Uso
Instrucciones:
1. Clona este repositorio en tu máquina local.
2. Abre el proyecto en PyCharm.
3. Importa el módulo de la librería en tus scripts.
4. Utiliza las funciones de para realizar simulaciones de experimentos cuánticos.

## Ejemplo de Uso

```python
import classicalToQuantum as lc

# Experimento canicas booleanas
boolean_Matrix = [[False, False, False, False, False, False], [True, False, False, False, False, True],
                         [True, False, False, False, False, False], [False, False, True, False, False, False],
                         [False, False, False, True, False, False], [False, False, False, False, True, False]]

vect_Ini = [True, False, False, False, False, False]
click = 1
result = lc.canicas_booleanas(click,boolean_Matrix, vect_Ini)
print("Simulacion :",result)
```

## Requisitos

Antes de comenzar con la ejecución de los contenidos de este repositorio, es esencial verificar que Python esté instalado en su computadora, ya que este es el lenguaje en el que se ha desarrollado este repositorio.

1. Dirijase a la página https://www.python.org/downloads/
2. De click en la opción de descarga o al siguiente enlace:
- [PyCharm 3.11](https://www.jetbrains.com/pycharm/)
3. Ejecute el programa que se descarga automáticamente.
4. Complete la instalacion.

## Versión
**Primera Versión**

## Autor
**Jose Ricardo Vasquez Vega**