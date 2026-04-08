NUTZUNGSBEDINGUNGEN UND DATENSCHUTZERKLÄRUNG
Minewache Launcher

Version 1.0.7
Gültig ab: Februar 2026

================================================================================

1. HAFTUNGSAUSSCHLUSS

Der Minewache Launcher wird ohne Gewähr bereitgestellt.
Eine Haftung für Schäden, die durch Vorsatz oder grobe Fahrlässigkeit verursacht
wurden, bleibt unberührt.
Für sonstige Schäden wird keine Haftung übernommen.
Die Nutzung erfolgt auf eigene Verantwortung des Anwenders.

================================================================================

2. DATENSCHUTZ

Der Minewache Launcher verarbeitet grundsätzlich keine personenbezogenen Daten
automatisch oder ohne Ihre aktive Zustimmung. Ausnahmen sind nachfolgend
transparent beschrieben.

2.1 KEINE AUTOMATISCHE DATENSAMMLUNG
Der Launcher sammelt keine Nutzungsdaten, Telemetriedaten oder sonstigen
Informationen über Ihr Nutzungsverhalten – es sei denn, Sie nutzen aktiv die
unten beschriebene Funktion „Logs senden".

2.2 LOKALE DATENSPEICHERUNG
Alle vom Launcher verwalteten Daten werden ausschließlich lokal auf Ihrem
Computer gespeichert:
- Speicherort: %APPDATA%\Minewache-Launcher
- Gespeicherte Daten: Einstellungen, Authentifizierungstoken, Skin-Verlauf
- Diese Daten verlassen Ihren Computer nicht automatisch durch den Launcher

2.3 MICROSOFT/MOJANG AUTHENTIFIZIERUNG
Der Launcher verwendet die offiziellen Microsoft/Mojang OAuth-APIs zur
Authentifizierung:
- Die Anmeldung erfolgt direkt über Microsoft-Server
- Der Launcher speichert die von Microsoft bereitgestellten
  Authentifizierungstoken (Refresh-Tokens) lokal für automatische Anmeldung
- Ihre Anmeldedaten (Benutzername/Passwort) werden NIEMALS vom Launcher
  gespeichert oder verarbeitet – nur die von Microsoft ausgestellten Tokens
- Die Kommunikation erfolgt ausschließlich mit offiziellen Microsoft/Mojang-
  Servern über verschlüsselte Verbindungen (HTTPS)

2.4 MINECRAFT-ASSETS UND MODPACK-DOWNLOADS
Der Launcher lädt folgende Daten aus offiziellen und autorisierten Quellen:
- Minecraft-Dateien von offiziellen Mojang-Servern
- Modpack-Dateien vom autorisierten Minewache-Server (HTTPS)
- Skin-Daten von offiziellen Minecraft-Services-APIs
- Alle Downloads erfolgen ausschließlich über verschlüsselte Verbindungen (HTTPS)

2.5 KEINE WEITERGABE VON DATEN
Der Launcher gibt KEINE Daten automatisch an Dritte weiter. Es erfolgt keine
automatische Übermittlung von:
- Anmeldedaten oder Authentifizierungstoken
- Persönlichen Informationen
- Nutzungsstatistiken oder Telemetriedaten
- Spielverhalten oder sonstigen Aktivitätsdaten

2.6 FREIWILLIGES EINSENDEN VON LOGDATEIEN („LOGS SENDEN")
Der Launcher bietet die optionale Funktion „Logs senden" (Einstellungen →
System & Wartung), mit der Sie Logdateien zur Fehlerdiagnose über einen
Discord-Webhook an das Minewache-Team übermitteln können.

Diese Funktion ist AUSSCHLIESSLICH auf Ihre explizite Aktion hin aktiv:
- Es werden KEINE Logs automatisch oder im Hintergrund gesendet
- Erst wenn Sie den Button „Logs senden" und anschließend die gewünschten
  Dateien auswählen sowie den Upload bestätigen, werden Daten überstellt

Folgende Daten werden dabei übermittelt:
- Minecraft-Logdateien (latest.log, ältere Logs aus dem logs-Ordner)
- Crash-Reports (crash-reports/*.txt), falls vorhanden
- Debug-Scan-Dateien (debug_scans/*.txt), falls vorhanden und ausgewählt

Diese Dateien können enthalten:
- Installationspfade und Dateinamen auf Ihrem System
- Java-Versionsinformationen und JVM-Parameter
- Mod-Liste und Launcher-Konfiguration
- Fehlermeldungen und Stack-Traces

Bitte stellen Sie vor dem Senden sicher, dass die ausgewählten Dateien
KEINE für Sie vertraulichen Informationen enthalten. Die Daten werden
ausschließlich zur Fehlerdiagnose verwendet und nicht an Dritte weitergegeben.

================================================================================

3. RECHTLICHES

Mit der Nutzung des Minewache Launchers erklären Sie sich mit diesen Bedingungen
einverstanden.

================================================================================

4. FUNKTIONSWEISE DES LAUNCHERS

4.1 AUTHENTIFIZIERUNG
- Microsoft-Konto-Anmeldung über offizielle OAuth-Schnittstelle
- Lokale Speicherung von Refresh-Tokens für automatische Anmeldung
- Automatische Token-Aktualisierung bei Bedarf

4.2 MODPACK-VERWALTUNG
- Download und Installation von Minecraft-Mods und -Konfigurationen
- Automatische Updates des Modpacks
- Verwaltung von benutzerdefinierten Mods (nur für autorisierte Benutzer)

4.3 SKIN-VERWALTUNG
- Anzeige und Verwaltung von Minecraft-Skins
- Upload von benutzerdefinierten Skins über offizielle Mojang-APIs
- Lokaler Skin-Verlauf mit Vorschaubildern

4.4 LOGS SENDEN (FREIWILLIG)
- Optionaler Upload von Logdateien zur Fehlerdiagnose via Discord
- Nur auf explizite Nutzeraktion – kein automatischer Upload
- Ausführliche Beschreibung: siehe Abschnitt 2.6

================================================================================

5. SYSTEMANFORDERUNGEN UND INSTALLATION

5.1 INSTALLATIONSORT
Der Launcher wird standardmäßig installiert unter:
- %LOCALAPPDATA%\Minewache Launcher

5.2 ERFORDERLICHE BERECHTIGUNGEN
Der Launcher benötigt folgende Berechtigungen:
- Lese- und Schreibzugriff auf den Installationsordner
- Lese- und Schreibzugriff auf %APPDATA%\Minewache-Launcher
- Netzwerkzugriff für Downloads und Authentifizierung
- Berechtigung zum Starten von Minecraft (Java-Prozess)

================================================================================

6. ÄNDERUNGEN DER NUTZUNGSBEDINGUNGEN

Diese Nutzungsbedingungen können jederzeit geändert werden. Änderungen werden 
mit der nächsten Version des Launchers wirksam. Bei wesentlichen Änderungen 
werden Sie beim nächsten Start des Launchers um erneute Zustimmung gebeten.

================================================================================

7. KONTAKT UND SUPPORT

Bei Fragen oder Problemen wenden Sie sich bitte an:
- Impressum: https://sarocesch.de/impressum.html

================================================================================

8. ZUSTIMMUNG

Durch die Installation und Nutzung des Minewache Launchers erklären Sie sich 
mit diesen Nutzungsbedingungen einverstanden, insbesondere:
- der lokalen Datenspeicherung (Abschnitt 2.2)
- der Microsoft/Mojang Authentifizierung (Abschnitt 2.3)
- der optionalen, freiwilligen Log-Übermittlung bei Nutzung von „Logs senden"
  (Abschnitt 2.6)

Wenn Sie mit diesen Bedingungen nicht einverstanden sind, installieren Sie
die Software bitte nicht.

================================================================================

© 2025-2026 Die Minewache
Alle Rechte vorbehalten.

Minecraft ist eine Marke von Mojang AB / Microsoft Corporation.
Der Minewache Launcher ist ein inoffizielles Projekt und steht in keiner 
Verbindung zu Mojang AB oder Microsoft Corporation.

================================================================================
