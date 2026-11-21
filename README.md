# Greifarm · Schul-Edition

Greifautomaten-Spiel für den Beamer, gesteuert per Handy. Homburgisches Gymnasium Nümbrecht.

## Spielen
1. Die Seite über GitHub Pages auf dem Laptop öffnen, einmal klicken (Ton an), **F** für Vollbild.
2. Handys scannen den QR-Code, geben einen Namen ein und stellen sich an.
3. Joystick bewegen, **GREIFEN!** drücken.

## Tasten am Laptop
- **E**: Einstellungen (Logo, Farben, Preise, Versuche, Greifkraft, Anzahl Automaten)
- **F**: Vollbild
- **K**: mit Tastatur mitspielen (Pfeile + Leertaste)
- **M**: Ton an/aus

## Schullogo
Logo in den Einstellungen hochladen oder als `logo.png` in dieses Repo legen.

## Abholscheine
Bei Preisen mit „Schein“ bekommt der Gewinner einen QR-Code aufs Handy. An der Preisausgabe mit einer normalen Handy-Kamera scannen und als eingelöst markieren. Jeder Schein funktioniert nur einmal.

## Technik
Eine einzige HTML-Datei. Verbindung Handy ↔ Laptop per WebRTC über den kostenlosen PeerJS-Server. Laptop und Handys brauchen Internet.
