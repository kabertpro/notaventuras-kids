# Notaventuras Kids — KABERT STUDIO

Juego web para aprender a leer notas en el pentagrama (clave de Sol). Un solo `index.html`, sin dependencias, funciona sin internet.

## Estructura
```
notaventuras-kids/
├─ index.html
├─ cabezas/        ← copia aquí tus 12 PNG de 300x300 (ver cabezas/LEEME.txt)
└─ LEEME.md
```

## Novedades de esta versión
- Pentagrama, clave y notas más grandes (también nítidos en pantallas retina/móviles).
- **Notas por ronda configurable de 5 a 15** (antes fijo en 10): menú → ⚙️ Ajustes.
- **Cabezas de nota intercambiables** con tus imágenes de `cabezas/`, con vista previa y opción «Clásica».
- Si falta una imagen o la carpeta, el juego usa la cabeza clásica y avisa en Ajustes.
- La configuración se guarda en el dispositivo (localStorage).
- El récord se guarda por nivel y por cantidad de notas (así no se mezclan partidas de 5 y de 15).

## Publicar en GitHub Pages
Sube `index.html` y la carpeta `cabezas/` a tu repositorio (arrastrar y soltar en el editor web) y activa Pages.
