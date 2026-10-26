# CinePeg – Base operativa

## Fonte ufficiale

La fonte ufficiale a regime sarà il database centrale cinepeg-db.js.

Le pagine HTML sono viste derivate e non devono diventare archivi indipendenti.

## Entità principali

- films: film posseduti, con durata, rating, genere, supporto, registi, cast e priorità.
- visions: calendario delle visioni.
- toRecover: film da recuperare nell'ordine di aggiunta.
- people: futura anagrafica unica di attori, attrici, registi e altri personaggi.
- oscars: future cerimonie, vincitori e nominati collegati alle entità.

## Regole di aggiornamento

Ogni modifica deve:

1. aggiornare il database centrale;
2. mantenere gli identificativi stabili;
3. non duplicare la stessa persona o lo stesso film;
4. rigenerare le pagine derivate;
5. verificare filtri, ricerca e ordinamenti;
6. conservare un backup precedente.

## Operazioni future dell'agente

- aggiungere o modificare film posseduti;
- registrare o correggere visioni;
- aggiungere o eliminare film da recuperare;
- cambiare priorità di revisione;
- aggiungere persone;
- aggiornare compleanni, stato di vita e dati anagrafici;
- aggiornare Oscar e nominations;
- aggiornare statistiche e collegamenti.
