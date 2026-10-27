# Prototipo MVP · Servicios Universitarios Inteligentes

Prototipo de baja fidelidad (escala de grises) de la aplicación web y móvil para
gestión de servicios universitarios. Muestra las pantallas de cada incremento
en tres vistas: escritorio, web/tableta y móvil.

## Estructura

- `index.html`: prototipo completo (HTML, CSS y JavaScript en un solo archivo, sin dependencias).
- `netlify.toml`: configuración de publicación para Netlify.

## Ver en local

Basta con abrir `index.html` en el navegador, o ejecutar:

```bash
npx serve .
```

## Publicar en Netlify

1. Sube este repositorio a GitHub.
2. En Netlify: **Add new site → Import an existing project → GitHub**, y elige el repositorio.
3. No hace falta comando de build. Netlify tomará `netlify.toml` (directorio de publicación: `.`).
4. Cada `git push` a la rama principal publica una nueva versión automáticamente.

Alternativa sin GitHub: en Netlify, **Add new site → Deploy manually** y arrastra la carpeta del proyecto.
