# Juegos de memoria para tablet — app lista para instalar

Siete juegos sencillos de estimulación cognitiva para tablet Android, pensados para personas mayores:
botones enormes, sin prisas ni penalizaciones, siempre en horizontal y con un icono de acceso por cada juego.

| Juego | En qué consiste |
|---|---|
| **Colores** | Repetir secuencias de colores, a velocidad constante. |
| **Sumas y restas** | Cuentas en vertical, como en el cuaderno, con 4 niveles. |
| **Los tubos** | Ordenar líquidos de colores por tubos. |
| **Las torres** | Torres de Hanói, de 2 a 6 discos. |
| **Mis fotos** | Fotos con sus nombres y, a veces, una pregunta sencilla. |
| **Las parejas** | Buscar parejas de fichas, al estilo mahjong. |
| **Mi música** | Reproductor de los vídeos que haya en la tablet. |

## Descargar e instalar

1. Descarga el APK: [`apk/Juegos_publica_v10.0.apk`](apk/Juegos_publica_v10.0.apk) (unos 70 KB).
2. Ábrelo en la tablet. Android pedirá permiso para instalar apps desde esa aplicación: acéptalo.
   Si aparece un aviso de Play Protect, elige «Instalar de todos modos» (es una app sin publicar en Google Play).
3. Aparecerán siete iconos nuevos. La primera vez, Android muestra un aviso de pantalla completa: pulsa «Entendido».

Requisitos: Android 7.0 o superior. Los juegos funcionan sin internet. La app declara el permiso de red, pero en esta versión no lo usa: el botón «Actualizar» (que trae fotos y vídeos de una carpeta de Google Drive) solo está en la versión familiar, que lleva su propia carpeta configurada.

**Comprobar la descarga** — huella SHA-256 del APK en [`apk/SHA256SUMS.txt`](apk/SHA256SUMS.txt) y del certificado de firma:
`6E:94:6F:B1:86:D4:14:53:BB:B0:76:F8:78:93:F3:DA:CA:53:B0:26:C2:91:61:45:FC:28:5E:D0:E0:75:8B:7E`

## Esta es la versión sin datos personales

- **Mis fotos** aparece vacío: esta versión no incluye ninguna foto.
- **Mi música** reproduce los vídeos (`mp4`, `m4v`, `webm`, `mkv`, `3gp`, `mov`) que copies en la carpeta
  `Android/data/es.lucia.juegos/files/videos` de la tablet. Lo más compatible es MP4 con vídeo H.264 y audio AAC.

## Contenido del repositorio

- `apk/` — el APK firmado y su huella.
- `web-minimizada/` — la parte web de los juegos tal y como va empaquetada en el APK: HTML y CSS minimizados y
  JavaScript ofuscado. No está pensada para editarse.

El código fuente no es público. Todos los derechos reservados.
