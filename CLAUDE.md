# sito-test — istruzioni per i collaboratori (e le loro istanze di Claude)

## Scopo
Sito statico di prova pubblicato con **GitHub Pages**.
- Repository: https://github.com/ingegnererecca-web/sito-test
- Sito pubblico: https://ingegnererecca-web.github.io/sito-test/

## Struttura
- `index.html` — pagina di prova principale (HTML + CSS + JS inline, nessuna dipendenza esterna)
- `galleria/index.html` — esempio di sito per una galleria d'arte immaginaria ("Galleria Meridiana"); opere disegnate in CSS, nessuna immagine esterna. URL: https://ingegnererecca-web.github.io/sito-test/galleria/
- `README.md` — descrizione breve
- `CLAUDE.md` — questo file: contesto condiviso per sincronizzarsi sul progetto

## Pubblicazione
- GitHub Pages serve il branch `main`, cartella radice (`/`).
- Ogni push su `main` ripubblica il sito automaticamente (1–2 minuti).
- Solo contenuti statici: niente PHP, database o codice lato server.

## Convenzioni
- Lingua dei contenuti e dei commit: italiano.
- Mantenere `index.html` autosufficiente (nessun CDN esterno salvo necessità).
- Prima di modifiche strutturali (nuove pagine, cartelle, framework) aggiornare questo file.

## Registro modifiche
- 2026-11-16 — Creata la repository e pubblicata la pagina di prova.
- 2026-11-16 — Aggiunto l'esempio di galleria d'arte in `galleria/`.
