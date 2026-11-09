# profmasar-test

Testseite für den Entwurf der Homepage profmasar.at (Stand v8, 2026-11-09).

Live: https://prof-masar.github.io/profmasar-test/

## Zweck

Nur zum Ansehen und Testen. Die Seite soll nicht in Suchmaschinen erscheinen:
`index.html` enthält `<meta name="robots" content="noindex">` und `robots.txt` sperrt alle Crawler.

## Inhalt

* `index.html`: die Startseite (eine Datei, alle Bilder und Schriften eingebettet, keine externen Anfragen)
* Keine Downloads (seit 2026-11-09). Der frühere Stand mit `downloads/` liegt im Branch `archiv-v7b-mit-downloads`.
* `robots.txt`, `.nojekyll`

Alle Links sind relativ. Der Inhalt kann später 1:1 auf den eigenen Webspace kopiert werden.

## Änderungen veröffentlichen

```
git add -A
git commit -m "Beschreibung der Änderung"
git push
```

Nach etwa 1 bis 2 Minuten ist die Änderung live.
