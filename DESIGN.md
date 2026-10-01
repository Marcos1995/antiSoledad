# Design

Tono: calma, calle, caminar. Verde de salud, sin gesto de citas ni swipe.
Mapa: teselas OSM, punto verde = tú, punto hueco = encuentro. Atribución visible.
Fuente: system-ui. Radio: 10px. Espacio: 4 8 12 16 24 32 48 64.
Columna `min(100% - 2rem, 36rem)`. Una acción por vista.

| | bg | surface | ink | muted | line | accent | on |
|---|---|---|---|---|---|---|---|
| light | `#FAFAF9` | `#FFFFFF` | `#1C1917` | `#57534E` | `#E7E5E4` | `#0F7B5F` | `#FFFFFF` |
| dark | `#0C0A09` | `#1C1917` | `#FAFAF9` | `#A8A29E` | `#292524` | `#4FD1A5` | `#0C0A09` |

Acento solo en el botón principal, la opción activa y el punto «en línea».
Error: `#9F1239` / `#FECDD3`, siempre con texto.
