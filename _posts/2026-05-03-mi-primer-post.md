---
title: "Introducción a GitHub Pages con Jekyll"
date: 2026-05-03
---

En esta entrada documento el proceso de configuración de un sitio estático usando **GitHub Pages** y **Jekyll**, realizado como ejercicio práctico del curso.

## ¿Qué es GitHub Pages?

GitHub Pages es un servicio de GitHub que permite publicar sitios web estáticos directamente desde un repositorio. Al habilitar esta función en la rama `main`, GitHub genera y despliega el sitio automáticamente con cada commit.

## Pasos realizados

1. **Habilitación de GitHub Pages**: Se activó el servicio desde la configuración del repositorio, seleccionando `main` como rama fuente.
2. **Personalización del homepage**: Se editó el archivo `index.md` para presentar el contenido principal del sitio.
3. **Configuración del tema**: Se modificó `_config.yml` para aplicar el tema `minima` y definir metadatos del sitio como título, descripción y autor.
4. **Creación del primer post**: Se creó este archivo siguiendo la convención de Jekyll para posts (`_posts/YYYY-MM-DD-titulo.md`) e incluyendo el frontmatter requerido.

## Aprendizajes

- Jekyll procesa archivos Markdown y los convierte en páginas HTML estáticas.
- El archivo `_config.yml` centraliza la configuración global del sitio.
- El **frontmatter** (bloque YAML al inicio de cada archivo) permite definir metadatos como título, fecha y categorías.
- La convención de nombres en `_posts/` es obligatoria para que Jekyll reconozca los archivos como entradas de blog.

## Conclusión

GitHub Pages con Jekyll es una herramienta accesible y eficiente para publicar documentación, portafolios o blogs técnicos directamente desde un repositorio de código.
