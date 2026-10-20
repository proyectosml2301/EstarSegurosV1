# Estar Seguros · Tablero de Asistencia Vial

Tablero de gestión de Asistencia Vial con el cierre de **agosto 2026**, por dimensiones
(plaza, sucursal, productor y estatus de verificación). Cifras en USD.

## Contenido

| Ruta | Descripción |
| --- | --- |
| `index.html` | Tablero de gestión · Estar Seguros · Asistencia Vial |

`index.html` es un archivo autocontenido: los datos y el estilo van embebidos y las únicas
dependencias externas son Chart.js y Google Fonts por CDN. No requiere build ni servidor.

## Uso local

Abrir `index.html` en el navegador, o servirlo con:

```bash
python -m http.server 8000
```

## Despliegue

Publicado con **GitHub Pages** desde la rama `main`, carpeta raíz. Cada push a `main`
actualiza el sitio automáticamente en <https://proyectosml2301.github.io/EstarSegurosV1/>.

## Confidencialidad

El tablero contiene nombres, RIF y montos de asegurados. El repositorio y el sitio son
públicos por decisión del responsable del proyecto; no deben enlazarse desde medios abiertos
ni compartirse fuera del alcance acordado con el cliente.
