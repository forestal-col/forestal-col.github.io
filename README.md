# Forestal Colombia

Sitio estático de Forestal Colombia, creado con [Astro](https://astro.build) y preparado para GitHub Pages.

## Desarrollo

```sh
npm install
npm run dev
```

## Publicación

Cada cambio enviado a `main` ejecuta el flujo de GitHub Actions en `.github/workflows/deploy.yml`. En el repositorio de GitHub, activa **Settings → Pages → Source: GitHub Actions** una única vez si aún no está seleccionado.

La carpeta `dist/` se conserva deliberadamente en control de versiones por ahora, aunque el flujo también la genera desde la fuente en cada despliegue.
