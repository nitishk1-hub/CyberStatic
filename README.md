# CyberStatic

Standalone CyberPross website source, mirrored from the production static directory on November 17, 2026.

## Pages

- `/` — CyberPross homepage
- `/products/` — All products
- `/products/cp-panel/` — CP-Panel product page
- `/products/security-scanner/` — Security Scanner product page

## Run locally

From the repository root on Ubuntu:

```bash
python3 -m http.server 8080
```

Open http://127.0.0.1:8080/.

## Deploy

The repository root is a ready-to-serve static site (HTML, CSS, JavaScript and SVG). Preserve paths under `assets/` and `products/` when deploying. The server's current static document root is `/var/www/cyberpross-recovered/cyberpross.cc/public`.

Source changes in this repository do not update production until deployed. The production server has its own atomic deployment and rollback workflow.

## Products

- [CP-Panel](https://github.com/nitishk1-hub/CP-Panel)
- [CyberPross Security Scanner](https://chromewebstore.google.com/detail/cyberpross-security-scann/edbncdajlofhbpejdnpjjgjlmbiemeie)
