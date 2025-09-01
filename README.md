# NekoTopia Website

Dies ist die statische Website für **NekoTopia**.  
Die Seite **Geschichte** wurde als blätterbares *Kapitel-Buch* umgesetzt. Kapitel werden durch `<h2>`-Überschriften definiert; die Fortschrittsanzeige übernimmt automatisch den Titel der Überschrift.

## Struktur
- `index.html` – Startseite
- `geschichte.html` – Geschichte (Flipbook mit Kapiteln über `<h2>`)
- `charakter.html`, `weltkarte.html`, `how-to.html`, `updates.html`
- `impressum.html`, `datenschutz.html`, `cookie-einstellungen.html`
- `style.css`
- `assets/` – Bilder, Logos, usw. (falls vorhanden)

## Lokale Vorschau
Einfach die `index.html` im Browser öffnen. Die Seite ist **ohne Build-Schritt** lauffähig.

## Kapitel pflegen
Setze in `geschichte.html` im `<main class="page">` vor jeden Abschnitt eine Überschrift `<h2>`.  
Jede `<h2>` startet automatisch ein neues Kapitel und ihr Text erscheint in der Fortschrittsanzeige.

## Deployment auf GitHub Pages
1. Neues Repo anlegen (öffentlich oder privat mit Pages).
2. Inhalt dieses Ordners in das Repo pushen (Branch `main`).
3. **GitHub Pages** in den Repo-Einstellungen aktivieren und **Branch: `main`, Folder: `/ (root)`** wählen.
4. Nach wenigen Minuten ist die Seite live.

---
Stand: 2025-09-01
