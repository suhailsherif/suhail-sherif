---
# Documentation: https://wowchemy.com/docs/managing-content/

title: No Quantum Speedup over Gradient Descent for Non-Smooth Convex Optimization
subtitle: ''
summary: ''
authors:
- Ankit Garg
- Robin Kothari
- Praneeth Netrapalli
- admin
tags: ['recent']
categories: []
date: '2021-01-01'
lastmod: 2022-05-26T02:11:26-04:00
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
publishDate: '2022-05-26T06:19:58.784176Z'
publication_types:
- '1'
abstract: 'We study the first-order convex optimization problem, where we have black-box access to a (not necessarily smooth) function $f:\\mathbb{R}^n \\to \\mathbb{R}$ and its (sub)gradient. Our goal is to find an $\\epsilon$-approximate minimum of $f$ starting from a point that is distance at most $R$ from the true minimum. If $f$ is $G$-Lipschitz, then the classic gradient descent algorithm solves this problem with $O((GR/\\epsilon)^2)$ queries. Importantly, the number of queries is independent of the dimension n and gradient descent is optimal in this regard: No deterministic or randomized algorithm can achieve better complexity that is still independent of the dimension $n$.<br><br>
In this paper we reprove the randomized lower bound of $\\Omega((GR/\\epsilon)^2)$ using a simpler argument than previous lower bounds. We then show that although the function family used in the lower bound is hard for randomized algorithms, it can be solved using $O(GR/\\epsilon)$ quantum queries. We then show an improved lower bound against quantum algorithms using a different set of instances and establish our main result that in general even quantum algorithms need $\\Omega((GR/\\epsilon)^2)$ queries to solve the problem. Hence there is no quantum speedup over gradient descent for black-box first-order convex optimization without further assumptions on the function family.'
publication: '*ITCS 2021*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2010.01801
- name: Talk Video
  url: https://www.youtube.com/watch?v=_JpxJ8ufEKg
---
