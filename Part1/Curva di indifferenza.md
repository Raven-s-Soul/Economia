# Curva di indifferenza

> Cap 4: par. 4.2 e 4.3; Capitolo 3; 

![Curva di indifferenza](./imgs/Curva%20di%20indifferenza.png)

> [!WARNING]
> ### Cobb-Douglas (esponenziale)
> Un esempio classico di curva di indifferenza regolare è la **curva di indifferenza di Cobb Douglas**: $\quad \mathnormal{U} (x_1 , x_2) = x_1^\alpha \cdot  x_2^\beta$
> > Soluzione ottima di Cobb Douglass non può essere mai ne di origine ne di frontiera.
>

Il paniere accessibile è una scelta interna a esso prende il nome di **soluzione interna**, mentre quando è tangente soddisfa la **condizione di tangenza**.

- tecnicamente le soluzione interne soddisfano *sempre* le condizione di tangenza.

### Non si intersecano:

- Se due curve si incrociassero, lo stesso paniere avrebbe due livelli di utilità diversi, il che è impossibile.
- **Implica preferenze coerenti**.

### Pendenza negativa:

- Per mantenere la stessa utilità, se aumenti il bene X devi ridurre il bene Y (e viceversa).
- Deriva dall’**ipotesi di non sazietà** (più è meglio).

### **Convessità verso l’origine**

- La curva è curva (non retta), piegata verso l’origine.
- Questo riflette la **preferenza per la varietà**: il consumatore preferisce combinazioni equilibrate dei beni piuttosto che estremi.
- Implica che il **saggio marginale di sostituzione (SMS)** diminuisce man mano che sostituisci un bene con l’altro.

### **Curve più lontane dall’origine = maggiore utilità**

- Spostandoti verso destra e in alto, aumentano le quantità dei beni → aumenta la soddisfazione.
- Deriva dall’ipotesi di **monotonicità delle preferenze**.

### **Continuità e densità**

- Le curve sono **continue** (senza salti) e **dense**: tra due curve qualsiasi, ne esistono infinite altre.
- Riflette preferenze ben definite e continue.
</aside>

<aside>

### **Quando accade una soluzione di frontiera?**

1. **Preferenze non bilanciate**
    - Il consumatore trae molta più utilità da un bene rispetto all’altro, quindi destina tutto il reddito a quello.
2. **Prezzi molto diversi**
    - Se un bene è molto più economico (o più utile in rapporto al prezzo), il consumatore lo preferisce interamente.
3. **Curve di indifferenza non convess**e
    - Ad esempio, con **beni perfetti sostituti**: le curve sono rette, quindi il consumatore compra solo il bene col **miglior rapporto U/P**.
4. **Beni complementari**
    - In casi estremi (come beni perfetti complementari a rapporto fisso), il punto ottimale è un angolo (es. scarpe: non puoi usare una scarpa sola).

### **Come si vede nel grafico?**

- Il punto ottimale **non è nell’interno della curva di bilancio**, ma su uno degli assi, dove il consumo di un bene = 0.
- Si dice che l’**ottimo è di frontiera**.
</aside>

>[!NOTE]
>## Qual è la relazione tra curva di indifferenza e funzione di utilità? [^1]
>La funzione di utilità rappresenta analiticamente le preferenze del consumatore, associando a ogni combinazione di beni un livello di soddisfazione:
>> Una curva di indifferenza è l’insieme di tutte le combinazioni di beni che garantiscono lo stesso livello di utilità. Essa è quindi ottenuta fissando la funzione di utilità a un valore costante: $U(x_1,x_2)=h$
>
>> Variando h si ottengono infinite curve di indifferenza e ad ogni curva di indifferenza corrisponde un determinato livello di utilità, e curve di indifferenza più lontane dall’origine rappresentano livelli di utilità più elevati.


***

# Tasso Marginale di Sostituzione (MRS) sulla curva di indifferenza [^1]

**Saggio Marginale** = la quantità di un bene a cui un consumatore rinuncia per avere un'unità in più di un altro, mantenendo la stessa soddisfazione

- U = funzione di utilità

$$
\begin{gather}
MRS_{U}= \frac {d Y} {d X}
\end{gather}
$$

Poiché lungo una curva di indifferenza l’utilità è costante, vale:

$$
\begin{gather}
d U = \frac {\partial U}{\partial X} dX + \frac {\partial U}{\partial Y} dY = 0
\end{gather}
$$

allora:

$$
\begin{gather}
\frac {d Y} {d X} = - \frac{\partial U/\partial X}{\partial U/\partial Y}
\end{gather}
$$

quindi:

$$
\begin{gather}
MRS_{U}= \frac {d Y} {d X} = - \frac{\partial U/\partial X}{\partial U/\partial Y}
\end{gather}
$$

- Pendenza della curva di indifferenza è l’opposto del saggio marginale di sostituzione.

>[!TIP]
>Esempio MRS è equivalente a $$A_1x_1 + A_2x_2 = k$$ dove i coefficienti delle x e tutte le variazioni che danno il rapporto richiesto $$\frac {-A_1} {A_2} = MSR$$.
>
>> esempio con MRS -0.4 quindi $$\to 4x_1 + 10x_2 = k$$
>
>Può anche essere visto come una retta ovvero $$y = mx + q$$ se si tratta di beni perfettamente sostituti.
>
>$$
>\begin{gather}
>x_2 = \frac {-A_1}{A_2} x_1 + \frac k A_2  
>\end{gather}
>$$
>
>$$
>\begin{gather}
>\frac{P_1}{P_2} = \frac {d Y} {d X} \to \quad \text{esiste un paniere dove sussiste la condizione di tangenza?}\\
>\frac{P_1}{P_2} = \frac {d Y} {d X} \to \quad \text{Equilibrio, ovvero ogni spostamento risulta ottimo}\\
>\frac{P_1}{P_2} \geq \frac {d Y} {d X} \to \quad \text{se è vero l'ottimo è una soluzione di frontiera}\\
>\frac{P_1}{P_2} \leq \frac {d Y} {d X} \to \quad \text{se è vero l'ottimo è tangente}\\
>\end{gather}
>$$
>
>> #### Analiticamente
>> "Il tasso marginale di sostituzione sulla curva di indifferenza e il tasso marginale di sostituzione sulla retta di bilancio" in base ai valori capisco se è di frontiera e me lo vado a calcolare.
>> Mi creo una funzione di utilità come $$U(x_1,x_2) = 4x_1 + 10x_2$$ e la provo nelle funzioni di frontiera.
>> #### Graficamente
>> Trovato l'insieme di bilancio, e le curve di indifferenza hanno questo trend o tendenza l'ottimo si trova ...

***

# Massimizzazione

$$
\begin{gather}
\text{Massimizzare } U(Z,P) \text{ soggetto al vincolo } P_ZZ+ P_PP < M  \\
\text{Massimizzare } U(Z,P) = \text{il valore di utilità assengnato a un paniere contentente (Z... e P...)}
\end{gather}
$$

- se i beni perfettamente divisibili, risolvibile con strumenti matematici semplici.

$$
\begin{gather}
\text{Soluzione interna}
\\
\frac{MU_P}{P_P} = \frac{MU_Z}{P_Z}
\\
\text{Soluzione di frontiera}
\\
\frac{MU_P}{P_P} \leq or \geq \frac{MU_Z}{P_Z}
\end{gather}
$$

$$
\begin{gather}
\frac{P_Z}{P_P} = \frac{MU_Z}{MU_P}
\\
\frac{MU_Z}{MU_P} = MRS_{ZP}
\end{gather}
$$

Perciò per le soluzioni di frontiera:

$$
\frac{MU_Z}{MU_P} \geq \frac{P_Z}{P_P}
$$

[^1]: appunti di telegram.
