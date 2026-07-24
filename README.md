# verumind Hub — Bezugsquelle (updates.verumind.de)

Öffentliche Bezugsquelle für Kundeninstallationen von verumind Hub.
Enthält **keine** Zugangsdaten und **keinen** Quellcode.

| Datei | Zweck |
|---|---|
| `verumind-hub-install.tar.gz` | Installationspaket (Compose-Datei, Caddyfile, `install.sh`, Konfig-Vorlage) — versionsneutral |
| `verumind-hub-install.tar.gz.sha256` | Prüfsumme zur Integritätsprüfung |
| `latest.json` | aktuelle Programmversion — von jeder Installation für die Update-Prüfung abgefragt |
| `index.html` | schlichte Übersichtsseite |

## Bei einem neuen Release

1. `latest.json` auf die neue Version setzen (`version`, `publishedAt`, `notes`).
2. Falls sich am Installer etwas geändert hat: `verumind-hub-install.tar.gz`
   und die Prüfsumme ersetzen.

Sobald das veröffentlicht ist, melden alle Installationen „Update verfügbar".
