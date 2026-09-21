# Galaxia de flores amarillas 🌻

Un regalo interactivo para teléfono, en un único `index.html` con HTML, CSS y JavaScript.

## Recorrido

1. Galaxia dorada con brazos espirales, profundidad, 2,400 partículas y flores en órbita.
2. Juego de plataformas en pixel art con una niñita, 12 flores y tres zonas: sendero, río y jardín. El recorrido mide 4,100 unidades, frente a las 2,200 anteriores.
3. Ramo animado final con nombres y, si lo escribiste, tu mensaje personalizado.

La niña tiene aceleración y frenado suaves, brazos y piernas coordinados, cabello en movimiento y respuesta al aterrizar. Controles: botones táctiles; flechas/A/D para caminar y espacio/arriba/W para saltar. No hay enemigos ni cronómetro. Puedes saltar etapas o repetir el recorrido.

## Tu mensaje

Al final abre **✧**. Introduce los nombres separados por comas y un mensaje opcional de hasta 800 caracteres; copia el enlace.

- Una persona: título en singular.
- Varias personas: título en plural.
- Cualquier nombre o grupo recibe exactamente el mensaje que escribas.
- Si el campo queda vacío, no aparece ninguna carta.
- Ya no hay mensajes ni grupos preestablecidos.

Los enlaces usan `?para=...&mensaje=...`. Admiten acentos, emojis y saltos de línea. El mensaje se muestra como texto, nunca como HTML. Los nombres y el mensaje son visibles en la URL; el generador discreto no está protegido por contraseña. Los enlaces antiguos con nombres siguen funcionando, pero ya no generan cartas automáticas.

## Canción

La página usa **`Flores_amarillas.mp3`**, con F mayúscula, junto a `index.html`, como el archivo subido al repositorio. El nombre distingue mayúsculas y minúsculas.

La música intenta comenzar al abrir la página. Si el navegador bloquea el inicio automático con sonido, se reintenta con el primer toque. El botón superior permite pausarla y reanudarla. Se pausa al ocultar la pestaña. Si falta el archivo o no carga, el recorrido funciona sin sonido.

## GitHub Pages

**Settings → Pages → Deploy from a branch → main → / (root) → Save**. Si ya está configurado, los cambios en `main` se publican automáticamente. Genera los enlaces desde la página publicada.

## Verificación

Comprobadas la sintaxis, las llamadas de dibujo, el recorrido físico completo con las 12 flores, las plataformas, el final, el reinicio y los saltos. Comprobados los mensajes con emojis, saltos de línea, texto HTML literal y campos vacíos. La revisión visual y la reproducción del MP3 en un teléfono real siguen pendientes.
