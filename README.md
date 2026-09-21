# Un universo de flores amarillas

Experiencia móvil en un único `index.html`, con HTML, CSS y JavaScript sin dependencias externas.

## Recorrido

1. Toca la chispa: el universo se expande y aparece una flor amarilla.
2. Recoge siete estrellas en una órbita con perspectiva. Sin cronómetro ni penalizaciones.
3. Se revela un ramo animado de 14 flores: girasoles, margaritas, tulipanes, rosas, narcisos y cempasúchil.

La profundidad usa proyección matemática en Canvas y transformaciones CSS/SVG; no requiere WebGL. El sonido de las estrellas es opcional. Hay botones para saltar las etapas, repetir y navegación por teclado. Respeta la preferencia de movimiento reducido y pausa al ocultar la pestaña.

## Enlaces personalizados

Al final del recorrido, abre el símbolo discreto **✧**, escribe nombres separados por comas y pulsa **Copiar enlace**. También hay un botón para cargar los tres nombres.

- Un nombre: encabezado personalizado sin carta.
- Varios nombres: encabezado en plural.
- Exactamente **Yuliana, Naomi y Esthefanía**: aparece la carta especial de amistad. El orden, las mayúsculas y los acentos no afectan la detección.
- Otros grupos: flores y nombres, sin la carta especial.

Los enlaces usan `?para=Nombre` o nombres separados por comas. Los enlaces anteriores de una persona siguen funcionando. El nombre es texto visible en la URL; el generador es discreto, no una función protegida por contraseña. La personalización no utiliza almacenamiento ni servicios externos.

## Publicación

En GitHub: **Settings → Pages → Deploy from a branch → main → / (root) → Save**. Si ya está configurado, GitHub Pages publicará los cambios de `main` automáticamente. Abre la página publicada para copiar enlaces compartibles; los archivos locales no se pueden compartir por URL.

## Edición

Todo está en `index.html`. La carta está en `#dedication`, las reglas de nombres en `parseNames` e `isSpecial`, y las flores en `arrangements` y `drawFlower`.

## Verificación

Se comprobó la sintaxis y la lógica de las transiciones, siete capturas únicas, reinicio, saltos, 14 flores, enlaces y reglas de dedicatorias. La revisión visual en un navegador móvil real sigue pendiente.
