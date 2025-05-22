
# Formulario Sensor - Envío de datos JSON

Este es un formulario HTML que permite enviar datos en formato JSON a una API desplegada en Render.

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub.
2. Sube los archivos `index.html` y `README.md`.
3. Ve a **Settings > Pages**.
4. En la sección "Source", selecciona la rama principal (`main` o `master`) y la carpeta raíz (`/root`).
5. Espera unos segundos y accede al enlace público que GitHub te dará.

## ¿Qué hace este formulario?

- Toma 4 campos: sensor_id, temperatura, vibración, estado.
- Reemplaza comas por puntos para valores numéricos.
- Envía los datos por `fetch` como JSON.
- Muestra la respuesta del servidor.
