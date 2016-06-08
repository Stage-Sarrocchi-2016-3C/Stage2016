## AVL TREE
L'albero AVL è una struttura ad albero binario di ricerca bilanciato, ovvero un albero in cui gli elementi sono numerati in modo che gli l'ordine sia decrescente da destra a sinistra e la cui altezza, grazie a particolari condizioni che la sua struttura deve soddisfare, rimane limitata.
gli alberi AVL Hanno buone prestazioni e gestione relativamente semplice.
Definizione: Un albero binario di ricerca è
un Albero AVL se per ogni nodo l’altezza del sottoalbero sinistro e quella
del sottoalbero destro di differiscono al più di uno. 
>Alberi AVL sono particolarmente adatti per realizzare efficienti strutture di tipo dizionario (insiemi dinamici su cui eseguiamo inserimenti, cancellazioni e ricerche)
### ROTAZIONE
L’inserimento o la cancellazione di un nodo potrebberofar perdere il bilanciamento di un albero AVL, è indispensabile mantenere il bilanciamento dell’albero anche se si `
inseriscono o si cancellano elementi, Il bilanciamento deve essere ripristinato mediante delle opportune operazioni sui nodi che prendono il nome di rotazioni.
Esistono quattro tipi di rotazioni di base:
* rotazioni SS: inserimento a sinistra nel sottoalbero sinistro
* rotazioni SD: inserimento a destra nel sottoalbero sinistro
* rotazioni DD: inserimento a destra nel sottoalbero destro
* rotazioni DS: inserimento a sinistra nel sottoalbero destro
>Queste rotazioni consistono nel portare l’elemento intermedio alla
  radice e nel far ridiscendere il nodo che causa lo sbilanciamento

![avl](https://fripp.files.wordpress.com/2008/02/ss.png)