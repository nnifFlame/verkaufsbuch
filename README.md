# Verkaufsbuch für Android

Deine manuelle Übersicht für Verkäufe auf selbst angelegten Verkaufsseiten: Versand, Abholung und Jahressummen in Euro.

## App herunterladen

**[Verkaufsbuch für Android herunterladen](https://github.com/nnifFlame/verkaufsbuch/releases/latest/download/Verkaufsbuch-Android.apk)**

Voraussetzung: Android 8.0 oder neuer. Die APK auf dem Android-Gerät öffnen und installieren. Falls Android danach fragt, für den verwendeten Browser oder Dateimanager „Aus dieser Quelle zulassen“ aktivieren.

## Funktionen

- Artikel, Preis, Verkaufsdatum und optionale Notiz eingeben.
- Versand oder Abholung auswählen.
- Für jedes Jahr Versand Gesamt, Abholung Gesamt und Insgesamt anzeigen.
- Verkäufe bearbeiten und nach Bestätigung löschen.
- Stückzahlen erfassen und zwischen Gesamtpreis und Preis pro Stück wechseln; der Gesamtbetrag wird sofort berechnet.
- Unter „Analysen“ sieben Diagramme ansehen: Monatsumsätze, verkaufte Stück pro Monat, Versand/Abholung nach Umsatz, Jahresvergleich, Top 5 Einzelverkäufe sowie Anzahl Verkäufe und Umsatz je Verkaufsseite.
- Eigene Verkaufsseiten ohne vorgegebene Anbieter anlegen und wieder auswählen.
- Bis zu 10 Bilder pro Verkauf als lokale JPEG-Kopien hinzufügen, ansehen und entfernen (Quelldatei bis 25 MB, lange Kante bis 1600 Pixel). Originalbilder bleiben unverändert.
- Blacklist mit Benutzernamen, Problemmarkierung, Notizen und bis zu 10 Fotos pro Nutzer verwalten.
- Blacklist-Nutzer optional Verkäufen zuordnen; gespeicherte Hinweise direkt im Verkauf sehen.
- Bei Bildern für Verkäufe und Blacklist zwischen Kamera und Fotobibliothek wählen.
- Offline arbeiten; Verkäufe bleiben lokal auf dem Gerät.

Die Summen beziehen sich auf Verkaufspreise. Porto und Gewinn werden nicht separat berechnet. Es gibt keine Verbindung zu Willhaben und keinen automatischen Import.

## Updates

Neue APK-Versionen erscheinen unter [Releases](https://github.com/nnifFlame/verkaufsbuch/releases). Eine neue Version wird über die bestehende App installiert. Dafür bleiben App-ID und Signaturschlüssel unverändert.

Ab Version 1.1 prüft die App beim Start automatisch auf neue Versionen. Über „Nach Updates suchen“ ist die Prüfung auch manuell möglich. Neue Versionen werden mit Neuerungen und einem Download-Button angezeigt. Der Download öffnet sich im Browser; anschließend wird die Installation der APK in Android bestätigt.

Version 1.1 muss einmal manuell über Version 1.0 installiert werden. Die bestehende App dabei nicht deinstallieren. Die Updateprüfung lädt nur [Versionsinformationen](version.json) von GitHub; Verkäufe werden nicht hochgeladen.

## Prüfung und Daten

Version 1.4 ergänzt eine private Blacklist und die Fotoaufnahme über die Kamera-App. Bestehende Verkäufe, Verkaufsseiten und Bilder bleiben erhalten. Eine Nutzerzuordnung ist optional. Umbenennen erhält die Verknüpfungen; beim Löschen eines Blacklist-Nutzers werden nur dessen Eintrag, Bilder und Nutzerzuordnungen entfernt, die Verkäufe bleiben bestehen. 136 Java- und 88 SQLite-Prüfungen bestanden. APK-Signatur und unveränderter Signaturschlüssel wurden geprüft. Kameraaufnahme, Bilddarstellung und Installation von 1.4 sind hier noch nicht auf einem Android-Gerät oder Emulator getestet.

Es gibt derzeit keinen Datenexport und keine Cloud-Synchronisierung. Beim Deinstallieren oder Löschen der App-Daten gehen die gespeicherten Verkäufe und Bildkopien verloren.

Dieses Repository dient zur Verteilung der fertigen App und ihrer Versionsinformationen.

