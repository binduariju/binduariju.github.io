---
title: "Lower Bounds for Approximate Sign Rank"
collection: publications
permalink: /publication/2026-approximate-sign-rank
date: 2026-05-01
venue: "arXiv Preprint"
paperurl: "https://arxiv.org/abs/2605.01038"
citation: "<b>Bindua, R.</b>, Hatami, H., Karimi, H., & Robere, R. (2026). 'Lower Bounds for Approximate Sign Rank.' <i>arXiv preprint arXiv:2605.01038</i>."
---

We prove new upper and lower bounds on \emph{$\epsilon$-approximate sign-rank}, a relaxation of sign-rank introduced by Chornomaz, Moran, and Waknine. 
We prove that every $m \times n$ sign matrix with approximate sign-rank~$d$ contains a monochromatic rectangle of size $d^{-O(d)}m \times d^{-O(d^2)}n$, paralleling classical results for exact sign-rank.  
As an application of our rectangle theorem, we establish a lower bound of $\Omega_{\epsilon,\gamma}(\sqrt{d/\log d})$ on the $\epsilon$-approximate sign-rank of $\gamma$-margin $d$-dimensional half-spaces.
Prior to our work, the only general lower bound technique known for approximate sign-rank yielded lower bounds of strength $\epsilon^{-1} - 1$, which are constant for fixed~$\epsilon$.

A key ingredient in the proof of our monochromatic rectangle theorem is a new geometric theorem on hyperplane avoidance. We show that for any set of $n$ points in general position in $\mathbb{R}^d$, there exist $d$ subsets, each of size $d^{-O(d)}\, n$, such that no hyperplane simultaneously splits all of them. The proof of the geometric theorem combines the Forster--Barthe isotropic position theorem, with the Bourgain--Tzafriri restricted invertibility principle.

Next, we study the relationship between approximate sign-rank and VC dimension. 
We prove a lower bound on approximate sign-rank in terms of VC dimension, and exhibit concept classes of VC dimension $2$ with large approximate sign-rank.

Finally, we study the approximate sign-rank of the $2^m \times 2^m$ Hadamard matrix $H_m$.
The sign-rank of $H_m$ is known to be $\Omega(\sqrt{2^m})$ by Forster's classic theorem.
Contrasting this result, we adapt an argument of Alman and Williams to show that the approximate sign-rank of $H_m$ is at most $m^{O(\sqrt{m} \log (1/\epsilon))}$, and hence the Hadamard matrix does not witness polynomial-strength lower bounds for approximate sign-rank.
By using our VC dimension bound, we prove that the approximate sign-rank of $H_m$ is at least $\Omega_\epsilon(m)$.
