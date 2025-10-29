# Práctica de Java Streams

Este repositorio contiene un proyecto de ejercicio para practicar la manipulación de colecciones en Java utilizando la API de Streams (Java 8+).

El objetivo es demostrar diversas operaciones funcionales sobre un conjunto de datos de ejemplo.

## Clases de Entidad

El proyecto utiliza las siguientes clases modelo (POJOs) para simular datos reales:

* `Alumno`
* `Producto`
* `Libro`
* `Empleado`

Todas las entidades están construidas con **Lombok** (`@Getter`, `@Setter`, `@ToString`, `@Builder`) para reducir el código repetitivo.

## Conceptos Aplicados en `Main.java`

La clase `Main` contiene todos los ejemplos prácticos. Ejecuta una serie de operaciones en listas de objetos, mostrando los resultados por consola.

Los principales temas cubiertos son:

* **Pipelines de Streams**: Encadenamiento de métodos.
* **Operaciones Intermedias**: `filter()`, `map()`, `sorted()`.
* **Operaciones Terminales**:
    * `collect()` (para agrupar en `List`, `Set`, `Map`).
    * `average()`, `sum()`, `max()`, `min()` para cálculos.
* **Agrupamiento Avanzado**: `Collectors.groupingBy()` para clasificar datos.
* **Ordenamiento**: Uso de `Comparator` para lógicas de ordenamiento personalizadas.
* **Manejo de Nulos**: Uso de `Optional` para representar valores que pueden estar ausentes.

## Requisitos

* JDK 17 o superior.
* Plugin de Lombok configurado en el IDE (necesario para que el IDE compile el proyecto correctamente).

## Ejecución

1.  Clonar el repositorio.
2.  Abrir el proyecto en un IDE (como IntelliJ IDEA, Eclipse, o VS Code).
3.  Ejecutar la clase `Main.java`.
4.  Observar los resultados de las operaciones en la consola.
