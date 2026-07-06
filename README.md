# Prototipo WebAR Educativo

Este repositorio contiene un prototipo inicial para visualizar modelos 3D en navegador y activar realidad aumentada desde dispositivos compatibles.

## Objetivo

Crear una base simple para desarrollar experiencias educativas con realidad aumentada usando HTML, CSS, JavaScript y modelos 3D en formato `.glb` o `.gltf`.

## Estructura

```text
webar-prototipo-educativo/
├── index.html
├── README.md
├── assets/
│   └── poster-placeholder.svg
└── models/
    └── README.md
```

## Cómo probarlo

1. Abre `index.html` desde GitHub Pages.
2. En computadora, usa el visor 3D para girar y acercar el modelo.
3. En celular compatible, presiona **Ver en realidad aumentada**.
4. Coloca el modelo sobre una superficie iluminada.

## Cómo cambiar el modelo 3D

En `index.html`, ubica esta línea:

```html
src="https://modelviewer.dev/shared-assets/models/Astronaut.glb"
```

Sustitúyela por la ruta de tu propio modelo:

```html
src="models/mi-modelo.glb"
```

Después sube el archivo `.glb` dentro de la carpeta `models/`.

## Fuentes recomendadas para modelos 3D

- Sketchfab
- Poly Haven
- Smithsonian 3D
- NASA 3D Resources
- Blender para crear o adaptar modelos propios

Antes de publicar un modelo, revisa la licencia de uso.

## Ruta de mejora

- Versión 1: visor 3D + botón AR.
- Versión 2: modelo científico propio.
- Versión 3: etiquetas educativas sobre el modelo.
- Versión 4: guía de observación y evaluación.
- Versión 5: AR con marcador usando AR.js o MindAR.
