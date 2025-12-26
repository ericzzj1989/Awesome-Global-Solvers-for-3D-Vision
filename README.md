# :sunglasses: Awesome Global Optimization for Geometric Vision
[![GitHub](https://img.shields.io/github/stars/ericzzj1989/Global-Optimization-for-Multiple-View-Geometry?style=social)](https://github.com/ericzzj1989/Global-Optimization-for-Multiple-View-Geometry)
![visitors](https://visitor-badge.laobi.icu/badge?page_id=mayuelala.Awesome-Global-Optimization-for-Multiple-View-Geometry&left_color=green&right_color=red)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)


## 🏠 Introduction
This repository contains a curative list of papers on **Global Optimization for Multiple View Geometry**. Please feel free to send us [pull requests](https://github.com/ericzzj1989/Global-Optimization-for-Multiple-View-Geometry/blob/main/how-to-PR.md) or [email](mailto:ericzzj89@gmail.com) to add papers! <br>

This is an active repository, you can watch for following the latest advances. If you find this repository useful, please consider [citing](#citation) 📝 and STARing ⭐ this list. Feel free to share this list with others!

---
## 🔥 News

---
## Table of Contents
  - [**Theory**](#theory)
    - [Branch-and-Bound (BnB)](#branch-and-bound-bnb)
    - [Semidefinite Programming (SDP)](#semidefinite-programming-sdp)
    - [Polynomial Optimization (POP)](#polynomial-optimization-pop)
    - [Consensus Maximization (CM)](#consensus-maximization-cm)
    - [Graduated Non-Convexity (GNC)](#graduated-non-convexity-gnc)
    - [Adaptive Trimming (ADAPT)](#adaptive-trimming-adapt)
- [**Application**](#application)
    - [Rotation Averaging](#rotation-averaging)
    - [Translation Averaging](#translation-averaging)
    - [Wahba Problem](#wahba-problem)
    - [Absolute Pose Estimation (PnP)](#absolute-pose-estimation-pnp)
    - [Relative Pose Estimation](#relative-pose-estimation)
    - [3D Registration](#3d-registration)
    - [Pose Graph Optimization](#pose-graph-optimization)
    - [Triangulation](#triangulation)
    - [Vanishing Point Estimation](#vanishing-point-estimation)
    - [Bundle Adjustment](#bundle-adjustment)
    - [All-in-One](#all-in-one)
- [**Other Resources**](#other-resources)
    - [Workshops](#workshops)
    - [Tutorials](#tutorials)
    - [Lectures](#lectures)
    - [Talks \& Seminars](#talks--seminars)


---
## Theory

### Branch-and-Bound (BnB)

- An Automatic Method of Solving Discrete Programming Problems, *Econometrica, 1960*. [[Paper](https://jmvidal.cse.sc.edu/library/land60a.pdf)]

- Branch-and-Bound Methods: A Survey, *Operations research, 1966*. [[Paper](https://pubsonline.informs.org/doi/abs/10.1287/opre.14.4.699)]

- Branch and Bound Algorithms-Principles and Examples, *1999*. [[Paper](https://janders.eecg.toronto.edu/1387/readings/b_and_b.pdf)]

- Branch-and-Bound Algorithms: A Survey of Recent Advances in Searching, Branching, and Pruning, *Discrete Optimization, 2016*. [[Paper](https://www.sciencedirect.com/science/article/pii/S1572528616000062)]

### Semidefinite Programming (SDP)

- Semidefinite Programming Relaxations of Nonconvex Quadratic Optimization, *Handbook of Semidefinite Programming, 2000*. [[Paper](https://www.math.uwaterloo.ca/~hwolkowi/henry/reports/chapqqps.pdf)]

- A Nonlinear Programming Algorithm for Solving Semidefinite Programs via Low-rank Factorization, *Mathematical Programming, 2003*. [[Paper](https://sburer.github.io/papers/007-lowrank.pdf)]

- Exploiting Sparsity in Semidefinite Programming via Matrix Completion I: General Framework, *SIAM Journal on Optimization, 2006*. [[Paper](https://pages.cs.wisc.edu/~nathanae/nonlinproj/fukada.pdf)]

- Semidefinite Relaxation of Quadratic Optimization Problems, *Signal Processing Magazine, 2010*. [[Paper](https://www1.se.cuhk.edu.hk/~manchoso/papers/sdrapp-SPM.pdf)]

- On Convex Relaxations for Quadratically Constrained Quadratic Programming, *Mathematical Programming, 2012*. [[Paper](https://optimization-online.org/wp-content/uploads/2010/08/2699.pdf)]

- SDPNAL+: A Majorized Semismooth Newton-CG Augmented Lagrangian Method for Semidefinite Programming with Nonnegative Constraints, *Mathematical Programming Computation, 2015*. [[Paper](https://arxiv.org/pdf/1406.0942)]

- The Non-Convex Burer-Monteiro Approach Works on Smooth Semidefinite Programs, *NeurIPS, 2016*. [[Paper](https://arxiv.org/pdf/1606.04970)]

- Random Laplacian Matrices and Convex Relaxations, *Foundations of Computational Mathematics, 2018*. [[Paper](https://arxiv.org/pdf/1504.03987)]

- Block-Coordinate Minimization for Large SDPs with Block-Diagonal Constraints, *arXiv, 2019*. [[Paper](https://arxiv.org/pdf/1903.00597)]

- Scalable Low-Rank Semidefinite Programming for Certifiably Correct Machine Perception, *WAFR, 2020*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-66723-8_33)]

- On the Local Stability of Semidefinite Relaxations, *Mathematical Programming, 2022*. [[Paper](https://arxiv.org/pdf/1710.04287)]

- Accelerating Certifiable Estimation with Preconditioned Eigensolvers, *RAL, 2022*. [[Paper](https://arxiv.org/pdf/2207.05257)]

- An Overview of the Burer-Monteiro Method for Certifiable Robot Perception, *RSS Workshop, 2024*. [[Paper](https://arxiv.org/pdf/2410.00117)]

- Toward Globally Optimal State Estimation Using Automatically Tightened Semidefinite Relaxations, *TRO, 2024*. [[Paper](https://arxiv.org/pdf/2308.05783)] [[Code](https://github.com/utiasASRL/constraint_learning)]

- Exploiting Chordal Sparsity for Fast Global Optimality with Application to Localization, *WAFR, 2024*. [[Paper](https://arxiv.org/pdf/2406.02365)]

- Fast, Scalable, Warm-Start Semidefinite Programming with Spectral Bundling and Sketching, *ICML, 2024*. [[Paper](https://arxiv.org/pdf/2312.11801)] [[Code](https://github.com/rangell/usbs)]

### Polynomial Optimization (POP)

- Global Optimization with Polynomials and the Problem of Moments, *SIAM Journal on Optimization, 2001*. [[Paper](https://www.researchgate.net/profile/Jean-Bernard-Lasserre/publication/2616595_Global_Optimization_With_Polynomials_And_The_Problem_Of_Moments/links/00b4951a5d937799ce000000/Global-Optimization-With-Polynomials-And-The-Problem-Of-Moments.pdf?origin=publicationDetail&_sg%5B0%5D=Xyl38RCrtJ0aF_kzChsHwdtFj8QBm0yfZVzP71GtkN8FZH415jgfha6L8cJnnhjiCjNDbhUMXkKcVUWHBu7GYg.M0Ma7_6QSgTIehOOwu3f2m5Xcf8A2_GwygeG8yxPrGcm_QIrNT8wDeBLoq4WGwckjoj3baN0OM4tRpf-HJT8IA&_sg%5B1%5D=fC2q7sMrsxepcN2mX_4buByuH8NH1LOWFTCwBBmwvbz9LjZYYpSKO3fd3jLo9ORY5PLtAt3V7LLjg5XBh-fvyatbJLMHnEJz2XGgMoiQ3u7t.M0Ma7_6QSgTIehOOwu3f2m5Xcf8A2_GwygeG8yxPrGcm_QIrNT8wDeBLoq4WGwckjoj3baN0OM4tRpf-HJT8IA&_iepl=&_rtd=eyJjb250ZW50SW50ZW50IjoibWFpbkl0ZW0ifQ%3D%3D&_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InB1YmxpY2F0aW9uIiwicG9zaXRpb24iOiJwYWdlSGVhZGVyIn19)]

- Semidefinite Programming Relaxations for Semialgebraic Problems, *Mathematical Programming, 2003*. [[Paper](https://www.mit.edu/~parrilo/pubs/files/SDPrelaxations.pdf)]

- Convergent SDP‐Relaxations in Polynomial Optimization with Sparsity, *SIAM Journal on Optimization, 2006*. [[Paper](https://www.researchgate.net/profile/Jean-Bernard-Lasserre/publication/221333756_Convergent_SDP-Relaxations_in_Polynomial_Optimization_with_Sparsity/links/00b4951a3bedde534e000000/Convergent-SDP-Relaxations-in-Polynomial-Optimization-with-Sparsity.pdf)]

- Sums of Squares, Moment Matrices and Optimization Over Polynomials, *Emerging Applications of Algebraic Geometry, 2008*. [[Paper](https://homepages.cwi.nl/~monique/files/moment-ima-update-new.pdf)]

- Optimality Conditions and Finite Convergence of Lasserre's Hierarchy, *Mathematical programming, 2014*. [[Paper](https://arxiv.org/pdf/1206.0319)]

- Convergence of Lasserre’s hierarchy: the general case, *OL, 2022*. [[Paper](https://arxiv.org/pdf/2011.08139)]

- Finding Global Minima via Kernel Approximations, *Mathematical Programming, 2025*. [[Paper](https://arxiv.org/pdf/2012.11978)]

### Consensus Maximization (CM)

- Efficient Globally Optimal Consensus Maximisation with Tree Search, *2015, CVPR*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2015/papers/Chin_Efficient_Globally_Optimal_2015_CVPR_paper.pdf)]

- Robust Fitting in Computer Vision: Easy or Hard?, *ECCV, 2018*. [[Paper](https://arxiv.org/pdf/1802.06464)]

- Deterministic Consensus Maximization with Biconvex Programming, *ECCV, 2018*. [[Paper](https://arxiv.org/pdf/1807.09436)] [[Code](https://github.com/ZhipengCai/Demo---Deterministic-consensus-maximization-with-biconvex-programming)]

- Consensus Maximization Tree Search Revisited, *2019, ICCV*. [[Paper](https://arxiv.org/pdf/1908.02021)] [[Code](https://github.com/ZhipengCai/MaxConTreeSearch)]

- Deterministic Approximate Methods for Maximum Consensus Robust Fitting, *2019, TPAMI*. [[Paper](https://arxiv.org/pdf/1710.10003)]

- Efficient Algorithms for Maximum Consensus Robust Fitting, *TRO, 2019*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8870243&casa_token=-j8fL-PdwLQAAAAA:w00l-vjtIGldKkgRjz29_jRUhlF3okPnkCMRevOhIyqBkROp2j4wK49DGOT3QQpiPLHF4wzcAzI)]

### Graduated Non-Convexity (GNC)

- On the Unification Line Processes, Outlier Rejection, and Robust Statistics with Applications in Early Vision, *IJCV, 1996*. [[Paper](https://www.cise.ufl.edu/~anand/pdf/ijcv.pdf)]

- On the Link between Gaussian Homotopy Continuation and Convex Envelopes, *CVPRW, 2015*. [[Paper](https://people.csail.mit.edu/hmobahi/pubs/gaussian_convenv_2015.pdf)]

- Graduated Non-Convexity for Robust Spatial Perception: From Non-Minimal Solvers to Global Outlier Rejection, *RAL, 2020*. [[Paper](https://arxiv.org/pdf/1909.08605)] [[Code](https://github.com/MIT-SPARK/GNC-and-ADAPT)]

- Adaptive Annealing for Robust Geometric Estimation, *CVPR, 2023*. [[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Sidhartha_Adaptive_Annealing_for_Robust_Geometric_Estimation_CVPR_2023_paper.pdf)]

- Adaptive Annealing for Robust Averaging, *ECCV, 2024*. [[Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08834.pdf)]

### Adaptive Trimming (ADAPT)

- Outlier-Robust Spatial Perception: Hardness, General-Purpose Algorithms, and Guarantees, *IROS, 2019*. [[Paper](https://arxiv.org/pdf/1903.11683)]

- Outlier-Robust Estimation: Hardness, Minimally Tuned Algorithms, and Applications, *TRO, 2021*. [[Pape](https://arxiv.org/pdf/2007.15109)] [[Code](https://github.com/MIT-SPARK/GNC-and-ADAPT)]

---

## Application

### Rotation Averaging

#### **SDP for Rotation Averaging**

- Angular Synchronization by Eigenvectors and Semidefinite Programming, *Applied and Computational Harmonic Analysis, 2011*. [[Paper](https://arxiv.org/pdf/0905.3174)]

- Global Motion Estimation from Point Matches, *3DIMPVT, 2012*. [[Paper](https://homes.cs.washington.edu/~kemelmi/sfm_3dimpvt12.pdf)]
  
- Simultaneous Multiple Rotation Averaging Using Lagrangian Duality, *ACCV, 2012*. [[Paper](https://scispace.com/pdf/simultaneous-multiple-rotation-averaging-using-lagrangian-1ecpzvpaw8.pdf)]

- Tightness of the Maximum Likelihood Semidefinite Relaxation for Angular Synchronization, *Mathematical Programming, 2017*. [[Paper](https://arxiv.org/pdf/1411.3272)]

- Near-Optimal Bounds for Phase Synchronization, *SIAM Journal on Optimization, 2018*. [[Paper](https://arxiv.org/pdf/1703.06605)]

- Rotation Averaging and Strong Duality, *CVPR, 2018*. [[Paper](https://arxiv.org/pdf/1705.01362)]

- Rotation Averaging with the Chordal Distance: Global Minimizers and Strong Duality, *TPAMI, 2019*. [[Paper](https://ieeexplore.ieee.org/document/8770111)]

- Rotation Coordinate Descent for Fast Globally Optimal Rotation Averaging, *CVPR, 2021*. [[Paper](https://arxiv.org/pdf/2103.08292)] [[Code](https://github.com/sfchng/Rotation_Coordinate_Descent)]

- Rotation Averaging in a Split Second: A Primal-Dual Method and a Closed-Form for Cycle Graphs, *ICCV, 2021*. [[Paper](https://arxiv.org/pdf/2109.08046)] [[Code](https://github.com/gabmoreira/maks)]

- Rotation Averaging: A Primal-Dual Method and Closed-Forms in Cycle Graphs, *arXiv, 2024*. [[Paper](https://arxiv.org/pdf/2406.18564)] [[Code](https://github.com/gabmoreira/maks)]

- Certifiably Optimal Anisotropic Rotation Averaging, *ICCV, 2025*. [[Paper](https://arxiv.org/pdf/2503.07353)] [[Code](https://github.com/ylochman/anisotropic-ra)] [[Project Page](https://ylochman.github.io/anisotropic-ra)]

#### **POP for Rotation Averaging**

- Globally Optimal Estimates for Rotation Averaging Problems, *IHMSC, 2014*. [[Paper](https://ieeexplore.ieee.org/document/6911507)]

#### **Others**

- Rotation Averaging and Weak Convexity, *International Symposium on Mathematical Theory of Networks and Systems, 2010*. [[Paper](https://trumpf.id.au/pubs/hartley_trumpf_dai_MTNS2010.pdf)]

- Exact and Stable Recovery of Rotations for Robust Synchronization, *Information and Inference: A Journal of the IMA, 2013*. [[Paper](https://arxiv.org/pdf/1211.2441)]

- Semidefinite Relaxations for Optimization Problems over Rotation Matrices, *CDC, 2014*. [[Paper](https://ecse.monash.edu/staff/james/rotationfiles/SPW_rot.pdf)]

- Global Robust Image Rotation from Combined Weighted Averaging, *JPRS, 2017*. [[Paper](https://ris.utwente.nl/ws/portalfiles/portal/30048921/Reich2017global.pdf)]

- Robust Group Synchronization via Quadratic Programming, *ICML, 2022*. [[Paper](https://arxiv.org/pdf/2206.08994)] [[Code](https://github.com/ColeWyeth/DESC)]

#### **Hybrid for Rotation Averaging**

- Shonan Rotation Averaging: Global Optimality by Surfing $SO(p)^n$, *ECCV, 2020*. [[Paper](https://arxiv.org/pdf/2008.02737)] [[Code](https://github.com/dellaert/ShonanAveraging)] [[Project Page](https://dellaert.github.io/ShonanAveraging/index.html)]

- Hybrid Rotation Averaging: A Fast and Robust Rotation Averaging Approach, *CVPR, 2021*. [[Paper](https://arxiv.org/pdf/2101.09116)] [[Code](https://github.com/ethz-asl/hybrid-rotation-averaging)]

##

### Translation Averaging

#### **SDP for Translation Averaging**

- Stable Camera Motion Estimation Using Convex Programming, *SIAM Journal on Imaging Sciences, 2015*. [[Paper](https://arxiv.org/pdf/1312.5047)]

#### **Others**

- Recovering Camera Motion Using $l_{\infty}$ Minimization, *CVPR, 2006*. [[Paper](https://ieeexplore.ieee.org/document/1640890)]

- Global Fusion of Relative Motions for Robust, Accurate and Scalable Structure from Motion, *ICCV, 2013*. [[Paper](https://openaccess.thecvf.com/content_iccv_2013/papers/Moulon_Global_Fusion_of_2013_ICCV_paper.pdf)]
 
- Robust Camera Location Estimation by Convex Programming, *CVPR, 2015*. [[Paper](https://arxiv.org/pdf/1412.0165)]

- ShapeFit and ShapeKick for Robust, Scalable Structure from Motion, *ECCV, 2016*. [[Paper](https://arxiv.org/pdf/1608.02165)]

- Baseline Desensitizing in Translation Averaging, *CVPR, 2018*. [[Paper](https://arxiv.org/pdf/1901.00643)]

#### **Translation Averaging with Structure (a.k.a. Known Rotations)**

- L1-Penalized Robust Estimation for a Class of Inverse Problems Arising in Multiview Geometry, *NeurIPS, 2009*. [[Paper](https://proceedings.neurips.cc/paper_files/paper/2009/file/65ded5353c5ee48d0b7d48c591b8f430-Paper.pdf)]

- Efficient Outlier Removal in Large Scale Global Structure-from-Motion, *arXiv, 2018*. [[Paper](https://arxiv.org/pdf/1808.03041)]

## 

### Wahba Problem

#### **BnB for Wahba Problem**

- Globally Optimal Consensus Set Maximization through Rotation Search, *ACCV, 2012*. [[Paper](https://d1wqtxts1xzle7.cloudfront.net/84933662/ACCV_2012-libre.pdf?1650946221=&response-content-disposition=inline%3B+filename%3DGlobally_Optimal_Consensus_Set_Maximizat.pdf&Expires=1756227652&Signature=ZZGpssYvDyhCYzfOtcqNvEITWH8b8j5D0JWCDeQaY4q5Cpxq50eDeG9xUt4XoC81UbxK6pAjlqDJV42DPYG--B8N0to9gt5hTpMoo~tseiCQFSq5T7~3LahwAloskJxJFMft~jYOeNPpVc6B9VryXp7eiVdfKs2rNn44AngbaFf-iHcpeSNWp3eZsLymzpMYj-OyRIEdBv0Y3ri9MLTXUCVud8fBj4OXSqTTBJOW7okYbIwVtVATC8U4KIQIJeyAEEOuIPzgfX0KSaePr-XyrAqGfDiAb882nbe2-GoVGvbiI2CkvSBXxEFtJt-a~APoVfcfJ4h09ANzoGPs9sYD4g__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)]

- Fast Rotation Search with Stereographic Projections for 3D Registration, *CVPR, 2014*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2014/papers/Bustos_Fast_Rotation_Search_2014_CVPR_paper.pdf)]

- Fast Rotation Search with Stereographic Projections for 3D Registration, *TPAMI, 2016*. [[Paper](https://ieeexplore.ieee.org/document/7381673)]

#### **SDP for Wahba Problem**

- Semidefinite Relaxation of a Robust Static Attitude Determination Problem, *CDC, 2011*. [[Paper](https://skoge.folk.ntnu.no/prost/proceedings/cdc-ecc-2011/data/papers/0926.pdf)]

- A Semidefinite Relaxation-Based Algorithm for Robust Attitude Estimation, *TSP, 2012*. [[Paper](https://spiral.imperial.ac.uk/server/api/core/bitstreams/69456b59-58b5-470a-9352-22321a0b02f4/content)]

- Point Registration via Efficient Convex Relaxation, *TOG, 2016*. [[Paper](https://haggaim.github.io/projects/point_registration/PMSDP_final_light.pdf)] [[Code](https://github.com/Haggaim/PM-SDP)]

- Exact Recovery with Symmetries for Procrustes Matching, *SIAM Journal on Optimization, 2017*. [[Paper](https://arxiv.org/pdf/1606.01548)]

- A Quaternion-based Certifiably Optimal Solution to the Wahba Problem with Outliers, *ICCV, 2019*. [[Paper](https://arxiv.org/pdf/1905.12536)]

- Near-Optimal Bounds for Generalized Orthogonal Procrustes Problem via Generalized Power Method, *arXiv, 2021*. [[Paper](https://arxiv.org/pdf/2112.13725)]

- Semidefinite Relaxations of Truncated Least-Squares in Robust Rotation Search: Tight or Not, *ECCV, 2022*. [[Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136830655.pdf)]

- Towards Understanding The Semidefinite Relaxations of Truncated Least-Squares in Robust Rotation Search, *arXiv, 2022*. [[Paper](https://arxiv.org/pdf/2207.08350)]

#### **Others**

- Semidefinite Descriptions of the Convex Hull of Rotation Matrices, *arXiv, 2014*. [[Paper](https://arxiv.org/pdf/1403.4914)]

- Linear-Matrix-Inequality-Based Solution to Wahba’s Problem, *Journal of Guidance, Control, and Dynamics, 2015*. [[Paper](https://deepblue.lib.umich.edu/bitstream/handle/2027.42/140644/1.g000132.pdf?sequence=1)]

#### **Robust Improvement**

- Guaranteed Outlier Removal for Rotation Search, *ICCV, 2015*. [[Paper](https://openaccess.thecvf.com/content_iccv_2015/papers/Bustos_Guaranteed_Outlier_Removal_ICCV_2015_paper.pdf)]

- ARCS: Accurate Rotation and Correspondence Search, *CVPR, 2022*. [[Paper](https://arxiv.org/pdf/2203.14493)] [[Code](https://github.com/liangzu/ARCS)]

##

### Absolute Pose Estimation (PnP)

#### **BnB**

- Optimal Estimation of Perspective Camera Pose, *ICPR, 2006*. [[Paper](https://ieeexplore.ieee.org/document/1699135)]

- Robust Optimal Pose Estimation, *ECCV, 2008*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-540-88682-2_12)]

- Linear Relaxation for Global Pose Estimation, *WCICA, 2010*. [[Paper](https://ieeexplore.ieee.org/document/5554370)]

- Globally Optimal 2D-3D Registration from Points or Lines Without Correspondences, *ICCV, 2015*. [[Paper](https://openaccess.thecvf.com/content_iccv_2015/papers/Brown_Globally_Optimal_2D-3D_ICCV_2015_paper.pdf)]

- Globally-Optimal Inlier Set Maximisation for Simultaneous Camera Pose and Feature Correspondence, *ICCV, 2017*. [[Paper](https://arxiv.org/pdf/1709.09384)]

- Globally-Optimal Inlier Set Maximisation for Camera Pose and Correspondence Estimation, *TPAMI, 2018*. [[Paper](https://ieeexplore.ieee.org/document/8388302)]

- 2D-3D Point Set Registration Based on Global Rotation Search, *TIP, 2018*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8579206)]

- The Alignment of the Spheres: Globally-Optimal Spherical Mixture Alignment for Camera Pose Estimation, *CVPR, 2019*. [[Paper](https://arxiv.org/pdf/1812.01232)]

- A Family of Globally Optimal Branch-and-Bound Algorithms for 2D-3D Correspondence-Free Registration, *PR, 2019*. [[Paper](https://www.sciencedirect.com/science/article/pii/S0031320319301426)]

- A Novel Method for the Absolute Pose Problem with Pairwise Constraints, *Remote Sensing, 2019*. [[Paper](https://arxiv.org/pdf/1903.10175)]

- Globally Optimal Camera Orientation Estimation from Line Correspondences by BnB algorithm, *RAL, 2020*. [[Paper](https://mediatum.ub.tum.de/doc/1578987/d940lkg94pulffrppfh5kvequ.Globally_Optimal_Camera_Orientation_Estimation_from_Line_Correspondences_by_BnB_algorithm.pdf)]

- Efficient and Outlier-Robust Simultaneous Pose and Correspondence Determination by Branch-and-Bound and Transformation Decomposition, *TPAMI, 2021*. [[Paper](https://ieeexplore.ieee.org/document/9485090)]

- Absolute Pose Estimation With a Known Direction by Motion Decoupling, *TCSVT, 2023*. [[Paper](https://ieeexplore.ieee.org/document/10093787)] [[Code](https://github.com/Liu-Yinlong/algorithm-for-PnP-with-known-vertical-direction)]

- Efficient and Globally Optimal Camera Orientation Estimation With Line Correspondences, *RAL, 2024*. [[Paper](https://ieeexplore.ieee.org/document/10702548)] [[Code](https://github.com/tyhuang98/EGO_PnL)]

- BnB-Based Robust PnP Pose Estimation Method for Outliers, *RAL, 2025*. [[Paper](https://ieeexplore.ieee.org/document/11011668)]

#### **SDR**

- Optimal Non-Iterative Pose Estimation via Convex Relaxation, *Image and Vision Computing, 2010*. [[Paper](https://pdf.sciencedirectassets.com/271526/1-s2.0-S0262885610X00099/1-s2.0-S0262885610000442/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEIv%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJGMEQCICRH2lxYhMsZDcttsfTScodS4H%2BEitLwOSj%2B1CNCg0DeAiBAAsR8%2F%2F39bE27HY04Y1KpJkZ1WWvZSvZ%2BBrnaO03xoCqzBQg0EAUaDDA1OTAwMzU0Njg2NSIMd6VyY%2BeGsdVTM%2F1aKpAF%2BRN2tJai1WBGR75POrMZpfZuCAmoAxp3S19sumKaUJUXfdCfROvFiDh7NCd2iCMDtI5ujfjA2is%2BC0oaYAueh5ZY29cXedOGqV5zJV3EVzcqKhyn1xIGUkZsLHUcHA8xb%2FMNSMpp393kiYC%2FmrCGLQDdz%2F9nCAavpeGwAwjfp51g6fS0%2FtniEP%2FhphBh5nAlIjiYwqqPM3blXZt4h8CfxbNIUzaO8OqTrbc1LXYvsdQuO5BhAS%2FOfMUC0eauC%2FUHub7Zy0hmS83idrEzDsP34NPwmJhcFadum4KqltKSfUiU75%2BxQ14JTyRpsRn6MQto5qT18fSJY3BKuE3wE2fvRKhhegLWLe6k1owTvBloAa2SKLuTpvQLil6lVUvbD%2BMEXhFmoS%2Bd4suGRl7%2F%2BJzTrjVEpbaaf4Ydv%2FTfaivZkHKGCRVZNtPEAWNjLblx8Z6QBZQWqNZR7dKftcXFCx35wV%2BnB3RCz%2Bj2Hq1x5qopqY%2BIjzV2X0T93YTtST7mbQ3qQXKQOkMpn9xVUfRfgPm9F8%2Fqbvm8qctmKk1WYYyEMzV3DqaZGazDG%2FBqm4y4e790QvP%2FYvEB%2BnqXLbPZLGe6HGKlZQqakULWPaIXIIakkiftl6MnwzVOwPEPhVd6bo5XpJpqHrpFprzRGs6SDQaP7Av02cXsnm2G98o9pyV6no01DG8f9eYeph8i9ixWhmWzzUGIc%2FlxrgJeBxhnlVKaDrbu71XhcAOyQ4SGFHgK%2F0pfpnrALNbV0Cudl75xqOUBhbmNfTFpQEof35j%2BINgQOs5lNae6pkiIbuGuUPDdqc%2F%2BQ3tvGMe6IATU9eLoeHEorxqfIjJFHEnw1gBFYbqV2cpF%2FWji%2BnZPx0E%2Fa5GR%2FYcwheyvxwY6sgFJF%2FQFjun0sV%2BECxOL%2FTuVzHq694OWgVoSgNDx4WluNXzjamfXyHvCKwlmMHfw0iU9V7ss%2FE5Q7qMpF%2BVEQpksEYBhTxMrVqgj1iqEtqJkeG07woDm8hgI6GfH6dKxPZS3XuMPq0tE1oKzBl29djNDQOHqpA0ryMSvORX%2BiIuV25Gpr8CCNiZvVDvyry8DGqKMbVFGg6dJBHiSevXO6wN4ywZqvh6vk%2BezL7V5SfQcLeJS&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20251012T191728Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY4HAWZ54J%2F20251012%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=f33e149fdbd6d12c067d0beb13314028b7209deda67f57ada1cc624dc5cf6316&hash=bf4dc2c21e39e90bb23c4eb02824e843075ad095d3ce8ec80a8058f74873e8a1&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0262885610000442&tid=spdf-d573f53d-a765-481d-818e-a16a9beb0ffb&sid=e6681d6173191544dc3a37793234a1d314c1gxrqb&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=1f175c5b0b5609575354&rr=98d8f00638d70146&cc=es)]

- CvxPnPL: A Unified Convex Solution to the Absolute Pose Estimation Problem from Point and Line Correspondences, *JMIV, 2023*. [[Paper](https://arxiv.org/pdf/1907.10545)] [[Code](https://github.com/SergioRAgostinho/cvxpnpl)]

#### **POP**

- Globally Optimal O(n) Solution to the PnP Problem for General Camera Models, *BMVC, 2008*. [[Paper](https://bmva-archive.org.uk/bmvc/2008/papers/31.pdf)]

- Certifiably Optimal and Robust Camera Pose Estimation From Points and Lines, *Access, 2020*. [[Paper](https://ieeexplore.ieee.org/document/9129691)]

- The Non-Tightness of a Convex Relaxation to Rotation Recovery, *Sensors, 2021*. [[paper](https://pdfs.semanticscholar.org/8443/078e59470deca8fabcb50b5294093e294cb5.pdf)]

#### Others

- A Direct Least-Squares (DLS) Method for PnP, *ICCV, 2011*. [[Paper](https://www-users.cse.umn.edu/~stergios/papers/ICCV-11-DLS-PnP.pdf)]

- Globally Optimal Pose Estimation from Line Correspondences, *ICAR, 2011*. [[Paper](https://www-users.cse.umn.edu/~stergios/papers/ICRA-2011-Line2Line.pdf)]

- Revisiting the PnP Problem: A Fast, General and Optimal Solution, *ICCV, 2013*. [[Paper](https://openaccess.thecvf.com/content_iccv_2013/papers/Zheng_Revisiting_the_PnP_2013_ICCV_paper.pdf)]

- UPnP: An Optimal O(n) Solution to the Absolute Pose Problem with Universal Applicability, *ECCV, 2014*. [[Paper](https://openreview.net/pdf?id=PbMNl2kC0u)]

- gDLS: A Scalable Solution to the Generalized Pose and Scale Problem, *ECCV, 2014*. [[Paper](https://vfragoso.com/pdfs/gdls_eccv_14.pdf)]

- Globally Optimal DLS Method for PnP Problem with Cayley Parameterization, *BMVC, 2015*. [[Paper](https://www.bmva-archive.org.uk/bmvc/2015/papers/paper078/paper078.pdf)] [[Code](https://github.com/g9nkn/pnp_problem)]

- Large Scale SfM with the Distributed Camera Model, *3DV, 2016*. [[Paper](https://arxiv.org/pdf/1607.03949)]

- A Versatile Approach for Solving PnP, PnPf, and PnPfr Problems, *ECCV, 2016*. [[Paper](https://jpn.nec.com/rd/people/docs/eccv2016_nakano.pdf)] [[Code](https://github.com/g9nkn/pnpfr_problem)]

- Unifying Algebraic Solvers for Scaled Euclidean Registration from Point, Line and Plane Constraints, *ACCV, 2016*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-319-54193-8_4)]

- Non-Iterative Rigid 2D/3D Point-Set Registration Using Semidefinite Programming, *TIP, 2016*. [[Paper](https://arxiv.org/pdf/1501.00630)]

- A Universal, Closed-Form Approach for Absolute Pose Problems, *CVIU, 2018*. [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1077314218300572)]

- gDLS*: Generalized Pose-and-Scale Estimation Given Scale and Gravity Priors, *CVPR, 2020*. [[Paper](https://arxiv.org/pdf/2004.02052)]

- A Consistently Fast and Globally Optimal Solution to the Perspective-n-Point Problem, *ECCV, 2020*. [[Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460460.pdf)] [[Code](https://github.com/terzakig/sqpnp)]

- Uncertainty-Aware Camera Pose Estimation from Points and Lines, *CVPR, 2021*. [[Paper](https://arxiv.org/pdf/2107.03890)] [[Code](https://github.com/alexandervakhitov/uncertain-pnp)]

- Efficient Solution to PnP Problem Based on Vision Geometry, *RAL, 2023*. [[Paper](https://ieeexplore.ieee.org/document/10319768)]

#### **Hybrid**

- Fast Certifiable Algorithm for the Absolute Pose Estimation of a Camera, *SIAM Journal on Imaging Sciences, 2024*. [[Paper](https://mapir.isa.uma.es/papersrepo/2024/mergarsal_cert_pnp.pdf)]

#### **Robust**

- Outliers Rejection for Robust Camera Pose Estimation using Graduated Non‐Convexity, *IET CV, 2024*. [[Paper](https://ietresearch.onlinelibrary.wiley.com/doi/pdfdirect/10.1049/cvi2.12330)]

##

### Relative Pose Estimation

#### **BnB for Relative Pose Estimation**

- Two View Geometry Estimation with Outliers, *BMVC, 2009*. [[Paper](https://bmva-archive.org.uk/bmvc/2009/Papers/Paper431/Paper431.pdf)]

- A Branch and Contract Algorithm for Globally Optimal Fundamental Matrix Estimation, *CVPR, 2011*. [[Paper](https://ieeexplore.ieee.org/document/5995352)]

- Direct Optimization of Frame-to-Frame Rotation, *ICCV, 2013*. [[Paper](https://openaccess.thecvf.com/content_iccv_2013/papers/Kneip_Direct_Optimization_of_2013_ICCV_paper.pdf)]

- Optimal Essential Matrix Estimation via Inlier-Set Maximization, *ECCV, 2014*. [[Paper](https://jlyang.org/eccv14_optimalematrix.pdf)]

- Optimal Relative Pose with Unknown Correspondences, *CVPR, 2016*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2016/papers/Fredriksson_Optimal_Relative_Pose_CVPR_2016_paper.pdf)]

- 



- Motion Estimation for Multi-Camera Systems using Global Optimization, *CVPR, 2008*. [[Paper](https://users.cecs.anu.edu.au/~hartley/Papers/PDF/KimLiHartley:CVPR08.pdf)]





- Globally Optimal Inlier Set Maximization With Unknown Rotation and Focal Length, *ECCV, 2014*. [[Paper](https://people.inf.ethz.ch/pomarc/pubs/BazinECCV14.pdf)]

- Efficient Globally-Optimal Correspondence-Less Visual Odometry for Planar Ground Vehicles, *ICRA, 2020*. [[Paper](https://arxiv.org/pdf/2203.00291)]

- Globally Optimal Consensus Maximization for Relative Pose Estimation With Known Gravity Direction, *RAL, 2021*. [[Paper](https://mediatum.ub.tum.de/doc/1613526/fwd04tq7nzvuegw23cpsnrcq5.Globally_Optimal_Consensus_Maximization_for_Relative_Pose_Estimation_With_Known_Gravity_Direction.pdf)] [[Code](https://github.com/Liu-Yinlong/Globally-Optimal-Consensus-Maximization-for-Relative-Pose-Estimation-with-Known-Gravity-Direction)]

- Globally-Optimal Inlier Maximization for Relative Pose Estimation Under Planar Motion, *Frontiers in Neurorobotics, 2022*. [[Paper](https://mediatum.ub.tum.de/doc/1649876/ldzwfew4eb3e2m1r71ktg6szj.fnbot-16-820703.pdf)]

#### **SDP for Relative Pose Estimation**

- Finding the Exact Rotation between Two Images Independently of the Translation, *ECCV, 2012*. [[Paper](https://people.inf.ethz.ch/pomarc/pubs/KneipECCV12.pdf)]

- A Certifiably Globally Optimal Solution to the Non-Minimal Relative Pose Problem, *CVPR, 2018*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/3968.pdf)]

- A Certifiably Globally Optimal Solution to Generalized Essential Matrix Estimation, *CVPR, 2020*. [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhao_A_Certifiably_Globally_Optimal_Solution_to_Generalized_Essential_Matrix_Estimation_CVPR_2020_paper.pdf)]

- Robot-to-Robot Relative Pose Estimation based on Semidefinite Relaxation Optimization, *IROS, 2020*. [[Paper](https://freeformrobotics.org/wp-content/uploads/2022/02/IROS20_0234_FI.pdf)]

- Certifiable Relative Pose Estimation, *IVC, 2021*. [[Paper](https://arxiv.org/pdf/2003.13732)]

- An Efficient Solution to Non-Minimal Case Essential Matrix Estimation, *TPAMI, 2022*. [[Paper](https://arxiv.org/pdf/1903.09067)] [[Code](https://github.com/jizhaox/npt-pose)]

- A Tighter Relaxation for the Relative Pose Problem Between Cameras, *JMIV, 2022*. [[Paper](https://mapir.isa.uma.es/papersrepo/2022/2022_mercedes_JMIV_tighter_rel_rpp_paper.pdf)] [[Code](https://github.com/mergarsal/TighterRPp)]

- Essential Matrix Estimation using Convex Relaxations in Orthogonal Space, *ICCV, 2023*. [[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Karimian_Essential_Matrix_Estimation_using_Convex_Relaxations_in_Orthogonal_Space_ICCV_2023_paper.pdf)] [[Code](https://github.com/armandok/QME)]

- Fast Certifiable Relative Pose Estimation with Gravity Prior, *2023*. [[Paper](https://mapir.isa.uma.es/papersrepo/2023/2023_mercedes_AI_priorRPp_doc.pdf)] [[Code](https://github.com/mergarsal/RedCertRPpPrior)]

- From Correspondences to Pose: Non-minimal Certifiably Optimal Relative Pose without Disambiguation, *CVPR, 2024*. [[Paper](https://arxiv.org/pdf/2312.05995)] [[Code](https://github.com/javrtg/C2P)] [[Project Page](https://javrtg.github.io/C2P/)]

- Certifiable Planar Relative Pose Estimation with Gravity Prior, *CVIU, 2024*. [[Paper](https://mapir.isa.uma.es/papersrepo/2024/mergarsal_cert_rpp_planar_prior.pdf)] [[Code](https://github.com/mergarsal/RedCertRPpPrior)]

- On Semidefinite Relaxations for Matrix-Weighted State-Estimation Problems in Robotics, *TRO, 2024*. [[Paper](https://arxiv.org/pdf/2308.07275)]

- Certifiably Optimal Rotation and Pose Estimation Based on the Cayley Map, *IJRR, 2025*. [[Paper](https://arxiv.org/pdf/2308.12418)]
  
#### **POP for Relative Pose Estimation**

- Estimating the Fundamental Matrix via Constrained Least-Squares: A Convex Approach, *TPAMI, 2002*. [[Paper](https://mi.eng.cam.ac.uk/~cipolla/publications/article/2002-PAMI-fundamental.pdf)]

- SDP Relaxations for Quadratic Optimization Problems Derived from Polynomial Optimization Problems, *APJOR, 2010*. [[Paper](https://s3.us.cloud-object-storage.appdomain.cloud/res-files/1885-MKqop.pdf)]

- Rank-Constrained Fundamental Matrix Estimation by Polynomial Global Optimization Versus the Eight-Point Algorithm, *JMIV, 2014*. [[Paper](https://arxiv.org/pdf/1403.4806)]

- 

- A Convex Optimization Approach to Robust Fundamental Matrix Estimation, *CVPR, 2015*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2015/papers/Cheng_A_Convex_Optimization_2015_CVPR_paper.pdf)]

- Non-Minimum Essential Matrix Estimation Using Sum of Square Method, *AIAM, 2019*. [[Paper](https://ieeexplore.ieee.org/abstract/document/8950797)]

- SPLP: A Certifiably Globally Optimal Solution to the Relative Pose Estimation Problem Using Points and Line Pairs, *JIN, 2022*. [[Paper](https://www.worldscientific.com/doi/abs/10.1142/S0219265921430453)]

#### **GNC for Relative Pose Estimation**

- Fast and Robust Certifiable Estimation of the Relative Pose Between Two Calibrated Cameras, *JMIV, 2021*. [[Paper](https://arxiv.org/pdf/2101.08524)] [[Code](https://github.com/mergarsal/FastCertRelPose)]
  
#### **Hybrid for Relative Pose Estimation**

- Scalable Distance-based Multi-Agent Relative State Estimation via Block Multiconvex Optimization, *RSS, 2024*. [[Paper](https://arxiv.org/pdf/2405.20883)]


#### **Unknown**

- Camera Displacement via Constrained Minimization of the Algebraic Error, *TPAMI,2009*. [[Paper](https://ieeexplore.ieee.org/abstract/document/4731224)]

##

### 3D Registration

#### **BnB for 3D Registration**

- The Registration Problem Revisited: Optimal Solutions From Points, Lines and Planes, *CVPR, 2006*. [[Paper](https://ieeexplore.ieee.org/document/1640887)]

- The 3D-3D Registration Problem Revisited, *ICCV, 2007*. [[Paper](https://users.cecs.anu.edu.au/~hongdong/ICCVBBPose_CRC_v12_afterrichard.pdf)]

- Branch-and-Bound Methods for Euclidean Registration Problems, *TPAMI, 2008*. [[Paper](https://www.researchgate.net/profile/Carl-Olsson/publication/24213723_Branch-and-Bound_Methods_for_Euclidean_Registration_Problems/links/004635350b97899adb000000/Branch-and-Bound-Methods-for-Euclidean-Registration-Problems.pdf?origin=publicationDetail&_sg%5B0%5D=ajuD2AkWssFLZdjQIaxRMJBya-sQVgmCcu5V8Nuc-XoW_lExPB_R8jhee9aFwQdfwZCQzlOcw0tkQ_ElaPRTNg.-OfN_lOTgr48aq_BMMF9JBGCr4QQZvYczg3KfX8nErYoVP3kO7AgwpfWGEz46Wy3VlLjFUn9s3rtr52jJW520Q&_sg%5B1%5D=wHJ6Gnp_0TzmSugg4_oLoNNiQkHZDEKArCfLWdn6RTPePC_8Il1lggtSIW_sAAkRzCf_18K9S95lUdObuEt2r0PJ_y1HP99HnxTz4uDumYrA.-OfN_lOTgr48aq_BMMF9JBGCr4QQZvYczg3KfX8nErYoVP3kO7AgwpfWGEz46Wy3VlLjFUn9s3rtr52jJW520Q&_sg%5B2%5D=eoII4B2fO0om69a34AcQrwFsGOaTF5KYPqIN4y4gpGp4vXkGqWGEvROfUfw8Ff8I_xWecC775MeZLtY.1A89mR_cjOO8BxdZR7V-6cs-fHZmSZCJJqO7l8qk-BEEXwvOTQlw5PHkif5bYLX51P4xbZVcXx63UpYDRW3lZQ&_iepl=&_rtd=eyJjb250ZW50SW50ZW50IjoibWFpbkl0ZW0ifQ%3D%3D&_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InB1YmxpY2F0aW9uIiwicG9zaXRpb24iOiJwYWdlSGVhZGVyIn19)]

- Go-ICP: Solving 3D Registration Efficiently and Globally Optimally, *ICCV, 2013*. [[Paper](https://openaccess.thecvf.com/content_iccv_2013/papers/Yang_Go-ICP_Solving_3D_2013_ICCV_paper.pdf)] [[Code](https://github.com/yangjiaolong/Go-ICP)]

- Go-ICP: A Globally Optimal Solution to 3D ICP Point-Set Registration, *TPAMI, 2015*. [[Paper](https://arxiv.org/pdf/1605.03344)] [[Code](https://github.com/yangjiaolong/Go-ICP)]

- Robust and Optimal Sum-of-Squares-Based Point-to-Plane Registration of Image Sets and Structured Scenes, *ICCV, 2015*. [[Paper](https://openaccess.thecvf.com/content_iccv_2015/papers/Paudel_Robust_and_Optimal_ICCV_2015_paper.pdf)]

- GOGMA: Globally-Optimal Gaussian Mixture Alignment, *CVPR, 2016*. [[Paper](https://arxiv.org/pdf/1603.00150)]

- An Efficient Globally Optimal Algorithm for Asymmetric Point Matching, *TPAMI, 2016*. [[Paper](https://www4.comp.polyu.edu.hk/~cslzhang/APM_files/data/APM.pdf)]

- Efficient Global Point Cloud Alignment using Bayesian Nonparametric Mixtures, *CVPR, 2017*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Straub_Efficient_Global_Point_CVPR_2017_paper.pdf)]

- Efficient Global Point Cloud Registration by Matching Rotation Invariant Features Through Translation Search, *ECCV, 2018*. [[Paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Yinlong_Liu_Efficient_Global_Point_ECCV_2018_paper.pdf)]

- Robust and Optimal Registration of Image Sets and Structured Scenes via Sum-of-Squares Polynomials, *IJCV, 2018*. [[Paper](https://hal.science/hal-02113657v1/document)]

- Fast and Globally Optimal Rigid Registration of 3D Point Sets by Transformation Decomposition, *arXiv, 2018*. [[Paper](https://arxiv.org/pdf/1903.08588)]

- Practical Optimal Registration of Terrestrial LiDAR Scan Pairs, *ISPRS Journal of Photogrammetry and Remote Sensing, 2019*. [[Paper](https://arxiv.org/pdf/1811.09962)]

- A Practical Maximum Clique Algorithm for Matching with Pairwise Constraints, *arXiv, 2019*. [[Paper](https://arxiv.org/pdf/1902.01534)]

- Globally Optimal Point Set Registration by Joint Symmetry Plane Fitting, *JMIV, 2021*. [[Paper](https://link.springer.com/content/pdf/10.1007/s10851-021-01024-4.pdf)]

- Deterministic Point Cloud Registration via Novel Transformation Decomposition, *CVPR, 2022*. [[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_Deterministic_Point_Cloud_Registration_via_Novel_Transformation_Decomposition_CVPR_2022_paper.pdf)]

- A Chebyshev Metamodel Based BnB Approach to Efficiently Search Global Optimum for 3D ICP Point Set Registration, *Computer Aided Geometric Design, 2023*. [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0167839623000109)]

- Fast and Deterministic (3+1)DOF Point Set Registration with Gravity Prior, *ISPRS Journal of Photogrammetry and Remote Sensing, 2023*. [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0924271623000825)] [[Code](https://github.com/Xinyi-tum/Fast-and-Deterministic-Registration)]

- QGORE: Quadratic-Time Guaranteed Outlier Removal for Point Cloud Registration, *TPAMI, 2023*. [[Paper](https://ieeexplore.ieee.org/document/10091912)]

- Scalable 3D Registration via Truncated Entry-wise Absolute Residuals, *CVPR, 2024*. [[Paper](https://arxiv.org/pdf/2404.00915)] [[Code](https://github.com/tyhuang98/TEAR-release)]

- Efficient and Robust Point Cloud Registration via Heuristics-Guided Parameter Search, *TPAMI, 2024*. [[Paper](https://arxiv.org/pdf/2404.06155)] [[Code](https://github.com/tyhuang98/HERE-release)]

- Efficient and Deterministic Search Strategy Based on Residual Projections for Point Cloud Registration with Correspondences, *TIV, 2024*. [[Paper](https://arxiv.org/pdf/2305.11716)]

- Hierarchical and Validated Branch-and-Bound Method for Global Point Cloud Registration, *TII, 2025*. [[Paper](https://ieeexplore.ieee.org/document/10716206)]

- Fast Globally Optimal Truncated Least Squares Point Cloud Registration with Fixed Rotation Axis, *arXiv, 2025*. [[Paper](https://arxiv.org/pdf/2508.15613)]

- Robust Point Cloud Registration via Geometric Overlapping Guided Rotation Search, *arXiv, 2025*. [[Paper](https://arxiv.org/pdf/2508.17427)] [[Code](https://github.com/Bitzhaozheng/GMOR)]
  
#### **SDP for 3D Registration**

- Solving Quadratically Constrained Geometrical Problems using Lagrangian Duality, *ICPR, 2008*. [[Paper](http://aeriksson.net/papers/olsson-eriksson-icpr-08.pdf)]

- Global Registration of Multiple Point Clouds Using Semidefinite Programming, *SIAM Journal on Optimization, 2015*. [[Paper](https://arxiv.org/pdf/1306.5226)]

- Convex Global 3D Registration with Lagrangian Duality, *CVPR, 2017*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Briales_Convex_Global_3D_CVPR_2017_paper.pdf)] [[Code](https://github.com/jbriales/CVPR17)]

- A Polynomial-time Solution for Robust Registration with Extreme Outlier Rates, *RSS, 2019*. [[Paper](https://arxiv.org/pdf/1903.08588)]

- Global Optimality for Point Set Registration Using Semidefinite Programming, *CVPR, 2020*. [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Iglesias_Global_Optimality_for_Point_Set_Registration_Using_Semidefinite_Programming_CVPR_2020_paper.pdf)]

- TEASER: Fast and Certifiable Point Cloud Registration, *TRO, 2020*. [[Paper](https://arxiv.org/pdf/2001.07715)] [[Code](https://github.com/MIT-SPARK/TEASER-plusplus)]

- GlobalPointer: Large-Scale Plane Adjustment with Bi-Convex Relaxation, *ECCV, 2024*. [[Paper](https://arxiv.org/pdf/2407.13537)] [[Code](https://github.com/WU-CVGL/GlobalPointer)] [[Project Page](https://bangyan101.github.io/GlobalPointer/)]

#### **Others**

- Global multiview registration using non-convex ADMM, *ICIP, 2017*. [[Paper](https://ieeexplore.ieee.org/document/8296429)]

#### **Robust Improvement for 3D Registration**

- Guaranteed Outlier Removal for Point Cloud Registration with Correspondences, *TPAMI, 2017*. [[Paper](https://arxiv.org/pdf/1711.10209)]

- On the Convergence of IRLS and Its Variants in Outlier-Robust Estimation, *CVPR, 2023*. [[Paper](http://openaccess.thecvf.com/content/CVPR2023/html/Peng_On_the_Convergence_of_IRLS_and_Its_Variants_in_Outlier-Robust_CVPR_2023_paper.html)] [[Code](https://github.com/liangzu/IRLS-CVPR2023)]

##

### Pose Graph Optimization

#### **SDP for Pose Graph Optimization**

- A Convex Optimization based Approach for Pose SLAM Problems, *IROS, 2012*. [[Paper](https://ieeexplore.ieee.org/document/6385742)]

- Lagrangian Duality in 3D SLAM: Verification Techniques and Optimal Solutions, *IROS, 2015*. [[Paper](https://arxiv.org/pdf/1506.00746)]

- On the Inclusion of Determinant Constraints in Lagrangian Duality for 3D SLAM, *RSS Workshop, 2015*. [[Paper](https://www.yasirlatif.info/movingsensors/cameraReady/paper08.pdf)]

- Pose Graph Optimization in the Complex Domain: Lagrangian Duality, Conditions For Zero Duality Gap, and Optimal Solutions, *arXiv, 2015*. [[Paper](https://arxiv.org/pdf/1505.03437)] [[Code](https://github.com/alpErenSari/poseGraphProject)]

- Duality-based verification techniques for 2D SLAM, *ICRA, 2015*. [[Paper](https://www.dropbox.com/scl/fi/pbpjk3s814eld9ugzsell/2015c-ICRA-duality2D.pdf?rlkey=v417x37w7c9fjowe649k918sr&e=1&dl=0)]

- Fast Global Optimality Verification in 3D SLAM, *IROS, 2016*. [[Paper](https://mapir.isa.uma.es/jbriales/publications/IROS16.pdf)] [[Code](https://github.com/jbriales/PGO-LagInit)]

- Lagrangian Duality in Complex Pose Graph Optimization, *SOIA, 2016*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-319-42056-1_5)]

- Planar Pose Graph Optimization: Duality, Optimal Solutions, and Verification, *TRO, 2016*. [[Paper](https://dellaert.github.io/files/Carlone16tro.pdf)]

- Initialization of 3D Pose Graph Optimization Using Lagrangian Duality, *ICRA, 2017*. [[Paper](https://mapir.isa.uma.es/jbriales/publications/ICRA17+supp.pdf)]

- Cartan-Sync: Fast and Global SE(d)-Synchronization, *RAL, 2017*. [[Paper](https://mapir.isa.uma.es/jbriales/publications/RAL17+supp.pdf)] [[Code](https://bitbucket.org/jesusbriales/cartan-sync/src)]

- Convex Relaxations for Pose Graph Optimization With Outliers, *RAL, 2018*. [[Paper](https://arxiv.org/pdf/1801.02112)]

- CPL-Sync: Efficient and Guaranteed Planar Pose Graph Optimization Using the Complex Number Representation, *IROS, 2019*. [[Paper](https://par.nsf.gov/servlets/purl/10178619)] [[Code](https://github.com/fantaosha/CPL-Sync)]

- Modeling Perceptual Aliasing in SLAM via Discrete-Continuous Graphical Models, *RAL, 2019*. [[Paper](https://arxiv.org/pdf/1810.11692)]

- SE-Sync: A Certifiably Correct Algorithm for Synchronization over the Special Euclidean Group, *IJRR, 2019*. [[Paper](https://arxiv.org/pdf/1612.07386)] [[Code](https://github.com/david-m-rosen/SE-Sync)]

- Distributed Certifiably Correct Pose-Graph Optimization, *TRO, 2019*. [[Paper](https://arxiv.org/pdf/1911.03721)] [[Code](https://github.com/mit-acl/dpgo)]

- SIM-Sync: From Certifiably Optimal Synchronization over the 3D Similarity Group to Scene Reconstruction with Learned Depth, *RAL, 2024*. [[Paper](https://arxiv.org/pdf/2309.05184)]

- Certifiably Correct Range-Aided SLAM, *TRO, 2024*. [[Paper](https://arxiv.org/pdf/2302.11614)] [[Code](https://github.com/MarineRoboticsGroup/cora)]

- Distributed Certifiably Correct Range-Aided SLAM, *ICRA, 2025*. [[Paper](https://arxiv.org/pdf/2503.03192)] [[Code](https://github.com/adthoms/dcora)]

#### **POP for Pose Graph Optimization**

- Guaranteed Globally Optimal Planar Pose Graph and Landmark SLAM via Sparse-Bounded Sums-of-Squares Programming, *ICRA, 2019*. [[Paper](https://arxiv.org/pdf/1809.07744)]

#### **Others**

- A Convex Relaxation for Approximate Global Optimization in Simultaneous Localization and Mapping, *ICRA, 2015*. [[Paper](https://david-m-rosen.github.io/publication/approxglobalslam-icra/ApproxGlobalSLAM-ICRA.pdf)]

- SCORE: A Second-Order Conic Initialization for Range-Aided SLAM, *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2210.03177)] [[Code](https://github.com/MarineRoboticsGroup/score)]

##

### Triangulation

#### **BnB for Triangulation**

- A Fast Optimal Algorithm for $L_2$ Triangulation, *ACCV, 2007*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-540-76390-1_28)]

- Triangulation of Points, Lines and Conics, *JMIV, 2008*. [[Paper](https://lucris.lub.lu.se/ws/portalfiles/portal/2621089/1245431.pdf)]
  
#### **SDP for Triangulation**

- Multi-View Structure Computation without Explicitly Estimating Motion, *CVPR, 2010*. [[Paper](https://users.cecs.anu.edu.au/~hongdong/cvpr10a.pdf)]

- A QCQP Approach to Triangulation, *ECCV, 2012*. [[Paper](https://arxiv.org/pdf/1207.7160)]

- Robust multiview $L_2$ triangulation via optimal inlier selection and 3D structure refinement, *PR, 2014*. [[Paper](https://www.sciencedirect.com/science/article/pii/S0031320314001204)]

- A Convex Relaxation to Compute the Nearest Structured Rank Deficient Matrix, *SIAM, 2021*. [[Paper](https://arxiv.org/pdf/1904.09661)] [[Code](https://github.com/diegcif/stls_sdp)]

- Semidefinite Relaxations for Robust Multiview Triangulation, *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2301.11431)] [[Code](https://github.com/Linusnie/robust-triangulation-relaxations)]

#### **Hybrid for Triangulation**

- Certifiable Solver for Real-Time N-View Triangulation, *RAL, 2023*. [[Paper](https://mapir.isa.uma.es/papersrepo/2023/2023_mercedes_RAL_Nview_triangulation_paper.pdf)] [[Code](https://github.com/mergarsal/FastNViewTriangulation)]

#### **Others**

- A Practical Algorithm for $L_\infty$ Triangulation with Outliers, *CVPR, 2007*. [[Paper](https://users.cecs.anu.edu.au/~hongdong/Linfty_CameraReady_ver3.9.pdf)]

- Triangulation in Omnidirectional Vision under the $L_\infty$-Norm, *ICINFA, 2010*. [[Paper](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=b367f4809c77958ba149c3d69cf96bc7abed3560)]

- L-Infinity Norm Minimization in the Multiview Triangulation, *CCC, 2012*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-16530-6_58)]

##

### Vanishing Point Estimation

#### **BnB for Vanishing Point Estimation**

- Globally Optimal Line Clustering and Vanishing Point Estimation in Manhattan World, *CVPR, 2012*. [[Paper](https://people.inf.ethz.ch/pomarc/pubs/BazinCVPR12.pdf)]

- Globally Optimal Manhattan Frame Estimation in Real-time, *CVPR, 2016*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2016/papers/Joo_Globally_Optimal_Manhattan_CVPR_2016_paper.pdf)]

- Robust and Globally Optimal Manhattan Frame Estimation in Near Real Time, *TPAMI, 2018*. [[Paper](https://arxiv.org/pdf/1605.03730)]

- Globally Optimal Inlier Set Maximization for Atlanta Frame Estimation, *CVPR, 2018*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Joo_Globally_Optimal_Inlier_CVPR_2018_paper.pdf)]

- Globally Optimal Inlier Set Maximization for Atlanta World Understanding, *TPAMI, 2019*. [[Paper](https://ieeexplore.ieee.org/document/8684265)]

- Globally Optimal Vertical Direction Estimation in Atlanta World, *TPAMI, 2020*. [[Paper](https://mediatum.ub.tum.de/doc/1575108/sbpjj4tkp2hgx5o95u2wotkzw.GlobalVerticallyCorrect.pdf)] [[Code](https://github.com/Liu-Yinlong/Globally-optimal-vertical-direction-estimation-in-Atlanta-world)]

#### **SDP for Vanishing Point Estimation**

- Convex Relaxation for Robust Vanishing Point Estimation in Manhattan World, *CVPR, 2025*. [[Paper](https://arxiv.org/pdf/2505.04788)] [[Code](https://github.com/WU-CVGL/GlobustVP/)]

#### **Hybrid for Vanishing Point Estimation**

- Quasi-globally Optimal and Efficient Vanishing Point Estimation in Manhattan World, *ICCV, 2019*. [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Li_Quasi-Globally_Optimal_and_Efficient_Vanishing_Point_Estimation_in_Manhattan_World_ICCV_2019_paper.pdf)]

- Globally Optimal and Efficient Vanishing Point Estimation in Atlanta World, *ECCV, 2020*. [[Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670154.pdf)]

- Quasi-globally Optimal and Near/True Real-time Vanishing Point Estimation in Manhattan World, *TPAMI, 2022*. [[Paper](https://ieeexplore.ieee.org/document/9193899)]

##

### Bundle Adjustment

#### **SDP for Bundle Adjustment**

- Building Rome with Convex Optimization, *RSS, 2025*. [[Paper](https://arxiv.org/pdf/2502.04640)] [[Code](https://github.com/ComputationalRobotics/XM-code)] [[Project Page](https://computationalrobotics.seas.harvard.edu/XM/)]

#### **Others**

- Projective Bundle Adjustment from Arbitrary Initialization using the Variable Projection Method， *ECCV, 2016*. [[Paper](https://core.ac.uk/download/pdf/83939266.pdf)]

- pOSE: Pseudo Object Space Error for Initialization-Free Bundle Adjustment, *CVPR, 2018*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Hong_pOSE_Pseudo_Object_CVPR_2018_paper.pdf)]

- expOSE: Accurate Initialization-Free Projective Factorization using Exponential Regularization, *CVPR, 2023*. [[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Iglesias_expOSE_Accurate_Initialization-Free_Projective_Factorization_Using_Exponential_Regularization_CVPR_2023_paper.pdf)]

- Power Variable Projection for Initialization-Free Large-Scale Bundle Adjustment, *ECCV, 2024*. [[Paper](https://arxiv.org/pdf/2405.05079)] [[Code](https://github.com/tum-vision/povar)]

- Towards Initialization-free Calibrated Bundle Adjustment, *arXiv, 2025*. [[Paper](https://arxiv.org/pdf/2506.23808)]

##

### All-in-One

#### **BnB**

- Practical Global Optimization for Multiview Geometry, *ECCV, 2006*. [[Paper](https://homes.cs.washington.edu/~sagarwal/optimal.pdf)]

- Global Optimization through Searching Rotation Space and Optimal Estimation of the Essential Matrix, *ICCV, 2007*. [[Paper](https://ieeexplore.ieee.org/document/4408896)]

- Practical Global Optimization for Multiview Geometry, *IJCV, 2008*. [[Paper](https://homes.cs.washington.edu/~sagarwal/kahl-agarwal-etal-ijcv-07.pdf)]

- Optimal Correspondences from Pairwise Constraints, *ICCV, 2009*. [[Paper](https://lup.lub.lu.se/search/files/4311163/1454018.pdf)]

- Global Optimization through Rotation Space Search, *IJCV, 2009*. [[Paper](https://users.cecs.anu.edu.au/~hartley/Papers/PDF/HartleyKahl:Ematrix.pdf)]

- Consensus Set Maximization with Guaranteed Global Optimality for Robust Geometry Estimation, *ICCV, 2009*. [[Paper](https://users.cecs.anu.edu.au/~hongdong/iccv09.pdf)]

- Deterministically Maximizing Feasible Subsystem for Robust Model Fitting with Unit Norm Constraint, *CVPR, 2011*. [[Paper](http://www.cvpapers.com/papers/1494.pdf)]

- Globally Optimal Linear Model Fitting with Unit-Norm Constraint, *IJCV, 2022*. [[Paper](https://link.springer.com/article/10.1007/s11263-022-01574-z)]

- Accelerating Globally Optimal Consensus Maximization in Geometric Vision, *TPAMI, 2024*. [[Paper](https://arxiv.org/pdf/2304.05156)]

#### **POP**

- Globally Optimal Estimates for Geometric Reconstruction Problems, *ICCV, 2005*. [[Paper](https://vision.cornell.edu/se3/wp-content/uploads/2014/09/iccv05a.pdf)]

- Globally Optimal Estimates for Geometric Reconstruction Problems, *IJCV, 2007*. [[Paper](https://www.cs.ait.ac.th/~mdailey/cvreadings/Kahl-Global.pdf)]

- Convex Relaxations for Consensus and Non-Minimal Problems in 3D Vision, *ICCV, 2019*. [[Paper](https://arxiv.org/pdf/1909.12034)]

- One Ring to Rule Them All: Certifiably Robust Geometric Perception with Outliers, *NeurIPS, 2020*. [[Paper](https://arxiv.org/pdf/2006.06769)] [[Code](https://github.com/MIT-SPARK/CertifiablyRobustPerception/tree/NeurIPS2020)]

- Certifiably Optimal Outlier-Robust Geometric Perception: Semidefinite Relaxations and Scalable Global Optimization, *TPAMI, 2022*. [[Paper](https://arxiv.org/pdf/2109.03349)] [[Code](https://github.com/MIT-SPARK/CertifiablyRobustPerception)]

#### **Others**

- $L_\infty$ Minimization in Geometric Reconstruction Problems, *CVPR, 2004*. [[Paper](https://www.robots.ox.ac.uk/~vgg/publications/2004/Hartley04b/hartley04b.pdf)]

- Multiple View Geometry and the $L_\infty$-Norm, *ICCV, 2005*. [[Paper](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=4709597f006ce58ee07043c7d140b8bb93df890f)]

- Removing Outliers Using The $L_\infty$ Norm, *CVPR, 2006*. [[Paper](https://ieeexplore.ieee.org/document/1640796)]

- Efficient Optimization for $L_\infty$-problems Using Pseudoconvexity, *ICCV, 2007*. [[Paper](https://ieeexplore.ieee.org/document/4409087)]

- A Fast Method to Minimize $L_\infty$ Error Norm for Geometric Vision Problems, *ICCV, 2007*. [[Paper](https://ieeexplore.ieee.org/document/4408913)]

- Quasiconvex Optimization for Robust Geometric Reconstruction, *TPAMI, 2007*. [[Paper](https://www.cs.cmu.edu/~ke/publications/quasiconvex-optimization-PAMI.pdf)]

- A Polynomial-time Bound for Matching and Registration with Outliers, *CVPR, 2008*. [[Paper](https://scispace.com/pdf/a-polynomial-time-bound-for-matching-and-registration-with-mpk50t5i0e.pdf)]

- Fast Algorithms for $L_\infty$ Problems in Multiview Geometry, *CVPR, 2008*. [[Paper](https://homes.cs.washington.edu/~sagarwal/gfp.pdf)]

- Multiple-View Geometry Under the $L_\infty$-Norm, *TPAMI, 2008*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=4385722&casa_token=RMj0FtymfNwAAAAA:QvSo2fMH6ILIauWl96KHR4P4wbqpeMON_IADNiLA5i2PTiAlI9abZ8VyV3K_R3ngx46Ij0hQqVM)]

- Efficient Reduction of L-infinity Geometry Problems, *CVPR, 2009*. [[Paper](https://users.cecs.anu.edu.au/~hongdong/1289.pdf)]

- Outlier Removal Using Duality, *CVPR, 2010*. [[Paper](http://aeriksson.net/papers/olsson-eriksson-etal-cvpr-10.pdf)] [[Code](https://www.maths.lth.se/matematiklth/personal/calle/Outl_dual/Outl_dual.html)]

- Optimal Geometric Fitting Under the Truncated $L_2$-Norm, *CVPR, 2013*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2013/papers/Ask_Optimal_Geometric_Fitting_2013_CVPR_paper.pdf)]

- Convex Relaxations of SE(2) and SE(3) for Visual Pose Estimation, *ICRA, 2014*. [[Paper](https://arxiv.org/pdf/1401.3700)]

- Consensus Maximization with Linear Matrix Inequality Constraints, *CVPR, 2017*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Speciale_Consensus_Maximization_With_CVPR_2017_paper.pdf)]

- On the Tightness of Semidefinite Relaxations for Rotation Estimation, *JMIV, 2022*. [[Paper](https://arxiv.org/pdf/2101.02099)]

- Performance Guarantees for Spectral Initialization in Rotation Averaging and Pose-Graph SLAM, *ICRA, 2022*. [[Paper](https://arxiv.org/pdf/2201.03773)]

- Quadratic Pose Estimation Problems: Globally Optimal Solutions, Solvability/Observability Analysis, and Uncertainty Description, *TRO, 2022*. [[Paper](https://gogojjh.github.io/assets/pdf/wu2022quadratic.pdf)]

- FracGM: A Fast Fractional Programming Technique for Geman-McClure Robust Estimator, *RAL, 2024*. [[Paper](https://arxiv.org/pdf/2409.13978)] [[Code](https://github.com/StephLin/FracGM)]

---

## Other Resources

### Workshops

- Frontiers of Optimization for Robotics workshop, *RSS, 2024*. [[Website](https://sites.google.com/robotics.utias.utoronto.ca/frontiers-optimization-rss24/home)]

##

### Tutorials

- Global Optimization for Geometric Understanding with Provable Guarantees, *ICCV, 2019*. [[Website](https://mit-spark.github.io/GlobalOptimization-ICCV2019/)]

- Certifiable Robot Perception: from Global Optimization to Safer Robots, *RSS, 2020*. [[Website](https://mit-spark.github.io/CertifiablePerception-RSS2020/)] [[Video](https://www.youtube.com/watch?v=hA7W80bBTMU)]

- RANSAC in 2020, *CVPR, 2020*. [[Website](https://cmp.felk.cvut.cz/cvpr2020-ransac-tutorial/)]

##

### Lectures

- Semidefinite Optimization and Relaxation. [[Website](https://hankyang.seas.harvard.edu/Semidefinite/)]

##

### Talks & Seminars

- Towards Globally Optimal State Estimation. [[Video](https://www.youtube.com/watch?v=vA8pCuMY_2E)]

- Certifiable Outlier-Robust Geometric Perception. [[Video](https://www.youtube.com/watch?v=hpqnBPL9lH4)]
