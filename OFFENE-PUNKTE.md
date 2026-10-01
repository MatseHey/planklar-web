# Offene Prüfpunkte der Website

Diese Hinweise standen bis zum 01.10.2026 gelb markiert (`<mark class="todo">`) direkt auf den Seiten.
Sie sind dort entfernt und hier gesammelt. Erledigte Punkte bitte streichen.

## Impressum (`impressum.html`, Abschnitt „Bildnachweise“)

- [ ] Apple verlangt die Quellenangabe „Apple Weather“ samt Link in der App (Umsetzung:
  `WeatherAttributionView`, vor Release gegen die aktuelle WeatherKit-API prüfen). Am Wetter-Chip
  der Startseite (Karte des aktiven Trips) wird sie derzeit nicht angezeigt.

## Datenschutz (`datenschutz.html`) und Privacy Policy (`privacy.html`)

- [ ] **Titelbilder / Pexels-Altdaten** (DE: Abschnitt „Titelbilder“, EN: „Cover photos“).
  Trips, die vor der Umstellung angelegt wurden, können noch eine Bild-Adresse von Pexels als
  Titelbild gespeichert haben. Diese Bilder werden direkt von den Servern von Pexels geladen;
  dabei erhält Pexels technisch bedingt die IP-Adresse des Geräts.

  Ursprünglicher Absatz zum Wiedereinsetzen, solange solche Trips existieren können
  (streichen, sobald keine mehr vorhanden sind bzw. die Altlogik in `TripCoverImage` entfernt ist):

  > Trips, die vor der Umstellung angelegt wurden, können noch eine Bild-Adresse von Pexels als
  > Titelbild gespeichert haben. Diese Bilder werden direkt von den Servern von Pexels geladen;
  > dabei erhält Pexels technisch bedingt die IP-Adresse des Geräts (Rechtsgrundlage Art. 6 Abs. 1
  > lit. f DSGVO).

  > Trips created before this change may still have a Pexels image address stored as their cover.
  > Those images are loaded directly from Pexels' servers, so Pexels technically receives the
  > device's IP address (legal basis Art. 6(1)(f) GDPR).

- [ ] **WeatherKit / Drittland** (DE: Abschnitt „Wetterdaten (Apple WeatherKit)“, EN: „Weather“).
  Ob Apple bei WeatherKit-Abfragen selbst Daten speichert oder in Drittländer (USA) übermittelt,
  ist nicht verifiziert. Aktuelle Angaben von Apple zu WeatherKit einholen und ggf. einen
  Drittlandhinweis (DPF/SCC) in beiden Sprachen ergänzen.
