# Outline of sections removed from version 1

These headings were removed from `treatise_differential_forms.tex` (Architecture A2).
Re-add each one when its reading starts.

## 5. De Rham Theory (removed subsection)

- 5.2 Singular (Co)Homology

## 6. Fibre Bundles

- 6.1 General Fibre Bundles
- 6.2 Principal Bundles
- 6.3 Vector Bundles (the basic definitions now sit in section 3.5)
- 6.4 Connections
- 6.5 Curvature

## 7. Lie Theory

- 7.1 Lie Groups
- 7.2 Lie Algebra
- Lie Algebroid (definition left blank)

Text of the Lie algebra definition:

```latex
\begin{definition}[Lie Algebra]\label{def:lie_algebra}
    A Lie algebra over a field $K$ is a $K$-vector space $\mathfrak{g}$ with a binary operation $[\cdot, \cdot] \colon \mathfrak{g} \times \mathfrak{g} \to \mathfrak{g}$, called the Lie bracket, which is
    \begin{enumerate}
        \item bilinear: $[\lambda x + \mu y, z] = \lambda[x, z] + \mu[y, z]$, $[z, \lambda x + \mu y] = \lambda[z, x] + \mu[z, y]$;
        \item alternating: $[x, x] = 0$; and
        \item satisfies the Jacobi identity: $[x, [y, z]] + [z, [x, y]] + [y, [z, x]] = 0$
    \end{enumerate}
    for all $x, y, z \in \mathfrak{g}$ and $\lambda, \mu \in K$.
\end{definition}
\begin{remark}
    If the field $K$ is not of characteristic two, then the lie bracket is also anticommutative.
    We can use anticommutativity to rewrite the Jacobi identity as
    \begin{equation}
        [x, [y, z]] = [[x, y], z] + [y, [x, z]],
    \end{equation}
    showing that $[x, \cdot]$ is akin to a derivation.
\end{remark}
```

## 8. Riemannian Geometry

## 9. Applications

## Old source TODOs

- START FIBRE BUNDLES
- MOVE MULTILINEAR ALGEBRA BEFORE MANIFOLDS
- MOVE DIFFERENTIAL FORMS AFTER MANIFOLDS, THEN FIBRE BUNDLES, THEN THE REST
