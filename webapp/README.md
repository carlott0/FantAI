# FantAI — sito vetrina

Landing page statica per presentare FantAI in vista della pubblicazione su Google Play. Non richiede backend, database o processo di build.

## Anteprima locale

```powershell
cd webapp
python -m http.server 8080
```

Aprire `http://localhost:8080`.

## Pubblicazione

Il workflow in `.github/workflows/pages.yml` pubblica automaticamente questa cartella su GitHub Pages a ogni push su `main`.

Nel repository GitHub aprire **Settings → Pages** e impostare **Source: GitHub Actions**. Il sito sarà disponibile su `https://carlott0.github.io/FantAI/`.
