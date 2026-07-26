# ARCANUM OS · Pack responsive definitivo (v3)

Estos 11 widgets reemplazan TODAS las versiones anteriores. Todos comparten:
- Fondo #191919 (se funde con Notion, sin bordes blancos).
- Se adaptan a la altura del bloque: NUNCA aparece barra de desplazamiento.
- Se reajustan solos al redimensionar y al cargar la fuente.

## Cómo se adaptan (dos comportamientos)

**Escalado a la caja** (hud, radar, barras, reloj, pomodoro, frases, dado, titulo, cita):
el widget crece o encoge como una unidad para caber perfecto en el alto y ancho que le des.
Ponle la altura que quieras: el contenido se acomoda solo, siempre centrado.

**Relleno de altura** (notas, marco):
llenan todo el bloque. En notas, la lista de notas se desplaza por dentro con la barra
oculta (arrastra o usa la rueda), así puedes tener muchas notas sin que encoja el texto.
En marco, la imagen cubre todo el espacio disponible.

## Instalación
Sube los 11 a tu repositorio arcanum-widgets de GitHub reemplazando los viejos.
Los nombres de archivo no cambian, así que las URLs que ya tienes en Notion siguen sirviendo.

## Base de tus links
https://emprendedorinteligente1502-crypto.github.io/arcanum-widgets/ARCHIVO.html

Archivos: hud · radar · barras · reloj · pomodoro · notas · frases · marco · dado · titulo · cita

## Parámetros (sin cambios)
- Todos: ?titulo=Tu%20texto
- hud/radar/barras: ?api=URL_DEL_WORKER (modo automático) o los parámetros de la fórmula
- reloj: ?formato=24
- pomodoro: ?trabajo=50&descanso=10&largo=20&sonido=1
- notas: ?id=unico (para varias bitácoras distintas)
- frases: ?frases=Frase 1 — Autor|Frase 2 — Autor
- marco: ?titulo=&tag=&img=URL
- dado: ?caras=6
- titulo/cita: ?texto=&sub= / ?texto=&autor=
