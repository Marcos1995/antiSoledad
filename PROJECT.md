<!-- managed-by-telegram-cursor-bot:agent-kit -->
# Contexto del proyecto

## Produccion
- URL: https://github.com/Marcos1995/antiSoledad
- Vista: https://marcos1995.github.io/antiSoledad/ (repo público; Chrome)
- Vista local: `index.html`

## Estado
- Web estática: apodo, ánimo y tema; lista de quién está disponible; charla en vivo.
- Canal público ntfy.sh (sin clave). Aviso en pantalla: no escribir datos personales.
- Latido cada 10 min (3 min si hablas). Alguien sigue visible unos 14 min.
- Falta: cuentas, moderación y sala privada. ntfy.sh corta cerca de 250 mensajes/día por IP.

## Stack
- `index.html` (HTML, CSS y JS). Sin build.
- Relay: `https://ntfy.sh/` POST + EventSource. Temas `antisoledad-m95-ahora` y `antisoledad-m95-c-<id>-<id>`.

## Comandos utiles
- Instalar: nada
- Test: dos navegadores en la misma URL
- Dev: abrir `index.html` o `python -m http.server`

## Notas para el agente
- Supuesto: tú (no voseo); lista, no swipe. No es una app de citas.
- No poner claves ni otro host. El canal es público a propósito (decisión Laya).
- Lean kit (ver AGENTS.md)
