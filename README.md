# Proyecto de Ejercicios y Aplicaciones en Python

## Descripción
Este cuaderno de Google Colab es una guía práctica y exhaustiva sobre conceptos esenciales de Python, desde la manipulación básica de bibliotecas hasta el manejo avanzado de estructuras de datos y excepciones. A través de ejercicios resueltos y situaciones prácticas, el cuaderno busca solidificar la comprensión y aplicación de las herramientas clave en el desarrollo con Python, especialmente útil para el análisis de datos.

## Contenido
El cuaderno está organizado en las siguientes secciones:

### 1. Bibliotecas y Módulos
Exploración de la instalación, importación y uso de diversas bibliotecas y módulos de Python.
*   **Instalación y Gestión:** Uso de `pip` para instalar y actualizar bibliotecas como `matplotlib`. Verificación de versiones.
*   **Importación:** Diferentes formas de importar módulos completos (`import math`) o funciones específicas (`from random import choice`).
*   **Aplicaciones Prácticas:**
    *   Visualización básica de datos con `matplotlib.pyplot` (e.g., gráficos de barras de notas de estudiantes).
    *   Generación de valores aleatorios y selección de elementos con el módulo `random` (`choice`, `randrange`, `sample`), incluyendo la generación de IDs de estudiantes.
    *   Uso de funciones matemáticas como `sqrt` del módulo `math`.
*   **Documentación:** Uso de la función `help()` para entender el funcionamiento de métodos y módulos.

### 2. Funciones
Creación y utilización de funciones, incluyendo funciones incorporadas, personalizadas y anónimas.
*   **Funciones Incorporadas (Built-in Functions):** Aplicación de funciones como `sum()`, `len()`, y `round()` para cálculos comunes (e.g., promedio de notas).
*   **Funciones Personalizadas (`def`):**
    *   Definición de funciones sin y con parámetros.
    *   Funciones que retornan uno o múltiples valores (e.g., promedio y situación del estudiante).
    *   Manejo del alcance de las variables dentro y fuera de las funciones.
    *   Inclusión de `Type Hints` y `Docstrings` para mejorar la legibilidad y la robustez del código.
*   **Funciones Lambda (Anónimas):** Definición de funciones compactas para operaciones sencillas (e.g., incremento de notas, cálculo de promedio ponderado).
*   **Mapeo de Valores:** Uso de `map()` en conjunto con funciones lambda para aplicar transformaciones a colecciones de datos (e.g., conversión de temperaturas Celsius a Fahrenheit).

### 3. Estructuras de Datos Compuestas
Manejo de colecciones de datos anidadas y creación eficiente de estructuras de datos.
*   **Estructuras Anidadas:**
    *   **Lista de Listas:** Organización y manipulación de datos complejos (e.g., separación de nombres y notas de estudiantes, agrupación de notas por estudiante).
    *   **Lista de Tuplas:** Creación y procesamiento de tuplas para almacenar registros (e.g., nombres de estudiantes con IDs generados aleatoriamente). Desempaquetado de tuplas.
*   **List Comprehension:**
    *   Creación concisa de listas a partir de iterables, incluyendo la aplicación de lógica condicional (e.g., cálculo de promedios, filtrado de estudiantes para becas).
    *   Uso de `zip()` para combinar iterables y procesarlos simultáneamente (e.g., combinar nombres y promedios, calcular IMC a partir de alturas y pesos).
*   **Dict Comprehension:**
    *   Creación y modificación eficiente de diccionarios (e.g., organizar registros de estudiantes por categoría, filtrar estudiantes becados).

### 4. Manejo de Excepciones
Estrategias para gestionar errores y asegurar la robustez de las aplicaciones.
*   **Tratamiento de Excepciones (`try...except`):** Captura y gestión de errores comunes como `KeyError`, `TypeError`, y `ValueError` para evitar interrupciones inesperadas del programa.
*   **Cláusulas Adicionales:** Implementación de `else` (código a ejecutar si no hay excepciones) y `finally` (código a ejecutar siempre, con o sin excepción).
*   **Tipos Comunes de Errores:** Ejemplos de `SyntaxError`, `NameError`, `IndexError`, `KeyError`, y `Warning` (con `numpy`).
*   **Generación de Excepciones (`raise`):** Creación de excepciones personalizadas para imponer reglas de negocio o validaciones específicas en funciones (e.g., limitar el número de notas en un cálculo de promedio).
