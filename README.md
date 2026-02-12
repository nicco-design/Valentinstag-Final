# Valentinstag Website

Diese Seite ist für **GitHub Pages** vorbereitet.

## Deployment über GitHub Pages

1. Repository auf GitHub pushen.
2. In GitHub zu **Settings → Pages** gehen.
3. Bei **Build and deployment** auswählen:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (oder dein Branch)
   - **Folder:** `/ (root)` **oder** `/docs`
4. **Save** klicken.
5. Nach dem Speichern zeigt GitHub oben in **Settings → Pages** direkt den Live-Link an (Format: `Your site is live at ...`).

## Wo ist die URL?

Die URL hängt davon ab, ob es ein **User/Org-Repo** oder ein **Projekt-Repo** ist:

- **User/Org-Repo** (Repo-Name ist exakt `<user>.github.io`):
  - URL: `https://<user>.github.io/`
- **Projekt-Repo** (normaler Repo-Name, z. B. `Valentinstag-Final`):
  - URL: `https://<user>.github.io/<repo>/`
  - Beispiel: `https://maxmustermann.github.io/Valentinstag-Final/`

Wichtig: Ob du `/ (root)` oder `/docs` wählst, ändert **nicht** das URL-Schema oben – nur den Ordner, aus dem veröffentlicht wird.

## Falls weiterhin 404 kommt

- Prüfen, ob wirklich der richtige Branch veröffentlicht wird.
- Prüfen, ob du die korrekte Projekt-URL nutzt: `https://<user>.github.io/<repo>/`
- In **Settings → Pages** nachsehen, ob dort die Seite als "live" angezeigt wird.
- Nach Änderungen 1–2 Minuten warten (Pages-Deploy kann kurz dauern).
