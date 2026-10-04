#formal
Eisenstein criteria gives us conditions for when a integer polynomial is irreducible over the rationals,

Given $P(x)=a_{0} +a_{1}x +a_{2}x^2\dots a_{n}x^n \in \mathbb{Z}(X)$
- $p$ divides each $a_i$ for $0 ≤ i < n$,
- $p$ does not divide $a_n$
- $p^2$ does not divide $a_0$
The the polynomial is irreducible over $\mathbb{Q}$
---




> [! exercise]-
> 
> # Eisenstein Criterion — Exercises
> 
> ## Easy
> 
> - **1.** Show that $x^2+2x+2$ is irreducible over $\mathbb{Q}$ using Eisenstein's criterion.
> 
> - **2.** Show that $x^3+3x^2+6x+3$ is irreducible over $\mathbb{Q}$.
> 
> - **3.** Show that $x^4+5x^3+10x^2+15x+5$ is irreducible over $\mathbb{Q}$.
> 
> - **4.** Show that $x^5+2x^4+6x^3+4x^2+8x+2$ is irreducible over $\mathbb{Q}$.
> 
> - **5.** Determine whether Eisenstein's criterion with $p=3$ applies to
>   $2x^4+6x^3+9x^2+12x+6$.
> 
> - **6.** Find a prime $p$ that proves
>   $3x^5+10x^4+5x^3+20x^2+15x+10$
>   is irreducible over $\mathbb{Q}$.
> 
> - **7.** Determine whether
>   $x^4+6x^3+12x^2+18x+12$
>   is Eisenstein at $p=2$, $p=3$, both, or neither.
> 
> - **8.** Construct a polynomial of degree $6$ that is Eisenstein at $p=7$.
> 
> ## Intermediate
> 
> - **9.** Explain why Eisenstein's criterion with $p=2$ fails for
>   $x^4+2x^3+4x^2+6x+4$.
> 
> - **10.** Does the failure of Eisenstein's criterion imply that the polynomial in Exercise 9 is reducible? Explain.
> 
> - **11.** Find all primes $p$ for which
>   $x^5+30x^4+60x^3+90x^2+120x+30$
>   is Eisenstein.
> 
> - **12.** Determine whether
>   $2x^5+15x^4+30x^3+45x^2+60x+15$
>   can be proved irreducible using Eisenstein's criterion.
> 
> - **13.** For which integers $n\geq2$ is
>   $x^n+6x+3$
>   immediately Eisenstein?
> 
> - **14.** Let $p$ be prime. Prove that
>   $x^n+px+p$
>   is irreducible over $\mathbb{Q}$ for every $n\geq2$.
> 
> - **15.** Let $p$ be prime. Determine when
>   $x^n+p^2x+p$
>   is Eisenstein at $p$.
> 
> ## Substitutions
> 
> - **16.** Let $f(x)=x^2+x+1$. Prove that $f(x)$ is irreducible over $\mathbb{Q}$ by applying Eisenstein's criterion to $f(x+1)$.
> 
> - **17.** Prove that
>   $x^4+x^3+x^2+x+1$
>   is irreducible over $\mathbb{Q}$ using the substitution $x\mapsto x+1$.
> 
> - **18.** Consider
>   $x^6+x^5+x^4+x^3+x^2+x+1$.
>   Try to prove irreducibility using a substitution and Eisenstein's criterion. If this fails, explain why.
> 
> - **19.** Show that $x^4+1$ is irreducible over $\mathbb{Q}$ by finding an appropriate transformation and applying Eisenstein's criterion.
> 
> - **20.** Let $p$ be prime and define
>   $f(x)=1+x+x^2+\cdots+x^{p-1}$.
>   Show that $f(x+1)$ is Eisenstein at $p$.
> 
> - **21.** Deduce that the cyclotomic polynomial
>   $\Phi_p(x)=1+x+\cdots+x^{p-1}$
>   is irreducible over $\mathbb{Q}$ whenever $p$ is prime.
> 
> ## Theory
> 
> - **22.** Prove Eisenstein's criterion using Gauss's lemma and reduction modulo $p$.
> 
> - **23.** Suppose $f(x)\in\mathbb{Z}[x]$ is Eisenstein at $p$. Prove that its constant term cannot be zero.
> 
> - **24.** Find an irreducible polynomial over $\mathbb{Q}$ for which Eisenstein's criterion applies for no prime $p$.
> 
> - **25.** Find an irreducible polynomial $f(x)$ for which Eisenstein's criterion does not apply directly to $f(x)$, but does apply to $f(x+1)$.
> 
> - **26.** Suppose $f(x)$ is Eisenstein at $p$. Determine whether $f(x^m)$ must also be Eisenstein at $p$. Prove your answer.
> 
> - **27.** Suppose
>   $f(x)=x^n+a_{n-1}x^{n-1}+\cdots+a_1x+a_0$
>   is Eisenstein at $p$.
>   Determine the $p$-adic valuation $v_p(a_0)$.
> 
> ## Challenging
> 
> - **28.** Let $p$ be prime. Prove that
>   $x^{p-1}+x^{p-2}+\cdots+x+1$
>   is irreducible over $\mathbb{Q}$ using:
>     - the binomial theorem,
>     - divisibility properties of $\binom{p}{k}$,
>     - Eisenstein's criterion,
>     - and the substitution $x\mapsto x+1$.
> 
> - **29.** Let $p$ be prime and suppose
>   $f(x)=x^n+pa_{n-1}x^{n-1}+\cdots+pa_1x+pa_0$
>   where $p\nmid a_0$.
>   If $\alpha$ is a root of $f$, prove that
>   $[\mathbb{Q}(\alpha):\mathbb{Q}]=n$.
> 
> - **30.** Construct an irreducible polynomial $f(x)\in\mathbb{Z}[x]$ of degree $10$ such that Eisenstein's criterion does not obviously apply to $f(x)$ itself, but $f(x+1)$ is Eisenstein. Prove that your polynomial is irreducible.