# Valutazione dei progetti di investimento/indebitamento
> Cap 15 fino a 15.2.8
## Che cosa si definisce per cumulata dei flussi di cassa e che ruolo gioca nei metodi di valutazione dei progetti di investimento?

>[!NOTE]
>La **cumulata dei flussi di cassa** è la somma algebrica, periodo per periodo, di tutte le entrate e le uscite generate da un progetto di investimento. Tipicamente un investimento presenta un’uscita iniziale, corrispondente al capitale investito, seguita da una serie di flussi di cassa positivi nel tempo.
>
>>La cumulata ha un ruolo **limitato** nei metodi di valutazione dei progetti di investimento: una cumulata positiva indica che, nel complesso, le entrate superano le uscite, mentre una cumulata negativa implica certamente la non convenienza del progetto.
>
>Tuttavia, una cumulata positiva **non fornisce informazioni sulla reale redditività dell’investimento**, poiché non tiene conto del valore del tempo del denaro e non è calcolata in relazione a un tasso di sconto. Per questo motivo non può sostituire criteri di valutazione più corretti come il **metodo del Valore Attuale Netto (VAN) o il metodo del Tasso Interno di Rendimento (TIR)**.
>
>>La cumulata può essere tuttavia utilizzata nel **metodo del tempo di recupero**, che valuta l’investimento in base alla rapidità con cui i flussi di cassa azzerano la cumulata, ovvero coprono l’investimento iniziale.

>[!CAUTION]
>## Si illustri il metodo del VAN per la valutazione di progetti di investimento
>
>Il metodo del VAN è un ottimo metodo per la valutazione di progetti di investimento, che fa uso del valore attuale del flusso di cassa.
>
>Il **Valore Attuale (VA)** è lo strumento economico che si usa per attualizzare all’istante di tempo 0 flussi di cassa futuri ad un dato tasso di sconto. Questo viene fatto perché una determinata somma di denaro oggi non equivale a disporre della stessa somma tra un anno.
>
>$$
>VA=\frac{F}{(1+r)^n}
>$$
>
>- $F \to$ flusso di cassa
>- $r \to$ tasso di sconto
>- $n \to$ anno del flusso di cassa
>
>Per calcolare il **valore attuale di una serie di flussi di cassa finiti**, è sufficiente applicare la formula a ciascun flusso e sommarli:
>
>$$
>VA=\frac{F_1}{(1+r)^1} + \frac{F_1}{(1+r)^2} + ... + \frac{F_1}{(1+r)^n}
>$$
>
>Definito il VA, il **VAN** è la differenza tra la cumulata di tutti i valori attuali dei flussi di cassa e l’investimento iniziale:
>
>$$
>VAN = - I_0 + \frac{F_1}{(1+r)^1} + \frac{F_1}{(1+r)^2} + ... + \frac{F_1}{(1+r)^n}
>$$
>
>- $I_0 \to$ Investimento iniziale
>
>**Il VAN misura operativamente il valore generato da un investimento**. Se il VAN è positivo, allora il progetto è conveniente e genera valore, se è negativo il progetto non è conveniente perché “distrugge” valore.

## Un progetto di investimento con cumulata nulla può avere un VAN positivo? Ed un progetto di indebitamento?
>
>Per **cumulata nulla si intende che la somma dei flussi di cassa non attualizzati è pari a zero** per cui:
>
>- **Progetto di investimento**: all’inizio ($t = 0$) si registra un flusso di cassa negativo (l’investimento iniziale), mentre per $t > 0$ si hanno flussi di cassa positivi (cedole). Poiché questi flussi positivi si manifestano in momenti futuri, il processo di attualizzazione li riduce. Di conseguenza, essendo la cumulata nulla il **VAN risulta necessariamente negativo**.
>- **Progetto di indebitamento**: qui la logica è completamente invertita. All’inizio ($t = 0$) si riceve un flusso di cassa positivo (l’indebitamento), seguito per $t > 0$ da flussi negativi (rate del rimborso del debito). Anche in questo caso i flussi futuri vengono attualizzati, ma essendo negativi il loro valore attuale è **inferiore** all’entrata iniziale. Essendo la cumulata nulla, in questo caso il **VAN risulta necessariamente positivo**.

## In che cosa si distinguono le obbligazioni irredimibili da quelle a scadenza?

>Le **obbligazioni a scadenza** hanno una **data di rimborso prefissata**: alla scadenza l’emittente restituisce il capitale agli investitori, che durante la vita del titolo ricevono cedole periodiche come remunerazione. Sono quindi strumenti con una durata definita e prevedibile.

>Le **obbligazioni irredimibili**, a differenza di quelle a scadenza, **non prevedono mai la restituzione del capitale**. Tuttavia gli investitori ricevono **cedole periodiche in modo perpetuo**.

***

## Come si determina il valore attuale di una rendita fissa costante per infiniti anni? Si dimostri il procedimento di determinazione

>Dimostriamo il procedimento di determinazione del valore attuale di una rendita perpetua costante:
>
>$$
>VA=\frac{F_1}{(1+r)^1} + \frac{F_1}{(1+r)^2} + ... + \frac{F_1}{(1+r)^n}
>$$
>
>Possiamo mettere in evidenza $\frac{F}{1+r}$
>
>$$
>VA=\frac{F_1}{(1+r)} ( 1  + \frac{1}{(1+r)} + ... + \frac{1}{(1+r)^{n-1}})
>$$
>
>L’interno della parentesi è una **serie geometrica infinita** con primo termine $a = 1$ e regione $q = \frac{1}{1+r}$, che converge per $|q|<1$ . La somma della serie è:
>
>$$
>S = \sum^{\infty}_{i=0} \frac{F}{(1+r)^i} = \frac{a}{1-q}= \frac{1}{1-\frac{1}{1+r}} = \frac{1}{\frac{1+r-1}{1+r}} = \frac{1+r}{r}
>$$
>
>Per cui il valore attuale di una rendita perpetua costante è:
>
>$$
>VA = \frac{F}{1+r}S=\frac{f}{1+r}*\frac{1+r}{r}=\frac{F}{r}
>$$

## Si dimostri la formula del valore attuale di finiti flussi di cassa costanti posticipati

>Dimostriamo il procedimento di determinazione del valore attuale di $n$ finiti flussi di cassa costanti posticipati:
>
>$$
>VA=\frac{F_1}{(1+r)^1} + \frac{F_2}{(1+r)^2} + ... + \frac{F_n}{(1+r)^n}
>$$
>
>Poiché i flussi sono tutti uguali, possiamo mettere in evidenza
>
>$$
>VA=\frac{F_1}{(1+r)} ( 1  + \frac{1}{(1+r)} + ... + \frac{1}{(1+r)^{n-1}})
>$$
>
>L’interno della parentesi è una **serie geometrica infinita** con primo termine $a = 1$ e regione $q = \frac{1}{1+r}$, La somma della serie è:
>
>$$
>S = \sum^{\infty}_{i=0} \frac{F}{(1+r)^i} = \frac{1-q^n}{1-q} = \frac{1-(\frac{1}{1+r})^{-n}}{1-\frac{1}{1+r}} = \frac{1-(1+r)^{-n}}{\frac{r}{1+r}}
>$$
>
>Per cui il valore attuale di finiti flussi di cassa costanti posticipati è:
>
>$$
>VA = \frac{F}{1+r}S=\frac{F}{1+r}*\frac{1-(1+r)^{-n}}{\frac{r}{1+r}}=F\frac{1-(1+r)^{-n}}{r}
>$$
>
>Moltiplico e divido per $(1+r)^n$
>
>$$
>VA = \frac{F}{r}*\frac{(1+r)^{n}-1}{(1+r)^n}
>$$






