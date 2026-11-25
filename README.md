# Weihnachtsmarkt 2026 – TV-Präsentation des Köcheclubs Werne

Endversion vom 17.11.2026 (Grundlage: „Version A“, Sieger der Mitglieder-Umfrage vom September 2026).

Aufruf: https://sire65.github.io/WM-Pr-s./

`index.html` ist eine einzige, eigenständige Datei und startet die TV-Präsentation. Dieselbe Präsentation ist in der
MarktKasse eingebaut und läuft am Stand automatisch auf dem Fernseher (`tv-player/weihnachtsmarkt-2026-version-a.html`).

## Was in der Endversion steckt

- Neues Rathaus-Bild als Hintergrund aller Folien (`assets/kasse-presentation/backgrounds/rathaus-werne-weihnachtsmarkt-v2.jpg`)
- Einheitliche Überschriften, Zierelemente und Abstände
- Preislisten mit den Preisen der Kasse, darunter Allergene/Zusatzstoffe je Artikel und die Pfandregel
- Mannschaftsfolie nur Text („Köcheclub Werne – seit 1991 in Werne“), Mitgliederfolien nur Vorname und gewählter Spruch,
  ohne Fotos; wer abgelehnt oder nicht geantwortet
  hat, ist ausgeblendet
- Wetterfolien zeigen das aktuelle Wetter für Werne (Open-Meteo, alle 30 Minuten neu)
- Keine Umfrage mehr (kein „Fertig – zur Umfrage“-Knopf, kein Anhalten auf der Schlussfolie)

Stand 25.11.2026 (Endversion · 2026-11-25):

- Neue Speisenfolien „Lust auf Grünkohl?“, „Lust auf Sauerkraut?“ und „Lust auf Kartoffeln?“: links das Gericht mit
  Mettendchen bzw. Heringsstipp, rechts ohne bzw. mit Kartoffelcreme, darunter Name und Preis aus der Kasse, unten rechts
  „Serviervorschlag“. Die Fotos sind Freisteller: Kassenfotos für Grünkohl und Sauerkraut, ein neues
  Foto für Kartoffeln mit Heringsstipp.
- Klaus, Reinhilde, Marianne und Karla erscheinen jetzt mit Vorname und Spruch.
- Nachgezogen aus der Kasse: Preisfolien als Speisekarte, Bühnenprogramm in Spalten, Öffnungszeiten Weihnachtsmarkt
  und Köcheclub, Annes Spruch.

Die Datei wird mit `tools/tv-endversion-bauen.cjs` aus dem Kasse-Repository erzeugt. Der Stand der Umfrage ist als Tag
`umfrage-2026-09` erhalten, die Fassung mit Fotos als Tag `mit-fotos-2026-11-17`.

## Auf dem Fernseher über iPad

Auf dem iPad die Adresse in Safari öffnen, die Präsentation starten, anschließend im Kontrollzentrum
„Bildschirmsynchronisierung“ wählen und das Apple TV auswählen. Für Vollbild einmal auf den Bildschirm tippen und
„Vollbild“ verwenden.
