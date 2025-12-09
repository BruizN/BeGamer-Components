# BeGamer-Components


Trabajare con el conjunto de herramientas Structurizr para documentar las decisiones técnicas y modelar la arquitectura del sistema mediante el modelo C4.

Herramientas:
- Structurizr: Para modelar la arquitectura del sistema y documentar las decisiones técnicas mediante el lenguaje DSL.
- Structurizr Lite: Para visualizar el archivo .dsl en local host de forma interactiva.
- structurizr-site-generatr: Para generar el sitio web de la arquitectura mediante un pipeline de GitHub Actions y usarlo en GitHub Pages.

## Inicializar Structurizr Lite

```bash
docker run -it --rm -p 8080:8080 -v "${PWD}:/usr/local/structurizr" structurizr/lite
```