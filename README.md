# Guía para realizar tus prácticas profesionales | ISND

Estructura lista para publicar en GitHub Pages:

```text
index.html
.nojekyll
assets/logo_isnd.png
formatos/aceptacion_practicas.doc
formatos/reporte_actividades.doc
formatos/evaluacion_actividades.doc
data/alumnos.json
```

## Publicación rápida

1. Crea un repositorio en GitHub, por ejemplo `practicas-isnd`.
2. Sube todos los archivos y carpetas de este paquete.
3. En el repositorio, entra a **Settings > Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. En **Branch**, selecciona `main` y carpeta `/root`.
6. Guarda y espera a que GitHub genere la liga.

## Actualizar la base de datos

Reemplaza `data/alumnos.json` por una nueva versión con este formato:

```json
[
  { "id": "22627", "avance": 100.00, "cumple_60": true }
]
```

## Actualizar formatos

Reemplaza los archivos en la carpeta `formatos`, conservando los mismos nombres:

- `aceptacion_practicas.doc`
- `reporte_actividades.doc`
- `evaluacion_actividades.doc`
