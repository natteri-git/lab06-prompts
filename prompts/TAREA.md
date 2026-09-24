# Tarea: Mi prompt profesional

## Funcionalidad elegida

Cálculo de notas de un estudiante en Java.

## Version 1: prompt basico

```text
Crea un programa en Java para calcular las notas de un estudiante.
```

### Qué cambié

Esta primera versión es un prompt básico y general. Solamente indica que se debe crear un programa para calcular notas.

### Por qué lo cambié

El prompt no especifica qué datos debe recibir el programa, cómo debe calcular las notas ni cómo debe presentar el resultado.

### Qué mejoró en la respuesta

La respuesta permite obtener una solución inicial, pero puede ser diferente de lo esperado porque la instrucción es demasiado general.

## Version 2

```text
Actua como desarrollador Java. Crea un programa para calcular el promedio de un estudiante a partir de tres notas. El programa debe mostrar las tres notas, el promedio y si el estudiante aprobo o reprobo. Usa una clase Estudiante.
```
### Qué cambié

Agregué un rol, indiqué que se utilizarían tres notas, definí el cálculo del promedio y establecí que se debe mostrar si el estudiante aprobó o reprobó.

### Por qué lo cambié

La primera versión no especificaba qué información debía manejar el programa ni qué resultado debía entregar.

### Qué mejoró en la respuesta

La respuesta es más específica porque el programa ahora tiene una clase definida, recibe tres notas, calcula un promedio y determina el estado del estudiante.

## Version 3: prompt final

```text
Actua como desarrollador Java. Crea un programa de consola para calcular el promedio final de un estudiante.

El sistema debe utilizar una clase Estudiante con los atributos nombre, nota1, nota2 y nota3. El promedio debe calcularse sumando las tres notas y dividiendo el resultado entre 3. El estudiante aprueba cuando el promedio es mayor o igual a 6.0; de lo contrario, reprueba.

Utiliza como ejemplo el estudiante "Ana" con las notas 8.0, 7.0 y 9.0, cuyo promedio esperado es 8.0 y cuyo resultado es "Aprobado".

No uses librerías externas y utiliza únicamente clases estándar de Java. Organiza el código en una clase Estudiante y una clase Main.

Presenta primero una breve explicación de la solución y después el código Java completo dentro de un bloque de código.
```
### Qué cambié

Agregué información específica sobre la estructura de la clase, la fórmula del promedio, la condición para aprobar, un ejemplo de entrada y resultado, una restricción sobre las librerías y el formato en que debe presentarse la respuesta.

### Por qué lo cambié

La segunda versión todavía dejaba algunos detalles abiertos, como los atributos de la clase, la fórmula exacta, la nota mínima para aprobar, un ejemplo concreto y la organización final del código.

### Qué mejoró en la respuesta

La respuesta final es más precisa y predecible. La IA tiene información suficiente para generar un programa que cumpla con los requisitos indicados y puede comprobar el resultado utilizando el ejemplo proporcionado.

## Componentes del prompt final

| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol | Actua como desarrollador Java. |
| Instrucción | Crea un programa de consola para calcular el promedio final de un estudiante. |
| Contexto | El sistema debe utilizar una clase Estudiante con los atributos nombre, nota1, nota2 y nota3. El promedio se calcula con las tres notas y el estudiante aprueba con un promedio mayor o igual a 6.0. |
| Ejemplo | Utiliza como ejemplo el estudiante "Ana" con las notas 8.0, 7.0 y 9.0, cuyo promedio esperado es 8.0 y cuyo resultado es "Aprobado". |
| Formato | Presenta primero una breve explicación de la solución y después el código Java completo dentro de un bloque de código. |

### Restricción

No uses librerías externas y utiliza únicamente clases estándar de Java.

## Evaluacion del resultado

| Criterio | Cumple (Sí / No) |
|----------|-------------------|
| ¿Está escrito en Java? | Sí |
| ¿Utiliza una clase Estudiante? | Sí |
| ¿Calcula correctamente el promedio de tres notas? | Sí |
| ¿Indica si el estudiante aprueba o reprueba? | Sí |
| ¿Incluye el ejemplo solicitado? | Sí |

## Errores que evite

### 1. Ser demasiado general

La primera versión solamente indicaba que se debía crear un programa para calcular notas. En las siguientes versiones agregué los datos, las reglas de cálculo, la condición de aprobación y la estructura de clases para evitar respuestas demasiado generales.

### 2. No indicar el formato

En la versión final indiqué que primero debía presentarse una breve explicación y después el código Java completo dentro de un bloque de código. De esta manera, la respuesta tiene una estructura clara y fácil de revisar.
