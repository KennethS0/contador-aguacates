# 🥑 Contador de Aguacates

Aplicación web sencilla para registrar cuántos aguacates se cosechan de cada árbol.

## Funciones

- Registrar una cosecha con **etiqueta del árbol** (opcional), **variedad** (Hass, Lamb Hass o Kahalu) y **cantidad** de aguacates.
- La app recuerda la última variedad elegida.
- Botones `+` / `−` para ajustar la cantidad rápidamente desde el celular.
- Autocompletado de etiquetas ya usadas.
- Editar o eliminar registros.
- Totales: aguacates, registros y árboles etiquetados.
- **Exportar a Excel (.xlsx)** con tres hojas:
  - `Registros`: cada cosecha con su variedad y fecha.
  - `Resumen por árbol`: total por etiqueta y variedad, y total general.
  - `Resumen por variedad`: total de Hass, Lamb Hass y Kahalu.

## Datos

Los datos se guardan en el navegador del dispositivo (`localStorage`). No se envían a ningún servidor,
por lo que cada teléfono/computadora tiene sus propios registros. Exporta a Excel periódicamente como respaldo.

## Publicación

Es un sitio estático (`index.html`) publicado con GitHub Pages desde la rama `main`.
