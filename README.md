# html-css-bootstrap-dashboard

## Descrizione

Progetto di esercitazione realizzato con **HTML, CSS e Bootstrap 5.3** per ricreare il layout responsive di una dashboard per la gestione di un catalogo libri.

L'interfaccia comprende:

- **navbar responsive** con logo, link di navigazione e barra di ricerca
- **sezione principale** con titolo, pulsante di aggiunta libro e tabella catalogo
- **sidebar** con card **Todo** e **F.A.Q.**
- adattamento ai diversi dispositivi: **desktop, tablet e mobile**

## Tecnologie utilizzate

- HTML5
- CSS3
- Bootstrap 5.3
- Bootstrap Icons

## Struttura del progetto

```text
html-css-bootstrap-dashboard/
│
├── index.html
├── README.md
├── css/
│   └── style.css
└── img/
    └── logo.png
```

## Obiettivi dell'esercizio

L'obiettivo era:

- usare correttamente la **griglia di Bootstrap**
- sfruttare i **componenti già pronti** del framework
- scrivere **poco CSS custom**, solo dove necessario
- realizzare un layout fedele agli screenshot forniti

## Componenti Bootstrap usati

Nel progetto sono stati utilizzati diversi componenti e utility di Bootstrap, tra cui:

- `navbar`
- `container-fluid`
- `row` e `col-*`
- `table` e `table-responsive`
- `card`
- `list-group`
- `accordion`
- `badge`
- `button`
- utility di spacing come `px-*`, `py-*`, `mb-*`, `gap-*`

## Responsive design

La dashboard è stata progettata in modo responsive:

- su **desktop** la tabella è affiancata alla sidebar
- su **tablet** il layout si adatta in modo più compatto
- su **mobile** gli elementi vengono disposti in colonna
- la colonna **Data prestito** viene nascosta sugli schermi piccoli tramite classi responsive Bootstrap

Esempio:

```html
<th class="d-none d-md-table-cell">Data prestito</th>
<td class="d-none d-md-table-cell">18/10/2023</td>
```

## Avvio del progetto

Per visualizzare il progetto:

1. scaricare o clonare la repository
2. aprire il file `index.html` nel browser

Non sono necessarie installazioni o dipendenze locali, perché Bootstrap e Bootstrap Icons sono collegati tramite CDN.

## Note

Questo progetto ha scopo didattico ed è pensato come esercitazione pratica per prendere confidenza con:

- layout responsive
- componenti Bootstrap
- organizzazione del codice HTML e CSS

## Autore

Progetto realizzato come esercizio didattico.
