
Non-flexible optimzation function:
$$
    f(x,\xi) =\sqrt{\left(<x,\xi> - \sum_{i=1}^d\xi_i\right) ^2}+ \|x\|_\infty + \delta 
$$

$x \in R^d$

$\xi_i \sim U[0,1]$
 
$\delta \sim \mathbf{N(0,\sigma^2)}$ 

Optimization set:

$$
    Q = \{x \in R^d: \|x \|_1 =1, x_i \ge 0 \}
$$


Goal:

$$ 
    \min\limits_{x \in Q} f(x)
$$


Constraints 

$$
    |x| < 1, x>0
$$