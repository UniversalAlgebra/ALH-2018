**Title.** Splitting residuated (semi)lattices

**Speaker.** P. Aglianó

**Institution.** Via Roma 56 53100, Siena, Italy

**Abstract.**
The concept of splitting is of lattice-theoretic origin; if $$\mathbf{L}$$ is any lattice a pair $$(a,b) \in L^2$$ of elements of $$L$$ is a **splitting pair** if $$L$$ is equal to the disjoint union of the ideal generated by $$a$$ and the filter generated by $$b$$.  If $$\mathcal{V}$$ is any variety, an algebra $$\mathbf{A} \in \mathcal{V}$$ is **splitting in $$\mathcal{V}$$** if $$\mathbb{V}(\mathbf{A})$$ is the right member of a splitting pair in the lattice of subvarieties of $$\mathcal{V}$$. A more transparent definition is the following: $$\mathbf{A}$$ is splitting in $$\mathcal{V}$$ if there is a subvariety $$\mathcal{W}_{\mathbf{A}} \subseteq \mathcal{V}$$ (the {\bf conjugate variety of $$\mathbf{A}$$}) such that for any variety $$\mathcal{U} \subseteq \mathcal{V}$$ either $$\mathcal{U}\subseteq \mathcal{W}_{\mathbf{A}}$$ or $$\mathbf{A} \in \mathcal{U}$$.

Splitting lattices were introduced by P. Whitman (1943) in the early 40's; thirty years later R. McKenzie (1972) explored the concept with greater fortune. Note that if $$(a,b)$$ is a splitting pair then, by a standard lattice theoretic argument, $$b$$ must be completely meet prime and $$a$$ completely join prime. If we apply this to the splitting pair $$(\mathcal{W}_{\mathbf{A}},\mathbb{V}(\mathbf{A}))$$ then $$\mathcal{W}_{\mathbf{A}}$$ is axiomatized by a single equation and $$\mathbf{A}$$ is a finitely generated subdirectly irreducible algebra. If moreover $$\mathcal{V}$$ is generated by its finite algebras, then $$\mathbf{A}$$ must in fact be finite and if $$\mathcal{V}$$ is also congruence distributive then (by Jónsson Lemma) $$\mathbf{A}$$ is in fact unique.  We summarize all this in a theorem:

**Theorem 1.** [McKenzie (1972)] Let $$\mathcal{V}$$ be a congruence distributive variety that is generated by its finite algebras; then any splitting algebra $$\mathbf{A}$$ in $$\mathcal{V}$$ is finite and subdirectly irreducible. Moreover the conjugate variety $$\mathcal{W}_{\mathbf{A}}$$ is axiomatizable by a single equation in the language of $$\mathcal{W}$$.

Being generated by its finite algebras is  the *finite model property* for the equational theory of $$\mathcal{V}$$: if an equation fails in $$\mathcal{V}$$, then it fails in some finite algebra in $$\mathcal{V}$$. The equation whose existence is postulated by Theorem 1 is called the **splitting equation** of $$\mathbf{A}$$.
Note that the theorem does not say that if the hypotheses hold, then there is a splitting algebra in $$\mathcal{V}$$; nor its proof produces an effective way of determining the splitting equation of $$\mathbf{A}$$, in case it is splitting. Both the existence and the splitting equation require *ad hoc* arguments; and in 1972 McKenzie did exactly that, characterizing  the splitting algebras in the variety of all lattices and also giving an algorithm (still the only one available) for their splitting equations.

Almost in the same period of time in which R. McKenzie was working towards his results, in a different part of the world  V. Jankov was studying intermediate logics, which amounts to studying subvarieties of the variety $$\mathcal{H}\mathcal{A}$$ of Heyting algebras. In his investigations Jankov (1968) found a way to associate to any finite subdirectly irreducible Heyting algebra $$\mathbf{A}$$ a term $$J_{\mathbf{A}}$$ (called the *Jankov formula*) and was able to prove essentially that:
1. the largest variety of Heyting algebras not containing $$\mathbb{V}(\mathbf{A})$$ is axiomatized by $$J_{\mathbf{A}} \approx 1$$;
2. hence any finite subdirectly irreducible Heyting algebra is splitting in $$\mathcal{H}\mathcal{A}$$ with splitting equation $$J_{\mathbf{A}} \approx 1$$.

<!-- A very good algebraic account of Jankov's argument can be found in \cite{GJKO}, pp. 441--444. -->

Subdirectly irreducible Heyting algebras are easily described: they are exactly all Heyting algebras having a unique maximal element below the top element $$1$$; a fancy way of saying that it that they can be represented as $$\mathbf{H} \oplus \mathbf 2$$, where $$\mathbf 2$$ is the two element Boolean algebra and $$\oplus$$ is the *ordinal sum*. So we can restate Jankov's result in this fashion:

**Theorem 2.** A finite Heyting algebra is splitting if and only if it is of the form $$\mathbf{H} \oplus \mathbf 2$$ for some Heyting algebra $$\mathbf{H}$$.

We will explain how this result can be generalized to several classes of residuated (semi)lattices.
