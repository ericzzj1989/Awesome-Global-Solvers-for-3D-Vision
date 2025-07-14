# Global Optimization for Multiple View Geometry [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)

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
      - [SDP ](#sdp)
      - [POP](#pop)
      - [RANSAC](#ransac)
      - [GNC](#gnc)
      - [Hybrid](#hybrid)
    - [Translation Averaging](#translation-averaging)
      - [Essential Matrix](#essential-matrix)
      - [Trifocal Tensor](#trifocal-tensor)
      - [Convex Relaxation](#convex-relaxation)
      - [Robust Estimation](#robust-estimation)
      - [Hybrid](#hybrid)
    - [Wahba Problem](#wahba-problem)
      - [Closed-form](#closed-form)
      - [BnB](#bnb)
      - [Convex Relaxation](#convex-relaxation)
      - [POP](#pop)
      - [RANSAC](#ransac)
      - [GNC](#gnc)
    - [Absolute Pose Estimation (PnP)](#absolute-pose-estimation-pnp)
      - [Analysis](#analysis)
      - [BnB](#bnb)
      - [SDP](#sdp)
      - [POP](#pop)
      - [GNC](#gnc)
    - [Relative Pose Estimation](#relative-pose-estimation)
      - [Minimal solvers](#minimal-solvers)
      - [BnB](#bnb)
      - [SDP](#sdp)
      - [POP](#pop)
      - [GNC](#gnc)
      - [Hybrid](#hybrid)
    - [3D Registration](#3d-registration)
      - [BnB](#bnb)
      - [SDP](#sdp)
      - [POP](#pop)
      - [GNC](#gnc)
    - [Pose Graph Optimization](#pose-graph-optimization)
      - [SDP](#sdp)
      - [GNC](#gnc)
    - [Triangulation](#triangulation)
      - [BnB](#bnb)
      - [SDP](#sdp)
      - [RANSAC](#ransac)
      - [Hybrid](#hybrid)
    - [Bundle Adjustment](#bundle-adjustment)
      - [SDP](#sdp)
    - [SLAM](#slam)
    - [All-in-One](#all-in-one)
      - [SDP](#sdp)

---
## Theory

### Bound-and-Branch (BnB)

### Semidefinite Programming (SDP)
- A convex relaxation to compute the nearest structured rank deficient matrix, *SIAM,2021*. [[Paper](https://epubs.siam.org/doi/abs/10.1137/19M1257640)]

### Polynomial Optimization (POP)

### Graduated Non-Convexity (GNC)

---
## Application

### Rotation Averaging

#### **Analysis**
- Combining Two-view Constraints For Motion Estimation, *CVPR, 2001*. [[Paper](https://ieeexplore.ieee.org/document/990963)]

#### **SDP**
- Global Motion Estimation from Point Matches, *3DIMPVT, 2012*. [[Paper](https://homes.cs.washington.edu/~kemelmi/sfm_3dimpvt12.pdf)]
  
- Simultaneous Multiple Rotation Averaging Using Lagrangian Duality, *ACCV, 2012*. [[Paper](https://scispace.com/pdf/simultaneous-multiple-rotation-averaging-using-lagrangian-1ecpzvpaw8.pdf)]

- Rotation Averaging and Strong Duality, *CVPR, 2018*. [[Paper](https://arxiv.org/pdf/1705.01362)]

#### **POP**
- Globally Optimal Estimates for Rotation Averaging Problems, *IHMSC, 2014*. [[Paper](https://ieeexplore.ieee.org/document/6911507)]

#### **RANSAC**
- Hierarchical RANSAC-Based Rotation Averaging, *SPL, 2020*. [[Paper](https://ieeexplore.ieee.org/document/9234640)]

- Revisiting Rotation Averaging: Uncertainties and Robust Losses, *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2303.05195)] [[Code](https://github.com/zhangganlin/GlobalSfMpy)]

#### **GNC**
- Pushing the Envelope of Rotation Averaging for Visual SLAM, *arXiv, 2020*. [[Paper](https://arxiv.org/pdf/2011.01163)]

- Adaptive Annealing for Robust Averaging, *ECCV, 2024*. [[Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/08834.pdf)]

#### **Hybrid**
- Shonan Rotation Averaging: Global Optimality by Surfing SO(p)^n, *ECCV, 2020*. [[Paper](https://arxiv.org/pdf/2008.02737)] [[Code](https://github.com/dellaert/ShonanAveraging)] [[Project Page](https://dellaert.github.io/ShonanAveraging/index.html)]

- Hybrid Rotation Averaging: A Fast and Robust Rotation Averaging Approach, *CVPR, 2021*. [[Paper](https://arxiv.org/pdf/2101.09116)] [[Code](https://github.com/ethz-asl/hybrid-rotation-averaging)]

##

### Translation Averaging

#### **Essential Matrix**
- Combining Two-view Constraints For Motion Estimation, *CVPR, 2001*. [[Paper](https://web.archive.org/web/20190307103302id_/http://pdfs.semanticscholar.org/dee5/b339cb49e4d7fef462a36c733b7ad8de28ca.pdf)]

#### **Trifocal Tensor**
- Recovering Camera Motion Using $l_{\infty}$ Minimization, *CVPR, 2006*. [[Paper](https://ieeexplore.ieee.org/document/1640890)]

- Exploiting Loops in the Graph of Trifocal Tensors for Calibrating a Network of Cameras, *ECCV, 2010*. [[Paper](https://imagine.enpc.fr/~monasse/Callisto/pdf/ECCV10Loop.pdf)]

- A Global Linear Method for Camera Pose Registration, *ICCV, 2013*. [[Paper](https://openaccess.thecvf.com/content_iccv_2013/papers/Jiang_A_Global_Linear_2013_ICCV_paper.pdf)]

- Global Fusion of Relative Motions for Robust, Accurate and Scalable Structure from Motion, *ICCV, 2013*. [[Paper](https://openaccess.thecvf.com/content_iccv_2013/papers/Moulon_Global_Fusion_of_2013_ICCV_paper.pdf)]

#### **Convex Relaxation**
- Robust Camera Location Estimation by Convex Programming, *CVPR, 2015*. [[Paper](https://arxiv.org/pdf/1412.0165)]

- Baseline Desensitizing in Translation Averaging, *CVPR, 2018*. [[Paper](https://arxiv.org/pdf/1901.00643)]

#### **Robust Estimation**
- Robust Global Translations with 1DSfM, *ECCV, 2014*. [[Paper](https://www.cs.cornell.edu/projects/1dsfm/docs/1DSfM_ECCV14.pdf)] [[Code](https://github.com/wilsonkl/SfM_Init)] [[Project Page](https://www.cs.cornell.edu/projects/1dsfm/)]

#### **Hybrid**
- Correspondence Reweighted Translation Averaging, *ECCV, 2022*. [[Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136930053.pdf)]

- Linear Global Translation Estimation with Feature Tracks, *BMVC, 2015*. [[Paper](https://arxiv.org/pdf/1503.01832)]

- Revisiting Global Translation Estimation with Feature Tracks, *CVPR, 2024*. [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Tao_Revisiting_Global_Translation_Estimation_with_Feature_Tracks_CVPR_2024_paper.pdf)]

## 

### Wahba Problem

#### **Closed-form**
- Fundamentals of spacecraft attitude determination and control
  
- Closed-form solution of absolute orientation using orthonormal matrices

- Attitude determination using vector observations and the singular value decomposition

- Least-squares fitting of two 3D point sets

- A generalized solution of the orthogonal procrustes problem

- Closed-form solution of absolute orientation using orthonormal matrices

#### **BnB**
- Global optimization through rotation space search, *IJCV, 2009*. [[Paper](https://users.cecs.anu.edu.au/~hartley/Papers/PDF/HartleyKahl:Ematrix.pdf)]

- Globally optimal consensus set maximization through rotation search, *ACCV, 2012*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-37444-9_42)]
 
- A polynomial-time bound for matching and registration with outliers, *CVPR, 2008*. [[Paper](https://ieeexplore.ieee.org/document/4587757)]
 
- Robust fitting for multiple view geometry, *ECCV, 2012*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-33718-5_53)]

#### **Convex Relaxation**
- A semidefinite relaxation-based algorithm for robust attitude estimation, *TSP, 2012*. [[Paper](https://ieeexplore.ieee.org/document/6203426)]

- A Quaternion-based Certifiably Optimal Solution to the Wahba Problem with Outliers, *ICCV 2019*. [[Paper](https://arxiv.org/pdf/1905.12536)][[Code](https://github.com/MIT-SPARK/TEASER-plusplus)]

- Semidefinite Relaxations of Truncated Least-Squares in Robust Rotation Search: Tight or Not, *ECCV, 2022*. [[Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136830655.pdf)]

- Towards Understanding The Semidefinite Relaxations of Truncated Least-Squares in Robust Rotation Search, *ECCV, 2022*. [[Paper](https://arxiv.org/pdf/2207.08350)]

#### **POP**
*(后续补充)*

#### **RANSAC**
- RANSIC: Fast and Highly Robust Estimation for Rotation Search and Point Cloud Registration Using Invariant Compatibility, *RAL, 2021*. [[Paper](https://arxiv.org/pdf/2104.09133)] [[Code](https://github.com/lukascher/RANSIC)]

#### **GNC**
- FracGM: A Fast Fractional Programming Technique for Geman-McClure Robust Estimator, *RAL, 2024*. [[Paper](https://arxiv.org/pdf/2409.13978)] [[Code](https://github.com/StephLin/FracGM)]

##

### Absolute Pose Estimation (PnP)

#### Analysis
- EPnP
 
- A simple, robust and fast method for the perspective-n-point problem, *PML,2018*. [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0167865518300692)]

- Upnp: An optimal o (n) solution to the absolute pose problem with universal applicability, *ECCV,2014*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-319-10590-1_9)]

- A universal, closed-form approach for absolute pose problems, *CVIU,2018*. [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1077314218300572)]

- FRPnP: Fast and robust absolute camera pose estimation with known focal length, *NCA,2017*. [[Paper](https://link.springer.com/article/10.1007/s00521-017-3032-6)]

- Minimal solution for uncalibrated absolute pose problem with a known vanishing point, *3DV,2013*. [[Paper](https://ieeexplore.ieee.org/abstract/document/6599070)]

- An efficient and accurate algorithm for the perspecitve-n-point problem, *IROS,2019*. [[Paper](https://ieeexplore.ieee.org/abstract/document/89684820)]

- Globally optimal dls method for pnp problem with cayley parameterization, *BMVC,2015*. [[Paper](https://www.researchgate.net/profile/Gaku-Nakano/publication/301451166_Globally_Optimal_DLS_Method_for_PnP_Problem_with_Cayley_parameterization/links/5e36c726a6fdccd965809503/Globally-Optimal-DLS-Method-for-PnP-Problem-with-Cayley-parameterization.pdf)]

- Absolute pose from one or two scaled and oriented features, *CVPR,2024*. [[Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Ventura_Absolute_Pose_from_One_or_Two_Scaled_and_Oriented_Features_CVPR_2024_paper.html)][[Code](https://github.com/danini/absolute-pose-from-oriented-and-scaled-features)]

- Revisiting the pnp problem: A fast, general and optimal solution, *ICCV,2013*. [[Paper](https://openaccess.thecvf.com/content_iccv_2013/html/Zheng_Revisiting_the_PnP_2013_ICCV_paper.html)]
  
- A versatile approach for solving pnp, pnpf, and pnpfr problems, *ECCV,2016*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-319-46487-9_21)]

#### BnB
- Absolute pose estimation with a known direction by motion decoupling, *TCSVT，2024*. [[Paper](https://ieeexplore.ieee.org/abstract/document/10093787)][[Code](https://github.com/Liu-Yinlong/algorithm-for-PnP-with-known-vertical-direction)]

#### SDP
- CvxPnPL: A unified convex solution to the absolute pose estimation problem from point and line correspondences, *JMIV,2023*. [[Paper](https://arxiv.org/abs/1907.10545)][[Code](https://github.com/SergioRAgostinho/cvxpnpl)]

- Globally optimal O(n) solution to the PnP problem for general camera models, *BMVC,2008*. [[Paper](https://bmva-archive.org.uk/bmvc/2008/papers/31.pdf)]

- Optimal and Robust Category-Level Perception: Object Pose and Shape Estimation From 2-D and 3-D Semantic Keypoints, *TRO,2023*. [[Paper](https://ieeexplore.ieee.org/abstract/document/10236506)][[Code](https://github.com/MIT-SPARK/PACE)]

#### POP
- The non-tightness of a convex relaxation to rotation recovery, *2021*. [paper](https://www.mdpi.com/1424-8220/21/21/7358)

- A consistently fast and globally optimal solution to the perspective-n-point problem, *ECCV,2020*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-58452-8_28)][[Code](https://github.com/terzakig/sqpnp)]
 
#### GNC
- Outliers rejection for robust camera pose estimation using graduated non‐convexity, *IET CV,2025*. [[Paper](https://www.researchgate.net/publication/387343981_Outliers_rejection_for_robust_camera_pose_estimation_using_graduated_non-convexity)]

### Relative Pose Estimation

#### Minimal solvers

- An efficient solution to the five-point relative pose problem, *TPAMI,2004*. [[Paper](https://ieeexplore.ieee.org/abstract/document/1288525)]

- Recent developments on direct relative orientation, *ISPRS,2006*. [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S092427160600030X)]

- Finding the exact rotation between two images independently of the translation, *ECCV,2012*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-33783-3_50)]

- In defence of the 8-point algorithm, *TPAMI,1997*. [[Paper](https://ieeexplore.ieee.org/abstract/document/601246)]

- Camera displacement via constrained minimizatio of the algebraic error, *TPAMI,2009*. [[Paper](https://ieeexplore.ieee.org/document/4731224)]

#### BnB

- Robust optimal pose estimation, *ECCV,2008*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-540-88682-2_12)]

- Two view geometry estimation with outliers, *BMVC,2009*. [[Paper](https://bmva-archive.org.uk/bmvc/2009/Papers/Paper431/Paper431.pdf)]

- Consensus set maximization with guaranteed global optimality for robust geometry estimation, *ICCV,2009*. [[Paper](https://ieeexplore.ieee.org/abstract/document/5459398)]

- Optimal essential matrix estimation via inlier-set maximization, *ECCV,2014*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-319-10590-1_8)]

- Optimal relative pose with unknown correspondences, *CVPR,2016*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2016/html/Fredriksson_Optimal_Relative_Pose_CVPR_2016_paper.html)]

- Direct optimization of frame-to-frame rotation, *ICCV,2013*. [[Paper](https://openaccess.thecvf.com/content_iccv_2013/html/Kneip_Direct_Optimization_of_2013_ICCV_paper.html)]

- Global optimization through rotation space search, *IJCV,2009*. [[Paper](https://link.springer.com/article/10.1007/s11263-008-0186-9)]


#### SDP

- Finding the exact rotation between two images independently of the translation, *ECCV,2012*,[[Paper](https://link.springer.com/chapter/10.1007/978-3-642-33783-3_50)]

- SDP relaxations for quadratic optimization problems derived from polynomial optimization problems, *APJOR，2010*,[[Paper](https://www.worldscientific.com/doi/abs/10.1142/S0217595910002533)]

- Globally optimal estimates for geometric reconstruction problems, *IJCV,2007*,[[Paper](https://link.springer.com/article/10.1007/s11263-006-0015-y)]

- A Certifiably Globally Optimal Solution to the Non-Minimal Relative Pose Problem, *CVPR, 2018*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2018/CameraReady/3968.pdf)]

- Robot-to-Robot Relative Pose Estimation based on Semidefinite Relaxation Optimization, *IROS, 2020*. [[Paper](https://freeformrobotics.org/wp-content/uploads/2022/02/IROS20_0234_FI.pdf)]

- Certifiable Relative Pose Estimation, *arXiv, 2020*, [[Paper](https://arxiv.org/pdf/2003.13732)]

- An Efficient Solution to Non-Minimal Case Essential Matrix Estimation, *TPAMI, 2022*. [[Paper](https://arxiv.org/pdf/1903.09067)] [[Code](https://github.com/jizhaox/npt-pose)]

- A Tighter Relaxation for the Relative Pose Problem Between Cameras, *JMIV, 2022*. [[Paper](https://mapir.isa.uma.es/papersrepo/2022/2022_mercedes_JMIV_tighter_rel_rpp_paper.pdf)] [[Code](https://github.com/mergarsal/TighterRPp)]

- From Correspondences to Pose: Non-minimal Certifiably Optimal Relative Pose without Disambiguation, *CVPR, 2024*. [[Paper](https://arxiv.org/pdf/2312.05995)] [[Code](https://github.com/javrtg/C2P)] [[Project Page](https://javrtg.github.io/C2P/)]

- Certifiably Optimal Rotation and Pose Estimation Based on the Cayley Map, *IJRR, 2025*. [[Paper](https://arxiv.org/pdf/2308.12418)]

#### POP

- SPLP: A Certifiably Globally Optimal Solution to the Relative Pose Estimation Problem Using Points and Line Pairs, *JIN,2022*. [[Paper](https://www.worldscientific.com/doi/abs/10.1142/S0219265921430453)]

#### GNC

- Fast and robust certifiable estimation of the relative pose between two calibrated cameras, *JMIV,2021*. [[Paper](https://link.springer.com/article/10.1007/s10851-021-01044-0)][[Code](https://github.com/mergarsal/FastCertRelPose.git)]
  
#### Hybrid

- Consensus maximization with linear matrix inequality constraints, *CVPR,2017*, [[Paper](https://openaccess.thecvf.com/content_cvpr_2017/html/Speciale_Consensus_Maximization_With_CVPR_2017_paper.html)]

##

### 3D Registration

- Fast Global Registration, *ECCV, 2016*. [[Paper](https://vladlen.info/papers/fast-global-registration.pdf)] [[Code](https://github.com/isl-org/FastGlobalRegistration)]

- SDRSAC: Semidefinite-Based Randomized Approach for Robust Point Cloud Registration without Correspondences, *2019, CVPR*, [[Paper](https://arxiv.org/pdf/1904.03483)] [[Code](https://github.com/intellhave/SDRSAC)]

#### BnB

- A polynomial-time bound for matching and registration with outliers, *CVPR,2008*. [[Paper](https://ieeexplore.ieee.org/abstract/document/4587757)]

- Go-icp: A globally optimal solution to 3d icp point-set registration, *TPAMI,2015*. [[Paper](https://ieeexplore.ieee.org/abstract/document/7368945)][[Code](https://github.com/yangjiaolong/Go-ICP)]

- Guaranteed Outlier Removal for Point Cloud Registration with Correspondences, *TPAMI, 2017*. [[Paper](https://arxiv.org/pdf/1711.10209)]

- PMC:A practical maximum clique algorithm for matching with pairwise constraints, **. [[Paper](https://ieeexplore.ieee.org/abstract/document/8107582)] <!-- Preprocessing for CMax/BnB, Deterministic Outlier Removal--> 
  
#### SDP

- Guided search consensus: Large scale point cloud registration by convex optimization, *ICIP, 2013*. [[Paper](https://ieeexplore.ieee.org/abstract/document/6738033)]

- Global Registration of Multiple Point Clouds Using Semidefinite Programming, *SIAM Journal on Optimization, 2015*. [[Paper](https://arxiv.org/pdf/1306.5226)]

- Non-Iterative Rigid 2D/3D Point-Set Registration Using Semidefinite Programming, *TIP, 2015*. [[Paper](https://arxiv.org/pdf/1501.00630)]

- Point Registration via Efficient Convex Relaxation, *TOG, 2016*. [[Paper](https://haggaim.github.io/projects/point_registration/PMSDP_final_light.pdf)] [[Code](https://github.com/Haggaim/PM-SDP)]

- Convex Global 3D Registration with Lagrangian Duality, *CVPR, 2017*. [[Paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Briales_Convex_Global_3D_CVPR_2017_paper.pdf)] [[Code](https://github.com/jbriales/CVPR17)]

- Global Optimality for Point Set Registration Using Semidefinite Programming, *CVPR, 2020*. [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Iglesias_Global_Optimality_for_Point_Set_Registration_Using_Semidefinite_Programming_CVPR_2020_paper.pdf)]

- TEASER: Fast and Certifiable Point Cloud Registration, *TRO, 2020*. [[Paper](https://arxiv.org/pdf/2001.07715)] [[Code](https://github.com/MIT-SPARK/TEASER-plusplus)]

- GlobalPointer: Large-Scale Plane Adjustment with Bi-Convex Relaxation, *ECCV, 2024*. [[Paper](https://arxiv.org/pdf/2407.13537)] [[Code](https://github.com/WU-CVGL/GlobalPointer)] [[Project Page](https://bangyan101.github.io/GlobalPointer/)]

#### POP
- a novel quaternion-based 2d-3d registration algorithm with line correspondence, *TIJEE,2014*. [[Paper](https://journal.esperg.com/index.php/TIJEE/article/view/3203)]
- Geometry of 3d environments and sum of squares polynomials, *arxiv,2016*. [[Paper](https://arxiv.org/abs/1611.07369)]<!--Geometric Representation with POP -->
- Robust and optimal registration of image sets and structured scenes via sum-of-squares polynomials[[Paper](https://link.springer.com/article/10.1007/s11263-018-1114-2)]
  
#### GNC

- Practical, fast and robust point cloud registration for 3d scene stitching and object localization, *ACCESS,2021*. [[Paper](https://ieeexplore.ieee.org/abstract/document/9667465)]

- Pyramid Semantic Graph-based Global Point Cloud Registration with Low Overlap, *IROS, 2023*. [[Paper](https://arxiv.org/pdf/2307.12116)] [[Code](https://github.com/HKUST-Aerial-Robotics/Pagor)]

##

### Pose Graph Optimization

#### BnB
*(To be supplemented)*
#### SDP

- Lagrangian Duality in Complex Pose Graph Optimization, *SOIA, 2016*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-319-42056-1_5)]

- Initialization of 3D Pose Graph Optimization Using Lagrangian Duality, *ICRA, 2017*. [[Paper](https://mapir.isa.uma.es/jbriales/publications/ICRA17+supp.pdf)]

- Convex Relaxations for Pose Graph Optimization With Outliers, *RAL, 2018*. [[Paper](https://arxiv.org/pdf/1801.02112)] 

- Efficient and Guaranteed Planar Pose Graph Optimization Using Complex Representation, *2019*. [[Paper](https://ieeexplore.ieee.org/abstract/document/8968044)][[Code](https://github.com/fantaosha/CPL-Sync)]

- Distributed Certifiably Correct Pose-Graph Optimization, *TRO, 2019*. [[Paper](https://arxiv.org/pdf/1911.03721)] [[Code](https://github.com/mit-acl/dpgo)]

- Pose Graph Optimization in the Complex Domain: Lagrangian Duality, Conditions For Zero Duality Gap, and Optimal Solutions, *arxiv 2015*. [[Paper](https://arxiv.org/abs/1505.03437)][[Code](https://github.com/alpErenSari/poseGraphProject)]

#### POP
*(To be supplemented)*

#### GNC

- Efficient Graduated Non-Convexity for Pose Graph Optimization, *ICCAS,2024*, [[Paper](https://ieeexplore.ieee.org/abstract/document/10773072)][[Code](https://github.com/SNU-DLLAB/EGNC-PGO)]

- Adaptive Graduated Non-Convexity for Pose Graph Optimization, *IROS Workshop, 2023*. [[Paper](https://arxiv.org/pdf/2308.11444)] [[Code](https://github.com/SNU-DLLAB/AGNC-PGO)]

- A Decoupled and Linear Framework for Global Outlier Rejection over Planar Pose Graph, *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2209.08543)]

##

### Triangulation

#### BnB

- A Fast Optimal Algorithm for L 2 Triangulation, *ACCV,2007*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-540-76390-1_28)]

- On triangulation algorithms in large scale camera network systems, *ACC,2012*. [[Paper](https://ieeexplore.ieee.org/abstract/document/6315278)]

- An exact algorithm for the minimum dilation triangulation problem(2017)[[Paper](https://link.springer.com/article/10.1007/s10898-017-0517-x)]
  
#### SDP

- A qcqp approach to triangulation, *ECCV,2012*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-642-33718-5_47)][[Code](https://github.com/linusnie/robust-triangulation-relaxations)]

- Semidefinite Relaxations for Robust Multiview Triangulation, *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2301.11431)] [[Code](https://github.com/Linusnie/robust-triangulation-relaxations)]

- Triangulation of points, lines and conics, *JMIV, 2008*. [[Paper](https://lucris.lub.lu.se/ws/portalfiles/portal/2621089/1245431.pdf)]

- Robust multiview L2 triangulation via optimal inlier selection and 3D structure refinement, *PR,2014*. [[Paper](https://www.sciencedirect.com/science/article/pii/S0031320314001204)]<!-- Numerical Optimization (DE), SOCP Bound Analysis-->

#### POP
*(To be supplemented)*

#### GNC
*(To be supplemented)*

#### RANSAC

- Robust uncertainty-aware multiview triangulation, *arxiv,2008*. [[Paper](https://arxiv.org/abs/2008.01258)]

#### Hybrid

- A Triangulation Method Based on minmaxKKT, *2012*. [[Paper](https://pure.nwpu.edu.cn/en/publications/a-triangulation-method-based-on-minmaxkkt)]

##

### Bundle Adjustment

#### SDP

- Building Rome with Convex Optimization, *RSS, 2025*. [[Paper](https://arxiv.org/pdf/2502.04640)] [[Code](https://github.com/ComputationalRobotics/XM-code)] [[Project Page](https://computationalrobotics.seas.harvard.edu/XM/)]

##

### SLAM

- Certifiably Correct Range-Aided SLAM, *TRO, 2024*. [[Paper](https://arxiv.org/pdf/2302.11614)] [[Code](https://github.com/MarineRoboticsGroup/cora)]

- Distributed Certifiably Correct Range-Aided SLAM, *ICRA, 2025*. [Paper](https://arxiv.org/pdf/2503.03192) [[Code](https://github.com/adthoms/dcora)]

##

### All-in-One

#### SDP

- One Ring to Rule Them All: Certifiably Robust Geometric Perception with Outliers, *NeurIPS, 2020*. [[Paper](https://arxiv.org/pdf/2006.06769)] [[Code](https://github.com/MIT-SPARK/CertifiablyRobustPerception)]

- Certifiably Optimal Outlier-Robust Geometric Perception: Semidefinite Relaxations and Scalable Global Optimization, *TPAMI, 2022*. [[Paper](https://arxiv.org/pdf/2109.03349)] [[Code](https://github.com/MIT-SPARK/CertifiablyRobustPerception)]
