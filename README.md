# TECATEX AEROSPACE — Landing Page

Sitio estático en HTML, preparado para publicarse con GitHub Pages.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub.
2. Sube `index.html` a la raíz del repositorio.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`.
6. Guarda los cambios. GitHub te mostrará la dirección pública del sitio.

## Personalizar la cuenta regresiva

Abre `index.html` y busca esta línea:

```js
const LAUNCH_DATE = "";
```

Agrega la fecha y hora del lanzamiento en formato ISO 8601, por ejemplo:

```js
const LAUNCH_DATE = "2027-06-15T10:00:00-07:00";
```

El ejemplo es ilustrativo; reemplázalo por la fecha real.

## Contenido pendiente

La página incluye espacios de muestra para fotografías, videos, nombres de integrantes y datos técnicos. Sustituye esos textos y elementos cuando tengas el material definitivo.

El logotipo está integrado dentro de `index.html`, por lo que no necesitas subirlo por separado.
