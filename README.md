[README.md](https://github.com/user-attachments/files/31922891/README.md)
# Révise avec Moi! 🇫🇷

Web app educativa standalone per il ripasso del francese (2ª e 3ª media).

## Pubblicazione su GitHub Pages

1. Crea un nuovo repository GitHub pubblico, per esempio `revise-avec-moi`.
2. Carica **tutti i file di questa cartella nella root del repository**.
3. Vai in **Settings → Pages**.
4. In **Build and deployment → Source** scegli **Deploy from a branch**.
5. Seleziona **main** e **/(root)**, quindi **Save**.
6. Quando GitHub Pages mostra il sito come pubblicato, apri il link indicato in **Settings → Pages**.

URL tipico:
`https://TUO-USERNAME.github.io/revise-avec-moi/`

## iPhone

Apri il sito in Safari → Condividi → **Aggiungi alla schermata Home**. Il progetto contiene manifest, icona Apple e service worker per un'esperienza più simile a un'app e per la cache offline dopo la prima visita.

## File principali

- `index.html` — app completa
- `manifest.webmanifest` — metadati web app/PWA
- `service-worker.js` — cache offline
- `.nojekyll` — impedisce la trasformazione Jekyll
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` — icone
