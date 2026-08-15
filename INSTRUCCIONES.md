# Ejercicio de clase — Armador de equipo (Bootstrap 5 + jQuery + AJAX)

**Se empieza y se termina en esta clase.** Trabajo individual o en pares.

## Qué ya funciona (no lo toques, es tu ejemplo de referencia)

- Navbar responsiva con botón de colapso en móvil.
- El catálogo de personajes: al abrir `index.html`, un `$.ajax` trae
  personajes desde la [Rick and Morty API](https://rickandmortyapi.com/)
  y los pinta como checkboxes con miniatura.
- El modal de detalle: la estructura HTML ya está, pero **vacía** —
  el contenido lo llena tu código en el TODO 2.

## Qué tenés que completar

Todo el trabajo va dentro del `<script>` al final de `index.html`, en
los bloques marcados `TODO`.

### Obligatorio para considerar el ejercicio terminado

1. **TODO 1** — Al presionar "Agregar al equipo", tomar los personajes
   marcados en el catálogo y renderizar una card de Bootstrap por cada
   uno dentro de `#mi-equipo` (la página principal, no el modal).
2. **TODO 2** — Que el botón "Ver detalle" de cada card abra el modal
   con los datos completos de ese personaje.

### Para casa 

3. **TODO 3** — No permitir agregar dos veces al mismo personaje;
   agregar un botón para quitarlo del equipo.
4. **TODO 4** — En el modal, hacer una segunda llamada AJAX a
   `personaje.origin.url` para mostrar el tipo de planeta de origen
   (AJAX encadenado).

## Pistas ya escritas en el código

- Cómo leer los checkboxes marcados.
- Dónde guardar los datos de cada personaje para no volver a pedirlos.
- El problema típico del TODO 2: Bootstrap 5 no soporta
  `$('#modal').modal('show')` (esa sintaxis es de Bootstrap 4) — hay
  que usar `new bootstrap.Modal(...)`.

## Cómo se evalúa 

- ✅ Termina con TODO 1 y TODO 2 funcionando.
- 🌟 Para casa: TODO 3 o TODO 4.
- Se puede pedir en el momento que expliquen una línea de su propio
  código 
