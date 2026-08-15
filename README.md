# 🛸 Armador de equipo

Ejercicio de clase: una app para armar un equipo de personajes usando la [Rick and Morty API](https://rickandmortyapi.com/) (pública, sin API key). Construida con **Bootstrap 5**, **jQuery** y **AJAX**.

## 🔗 Demo en vivo

👉 **[https://aleosorio22.github.io/armador-equipo/](https://aleosorio22.github.io/armador-equipo/)**

## ¿Qué hace?

- **Catálogo** — carga una lista de personajes desde la API una sola vez al abrir la página y los guarda en memoria.
- **Armá tu equipo** — seleccioná personajes con checkboxes y agregalos a tu equipo como cards.
- **Ver detalle** — cada card abre un modal con la información del personaje (estado, especie, origen y última ubicación).
- **Sin duplicados** — no permite agregar dos veces al mismo personaje.
- **AJAX encadenado** — al abrir el detalle hace una segunda llamada a la API para traer el tipo y la dimensión del planeta de origen.

## 🛠️ Tecnologías

- HTML5
- [Bootstrap 5.3](https://getbootstrap.com/) — layout, cards, navbar y modales
- [jQuery 3.7](https://jquery.com/) — manipulación del DOM y peticiones AJAX
- [Rick and Morty API](https://rickandmortyapi.com/) — fuente de datos

## 🚀 Cómo correrlo localmente

No necesita instalación ni servidor. Solo abrí el archivo `index.html` en el navegador:

```bash
git clone https://github.com/aleosorio22/armador-equipo.git
cd armador-equipo
open index.html
```

## 📚 Conceptos practicados

- Cargar datos con `$.ajax` y el patrón spinner → petición → pintar/error.
- Delegación de eventos para elementos creados dinámicamente.
- La API nativa de modales de Bootstrap 5 (`new bootstrap.Modal(...)`).
- Encadenar dos llamadas AJAX donde la segunda depende del resultado de la primera.