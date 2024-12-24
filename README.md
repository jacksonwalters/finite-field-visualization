# finite-field-visualization

This code creates visualizations of finite fields using `matplotlib`.

For a finite field with multiplicative generator $\alpha$, we use the map

$$\alpha^k \mapsto \exp(2 \pi i k / (q-1))$$

which is used in computing Brauer characters for representations over finite fields.

If $q = p^r$, we label points on the unit circle with their corresponding vector representation over $F_q$ in terms of a monomial basis.

That is, $F_q \cong F_p[x]/(f(x))$ where $f(x)$ is a suitable polynomial of degree $r$, usually a Conway polynomial.

One can then see the interplay of the multiplicative structure (a cyclic group of size $q-1$) and the additive structure (an $F_p$ vector space).

![F_25](images/finite_field_25.png)
