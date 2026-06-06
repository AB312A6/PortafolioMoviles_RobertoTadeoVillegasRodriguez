# 📊 Proyecto 1: Análisis de Datos con Dart

---

## 🎯 1. Objetivo del Proyecto
Desarrollar e implementar una aplicación interactiva de interfaz de línea de comandos (CLI) estructurada en **Dart**. El sistema está diseñado para procesar de manera automatizada colecciones de datos estructuradas bajo el formato estándar **JSON**, permitiendo la ejecución de búsquedas, filtrados dinámicos y cálculos estadísticos con un alto nivel de eficiencia computacional.

---

## 💡 2. Problema que Resuelve
Esta herramienta mitiga la ineficiencia y el margen de error asociados al procesamiento manual de grandes volúmenes de registros de personal (tales como nombres, edades y salarios). En lugar de calcular promedios y buscar perfiles de manera tradicional, el sistema centraliza la manipulación de la información a través de un archivo local, generando reportes analíticos de forma instantánea sin la necesidad de consumir recursos en una interfaz gráfica (GUI) pesada.

---

## 🧰 3. Tecnologías Utilizadas

| Herramienta / SDK | Categoría | Propósito en el Desarrollo |
| :--- | :--- | :--- |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" alt="vscode" width="16" height="16"/> **Visual Studio Code** | Entorno de Desarrollo (IDE) | Plataforma principal utilizada para la codificación, formateo estricto y ejecución del entorno de consola. |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dart/dart-original.svg" alt="dart" width="16" height="16"/> **Dart (Console SDK)** | Lenguaje de Programación | Núcleo lógico del sistema encargado de orquestar el flujo de la aplicación y el procesamiento de datos. |
| 🗄️ **`dart:io`** | Librería Nativa | Módulo de entrada/salida implementado para la manipulación directa y persistencia de archivos en el sistema local. |
| 🔄 **`dart:convert`** | Librería Nativa | Utilidad de codificación encargada de la serialización y deserialización de flujos de texto plano hacia objetos JSON y viceversa. |

---

## 🧠 4. Conceptos Aplicados

* **Programación Orientada a Objetos (POO):** Abstracción de entidades del mundo real y modelado de datos estructurado mediante el uso de clases fuertemente tipadas.
* **Constructores de Tipo Factoría (`factory`):** Implementación de métodos seguros de deserialización para mapear diccionarios de datos (`Map<String, dynamic>`) directamente hacia instancias de clase validadas.
* **Programación Funcional:** Manipulación limpia y optimizada de colecciones a través de la aplicación de métodos iterativos avanzados como `.map()`, `.where()` y `.fold()`.
* **Null Safety Estricto:** Aplicación de operadores de coalescencia nula (`??`) y validaciones de tipo en tiempo de compilación para garantizar la estabilidad del software y evitar excepciones en tiempo de ejecución.

---

## 📸 5. Evidencias de Funcionamiento

A continuación se documenta la secuencia operativa del sistema interactivo a través de la terminal:

1. **Carga de Archivo JSON:** Evidencia de la lectura inicial y validación exitosa de la base de datos local al arrancar el script.
2. **Menú de la Aplicación:** Despliegue de la interfaz de texto con todas las opciones operativas disponibles para el usuario.
3. **Mostrar Registros:** Impresión iterativa y formateada en consola de la totalidad de perfiles extraídos del documento JSON.
4. **Búsqueda de Usuario:** Demostración práctica de los algoritmos de filtrado individual a partir del ingreso de un criterio de búsqueda (nombre).
5. **Cálculo de Estadísticas:** Ejecución del módulo matemático interno que procesa promedios salariales y evalúa rangos de edades.
6. **Creación de Resumen:** Confirmación del sistema indicando que las métricas analizadas fueron recopiladas y empaquetadas con éxito.
7. **Ubicación del Reporte:** Captura de la ruta del directorio local que demuestra dónde se almacenó físicamente el nuevo documento generado.
8. **Estructura del Resumen:** Vista interna del archivo de salida (`resumen_analisis.json`) mostrando el formato final de las métricas.
9. **Finalización del Programa:** Rutina de salida que cierra el flujo de ejecución de manera segura y libera los recursos de la consola.

---
---

## 💭 6. Reflexión Personal

* **¿Qué aprendí? (Perspectiva Técnica):** Comprendí a fondo la arquitectura asíncrona que ofrece Dart para la lectura de archivos y dimensioné el poder práctico de los constructores `factory`. Estos me permitieron transformar datos planos y volátiles (provenientes de un JSON) en objetos fuertemente tipados, garantizando que el compilador trabaje con estructuras seguras.
* **¿Qué fue difícil? (Desafíos Encontrados):** El mayor obstáculo consistió en la correcta implementación lógica de los métodos funcionales, en especial `.fold()`, para iterar y calcular promedios acumulados. Paralelamente, representó un reto estructurar el código para asegurar que las operaciones asíncronas (`async`/`await`) de lectura y escritura no bloquearan el ciclo de vida del menú interactivo.
* **¿Qué mejoraría? (Visión de Futuro):** En una próxima versión, desarrollaría un módulo de escritura bidireccional que faculte al usuario para añadir o dar de alta nuevos registros de personal directamente desde la consola, inyectándolos en el archivo `datos.json` sin tener que recurrir a la edición manual del documento de texto.

## 🚀 7. Instrucciones de Ejecución

Sigue estas directrices para desplegar y probar la herramienta en tu entorno local.

### 7.1 Requisitos Previos
Asegúrate de tener el SDK de Dart instalado y configurado en las variables de entorno de tu computador. Puedes verificarlo ejecutando:
```bash
dart --version
