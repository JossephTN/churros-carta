# Carta digital — Churro's (Calama)

Página estática de la carta de [CHURRO'S](https://www.instagram.com/churros_cl/), servida
por GitHub Pages y enlazada desde el QR del local.

- `index.html` — la carta completa (fondo negro, opcionales como fichas, botón "Pedir por WhatsApp")
  y al final la tarjeta de reseña de Google Maps con premio (1 churro relleno de manjar gratis).
- `resena.html` — página puente de reseñas: paso 1 dejar la reseña, paso 2 ver la carta.
- `compartir.jpg`, `favicon-32.png`, `icono-512.png`, `apple-touch-icon.png` — imagen que aparece al
  compartir el link e íconos de la pestaña y del celular.
- `fuentes/` — Anton y Montserrat (licencia OFL, incluida).
- `impresos/qr-card-churros.png` — tarjeta vertical lista para imprimir en el local, con el
  QR que apunta a esta página.
- `impresos/story-resena-qr.png` / `story-resena-qr-4k.png` — tarjeta 1080x1920 (formato
  historia de Instagram, también en 4K) enfocada en la reseña de Google.

Este repo es público solo porque GitHub Pages gratis lo requiere — no contiene estrategia
de marca ni información interna del negocio, solo la página pública de la carta.

La carta se genera desde el repo privado del proyecto (`carta.json` + `scripts/impresos/generar_carta.py`);
no se edita a mano acá. Última actualización: 2026-10-13.
