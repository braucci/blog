# Quaderno di Volo

Repository del blog personale di Biagio Raucci, pubblicato tramite
GitHub Pages all'indirizzo:

**https://braucci.github.io/blog/**

---

## Struttura

```
blog/
├── _config.yml              # configurazione del sito
├── _posts/                  # tutti i post (nome: AAAA-MM-GG-titolo.md)
├── _layouts/                # template personalizzati (opzionale)
├── _includes/               # frammenti riutilizzabili (opzionale)
├── _sass/                   # parziali SCSS (opzionale)
├── assets/
│   ├── css/style.scss       # foglio di stile personalizzato
│   └── images/              # immagini per i post
├── index.md                 # homepage
├── chi-sono.md              # pagina "Chi sono"
├── archivio.md              # archivio cronologico dei post
├── Gemfile                  # dipendenze (per anteprima locale)
└── README.md                # questo file
```

## Come scrivere un nuovo post

1. Crea un file in `_posts/` con il nome nel formato:
   `AAAA-MM-GG-titolo-del-post.md`
2. Inserisci all'inizio il front matter YAML:

   ```yaml
   ---
   layout: post
   title: "Titolo del post"
   date: 2026-05-21 10:00:00 +0200
   categories: [saggi]
   tags: [filosofia, scrittura]
   excerpt: "Un estratto di 1–3 frasi che compare in homepage."
   ---
   ```
3. Scrivi il corpo in Markdown.
4. Commit + push: il post è online entro un minuto.

## Anteprima locale (opzionale)

Richiede Ruby installato. Dal terminale, nella cartella del repository:

```bash
bundle install              # solo la prima volta
bundle exec jekyll serve    # avvia il server locale
```

Apri il browser su `http://localhost:4000/blog/`.

## Note

- I file con nome che inizia con `_` o `.` non sono pubblicati.
- Le immagini dei post vanno in `assets/images/` e si richiamano con
  `![alt]({{ "/assets/images/nome.jpg" | relative_url }})`.
- Per pubblicare un post in futuro, basta usare una data futura: Jekyll
  non lo mostrerà finché non sarà arrivato il momento.
