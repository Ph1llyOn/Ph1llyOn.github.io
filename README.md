# ph1llyon.github.io

Sito personale di **Filippo Marcon (Phill)** — pubblicato su
[ph1llyon.github.io](https://ph1llyon.github.io/) via GitHub Pages.

## Contenuto

- **Hero** — nome, presentazione e call to action
- **Chi sono** — breve bio (studente IT, sviluppatore)
- **Progetti** — IslandMC, il libro *3:17*, *Diario di un Content Creator*
- **Competenze tecniche** — stack reale (PHP, JavaScript, …)
- **Contatti** — GitHub, Instagram, TikTok, Amazon

## Stack

Solo **HTML + CSS + JavaScript vanilla** in un unico `index.html`.
Nessun framework, nessuna dipendenza, nessun build system:
GitHub Pages pubblica il file così com'è.

## Come modificarlo

1. Modifica `index.html` con un qualsiasi editor di testo.
2. Per vedere le modifiche in locale: `python3 -m http.server` nella cartella
   e apri `http://localhost:8000`.
3. Fai commit su un branch dedicato e apri una pull request verso `main`
   — mai commit diretti su `main` senza revisione.

## Note di accessibilità

- Contenuti visibili anche senza JavaScript (progressive enhancement)
- `prefers-reduced-motion` rispettato, focus da tastiera visibile,
  skip link e landmark `<main>`/`<nav>` con label ARIA.
