# CinePlay Android

Proyecto Android inicial con interfaz de catálogo, filtros, búsqueda y favoritos. Los enlaces de cada título abren la ficha externa del proveedor en el navegador.

## Compilar en GitHub Actions
1. Sube todos los archivos a la rama `main` de tu repositorio.
2. Abre la pestaña **Actions**.
3. Selecciona **Build CinePlay APK** y pulsa **Run workflow** (o espera al push).
4. Cuando termine, abre la ejecución y descarga el artefacto **CinePlay-apk**.
5. Dentro encontrarás `app-debug.apk`.

## Importante
- Este es un APK de depuración, apto para instalar manualmente en Android; no es una versión firmada para publicar en Google Play.
- Los enlaces externos no están garantizados como permanentes ni todos han sido verificados desde este proyecto. La legalidad y disponibilidad dependen de la ficha/licencia y del país.
- Los botones abren la ficha externa; no se descargan ni alojan películas dentro de la app.
