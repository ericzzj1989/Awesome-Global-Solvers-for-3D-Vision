# Global-Optimization-for-Multiple-View-Geometry
This is the official repository of **A Survey of Global Optimization for Geometric Perception: Theory and Application**, a comprehensive survey of recent progress in Global Optimization for multiple view geometry. For details, please refer to:


# Framework
[Applications]

## Applications
### Rotation Averaging
#### Analysis
- Combining two-view constraints for motion estimation(CVPR,2001)[[paper]](https://ieeexplore.ieee.org/document/990963)
#### SDP
- Global Motion Estimation from Point Matches(3DIMPVT,2012)[[paper]](https://ieeexplore.ieee.org/document/6374980)
- Simultaneous multiple rotation averaging using Lagrangian duality(ACCV,2012)[[paper]](https://link.springer.com/chapter/10.1007/978-3-642-37431-9_19)
- Rotation Averaging and Strong Duality(CVPR,2018)[[paper]](https://ieeexplore.ieee.org/document/8578119)
#### GNC
#### Hybrid
- Shonan Rotation Averaging: Global Optimality by Surfing SO(p)^n(ECCV,2020)[[paper]](https://arxiv.org/abs/2008.02737)
- Hybrid Rotation Averaging:A Fast and Robust Rotation Averaging Approach(CVPR,2021)[[paper]](https://arxiv.org/abs/2101.09116)

### Translation Averaging
#### Essential Matrix based Methods
- Combining two-view constraints for motion estimation(CVPR,2001)[[paper]](https://ieeexplore.ieee.org/document/990963)
#### Trifocal Tensor based Methods
- Global Motion Estimation from Point Matches(3DIMPVT,2012)[[paper]](https://ieeexplore.ieee.org/document/6374980)
- Exploiting loops in the graph of trifocal tensors for calibrating a network of cameras
- A global linear method for camera pose registration
- Global fusion of relative motions for robust, accurate and scalable structure from motion
- Recovering camera motion using $l_{\infty}$ minimization
#### Convex Relaxation
- Robust camera location estimation by convex programming
#### Robust Estimation
- 1DSfM:Robust Global Translations with 1DSfM(ECCV,2014)[[paper]](https://www.cs.cornell.edu/projects/1dsfm/)
- IRLS
- RANSAC based
#### Hybrid
- Correspondence Reweighted Translation Averaging(ECCV,2022)[[paper]](https://link.springer.com/chapter/10.1007/978-3-031-19827-4_4)
- Linear Global Translation Estimation with Feature Tracks(CVPR,2015)[[paper]](https://arxiv.org/abs/1503.01832)

### Wahba Problem
#### Closed-form solution
- Fundamentals of spacecraft attitude determination and control
- Closed-form solution of absolute orientation using orthonormal matrices
- Attitude determination using vector observations and the singular value decomposition
- Least-squares fitting of two 3D point sets
- A generalized solution of the orthogonal procrustes problem
- Closed-form solution of absolute orientation using orthonormal matrices
#### Global Methods:CMax & BnB & Convex_Relaxation
- GORE:
👇**BnB**
- Global optimization through rotation space search
- Globally optimal consensus set maximization through rotation search
- A polynomialtime bound for matching and registration with outliers
- Robust fitting for multiple view geometry
👇**Convex_Relaxation**
- Convex Global 3D Registration with Lagrangian Duality
- A semidefinite relaxation-based algorithm for robust attitude estimation
- A Quaternion-based Certifiably Optimal Solution to the Wahba Problem with Outliers(ICCV,2019)
### Absolute Pose Estimation (PnP)
- EPnP
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
- A certifiably globally optimal solution to the non-minimal relative pose problem(CVPR,2018)
- SDP relaxations for quadratic optimization problems derived from polynomial optimization problems(2010)
- Globally optimal estimates for geometric reconstruction problems(2007)
👇**BnB**
- Robust optimal pose estimation(ECCV,2008)
- Two view geometry estimation with outliers(BMVC,2009)
- Consensus set maximization with guaranteed global optimality for robust geometry estimation(ICCV,2009)
- Optimal essential matrix estimation via inlier-set maximization(ECCV,2014)
- Optimal relative pose with unknown correspondences(CVPR,2016)
- Direct optimization of frame-to-frame rotation(ICCV,2013)
- Global optimization through rotation space search(IJCV,2009)
👇**Hybrid**
- Consensus maximization with linear matrix inequality constraints(CVPR,2017)
### 3D Registration
- TEASER: Fast and Certifiable Point Cloud Registration(TRO,2020)

### Pose Graph Optimization

### Triangulation
