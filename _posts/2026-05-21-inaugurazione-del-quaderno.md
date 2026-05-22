---
layout: post
title: "Inaugurazione del quaderno"
date: 2026-05-21 10:00:00 +0200
categories: [meta]
tags: [scrittura, blog, appunti]
excerpt: "Un quaderno bianco è un piccolo abisso: l'inizio di ogni scrittura
ha qualcosa della vertigine. Eppure cominciare è l'unico modo per scoprire
cosa si voleva dire."
---

Un quaderno bianco è un piccolo abisso. L'inizio di ogni scrittura ha
qualcosa della vertigine: lo sguardo si posa sul vuoto della pagina e
per un istante si misura il proprio silenzio.

Eppure cominciare è l'unico modo per scoprire cosa si voleva dire.
Si scrive — almeno, io scrivo — per la stessa ragione per cui si
disegna il diagramma delle sollecitazioni lungo un'ala: non perché si
sappia in anticipo come andrà, ma perché tracciare la linea è il solo
modo di rendere visibile la forza.

Questo quaderno raccoglierà appunti irregolari. Pagine di didattica,
forse; brevi saggi su ciò che leggo o fotografo; qualche annotazione
tecnica che vale la pena di non perdere. Non prometto né continuità né
sistema. Prometto solo di scrivere quando ne sentirò la necessità —
che è poi l'unica forma di onestà accessibile a chi scrive.

## Una nota tecnica

Per chi fosse curioso: queste pagine sono generate da
[Jekyll](https://jekyllrb.com) e pubblicate gratuitamente da GitHub
Pages. Il sorgente vive in un repository pubblico, e ogni post nasce
come un semplice file di testo in Markdown.

Si può scrivere così:

```markdown
---
title: "Titolo del post"
date: 2026-05-21
---

Il corpo del testo, in **Markdown**.
```

E si può inserire codice — per esempio una funzione Python — con
evidenziazione automatica della sintassi:

```python
def coefficiente_portanza(alpha, alpha_0=-2.0, slope=0.11):
    """Curva CL-alpha lineare (regime di basse incidenze)."""
    return slope * (alpha - alpha_0)
```

O una formula matematica, se in futuro abiliterò MathJax:

> $C_L = C_{L,\alpha} \, (\alpha - \alpha_0)$

Per ora basta così. Il quaderno è aperto.
