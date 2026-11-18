# Catalogo base di ContaCHO

Prodotti alimentari **di marca** con i carboidrati per 100 g **verificati sull'etichetta**, letti dall'app
[ContaCHO](https://claude.ai/artifact/W5ne7z9cVwdJnajN216DtA) all'avvio. Gli alimenti generici (pasta, latte, frutta…)
vengono invece dalle tabelle ufficiali CREA e non sono qui.

- `catalogoBase.json` — il catalogo (formato descritto in `schemaCatalogo.json`)
- Nessun dato personale: niente nomi, nickname, email o diari.

## Come si aggiorna

1. Nell'app un utente propone un prodotto nuovo o una correzione.
2. Un **owner** o un **writer** la verifica sull'etichetta e la approva (o la rifiuta).
3. L'owner esporta il catalogo approvato e il file viene pubblicato qui con un commit.

Le modifiche dirette a questo repository sono riservate al proprietario. Proposte esterne (pull request) non vengono unite:
le correzioni passano dall'app.

## Varianti

I valori di un prodotto possono cambiare nel tempo (nuova ricetta, nuova etichetta). Ogni variante vale **dalla sua data
in avanti**: i pasti già registrati nel diario conservano i valori del giorno in cui sono stati mangiati.

## Avvertenza

Valori indicativi a scopo alimentare, non destinati a decisioni terapeutiche.
