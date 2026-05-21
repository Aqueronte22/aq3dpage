# AQ3D site

Este repositorio está preparado para subirse directamente a Cloudflare Pages como sitio estático.

## Archivos

- `index.html`: web principal
- `_headers`: cabeceras recomendadas para Cloudflare Pages
- `_redirects`: redirección básica
- `assets/`: carpeta para imágenes futuras

## Configuración en Cloudflare Pages

- **Framework preset**: None
- **Build command**: dejar vacío
- **Build output directory**: `/` si estos archivos están en la raíz del repositorio
- Si decides meterlos dentro de una carpeta, usa esa carpeta como output directory

## Motivo del error anterior

Cloudflare no encontró una carpeta con archivos estáticos en la ruta configurada. Eso suele pasar cuando:

- el output directory apunta a una carpeta incorrecta,
- el archivo principal no se llama `index.html`,
- o los archivos no están en la raíz esperada.

Con esta estructura, puedes subir el contenido directamente al repo y desplegarlo como sitio estático.
