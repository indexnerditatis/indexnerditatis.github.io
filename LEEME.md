# Nerditas 2.0

Test de nerdidad para humanistas, filósofos y teólogos, en español, italiano e inglés.
Funciona sin conexión una vez instalada y no guarda ni envía ningún dato.

## Instalarla en el teléfono

Abre la dirección de la app **una vez con conexión** y:

- **iPhone (Safari):** botón Compartir → «Añadir a pantalla de inicio».
- **Android (Chrome):** menú ⋮ → «Instalar app» o «Añadir a pantalla de inicio».

## Actualizarla

Al subir cambios, sube también el número de versión en `sw.js` (`const CACHE = "nerditas-v2.0.1"`, etc.).
Los teléfonos reciben la versión nueva la próxima vez que abran la app con conexión.

## Contenido

- `index.html`: la app (preguntas, cálculo y pantallas).
- `sw.js`: guarda la app en el teléfono para el uso sin conexión.
- `manifest.webmanifest` e `icons/`: nombre, colores e icono de la app instalada.
- `fonts/`: IM Fell English y JetBrains Mono, con licencia libre SIL Open Font License (textos incluidos).
