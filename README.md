# Portafolio Digital — Laboratorio de Estadísticas para Negocios 1

Sitio estático (HTML/CSS puro, sin build) con la página principal y una página por cada tema del curso.

## Archivos

- `index.html` — página principal (autor, curso, índice de temas)
- `tema1.html` a `tema7.html` — una página por tema, con descripción y botones a las carpetas de Google Drive de las prácticas correspondientes
- `style.css` — estilos compartidos

Puedes reemplazar el recuadro "Espacio para imagen o gráfico del tema" en cada página por una etiqueta `<img src="...">` cuando tengas tus propias imágenes o capturas.

## Cómo subirlo a GitHub (sin usar terminal)

1. Entra a [github.com](https://github.com) e inicia sesión (o crea una cuenta si no tienes).
2. Haz clic en **New repository** (botón verde arriba a la derecha o en github.com/new).
3. Nombra el repositorio, por ejemplo `portafolio-estadisticas`. Puede ser público o privado. No marques "Add a README" (ya tienes uno). Clic en **Create repository**.
4. En la página del repo recién creado, busca el enlace **"uploading an existing file"**.
5. Arrastra los archivos de esta carpeta (`index.html`, `style.css`, `tema1.html`...`tema7.html`, `README.md`) a esa zona.
6. Baja y haz clic en **Commit changes**.

Con eso ya tienes el repo en GitHub, sin necesidad de git ni terminal.

## Cómo desplegarlo en Vercel

1. Entra a [vercel.com](https://vercel.com) e inicia sesión con tu cuenta de GitHub (botón "Continue with GitHub").
2. Clic en **Add New... → Project**.
3. Selecciona el repositorio `portafolio-estadisticas` de la lista (autoriza acceso si te lo pide).
4. Framework Preset: déjalo en **Other** (es HTML estático, no necesita build).
5. Clic en **Deploy**.
6. En un par de minutos Vercel te da una URL pública (algo como `portafolio-estadisticas.vercel.app`) — esa es la que entregas.

Cada vez que subas cambios al repo de GitHub, Vercel vuelve a desplegar automáticamente.
