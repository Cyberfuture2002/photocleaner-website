# Admin Release Note (Update-JSON)

Bei jedem Release nur diese 4 Felder in `updates/latest.json` anpassen:

1. `latest_version` (SemVer, z. B. `0.8.6`)
2. `download_url` (vollstaendige URL auf `download.html`)
3. `release_notes_url` (vollstaendige URL auf `changelog.html`)
4. `published_at` (ISO-8601 UTC, z. B. `2026-04-10T08:00:00Z`)

Danach committen und deployen. Keine weiteren Website-Aenderungen noetig.
