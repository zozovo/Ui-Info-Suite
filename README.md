$$
\begin{align*}
\Pr(A_n|B) = \frac{\Pr(B|A_n)\Pr(A_n)}{\Pr(B)} &= \frac{\Pr(B|A_n)\Pr(A_n)}{\Pr(B|A_n)\Pr(A_n) + \Pr(\neg A_n)\Pr(B|\neg A_n)} \\
&= \frac{\Pr(B|A_n)\Pr(A_n)}{\sum_{i} \Pr(B|A_i)\Pr(A_i)} \\
&= \frac{\Pr(B|A_n)\Pr(A_n)}{\Pr(A_1)\Pr(B|A_1)+\Pr(A_2)\Pr(B|A_2)+\cdots+\Pr(A_i)\Pr(B|A_i)}
\end{align*}
$$
