# Galaxia de flores amarillas 🌻

Experiencia para teléfono en un solo `index.html`, con HTML, CSS y JavaScript.

## Recorrido

1. Toca la luz para entrar a una galaxia con anillo dorado, 1,800 partículas y girasoles en órbita.
2. Juega un pequeño nivel de plataformas en pixel art, con una niñita de cabello castaño y vestido turquesa: camina, salta y recoge siete flores. El paisaje usa tonos dorados, tierra, verdes y agua turquesa, con árboles otoñales y hojas animadas.
3. Al terminar, se revela un ramo de 14 flores de seis tipos y la dedicatoria correspondiente.

Controles móviles: izquierda, derecha y SALTAR. En computadora: flechas o A/D, y espacio, arriba o W para saltar. El nivel no tiene enemigos ni cronómetro. Incluye saltar etapas y repetir.

## Añadir la canción

Sube tu archivo con el nombre exacto **`flores_amarillas.mp3`** a la raíz del repositorio, junto a `index.html`:

- `index.html`
- `flores_amarillas.mp3`
- `README.md`

Usa **Add file → Upload files**, selecciona el MP3 y guarda los cambios. La canción se intenta reproducir desde la entrada a la página. Si el navegador bloquea el autoplay con sonido, se reintenta con el primer toque. Se repite en bucle y se pausa con el botón musical superior. Si el navegador impide el primer intento, toca el botón musical. Si falta el MP3, el recorrido sigue funcionando sin sonido. La música se pausa al ocultar la pestaña.

## Dedicatorias

Abre **✧** al final, escribe nombres separados por comas y pulsa **Copiar enlace**. El campo empieza vacío, sin ejemplos ni botones con nombres.

- Un nombre: flores a su nombre, sin carta especial.
- Varios nombres: título en plural.
- Exactamente Yuliana, Naomi y Esthefanía: carta de amistad especial. Acepta otro orden, mayúsculas y nombres sin acentos.
- Otros grupos: nombres y flores, sin esa carta.

El generador está discreto, no protegido por contraseña. Los nombres son visibles en la URL. Los enlaces anteriores con `?para=Nombre` siguen funcionando.

## Publicación

GitHub **Settings → Pages → Deploy from a branch → main → / (root) → Save**. Si Pages ya está activo, publicará los cambios automáticamente. Genera los enlaces desde la página publicada, no desde un archivo local.

## Verificación

Pruebas ejecutadas: sintaxis, renderizado por llamadas Canvas, simulación completa del recorrido usando movimiento/saltos y colisiones reales, recogida de siete flores, revelación del ramo, reinicio, salto de etapas y reglas de enlaces/dedicatorias. La reproducción del MP3 requiere que se suba el archivo; la revisión visual en un teléfono real sigue pendiente.
