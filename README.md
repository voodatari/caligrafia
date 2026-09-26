# Cuaderno de caligrafía

Generador de fichas de caligrafía para Primaria. Escribes o pegas un texto y la web crea fichas A4 con pauta y letra punteada para repasar, listas para imprimir o guardar en PDF.

**Web:** https://voodatari.github.io/caligrafia/

Los cambios de cada versión están en el [registro de cambios](CHANGELOG.md).

## Qué permite hacer

- Pegar varios textos separados por una línea en blanco. Cada uno puede empezar en una ficha nueva.
- Poner el tema de cada ficha con una línea que empiece por `#` (por ejemplo `# El lince ibérico`).
- Elegir el tipo de letra:
  - imprenta a mano, con el ligero temblor de un trazo real;
  - imprenta de trazo limpio, la misma letra con trazos perfectos;
  - cursiva enlazada, la letra ligada escolar.
- Elegir la letra inclinada o recta y su tamaño (de 3,5 a 9 mm de altura de mayúscula).
- Repartir los renglones de cinco formas: repasar y copiar, modelo + repasar + copiar, repasar dos veces, solo repasar, o modelo y copiar.
- Elegir la pauta y ajustar su intensidad: cuatro líneas, tres líneas, de colores (cielo, hierba y tierra) o solo renglón. La cursiva usa una pauta de tres franjas iguales.
- Cambiar el color del punteado y poner la primera letra de cada renglón en trazo continuo.
- Llenar los renglones sobrantes repitiendo el texto.
- Cambiar título, numeración, líneas de Nombre y Fecha y pie de página.
- Cargar 20 textos de ejemplo pensados para alumnado de 10 años en Andalucía.
- Descargar las 12 fuentes para usarlas en Word.

Todo funciona en el navegador y la configuración se recuerda en el propio equipo. El texto no se envía a ningún servidor.

## Imprimir

Pulsa **Imprimir o guardar en PDF**. En la ventana de impresión elige tamaño **A4**, márgenes **Ninguno** y escala **100 %**, y desactiva los encabezados y pies de página del navegador.

## Fuentes

Están en la carpeta `fonts/`, y todas juntas en `fonts/fuentes-caligrafia.zip`. Cada familia tiene cuatro archivos:

| Familia | Inclinada | Inclinada punteada | Recta | Recta punteada |
|---|---|---|---|---|
| Imprenta a mano | `ImprentaEscolar` | `ImprentaEscolarPunteada` | `ImprentaEscolarRecta` | `ImprentaEscolarRectaPunteada` |
| Imprenta de trazo limpio | `ImprentaEscolarLimpia` | `ImprentaEscolarLimpiaPunteada` | `ImprentaEscolarLimpiaRecta` | `ImprentaEscolarLimpiaRectaPunteada` |
| Cursiva enlazada | `CursivaEscolar` | `CursivaEscolarPunteada` | `CursivaEscolarRecta` | `CursivaEscolarRectaPunteada` |

(Todos los archivos terminan en `-Regular.ttf`.)

Incluyen ñ, vocales con tilde, ü y los signos ¿ ¡ « ». Los trazos se basan en las fuentes Hershey: Roman Simplex para la imprenta y para las mayúsculas y los números de la cursiva, y Script Simplex para las minúsculas cursivas, de A. V. Hershey (U.S. National Bureau of Standards), cuyo uso se permite con atribución.
