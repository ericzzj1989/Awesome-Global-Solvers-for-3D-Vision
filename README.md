# Global Optimization for Multiple View Geometry
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
  - [Theory](#theory)
    - [Branch-and-Bound (BnB)](#branch-and-bound-bnb)
    - [Semidefinite Programming (SDP)](#semidefinite-programming-sdp)
    - [Polynomial Optimization (POP)](#polynomial-optimization-pop)
    - [Graduated Non-Convexity (GNC)](#graduated-non-convexity-gnc)
- [Application](#application)
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


---
## Theory

### Branch-and-Bound (BnB)

- Consensus Set Maximization with Guaranteed Global Optimality for Robust Geometry Estimation, *ICCV, 2009*. [[Paper](https://users.cecs.anu.edu.au/~hongdong/iccv09.pdf)]

- GOGMA: Globally-Optimal Gaussian Mixture Alignment, *CVPR, 2016*. [[Paper](https://arxiv.org/pdf/1603.00150)]

- The Alignment of the Spheres: Globally-Optimal Spherical Mixture Alignment for Camera Pose Estimation, *CVPR, 2019*. [[Paper](https://arxiv.org/pdf/1812.01232)]

### Semidefinite Programming (SDP)

- A Nonlinear Programming Algorithm for Solving Semidefinite Programs via Low-rank Factorization, *Mathematical Programming, 2003*. [[Paper](https://sburer.github.io/papers/007-lowrank.pdf)]

- On Convex Relaxations for Quadratically Constrained Quadratic Programming, *Mathematical Programming, 2012*, [[Paper](https://optimization-online.org/wp-content/uploads/2010/08/2699.pdf)]

- Semidefinite Relaxations for Optimization Problems over Rotation Matrices, *CDC, 2014*. [[Paper](https://ecse.monash.edu/staff/james/rotationfiles/SPW_rot.pdf)]

- The Non-Convex Burer-Monteiro Approach Works on Smooth Semidefinite Programs, *NeurIPS, 2016*. [[Paper](https://arxiv.org/pdf/1606.04970)]

- Block-Coordinate Minimization for Large SDPs with Block-Diagonal Constraints, *arXiv, 2019*. [[Paper](https://arxiv.org/pdf/1903.00597)]

- A Convex Relaxation to Compute the Nearest Structured Rank Deficient Matrix, *SIAM, 2021*. [[Paper](https://arxiv.org/pdf/1904.09661)] [[Code](https://github.com/diegcif/stls_sdp)]

- On the Tightness of Semidefinite Relaxations for Rotation Estimation, *JMIV, 2022*. [[Paper](https://arxiv.org/pdf/2101.02099)]

- On the Local Stability of Semidefinite Relaxations, *MP, 2022*. [[Paper](https://arxiv.org/pdf/1710.04287)]

- Semidefinite Relaxations of Truncated Least-Squares in Robust Rotation Search: Tight or Not, *ECCV, 2022*. [[Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136830655.pdf)]

- Accelerating Certifiable Estimation with Preconditioned Eigensolvers, *RAL, 2022*. [Paper](https://arxiv.org/pdf/2207.05257)]

- On the Convergence of IRLS and Its Variants in Outlier-Robust Estimation, *CVPR, 2023*. [[Paper](http://openaccess.thecvf.com/content/CVPR2023/html/Peng_On_the_Convergence_of_IRLS_and_Its_Variants_in_Outlier-Robust_CVPR_2023_paper.html)] [[Code](https://github.com/liangzu/IRLS-CVPR2023)]

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

### Graduated Non-Convexity (GNC)

- Graduated Non-Convexity for Robust Spatial Perception: From Non-Minimal Solvers to Global Outlier Rejection, *RAL, 2020*. [[Paper](https://arxiv.org/pdf/1909.08605)] [[Code](https://github.com/MIT-SPARK/GNC-and-ADAPT)]

- Outlier-Robust Estimation: Hardness, Minimally Tuned Algorithms, and Applications, *TRO, 2021*, [[Pape](https://arxiv.org/pdf/2007.15109)] [[Code](https://github.com/MIT-SPARK/GNC-and-ADAPT)]

- Adaptive Annealing for Robust Geometric Estimation, *CVPR, 2023*. [[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Sidhartha_Adaptive_Annealing_for_Robust_Geometric_Estimation_CVPR_2023_paper.pdf)]

---

## Application

### Rotation Averaging

#### **Analysis**

- Combining Two-view Constraints For Motion Estimation, *CVPR, 2001*. [[Paper](https://ieeexplore.ieee.org/document/990963)]

#### **BnB for Rotation Averaging**

#### **SDP for Rotation Averaging**

- Angular synchronization by eigenvectors and semidefinite programming, *Applied and Computational Harmonic Analysis, 2011*. [[Paper](https://arxiv.org/pdf/0905.3174)]

- Global Motion Estimation from Point Matches, *3DIMPVT, 2012*. [[Paper](https://homes.cs.washington.edu/~kemelmi/sfm_3dimpvt12.pdf)]
  
- Simultaneous Multiple Rotation Averaging Using Lagrangian Duality, *ACCV, 2012*. [[Paper](https://scispace.com/pdf/simultaneous-multiple-rotation-averaging-using-lagrangian-1ecpzvpaw8.pdf)]

- Semidefinite Relaxations for Optimization Problems over Rotation Matrices, *CDC, 2014*. [[Paper](https://ecse.monash.edu/staff/james/rotationfiles/SPW_rot.pdf)]

- Global Robust Image Rotation from Combined Weighted Averaging, *JPRS, 2017*. [[Paper](https://ris.utwente.nl/ws/portalfiles/portal/30048921/Reich2017global.pdf)]

- Tightness of the Maximum Likelihood Semidefinite Relaxation for Angular Synchronization, *Mathematical Programming, 2017*. [[Paper](https://arxiv.org/pdf/1411.3272)]

- Rotation Averaging and Strong Duality, *CVPR, 2018*. [[Paper](https://arxiv.org/pdf/1705.01362)]

- Rotation Averaging with the Chordal Distance: Global Minimizers and Strong Duality, *TPAMI, 2021*. [[Paper](https://ieeexplore.ieee.org/abstract/document/8770111)]

- Rotation Coordinate Descent for Fast Globally Optimal Rotation Averaging, *CVPR, 2021*. [[Paper](https://arxiv.org/pdf/2103.08292)]

- On the Tightness of Semidefinite Relaxations for Rotation Estimation, *JMIV, 2022*. [[Paper](https://arxiv.org/pdf/2101.02099)]

- Certifiably Optimal Anisotropic Rotation Averaging, *ICCV, 2025*. [[Paper](https://arxiv.org/pdf/2503.07353)] [[Code](https://github.com/ylochman/anisotropic-ra)] [[Project Page](https://ylochman.github.io/anisotropic-ra)]

#### **POP for Rotation Averaging**

- Globally Optimal Estimates for Rotation Averaging Problems, *IHMSC, 2014*. [[Paper](https://ieeexplore.ieee.org/document/6911507)]

#### **RANSAC for Rotation Averaging**

- Hierarchical RANSAC-Based Rotation Averaging, *SPL, 2020*. [[Paper](https://ieeexplore.ieee.org/document/9234640)]

- Revisiting Rotation Averaging: Uncertainties and Robust Losses, *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2303.05195)] [[Code](https://github.com/zhangganlin/GlobalSfMpy)]

#### **GNC for Rotation Averaging**

- Pushing the Envelope of Rotation Averaging for Visual SLAM, *arXiv, 2020*. [[Paper](https://arxiv.org/pdf/2011.01163)]

- Adaptive Annealing for Robust Averaging, *ECCV, 2024*. [[Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08834.pdf)]

#### **Hybrid for Rotation Averaging**

- Shonan Rotation Averaging: Global Optimality by Surfing SO(p)^n, *ECCV, 2020*. [[Paper](https://arxiv.org/pdf/2008.02737)] [[Code](https://github.com/dellaert/ShonanAveraging)] [[Project Page](https://dellaert.github.io/ShonanAveraging/index.html)]

- Hybrid Rotation Averaging: A Fast and Robust Rotation Averaging Approach, *CVPR, 2021*. [[Paper](https://arxiv.org/pdf/2101.09116)] [[Code](https://github.com/ethz-asl/hybrid-rotation-averaging)]

#### **Robust Estimation**

- HARA: A Hierarchical Approach for Robust Rotation Averaging. *CVPR, 2022*. [[Paper](https://arxiv.org/pdf/2111.08831)] [[Code](https://github.com/sunghoon031/HARA)]

#### **Others**

- Rotation Averaging in a Split Second: A Primal-Dual Method and a Closed-Form for Cycle Graphs, *ICCV, 2021*. [[Paper](https://arxiv.org/pdf/2109.08046)] <!-- empirically global optimum;primal-dual -->

- Fast and Robust Rotation Averaging with Anisotropic Coordinate Descent, *arXiv, 2025*. [[Paper](https://arxiv.org/pdf/2506.01940)] [[Code](https://github.com/ylochman/acd)] [[Project page](https://ylochman.github.io/acd)]<!-- bridge the gap between optimality, robustness and efficiency of anisotropic rotation averaging --> 

##

### Translation Averaging

#### **Trifocal Tensor**

- Global Fusion of Relative Motions for Robust, Accurate and Scalable Structure from Motion, *ICCV, 2013*. [[Paper](https://openaccess.thecvf.com/content_iccv_2013/papers/Moulon_Global_Fusion_of_2013_ICCV_paper.pdf)]

#### **Convex Relaxation**

- Linear Global Translation Estimation with Feature Tracks, *BMVC, 2015*. [[Paper](https://arxiv.org/pdf/1503.01832)]

- Robust Camera Location Estimation by Convex Programming, *CVPR, 2015*. [[Paper](https://arxiv.org/pdf/1412.0165)]

- Baseline Desensitizing in Translation Averaging, *CVPR, 2018*. [[Paper](https://arxiv.org/pdf/1901.00643)]

#### **SDP for Translation Averaging**

- Stable Camera Motion Estimation Using Convex Programming, *SIAM Journal on Imaging Sciences, 2015*. [[Paper](https://arxiv.org/pdf/1312.5047)]

#### **Robust Estimation**

- Robust Global Translations with 1DSfM, *ECCV, 2014*. [[Paper](https://www.cs.cornell.edu/projects/1dsfm/docs/1DSfM_ECCV14.pdf)] [[Code](https://github.com/wilsonkl/SfM_Init)] [[Project Page](https://www.cs.cornell.edu/projects/1dsfm/)]
  
- Correspondence Reweighted Translation Averaging, *ECCV, 2022*. [[Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136930053.pdf)]

#### **Hybrid for Translation Averaging**

- ARCS: Accurate Rotation and Correspondence Search, *CVPR, 2022*. [Paper](https://arxiv.org/pdf/2203.14493)] [[Code](https://github.com/liangzu/ARCS)

- Revisiting Global Translation Estimation with Feature Tracks, *CVPR, 2024*. [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Tao_Revisiting_Global_Translation_Estimation_with_Feature_Tracks_CVPR_2024_paper.pdf)]

#### **Others**

- Outlier Removal Using Duality, *CVPR, 2010*. [[Paper](http://aeriksson.net/papers/olsson-eriksson-etal-cvpr-10.pdf)] [[Code](https://www.maths.lth.se/matematiklth/personal/calle/Outl_dual/Outl_dual.html)] <!--translation averaging+triangulation -->

- L1-Penalized Robust Estimation for a Class of Inverse Problems Arising in Multiview Geometry, *NeurIPS, 2009*. [[Paper](https://proceedings.neurips.cc/paper_files/paper/2009/file/65ded5353c5ee48d0b7d48c591b8f430-Paper.pdf)] <!--translation averaging+triangulation -->

- Efficient Outlier Removal in Large Scale Global Structure-from-Motion, *arXiv, 2018*. [[Paper](https://arxiv.org/pdf/1808.03041)] <!--translation averaging+triangulation -->

## 

### Wahba Problem

#### **Closed-form**

- Fundamentals of spacecraft attitude determination and control
  
- Closed-form solution of absolute orientation using orthonormal matrices

- Attitude determination using vector observations and the singular value decomposition

- Least-squares fitting of two 3D point sets

- A generalized solution of the orthogonal procrustes problem

- Closed-form solution of absolute orientation using orthonormal matrices

<!-- - Robust fitting for multiple view geometry, *ECCV, 2012*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-33718-5_53)] -->

#### **BnB for Wahba Problem**

- Fast Rotation Search with Stereographic Projections for 3D Registration. *CVPR, 2014*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2014/papers/Bustos_Fast_Rotation_Search_2014_CVPR_paper.pdf)]

#### **Convex Relaxation**

- Semidefinite Relaxation of a Robust Static Attitude Determination Problem, *CDC-ECC, 2011*. [[Paper](https://skoge.folk.ntnu.no/prost/proceedings/cdc-ecc-2011/data/papers/0926.pdf)]

- A Semidefinite Relaxation-Based Algorithm for Robust Attitude Estimation, *TSP, 2012*. [[Paper](https://spiral.imperial.ac.uk/server/api/core/bitstreams/69456b59-58b5-470a-9352-22321a0b02f4/content)]

- A Quaternion-based Certifiably Optimal Solution to the Wahba Problem with Outliers, *ICCV, 2019*. [[Paper](https://arxiv.org/pdf/1905.12536)]

- Semidefinite Relaxations of Truncated Least-Squares in Robust Rotation Search: Tight or Not, *ECCV, 2022*. [[Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136830655.pdf)]

- Towards Understanding The Semidefinite Relaxations of Truncated Least-Squares in Robust Rotation Search, *ECCV, 2022*. [[Paper](https://arxiv.org/pdf/2207.08350)]

#### **POP for Wahba Problem**
*(To be supplemented)*

#### **RANSAC for Wahba Problem**

- RANSIC: Fast and Highly Robust Estimation for Rotation Search and Point Cloud Registration Using Invariant Compatibility, *RAL, 2021*. [[Paper](https://arxiv.org/pdf/2104.09133)] [[Code](https://github.com/lukascher/RANSIC)]

#### **GNC for Wahba Problem**

- FracGM: A Fast Fractional Programming Technique for Geman-McClure Robust Estimator, *RAL, 2024*. [[Paper](https://arxiv.org/pdf/2409.13978)] [[Code](https://github.com/StephLin/FracGM)]

#### **Others**

- Linearly Solving Robust Rotation Estimation, *arXiv, 2025*. [[Paper](https://arxiv.org/pdf/2506.11547)] <!-- voting-based approach -->

##

### Absolute Pose Estimation (PnP)

#### **Analysis**

- EPnP: An Accurate O(n) Solution to the PnP Problem, *IJCV, 2008*. [[Paper](https://www.tugraz.at/fileadmin/user_upload/Institute/ICG/Images/team_lepetit/publications/lepetit_ijcv08.pdf)]

- Minimal Solution for Uncalibrated Absolute Pose Problem with a Known Vanishing Point, *3DV, 2013*. [[Paper](https://www.researchgate.net/profile/Horst-Wildenauer/publication/261262847_Minimal_Solution_for_Uncalibrated_Absolute_Pose_Problem_with_a_Known_Vanishing_Point/links/54e5e6e00cf277664ff1b29f/Minimal-Solution-for-Uncalibrated-Absolute-Pose-Problem-with-a-Known-Vanishing-Point.pdf)]

- Revisiting the PnP Problem: A Fast, General and Optimal Solution, *ICCV, 2013*. [[Paper](https://openaccess.thecvf.com/content_iccv_2013/papers/Zheng_Revisiting_the_PnP_2013_ICCV_paper.pdf)] [[Code](https://github.com/danini/absolute-pose-from-oriented-and-scaled-features)]

- UPnP: An Optimal O(n) Solution to the Absolute Pose Problem with Universal Applicability, *ECCV, 2014*. [[Paper](https://openreview.net/pdf?id=PbMNl2kC0u)]

- Globally Optimal DLS Method for PnP Problem with Cayley parameterization, *BMVC, 2015*. [[Paper](https://www.bmva-archive.org.uk/bmvc/2015/papers/paper078/paper078.pdf)] [[Code](https://github.com/g9nkn/pnp_problem)]

- A Versatile Approach for Solving PnP, PnPf, and PnPfr Problems, *ECCV, 2016*. [[Paper](https://jpn.nec.com/rd/people/docs/eccv2016_nakano.pdf)] [[Code](https://github.com/g9nkn/pnpfr_problem)]

- Fast and robust absolute camera pose estimation with known focal length, *NCA, 2018*. [[Paper](https://link.springer.com/article/10.1007/s00521-017-3032-6)]
 
- A Simple, Robust and Fast Method for the Perspective-n-Point Problem, *PRL, 2018*. [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0167865518300692)]

- A Universal, Closed-Form Approach for Absolute Pose Problems, *CVIU, 2018*. [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1077314218300572)]

- An Efficient and Accurate Algorithm for the Perspecitve-n-Point Problem, *IROS, 2019*. [[Paper](https://www.cs.cmu.edu/~kaess/pub/Zhou19iros.pdf)]

- Absolute Pose from One or Two Scaled and Oriented Features, *CVPR, 2024*. [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Ventura_Absolute_Pose_from_One_or_Two_Scaled_and_Oriented_Features_CVPR_2024_paper.pdf)] [[Code](https://github.com/danini/absolute-pose-from-oriented-and-scaled-features)]

#### **BnB for PnP**

- Optimal Estimation of Perspective Camera Pose, *ICPR, 2006*. [[Paper](https://www.researchgate.net/profile/Carl-Olsson/publication/224649282_Optimal_Estimation_of_Perspective_Camera_Pose/links/004635350b975b3292000000/Optimal-Estimation-of-Perspective-Camera-Pose.pdf)]
  
- Absolute Pose Estimation With a Known Direction by Motion Decoupling, *TCSVT, 2024*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10093787)] [[Code](https://github.com/Liu-Yinlong/algorithm-for-PnP-with-known-vertical-direction)]

#### **SDP for PnP**

- Globally Optimal O(n) Solution to the PnP Problem for General Camera Models, *BMVC, 2008*. [[Paper](https://bmva-archive.org.uk/bmvc/2008/papers/31.pdf)]

- CvxPnPL: A Unified Convex Solution to the Absolute Pose Estimation Problem from Point and Line Correspondences, *JMIV, 2023*. [[Paper](https://arxiv.org/pdf/1907.10545)] [[Code](https://github.com/SergioRAgostinho/cvxpnpl)]

- Optimal and Robust Category-level Perception: Object Pose and Shape Estimation from 2D and 3D Semantic Keypoints, *TRO, 2023*. [[Paper](https://arxiv.org/pdf/2206.12498)] [[Code](https://github.com/MIT-SPARK/PACE)]

#### **POP for PnP**

- The Non-Tightness of a Convex Relaxation to Rotation Recovery, *Sensors, 2021*. [[paper](https://pdfs.semanticscholar.org/8443/078e59470deca8fabcb50b5294093e294cb5.pdf)]
 
#### **GNC for PnP**

- Outliers Rejection for Robust Camera Pose Estimation using Graduated Non‐Convexity, *IET CV, 2024*. [[Paper](https://www.researchgate.net/publication/387343981_Outliers_rejection_for_robust_camera_pose_estimation_using_graduated_non-convexity)]

#### Others

- A Consistently Fast and Globally Optimal Solution to the Perspective-n-Point Problem, *ECCV, 2020*. [[Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460460.pdf)] [[Code](https://github.com/terzakig/sqpnp)]

##

### Relative Pose Estimation

#### **Minimal solvers**

- In Defense of the Eight-Point Algorithm, *TPAMI, 1997*. [[Paper](https://www.cse.unr.edu/~bebis/CS485/Handouts/hartley.pdf)]

- An Efficient Solution to the Five-Point Relative Pose Problem, *TPAMI, 2004*. [[Paper](https://www-users.cse.umn.edu/~hspark/CSci5980/nister.pdf)]

- Recent Developments on Direct Relative Orientation, *JPRS, 2006*. [[Paper](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=514fa8d4981cc2b2aecfc02e0e3a8f4be717bcd7)]

- Camera Displacement via Constrained Minimization of the Algebraic Error, *TPAMI, 2009*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4731224)]

- Finding the Exact Rotation between Two Images Independently of the Translation, *ECCV, 2012*. [[Paper](https://people.inf.ethz.ch/pomarc/pubs/KneipECCV12.pdf)]

- RePoseD: Efficient Relative Pose Estimation With Known Depth Information, *ICCV, 2025*. [[Paper](https://arxiv.org/pdf/2501.07742)]

#### **BnB for Relative Pose Estimation**

- Global Optimization through Searching Rotation Space and Optimal Estimation of the Essential Matrix, *ICCV, 2007*. [[Paper](https://ieeexplore.ieee.org/document/4408896)]

- Robust Optimal Pose Estimation, *ECCV, 2008*. [[Paper](https://www.researchgate.net/profile/Olof-Enqvist/publication/221304187_Robust_Optimal_Pose_Estimation/links/0f3175371ef676bf33000000/Robust-Optimal-Pose-Estimation.pdf)]

- Two View Geometry Estimation with Outliers, *BMVC, 2009*. [[Paper](https://bmva-archive.org.uk/bmvc/2009/Papers/Paper431/Paper431.pdf)]

- A Branch-and-Bound Algorithm for Globally Optimal Calibration of a Camera-and-Rotation-Sensor System, *ICCV, 2009*. [[Paper](http://vigir.missouri.edu/~gdesouza/Research/Conference_CDs/IEEE_ICCV_2009/contents/pdf/iccv2009_151.pdf)]

- Consensus Set Maximization with Guaranteed Global Optimality for Robust Geometry Estimation, *ICCV, 2009*. [[Paper](https://users.cecs.anu.edu.au/~hongdong/iccv09.pdf)]

- Global Optimization through Rotation Space Search, *IJCV, 2009*. [[Paper](https://users.cecs.anu.edu.au/~hartley/Papers/PDF/HartleyKahl:Ematrix.pdf)]

- Direct Optimization of Frame-to-Frame Rotation, *ICCV, 2013*. [[Paper](https://openaccess.thecvf.com/content_iccv_2013/papers/Kneip_Direct_Optimization_of_2013_ICCV_paper.pdf)]

- Optimal Essential Matrix Estimation via Inlier-Set Maximization, *ECCV, 2014*. [[Paper](https://jlyang.org/eccv14_optimalematrix.pdf)]

- Globally Optimal Inlier Set Maximization With Unknown Rotation and Focal Length, *ECCV, 2014*. [[Paper](https://people.inf.ethz.ch/pomarc/pubs/BazinECCV14.pdf)]

- Optimal Relative Pose with Unknown Correspondences, *CVPR, 2016*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2016/papers/Fredriksson_Optimal_Relative_Pose_CVPR_2016_paper.pdf)]

- Globally Optimal Consensus Maximization for Relative Pose Estimation With Known Gravity Direction, *RAL, 2021*. [[Paper](https://mediatum.ub.tum.de/doc/1613526/fwd04tq7nzvuegw23cpsnrcq5.Globally_Optimal_Consensus_Maximization_for_Relative_Pose_Estimation_With_Known_Gravity_Direction.pdf)] [[Code](https://github.com/Liu-Yinlong/Globally-Optimal-Consensus-Maximization-for-Relative-Pose-Estimation-with-Known-Gravity-Direction)]

#### **SDP for Relative Pose Estimation**

- SDP Relaxations for Quadratic Optimization Problems Derived from Polynomial Optimization Problems, *APJOR, 2010*. [[Paper](https://s3.us.cloud-object-storage.appdomain.cloud/res-files/1885-MKqop.pdf)]

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

- Certifiably Optimal Rotation and Pose Estimation Based on the Cayley Map, *IJRR, 2025*. [[Paper](https://arxiv.org/pdf/2308.12418)]

- On Semidefinite Relaxations for Matrix-Weighted State-Estimation Problems in Robotics, *TRO, 2024*. [[Paper](https://arxiv.org/pdf/2308.07275)]
  
#### **POP for Relative Pose Estimation**

- Estimating the Fundamental Matrix via Constrained Least-Squares: A Convex Approach, *TPAMI, 2002*. [[Paper](https://mi.eng.cam.ac.uk/~cipolla/publications/article/2002-PAMI-fundamental.pdf)]

- Rank-Constrained Fundamental Matrix Estimation by Polynomial Global Optimization Versus the Eight-Point Algorithm, *JMIV, 2014*. [[Paper](https://arxiv.org/pdf/1403.4806)]

- A Convex Optimization Approach to Robust Fundamental Matrix Estimation, *CVPR, 2015*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2015/papers/Cheng_A_Convex_Optimization_2015_CVPR_paper.pdf)]

- Non-Minimum Essential Matrix Estimation Using Sum of Square Method, *AIAM, 2019*. [[Paper](https://ieeexplore.ieee.org/abstract/document/8950797)]

- SPLP: A Certifiably Globally Optimal Solution to the Relative Pose Estimation Problem Using Points and Line Pairs, *JIN, 2022*. [[Paper](https://www.worldscientific.com/doi/abs/10.1142/S0219265921430453)]

#### **GNC for Relative Pose Estimation**

- Fast and Robust Certifiable Estimation of the Relative Pose Between Two Calibrated Cameras, *JMIV, 2021*. [[Paper](https://arxiv.org/pdf/2101.08524)] [[Code](https://github.com/mergarsal/FastCertRelPose)]
  
#### **Hybrid for Relative Pose Estimation**

- Scalable Distance-based Multi-Agent Relative State Estimation via Block Multiconvex Optimization, *RSS, 2024*.[[Paper](https://arxiv.org/pdf/2405.20883)]

#### **Others**

- Recovering Camera Motion Using $l_{\infty}$ Minimization, *CVPR, 2006*. [[Paper](https://ieeexplore.ieee.org/document/1640890)]
  
##

### 3D Registration

#### **BnB for 3D Registration**

- The 3D-3D Registration Problem Revisited, *ICCV, 2007*. [[Paper](https://users.cecs.anu.edu.au/~hongdong/ICCVBBPose_CRC_v12_afterrichard.pdf)]

- A Polynomial-time Bound for Matching and Registration with Outliers, *CVPR, 2008*. [[Paper](https://scispace.com/pdf/a-polynomial-time-bound-for-matching-and-registration-with-mpk50t5i0e.pdf)]

- Branch-and-Bound Methods for Euclidean Registration Problems, *TPAMI, 2008*. [[Paper](https://www.researchgate.net/profile/Carl-Olsson/publication/24213723_Branch-and-Bound_Methods_for_Euclidean_Registration_Problems/links/004635350b97899adb000000/Branch-and-Bound-Methods-for-Euclidean-Registration-Problems.pdf?origin=publicationDetail&_sg%5B0%5D=ajuD2AkWssFLZdjQIaxRMJBya-sQVgmCcu5V8Nuc-XoW_lExPB_R8jhee9aFwQdfwZCQzlOcw0tkQ_ElaPRTNg.-OfN_lOTgr48aq_BMMF9JBGCr4QQZvYczg3KfX8nErYoVP3kO7AgwpfWGEz46Wy3VlLjFUn9s3rtr52jJW520Q&_sg%5B1%5D=wHJ6Gnp_0TzmSugg4_oLoNNiQkHZDEKArCfLWdn6RTPePC_8Il1lggtSIW_sAAkRzCf_18K9S95lUdObuEt2r0PJ_y1HP99HnxTz4uDumYrA.-OfN_lOTgr48aq_BMMF9JBGCr4QQZvYczg3KfX8nErYoVP3kO7AgwpfWGEz46Wy3VlLjFUn9s3rtr52jJW520Q&_sg%5B2%5D=eoII4B2fO0om69a34AcQrwFsGOaTF5KYPqIN4y4gpGp4vXkGqWGEvROfUfw8Ff8I_xWecC775MeZLtY.1A89mR_cjOO8BxdZR7V-6cs-fHZmSZCJJqO7l8qk-BEEXwvOTQlw5PHkif5bYLX51P4xbZVcXx63UpYDRW3lZQ&_iepl=&_rtd=eyJjb250ZW50SW50ZW50IjoibWFpbkl0ZW0ifQ%3D%3D&_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InB1YmxpY2F0aW9uIiwicG9zaXRpb24iOiJwYWdlSGVhZGVyIn19)]

- Go-ICP: A Globally Optimal Solution to 3D ICP Point-Set Registration, *TPAMI, 2015*. [[Paper](https://arxiv.org/pdf/1605.03344)] [[Code](https://github.com/yangjiaolong/Go-ICP)]

- An Efficient Globally Optimal Algorithm for Asymmetric Point Matching, *TPAMI, 2017*. [[Paper](https://www4.comp.polyu.edu.hk/~cslzhang/APM_files/data/APM.pdf)]

- Guaranteed Outlier Removal for Point Cloud Registration with Correspondences, *TPAMI, 2017*. [[Paper](https://arxiv.org/pdf/1711.10209)]

- A Practical Maximum Clique Algorithm for Matching with Pairwise Constraints, *arXiv, 2019*. [[Paper](https://arxiv.org/pdf/1902.01534)] <!-- Preprocessing for CMax/BnB, Deterministic Outlier Removal--> 

- Scalable 3D Registration via Truncated Entry-wise Absolute Residuals, *CVPR, 2024*. [[Paper](https://arxiv.org/pdf/2404.00915)] [[Code](https://github.com/tyhuang98/TEAR-release)]

- Fast Globally Optimal Truncated Least Squares Point Cloud Registration with Fixed Rotation Axis, *arXiv, 2025*. [[Paper](https://arxiv.org/pdf/2508.15613)]
  
#### **SDP for 3D Registration**

- Guided Search Consensus: Large Scale Point Cloud Registration by Convex Optimization, *ICIP, 2013*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6738033)]

- Global Registration of Multiple Point Clouds Using Semidefinite Programming, *SIAM Journal on Optimization, 2015*. [[Paper](https://arxiv.org/pdf/1306.5226)]

- Non-Iterative Rigid 2D/3D Point-Set Registration Using Semidefinite Programming, *TIP, 2015*. [[Paper](https://arxiv.org/pdf/1501.00630)]

- Point Registration via Efficient Convex Relaxation, *TOG, 2016*. [[Paper](https://haggaim.github.io/projects/point_registration/PMSDP_final_light.pdf)] [[Code](https://github.com/Haggaim/PM-SDP)]

- Convex Global 3D Registration with Lagrangian Duality, *CVPR, 2017*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Briales_Convex_Global_3D_CVPR_2017_paper.pdf)] [[Code](https://github.com/jbriales/CVPR17)]

- A Polynomial-time Solution for Robust Registration with Extreme Outlier Rates, *RSS, 2019*. [[Paper](https://arxiv.org/pdf/1903.08588)]

- SDRSAC: Semidefinite-Based Randomized Approach for Robust Point Cloud Registration without Correspondences, *2019, CVPR*. [[Paper](https://arxiv.org/pdf/1904.03483)] [[Code](https://github.com/intellhave/SDRSAC)]

- Global Optimality for Point Set Registration Using Semidefinite Programming, *CVPR, 2020*. [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Iglesias_Global_Optimality_for_Point_Set_Registration_Using_Semidefinite_Programming_CVPR_2020_paper.pdf)]

- TEASER: Fast and Certifiable Point Cloud Registration, *TRO, 2020*. [[Paper](https://arxiv.org/pdf/2001.07715)] [[Code](https://github.com/MIT-SPARK/TEASER-plusplus)]

- GlobalPointer: Large-Scale Plane Adjustment with Bi-Convex Relaxation, *ECCV, 2024*. [[Paper](https://arxiv.org/pdf/2407.13537)] [[Code](https://github.com/WU-CVGL/GlobalPointer)] [[Project Page](https://bangyan101.github.io/GlobalPointer/)]
  
#### **POP for 3D Registration**

- Geometry of 3D Environments and Sum of Squares Polynomials, *RSS, 2013*. [[Paper](https://arxiv.org/pdf/1611.07369)]

- A Novel Quaternion-based 2D-3D Registration Algorithm with Line Correspondence, *TIJEE, 2014*. [[Paper](https://journal.esperg.com/index.php/TIJEE/article/view/3203)]
 
- Robust and Optimal Registration of Image Sets and Structured Scenes via Sum-of-Squares Polynomials, *IJCV, 2018*. [[Paper](https://hal.science/hal-02113657v1/document)]
  
#### **GNC for 3D Registration**

- Practical, Fast and Robust Point Cloud Registration for 3D Scene Stitching and Object Localization, *Access, 2021*. [[Paper](https://arxiv.org/pdf/2111.04228)]

- Pyramid Semantic Graph-based Global Point Cloud Registration with Low Overlap, *IROS, 2023*. [[Paper](https://arxiv.org/pdf/2307.12116)] [[Code](https://github.com/HKUST-Aerial-Robotics/Pagor)]

- Adaptive Annealing for Robust Geometric Estimation, *CVPR, 2023*. [[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Sidhartha_Adaptive_Annealing_for_Robust_Geometric_Estimation_CVPR_2023_paper.pdf)]

- G3Reg: Pyramid Graph-based Global Registration using Gaussian Ellipsoid Model, *TASE, 2024*. [[Paper](https://arxiv.org/pdf/2308.11573)] [[Code](https://github.com/HKUST-Aerial-Robotics/G3Reg)]

#### **Others**

- Robust Reconstruction of Indoor Scenes, *CVPR, 2015*. [[Paper](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Choi_Robust_Reconstruction_of_2015_CVPR_paper.pdf)]<!-- Line- process; Robust estimation-->

- Non-Iterative Rigid 2D/3D Point-Set Registration using Semidefinite Programming, *TIP, 2016*. [[Paper](https://arxiv.org/pdf/1501.00630)]

- Fast Global Registration, *ECCV, 2016*. [[Paper](https://vladlen.info/papers/fast-global-registration.pdf)] [[Code](https://github.com/isl-org/FastGlobalRegistration)]

- Maximizing Robustness of Point-Set Registration by Leveraging Non-Convexity, *arXiv, 2020*. [[Paper](https://arxiv.org/pdf/2004.08772)]

- A New Outlier Removal Strategy Based on Reliability of Correspondence Graph for Fast Point Cloud Registration, *TPAMI, 2022*. [[Paper](https://arxiv.org/pdf/2205.07404)] [[Code](https://github.com/WPC-WHU/GROR)]<!-- Graph-based Reliable Outlier Removal; Robust Estimation-->

- 3D Registration with Maximal Cliques, *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2305.10854)] [[Code](https://github.com/zhangxy0517/3D-Registration-with-Maximal-Cliques)]<!-- MAC has variants; Robust Estimation -->

##

### Pose Graph Optimization

#### **BnB for Pose Graph Optimization**
*(To be supplemented)*

#### **SDP for Pose Graph Optimization**

- A convex optimization based approach for pose SLAM problems, *IROS, 2012*. [[Paper](https://ieeexplore.ieee.org/document/6385742)]

- Pose Graph Optimization in the Complex Domain: Lagrangian Duality, Conditions For Zero Duality Gap, and Optimal Solutions, *arXiv, 2015*. [[Paper](https://arxiv.org/pdf/1505.03437)] [[Code](https://github.com/alpErenSari/poseGraphProject)]

- Duality-based verification techniques for 2D SLAM, *ICRA, 2015*. [[Paper](https://www.dropbox.com/scl/fi/pbpjk3s814eld9ugzsell/2015c-ICRA-duality2D.pdf?rlkey=v417x37w7c9fjowe649k918sr&e=1&dl=0)]

- Fast Global Optimality Verification in 3D SLAM, *IROS, 2016*. [[Paper](https://mapir.isa.uma.es/jbriales/publications/IROS16.pdf)] [[Code](https://github.com/jbriales/PGO-LagInit)]

- Lagrangian Duality in Complex Pose Graph Optimization, *SOIA, 2016*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-319-42056-1_5)]

- Planar Pose Graph Optimization: Duality, Optimal Solutions, and Verification, *TRO, 2016*. [[Paper](https://dellaert.github.io/files/Carlone16tro.pdf)]

- Initialization of 3D Pose Graph Optimization Using Lagrangian Duality, *ICRA, 2017*. [[Paper](https://mapir.isa.uma.es/jbriales/publications/ICRA17+supp.pdf)]

- Cartan-Sync: Fast and Global SE(d)-Synchronization, *RAL, 2017*. [[Paper](https://mapir.isa.uma.es/jbriales/publications/RAL17+supp.pdf)] [[Code](https://bitbucket.org/jesusbriales/cartan-sync/src)]

- Convex Relaxations for Pose Graph Optimization With Outliers, *RAL, 2018*. [[Paper](https://arxiv.org/pdf/1801.02112)]

- SE-Sync: A Certifiably Correct Algorithm for Synchronization over the Special Euclidean Group, *IJRR, 2019*. [[Paper](https://arxiv.org/pdf/1612.07386)] [[Code](https://github.com/david-m-rosen/SE-Sync)]

- CPL-Sync: Efficient and Guaranteed Planar Pose Graph Optimization Using the Complex Number Representation, *IROS, 2019*. [[Paper](https://par.nsf.gov/servlets/purl/10178619)] [[Code](https://github.com/fantaosha/CPL-Sync)]

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

- A QCQP Approach to Triangulation, *ECCV, 2012*. [[Paper](https://arxiv.org/pdf/1207.7160)]

- Robust multiview $L_2$ triangulation via optimal inlier selection and 3D structure refinement, *PR, 2014*. [[Paper](https://www.sciencedirect.com/science/article/pii/S0031320314001204)]<!-- Numerical Optimization (DE), SOCP Bound Analysis-->

- Semidefinite Relaxations for Robust Multiview Triangulation, *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2301.11431)] [[Code](https://github.com/Linusnie/robust-triangulation-relaxations)]

#### **Hybrid for Triangulation**

- Certifiable Solver for Real-Time N-View Triangulation, *RAL, 2023*. [[Paper](https://mapir.isa.uma.es/papersrepo/2023/2023_mercedes_RAL_Nview_triangulation_paper.pdf)] [[Code](https://github.com/mergarsal/FastNViewTriangulation)]

#### **Others**

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

- Practical Global Optimization for Multiview Geometry, *ECCV, 2006*. [[Paper](https://cseweb.ucsd.edu/~mkchandraker/pdf/eccv06_optimal.pdf)] <!--  n-view triangulation, PnP and the estimation of general projections  -->

- Practical Global Optimization for Multiview Geometry, *IJCV, 2008*. [[Paper](https://cseweb.ucsd.edu/~mkchandraker/pdf/ijcv08_optimal.pdf)] <!--  n-view triangulation, PnP and the estimation of general projections  -->

- Globally Optimal Consensus Set Maximization through Rotation Search, *ACCV, 2012*. [[Paper](https://d1wqtxts1xzle7.cloudfront.net/84933662/ACCV_2012-libre.pdf?1650946221=&response-content-disposition=inline%3B+filename%3DGlobally_Optimal_Consensus_Set_Maximizat.pdf&Expires=1756227652&Signature=ZZGpssYvDyhCYzfOtcqNvEITWH8b8j5D0JWCDeQaY4q5Cpxq50eDeG9xUt4XoC81UbxK6pAjlqDJV42DPYG--B8N0to9gt5hTpMoo~tseiCQFSq5T7~3LahwAloskJxJFMft~jYOeNPpVc6B9VryXp7eiVdfKs2rNn44AngbaFf-iHcpeSNWp3eZsLymzpMYj-OyRIEdBv0Y3ri9MLTXUCVud8fBj4OXSqTTBJOW7okYbIwVtVATC8U4KIQIJeyAEEOuIPzgfX0KSaePr-XyrAqGfDiAb882nbe2-GoVGvbiI2CkvSBXxEFtJt-a~APoVfcfJ4h09ANzoGPs9sYD4g__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)] <!--  vanishing point estimation, line clustering and rotation estimation  -->

- Accelerating Globally Optimal Consensus Maximization in Geometric Vision, *TPAMI, 2024*. [[Paper](https://arxiv.org/pdf/2304.05156)] <!--  PnP, relative camera pose estimation, 3D registration, and rotation and focal length estimation (Wahba)  -->

#### **POP**

- Globally Optimal Estimates for Geometric Reconstruction Problems, *ICCV, 2005*. [[Paper](https://vision.cornell.edu/se3/wp-content/uploads/2014/09/iccv05a.pdf)] <!--  triangulation, absolute camera pose, homography estimation, fundamental matrix  -->

- Globally Optimal Estimates for Geometric Reconstruction Problems, *IJCV, 2007*. [[Paper](https://www.cs.ait.ac.th/~mdailey/cvreadings/Kahl-Global.pdf)] <!--  triangulation, absolute camera pose, homography estimation, fundamental matrix  -->

- One Ring to Rule Them All: Certifiably Robust Geometric Perception with Outliers, *NeurIPS, 2020*. [[Paper](https://arxiv.org/pdf/2006.06769)] [[Code](https://github.com/MIT-SPARK/CertifiablyRobustPerception/tree/NeurIPS2020)] <!--  Single Rotation Averaging, Shape Alignment, Point Cloud Registration, Mesh Registration   -->

- Certifiably Optimal Outlier-Robust Geometric Perception: Semidefinite Relaxations and Scalable Global Optimization, *TPAMI, 2022*. [[Paper](https://arxiv.org/pdf/2109.03349)] [[Code](https://github.com/MIT-SPARK/CertifiablyRobustPerception)] <!--  Single rotation averaging, Multiple rotation averaging, Point cloud registration, Mesh registration, Absolute pose estimation, Category-Level Object Pose and Shape Estimation -->

#### **Others**

- $L_\infty$ Minimization in Geometric Reconstruction Problems, *CVPR, 2004*. [[Paper](https://www.robots.ox.ac.uk/~vgg/publications/2004/Hartley04b/hartley04b.pdf)] <!--  triangulation, translation+3d points  -->

- Multiple View Geometry and the $L_\infty$-Norm, *ICCV, 2005*. [[Paper](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=4709597f006ce58ee07043c7d140b8bb93df890f)] <!--  triangulation, camera resectioning and homography estimation  -->

- Quasiconvex Optimization for Robust Geometric Reconstruction, *TPAMI, 2007*. [[Paper](https://www.cs.cmu.edu/~ke/publications/quasiconvex-optimization-PAMI.pdf)] <!--  multi-view triangulation and sequential structure from motion and planar homography estimation  -->

- Multiple View Geometry Under the $L_\infty$-Norm, *TPAMI, 2008*. [[Paper](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=86e4bfa3dfdc371c9c77447d5577d44c6528a2ac)] <!--  triangulation, camera resectioning and homography estimation  -->

- Consensus Maximization with Linear Matrix Inequality Constraints, *CVPR, 2017*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Speciale_Consensus_Maximization_With_CVPR_2017_paper.pdf)] <!--  Similarity Transformation and Absolute Pose and Relative Pose  -->
