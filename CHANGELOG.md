# Registro de cambios

Aquí se apuntan los cambios de cada versión del Cuaderno de caligrafía.
La versión más reciente va arriba.

## [1.2] - 2026-09-26

### Cambiado

- **Mayúsculas y números de la cursiva más sencillos.** Los anteriores eran demasiado enrevesados para el alumnado. Ahora tienen la forma de la letra de imprenta, con la misma inclinación y el mismo grosor que las minúsculas cursivas. Las minúsculas siguen enlazadas igual que antes.
- **La cursiva empieza inclinada.** Cada tipo de letra recuerda su propia inclinación. Al elegir la cursiva por primera vez sale inclinada, aunque la imprenta se esté usando recta.

## [1.1] - 2026-09-26

### Añadido

- **Imprenta de trazo limpio.** Es la misma letra de imprenta que la versión a mano, pero con trazos perfectos, sin temblor. Tiene versión inclinada y recta, cada una continua y punteada.
- **Cursiva enlazada.** Letra ligada escolar, con versión inclinada y recta, cada una continua y punteada. Incluye ñ, vocales con tilde, ü y los signos ¿ ¡ « ».
- **Pauta propia para la cursiva.** Tiene tres franjas iguales (ascendentes, cuerpo y descendentes), como en los cuadernos de letra ligada. La imprenta mantiene su pauta de siempre.
- **Selector de letra en dos partes.** Primero se elige el tipo (imprenta a mano, imprenta de trazo limpio o cursiva) y después la inclinación (inclinada o recta). Cada opción muestra una muestra con su propia letra.
- **Un tamaño para cada tipo de letra.** La web recuerda el tamaño elegido para cada tipo. La cursiva empieza en 8 mm, porque a 6 mm su cuerpo queda demasiado pequeño.
- **Descarga de las fuentes.** Se pueden descargar las 12 fuentes una a una o todas juntas en un ZIP.
- Número de versión y enlace a este registro al pie del panel.

### Cambiado

- Las fuentes ya no van metidas dentro de `index.html`: se cargan desde la carpeta `fonts/`. La página pasa de 395 KB a 39 KB y solo descarga la letra que se está usando.
- El README describe las tres familias de letra y las 12 fuentes.

### Sin cambios

- Las cuatro fuentes de la imprenta a mano (`ImprentaEscolar*.ttf`) son exactamente las mismas de la versión 1.0.

## [1.0] - 2026-09-25

Primera versión publicada.

### Añadido

- Generador de fichas A4 de caligrafía a partir de uno o varios textos separados por una línea en blanco. Una línea que empieza por `#` pone el tema de la ficha.
- Imprenta a mano, inclinada y recta, con trazo continuo y punteado.
- Tamaño de letra de 3,5 a 9 mm (altura de las mayúsculas).
- Cinco formas de repartir los renglones: repasar y copiar, modelo + repasar + copiar, repasar dos veces, solo repasar, y modelo y copiar.
- Cuatro pautas: cuatro líneas, tres líneas, de colores y solo renglón, con intensidad ajustable.
- Color del punteado, primera letra de cada renglón en trazo continuo, relleno de renglones sobrantes, barras laterales y más espacio entre renglones.
- Título con numeración, líneas de Nombre y Fecha, pie de página y «Página X de Y».
- 20 textos de ejemplo para alumnado de 10 años en Andalucía.
- Impresión o guardado en PDF, y descarga de las fuentes para Word.
