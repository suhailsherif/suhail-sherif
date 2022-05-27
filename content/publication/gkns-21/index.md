---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Near-Optimal Lower Bounds For Convex Optimization For All Orders of Smoothness
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
lastmod: 2022-05-26T02:21:48-04:00
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
publishDate: '2022-05-26T06:21:48.391481Z'
publication_types:
- '2'
abstract: 'We study the complexity of optimizing highly smooth convex functions. For a positive integer $p$, we want to find an $\\epsilon$-approximate minimum of a convex function $f$, given oracle access to the function and its first $p$ derivatives, assuming that the $p$th derivative of $f$ is Lipschitz.
Recently, three independent research groups (Jiang et al., PLMR 2019; Gasnikov et al., PLMR 2019; Bubeck et al., PLMR 2019) developed a new algorithm that solves this problem with $\\tilde{O}(1/\\epsilon^{2/3p+1})$ oracle calls for constant $p$. This is known to be optimal (up to log factors) for deterministic algorithms, but known lower bounds for randomized algorithms do not match this bound. We prove a new lower bound that matches this bound (up to log factors), and holds not only for randomized algorithms, but also for quantum algorithms.'
publication: '*NeurIPS 2021*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2112.01118
- name: Talk Video
  url: https://www.youtube.com/watch?v=X9iXTuXpttc
---
