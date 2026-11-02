# profmasar-test

Testseite für den Entwurf der Homepage profmasar.at (Stand v6).

Live: https://prof-masar.github.io/profmasar-test/

## Zweck

Nur zum Ansehen und Testen. Die Seite soll nicht in Suchmaschinen erscheinen:
`index.html` enthält `<meta name="robots" content="noindex">` und `robots.txt` sperrt alle Crawler.

## Inhalt

* `index.html`: die Startseite (eine Datei, alle Bilder und Schriften eingebettet, keine externen Anfragen)
* `downloads/`: die freigegebenen Schüler PDFs
* `robots.txt`, `.nojekyll`

Alle Links sind relativ. Der Inhalt kann später 1:1 auf den eigenen Webspace kopiert werden.

## Änderungen veröffentlichen

```
git add -A
git commit -m "Beschreibung der Änderung"
git push
```

Nach etwa 1 bis 2 Minuten ist die Änderung live.
