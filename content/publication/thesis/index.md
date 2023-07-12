---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Communication Complexity and Quantum Optimization Lower Bounds via Query Complexity
subtitle: ''
summary: ''
authors:
- admin
tags: []
categories: []
date: '2021-05-17'
lastmod: 2022-05-26T23:48:14-04:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 'One of the first published decision trees'
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-05-27T03:48:14.593793Z'
publication_types:
- '7'
abstract: 'My PhD work was in the areas of query and communication complexity. These complexity models have a rich background connecting them to each other, to polynomials, to matrices, and they also serve as practical abstractions for various computing paradigms. In this thesis we provide more insight into these connections. The work in this thesis comes from three published papers:

  - <a href="/publication/cms-20/">The Log-Approximate-Rank Conjecture Is False</a>, with Arkadev Chattopadhyay and Nikhil S. Mande: There are numerous neat connections between communication protocols and matrix ranks/norms. We show that certain conjectured connections between randomized communication protocols and approximate rank/matrix norms do not hold.
  
  - <a href="/publication/cgs-20/">Towards Stronger Counterexamples to the Log-Approximate-Rank Conjecture</a>, with Arkadev Chattopadhyay and Ankit Garg: We look at some simple functions arising from a combinatorial structure known as subspace designs. We show evidence that these simple functions are hard to compute. The simplicity of the functions and the conjectured hardness are even more glaringly at odds with each other than in the function presented in the previous work. We put forth a fundamental conjecture about subspaces that would prove the conjectured hardness if true.
  
  - <a href="/publication/gkns-20/">No Quantum Speedup over Gradient Descent for Non-Smooth Convex Optimization</a>, with Ankit Garg, Robin Kothari and Praneeth Netrapalli: Optimization algorithms are often black-box algorithms, looking at the outputs of the functions they are trying to optimize rather than looking at the inner workings of the function. This abstraction of a black-box algorithm is captured by query complexity. The well-known Gradient Descent is a black-box algorithm that is provably optimal for the task of non-smooth convex optimization. Using known techniques in quantum query complexity, we are able to show that Gradient Descent can not be improved upon by a quantum black-box algorithm. This is in contrast to other quantum black-box algorithms such as Grover''s search and Shor''s period finding algorithm which show significant speedups.
  
  
Addenda:

  - Conjecture 7.1 is true! TsunMing Cheung, Hamed Hatami, Kaave Hosseini and Morgan Shirley proved in <a href="https://eccc.weizmann.ac.il/report/2022/165/">Separation of the factorization norm and randomized communication complexity</a> that the $\gamma_2$ norm of the Integer Inner Product function is large despite it being easy to compute using randomized communication. It also turns out to follow from previous results in discrepancy theory.<br><br>

  - Conjecture 7.3 is false! The above-mentioned results in discrepancy theory also extend to an exponential separation between Randomized Parity Decision Trees and the logarithm of the $L_1$ norm, and hence between RPDTs and SubspaceDTs as well. This also provides insight to the approximate $L_1$ norm, showing that this can be far smaller than the exact $L_1$ norm even for a Boolean function. (To be published by the authors of the previous work.) (I also thank Swagato Sanyal for previously pointing out that there was a polynomial separation using the binary NAND tree. [<a href="https://www.math.ias.edu/~avi/PUBLICATIONS/MYPAPERS/SW86/SW86.pdf">Probabilistic boolean decision trees and the complexity of evaluating game trees</a>, Saks and Wigderson ''86 [Example 1.1]].)
  '
publication: 'PhD Thesis'
links:
- name: PDF
  url: /uploads/Suhail_Thesis.pdf
---
