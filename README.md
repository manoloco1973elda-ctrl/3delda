# 3DELDA

Web estática para publicar con GitHub Pages.

## Publicarla gratis

1. Crea una cuenta en [GitHub](https://github.com) si aún no tienes una.
2. Crea un repositorio nuevo llamado `3delda` y súbele estos cuatro archivos: `index.html`, `style.css`, `script.js` y `README.md`.
3. En el repositorio, abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**, elige `main` y la carpeta `/(root)`, y guarda.
5. GitHub te mostrará tu dirección pública, normalmente `https://TU-USUARIO.github.io/3delda/`.

## Añadir las fotos reales

Crea una carpeta `fotos` y sube dentro tus imágenes. Después sustituye cada bloque como este:

```html
<div class="photo placeholder one"><span>Tu foto aquí</span></div>
```

por:

```html
<div class="photo" style="background: url('fotos/nombre-de-tu-foto.jpg') center / cover;"></div>
```

También puedes cambiar los nombres, materiales y el enlace de contacto directamente en `index.html`.
