> [!NOTE] <!--easygit-callout:original=theorem,collapse=-->
> *Lagrange's theorem* 
> The order of any subgroup divides the order of the group
> 
> > [!proof]-
> > We consider the cosets $gH =  \{ gh:\forall h\in H \}$, where $H\leq G$ 
> > 
> > If we define the relation in $G$, where $a\sim b$ iff a and b are in the same subgroup.
> > This relation is
> > - *symmetric*: $a \sim a$ (trivial)
> > - *reflexive*: $a\sim b \to b\sim a$  (trivial)
> > - transitive: $a\sim b,b\sim c \to c\sim d$ (trivial)
> > Which means it's an equivalence relation, and it partitions $G$ equally.
> > 
> > Consider $aH$, $a$ sends every element in $H$ to another element in $G$, no 2 elements can send to the same element as $ah_{1}=ah_{2}\to h_{1}=h_{2}$ , which means all cosets of $H$ are of equal size, including $eH=H$
> > 
> > We denote the number of cosets of $H$ in $G$ as $[G:H]$, since the number of cosets divides G evenly, and the size of the coset are equal which equals H, we get $$[G:H] =\frac{\lvert G \rvert }{\lvert H \rvert }$$
> > Q.E.D

> [!NOTE] <!--easygit-callout:original=exercise,collapse=---> exercises chatgpt
> 
> 
> ## Basic
> 
> 1. Let $G$ be a finite group with $|G|=12$. List all possible orders of subgroups of $G$.
> 
> 2. Let $G$ be a finite group with $|G|=20$. Can $G$ have a subgroup of order $6$? Justify your answer.
> 
> 3. Let $H \leq G$, where $|G|=30$ and $|H|=5$. Find the index $[G:H]$.
> 
> 4. Let $G$ be a group of order $24$ and let $a \in G$. List all possible values of $|a|$.
> 
> 5. Suppose $|G|=15$. Can $G$ contain an element of order $4$?
> 
> 6. Let $G$ be a finite group and $a \in G$. Prove that $|a|$ divides $|G|$.
> 
> ## Elementary Applications
> 
> 7. Let $G$ be a group of order $35$. Show that every element $a \in G$ satisfies $a^{35}=e$.
> 
> 8. Let $G$ be a group of order $18$. Suppose $a \in G$ and $a^5=e$. Determine the possible values of $|a|$.
> 
> 9. Let $G$ be a group of order $21$. Suppose $a \neq e$. What are the possible orders of $a$?
> 
> 10. Prove that every group of prime order is cyclic.
> 
> 11. Let $G$ be a group of order $17$. Show that every nonidentity element generates $G$.
> 
> 12. Let $G$ be a group of order $p$, where $p$ is prime. Determine all subgroups of $G$.
> 
> ## Intermediate
> 
> 13. Let $G$ be a finite group and $H,K \leq G$. Suppose $\gcd(|H|,|K|)=1$. Prove that $H \cap K=\{e\}$.
> 
> 14. Let $G$ be a group of order $56$. Suppose $H \leq G$ has order $8$ and $K \leq G$ has order $7$. Prove that $H \cap K=\{e\}$.
> 
> 15. Let $G$ be a finite group and $H \leq G$. Prove that if $[G:H]=1$, then $H=G$.
> 
> 16. Suppose $G$ is finite and $H \leq K \leq G$. Prove the index formula
> 
> $[G:H]=[G:K][K:H].$
> 
> ## Harder
> 
> 17. Let $G$ be a finite group and let $H,K \leq G$. Prove that
> 
> $|HK|=\frac{|H||K|}{|H\cap K|}.$
> 
> Hint: study how many pairs $(h,k)\in H\times K$ can give the same product $hk$.
> 
> 18. Let $G$ be a group of order $pq$, where $p$ and $q$ are distinct primes. Show that every proper nontrivial subgroup of $G$ has order $p$ or $q$.
> 
> 19. Let $G$ be a finite group whose order is odd. Prove that $G$ has no element of order $2$. Deduce that the equation
> 
> $x^2=e$
> 
> has only the solution $x=e$.
> 
> 20. Let $G$ be a finite group. Suppose $\gcd(k,|G|)=1$. Prove that the map
> 
> $f:G\to G,\qquad f(x)=x^k$
> 
> is injective if $G$ is abelian. Deduce that every element of $G$ has a unique $k$-th root.


 

