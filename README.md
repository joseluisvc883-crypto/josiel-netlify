# Josiel — El Inicio a la Felicidad

Página estática lista para desplegar en Netlify.

Contenido:
- index.html (página principal)
- netlify.toml (configuración Netlify)
- cancion.mp3 (opcional: subir si deseas que el audio esté alojado en el repo)

Cómo proceder (opciones):

1) Yo subo y despliego por ti (recomendado si quieres que lo haga ahora)
- Confirmas aquí que suba los archivos al repo (y si quieres que incluya cancion.mp3).
- Yo haré commit de index.html, netlify.toml y README.md (y cancion.mp3 si lo suministras).
- Te devolveré el enlace del repo y, una vez conectado a Netlify, la URL pública del sitio.

2) Lo subes tú desde tu máquina
- Clona el repo: `git clone https://github.com/joseluisvc883-crypto/josiel-netlify.git`
- Copia index.html, netlify.toml y cancion.mp3 (si tienes).
- Commit y push:
  - `git add .`
  - `git commit -m "Initial site files"`
  - `git push origin main`
- Conecta el repo en Netlify (New site from Git -> GitHub -> selecciona `josiel-netlify`). Publish directory: `.`

3) Deploy manual (drag & drop)
- Comprime los archivos y súbelos en Netlify Drag & Drop.

Notas:
- Si quieres un dominio personalizado, puedo añadírtelo (necesitarás acceso al DNS).
- Para formularios (RSVP) o un mapa, dímelo y lo integro con Netlify Forms o una incrustación de Google Maps.
