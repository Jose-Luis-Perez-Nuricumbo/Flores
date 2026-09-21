# Flores amarillas 🌼

Un jardín animado para regalar un poquito de sol. HTML, CSS y JavaScript en un solo `index.html`, sin dependencias ni archivos externos.

## Verlo

Descarga `index.html` y ábrelo en un navegador moderno. Pulsa **Abrir mi regalo**.

- Siete flores ilustradas con SVG, crecimiento y movimiento suave.
- Luciérnagas y partículas al tocar el jardín.
- Carta, música ambiental original opcional y dedicatoria por nombre.
- Diseño adaptable, controles por teclado y respeto por la preferencia de movimiento reducido.

## Publicarlo con GitHub Pages

En el repositorio, abre **Settings → Pages**. En **Build and deployment**, selecciona **Deploy from a branch**, rama **main** y carpeta **/ (root)**. Guarda y espera a que GitHub muestre el enlace de la página.

Después de publicarlo, el botón **Dedicar** copia un enlace con el nombre de la persona. El nombre queda visible en la URL (`?para=Nombre`). Cuando se abre como archivo local, se indica que es necesario publicarlo para compartir un enlace.

## Personalizar

En `index.html`, cambia la dedicatoria dentro de `<dialog id="letter">`, los textos de la sección `.hero` o los colores de `:root`. El CSS está en `<style>` y JavaScript en `<script>`.

La música solo se reproduce al activarla; no se descarga ni utiliza ninguna canción de terceros.
