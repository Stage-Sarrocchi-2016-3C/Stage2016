
## STRUTTURA DATI
In informatica una struttura dati è un sistema di organizzazione dei dati all'interno della memoria.
Si può scegliere fra i diversi tipi di strutture dati in base all'algoritmo che si intende utilizzare.
La struttura dati è in grado di trasformare i dati semplici del linguaggi di programmazione in dati più complessi grazie ad un processo chiamato "instanziazione" che avverrà durante la compilazione o l'esecuzione del codice.

## TIPI DI STRUTTURE DATI
* Array: l’array è una struttura dati che può contenere un numero di dati dello stesso tipo di cui ognuno è associato ad un indice numerico. L'array ha una struttura simile ad una tabella a una o due dimensioni, e ogni slot è associato a uno o due coordinate.

* Array associativo: l’array associativo permette di indicare dati mediante indici numerici e stringhe.

* Record: un record è una struttura dati che può contenere un numero di dati che possono essere di diverso tipo.

* Union: un’union è una struttura dati che permette di memorizzare solo alcuni tipi di dati.

* Union tag: un’union tag è un’union che contiene un campo aggiuntivo che indica il tipo di dato corrente.

* Set: un set è una struttura dati che contiene dati diversi tra di loro.

* Grafo: è una struttura dati composta da nodi. Ogni nodo contiene un valore e uno o più puntatori. I grafi sono utili per la rappresentazione gerarchica delle reti.

* Albero: è una struttura nella quale si identificano dei nodi e dei collegamenti, ogni nodo può essere  “padre” di uno o più nodi figli ma non può essere “figlio” di più nodi; a differenza del grafo l'albero non può contenere cicli ovvero partendo dall'alto e scendendo non è possibile tornare in alto.

* Classe: una classe è una struttura dati che può contenere, oltre a diversi tipi di dati, anche operazioni e funzioni.

![albero](https://upload.wikimedia.org/wikipedia/commons/3/36/Binary_tree_(oriented_digraph).png) *una struttura ad albero*

## Pro e contro di alcune strutture dati

Array
>Pro:
1. L'accesso ad un elemento di un array è veloce in quanto siamo in grado di calcolare la sua posizione in fretta.

>Contro:
1. Se vogliamo inserire o cancellare un elemento, dobbiamo spostare gli elementi successivi rallentando il calcolo sensibilmente.
2. Abbiamo bisogno di un blocco di sufficiente memoria per contenere l'array.
3. facilmente danneggiabili

Albero
>Pro:
1. La ricerca è più veloce.
2. Inserire / eliminare chiavi in un tempo moderato (più veloce di un array e più lento rispetto a liste concatenate non ordinate).

>Contro:
1. Grande spreco di collegamenti non utilizzati
2. limite predeterminato sul numero di figli di un nodo

Grafo
>Pro:
1. Trovare il percorso in modo efficiente

>Contro:
1. Grande spreco di collegamenti non utilizzati

## FORME DEI DATI
Principalmente abbiamo due metodi per rappresentare i dati:
* indicizzate: i dati sono contenuti in array
* collegate: i dati sono contenuti in record collegati fra loro mediante puntatori, a loro volta possono essere divise in collegamento a lista semplice o a lista doppia.

    ![lista](http://www.science.unitn.it/~brunato/labpro1/lista-avanzap.gif)
    *collegamento a lista semplice*
## Pro e contro delle forme
Ovviamente ognuna delle rappresentazioni hanno vantaggi e svantaggi
>indicizzate:    
* Pro: accesso diretto ai dati mediante indici
* Contro: dimensione fissa
> collegate:
* Pro: dimensione variabile
* Contro: accesso sequenziale ai dati

## SUPPORTO NEI LINGUAGGI DI PROGRAMMAZIONE

I linguaggi di basso livello non supportano le strutture dati, mentre alcuni linguaggi ad alto livello hanno una sintassi particolare incorporata per alcune strutture dati; per esempio la maggior parte dei linguaggi permette l’implementazione di librerie in modo da poter riutilizzare strutture dati da programmi diversi.
Alcuni linguaggi moderni supportano la programmazione modulare, ovvero una programmazione basata su “moduli” separati in grado ognuno di svolgere le proprie funzioni.
