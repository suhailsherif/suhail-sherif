---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Lifting to Parity Decision Trees via Stifling
subtitle: ''
summary: ''
authors:
- Arkadev Chattopadhyay
- Nikhil S. Mande
- admin
- Swagato Sanyal
tags: ['recent']
categories: []
date: '2023-01-11'
lastmod: 2023-01-11T02:11:26-04:00
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
publishDate: '2023-01-11T06:19:58.588894Z'
publication_types:
- '1'
abstract: 'We show that the deterministic decision tree complexity of a (partial) function or relation $f$ lifts to the deterministic parity decision tree (PDT) size complexity of the composed function/relation $f \circ g$ as long as the gadget $g$ satisfies a property that we call stifling. We observe that several simple gadgets of constant size, like Indexing on 3 input bits, Inner Product on 4 input bits, Majority on 3 input bits and random functions, satisfy this property. It can be shown that existing randomized communication lifting theorems ([Göös, Pitassi, Watson. SICOMP''20], [Chattopadhyay et al. SICOMP''21]) imply PDT-size lifting. However there are two shortcomings of this approach: first they lift randomized decision tree complexity of $f$, which could be exponentially smaller than its deterministic counterpart when either $f$ is a partial function or even a total search problem. Second, the size of the gadgets in such lifting theorems are as large as logarithmic in the size of the input to $f$. Reducing the gadget size to a constant is an important open problem at the frontier of current research.<br><br>
Our result shows that even a random constant-size gadget does enable lifting to PDT size. Further, it also yields the first systematic way of turning lower bounds on the width of tree-like resolution proofs of the unsatisfiability of constant-width CNF formulas to lower bounds on the size of tree-like proofs in the resolution with parity system, i.e., $\mathrm{Res}(\oplus)$, of the unsatisfiability of closely related constant-width CNF formulas.'
publication: '*ITCS 2023*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2211.17214
- name: Talk Video
  url: https://www.youtube.com/watch?v=xcnn6jVNY0o
---
