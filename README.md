# Névé — sitio estático (estructura plana)

Misma página que la versión con carpeta `assets/`, pero con todos los
archivos sueltos al mismo nivel — pensada para subirse desde el
subidor web de GitHub, que acepta varios archivos a la vez pero no
carpetas.

## Subirlo a GitHub (desde el navegador, sin terminal)

1. Entra a tu repositorio en github.com.
2. **Add file → Upload files**.
3. Selecciona **todos** los archivos de esta carpeta a la vez (los 15:
   `index.html`, `styles.css`, `enhancements.css`, `app.js` y las 11
   imágenes) y suéltalos ahí. Como no hay ninguna carpeta de por
   medio, el subidor los sube todos sin problema.
4. Confirma el commit ("Commit changes").
5. **Settings → Pages → Build and deployment → Source**: elige
   *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
6. Espera uno o dos minutos y entra a
   `https://TU-USUARIO.github.io/TU-REPO/`.

Si ya habías subido antes solo `index.html`, no borres nada: sube
estos archivos igual, encima. Como los nombres no chocan con nada, se
agregan sin pisar lo que ya tenías (o, si vuelves a subir `index.html`,
GitHub te va a preguntar si quieres reemplazarlo — di que sí).

## Si más adelante prefieres usar carpetas (opcional)

La estructura con `assets/` (más ordenada para mantener) sigue
disponible en `neve_static/` — usa esa si en algún momento subes el
sitio por línea de comandos (`git add .` sí sube carpetas sin
problema) o con GitHub Desktop.

## Antes de publicar

- Cambia el número de WhatsApp: en `index.html`, busca
  `data-whatsapp="52100000000"` y `data-message="..."` cerca del inicio
  del archivo.
- `logo1.png` trae un fondo celeste incrustado en la imagen (no es
  CSS). Si tienes una versión con fondo transparente, reemplázala.

## Ver antes de subir

Abre `index.html` directamente haciendo doble clic — al estar todo en
la misma carpeta, funciona sin servidor.
