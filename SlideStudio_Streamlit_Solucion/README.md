# SlideStudio — versión autónoma corregida

## Actualizar una app ya desplegada
Sustituye `SlideStudio_Streamlit/streamlit_app.py` por el nuevo `streamlit_app.py` en esa misma carpeta de tu repositorio. Conserva la ruta existente en Streamlit. No necesitas subir `vendor`, `index.html`, `app.js` ni `styles.css`.

## Instalación nueva
Sube `streamlit_app.py` y `requirements.txt` a la raíz del repositorio. En Streamlit, selecciona la rama `main` y `streamlit_app.py` como Main file path. Se recomienda Python 3.12 o 3.13.

El editor está integrado en Python y no depende de archivos auxiliares ni CDN. La generación de contenido es una estructura basada en plantillas locales (no IA generativa ni investigación en internet). El diseño por imagen se aproxima por colores y composición. La exportación PNG guarda imágenes; PowerPoint conserva los objetos editables. Cambiar colores o estilo no regenera los textos. Cambiar tema, puntos clave, cantidad o tipo con el modo automático activo vuelve a generar las diapositivas; desactívalo para conservar ediciones manuales.

PptxGenJS 4.0.0 se distribuye bajo la licencia MIT incluida en el código y en PptxGenJS-LICENSE.txt.
