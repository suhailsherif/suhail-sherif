---
# Documentation: https://wowchemy.com/docs/managing-content/

title: One-Way Communication Complexity and Non-Adaptive Decision Trees
subtitle: ''
summary: ''
authors:
- Nikhil S. Mande
- Swagato Sanyal
- admin
tags: ['recent']
categories: []
date: -01-01
lastmod: 2022-05-26T04:13:27-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-05-26T08:13:27.649011Z'
publication_types:
- '1'
abstract: 'We study the relationship between various one-way communication complexity measures of a composed function with the analogous decision tree complexity of the outer function. We consider two gadgets: the AND function on 2 inputs, and the Inner Product on a constant number of inputs. More generally, we show the following when the gadget is Inner Product on $2b$ input bits for all $b \geq 2$, denoted $\mathsf{IP}$.

    - If $f$ is a total Boolean function that depends on all of its $n$ input bits, then the bounded-error one-way quantum communication complexity of $f \circ \mathsf{IP}$ equals $\Omega(n(b-1))$.

    - If $f$ is a *partial* Boolean function, then the deterministic one-way communication complexity of $f \circ \mathsf{IP}$ is at least the non-adaptive decision tree complexity of $f$.


To prove our quantum lower bound, we first show a lower bound on the VC-dimension of $f \circ \mathsf{IP}$. We then appeal to a result of Klauck [STOC ''00], which immediately yields our quantum lower bound.
Our deterministic lower bound relies on a combinatorial result independently proven by Ahlswede and Khachatrian [Adv. Appl. Math. ''98], and Frankl and Tokushige [Comb. ''99].


It is known due to a result of Montanaro and Osborne [arXiv ''09] that the deterministic one-way communication complexity of $f \circ \mathsf{XOR}$ *equals* the non-adaptive parity decision tree complexity of $f$.
In contrast, we show the following when the inner gadget is the AND function on 2 input bits.

    - There exists a function for which even the *quantum* non-adaptive AND decision tree complexity of $f$ is exponentially large in the deterministic one-way communication complexity of $f \circ \mathsf{AND}$.
    
    - However, for symmetric functions $f$, the non-adaptive AND decision tree complexity of $f$ is at most quadratic in the (even two-way) communication complexity of $f \circ \mathsf{AND}$.


In view of the first bullet, a lower bound on non-adaptive AND decision tree complexity of $f$ *does not* lift to a lower bound on one-way communication complexity of $f \circ \mathsf{AND}$.


The proof of the first bullet above uses the well-studied *Odd-Max-Bit* function. 


For the second bullet, we first observe a connection between the one-way communication complexity of $f$ and the *Möbius sparsity* of $f$, and then give a lower bound on the Möbius sparsity of symmetric functions. An upper bound on the non-adaptive AND decision tree complexity of symmetric functions follows implicitly from prior work on combinatorial group testing; for the sake of completeness, we include a proof of this result.


It is well known that the rank of the communication matrix of a function $F$ is an upper bound on its deterministic one-way communication complexity. This bound is known to be tight for some $F$. However, in our final result we show that this is not the case when $F = f \circ \mathsf{AND}$. More precisely we show that for all $f$, the deterministic one-way communication complexity of $F = f \circ \mathsf{AND}$ is at most $(\mathsf{rank}(M_{F}))(1 - \Omega(1))$, where $M_{F}$ denotes the communication matrix of $F$.'
publication: '*STACS 2022*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2105.01963
---
