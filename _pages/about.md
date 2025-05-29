---
permalink: /
title: "Nice to meet you! 👋"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Ionuț (pronounced Ionutz) and I am a Ph.D. student working in efficient optimization for Deep Learning at the Institute of 
Science and Technology Austria (ISTA) under the supervision of [Dan Alistarh](https://people.csail.mit.edu/alistarh/). Before starting my 
PhD in October 2021 at ISTA, I worked as a Research Scientist at Amazon. Prior to that, I was an intern at the University of Maryland in 
College Park, USA and worked under the supervision of [Tudor Dumitras](https://users.umiacs.umd.edu/~tudor/).

My main interest is improving the performance of optimization algorithms for Deep Learning, especially Large Language Models (LLMs).
I am especially focused on reducing the memory usage of optimizer states by leveraging compression techniques, such as sparsity, 
low-rank and quantization through numerical linear algebra and CUDA programming when needed.

My primary research focus is on effiient optimization algorithms for Deep Learning, with a particular emphasis on LLMs. I'm especially
interested in reducing the memory footprint of optimizer states by applying compression techniques such as sparsity, low-rank 
approximations, and quantization. To achieve this, I often draw on tools from numerical linear algebra and implement custom solutions with
CUDA programming when performance demands it.

I maintain the [ISTA-DasLab-Optimizers](https://github.com/IST-DASLab/ISTA-DASLab-Optimizers) repository, a GitHub project from our 
[DASLab group](https://github.com/IST-DASLab) at ISTA, containing all optimization algorithms developed in our lab. Feel free to give it 
a try by installing it via `pip install ista-daslab-optimizers`.

I also developed [GridSearcher](https://github.com/IST-DASLab/GridSearcher), a tool designed to replace the bash scripts to launch training
experiments for Deep Learning models. It allows defining the hyper-parameter values for grid search and has the option to run 
distributed or single GPU experiments, while ensuring a basic GPU synchronization. It is available to install via `pip install 
gridsearcher`.