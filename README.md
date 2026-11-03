# Marcas y derechos de autor (tb)

Sitio estático (HTML) con cotizador de registro de marca, declaración de uso y renovación.

## Archivos
- `index.html` — página principal y cotizador (registro de marca)
- `derechos-de-autor.html` — pestaña de derechos de autor ante el INDAUTOR (el WhatsApp se cambia en su `<script>`, variable `WHATSAPP`)
- `aviso-de-privacidad.html` — aviso de privacidad integral
- `favicon.svg`, `apple-touch-icon.png` — íconos
- `og-image.jpg` — imagen al compartir el enlace (WhatsApp, Facebook, etc.)

## Cambiar precios o WhatsApp
En `index.html`, busca `CONFIGURACIÓN` dentro del `<script>`:
- `WHATSAPP` — número con código de país, sin espacios
- `ESTUDIO`, `POR_CLASE`, `DECLARACION`, `RENOVACION` — precios en MXN

## Publicación
Cloudflare Pages conectado a este repositorio. Cada cambio en la rama `main` se publica solo.
- Framework preset: None
- Build command: (vacío)
- Build output directory: `/`
