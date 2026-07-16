# Street Flags — Finanzas

Proyecto estático listo para subir a GitHub y publicar en Netlify.

## Archivos incluidos

- `index.html`: aplicación completa.
- `netlify.toml`: configuración de deploy en Netlify.
- `_redirects`: fallback para que Netlify sirva siempre `index.html`.
- `package.json`: opcional, solo para previsualizar localmente.
- `.gitignore`: evita subir archivos innecesarios.

## Publicar en Netlify desde GitHub

1. Crea un repositorio nuevo en GitHub.
2. Sube todos estos archivos a la raíz del repositorio.
3. En Netlify, elige **Add new site → Import an existing project**.
4. Conecta GitHub y selecciona el repositorio.
5. Deja el build así:
   - Build command: vacío
   - Publish directory: `.`
6. Publica el sitio.

## Publicar arrastrando el ZIP/carpeta a Netlify

También puedes entrar a Netlify y usar **Deploy manually** arrastrando la carpeta del proyecto o el ZIP descomprimido.

## Probar localmente

```bash
npm install
npm run preview
```

La app usa CDN externos para XLSX y Chart.js, así que necesita internet para cargar gráficos y leer Excel.
