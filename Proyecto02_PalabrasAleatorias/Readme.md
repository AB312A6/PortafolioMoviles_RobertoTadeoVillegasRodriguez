# 📱 Proyecto 2: Aplicación en Flutter

---

## 🎯 1. Objetivo del Proyecto
El fin de esta práctica es conceptualizar, estructurar y maquetar una aplicación móvil multiplataforma y responsiva empleando las capacidades del framework **Flutter** y el lenguaje **Dart**. El núcleo del proyecto se centra en asimilar el paradigma del diseño declarativo, la composición estéticamente fluida de interfaces de usuario bajo los lineamientos de **Material Design 3**, y la orquestación de un estado global centralizado.

---

## 💡 2. Problema que Resuelve
Esta solución mitiga la necesidad de idear y producir de forma automatizada nomenclaturas o conceptos compuestos a través del emparejamiento aleatorio de términos. Asimismo, contrarresta la volatilidad de la información retenida temporalmente en memoria; para ello, provee un mecanismo interactivo que faculta al usuario para preseleccionar sus opciones predilectas (función de favoritos mediante "Like") y consultar un índice consolidado en tiempo real, garantizando transiciones de pantalla totalmente fluidas y coherentes.

---

## 🧰 3. Tecnologías Utilizadas

| Herramienta / SDK | Categoría | Propósito en el Desarrollo |
| :--- | :--- | :--- |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flutter/flutter-original.svg" alt="flutter" width="16" height="16"/> **Flutter SDK** | Framework de Desarrollo | Kit de herramientas de código abierto de Google diseñado para compilar interfaces nativas de forma nativa desde un único árbol de código base. |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dart/dart-original.svg" alt="dart" width="16" height="16"/> **Dart Language** | Lenguaje de Programación | Lenguaje fuertemente tipado con capacidades optimizadas para el renderizado síncrono de interfaces y reactividad lógica. |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" alt="vscode" width="16" height="16"/> **Visual Studio Code** | Entorno de Desarrollo (IDE) | Editor de código principal optimizado con las extensiones oficiales de Flutter/Dart para análisis estático, formateo y depuración continua. |
| 📦 **`english_words`** | Paquete Externo | Biblioteca de utilidades que provee el diccionario léxico y las reglas gramaticales para las combinaciones aleatorias. |
| 🏗️ **`Provider`** | Gestor de Estado | Solución integral para la inyección de dependencias y la notificación centralizada de mutaciones de datos hacia los widgets del sistema. |

---

## 🧠 4. Conceptos Aplicados

* **Arquitectura Declarativa:** Estructura donde la interfaz de usuario es una consecuencia matemática directa del estado actual de los datos ($UI = f(state)$), reconstruyéndose de forma automática ante cualquier cambio.
* **Manejo de Estado Centralizado (`ChangeNotifier`):** Aislamiento de la lógica de negocio en una clase contenedora independiente que notifica selectivamente a los elementos escuchas (`notifyListeners()`) para actualizar la pantalla de forma eficiente.
* **Layouts Responsivos y Adaptabilidad:** Implementación arquitectónica de componentes avanzados como `NavigationRail` (paneles de navegación laterales orientados a pantallas anchas), `SafeArea` (protección contra intrusiones de hardware como esquinas redondeadas o notches), así como contenedores fluidos tipo `Column`, `Row` y `ListView`.
* **Anidamiento de Widgets Estilizados:** Personalización exhaustiva de componentes pertenecientes a las especificaciones de Material Design 3 (tales como `BigCard`, `ElevatedButton`, `Icon` y animaciones en listas).

---

## 📸 5. Evidencias de Funcionamiento

A continuación, se presenta la secuencia operativa de la aplicación móvil desplegada en el entorno de pruebas:

1. **Inicialización en Modo Debug:** Evidencia del proceso de compilación nativa del árbol de widgets reflejado en el emulador desde el IDE.
2. **Interfaz del Generador:** Vista principal de la pantalla (`GeneratorPage`) que exhibe el diseño declarativo y la tarjeta central que aloja los términos aleatorios.
3. **Mutación de Estado (Botón Next):** Demostración de la reactividad inmediata del sistema al accionar el botón de refresco, alterando el par léxico al instante.
4. **Registro de Favoritos:** Actualización reactiva de los elementos gráficos al pulsar la opción de "Like", sincronizando el icono de corazón con el estado global de datos.
5. **Panel de Favoritos:** Despliegue de la sección independiente (`FavoritesPage`), encargada de listar de manera limpia las opciones seleccionadas junto con un recuento total dinámico.

> 💡 *Nota: Puedes enlazar las capturas multimedia correspondientes a cada punto utilizando la sintaxis de Markdown estándar: `![Descripción de la imagen](Ruta_De_La_Imagen.png)`.*

---

## 🚀 6. Instrucciones de Ejecución y Despliegue

Sigue esta guía detallada para clonar de forma local el repositorio, preparar las dependencias de software y ejecutar el aplicativo en navegadores web o entornos de escritorio compatibles.

### 6.1 Requisitos Previos
* Contar con una instalación íntegra del SDK de Flutter y el motor de Dart debidamente vinculados a las variables de entorno de tu sistema operativo.
* Disponer de Visual Studio Code junto con el ecosistema de extensiones oficiales de Flutter y Dart configuradas.
* Tener habilitado un entorno de ejecución compatible (Google Chrome, Microsoft Edge o soporte nativo para Windows Desktop activado en tu canal de Flutter).

### 6.2 Clonación del Repositorio
Abre tu consola de comandos local e importa el código fuente completo del portafolio académico con la siguiente instrucción:
```bash
git clone [https://github.com/AB312A6/PortafolioMoviles_RobertoTadeoVillegasRodriguez.git](https://github.com/AB312A6/PortafolioMoviles_RobertoTadeoVillegasRodriguez.git)
