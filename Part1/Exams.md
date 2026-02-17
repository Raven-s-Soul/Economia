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























