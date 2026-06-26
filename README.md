# MilPlatos

App web offline para armar menús semanales saludables. Un solo archivo, sin servidor.

## Publicar en GitHub Pages
1. Creá un repositorio nuevo (público), p.ej. `milplatos`.
2. Subí **todo el contenido de esta carpeta** (no la carpeta, sino los archivos: index.html, manifest.json, service-worker.js, icon.svg, icon-192.png, icon-512.png).
3. En el repo: **Settings → Pages**.
4. En **Build and deployment → Source**, elegí **Deploy from a branch**.
5. Branch: **main** y carpeta **/(root)**. Guardá.
6. Esperá ~1 minuto. Tu app queda en `https://TU_USUARIO.github.io/milplatos/`.

## Notas
- Es una PWA: desde el celular, "Agregar a pantalla de inicio" la instala y funciona offline.
- Si actualizás `index.html`, subí el cambio y subí el número de versión en `service-worker.js` (CACHE = 'milplatos-v2', etc.) para que se actualice en los dispositivos.
- Acordate de cambiar `APP_URL` dentro de index.html por la URL real (la del botón Compartir).
