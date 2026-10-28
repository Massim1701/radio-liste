# radio-liste

Schreibt mit, welcher Interpret und Titel auf den 80s80s-Kanälen läuft (nur Text, kein Audio) und legt die Liste
als `titel.jsonl` in einen Release. Ein Programm auf einem eigenen Server holt sie dort ab und gleicht sie mit
einer Musikdatenbank ab.

- `radio_sammler.py` liest die öffentlichen Stream-Metadaten (ICY), wie ein Player.
- `.github/workflows/radio-liste.yml` läuft manuell (Test) oder nach Zeitplan.
