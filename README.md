# HTML-Website: Über mich, 360° Projekte, Kontakt

Diese Website besteht aus:

- `index.html`
- `style.css`

## Anpassen

In `index.html` kannst du folgende Texte ändern:

- `Dein Name`
- Beschreibung im Abschnitt „Über mich“
- Projekttitel und Projektbeschreibungen
- Links bei „Projekt öffnen“
- Kontaktformular

## Kontaktformular

Das Formular ist optisch fertig, verschickt aber noch keine E-Mails.

Damit es funktioniert, brauchst du z. B.:

- Formspree
- Netlify Forms
- eigenes PHP-Script
- anderes Formular-Backend

Dann wird im Formular diese Zeile angepasst:

```html
<form class="contact-form" action="" method="post">
```

## GitHub Pages

1. Repository erstellen.
2. Dateien hochladen.
3. Settings → Pages öffnen.
4. Source: Deploy from branch.
5. Branch: main, Ordner: /root.
