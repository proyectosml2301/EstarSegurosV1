# Estar Seguros · Tableros de Asistencia Vial

Sitio estático con los tableros de gestión y resultados técnicos del cierre de **agosto 2026**
para las carteras de Asistencia Vial de Estar Seguros y Seguros Venezuela.

## Contenido

| Ruta | Tablero |
| --- | --- |
| `index.html` | Portada con acceso a los tres tableros |
| `tableros/gestion-asistencia-vial.html` | Consola de gestión por dimensiones (plaza, sucursal, productor) |
| `tableros/estar-seguros-resultados.html` | Resultados técnicos · Estar Seguros |
| `tableros/seguros-venezuela-resultados.html` | Resultados técnicos · Seguros Venezuela (vista cliente) |

Cada tablero es un archivo HTML autocontenido: los datos y el estilo van embebidos y las
dependencias externas son Chart.js y Google Fonts por CDN. No requiere build ni servidor.

## Uso local

Abrir `index.html` en el navegador, o servirlo con:

```bash
python -m http.server 8000
```

## Despliegue

Publicado con **GitHub Pages** desde la rama `main`, carpeta raíz. Cada push a `main`
actualiza el sitio automáticamente.

## Confidencialidad

Los tableros contienen nombres, RIF y montos de asegurados. El repositorio y el sitio son
públicos por decisión del responsable del proyecto; no deben enlazarse desde medios abiertos
ni compartirse fuera del alcance acordado con el cliente.
