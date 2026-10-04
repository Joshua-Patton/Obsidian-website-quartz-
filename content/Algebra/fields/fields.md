A field is abelian [[groups|group]] under addition and abelian group under multiplication, with distributive property.

- the characteristic - how many times you must add 1 to get to zero, (zero if it never happens)



- [[history of field theory]]
- why fields are important
- examples of fields and their properties

- [[field extensions]]

- [[Reducibility]]
- [[Field polynomials]]



- [[Galois theory]]









# some later topics
Finite fields and Frobenius
Roots of unity
Field norms and traces
Primitive element theorem
Symmetric polynomials
Valuations
Local fields such as
Number fields
Function fields
Transcendental extensions
Krull dimension and transcendence degree
Algebraic geometry and function fields
Étale extensions
Infinite Galois theory
Profinite Galois groups
Absolute Galois groups

> [!NOTE] <!--easygit-callout:original=exercise,collapse=--->
> # Difficult Field Theory Exercises
> 
> ## 1. Normal Closure Bound
> 
> Let $E/F$ be a finite separable extension with $[E:F]=n$, and let $N/F$ be its normal closure. Prove that $[N:F]\mid n!$. Let $G=\operatorname{Gal}(N/F)$ act on $\operatorname{Hom}_F(E,N)$. Determine necessary and sufficient conditions for $[N:F]=n!$ in terms of this action.
> 
> **Topics:** Normal closures, embeddings, separability, Galois groups.
> 
> **Reference:** [Harvard — Field Theory and Galois Theory Qualifying Questions](https://www.math.harvard.edu/media/galois.pdf)
> 
> ## 2. Normality Is Not Transitive
> 
> Construct fields $K\subset L\subset M$ such that $L/K$ and $M/L$ are finite normal extensions, but $M/K$ is not normal. Compute $[L:K]$, $[M:L]$, and $[M:K]$. Determine the normal closure $N$ of $M/K$, compute $[N:K]$, and determine $\operatorname{Gal}(N/K)$.
> 
> **Topics:** Normal extensions, towers, normal closures.
> 
> **Reference:** [Stanford Math 210B — Field Theory Exercises](https://math.stanford.edu/~akshay/210B/hw5.pdf)
> 
> ## 3. Primitive Element with a Constraint
> 
> Let $L/K$ be a finite separable extension with $K$ infinite, and suppose $L=K(\alpha,\beta)$. Prove that $L=K(\alpha+c\beta)$ for all but finitely many $c\in K$. Find a bound for the number of exceptional values of $c$ in terms of $[L:K]$.
> 
> **Topics:** Primitive element theorem, embeddings, separability.
> 
> **Reference:** [Berkeley Math 114 — Galois Theory](https://math.berkeley.edu/~serganov/114/)
> 
> ## 4. Tensor Products of Fields
> 
> Let $K/k$ be finite separable and let $L/k$ be any field extension. Prove that $K\otimes_kL$ is isomorphic as an $L$-algebra to a finite product $L_1\times\cdots\times L_r$, where each $L_i/L$ is finite separable. Determine necessary and sufficient conditions for $K\otimes_kL$ to be a field, and relate this to linear disjointness.
> 
> **Topics:** Tensor products, separability, linear disjointness.
> 
> **Reference:** [Harvard — Past Qualifying Exams](https://www.math.harvard.edu/graduate/study-the-qualifying-exam/some-old-qualifying-exams/)
> 
> ## 5. Finite Fields and Primitive Elements
> 
> Let $K=\mathbb F_q$ and $L=\mathbb F_{q^n}$. Prove from first principles that $L^\times$ is cyclic. Deduce that $L/K$ is simple. Prove that the norm $N_{L/K}:L^\times\to K^\times$ is surjective and determine the norm explicitly as a power map.
> 
> **Topics:** Finite fields, cyclic groups, primitive elements, norms.
> 
> **Reference:** [Stanford Math 210B — Field Theory Exercises](https://math.stanford.edu/~akshay/210B/hw5.pdf)
> 
> ## 6. Separable and Purely Inseparable Decomposition
> 
> Let $L/K$ be a finite normal extension, not necessarily separable, and let $G=\operatorname{Aut}_K(L)$. Prove that $L/L^G$ is separable and $L^G/K$ is purely inseparable. If $L_s$ is the maximal separable subextension of $L/K$, prove that $L_s/K$ is Galois. Determine the precise hypotheses under which the natural map $L_s\otimes_KL^G\to L$ is an isomorphism.
> 
> **Topics:** Separability, purely inseparable extensions, fixed fields.
> 
> **Reference:** [Stanford Math 210B — Field Theory Exercises](https://math.stanford.edu/~akshay/210B/hw5.pdf)
> 
> ## 7. Inseparable Degree
> 
> Let $L/K$ be a finite extension with $\operatorname{char}(K)=p>0$. Prove that there exists a unique maximal separable intermediate field $K\subseteq L_s\subseteq L$. Prove that $[L:L_s]=p^r$ for some $r\geq0$, and that the number of distinct $K$-embeddings $L\hookrightarrow\overline K$ equals $[L_s:K]$. Deduce the relation between total degree, separable degree, and inseparable degree.
> 
> **Topics:** Separable degree, inseparable degree, embeddings.
> 
> **Reference:** [Harvard — Field Theory and Galois Theory](https://www.math.harvard.edu/media/galois.pdf)
> 
> ## 8. Quartic Splitting Field
> 
> Let $K$ be the splitting field over $\mathbb Q$ of $f(x)=x^4-x^2-1$. Determine $K$ explicitly, compute $[K:\mathbb Q]$, and determine $\operatorname{Gal}(K/\mathbb Q)$. Determine the complete lattice of intermediate fields using the Galois correspondence, and identify which intermediate extensions are normal over $\mathbb Q$.
> 
> **Topics:** Splitting fields, quartics, Galois correspondence.
> 
> **Reference:** [Harvard — Past Qualifying Exams](https://www.math.harvard.edu/graduate/study-the-qualifying-exam/some-old-qualifying-exams/)
> 
> ## 9. Composita and Intersections
> 
> Let $E/K$ and $F/K$ be finite extensions in a common algebraic closure, with $E/K$ Galois. Prove that $[EF:F]=[E:E\cap F]$. Deduce that $E$ and $F$ are linearly disjoint over $K$ if and only if $E\cap F=K$. Investigate what can fail when $E/K$ is not Galois and construct an explicit counterexample.
> 
> **Topics:** Composita, intersections, linear disjointness.
> 
> **Reference:** [Berkeley Math 114 — Galois Theory](https://math.berkeley.edu/~ribet/114/)
> 
> ## 10. Automorphisms of Algebraically Closed Fields
> 
> Let $L$ be an algebraically closed field of characteristic $0$. Prove that $L$ cannot possess a field automorphism of finite odd prime order. Study the fixed field $K=L^{\langle\sigma\rangle}$, the roots of unity in $L$, and the norm map $N_{L/K}:L^\times\to K^\times$.
> 
> **Topics:** Automorphisms, fixed fields, roots of unity, norms.
> 
> **Reference:** [Stanford Math 210B — Field Theory Exercises](https://math.stanford.edu/~akshay/210B/hw5.pdf)
> 
> ## 11. Algebraic Closure of a Finite Field
> 
> Let $\overline{\mathbb F_p}$ be an algebraic closure of $\mathbb F_p$. Prove that every finite subextension is of the form $\mathbb F_{p^n}$ and that $\mathbb F_{p^m}\subseteq\mathbb F_{p^n}$ if and only if $m\mid n$. Determine $\operatorname{Aut}_{\mathbb F_p}(\overline{\mathbb F_p})$ and explain the role of the Frobenius automorphism $x\mapsto x^p$. Explain why infinite Galois theory requires more structure than the finite Galois correspondence.
> 
> **Topics:** Finite fields, Frobenius, infinite Galois extensions.
> 
> **Reference:** [Berkeley Math 114 — Galois Theory](https://math.berkeley.edu/~serganov/114/)
> 
> ## 12. Purely Inseparable Tower
> 
> Let $K=\mathbb F_p(s,t)$ and $L=K(s^{1/p^m},t^{1/p^n})$ for $m,n\geq1$. Determine $[L:K]$, its separable and inseparable degrees, its exponent, and $\operatorname{Aut}_K(L)$. Investigate the intermediate fields $K\subseteq E\subseteq L$ and determine whether $L/K$ can be simple.
> 
> **Topics:** Purely inseparable extensions, characteristic $p$.
> 
> ## 13. Galois Group from Factorisation Data
> 
> Let $f(x)\in\mathbb Q[x]$ be irreducible of degree $5$ with nonsquare discriminant. Suppose that for suitable primes $p$ and $q$, the reduction modulo $p$ factors as an irreducible quadratic times an irreducible cubic, while modulo $q$ remains irreducible. Translate these factorizations into cycle types in $\operatorname{Gal}(f/\mathbb Q)\subseteq S_5$ and determine the possible Galois group, justifying every group-theoretic restriction used.
> 
> **Topics:** Galois groups, cycle types, discriminants.
> 
> **Reference:** [Harvard — Field Theory and Galois Theory](https://www.math.harvard.edu/media/galois.pdf)
> 
> ## 14. Transcendence Degree
> 
> Let $L=K(\alpha_1,\ldots,\alpha_n)$ be a finitely generated field extension. Prove that every maximal algebraically independent subset of $\{\alpha_1,\ldots,\alpha_n\}$ has the same cardinality, thereby proving that $\operatorname{trdeg}_K L$ is well-defined. For $K\subseteq F\subseteq L$, prove under suitable hypotheses that $\operatorname{trdeg}_K L=\operatorname{trdeg}_K F+\operatorname{trdeg}_F L$.
> 
> **Topics:** Algebraic independence, transcendence bases, transcendence degree.
> 
> ## 15. Normal Basis Theorem
> 
> Let $L/K$ be a finite Galois extension with $G=\operatorname{Gal}(L/K)$. Prove that there exists $\alpha\in L$ such that $\{\sigma(\alpha):\sigma\in G\}$ is a $K$-basis of $L$. First prove the result for finite fields, then prove the general case. Interpret the theorem in terms of the $K[G]$-module structure of $L$.
> 
> **Topics:** Normal bases, Galois extensions, automorphisms.
> 
> **Reference:** [Berkeley Math 114 — Galois Theory](https://math.berkeley.edu/~serganov/114/)

