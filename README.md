# Verkaufsbuch für Android

Deine manuelle Übersicht für Willhaben-Verkäufe: Versand, Abholung und Jahressummen in Euro.

## App herunterladen

**[Verkaufsbuch für Android herunterladen](https://github.com/nnifFlame/verkaufsbuch/releases/latest/download/Verkaufsbuch-Android.apk)**

Voraussetzung: Android 8.0 oder neuer. Die APK auf dem Android-Gerät öffnen und installieren. Falls Android danach fragt, für den verwendeten Browser oder Dateimanager „Aus dieser Quelle zulassen“ aktivieren.

## Funktionen

- Artikel, Preis, Verkaufsdatum und optionale Notiz eingeben.
- Versand oder Abholung auswählen.
- Für jedes Jahr Versand Gesamt, Abholung Gesamt und Insgesamt anzeigen.
- Verkäufe bearbeiten und nach Bestätigung löschen.
- Stückzahlen erfassen und zwischen Gesamtpreis und Preis pro Stück wechseln; der Gesamtbetrag wird sofort berechnet.
- Unter „Analysen“ fünf Diagramme ansehen: Monatsumsätze, verkaufte Stück pro Monat, Versand/Abholung nach Umsatz, Jahresvergleich und Top 5 Einzelverkäufe.
- Offline arbeiten; Verkäufe bleiben lokal auf dem Gerät.

Die Summen beziehen sich auf Verkaufspreise. Porto und Gewinn werden nicht separat berechnet. Es gibt keine Verbindung zu Willhaben und keinen automatischen Import.

## Updates

Neue APK-Versionen erscheinen unter [Releases](https://github.com/nnifFlame/verkaufsbuch/releases). Eine neue Version wird über die bestehende App installiert. Dafür bleiben App-ID und Signaturschlüssel unverändert.

Ab Version 1.1 prüft die App beim Start automatisch auf neue Versionen. Über „Nach Updates suchen“ ist die Prüfung auch manuell möglich. Neue Versionen werden mit Neuerungen und einem Download-Button angezeigt. Der Download öffnet sich im Browser; anschließend wird die Installation der APK in Android bestätigt.

Version 1.1 muss einmal manuell über Version 1.0 installiert werden. Die bestehende App dabei nicht deinstallieren. Die Updateprüfung lädt nur [Versionsinformationen](version.json) von GitHub; Verkäufe werden nicht hochgeladen.

## Prüfung und Daten

Version 1.2 enthält Analysen und Stückzahlen. Vorhandene Einträge werden mit Stückzahl 1 und Gesamtpreis übernommen. 99 automatisierte Berechnungs-, Analyse- und Updateprüfungen bestehen. Die SQL-Datenübernahme wurde mit SQLite geprüft. APK-Signatur und identischer Signaturschlüssel zur Vorversion wurden geprüft. Die Update-Erkennung wurde am 23.09.2026 von einem Nutzer auf einem Android-Handy erfolgreich getestet. Ein vollständiger Gerätetest aller Funktionen steht noch aus.

Es gibt derzeit keinen Datenexport und keine Cloud-Synchronisierung. Beim Deinstallieren oder Löschen der App-Daten gehen die gespeicherten Verkäufe verloren.

Dieses Repository dient zur Verteilung der fertigen App und ihrer Versionsinformationen.

