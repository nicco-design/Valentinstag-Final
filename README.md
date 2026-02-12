# Valentinstag Website

Diese Seite ist für **GitHub Pages** vorbereitet.

## Deployment über GitHub Pages

1. Repository auf GitHub pushen.
2. In GitHub zu **Settings → Pages** gehen.
3. Bei **Build and deployment** auswählen:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (oder dein Branch)
   - **Folder:** `/ (root)` **oder** `/docs`
4. Speichern.

Die Website liegt jetzt in beiden Varianten bereit:
- `index.html` im Root
- `docs/index.html` im `docs`-Ordner

Damit funktioniert die Seite unabhängig davon, ob in GitHub Pages `/ (root)` oder `/docs` eingestellt ist.

## Falls weiterhin 404 kommt

- Prüfen, ob wirklich der richtige Branch veröffentlicht wird.
- Bei Projekt-Repos die korrekte URL nutzen: `https://<user>.github.io/<repo>/`
- Nach Änderungen 1–2 Minuten warten (Pages-Deploy kann kurz dauern).
