# Fanflare

## Python Server starten um Webseite aufzurufen

Mit Python einfachen HTTP Server starten um lokale Dateien via JavaScript Fetch zu laden. Ist nötig damit kein Cross-Origin Request Blocked Fehler auftaucht.

<code>
    python3 -m http.server
</code>

Die Webseite kann unter http://0.0.0.0:8000/ aufgerufen werden.

## Caching für Development deaktivieren 

Wenn das Caching aktiviert ist, werden die Änderung nach Refresh der Webseite nicht sichtbar. Du kannst das Caching wie folgt deaktivieren:

1. Rechtsklick und Inspect / fn + F12 Taste drücken
2. Auf Network Tab wechseln
3. Häckchen Disable Cache ankreuzen