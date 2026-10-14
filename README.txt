VIRELO V5.2 — VERSION DE PRUEBA

Qué incluye
- Página minimalista orientada a creadores de contenido: demostración visual del original y tres salidas, sin sección de pasos, FAQ ni footer redundante.
- Un video por operación.
- Tres salidas por defecto: vertical 1080x1920, cuadrada 1080x1080 y horizontal 1920x1080. También se puede crear una sola.
- Vista previa estática de las tres composiciones a partir de un fotograma del video seleccionado; se actualiza mientras cambia el encuadre.
- Sección «Elegir encuadre»: arrastrar dentro del cuadro mueve la selección; arrastrar sus esquinas cambia el área visible. «Restablecer» vuelve al video completo.
- El área seleccionada se utiliza para el contenido principal y el fondo difuminado en las tres salidas.
- Nombre opcional para los archivos. Si se deja vacío, usa el nombre del original; añade -vertical, -cuadrado o -horizontal.
- Descargas MP4 individuales y ZIP conjunto.
- Botón para quitar el video seleccionado; cancelación con confirmación.
- Intenta mantener la pantalla encendida durante el procesamiento cuando el navegador lo permite.

Límites actuales
- Máximo 3 min 30 s por video (límite provisional).
- Salidas fijadas a 1080p / 1080x1080; no exporta 4K.
- La exportación codifica video H.264 y audio AAC cuando existe audio compatible.
- Requiere conexión para descargar FFmpeg.wasm y JSZip si no están en caché.
- La vista previa es una imagen estática del encuadre, no una previsualización del movimiento o de la compresión final.
- El rendimiento depende del navegador, dispositivo, duración, códec, resolución y memoria disponible.
- No se ha validado una conversión real en navegador desde este empaquetado. Prueba con un video corto antes de reemplazar la versión anterior.

Acceso
Se mantiene la clave que usaba V5.1. La comprobación local es una barrera básica, no un sistema de licencias seguro.

Publicación
Descomprime el ZIP y sube el contenido de la carpeta Virelo-V5 a la raíz del repositorio de GitHub Pages. Mantén juntos index.html, style.css, app.js y hero-skate.webp.

Licencias
La aplicación usa FFmpeg.wasm y descarga componentes desde CDN. Revisa y cumple las licencias de los componentes antes de distribuir comercialmente; FFmpeg.wasm/core está publicado bajo GPL-2.0-or-later.
