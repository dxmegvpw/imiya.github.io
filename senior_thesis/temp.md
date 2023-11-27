---
layout: default
title: Senior thesis
---

# Detail of the computation

We feel frustration with the challenging computations involved in studying SUSY. I will document the process of such challenging computations.

## Deriving zero-mode equations

10D SYM action in $\mathcal{N}=1$ is given by
$$
    \begin{equation}
        S
        =
        \int\text{d}^{10}X
        \sqrt{-G}
        \left[
            \int\text{d}^{4}\theta
            \mathcal{K}
            +
            \left\{
                \int\text{d}^{2}\theta
                \left(
                    \frac{1}{4g^2}
                    \mathcal{W}^{\alpha}\mathcal{W}_{\alpha}
                    +
                    \mathcal{W}
                \right)
                +
                \text{h.c.}
            \right\}
        \right]
    \end{equation}
$$
where
$$
    \begin{align}
        \mathcal{K}
        &=
        \frac{2}{g^2}
        h^{\bar{i}j}
        \text{Tr}
        \left[
            \left\{
            (
                \sqrt{2}\bar{\partial_{\bar{i}}}
                +
                \bar{\phi}_{\bar{i}}
            )
            e^{-V}
            \right\}
            \left\{
            (
                \sqrt{2}\partial_{j}
                +
                \phi_{j}
            )
            e^{-V}
            \right\}
        \right.
        \nonumber
        \\
        &\hspace{100pt}
        \left.
            +
            (
                \bar{\partial}_{\bar{i}}e^{-V}
            )
            (
                \partial_{j}e^{V}
            )
        \right]
        +
        \mathcal{K}_\text{WZW}
        ,
        \\
        \mathcal{W}
        &=
        \frac{1}{g^2}
        \varepsilon^{\text{ijk}}
        e^{\ i}_{\text{i}}e^{\ j}_{\text{j}}e^{\ k}_{\text{k}}
        \text{Tr}
        \left[
            \sqrt{2}\phi_{i}
            \left(
                \partial_{j}\phi_{k}
                -
                \frac{1}{3\sqrt{2}}[\phi_{j},\phi_{k}]
            \right)
        \right]
        .
    \end{align}
$$
The term $\mathcal{K}_\text{WZW}$ is so called Wess-Zumino-Witten term which vanishes when we take Wess-Zumino gauge
$$
    \begin{align}
        V
        &=
        -
        \theta\sigma^{\mu}\bar{\theta}A_{\mu}
        +
        i\overline{\theta\theta}\theta\lambda_{0}
        -
        i\theta\theta\overline{\theta\lambda}_{0}
        +
        \frac{1}{2}\theta\theta\overline{\theta\theta}
        ,
        \\
        \phi_{i}
        &=
        \frac{1}{\sqrt{2}}
        A_i
        +
        \sqrt{2}\theta\lambda_{i}
        +
        \theta\theta F_{i}.
    \end{align}
$$












## Reference

1. H. Abe, T. Kobayashi, H. Ohki, and K. Sumita, *“Superfield description of 10D SYM theory with magnetized extra dimensions,”* Nuclear Physics B, vol. 863, no. 1, pp. 1–18, Oct. 2012, [doi: 10.1016/j.nuclphysb.2012.05.012](https://www.sciencedirect.com/science/article/pii/S0550321312002714).

