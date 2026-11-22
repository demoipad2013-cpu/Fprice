# Fprice

Carteles de precio Apple y Falabella para Falabella Costanera, listos para imprimir con el mismo diseño y márgenes del Excel.

**Secciones:** Price Tickets Apple (lanzamiento NPI destacado, iPhone, Mac, iPad, Apple Watch, HomePod, AirPods y Apple Shop Core Falabella Costanera) · Precios Falabella · Pestañas evento Falabella · Flejes Accesorios · Calculadora Falabella.

## Archivos

| Archivo | Para qué sirve |
| --- | --- |
| `index.html` | La App |
| `datos/plantillas.json` | Diseño exacto de cada hoja del Excel |
| `datos/fotos.json` | Fotos de los equipos de Precios Falabella |
| `datos/xl-main.txt` | Excel base Price Ticket NPI (para "Descargar Excel") |
| `datos/xl-asc.txt` | Excel base Apple Shop Core (para "Descargar Excel") |
| `datos/xl-mbp14m6.txt` | Excel base MacBook Pro 14" M6 de Apple Shop Core |
| `.nojekyll` | Hace que GitHub Pages publique los archivos tal cual |

## Publicar en GitHub Pages

1. Descomprime el zip y sube todo el contenido a la raíz del repositorio (incluida la carpeta `datos`).
2. En el repositorio: **Settings → Pages → Branch: main / (root) → Save**.
3. Después de 1 o 2 minutos la App queda en `https://<usuario>.github.io/<repositorio>/`.

Para actualizar, sube el `index.html` y la carpeta `datos` nuevos con los mismos nombres: reemplazan a los anteriores.
