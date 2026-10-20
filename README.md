# Seguros Venezuela · Tablero de Asistencia Vial

Tablero de resultados técnicos del cierre de **agosto 2026** para la cartera de Asistencia
Vial de Seguros Venezuela.

## Contenido

| Ruta | Descripción |
| --- | --- |
| `index.html` | Tablero de resultados técnicos · Seguros Venezuela |

Cuota devengada pro-rata temporis, expuestos a riesgo como unidad de exposición y vehículos
activos por plaza. Bordereaux de cuotas cobradas y reclamaciones hasta agosto 2026, en USD.

`index.html` es un archivo autocontenido: los datos y el estilo van embebidos y la única
dependencia externa es Chart.js por CDN. No requiere build ni servidor.

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
