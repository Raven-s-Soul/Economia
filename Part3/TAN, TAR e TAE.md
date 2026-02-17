# TAN, TAR e TAE
> Par. 15.2.10 e 15.2.11;

>[!NOTE]
>## Qual è la differenza tra valore reale e valore nominale di un investimento?
>La differenza tra valore reale e valore nominale di un investimento risiede nell'**inflazione**, ovvero l'**aumento generalizzato** dei prezzi che riduce il potere d'acquisto del denaro.
>
>Il valore nominale di un investimento è il valore espresso in unità monetarie correnti, così come risulta dai flussi di cassa osservati, **senza tenere conto dell’inflazione**. 
>
>Nel caso di un capitale iniziale $I_0$ che rende a un tasso nominale $TAN$ il valore nominale dell’investimento all’anno $n$ è:
>
>$$
>V_n^N = I_0(1+TAN)^n
>$$
>
>Il **valore reale**, invece, misura il **potere d’acquisto effettivo** di quell’investimento, cioè il suo valore monetario al netto dell’inflazione. A parità di valore nominale, un investimento può avere un valore reale diverso a seconda dell’andamento dell’inflazione nel tempo.
>
>
>$$
>V_n^R = \frac{V_n^N}{(1+i)^n} = I_0 \frac{(1+TAN)^n}{(1+i)^n}
>$$

***

>[!IMPORTANT]
>## Si dimostri la determinazione della formula del tasso di rendimento reale a partire da quello nominale e dall’inflazione
>Fino ad ora abbiamo chiamato **tasso di scambio**, il **tasso di scambio nominale (TAN)**.
>
>Il **tasso di scambio reale (TAR)**, a differenza di quello nominale, **misura la redditività effettiva dell’investimento al netto dell’inflazione**, cioè tenendo conto della perdita di potere d’acquisto della moneta nel tempo.

>[!TIP]
>### Dimostrazione della formula del TAR
>
>Se il capitale $I_0$ rende ad un tasso di rendimento nominale TAN, al termine del primo periodo il valore nominale $V_1^N$ dell’investimento sarà pari a:
>
>
>$$
>V_1^N = I_0(1+TAN)
>$$
>
>Tuttavia a causa dell’inflazione , il potere d’acquisto della moneta si riduce, pertanto il valore reale $V_1^R$ al termine del primo periodo al netto dell’inflazione sarà pari a:
>
>
>$$
>V_1^R = \frac{V_1^N}{1+i} = \frac{I_0(1+TAN)}{1+i}
>$$
>
>Per definizione il **tasso di rendimento reale TAR** è il tasso che soddisfa la seguente relazione:
>
>
>$$
>V_1^R = I_0(1+TAR)
>$$
>
>Eguagliando le due espressioni ottengo:
>
>
>$$
>I_0(1+TAR) = \frac{I_0(1+TAN)}{1+i}
>$$
>
>Per cui il TAR è definito come:
>
>
>$$
>TAR = \frac{1+TAN}{1+i} -1 = \frac{1+TAN-1-i}{1+i} = \frac{TAN-i}{1+i}
>$$

***

>[!CAUTION]
>## Si descriva la formula di determinazione dell’ammortamento lineare di un bene capitalizzabile e si illustri se e come interviene l’ammortamento nella definizione dei flussi di cassa di un progetto di investimento nel bene.
>
>L’**ammortamento lineare** è un metodo che consente di ripartire **in parti uguali il costo** di un bene capitalizzabile lungo la sua vita utile. La formula per determinare l’ammortamento annuo è:
>
>$$
>\text{Ammortamento} = \frac{\text{Costo di acquisto} - \text{Valore residuo}}{\text{Anni di vita utile del bene}}
>$$
>
>A livello finanziario, la spesa del bene avviene tutta in un’unica soluzione. A livello di flussi di cassa, la somma totale di acquisto del bene viene spalmata nei vari anni di vita utile del bene. Quindi avrò n flussi di cassa negativi pari al valore dell’ammortamento lineare calcolato.
>
>L’ammortamento gioca un ruolo fondamentale nel **calcolo delle tasse**: le tasse si calcolano sugli utili, la presenza di un ammortamento diminuisce gli utili e quindi anche le tasse.

***

>[!IMPORTANT]
>## Come si determina il Tasso annuo equivalente a partire dal tasso annuo, considerando una capitalizzazione trimestrale?
>
>Il **Tasso Annuo Equivalente (TAE)** è il tasso che misura il rendimento effettivo di un investimento quando il periodo di capitalizzazione non è annuale, ma è frazionato.

>[!TIP]
>### Dimostrazione della formula del TAE
>
>Dopo un anno, il capitale accumulato con capitalizzazione frazionata in $m$ periodi, partendo da un investimento $I_0$ iniziale è:
>
>$$
>V_1 = I_0 (1+ \frac{TAN}{m})^m
>$$
>
>Il Tasso Annuo Equivalente TAE, è per definizione, il tasso che soddisfa la seguente relazione:
>
>$$
>V_1 = I_0 (1+ TAE)
>$$
>
>Eguagliando le due espressioni ottengo:
>
>
>$$
>I_0 (1+ TAE) = I_0 (1+ \frac{TAN}{m})^m
>$$
>
>Per cui il TAE è definito come:
>
>
>$$
>TAE = (1+ \frac{TAN}{m})^m -1
>$$
>
>Nel caso di una capitalizzazione trimestrale $m=4$:
>
>
>$$
>TAE = (1+ \frac{TAN}{4})^4 -1
>$$
>
>*(m=4 perché in un anno ho 4 trimestri).*
