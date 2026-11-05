# Petal Link

Hand it a link. Watch the bouquet fold itself into a code you can scan.

Petal Link turns any URL into a working QR code with a small animation: a bouquet of flowers breaks apart, and every petal and bud flies into place as a module of the code. The gaps fill in with colors from the nearest flower, so the finished code keeps the bouquet's palette.

**Live demo:** [mohit7e.github.io/petal-link](https://mohit7e.github.io/petal-link/)

Also featured at [ehmtoi.com/projects](https://ehmtoi.com/projects/index.html).

## Features

- Accepts links with or without `https://`
- Every finished code is darkened enough to scan reliably with a phone camera
- Copy the link, or reset for a new bouquet
- Light and dark mode
- Respects reduced-motion settings
- Works on desktop and phone

## Run it

It's a single HTML file with no build step. Open `index.html` in a browser.

QR encoding uses [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator), loaded from a CDN.

## Author

[Mohit Eedupuganti](https://ehmtoi.com)
