# Exams Part1


## 13/11/2019 - A3 Si descriva formalmente il problema del costo minimo di produzione presentando e discutendo la relazione di ottimalità. 

L’obiettivo di un produttore è produrre un certo output abbattendo il più possibile i costi.

>Conoscendo:
>- output desiderato $\bar Y$
>- Il vettore dei prezzi dei processi produttivi $W = (w_1,w_2,...,w_n)$
>- la funzione di produzione $y=f(z_1,z_2,...,z_n)$
>

Allora è possibile risolvere un problema di minimo per trovare quei fattori produttivi che mi permettono di produrre $\bar Y$ minimizzando la spesa dei fattori produttivi.

Nel caso bidimensionale:

$$
\begin{gather}
\frac{\text{min}}{z_1,z_2} \quad w_1z_1+w_2z_2 \\
f(z_1,z_2) \geq \bar Y \\
z_1 \geq 0 \\
z_2 \geq 0
\end{gather}
$$

L’ottimo del produttore si ha nel punto di tangenza tra l’isoquanto associato al livello di output $\bar Y$ e la retta di isocosto. In particolare:

$$
(z_1',z_2') = 
\begin{cases}
f(z_1,z_2) = \bar Y \\
-\frac{w_1}{w_2}=-\frac{\partial f/\partial z_1}{\partial f/\partial z_2}
\end{cases}
$$

La seconda condizione afferma che, nel punto di costo minimo, il saggio marginale di sostituzione tecnica tra $z_1$ e $z_2$ è uguale al rapporto dei loro prezzi.

***

## 23/02/2023 Si fornisca, dimostrandolo, un esempio di funzione di produzione che presenti rendimento di scala crescenti (dimostrando il comportamento)

Una funzione di produzione che ha rendimento di scala crescenti è $y=(z_1+z_2)^2$:


$$
\begin{gather}
f(tz_1,tz_2) = (tz_1,tz_2)^2 = t^2(z_1,z_2)^2 \\
t*f(tz_1,tz_2) = t^2(z_1,z_2)^2
\end{gather}
$$

$f(tz_1,tz_2) > t*f(z_1,z_2)$ per cui i rendimenti di scala sono crescenti.

***

## 13/11/2024 Rappresentare una possibile funzione di domanda ad elasticità costante con elasticità pari in modulo a 3 nel caso in cui il consumatore acquisti 128 unità di prodotto in corrispondenza di un prezzo pari a 2 euro.

Le funzioni di domanda a elasticità costante hanno la forma $q(p)=\frac{a}{p^b}$
- $\epsilon = |3| \to b = 3$
- q = 128
- p = 2

$$
128 = \frac{a}{2^3} \to a = 128 * 2^3 = 1024
$$

allora:

$$
q(p) = \frac{1024}{p^3}
$$

















































