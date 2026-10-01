<!-- managed-by-telegram-cursor-bot:agent-kit -->
# Contexto del proyecto

## Produccion
- URL: https://github.com/Marcos1995/antiSoledad
- Vista: https://marcos1995.github.io/antiSoledad/ (repo público; Chrome)
- Vista local: `index.html`

## Estado
- Web estática: ubicación del navegador, mapa OSM y gente a menos de 1,5 km para quedar en persona.
- La zona publicada se redondea a ~100 m. El hilo solo sirve para ponerse de acuerdo y salir.
- Canal público ntfy.sh (sin clave). Latido cada 10 min (3 min si te mueves). Visible unos 14 min.
- Falta: cuentas, moderación y sala privada. ntfy.sh corta cerca de 250 mensajes/día por IP.

## Stack
- `index.html` (HTML, CSS y JS). Sin build. Mapa: teselas `tile.openstreetmap.org`, sin librería.
- Relay: `https://ntfy.sh/` POST + EventSource. Temas `antisoledad-m95-ahora` y `antisoledad-m95-c-<id>-<id>`.
- Ubicación: hace falta https o localhost (no `file://`).

## Comandos utiles
- Instalar: nada
- Test: dos navegadores en la misma URL
- Dev: abrir `index.html` o `python -m http.server`

## Notas para el agente
- Supuesto: tú (no voseo); quedar a pie, no charla desde casa. No es una app de citas.
- No poner claves ni otro host. Canal público y mapa OSM (decisiones Laya).
- Lean kit (ver AGENTS.md)
