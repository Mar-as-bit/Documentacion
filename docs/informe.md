## URL del github
[Github enlace perfil](https://github.com/Mar-as-bit/Documentacion)

## URL Github Pages
[Enlace Github Pages](https://github.com/Mar-as-bit/Documentacion/settings/pages)

## URL Github workflows
[Enlace Github workflows](https://github.com/Mar-as-bit/Documentacion/blob/main/.github/workflows/deploy-pages.yml)
## Breve explicación de la estructura creada con Docusaurus

La documentación del proyecto se ha organizado con **Docusaurus**, separando el contenido, la configuración y los recursos del sitio.

### Documentación del proyecto

La carpeta `docs/` contiene los documentos escritos en Markdown: una introducción y los apartados de análisis, diseño, implementación, pruebas y despliegue. Cada apartado recoge la información correspondiente del proyecto Gestor de Tareas DAW.

### Estructura de archivos y carpetas

- `src/`: contiene las páginas y los componentes utilizados para personalizar la web.
- `static/`: almacena recursos estáticos, como imágenes e iconos.
- `docusaurus.config.ts`: contiene la configuración general del sitio, como el título, `url` y `baseUrl`.
- `sidebars.ts`: configura el menú lateral de la documentación.
- `package.json`: recoge las dependencias y los comandos del proyecto.
- `.github/workflows/deploy-pages.yml`: define el proceso automático de construcción y publicación en GitHub Pages.

### Generación del sitio estático

Al ejecutar `npm run build`, se genera la carpeta `build/`, que contiene el sitio estático preparado para publicarse.