# ChicoBrap · páginas legales

Página de inicio, política de privacidad y términos de servicio para registrar ChicoBrap Uploader en Google Cloud, TikTok for Developers y Meta for Developers.

## Publicar en GitHub Pages

1. Crea un repositorio público en GitHub, por ejemplo `chicobrap`.
2. Sube los cuatro ficheros a la raíz: `index.html`, `privacidad.html`, `terminos.html` y `style.css`.
3. En el repositorio: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`. Guarda.
4. En uno o dos minutos la web estará en `https://chicorafa.github.io/chicobrap/`.

## URLs para los formularios de las apps

| Campo | URL |
| --- | --- |
| Página de inicio / App website | `https://chicorafa.github.io/chicobrap/` |
| Política de privacidad / Privacy Policy URL | `https://chicorafa.github.io/chicobrap/privacidad.html` |
| Términos de servicio / Terms of Service URL | `https://chicorafa.github.io/chicobrap/terminos.html` |
| Eliminación de datos / Data deletion URL | `https://chicorafa.github.io/chicobrap/eliminar-datos.html` |
| Redirect URI (TikTok, Meta) | `https://chicorafa.github.io/chicobrap/callback.html` |

## Notas

- TikTok pide que el sitio web de la app esté verificado. En la consola de TikTok for Developers, añade el dominio `chicorafa.github.io` (o la URL con prefijo) y sigue sus instrucciones de verificación; normalmente consiste en subir un fichero `.txt` que te dan o añadir una etiqueta `<meta>` en `index.html`.
- Si más adelante montas el dominio de ChicoStuff, en Settings → Pages → Custom domain puedes apuntarlo a esta misma web y actualizar las URLs en las consolas.
