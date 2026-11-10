# Clutch (sitio web)

Sitio estático de Clutch. No necesita instalación ni build: es un `index.html` con las fotos en `img/`.

## Cosas que vas a editar
Abre `index.html` y busca el bloque que empieza con `// CONFIGURA AQUÍ`:

- `var WA`: tu número de WhatsApp en formato internacional, sin + ni espacios. Ejemplo: `5255XXXXXXXX`.
- `var PKGS`: nombre, contenido, entrega y precio de cada paquete.
- `var PAY`: los 3 links de pago de Mercado Pago, en el orden de los paquetes. Ejemplo: `["https://mpago.la/aaa","https://mpago.la/bbb","https://mpago.la/ccc"]`.
- `var GALLERY`: las fotos del portafolio. Para agregar una, sube el archivo a `img/` y añade una línea con su ruta y su texto alternativo.

## Publicar (GitHub + Netlify)
1. En GitHub crea un repositorio nuevo llamado `clutch-web`.
2. Sube el contenido de esta carpeta (index.html, img, favicon.svg, netlify.toml).
3. En Netlify: Add new site, Import an existing project, elige GitHub y el repositorio `clutch-web`.
4. Sin comando de build y con directorio de publicación `.` (punto). Deploy.
5. Cada cambio que guardes en GitHub se publica solo.

## Dominio
En Netlify, Domain management, Add a domain, y sigue las instrucciones de DNS de tu registrador.
