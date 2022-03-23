Nome:
Cognome:

Fila:
Postazione:


# VERIFICA: Fondamenti di version control
### Variante 8

## Attenzione!
- compilare con nome, cognome, fila e posizione nell'intestazione di questo file
- prima di effettuare le modifiche ai file assicurarsi di avere la HEAD sul branch richiesto dall'esercizio
- utilizzare messaggi di commit descrittivi, verranno utilizzati per la valutazione



## Esercizio 1 (3 punti)
Partendo dal branch 'main':
- salvare le modifiche a questo file (Verifica-8.md)
- aggiungere il file alla staging area
- effettuare un commit delle modifiche

Partendo dal branch 'develop':
- creare un nuovo branch 'feature/capitolo-8'
- effettuare un checkout del nuovo branch
- creare un nuovo file chiamato 'documento.txt' ed inserire il seguente testo:

```
Capitolo 8.
Will royalties in the company do instead of cash can you please send me the design specs again? for we need more images of groups of people having non-specific types of fun there is too much white space make it look like Apple. We are a startup can you make it pop, and we don't need a contract, do we you might wanna give it another shot can we barter services? yet that's great, but can you make it work for ie 2 please yet doing some work for us "pro bono" will really add to your portfolio i promise.
```

- aggiungere il file alla staging area
- effettuare il commit della modifica
- effetturare un push sul repository remoto creando il nuovo branch (upstream)

## Esercizio 2 (3 punti)
- spostarsi sul branch 'main'
- effettuare un allineamento con 'origin' (pull)
- effettuare la push del branch su origin (per riportare i dati compilati di questo file)

Nota: qualcuno fra i colleghi potrebbero aver effettuato delle modifiche sul branch 'main' del repository remoto (origin) prima di te, per questo occorre riallinearsi con un 'pull'.

## Esercizio 3 (12 punti per le domande + 3 per la procedura)
- spostarsi sul branch 'teoria'
- creare un nuovo file chiamato <nome>-<cognome>.txt
- rispondere alle seguenti domande: (riportare anche il testo della domanda per facilitare la correzione del compito)

    1. Cosa fa il comando 'git restore --staged <file>'? Spiega come funziona la staging area
    2. Descrivi il comando 'git checkout <branch>', spiegando come funziona la history, cosa sono i branch e cosa è la HEAD
    3. Cos'è un repository remoto? Descrivi cosa fa il comando 'git pull'

- effettuare una commit ed una push con il file di testo compilato

Nota: assicurati che la push abbia avuto esito positivo, poichè la valutazione potrà essere fatta solo se il file è correttamente riportato sul repository remoto

## Esercizio 4 (3 punti)
- lavora sul branch 'test'
- aprendo il file 'test-8.html' nota che c'è una riga di testo aggiunta per errore
- stacca un branch per correggere il problema: 'bugfix/08-rimozione-riga'
- correggi il problema e verifica che il file html sia visualizzato correttamente
- a lavoro ultimato, effettua una commit
- fai un push del branch di bugfix su origin
- tornando al branch 'test' effettua l'allineamento con il branch di bugfix (merge)
- dopo una verifica di funzionamento, effettua la push verso il repository remoto
- riporta la modifica sul branch di develop, anche sul repository remoto

## Esercizio 5 (3 punti)
- torniamo al branch 'develop' (ora quasi tutti i colleghi dovrebbero aver terminato l'esercizio 1)
- allinearsi al repo remoto (fetch/pull)
- fare il merge del proprio feature branch ('feature/capitolo-8'), risolvendo eventuali conflitti: il file 'documento.txt' deve presentarsi con tutti i capitoli in ordine
- fare il push su origin

## Esercizio 6 (3 punti)
- sul branch 'develop'
- creare un branch 'sfondo/thistle'
- modificare nel file 'style.css' il colore di sfondo della pagina in 'thistle'
- verificare che aprendo la pagina 'test-8.html' il colore di sfondo sia effettivamente cambiato
- effettuare una commit con le modifiche richieste
- fare la push del branch sul repository remoto
- tornare sul branch develop
- nel file 'test-8.html' modificare il titolo tra tag h1 con 'Titolo modificato'
- effettuare il commit della modifica, e la push su origin
- spostarsi nuovamente sul branch 'sfondo/thistle'
- allinearsi al branch develop e verificare che ora la pagina test-8.html presenti il titolo modificato
- fare il push su origin
