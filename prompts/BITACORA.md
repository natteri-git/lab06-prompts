# Bitacora de prompts 
Laboratorio 06: Fundamentos de Ingenieria de Prompts. 
Herramienta de IA usada: (Chatgpt) 
## Ejercicio 2: Tokens y ventana de contexto 
| Texto | Caracteres | Tokens |
|-------|------------|--------|
| Los estudiantes programan en Java. | 36 | 8 |
| The students program in Java. | 31 | 7 |
| desafortunadamente | 18 | 4 |

## Ejercicio 3: Temperatura

| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|-------------|----------------|----------------------------|
| 0           | 100,0%         | BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec |
| 0.5         | 65,3%          | BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec |
| 1           | 44,5%          | BiblioTec, LibroYa, LibroYa, PrestaLibro, PaginaLibre |
| 1.8         | 32,2%          | BiblioTec, BiblioTec, BiblioTec, BiblioTec, LibroYa |

Al subir la temperatura, BiblioTec se vuelve menos dominante y aumenta la variedad de nombres elegidos.

El simulador nunca inventa un nombre nuevo porque solo puede elegir entre las opciones que ya están en la lista.
## Ejercicio 4: Prompt vago vs estructurado 
| Criterio | Prompt vago | Prompt estructurado |
|----------|-------------|---------------------|
| Menciona el objetivo del sistema | ✓ | ✓ |
| Menciona a los usuarios principales | ✗ | ✓ |
| Tiene exactamente 3 funcionalidades | ✗ | ✓ |
| Está en 3 párrafos | ✗ | ✓ |
| Lo usaría en un informe real | ✓ | ✓ |
## Ejercicio 5: Anatomia de un prompt 
| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol | Actua como desarrollador Java. |
| Instruccion | Crea un programa en Java para gestionar los productos de una tienda usando una clase Producto. |
| Contexto | Los atributos de la clase Producto son codigo, nombre, precio y stock. |
| Ejemplo | getPrecio(), setPrecio(double precio). |
| Formato | Explica primero la estructura de la clase y luego presenta el codigo Java. |
## Ejercicio 6: Del prompt basico al profesional
| **Qué revisar**                                       | **Cumple (Sí / No)** |
|-------------------------------------------------------|----------------------|
| ¿Está escrito en Java y usa Swing?                   | Sí                   |
| ¿Pide correo y contraseña?                            | Sí                   |
| ¿Explica el funcionamiento antes o después del código? | Sí                   |
| ¿El código está organizado en clases?                 | Sí                   |
| ¿Valida los datos que ingresa el usuario?             | Sí                   |

```text
Prompt profesional:

Actua como desarrollador Java. Crea un ejemplo de login para una aplicacion de escritorio utilizando Swing. El usuario debe ingresar correo y contrasena. Explica brevemente el funcionamiento y presenta el codigo organizado por clases.

Mejora:

Mejora el codigo anterior con estas restricciones: no uses librerias externas, valida que el correo contenga @ y que la contrasena tenga al menos 8 caracteres, y muestra los mensajes con JOptionPane.
```





