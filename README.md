# Luca Invernizzi — Web Design

Sito portfolio/landing page statico per presentare servizi di web design rivolti a PMI, professionisti e piccole realtà in Ticino.

## Perché è statico

Questa V1 usa HTML, CSS e JavaScript senza framework o dipendenze. Per un sito vetrina significa:

- deploy immediato su GitHub Pages;
- nessun `npm install` o processo di build;
- manutenzione semplice;
- caricamento veloce;
- costi hosting GitHub Pages = 0 CHF.

## Pubblicazione su GitHub Pages

1. Crea un nuovo repository GitHub, per esempio `web-design-luca`.
2. Carica **tutto il contenuto di questa cartella** nella root del repository.
3. Vai in `Settings → Pages`.
4. In `Build and deployment`, scegli `Deploy from a branch`.
5. Seleziona branch `main` e cartella `/ (root)`.
6. Salva. Dopo pochi minuti GitHub mostrerà l'URL pubblico.

## Dominio personalizzato

Quando avrai acquistato un dominio, in `Settings → Pages → Custom domain` inserisci il dominio o sottodominio desiderato. Se usi ad esempio `web.lucainvernizzi.ch`, crea presso il registrar il record DNS richiesto da GitHub Pages e abilita `Enforce HTTPS` quando diventa disponibile.

Consiglio: prima pubblica e testa il sito con l'URL GitHub Pages; collega il dominio solo dopo.

## File importanti

- `index.html` — homepage
- `progetti/verbano.html` — case study Verbano
- `progetti/mvca.html` — case study MVCA
- `privacy.html` — pagina privacy minimale
- `assets/style.css` — design completo
- `assets/site.js` — menu, FAQ, animazioni leggere
- `assets/media/` — video e materiale Verbano

## Modifiche rapide

### E-mail / telefono
Cerca nel progetto:

- `luca.invernizzi@students.ffhs.ch`
- `+41789458035`

### Colori
Sono definiti all'inizio di `assets/style.css` nelle variabili `:root`.

### Video Verbano
Sostituisci i file in `assets/media/` mantenendo gli stessi nomi oppure modifica i path nell'HTML.

## Prima di renderlo definitivo

- aggiungere una vera immagine/screenshot del progetto MVCA se desiderato;
- verificare che i testi dei case study descrivano esattamente il lavoro effettivamente consegnato;
- aggiungere il dominio definitivo;
- aggiornare la privacy se in futuro vengono introdotti analytics, form, newsletter, mappe o servizi esterni.
