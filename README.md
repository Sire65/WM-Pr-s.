# Weihnachtsmarkt 2026 – TV-Präsentation des Köcheclubs Werne

Endversion vom 17.11.2026 (Grundlage: „Version A“, Sieger der Mitglieder-Umfrage vom September 2026).

Aufruf: https://sire65.github.io/WM-Pr-s./

`index.html` ist eine einzige, eigenständige Datei und startet die TV-Präsentation. Dieselbe Präsentation ist in der
MarktKasse eingebaut und läuft am Stand automatisch auf dem Fernseher (`tv-player/weihnachtsmarkt-2026-version-a.html`).

## Was in der Endversion steckt

- Neues Rathaus-Bild als Hintergrund aller Folien (`assets/kasse-presentation/backgrounds/rathaus-werne-weihnachtsmarkt-v2.jpg`)
- Einheitliche Überschriften, Zierelemente und Abstände
- Preislisten mit den Preisen der Kasse, darunter Allergene/Zusatzstoffe je Artikel und die Pfandregel
- Mitgliederfolien so, wie es jedes Mitglied in der Spruch-Auswahl gewählt hat; wer abgelehnt oder nicht geantwortet
  hat, ist ausgeblendet
- Keine Umfrage mehr (kein „Fertig – zur Umfrage“-Knopf, kein Anhalten auf der Schlussfolie)

Noch offen: Öffnungszeiten und Gesamtprogramm 2026.

Die Datei wird mit `tools/tv-endversion-bauen.cjs` aus dem Kasse-Repository erzeugt. Der Stand der Umfrage ist als Tag
`umfrage-2026-09` erhalten.

## Auf dem Fernseher über iPad

Auf dem iPad die Adresse in Safari öffnen, die Präsentation starten, anschließend im Kontrollzentrum
„Bildschirmsynchronisierung“ wählen und das Apple TV auswählen. Für Vollbild einmal auf den Bildschirm tippen und
„Vollbild“ verwenden.
