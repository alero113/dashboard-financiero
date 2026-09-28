# Dashboard financiero personal

Sitio estático compuesto por un único archivo `index.html`.

## Publicación en Render

1. Crear un repositorio nuevo en GitHub.
2. Subir `index.html` a la raíz del repositorio.
3. En Render seleccionar **New > Static Site**.
4. Conectar el repositorio.
5. Configurar:
   - Branch: `main`
   - Build Command: dejar vacío
   - Publish Directory: `.`
6. Crear el sitio y abrir la URL terminada en `.onrender.com`.

## Datos

El dashboard consume directamente dos hojas de Google Sheets publicadas como CSV. No utiliza Neon, backend ni base de datos.

## Actualizaciones

Los cambios en Google Sheets se reflejan al actualizar el dashboard. El archivo también intenta refrescar los datos automáticamente cada cinco minutos.
