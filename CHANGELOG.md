# Registro de cambios

Aquí se apuntan los cambios de cada versión del Cuaderno de caligrafía.
La versión más reciente va arriba.

## [1.3.2] - 2026-09-26

### Corregido

- **La cursiva recta se echaba a la izquierda.** Para enderezarla se había supuesto que la letra de partida estaba inclinada unos 18º, pero sus trazos verticales (las astas de l, t, d, i, n...) solo lo están unos 11º. Al quitarle de más, la «recta» quedaba ligeramente inclinada hacia la izquierda. Ahora se corrige con la inclinación medida y las astas quedan verticales.
- **Mayúsculas y números de la cursiva con la misma inclinación que las minúsculas.** Por el mismo error, en la cursiva recta iban algo inclinados y en la inclinada, más tumbados que el resto. Ahora van igual que las minúsculas. La cursiva inclinada mantiene su inclinación suave de siempre, de unos 6º.

## [1.3.1] - 2026-09-26

### Corregido

- **Líneas en blanco debajo de los títulos.** Algunas IA, como ChatGPT, dejan una o varias líneas en blanco entre la línea del título (`# ...`) y su texto, aunque el encargo pida lo contrario. Como la línea en blanco separa un texto del siguiente, salían fichas con el título y sin texto. Ahora:
  - al pegar en la caja «Texto» o en la ventana de textos con IA, esas líneas se quitan y un aviso dice cuántas se han quitado;
  - aunque se escriban a mano, las fichas salen bien;
  - un título que se queda sin texto ya no crea una ficha vacía.
- En la ventana de textos con IA, si la respuesta traía el título en un bloque aparte, el texto se pegaba en la misma línea que el título. Ahora va debajo, como debe.

## [1.3] - 2026-09-26

### Añadido

- **Crear textos con IA.** Un nuevo botón abre una ventana en tres pasos:
  1. Eliges cuántas fichas quieres (una por tema), la edad del alumnado, el tipo de texto y los temas. Los temas se escriben separados por comas o se añaden y quitan pulsando etiquetas: videojuegos, deportes, cine y series, cuentos, aventuras y más.
  2. La web escribe el encargo y lo envía a Claude o a ChatGPT, que lo reciben directamente. Gemini y DeepSeek no lo permiten: se abren y el encargo queda copiado para pegarlo. También se puede copiar para cualquier otra IA, o verlo y retocarlo antes de enviarlo.
  3. Pegas la respuesta y los textos pasan a la ficha, sustituyendo o añadiéndose a los que ya había.
- **Extensión calculada con la configuración de la ficha.** El encargo pide a la IA el número de palabras y caracteres que caben en una ficha, según el tamaño de letra, el tipo de letra, el reparto de renglones, las líneas de Nombre y Fecha y el espacio entre renglones. Por ejemplo, con la imprenta a 6 mm caben unas 60-73 palabras, y a 8 mm unas 31-38.
- **Limpieza de la respuesta.** Se quitan la introducción y la despedida de la IA, las negritas y la numeración de los títulos. Las comillas inglesas pasan a « », los puntos suspensivos a tres puntos y las rayas a guiones, y se eliminan los emojis y los símbolos que la letra no tiene.
- **Revisión del resultado.** Al pegar la respuesta se avisa de qué textos no caben en una ficha y cuáles dejan renglones libres.

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
