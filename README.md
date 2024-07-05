Esercizio di oggi(05/07/24): *Griglia Campo Minato*
nome repo: *js-campominato-grid*
*Consegna*
L'utente clicca su un bottone che genererà una griglia di gioco quadrata.
Ogni cella ha un numero progressivo, da 1 a 100.
Ci saranno quindi 10 caselle per ognuna delle 10 righe.
Quando l'utente clicca su ogni cella, la cella cliccata si colora di azzurro ed emetto un messaggio in console con il numero della cella cliccata.
Scomponete sempre il problema in sotto problemi, senza andare troppo nel dettaglio questa volta. Andate nel dettaglio solo quando non riusciti ad implementare in codice qualcosa.
Numero di push: 15 circa
*Bonus* (farlo in una cartella bonus)
Aggiungere una select accanto al bottone di generazione, che fornisca una scelta tra tre diversi livelli di difficoltà:
- con difficoltà 1 => 100 caselle, con un numero compreso tra 1 e 100, divise in 10 caselle per 10 righe;
- con difficoltà 2 => 81 caselle, con un numero compreso tra 1 e 81, divise in 9 caselle per 9 righe;
- con difficoltà 3 => 49 caselle, con un numero compreso tra 1 e 49, divise in 7 caselle per 7 righe;
*Consigli del giorno:*
Scriviamo prima cosa vogliamo fare passo passo in italiano, dividiamo il lavoro in micro problemi.
Ad esempio:
Di cosa ho bisogno per generare i numeri?
Proviamo sempre prima con dei console.log() per capire se stiamo ricevendo i dati giusti.
Le validazioni e i controlli possiamo farli anche in un secondo momento.


|SOLUZIONE|

1.> Creo un pulsante di nome "Start"
1.1.>Recupero il pulsante dal dom

2.>Creo l'elemento che conterrà la mia griglia
2.1.>Recupero l'elemento

3.>Assegno l'evento click al pulsante recuperato nel dom 

4.>Definisco la funzione che mi crea i quadrati nella griglia
4.1.>Assegnazione della classe square all'elemento creato
4.2.>restituisco il quadrato nella variabile current element

5.>Eseguo un ciclo for per la grglia 10x10
5.1.>Creo un singolo quadrato funzione createsquare
5.2.>Aggiungo l'evento click al quadrato
5.3.>Quando cliccata diventa azzurra e mostra il numero in console

6.>Metto il numero progressivo al quadrato

7.>Appendo il quadrato creato nella griglia
 
