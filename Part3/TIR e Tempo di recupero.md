# TIR e Tempo di recupero
> 15.2.9; Capitolo 17 fino a 17.1.4;

>[!CAUTION]
>## Il metodo del TIR per la valutazione di progetti di investimento
>
>Per calcolare il VAN è necessario avere preliminarmente scelto il tasso di sconto `r`, senza il quale non sarebbe possibile attualizzare i flussi di cassa. La scelta di questo tasso è spesso problematica.
>
>$$
>VAN = - I_0 + \frac{F_1}{(1+r)^1} + \frac{F_1}{(1+r)^2} + ... + \frac{F_1}{(1+r)^n} = - I_0 \sum^{n}_{i=1} \frac{F_i}{(1+r)^i}
>$$
>
>Il **Tasso Interno di Rendimento (TIR)** permette di superare questo problema: il **TIR** è il **tasso di sconto** che rende il VAN del progetto pari a zero:
>
>
>$$
>-I_0 + \sum^{n}_{i=1} \frac{F_i}{(1+TIR)^i} = 0
>$$
>
>Attraverso il TIR è quindi possibile calcolare il tasso di sconto che mi permette di generare un rendimento attualizzato **perfettamente equivalente all’investimento**.
>- Se il TIR è maggiore del **tasso minimo accettabile**, il progetto è conveniente.
>- Se il TIR è uguale o minore del tasso minimo, il progetto non è conveniente.

***

>[!WARNING]
>## Si illustrino compiutamente i limiti del metodo del TIR nella valutazione dei progetti di investimento.
>
>1. Un primo limite del TIR è che non consente di confrontare correttamente progetti di investimento alternativi: un progetto con TIR minore può infatti presentare, per alcuni valori di $r$ un VAN superiore rispetto a un progetto con TIR maggiore.
>2. Un secondo limite del TIR è che se il polinomio che azzera il VAN ha più soluzioni, allora esistono più valori del TIR.
>3. Infine nel caso di un progetto di indebitamento, tra diversi progetti di indebitamento, devo scegliere quello con il TIR minore, e non quello con il TIR maggiore. La complessità della valutazione dei progetti reali porta spesso a cadere nella trappola di considerare il progetto con TIR maggiore.

## Si disegni l’andamento del VAN in funzione del tasso di sconto nel caso di investimento, indicando il TIR. Cosa cambia se si studia un progetto di indebitamento?

![](./imgs/VANeTIR.png)

Il grafico mostra il VAN di un **progetto di investimento** in funzione del tasso di sconto `r`.
>-La curva **decresce al crescere di** `r`: i flussi futuri valgono meno se scontati a tassi più alti
>- Il TIR è il punto in cui $VAN = 0$
>- Si osserva che Il VAN è negativo per $r>TIR$ e positivo per $r<TIR$

Nel caso di un **progetto di indebitamento**, la situazione è speculare:

>-La curva del VAN **aumenta con il tasso di sconto**, perché i flussi negativi futuri vengono scontati più pesantemente.
>-Il VAN è negativo per $r<TIR$ e positivo per $r>TIR$
























