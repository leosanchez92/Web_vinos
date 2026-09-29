# Web Vinos — Guía Kalycatas

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white) ![Quarto](https://img.shields.io/badge/Quarto-39729E?style=flat-square&logo=quarto&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

> 📜 **Nota arqueológica**
>
> Este proyecto fue construido hace varios años, cuando la asistencia para programar era buscar soluciones en foros de StackOverflow a las 2 a.m., y reparar el código a prueba y error. Cada función acá fue pensada, escrita y depurada a mano. Hecho con cariño y pocas horas de sueño.

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
