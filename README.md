# planklar. – Website

Onepager, Datenschutzerklärung (DE/EN) und Impressum der iOS-App planklar.
Statisches HTML ohne Build-Schritt, ausgeliefert über GitHub Pages:
https://matsehey.github.io/planklar-web/

- `index.html` – Onepager mit Warteliste (per Mail)
- `datenschutz.html` / `privacy.html` – Datenschutzerklärung DE/EN, inhaltlich synchron halten
- `impressum.html` – Impressum nach § 5 DDG
- `style.css` – Farben aus `AppTheme.swift` der App, Dark Mode per `prefers-color-scheme`
- `assets/` – Logo, Favicons, Hero-Mockup

Die Seite lädt nichts von Dritten (keine Schriften, kein Tracking, keine Cookies).
Offene Platzhalter sind auf der Seite gelb markiert (`<mark class="todo">`),
Prüfhinweise stehen als HTML-Kommentare im Quelltext.

Die App verlinkt Datenschutz und Impressum über `AppContact.websiteURL` –
ändert sich die Adresse (z. B. eigene Domain), dort und in App Store Connect anpassen.
