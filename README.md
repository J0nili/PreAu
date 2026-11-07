# Control presentes y ausentes

Aplicación web (PWA) para llevar el control de citados, presentes y ausentes por salón.
Funciona sin servidor propio: solo HTML, CSS y JavaScript, con los datos guardados en el navegador (localStorage).

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (público, o privado si tu plan permite Pages).
2. Sube **todos** los archivos de esta carpeta a la raíz del repositorio:
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` y `.nojekyll`.
3. En el repositorio ve a **Settings → Pages**.
4. En *Build and deployment* elige **Deploy from a branch**, rama **main** y carpeta **/ (root)**, y pulsa *Save*.
5. Espera uno o dos minutos. La app quedará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

## Instalar como app

- **iPhone / iPad:** abre la dirección en Safari → Compartir → *Agregar a pantalla de inicio*.
- **Android:** abre la dirección en Chrome → menú ⋮ → *Instalar app* (o el botón *Instalar app* dentro de Opciones).
- **Computador:** en Chrome o Edge, ícono de instalar en la barra de direcciones.

## Notas

- Todas las rutas son relativas, por lo que funciona en la raíz o en una subcarpeta (`/NOMBRE-DEL-REPOSITORIO/`).
- Si publicas una versión nueva y no la ves, cierra y abre la app dos veces (el service worker actualiza en segundo plano).
- Los datos de localStorage son locales a cada navegador/dispositivo; usa *Descargar CSV* e *Importar CSV* para pasarlos entre equipos.
