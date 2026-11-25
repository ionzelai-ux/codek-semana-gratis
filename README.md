# Semana gratis · CODEK Training

Página que abre el QR de la puerta del gimnasio (https://semana.codektraining.es).
Las reservas van al Apps Script del CRM (`action=reservar`, `tipo=prueba`) con `origen`
según el `?src=` del QR (`puerta`, `hall`). Prueba sin tocar el CRM con `?demo=1`.

- `index.html` — la página. Arriba del `<script>` está `CFG` (dirección, puerta, Maps, WhatsApp).
- `carteles.html` / `carteles.pdf` — los dos carteles para imprimir.
- `hacer-qr.py` — regenera `qr-puerta.svg` y `qr-hall.svg` (`pip install segno`).
