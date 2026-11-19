# TracciaLotto HACCP & DVR

## Guida rapida per pubblicare online e creare l'APK Android
1. Carica tutti i file di questa cartella su una nuova repository GitHub (es. `traccialotto-haccp-dvr`).
2. Collega la repository su **Vercel** (o Netlify / Cloudflare Pages) con comando di build `npm run build` e cartella output `dist`.
3. Copia l'URL HTTPS generato, vai su **https://www.pwabuilder.com**, incolla l'URL e clicca **Package for Stores -> Android -> Generate Package** per scaricare il file `app-release-signed.apk`.
