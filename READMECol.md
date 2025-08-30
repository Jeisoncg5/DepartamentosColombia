# Ejercicio Mapa Político de Colombia

Este proyecto es una web estática desarrollada en **HTML y CSS**, cuyo objetivo es mostrar un **mapa político de Colombia** y permitir la navegación hacia páginas individuales de algunos departamentos.

## 📂 Estructura del proyecto

```bash
EjerMapaColombia/
├── index.html          # Página principal con el mapa de Colombia y enlaces interactivos
├── casanare.html       # Página con información del departamento de Casanare
├── huila.html          # Página con información del departamento del Huila
├── sucre.html          # Página con información del departamento de Sucre
├── css/
│   └── style.css       # Hoja de estilos principal para todas las páginas
├── img/                # Carpeta de imágenes usadas en el proyecto
│   ├── MapaCol.jpg
│   ├── Casanare.png
│   ├── Huila.png
│   ├── Sucre.png
│   └── ... (otras imágenes de paisajes y cultura)
└── .git/               # Carpeta de control de versiones Git
```

## Funcionamiento

- La página principal (`index.html`) muestra un **mapa político de Colombia** con áreas interactivas en forma de polígonos (`<area>` con `coords`).
- Cada área del mapa enlaza a un archivo HTML correspondiente a un departamento:
  - **Casanare** → `casanare.html`
  - **Huila** → `huila.html`
  - **Sucre** → `sucre.html`
- Cada página de departamento incluye:
  - Una breve **descripción geográfica e histórica**.
  - Sección de **gastronomía típica**.
  - Apartado de **información clave** (capital, ubicación, economía, área, población).
  - Una sección de **cultura y turismo**.
  - Imágenes representativas del territorio.

##  Estilos

El archivo `css/style.css` centraliza los estilos del proyecto, aplicando un formato uniforme a títulos, párrafos, imágenes y listas.  
Esto garantiza que todas las páginas compartan la misma estética.

## Imágenes

La carpeta `img/` contiene los mapas e imágenes de apoyo utilizadas en las páginas de cada departamento y en el mapa principal.

Ejemplos:
- `MapaCol.jpg` → Imagen principal del mapa político de Colombia.
- `Casanare.png`, `Huila.png`, `Sucre.png` → Mapas individuales de los departamentos.
- Fotografías de paisajes, ciudades y gastronomía.

## Requisitos

Este proyecto es completamente **estático**, por lo tanto **no requiere servidor** ni dependencias externas.  
Para visualizarlo basta con abrir el archivo `index.html` en cualquier navegador web moderno.

## Uso

1. Abre `index.html` en un navegador.  
2. Haz clic en el área de un departamento dentro del mapa de Colombia.  
3. Accede a la información detallada de cada departamento en su respectiva página.  

O tambien puedes acceder mediante este link web.

**[astonishing-kleicha-5376a7.netlify.app](https://astonishing-kleicha-5376a7.netlify.app/)**



