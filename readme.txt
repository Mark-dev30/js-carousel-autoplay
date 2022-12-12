ESERCIZIO:
Ripetiamo l'esercizio sul carosello ma questa volta implementando l'autoplay. Non dovete rifare tutto da capo, partite da quanto già fatto. Create una nuova repo e dentro copiateci i file dell'esercizio vecchio. Quindi fate un primo push. Suddividetevi poi il lavoro in step come abbiamo sempre fatto su un file di testo quindi fate un altro push. Potete poi cominciare a lavorare sull'esercizio.

RISOLVO:
1 - Creo un autoplay che manda avanti le img dopo 3 secondi.
    1.1 - Creo un intervallo di tre secondi con setInterval.
    1.2 - All'interno dell'intervallo rimuovo la classe "active" nell'elemento attivo.
        1.2.1 - Rimuovo la classe "active" dall'elemento "items".
        1.2.2 - Rimuovo la classe "active" dall'elemento "circle".
        1.2.3 - Rimuovo la classe "no_layer" dall'elemento "layer".
    1.3 - Creo una condizione per verificare se l'elemento attivo è null'ultima img.
        1.3.1 - Se l'elemento attivo è nell'ultima posizione, do alla variabile un valore negativo.
    1.4 - Incremento la variabile di 1.
    1.5 - Aggiungo la classe "active" al nuovo elemento.
        1.5.1 - Aggiungo la classe "active" dall'elemento "items" con il valore aumentato di "itemActive".
        1.5.2 - Aggiungo la classe "active" dall'elemento "circle" con il valore aumentato di "itemActive".
        1.5.3 - Aggiungo la classe "no_layer" dall'elemento "layer" con il valore aumentato di "itemActive".