Optimization task:

$$
\min\limits_{x \in D} f(x) = \min_{x \in D} \mathbf{E_{\xi \sim \pi(\xi)}} f(x, \xi) 
$$

- $x$ - parameters of model restricted to set $D$ 
- $\xi$ - represents samples from training set describing $\pi$ probability distribution


Bias term:


$$
\mathbf{E}_{e,\xi}[ \nabla f_\gamma(x,e,\xi)] = \nabla f_\gamma 
$$


$$
\Delta \lesssim \frac{\varepsilon^2}{\sqrt{d}}
$$


Algorithm assumption:

$$
\mathbf{E}_{e,\xi}[\| \nabla f_\gamma(x,e,\xi) \|_q^2] \le \sigma^2
$$


For l2:

$$
\mathbf{E}_{e,\xi}[\| \nabla f_\gamma(x,e,\xi) \|_q^2] \le \kappa(p,d)\left(M_2^2 + \frac{d^2 \Delta^2}{12(1+\sqrt{2}^2 \gamma^2)}\right)
$$

Optimal convexity parameter:


l1-regulization:

$$
    \gamma = \frac{\sqrt{d}\varepsilon}{4M_2}
$$

l2-regulization:

$$
    \gamma = \frac{\varepsilon}{2M_2}
$$
