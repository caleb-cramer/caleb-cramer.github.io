---
layout: archive
title: "Projects"
permalink: /portfolio/
author_profile: false
mathjax: true
---

## ML/AI & Computational Projects

Below are my machine learning, computational, and research projects. Each includes links to the GitHub repository and technical details.

---

### Dueling Bandits for ATP Tennis

**Technologies:** Python, Jupyter Notebook, Online Learning Algorithms  
**GitHub:** [github.com/caleb-cramer/Dueling-Bandits-for-ATP-Tennis](https://github.com/caleb-cramer/Dueling-Bandits-for-ATP-Tennis)  
**Duration:** Course project, 2026   
**Course:** CSE 541 - Interactive Learning (University of Washington)

This project applies dueling bandit algorithms to professional tennis (ATP) match prediction and analysis. Using online learning techniques, the algorithm learns to predict match outcomes and player performance based on head-to-head comparisons.

**Key Results:**
- Implemented interactive learning algorithms for preference-based learning
- Applied dueling bandit framework to real-world sports data
- Demonstrates practical application of online learning to temporal prediction

**Technical Approach:**
- Dueling bandit algorithms for learning from pairwise comparisons
- Real-time prediction model that adapts to new match data
- Evaluation on ATP historical match records

---

### Wildfire Spread Modeling: Coupled Reaction-Diffusion-Convection System

**Technologies:** Python, Jupyter Notebook, Numerical Methods, PDEs  
**GitHub:** [github.com/caleb-cramer/581FinalProject](https://github.com/caleb-cramer/581FinalProject)  
**Duration:** Course project, 2025    
**Course:** AMATH 581 - Scientific Computing (University of Washington)

This project models wildfire spread using a coupled system of partial differential equations incorporating reaction, diffusion, and convection dynamics. The work bridges numerical analysis with real-world environmental applications.

**Key Results:**
- Developed and validated numerical schemes for coupled PDE systems
- Modeled physical fire propagation with environmental factors
- Applied high-order numerical methods for accuracy and stability
- Visualization of fire dynamics over time and space

**Technical Approach:**
- Finite difference and finite element methods
- Coupled reaction-diffusion-convection equations
- Stability analysis and convergence testing
- Scientific visualization of simulation results

---

### Staggered Designer Multistep Methods

**Technologies:** Python, MATLAB, Numerical Analysis, Scientific Computing  
**GitHub:** [github.com/caleb-cramer/staggered-multistep](https://github.com/caleb-cramer/staggered-multistep)  
**Duration:** Research project, 2021  
**Advisor:** Dr. Michelle Ghrist (University of Washington)  
**Course:** MATH 498A - Independent Research

Research focused on developing and analyzing staggered designer multistep methods for solving systems of differential equations. This work explores novel temporal discretization schemes with improved stability and accuracy properties.

**Key Results:**
- Developed new multistep method variants with enhanced stability regions
- Rigorous error analysis and convergence proofs
- Computational validation against established benchmarks
- Theoretical contributions to numerical ODE literature

**Technical Approach:**
- Linear multistep methods design and optimization
- Stability function analysis
- Order of accuracy investigation
- Application to stiff systems of equations

---

### Submarine Tracking via Spectral Filtering

**Technologies:** Signal Processing, 3D Fast Fourier Transform, Spectral Analysis   
**GitHub:** [https://github.com/caleb-cramer/Computational-Methods-Data-Analysis](https://github.com/caleb-cramer/Computational-Methods-Data-Analysis/tree/main/HW1)    
**Duration:** Course project, 2026  
**Course:** AMATH 582 - Advanced Computational Methods for Data Analysis

This project focuses on isolating and tracking a moving target's frequency signature from highly noisy 3D hydroacoustic sensor data. 



**Key Results:**
- Successfully decoupled the submarine's mechanical signature from heavy Gaussian white noise to reconstruct its precise 3D flight path.
- Improved computational efficiency from $O(N^2)$ to $O(N \log N)$.

**Technical Approach:**
- Transformed 4D spatial-temporal tensor data into the frequency domain utilizing a 3D Fast Fourier Transform (FFT).
- Designed and applied an adaptive Gaussian filter centered on the target's peak frequency.

---

### Multi-Resolution Edge Detection in Degraded Images

**Technologies:** Discrete Wavelet Transforms, Multi-Resolution Analysis, Image Processing  
**GitHub:** [https://github.com/caleb-cramer/Computational-Methods-Data-Analysis](https://github.com/caleb-cramer/Computational-Methods-Data-Analysis/tree/main/HW2)    
**Duration:** Course project, 2026  
**Course:** AMATH 582 - Advanced Computational Methods for Data Analysis

This project performs robust edge detection on digital images heavily degraded by varying levels of noise without losing structural boundaries. 



**Key Results:**
- Aggregated wavelet magnitudes across levels to reinforce strong edges and average out random noise.
- Significantly outperformed standard single-level analysis even under extreme noise conditions.

**Technical Approach:**
- Engineered a Multi-Resolution Analysis (MRA) pipeline utilizing Discrete Wavelet Transforms (DWT).
- Evaluated Haar, Daubechies (db2), and Coiflet (coif2) wavelet families across multiple decomposition scales.
- Optimized the pipeline via adaptive Garrote thresholding and Gaussian blurring.

---

### High-Dimensional Video Background Subtraction

**Technologies:** Randomized SVD, Low-Rank Approximation, Computer Vision   
**GitHub:** [https://github.com/caleb-cramer/Computational-Methods-Data-Analysis](https://github.com/caleb-cramer/Computational-Methods-Data-Analysis/tree/main/HW3)    
**Duration:** Course project, 2026  
**Course:** AMATH 582 - Advanced Computational Methods for Data Analysis

This project performs real-time background subtraction on video data where deterministic Singular Value Decomposition (SVD) is computationally prohibitive.



**Key Results:**
- Reduced algorithmic complexity from $O(mn^2)$ to $O(mn \log k)$, achieving a 120x computational speedup on test datasets.
- Visual analysis proved the randomized method maintained near-identical accuracy for separating the static background (low-rank structure) from moving foreground elements (sparse outliers).

**Technical Approach:**
- Implemented Randomized SVD (rSVD) using Gaussian random sampling to create a "sketch" of the input matrix's range before computing a low-rank approximation.

---

### Physicochemical Wine Quality Classification

**Technologies:** Machine Learning, Kernel Ridge Regression, Supervised Learning    
**GitHub:** [https://github.com/caleb-cramer/Computational-Methods-Data-Analysis](https://github.com/caleb-cramer/Computational-Methods-Data-Analysis/tree/main/HW4)    
**Duration:** Course project, 2026     
**Course:** AMATH 582 - Advanced Computational Methods for Data Analysis

This project classifies wine quality using 11 chemical features while navigating class imbalances and complex, non-linear feature relationships.

**Key Results:**
- Demonstrated that the L1-norm Laplacian Kernel model handled quality-grading outliers best, achieving the peak classification accuracy of 64.7%.
- Leveraged the linear Affine model as a baseline to extract highly interpretable correlation coefficients, mapping the exact impact of features like alcohol content and acidity on specific quality tiers.

**Technical Approach:**
- Developed a supervised learning framework evaluating an Affine (Linear) Regressor against Kernel Ridge Regression models.
- Utilized Radial Basis Function (RBF), Laplacian, and Polynomial kernels.
- Tuned hyperparameters via k-fold cross-validation.

---

### Spectral Clustering of Political Networks

**Technologies:** Spectral Clustering, Graph Theory, Semi-Supervised Learning   
**GitHub:** [https://github.com/caleb-cramer/Computational-Methods-Data-Analysis](https://github.com/caleb-cramer/Computational-Methods-Data-Analysis/tree/main/HW5)    
**Duration:** Course project, 2026      
**Course:** AMATH 582 - Advanced Computational Methods for Data Analysis

This project predicts the partisan affiliation of 435 U.S. House members based on categorical voting records—a topological space where standard K-Means clustering fails.



**Key Results:**
- The algorithm successfully mapped non-linear voting behaviors to predict the entire congressional divide with 88% accuracy using only a small seed of labeled data.

**Technical Approach:**
- Modeled the dataset as an interconnected network, utilizing a Gaussian distance metric to construct a Graph Laplacian.
- Computed the Fiedler vector to identify the structural bottleneck representing the partisan divide.
- Extended the unsupervised spectral clustering into a Semi-Supervised Learning (SSL) framework via Laplacian embedding.

---

### Machine Learning from Scratch

**Technologies:** Python, Jupyter Notebook, NumPy, Scikit-learn  
**GitHub:** [github.com/caleb-cramer/MLFinalProject](https://github.com/caleb-cramer/MLFinalProject)  
**Duration:** Course project, 2021  
**Course:** CPSC 322 - Intro to Machine Learning (Gonzaga University)

Implemented fundamental machine learning algorithms from scratch without relying on high-level ML libraries. This project demonstrates deep understanding of algorithm mechanics and computational implementation.

**Key Results:**
- Implemented core algorithms including decision trees, SVM, clustering methods
- Achieved competitive performance with library implementations
- Comprehensive documentation of algorithmic principles
- Performance analysis and optimization

**Technical Approach:**
- Manual implementation of classification and clustering algorithms
- Feature engineering and data preprocessing
- Cross-validation and hyperparameter tuning
- Comparative analysis of algorithm performance

---

### Rock-Paper-Scissors Win Predictor

**Technologies:** C++, Statistics, Pattern Recognition  
**GitHub:** [github.com/caleb-cramer/rps-machine](https://github.com/caleb-cramer/rps-machine)  
**Duration:** Personal project, 2018  

A competitive Rock-Paper-Scissors playing engine that exploits statistical patterns in opponent behavior. Inspired by the book "Rock Breaks Scissors," this project demonstrates practical pattern recognition and prediction techniques.

**Key Results:**
- Achieves statistical edge over random play through pattern exploitation
- Learns and adapts to opponent strategies in real-time
- Demonstrates practical application of statistical learning

**Technical Approach:**
- Opponent pattern analysis and statistical modeling
- Adaptive strategy selection
- Historical performance tracking

---

### DIVDR: Database Integration & Visualization

**Technologies:** Java, Database Systems  
**GitHub:** [github.com/caleb-cramer/224Project](https://github.com/caleb-cramer/224Project)  
**Duration:** Course project, 2021  
**Course:** CPSC 224 - Computer Systems II

Full-stack database application integrating data management with visualization capabilities.

---

## Areas of Focus

My project portfolio demonstrates expertise in:

- **Online Learning:** Algorithms that adapt and learn from streaming or sequential data
- **Numerical Analysis:** Efficient computational methods and numerical solution of differential equations
- **Computer Vision & ML:** Pattern recognition and data-driven learning systems
- **Scientific Computing:** High-performance numerical methods for physical systems
- **Systems Programming:** Low-level implementation and optimization

---

## Additional Work

Beyond the featured projects above, I have additional repositories covering:
- Mathematical research and proofs
- Course assignments and learnings
- Experimental implementations
- GIS and geospatial analysis projects

Check my [GitHub profile](https://github.com/caleb-cramer) for the complete collection.

---

## Technologies & Tools

**Languages:** Python, C++, Java, MATLAB, LaTeX  
**ML/Numerical:** PyTorch, TensorFlow, NumPy, SciPy, Scikit-learn  
**Tools:** Jupyter Notebook, Git, Linux, Azure, AWS, Docker, Snowflake, Databricks  
**Specializations:** Numerical methods, online learning, pattern recognition, scientific computing
