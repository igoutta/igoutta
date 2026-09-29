# Arte

Monograma "GA" de Gustavo Alvarado.

| Archivo | Qué es |
| --- | --- |
| `SVGBOB-GA` | El monograma dibujado en ASCII en el [editor de Svgbob](https://ivanceras.github.io/svgbob-editor/). Es la fuente del logo. |
| `ASCII-GA` | El mismo monograma en arte ASCII de puntos. |
| `../img/logo.svg` | SVG generado con [Svgbob](https://github.com/ivanceras/svgbob) a partir de `SVGBOB-GA`. |
| `../img/logo-light.svg`, `../img/logo-dark.svg` | Copias de `logo.svg` con color fijo para el README de GitHub, que elige una según su propio tema (claro u oscuro) con `<picture>`. |

Cambios hechos a mano sobre `logo.svg`, sin tocar la geometría:

- fondo transparente;
- trazo con la tinta del sitio: `#16232b` en tema claro y `#dce5e9` en oscuro;
- grosor de línea constante (~1,25 px) a cualquier tamaño (`vector-effect: non-scaling-stroke`);
- los puntos que Svgbob dejaba como texto (`.........`) son círculos en su celda de la cuadrícula, del mismo tamaño en pantalla que el trazo.

Para regenerarlo, pega `SVGBOB-GA` en el editor de Svgbob y exporta el SVG.
Después hay que volver a aplicar esos cambios y sacar de nuevo las dos copias
de color fijo.
