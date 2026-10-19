# Pérgola 3D

Editor 3D de una pérgola / quincho moderno (estructura de aluminio antracita, cielorraso de listones símil madera, banda abierta de listones, columnas con aletas, cocina con parrilla, TV en pared de listones y muralla). Funciona en el navegador, sin instalar nada.

**Abrir el editor:** https://aldorodrigo.github.io/pergola-3d/

## Qué permite

- **Mover y rotar** cualquier pieza con el mouse (W / E) o escribiendo la posición exacta.
- **Editar medidas**: techo (largo, ancho, altura, fascia), banda de listones, cielorraso, vigas, spots, columnas y aletas, piso, muralla, muebles, isla con parrilla, pileta, etc.
- **Agregar, duplicar y borrar** objetos; deshacer y rehacer (Ctrl+Z / Ctrl+Y).
- **Comparar con fotos**: superpone una foto de referencia sobre el 3D (opacidad, modo diferencia) para ajustar el modelo al original.
- **Medir** distancias, vistas de planta, frente y lateral, cotas y modo noche.
- **Guardar** el proyecto (automático en el navegador y como archivo `.json`).
- **Techo inclinado**: pendiente y lado bajo configurables; columnas, paneles y ventiladores llegan solos al cielorraso inclinado.
- **Estructura metálica**: armado apilado (vigas principales sobre columnas, transversales encima y correas C arriba). Predimensiona automáticamente perfiles, columnas, placas base, pernos y zapatas según la posición de las columnas, ajusta el alto del techo al paquete de la estructura y dimensiona la canaleta oculta según la lluvia de diseño. Por defecto usa caños y perfiles de hasta 2 mm del mercado paraguayo (los perfiles grandes se arman soldando 2 caños, y las columnas de 20×20 se arman con 4 caños y chapa) y muestra el costo aproximado de materiales en guaraníes. Cómputo de materiales descargable (CSV). Es un predimensionado orientativo: debe verificarlo un profesional matriculado antes de construir.
- **La estructura respeta el diseño**: ninguna viga cruza la banda abierta de lamas. Las lamas llevan un caño adentro y, si hace falta, separadores. Columnas y vigas se eligen para que entren en los postes, la fascia y la viga de la banda. Lo que igual queda a la vista (separadores, gárgolas, bajadas) también se dibuja en la vista *Terminado*, así lo que se ve es lo que construye el herrero.
- **Vistas** *Terminado*, *Sin cielorraso*, *Capas* (cada parte de la obra en su color, con capas que se prenden, apagan y separan) y *Estructura* (teclas 5–8).
- **Exportar a AutoCAD**: DXF 3D (mallas por capa) y DXF 2D (planta, vista frontal y lateral con cotas), en metros, centímetros o milímetros. Incluye la opción de exportar solo la estructura metálica y las fundaciones.

## Uso local

Descargá `pergola-3d.html` junto con la carpeta `referencias/` y abrilo con doble clic en Chrome o Edge (necesita internet para cargar Three.js desde el CDN).

## Atajos

| Tecla | Acción |
|---|---|
| W / E | mover / rotar |
| M | medir |
| Flechas · RePág / AvPág | mover un paso · subir / bajar |
| F | enfocar la selección |
| Ctrl+D · Supr | duplicar · eliminar |
| Ctrl+Z / Ctrl+Y | deshacer / rehacer |
| Q | mostrar / ocultar la foto de referencia |
| 1 – 4 | vista 3D, planta, frente, lateral |
| 5 – 8 | terminado, sin cielorraso, capas, estructura |

Hecho con [Three.js](https://threejs.org).
