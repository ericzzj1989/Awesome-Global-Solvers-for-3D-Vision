# Global-Optimization-for-Multiple-View-Geometry [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)

## 🏠 About
This repo contains a curative list of **Global Optimization for Multiple View Geometry**. Please feel free to send us [pull requests](https://github.com/ericzzj1989/Global-Optimization-for-Multiple-View-Geometry/blob/main/how-to-PR.md) or [email](mailto:ericzzj89@gmail.com) to add papers! <br>

This is an active repository, you can watch for following the latest advances. If you find this repository useful, please consider [citing](#citation) 📝 and STARing ⭐ this list. Feel free to share this list with others!

---
## 🔥 News

---
## Overview
  - [Theory](#theory)
    - [Bound-and-Branch (BnB)](#bound-and-branch-bnb)
    - [Semidefinite Programming (SDP)](#semidefinite-programming-sdp))
    - [Polynomial Optimization (POP)](#polynomial-optimization-pop)
    - [Graduated Non-Convexity (GNC)](#graduated-non-convexity-gnc)
  - [Application](#application)
    - [Rotation Averaging](#rotation-averaging)
      - [Analysis](#analysis)
      - [SDP](#sdp)
      - [POP](#pop)
      - [RANSAC](#ransac)
      - [GNC](#gnc)
      - [Hybrid](#hybrid)
    - [Translation Averaging](#rotation-averaging)
      - [Essential Matrix](#essential-matrix)
      - [Trifocal Tensor](#trifocal-tensor)
      - [Convex Relaxation](#convex-relaxation)
      - [Robust Estimation](#robust-estimation)
      - [Hybrid](#hybrid)
    - [Wahba Problem](#wahba-problem)
    - [Absolute Pose Estimation (PnP)](#absolute-pose-estimation-pnp)
    - [Relative Pose Estimation](#relative-pose-estimation)
    - [3D Registration](#3d-registration)
    - [Pose Graph Optimization](#pose-graph-optimization)
    - [Triangulation](#triangulation)
    - [Bundle Adjustment](#bundl-adjustment)
    - [SLAM](#slam)
    - [All-in-One](#all-in-one)

---
## Theory

### Bound-and-Branch (BnB)

### Semidefinite Programming (SDP)

### Polynomial Optimization (POP)

### Graduated Non-Convexity (GNC)

---
## Application

### Rotation Averaging

#### **Analysis**
- "Combining two-view constraints for motion estimation", *CVPR, 2001*. [[Paper](https://ieeexplore.ieee.org/document/990963)]

#### **SDP**
- "Global Motion Estimation from Point Matches", *3DIMPVT, 2012*. [[Paper](https://ieeexplore.ieee.org/document/6374980)]  
- "Simultaneous multiple rotation averaging using Lagrangian duality", *ACCV, 2012*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-37431-9_19)]  
- "Rotation Averaging and Strong Duality", *CVPR 2018*. [[Paper](https://ieeexplore.ieee.org/document/8578119)]

#### **POP**
- "Globally optimal estimates for rotation averaging problems", *2014*. [[Paper](https://ieeexplore.ieee.org/document/6911507)]

#### **RANSAC**
- "Hierarchical RANSAC-based rotation averaging", *SPL, 2020*. [[Paper](https://ieeexplore.ieee.org/document/9234640)]  
- "Revisiting rotation averaging: Uncertainties and robust losses", *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2303.05195)] [[Code](https://github.com/zhangganlin/GlobalSfMpy)]

#### **GNC**
- "Pushing the envelope of rotation averaging for visual slam", *arXiv, 2020*. [[Paper](https://arxiv.org/pdf/2011.01163)]  
- "Adaptive annealing for robust averaging", *ECCV 2024*. [[Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08834.pdf)]

#### **Hybrid**
- "Shonan Rotation Averaging: Global Optimality by Surfing SO(p)^n", *ECCV, 2020*. [[Paper](https://arxiv.org/pdf/2008.02737)] [[Code](https://github.com/NeBula-AI/Shonan-Rotation-Averaging)]  
- "Hybrid Rotation Averaging: A Fast and Robust Rotation Averaging Approach", *CVPR, 2021*. [[Paper](https://arxiv.org/pdf/2101.09116)] [[Code](https://github.com/ethz-asl/hybrid-rotation-averaging)]

---

### Translation Averaging

#### **Essential Matrix**
- "Combining two-view constraints for motion estimation", *CVPR, 2001*. [[Paper](https://ieeexplore.ieee.org/document/990963)]

#### **Trifocal Tensor**
- "Global Motion Estimation from Point Matches", *3DIMPVT, 2012*. [[Paper](https://ieeexplore.ieee.org/document/6374980)]  
- "Exploiting Loops in the Graph of Trifocal Tensors for Calibrating a Network of Cameras", *ECCV, 2010*. [[Paper](https://imagine.enpc.fr/~monasse/Callisto/pdf/ECCV10Loop.pdf)]
- "A Global Linear Method for Camera Pose Registration", *ICCV, 2013*. [[Paper](https://openaccess.thecvf.com/content_iccv_2013/papers/Jiang_A_Global_Linear_2013_ICCV_paper.pdf)]  
- "Global Fusion of Relative Motions for Robust, Accurate and Scalable Structure from Motion", *ICCV, 2013*. [[Paper](https://openaccess.thecvf.com/content_iccv_2013/papers/Moulon_Global_Fusion_of_2013_ICCV_paper.pdf)]
- "Recovering Camera Motion Using $l_{\infty}$ Minimization", *CVPR, 2006*.

#### **Convex Relaxation**
- "Robust Camera Location Estimation by Convex Programming", *CVPR, 2015*. [[Paper](https://arxiv.org/pdf/1412.0165)]  
- "Baseline Desensitizing in Translation Averaging (LUD & Shapefit)", *CVPR, 2018*. [[Paper](https://arxiv.org/pdf/1901.00643)]

#### **Robust Estimation**
- "1DSfM: Robust Global Translations with 1DSfM", *ECCV, 2014*. [[Paper](https://www.cs.cornell.edu/projects/1dsfm/)]

#### **Hybrid**
- "Correspondence Reweighted Translation Averaging", *ECCV 2022*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-19827-4_4)] [[Code](https://github.com/zju3dv/crta)]  
- "Linear Global Translation Estimation with Feature Tracks", *CVPR, 2015*. [[Paper](https://arxiv.org/pdf/1503.01832)]

---


### Wahba Problem

#### **Closed-form**
- "Fundamentals of spacecraft attitude determination and control".  
- "Closed-form solution of absolute orientation using orthonormal matrices".  
- "Attitude determination using vector observations and the singular value decomposition".  
- "Least-squares fitting of two 3D point sets".  
- "A generalized solution of the orthogonal procrustes problem".  
- "Closed-form solution of absolute orientation using orthonormal matrices".

#### **BnB**
- "Global optimization through rotation space search", *IJCV, 2009*. [[Paper](https://users.cecs.anu.edu.au/~hartley/Papers/PDF/HartleyKahl:Ematrix.pdf)]  
- "Globally optimal consensus set maximization through rotation search", *ACCV, 2012*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-37444-9_42)]  
- "A polynomial-time bound for matching and registration with outliers", *CVPR, 2008*. [[Paper](https://ieeexplore.ieee.org/document/4587757)]  
- "Robust fitting for multiple view geometry", *ECCV, 2012*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-33718-5_53)]

#### **Convex Relaxation**
- "A semidefinite relaxation-based algorithm for robust attitude estimation", *TSP, 2012*. [[Paper](https://ieeexplore.ieee.org/document/6203426)]  
- "A Quaternion-based Certifiably Optimal Solution to the Wahba Problem with Outliers", *ICCV 2019*. [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Yang_A_Quaternion-Based_Certifiably_Optimal_Solution_to_the_Wahba_Problem_With_ICCV_2019_paper.pdf)] [[Code](https://github.com/MIT-SPARK/TEASER-plusplus)]  
- "Semidefinite relaxations of truncated least-squares in robust rotation search: Tight or not", *ECCV, 2022*. [[Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136830655.pdf)]  
- "Optimal pose and shape estimation for category-level 3D object perception", *RSS, 2021*. [[Paper](https://arxiv.org/pdf/2104.08383)] [[Code](https://github.com/mit-spark/pace)]

#### **POP**
*(后续补充)*

#### **RANSAC**
- "RANSIC: Fast and Highly Robust Estimation for Rotation Search and Point Cloud Registration Using Invariant Compatibility", *RAL, 2021*. [[Paper](https://arxiv.org/pdf/2104.09133)] [[Code](https://github.com/lukascher/RANSIC)]

#### **GNC**
- "A fast fractional programming technique for Geman-McClure robust estimator", *RAL, 2024*. [[Paper](https://arxiv.org/pdf/2409.13978)] [[Code](https://github.com/StephLin/FracGM)]


### Absolute Pose Estimation (PnP)

#### Analysis
- EPnP 
- The non-tightness of a convex relaxation to rotation recovery | 2021 | [paper](https://www.mdpi.com/1424-8220/21/21/7358) | – |
- CvxPnPL: A unified convex solution to the absolute pose estimation problem from point and line correspondences
- Upnp: An optimal o (n) solution to the absolute pose problem with universal applicability
- Revisiting the pnp problem: A fast, general and optimal solution
- Globally optimal dls method for pnp problem with cayley parameterization
- A versatile approach for solving pnp, pnpf, and pnpfr problems
- A simple, robust and fast method for the perspective-n-point problem
- An efficient and accurate algorithm for the perspecitve-n-point problem
- A consistently fast and globally optimal solution to the perspective-n-point problem
- Globally optimal O(n) solution to the PnP problem for general camera models


### Relative Pose Estimation

#### Minimal solvers
- An efficient solution to the five-point relative pose problem(2004)
- Recent developments on direct relative orientation(2006)
- Finding the exact rotation between two images independently of the translation(ECCV,2012)
- In defence of the 8-point algorithm(ICCV,1995)

#### Global Optimization

👇**SDP**
- Camera displacement via constrained minimizatio of the algebraic error(TPAMI,2009)
- Finding the exact rotation between two images independently of the translation(ECCV,2012)
- A certifiably globally optimal solution to the non-minimal relative pose problem(CVPR,2018)
- SDP relaxations for quadratic optimization problems derived from polynomial optimization problems(2010)
- Globally optimal estimates for geometric reconstruction problems(2007)
- Certifiably optimal rotation and pose estimation based on the cayley map(2025)
- Robot-to-Robot Relative Pose Estimation based on Semidefinite Relaxation Optimization(2020)

👇**BnB**
- Robust optimal pose estimation(ECCV,2008)
- Two view geometry estimation with outliers(BMVC,2009)
- Consensus set maximization with guaranteed global optimality for robust geometry estimation(ICCV,2009)
- Optimal essential matrix estimation via inlier-set maximization(ECCV,2014)
- Optimal relative pose with unknown correspondences(CVPR,2016)
- Direct optimization of frame-to-frame rotation(ICCV,2013)
- Global optimization through rotation space search(IJCV,2009)
- Certifiable relative pose estimation(2021)
  
👇**Hybrid**
- Consensus maximization with linear matrix inequality constraints(CVPR,2017)
#### RANSAC
- An efficient solution to the five-point relative pose problem(TPAMI,2004)
- Fast and robust certifiable estimation of the relative pose between two calibrated cameras(2021)


### 3D Registration

- Point Registration via Efficient Convex Relaxation (TOG,2016)
- Fast Global Registration (ECCV,2016)

- SDRSAC: Semidefinite-Based Randomized Approach for Robust Point Cloud Registration without Correspondences (2019,CVPR)
- TEASER: Fast and Certifiable Point Cloud Registration (TRO,2020)

#### BnB
- A polynomial-time bound for matching and registration with outliers(CVPR,2008)
- Go-icp: A globally optimal solution to 3d icp point-set registration(TPAMI,2015)
- GORE:
- PMC:A practical maximum clique algorithm for matching with pairwise constraints
#### SDP
- Guided search consensus: Large scale point cloud registration by convex optimization(2013)
- on-iterative rigid 2d/3d pointset registration using semidefinite programming(TIP,2015)
- Point registration via efficient convex relaxation(2016)
- Convex Global 3D Registration with Lagrangian Duality (CVPR,2017)
| Convex Global 3D Registration with Lagrangian Duality | CVPR 2017 | [paper](https://ieeexplore.ieee.org/document/8100078) | – |
#### GNC
- Practical, fast and robust point cloud registration for 3d scene stitching and object localization(2021)
- Pyramid semantic graph-based global point cloud registration with low overlap(IROS,2023)


### Pose Graph Optimization

#### SDP
- Lagrangian Duality in Complex Pose Graph Optimization(2016)
- Initialization of 3D Pose Graph Optimization Using Lagrangian Duality(ICRA,2017)
- Convex Relaxations for Pose Graph Optimization With Outliers(RAL,2018)
- Efficient and Guaranteed Planar Pose Graph Optimization Using Complex Representation(2019)
- Distributed Certifiably Correct Pose-Graph Optimization(TRO,2019)

#### GNC
- Efficient Graduated Non-Convexity for Pose Graph Optimization(ICCAS,2024)
- Adaptive Graduated Non-Convexity for Pose Graph Optimization(arxiv,2023)
- A Decoupled and Linear Framework for Global Outlier Rejection over Planar Pose Graph(ICRA,2023)
- Improving Pose Graph Optimization via Efficient Graduated Non-convexity Scheduling


### Triangulation

#### SDP
- A qcqp approach to triangulation(ECCV,2012)
- Semidefinite Relaxations for Robust Multiview Triangulation (CVPR,2023)
- Triangulation of points, lines and conics(JMIV,2007)
- A convex relaxation to compute the nearest structured rank deficient matrix(SIAM,2021)
  
#### BnB
- A Fast Optimal Algorithm for L 2 Triangulation(2007)
- On triangulation algorithms in large scale camera network systems(ACC,2012)
- An exact algorithm for the minimum dilation triangulation problem(2017)
  
#### RANSAC
- Robust multiview L2 triangulation via optimal inlier selection and 3D structure refinement
- Robust uncertainty-aware multiview triangulation
- Structure-from-motion revisited

#### Hybrid
- A Triangulation Method Based on minmaxKKT(2012)


### Bundle Adjustment
- Building Rome with Convex Optimization (RSS,2025)


### SLAM
- [Certifiably Correct Range-Aided SLAM](https://arxiv.org/pdf/2302.11614) (TRO,2024)
- [Distributed Certifiably Correct Range-Aided SLAM](https://arxiv.org/pdf/2503.03192) (ICRA,2025)

### All-in-One
- One Ring to Rule Them All: Certifiably Robust Geometric Perception with Outliers (NeurIPS,2020)
- Certifiably Optimal Outlier-Robust Geometric Perception: Semidefinite Relaxations and Scalable Global Optimization (TPAMI,2022)
