
# Ventiladores Dashboard (IMSS-BIENESTAR)

Este paquete contiene:
- `index.html`
- `/logos/gobmx.png`
- `/logos/imss-bienestar.png`

## Publicar en GitHub Pages (gratis)

1. Crea un repositorio nuevo en GitHub (por ejemplo: `ventiladores-dashboard`).
2. Sube estos archivos conservando la estructura de carpetas:
   ```
   / (raíz del repo)
   ├── index.html
   └── logos/
       ├── gobmx.png
       └── imss-bienestar.png
   ```
3. En el repositorio: **Settings → Pages** → Source: `Deploy from a branch` → Branch: `main` → Folder: `/ (root)` → Save.
4. Abre la URL que GitHub Pages te da, ejemplo: `https://tuusuario.github.io/ventiladores-dashboard/`.

## (Opcional) Habilitar Firebase para colaboración en línea

- En `index.html` busca `const firebaseConfig = { ... }` y pega las credenciales de tu proyecto.
- Crea las colecciones `hospitals` y `ventilators`.
- Ajusta reglas de seguridad (bloque al final del HTML).
- Crea usuarios de hospital en Firebase Authentication.

> Si no configuras Firebase, funciona en **modo local** con `localStorage`.
