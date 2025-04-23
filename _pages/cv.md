---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Mathematics (Operations Research, Mathematical Programming), [Department of Mathematical Sciences](https://www.math.tsinghua.edu.cn/), [Tsinghua University](https://www.tsinghua.edu.cn/), supervised by [Prof. Wenxun Xing](https://www.genealogy.math.ndsu.nodak.edu/id.php?id=182440), 2019.09 - 2024.01 (Complete the Program Ahead of Schedule)

  Awards: Excellent Doctoral Dissertation of Tsinghua University, Outstanding Graduates of Beijing
* B.S. in Mathematics and Applied Mathematics, [Cuiying Honors College](https://cycollege.lzu.edu.cn/), [Lanzhou University](https://www.lzu.edu.cn/) as part of
China's Top-Notch Undergraduate Training Program, 2015.09 - 2019.06

  Awards: China National Scholarship, Outstanding Graduates

Work Experience
======
* Postdoctoral Fellow, 2024.02 - Now
  * [Department of Applied Mathematics](https://www.polyu.edu.hk/ama/), [The Hong Kong Polytechnic University](https://www.polyu.edu.hk/)
  * supervised by [Prof. Defeng Sun](https://www.polyu.edu.hk/ama/profile/dfsun/)

* Research Assistant, 2024.01 - 2024.02
  * [Department of Applied Mathematics](https://www.polyu.edu.hk/ama/), [The Hong Kong Polytechnic University](https://www.polyu.edu.hk/)
  * visit [Prof. Defeng Sun](https://www.polyu.edu.hk/ama/profile/dfsun/)
  
Research
======
* **Design and analyze proximal (linearized) ADMM, SGA-RMSProp, and regularized Newton’s method
for large-scale problems:**

  * Parallelizable proximal (linearized) ADMM algorithms for training residual neural networks are designed.
Convergence, R-(sub)linear rate, and time complexity are investigated both theoretically and numerically.

  * RMSProp with stable gradient adjustment and mini-batch stochastic gradient (SGA-RMSProp) is
designed. R-linear convergence and the influence of batch size are both theoretically and numerically analyzed.

  * An adaptive quadratic regularized Newton's method is proposed, requiring no prior knowledge of the
Hessian's Lipschitz constant.

* **BP and non-BP training for deep neural networks (DNNs):**

  * Both serial and parallel/distributed proximal (linearized) ADMM algorithms for training residual neural networks
are proposed, mitigating the drawbacks of BP-based training as follows:

    * Effectively mitigate exploding gradient issues
    * Facilitate parallel execution across network layers and significantly reduce computational time
    * Significantly reduce per-node memory requirements during distributed training
   
    Theoretically, both convergence and complexity analyses are presented, and Python's multiprocessing and IPC are
employed to develop a control protocol for parallel implementation.
  * A unified framework is proposed for analyzing the convergence rate of alternating-minimization-based DNN
training algorithms.
  * A stable gradient-adjusted RMSProp (SGA-RMSProp) algorithm incorporating mini-batch stochastic
gradient is proposed. R-linear convergence is established for the linear least squares problem.

* **Semidefinite programming (SDP) relaxation for matrix optimization over uncertain linear system:**

  A polynomial-time solvable SDP approximation model for an NP-hard matrix optimization problem over uncertain
linear system on finite horizon is developed. This method can be used in model predictive control, COVID-19
pandemic optimal control, Markov chains, and multi-stage enterprise input-output model.

* **Global optimization algorithms for complex quadratically constrained quadratic programmings
(CQCQPs):**

  A new SDP-relaxation-based branch-and-bound algorithm for a class of CQCQPs with nonconvex constraints
on modulus and phase difference is proposed. Experiment results show that the algorithm outperforms Gurobi and
existing global algorithm when applied to discrete and virtual beamforming problems.

Skills
======
* Research:
  * Numerical optimization algorithm design: proximal point algorithm (PPA), stochastic gradient descent (SGD), block
coordinate descent (BCD), alternating direction method of multipliers (ADMM)
  * Convergence (rate) analysis and complexity analysis
  * Theoretical analysis for deep neural networks training
  * Semidefinite programming relaxation
  * Global optimization algorithm design: branch-and-bound, cutting plane
* Coding:
  Python, Julia, MATLAB; Gurobi, Mosek, CVX, PyTorch

Honors and Awards
======
Tsinghua Univeristy

* Excellent Doctoral Dissertation of Tsinghua University, 2024.06
* Outstanding Graduates of Beijing, 2024.01
* Alumni of Tsinghua University-Zhaoyi Innovation Scholarship, 2023.12
* Zhao Fangxiong Scholarship, 2023.04
* Friends of Tsinghua University-Zhuji Excellence Scholarship, 2022.12
* Excellent Teaching Assistant Award, 2022.12
* Huiyan Excellence Scholarship, 2021.12
* Mr. Zheng Zongcheng and Mrs. Zheng Xu Cuiping Memorial Scholarship, 2020.07
* Excellent Teaching Assistants (6 times), 2020-2023

Lanzhou University

* Outstanding Graduates, 2018.12
* Excellent Student Models, 2018.12
* China National Scholarship, 2018.11
* Second Prize in the Final of the 9th National College Students Mathematical Competition, 2018.03
* Merit Students of Colleges and Universities in Gansu Province, 2017.12
* First-Class Scholarship for Outstanding Students (2 times), 2016, 2017
* First-Class Scholarship for Research and Innovation, 2017.12
* First Prize in the Gansu Division of the 8th (9th) National College Students, 2016, 2017
* Student Models, 2016.12



Talks
======
* A Matrix Optimization Problem over An Uncertain Linear System and Its Semidefinite Programming Approximations. MOS2023, Chengdu, China. 2023.05
* A Multi-Stage Optimal Control Model for COVID-19. MOS2021. 2021.03
  
Teaching
======

* Modern Method for Optimal Calculation (60420174-0), TA, Tsinghua University,
  Spring 2022, Excellent Teaching Assistant; Spring 2023, Excellent Teaching Assistant

* Algorithm Analysis and Design (70420334-0), TA, Tsinghua University,
Autumn 2022, Excellent Teaching Assistant; Autumn 2023, Excellent Teaching Assistant

* Probability and Stochastic Processes (10421373-1), TA, Tsinghua University, Spring 2021

* Probability and Statistics (10420803), TA, Tsinghua University,
  Autumn 2020, Excellent Teaching Assistant; Spring 2020; Autumn 2021, Excellent Teaching Assistant


