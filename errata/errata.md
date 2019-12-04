## Errata in printed version of notes

- p8, Section 1.2.1. missing minus sign. Should be "probabilities $\theta$ and $1 - \theta$ respectively", not "probabilities $\theta$ and $1\theta$ respectively"
- p8, Definition 1.2. $x$ should be $y$ in the probability function.
- p9, Section 1.3.1, missing minus sign. $F(y)$ should be $1 - e^{-\theta y}$, not $1e^{-\theta y}$
- p9, Example 1.1, missing minus signs. Should be $e^{-1} - e^{-2} = 0.37 - 0.14$ not $e^{-1} e^{-2} = 0.37 0.14$.
- p10, Section 1.3.2, Definition 1.7. A *uniform* distribution has this pdf, not a *normal* distribution as stated.
- p14, Definition 2.3, missing minus sign. $\mu_r = E\left\{[Y - E(Y)]^r \right\}$, not $\mu_r = E\left\{[Y E(Y)]^r \right\}$.
- p14, Proof of Theorem 2.1, missing bracket. $\mu_3 =  E\{[Y - E(Y)]^3\}$, not
 $E\{[Y - E(Y]^3\}$.
- p16, Example 2.6. In the second line of the display for $\mu_3^\prime$, should be
 $\frac{1}{\theta^3}$ outside of the integral, not $\frac{1}{\theta^2}$.
- p17, Example 2.6. In the last line, kurtosis should be $\gamma_2 = 9$, not $\gamma_2 = 4$.
- p20, Proof of Theorem 3.1. The last line should conclude $M_Y^{(r)}(0) = \mu_r^\prime$,
not $\mu_r$.
- p23, Example 3.4. Should get $\mu_4 = 3 \sigma^4$, not $3 \sigma^2$.
- p31, Section 5.1. The defining property of the order statistics should be
\[y_{(1)} \leq y_{(2)} \leq \ldots \leq y_{(n)}\] not
\[y_{(1)} < y_{(2)} < \ldots < y_{(n)}.\]
- p31, Section 5.1. The notation for the sample maximum on line 10  has not been rendered correctly: this should be $y_{(n)}$, not y_{(n)}.
- p40, Theorem 6.1 (Cochran's Theorem), missing minus sign. Should define $V = W - U$, rather than $V = WU$.
- p41, Proof of Theorem 6.1. We need to use the fact that
$\sum_{i=1}^n (Y_i - \bar Y)^2 \geq 0$, rather than $\sum_{i=1}^n (Y_i - \bar Y) \geq 0$.
- p44, Example 7.2, missing minus sign. In first line of display, should be $P(-\log(Y) \leq u)$, not $P(\log(Y) \leq u)$.
- p49, Properties of $f(y_1, y_2)$. The limits on the integrals in property 2 should
be swapped: $y_1$ should be integrated from $a_1$ to $b_1$ and $y_2$ from $a_2$ to $b_2$.
- p50, Example 8.1. The limits on the integral have not been rendered correctly: this should be $\int_{-1}^{1} \frac{1}{4} dy_2$.
- p50, Example 8.2. The joint pdf should be $1/{\pi}$ not $1 \pi$.
- p51, Example 8.3. The integration over $y_1$ should not disappear half way down the display, and the term $y_2 dy_2$ should not appear on the penultimate line. In full, the display should be
\begin{align*}
E(Y_1 Y_2) &= \int_{-\infty}^\infty \int_{-\infty}^\infty
y_1 y_2 f(y_1, y_2) dy_2 dy_1 \\
&= \frac{1}{\pi} \int_{-1}^1 \int_{-\sqrt{1 - y_1^2}}^{\sqrt{1 - y_1^2}}
y_1 y_2 dy_2 dy_1 \\
&= \frac{1}{\pi} \int_{-1}^1 y_1 \left(\int_{-\sqrt{1 - y_1^2}}^{\sqrt{1 - y_1^2}} y_2 dy_2\right) dy_1 \\
&= \frac{1}{\pi} \int_{-1}^1 y_1 \left[\frac{y_2^2}{2}\right]_{-\sqrt{1 - y_1^2}}^{\sqrt{1 - y_1^2}} dy_1 \\
&= \frac{1}{\pi} \int_{-1}^1 y_1 \left[\frac{y_2^2}{2}\right]_{-\sqrt{1 - y_1^2}}^{\sqrt{1 - y_1^2}} dy_1 \\
&= \frac{1}{\pi} \int_{-1}^1 y_1 \times 0  dy_1 \\
&= 0,
\end{align*}
- p54, Section 8.3. In the final two displayed equations, $(1 - \rho)^2$ should be
$(1 - \rho^2)$.
- p58, Proposition 9.1. The distribution of $Y_2$ should be $\text{gamma}(n, \beta)$ not $\gamma(n, \beta)$.
- p60, proof of Proposition 9.2, mising word. Should be "the domain of 
$U_1$ and $U_2$ is clearly $U_1 \in \mathbb{R}$" rather than 
"the of $U_1$ and $U_2$ is clearly $U_1 \in \mathbb{R}$".
- p60, proof of Proposition 9.2. On final line of page, should be $\frac{|u_2|}{2 \pi} \exp \left(-\frac{u_2^2(1 + u_1^2)}{2} \right)$ not $\frac{|u_2|}{2 \pi} \exp \left(-\frac{u_2^2(1 + u_2^2)}{2} \right)$.
- p60, proof of Proposition 9.2, second line of display for $g_1(u_1)$.
Should be $\frac{1}{2 \pi}  \int_{-\infty}^\infty |u_2| \exp \left(-\frac{u_2^2(1 + u_1^2)}{2} \right)  du_2$ not  $\frac{1}{2 \pi}  \int_{-\infty}^\infty |u_2| \exp \left(-\frac{u_2^2(1 + u_2^2)}{2} \right)  du_2$.
- p62, Proposition 9.3, $Y_k$ should be $Y_2$ in the definition of $U_1$.
- p63, proof of Proposition 9. In the first line of the display for $g(u_1, u_2)$,
$y_2$ should be $u_2$.
- p75, Example 10.11. In the second display, $\frac{\bar Y \tilde \theta_2}{(1 + \bar Y \tilde \theta_2)}{\tilde \theta_2^2}$ should be $\frac{\bar Y \tilde \theta_2 (1 + \bar Y \tilde \theta_2)}{\tilde \theta_2^2}$.
- p77, Example 10.12. In second display, $\frac{d^2}{d\theta^2}$ should be
$\frac{d^2}{d\theta^2} \log L(\theta;y_1, \ldots, y_n)$.
 p78, Example 10.14. The pdf and likelihood are incorrect. They should be \[f(y; \theta) = \frac{1}{\Gamma(\theta)} y^{\theta - 1} e^{-y},
\quad y > 0,\]
and
\[L(\theta; y_1, \ldots, y_n) = \prod_{i=1}^n \frac{1}{\Gamma(\theta)}  y_i^{\theta - 1} e^{-y_i}.\]
