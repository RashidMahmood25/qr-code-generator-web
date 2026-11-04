# QR Code Generator (Web)

A single-page, free QR code generator. Type any text or link, pick a size, and
download the QR code as a PNG image. No sign-up, no server — everything runs in
your browser.

## How to use

1. Open `index.html` in any modern browser (double-click the file, or serve the
   folder with any static server).
2. Type your text or link, choose a size, press **Generate QR Code**.
3. Press **Download PNG** to save the code as an image.
4. Scan it with your phone camera to test it before printing.

An internet connection is needed once, because the QR drawing library
(qrcodejs) loads from a CDN. Your text is never sent to any server.

## What was practiced

- Single self-contained HTML/CSS/JS page
- DOM events (click + Enter key), input validation
- Using a small open-source JS library (qrcodejs, MIT)
- Exporting a canvas/image as a downloadable PNG file
