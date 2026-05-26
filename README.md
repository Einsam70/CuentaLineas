# 📊 TextMetrika — Análisis y Limpieza de Archivos

[![Licencia: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-Pure-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-Pure-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Pure-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![Privacidad](https://img.shields.io/badge/privacy-100%25%20Local-orange)](https://developer.mozilla.org/en-US/docs/Web/Privacy)

**TextMetrika** es una utilidad web portable ideada para el análisis estático, curación y limpieza de archivos de texto y código fuente. Todo el procesamiento ocurre de manera **100% local en tu navegador** mediante la API `FileReader`, lo que garantiza una privacidad absoluta al no subir jamás tus documentos a ningún servidor externo.

---

## 🎯 Características Principales

* **📁 Soporte Multi-archivo & Drag-and-Drop:** Arrastra múltiples archivos simultáneamente a la zona interactiva o utiliza el explorador clásico.
* **🔍 Métricas Detalladas:** Obtén de un vistazo el tamaño del documento, líneas totales, líneas filtradas y conteo real de palabras.
* **⚡ Filtros Inteligentes para Código:** Opción de ignorar líneas vacías o comentarios de sintaxis estándar (`//` y `#`), ideal para auditar código fuente limpio.
* **🧹 Herramientas de Curación Quirúrgica:**
  * **Individual:** Descarga cualquier archivo de la lista aplicando de forma aislada los filtros establecidos, eliminando líneas duplicadas o reordenándolo alfabéticamente.
  * **Masiva (Consolidación):** Une el contenido de todos los archivos procesados en un único documento limpio, sin duplicados o completamente ordenado de la A a la Z.

---

## 🛠️ Tecnologías Utilizadas

Para garantizar la máxima velocidad, portabilidad y ligereza, el proyecto ha sido desarrollado utilizando tecnologías web nativas, sin dependencias ni librerías externas pesadas:
* **HTML5** (Estructura semántica y API de arrastrar y soltar)
* **CSS3** (Diseño limpio, responsivo y adaptado al esquema de color del sistema)
* **Vanilla JavaScript** (Lectura asíncrona de archivos mediante `Promises` y manipulación de texto en memoria)

---

## 🚀 Cómo Utilizar

Al ser una aplicación portable, no requiere instalación ni un entorno de servidor local (`Node.js`, `Apache`, etc.):

1. Descarga o clona este repositorio.
2. Abre el archivo `index.html` en cualquier navegador moderno (Chrome, Firefox, Edge, Safari).
3. ¡Listo! Ya puedes empezar a arrastrar tus archivos `.txt`, `.csv`, `.js`, `.py`, `.md` o `.html` para procesarlos al instante.

![Captura de pantalla de TextMetrika](/screenshots/TexMetrika.png)

---

## 📝 Ejemplos de Casos de Uso

* **Desarrollo de Software:** Limpiar comentarios temporales y líneas en blanco de scripts antes de su distribución o cálculo de métricas de código bruto.
* **Gestión de Diccionarios y Listas:** Unificar múltiples listas de palabras, eliminar registros duplicados de manera fulminante y ordenarlas alfabéticamente de la A a la Z en segundos.
* **Auditoría de Datos:** Analizar rápidamente el tamaño y volumen de palabras de archivos estructurados planos (como logs o ficheros `.csv`).

---

## 📌 Próximas Mejoras (Roadmap)

- [ ] Soporte multilingüe (Selector de idiomas)
- [ ] Conmutador de **Modo Oscuro** automático/manual
- [ ] Soporte extendido para bloques de comentarios multilínea (`/* ... */`)
- [ ] Filtro de visualización interactivo en la tabla por extensión de archivo

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Siéntete libre de clonarlo, modificarlo y adaptarlo a tus necesidades.