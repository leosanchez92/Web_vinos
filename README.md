# Web Vinos — Guía Kalycatas

*🧓 Creado antes de la IA.*

Mapa interactivo de viñedos construido con [Leaflet](https://leafletjs.com/), [Bootstrap](https://getbootstrap.com/) y jQuery. Permite explorar viñedos por Denominación de Origen (D.O.), buscar viñas por nombre y consultar información geológica, climática y de viticultura de cada ubicación.

## Características

- Visualización de viñedos sobre una capa satelital de Google Maps.
- Búsqueda de viñas por nombre con resaltado en el mapa.
- Panel lateral con información detallada (clima, geomorfología, suelo, variedad, viticultura, vinificación, guarda, tasting y puntaje) para los viñedos que cuentan con datos adicionales.
- Capa geológica activable en modo comparación lado a lado (side-by-side) con el contorno de las D.O.

## Estructura del proyecto

```
├── index.html          # Página principal con el mapa y la lógica de la aplicación
├── assets/              # Librerías y estilos de terceros (Leaflet y sus plugins)
├── data/                 # Datos geográficos (GeoJSON) e íconos del mapa
└── images/               # Logos e imágenes generales del sitio
```

## Uso local

Al ser un sitio estático, basta con servir la carpeta del proyecto con cualquier servidor HTTP simple, por ejemplo:

```bash
python3 -m http.server 8000
```

Luego abre `http://localhost:8000` en tu navegador.
