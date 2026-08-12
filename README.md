# HufManager Pro – Februar 2026

Historischer Referenzstand des HufManager aus Februar 2026.

## Zweck

Dieses Repository dient als **sauberer, nachvollziehbarer Referenzstand** für die spätere Rekonstruktion eines eigenständigen HufManager – getrennt von HufiApp.

Der Originalexport bleibt unverändert im Archiv erhalten. In dieses Repository kommt nur eine **bereinigte Version ohne Secrets, Tokens oder lokale Umgebungsdateien**.

## Einordnung

- Zeitraum: Februar 2026
- Quelle: Lovable / GitHub-basierter Entwicklungsstand
- Rolle: möglicher letzter großer eigenständiger HufManager vor der späteren HufiApp-Vermischung
- Status: `PRE-HUFIAPP REFERENCE CANDIDATE`
- Rohstand: separat archiviert

## Wichtige Funktionsbereiche im Rohstand

Unter anderem vorhanden:

- Dashboard
- Kundenverwaltung
- Pferdeakte / Pferdedetails
- Kalender und Touren
- Hufanalyse / LTZ-Analyse
- Rechnungen und Ausgaben
- Lager
- Services
- Team
- Management
- Academy-Grundstruktur
- Chat / Netzwerk
- Kundenportal
- Landingpage
- PWA / Offline
- Admin-Bereiche

## Sicherheitsregel

Der historische Roh-Export enthält lokale Environment-/Credential-Fundstellen. Deshalb wird er **nicht ungeprüft veröffentlicht**.

Vor dem Code-Import:

1. `.env` und lokale Secrets entfernen.
2. verdächtige Tokens/Keys prüfen und gegebenenfalls rotieren.
3. nur `.env.example` mit Platzhaltern einchecken.
4. Build-/Cache-/lokale Dateien ausschließen.
5. anschließend Secret-Scan wiederholen.

## Archivprinzip

- RAW bleibt unverändert erhalten.
- Dieses Repo ist die bereinigte Referenz.
- Keine automatische Löschung historischer Stände.
- Spätere Vergleiche dokumentieren klar: `IM CODE BELEGT`, `PER SCREENSHOT BELEGT`, `AUS ERINNERUNG WAHRSCHEINLICH`.

## Nächster Schritt

Bereinigten Februar-2026-Stand importieren und anschließend gegen ältere HufManager-Versionen sowie spätere HufiApp-vermischte Stände vergleichen.
