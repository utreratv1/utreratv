UTRERA TV — PWA

CONTENIDO
- index.html: reproductor a pantalla completa.
- manifest.json: configuración instalable.
- sw.js: caché de la carcasa de la aplicación.
- icons/: iconos de la aplicación.

PUBLICACIÓN EN GITHUB PAGES
1. Crea un repositorio y sube todos los archivos y la carpeta icons.
2. En GitHub, entra en Settings > Pages.
3. En Build and deployment, elige Deploy from a branch.
4. Selecciona la rama principal y la carpeta / (root), y guarda.
5. Abre la dirección HTTPS que proporciona GitHub Pages.

PUBLICACIÓN EN VERCEL
1. Importa el repositorio en Vercel.
2. No necesitas framework ni comando de compilación.
3. Usa la raíz del proyecto como directorio de publicación.

INSTALACIÓN
- Android/Chrome: abre la web publicada y utiliza «Instalar aplicación» o
  «Añadir a pantalla de inicio» en el menú del navegador.
- iPhone/iPad: Safari > Compartir > Añadir a pantalla de inicio.
  iOS no permite que una página web fuerce la instalación con un solo toque.

IMPORTANTE
- La aplicación necesita Internet para recibir la emisión de VDO.Ninja.
- El service worker almacena únicamente los archivos básicos de la web;
  no puede almacenar ni garantizar la disponibilidad del vídeo en directo.
- La reproducción automática depende de las políticas del navegador y del
  dispositivo. Algunos navegadores pueden exigir una interacción del usuario.
- Publica siempre bajo HTTPS para que el service worker y la instalación PWA
  estén disponibles.
