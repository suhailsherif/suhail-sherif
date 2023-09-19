---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An improved protocol for ExactlyN with more than 3 players
subtitle: ''
summary: ''
authors:
- Lianna Hambardzumyan
- Toniann Pitassi
- admin
- Morgan Shirley
- Adi Shraibman
tags: ['recent']
categories: []
date: -01-01
lastmod: 2023-09-15T04:13:27-04:00
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
publishDate: '2023-09-15T08:13:27.649011Z'
publication_types:
- '3'
abstract: 'The ExactlyN problem in the number-on-forehead (NOF) communication setting asks $k$ players, each of whom can see every input but their own, if the $k$ input numbers add up to $N$. Introduced by Chandra, Furst and Lipton in 1983, ExactlyN is important for its role in understanding the strength of randomness in communication complexity with many players. It is also tightly connected to the field of combinatorics: its $k$-party NOF communication complexity is related to the size of the largest corner-free subset in $[N]^{k-1}$. 


In 2021, Linial and Shraibman gave more efficient protocols for ExactlyN for 3 players. As an immediate consequence, this also gave a new construction of larger corner-free subsets in $[N]^2$. Later that year Green gave a further refinement to their argument. These results represent the first improvements to the highest-order term for $k=3$  since the famous work of Behrend in 1946. In this paper we give a corresponding improvement to the highest-order term for all $k>3$, the first since Rankin in 1961. That is, we give a more efficient protocol for ExactlyN as well as larger corner-free sets in higher dimensions.


Nearly all previous results in this line of research approached the problem from the combinatorics perspective, implicitly resulting in non-constructive protocols for ExactlyN. Approaching the problem from the communication complexity point of view and constructing explicit protocols for ExactlyN was key to the improvements in the $k=3$ setting. As a further contribution we provide explicit protocols for ExactlyN for any number of players which serves as a base for our improvement.'
# publication: '*arXiv*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2309.06554
---
