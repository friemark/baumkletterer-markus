# Baumkletterer Markus – Docker-Demo

## Lokal starten
Voraussetzung: Docker ist installiert.

```bash
docker build -t baumkletterer-demo .
docker run --rm -p 8080:80 baumkletterer-demo
```

Dann im Browser `http://localhost:8080` öffnen.

## Veröffentlichen
Das Image kann in eine Container-Registry (z. B. Docker Hub) hochgeladen und anschließend bei einem Container-Host gestartet werden.

## Vor einer echten Veröffentlichung prüfen
- E-Mail-Adresse und Kontaktdaten kontrollieren.
- Impressum und Datenschutzerklärung ergänzen.
- Bildrechte und Einverständnis abgebildeter Personen klären.
- Leistungsbeschreibungen und rechtliche Angaben prüfen.

Diese Demo enthält statische Dateien und benötigt keine Datenbank.
