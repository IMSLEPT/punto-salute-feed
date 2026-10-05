# punto-salute-feed

Feed pubblico di aggiornamento per l'app **Punto Salute** (solo dati JSON, nessun codice).

- `feed.json` – edizioni delle fonti, avvisi, correzioni validate alle schede (schema 2).
- L'app lo scarica in HTTPS (al massimo una volta al giorno), lo valida e applica solo correzioni conformi alle regole interne (nessun dosaggio, nessun HTML, solo link a schede esistenti).
- Generato da `web/tools/build-feed.mjs` nel repository dell'app e rivisto mensilmente.

Contenuto a scopo educativo: verificare sempre il protocollo locale.
