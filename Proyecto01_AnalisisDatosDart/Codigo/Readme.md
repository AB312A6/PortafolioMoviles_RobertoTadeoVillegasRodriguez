# 📊 Proyecto 1: Análisis de Datos con Dart

---

## 🎯 1. Objetivo del Proyecto
El propósito de esta solución es diseñar e implementar una aplicación de consola interactiva (CLI) construida con **Dart**. El sistema está optimizado para la lectura, procesamiento masivo y análisis estadístico automatizado de colecciones de datos estructuradas bajo el formato estándar **JSON**, permitiendo realizar búsquedas complejas y filtrados de información de manera ágil y eficiente.

---

## 💡 2. Problema que Resuelve
En entornos administrativos, el manejo y procesamiento manual de volúmenes considerables de registros de personal (tales como nombres, edades o nóminas) suele ser propenso a errores y requiere demasiado tiempo. 

Este software mitiga esa problemática al centralizar la manipulación de la información mediante un archivo local. El sistema realiza cálculos analíticos al instante y genera reportes consolidados sin la necesidad de desplegar una interfaz gráfica (GUI) robusta o pesada, optimizando así el uso de recursos de la máquina.

---

## 🧰 3. Tecnologías Utilizadas

| Componente | Tipo / Herramienta | Aplicación en el Proyecto |
| :--- | :--- | :--- |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" alt="vscode" width="16" height="16"/> **Visual Studio Code** | Entorno de Desarrollo | IDE principal utilizado para la codificación, depuración de flujos y ejecución del entorno de comandos. |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dart/dart-original.svg" alt="dart" width="16" height="16"/> **Dart (Console SDK)** | Lenguaje de Programación | Núcleo tecnológico y motor lógico encargado de estructurar todo el ciclo de vida del sistema. |
| 🗄️ **`dart:io`** | Librería Nativa | Módulo especializado en la gestión de flujos de entrada/salida para la lectura y persistencia de archivos en el almacenamiento local. |
| 🔄 **`dart:convert`** | Librería Nativa | Componente encargado de la codificación y decodificación estricta de cadenas de texto plano hacia estructuras de objetos JSON. |

---

## 🧠 4. Conceptos Aplicados

* **Programación Orientada a Objetos (POO):** Abstracción de entidades del mundo real mediante clases fuertemente tipadas para un modelado de datos más limpio y escalable.
* **Constructores de Tipo Factoría (`factory`):** Implementación de métodos avanzados de deserialización para transformar mapas clave-valor (`Map<String, dynamic>`) en instancias seguras de objetos de manera controlada.
* **Programación Funcional:** Manipulación declarativa y optimizada de colecciones de datos a través de combinadores nativos como `.map()`, `.where()` y `.fold()`.
* **Null Safety Estricto:** Mitigación de excepciones en tiempo de ejecución mediante la validación estricta de tipos de datos y el uso del operador de coalescencia nula (`??`).

---

## 📸 5. Evidencias de Funcionamiento

A continuación, se detalla la secuencia de ejecución de la herramienta interactiva en la terminal:

1. **Carga de Archivo JSON:** Validación visual que confirma la lectura exitosa de la base de datos local al inicializar la aplicación.
2. **Menú de la Aplicación:** Despliegue de la interfaz de consola interactiva con las diferentes operaciones disponibles.
3. **Mostrar Registros:** Impresión estructurada y formateada en columnas de todos los perfiles recuperados.
4. **Búsqueda de Usuario:** Demostración del comportamiento de los filtros algorítmicos al ingresar un criterio de búsqueda por nombre específico.
5. **Cálculo de Estadísticas:** Procesamiento matemático en tiempo real encargado de computar promedios salariales y rangos de edad.
6. **Creación de Resumen:** Confirmación en consola que valida la correcta compilación de métricas finales.
7. **Ubicación del Reporte:** Registro visual que muestra el destino exacto del nuevo archivo generado dentro del directorio.
8. **Estructura del Resumen:** Vista interna del archivo `resumen_analisis.json` con los indicadores analíticos listos para su uso.
9. **Finalización del Programa:** Rutina de cierre formal que libera la consola de comandos de forma segura.

> 💡 *Nota: Puedes adjuntar tus capturas de pantalla correspondientes debajo de cada punto utilizando etiquetas Markdown tradicionales: `![Texto Alternativo](Ruta_De_La_Imagen.png)`.*

---

## 🚀 6. Instrucciones de Ejecución

Para inicializar este script en tu entorno local, sigue estas directrices:

1. Asegúrate de contar con el entorno de ejecución de Dart instalado en tu sistema:
```bash
   dart --version
