# Matrix computation and numerical methods — ICML 2026 / ICLR 2026 / NeurIPS 2025

186 accepted papers: 51 ICLR 2026, 65 ICML 2026, 70 NeurIPS 2025. Updated 2026-09-24.

The catalog separates direct deep-learning applications, general ML, theoretical foundations and scientific computing. X9 includes adjacent numerical primitives beyond matrix algebra. Each entry records the computed quantity, computational idea, qualification and primary-source links. Most entries are supported by the accepted abstract; targeted full-text checks are marked.

| Category | Papers |
|---|---:|
| X1 — Matrix functions, roots and matrix geometry | 13 |
| X2 — Eigenproblems, spectral computation and SVD analysis | 17 |
| X3 — Fisher, Hessian, derivatives and implicit differentiation | 33 |
| X4 — Randomized sketching and kernel approximations | 16 |
| X5 — Attention, state-space algebra and parallel scans | 36 |
| X6 — Matrix and tensor methods for compression | 30 |
| X7 — Structured products, transforms and GPU kernels | 17 |
| X8 — Linear systems, sparse solvers and Gaussian processes | 15 |
| X9 — Related numerical primitives and computation | 9 |

## X1 — Matrix functions, roots and matrix geometry

### Back to Square Roots: An Optimal Bound on the Matrix Factorization Error for Multi-Epoch Differentially Private SGD

**ICLR 2026 · Accept (Poster)** · Nikita Kalinin; Ryan McKenna; Jalaj Upadhyay; Christoph Lampert

[OpenReview](<https://openreview.net/forum?id=EEr6cADbZx>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010697>) · [PDF](<https://openreview.net/pdf?id=EEr6cADbZx>)

**Categories:** X1 — Matrix functions, roots and matrix geometry.

**Quantity:** Correlated-noise matrix factorization for multi-epoch DP-SGD.

**Computational idea:** Use a banded inverse square-root factorization with a tight asymptotic error characterization.

**Scope:** Deep learning. **Qualification:** Privacy mechanism factorization, rather than a general optimizer preconditioner.

**Evidence:** Official accepted-paper title and abstract.

### Fast and Stable Riemannian Metrics on SPD Manifolds via Cholesky Product Geometry

**ICLR 2026 · Accept (Poster)** · Ziheng Chen; Yue Song; Xiaojun Wu; Nicu Sebe

[OpenReview](<https://openreview.net/forum?id=5S8ruWKe8l>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011463>) · [PDF](<https://openreview.net/pdf?id=5S8ruWKe8l>)

**Categories:** M5 — Supporting geometry, statistics, and training-dynamics papers; X1 — Matrix functions, roots and matrix geometry.

**Quantity:** Riemannian operators on SPD matrices.

**Computational idea:** Use Cholesky product geometry to construct fast metrics with closed-form operators for SPD neural networks.

**Scope:** Deep learning. **Qualification:** Changes the chosen metric; not a universal acceleration of every existing SPD metric.

**Manifold relevance:** PCM and BWCM supply fast, stable closed-form geometric operators for SPD networks and classifiers; useful optimization infrastructure, not primarily an optimizer paper.

**Geometry:** SPD matrices via Cholesky product geometry. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/GitZH-Chen/PCM_BWCM.>). Links extracted from the accepted abstract; code was not tested.

### The Polar Express: Optimal Matrix Sign Methods and their Application to the Muon Algorithm

**ICLR 2026 · Accept (Oral)** · Noah Amsel; David Persson; Christopher Musco; Robert M. Gower

[OpenReview](<https://openreview.net/forum?id=yRtgZ1K8hO>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006553>) · [PDF](<https://openreview.net/pdf?id=yRtgZ1K8hO>)

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X1 — Matrix functions, roots and matrix geometry.

**Quantity:** Polar factor and matrix sign for Muon.

**Computational idea:** Use matrix-multiplication-only polynomial iterations with minimax-designed coefficients and finite-precision stabilization.

**Scope:** Deep learning. **Qualification:** Optimality refers to the paper's polynomial/minimax setting; finite iterations approximate the polar factor.

**Optimizer relevance:** Polar Express computes matrix polar factors with GPU-friendly polynomial iterations and finite-precision safeguards; improves the orthogonalization subroutine used by Muon.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2505.16932v4>): Sections 3.2-3.3; minimax polynomial design and singular-value interval selection. The interval-based optimality claim is more specific than universal optimality over all matrix algorithms.

### DASH: Faster Shampoo via Batched Block Preconditioning and Efficient Inverse-Root Solvers

**ICML 2026 · Accept (regular)** · Ionut-Vlad Modoranu; Philip Zmushko; Erik Schultheis; Mher Safaryan; Dan Alistarh

[OpenReview](<https://openreview.net/forum?id=ujeyxKwTGM>) · [Official program](<https://icml.cc/virtual/2026/poster/60988>) · [PDF](<https://openreview.net/pdf?id=ujeyxKwTGM>)

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X1 — Matrix functions, roots and matrix geometry.

**Quantity:** Shampoo inverse-root preconditioners.

**Computational idea:** Batch preconditioner blocks into tensors; use Newton-DB iteration and Chebyshev approximations for inverse roots.

**Scope:** Deep learning. **Qualification:** Accuracy and convergence depend on scaling, damping and solver choice.

**Optimizer relevance:** DASH accelerates Distributed Shampoo through batched preconditioner blocks and faster inverse-root algorithms; directly relevant to practical structured preconditioning.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2602.02016v1>): Sections 2-4 and Appendix A; batched blocks, Newton-Denman-Beavers, scaling and Chebyshev inverse roots. Preprint v1 reports different headline timing from the accepted abstract; the catalog deliberately does not merge these speedup figures.

**Code links listed by authors:** [Repository](<https://github.com/IST-DASLab/DASH.>). Links extracted from the accepted abstract; code was not tested.

### FOAM: Frequency and Operator-Error Based Adaptive Damping Method for Reducing Staleness-Oriented Error for Shampoo

**ICML 2026 · Accept (regular)** · Kyunghun Nam; Sumyeong Ahn

[OpenReview](<https://openreview.net/forum?id=ZwFJbTzJP9>) · [Official program](<https://icml.cc/virtual/2026/poster/63117>) · [PDF](<https://openreview.net/pdf?id=ZwFJbTzJP9>)

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X1 — Matrix functions, roots and matrix geometry.

**Quantity:** Stale Shampoo preconditioners.

**Computational idea:** Adapt damping and eigendecomposition frequency using an estimate of operator error from stale preconditioners.

**Scope:** Deep learning. **Qualification:** Controls a computation-versus-staleness trade-off; does not eliminate matrix decompositions entirely.

**Optimizer relevance:** Adaptive damping and eigendecomposition frequency address errors from stale Shampoo preconditioners. This FOAM differs from the state-folding FOAM in group D.

**Evidence:** Official accepted-paper title and abstract.

### PRISM: Distribution-free Adaptive Computation of Matrix Functions for Accelerating Neural Network Training

**ICML 2026 · Accept (regular)** · Shenghao Yang; Zhichao Wang; Oleg Balabanov; N. Benjamin Erichson; Michael Mahoney

[OpenReview](<https://openreview.net/forum?id=hwhvjhXC0m>) · [Official program](<https://icml.cc/virtual/2026/poster/62288>) · [PDF](<https://openreview.net/pdf?id=hwhvjhXC0m>)

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X1 — Matrix functions, roots and matrix geometry.

**Quantity:** Matrix roots, inverse roots and polar factors.

**Computational idea:** Fit iteration polynomials to the current spectrum through randomized sketched least squares; use matrix multiplications for the main iteration.

**Scope:** Deep learning. **Qualification:** Iterative approximation; no explicit spectral bounds required by the proposed fitting scheme.

**Optimizer relevance:** PRISM combines adaptive polynomial approximation with randomized sketching to accelerate matrix functions used by Shampoo and Muon.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2601.22137v1>): Sections 3-5; adaptive polynomial fitting, randomized sketching, and supported matrix functions. Preprint version v1; accepted title and venue are taken from the official conference program.

### A Stable Whitening Optimizer for Efficient Neural Network Training

**NeurIPS 2025 · Accept (poster)** · Kevin Frans; Sergey Levine; Pieter Abbeel

[OpenReview](<https://openreview.net/forum?id=0T8i3uXq3O>) · [Official program](<https://neurips.cc/virtual/2025/poster/120317>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/fe722dac731f46d30b043c6b0db9a3ef-Paper-Conference.pdf>)

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X1 — Matrix functions, roots and matrix geometry.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/fe722dac731f46d30b043c6b0db9a3ef-Abstract-Conference.html>)

**Quantity:** Whitened and normalized matrix-gradient updates.

**Computational idea:** SPlus reuses a historical Shampoo eigenbasis and normalizes current gradients in that basis.

**Scope:** Deep learning. **Qualification:** Cached eigenbases and bounded updates define a particular optimizer; they are not exact inversion of the current full Hessian.

**Optimizer relevance:** SPlus combines cached Shampoo eigenbases with current-gradient normalization, shape-aware scaling and iterate averaging to stabilize language-model training.

**Evidence:** Official accepted-paper title and abstract.

### Perturbation Bounds for Low-Rank Inverse Approximations under Noise

**NeurIPS 2025 · Accept (poster)** · Phuc Tran; Nisheeth K. Vishnoi

[OpenReview](<https://openreview.net/forum?id=bPNzBXl1n7>) · [Official program](<https://neurips.cc/virtual/2025/poster/117183>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/953d276d037e701fcd97dbb34ebb2394-Paper-Conference.pdf>)

**Categories:** X1 — Matrix functions, roots and matrix geometry.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/953d276d037e701fcd97dbb34ebb2394-Abstract-Conference.html>)

**Quantity:** Noise sensitivity of truncated inverse approximations.

**Computational idea:** Contour-integral analysis of reciprocal spectral functions gives refined bounds for low-rank inverse perturbations.

**Scope:** Theory / foundations. **Qualification:** A theory contribution, not a faster inverse algorithm; spectral gaps and noise alignment qualify the estimates.

**Evidence:** Official accepted-paper title and abstract.

### PoLAR: Polar-Decomposed Low-Rank Adapter Representation

**NeurIPS 2025 · Accept (poster)** · Kai Lion; Liang Zhang; Bingcong Li; Niao He

[OpenReview](<https://openreview.net/forum?id=jDxFD45kkc>) · [Official program](<https://neurips.cc/virtual/2025/poster/116485>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/db79b6c50430a52fbab9d63efb8433ca-Paper-Conference.pdf>)

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; M2 — Manifold-based LLM training and low-rank adaptation; X1 — Matrix functions, roots and matrix geometry.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/db79b6c50430a52fbab9d63efb8433ca-Abstract-Conference.html>)

**Quantity:** Geometrically separated low-rank directions and scales.

**Computational idea:** PoLAR uses a polar-inspired three-factor representation and Riemannian updates for orthonormal factors.

**Scope:** Deep learning. **Qualification:** A fine-tuning parameterization; it is not a new general-purpose polar-decomposition solver.

**Optimizer relevance:** PoLAR uses two orthonormal factors and a scale factor with Riemannian optimization for parameter-efficient fine-tuning.

**Manifold relevance:** PoLAR uses a polar-inspired low-rank parameterization and Riemannian factor updates for fine-tuning.

**Geometry:** Two Stiefel factors with a separate scale. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### Purifying Shampoo: Investigating Shampoo's Heuristics by Decomposing its Preconditioner

**NeurIPS 2025 · Accept (spotlight)** · Runa Eschenhagen; Aaron Defazio; Tsung-Hsien Lee; Richard Turner; Hao-Jun Shi

[OpenReview](<https://openreview.net/forum?id=kePsKwxvaV>) · [Official program](<https://neurips.cc/virtual/2025/poster/116361>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/f14f4eda29a74c02c803699a09529bb9-Paper-Conference.pdf>)

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics; X1 — Matrix functions, roots and matrix geometry.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/f14f4eda29a74c02c803699a09529bb9-Abstract-Conference.html>)

**Quantity:** Shampoo eigenbasis and inverse-root preconditioning.

**Computational idea:** Separates eigenvalue adaptation from eigenbasis estimation and schedules eigendecompositions using an error criterion motivated by warm-started QR.

**Scope:** Deep learning. **Qualification:** The criterion supports both QR and eigendecomposition; the reported adaptive eigh implementation was faster than the tested QR variants. This remains a structured preconditioner.

**Optimizer relevance:** Purifying Shampoo separates eigenvalue and eigenbasis adaptation, removes grafting through eigenvalue correction, and adaptively schedules eigenbasis updates.

**Training dynamics relevance:** Purifying Shampoo separates eigenvalue and eigenbasis adaptation, removes grafting through eigenvalue correction, and adaptively schedules eigenbasis updates.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Grafting; eigenvalue adaptation; eigenbasis refresh frequency.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://proceedings.neurips.cc/paper_files/paper/2025/file/f14f4eda29a74c02c803699a09529bb9-Paper-Conference.pdf>): Sections 4.1–4.2, equation (11), pages 6–7. The eigenbasis-error criterion can skip eigendecompositions. Adaptive eigh was faster than the tested warm-started QR variants on the reported workload; speed is not a universal QR advantage.

### Revitalizing SVD for Global Covariance Pooling: Halley’s Method to Overcome Over-Flattening

**NeurIPS 2025 · Accept (poster)** · Jiawei Gu; Ziyue Qiao; Xinming Li; Zechao Li

[OpenReview](<https://openreview.net/forum?id=fqpbXJ2QtC>) · [Official program](<https://neurips.cc/virtual/2025/poster/116798>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1292cf2ff215e3c857c34c32336413a5-Paper-Conference.pdf>)

**Categories:** X1 — Matrix functions, roots and matrix geometry.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/1292cf2ff215e3c857c34c32336413a5-Abstract-Conference.html>)

**Quantity:** Matrix power normalization and stable SVD derivatives for covariance pooling.

**Computational idea:** Halley-SVD combines higher-order iteration with a stabilized backward treatment to address spectral over-flattening.

**Scope:** Deep learning. **Qualification:** Designed for covariance-pooling layers; finite numerical iterations and stabilized derivatives require separate accuracy assessment.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1292cf2ff215e3c857c34c32336413a5-Paper-Conference.pdf>): Sections 3.2–3.4, equations (7)–(8), pages 5–6. The reported layer iterates a covariance square-root approximation and differentiates through the iterations, avoiding explicit inverse eigenvalue-gap factors. This passage check does not independently validate the iteration or claimed convergence rate.

### Riemannian Flow Matching for Brain Connectivity Matrices via Pullback Geometry

**NeurIPS 2025 · Accept (poster)** · Antoine Collas; Ce Ju; Nicolas Salvy; Bertrand Thirion

[OpenReview](<https://openreview.net/forum?id=NY3LzmUXl7>) · [Official program](<https://neurips.cc/virtual/2025/poster/118350>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/5616112a0120c15bf7d47a6bccc21bc3-Paper-Conference.pdf>)

**Categories:** M4 — Related constrained and geometry-aware optimization; X1 — Matrix functions, roots and matrix geometry.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/5616112a0120c15bf7d47a6bccc21bc3-Abstract-Conference.html>)

**Quantity:** Flow-matching computations on SPD and correlation matrices.

**Computational idea:** DiffeoCFM uses matrix diffeomorphisms and pullback metrics to transform geometric flow matching into Euclidean computations.

**Scope:** Deep learning. **Qualification:** Equivalence is tied to the selected diffeomorphism and pullback metric, not every canonical matrix-manifold metric.

**Manifold relevance:** DiffeoCFM transports matrix-manifold flow matching through diffeomorphisms so that the training objective can be implemented in Euclidean coordinates.

**Geometry:** SPD and correlation matrices with pullback geometry. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/antoinecollas/DiffeoCFM>). Links extracted from the accepted abstract; code was not tested.

### SUMO: Subspace-Aware Moment-Orthogonalization for Accelerating Memory-Efficient LLM Training

**NeurIPS 2025 · Accept (poster)** · Yehonathan Refael; Guy Smorodinsky; Tom Tirer; Ofir Lindenbaum

[OpenReview](<https://openreview.net/forum?id=DIjRvEKOeG>) · [Official program](<https://neurips.cc/virtual/2025/poster/119226>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/d85a66edadd443ac2350e93c0287f4f9-Paper-Conference.pdf>)

**Categories:** D — Memory-efficient and low-precision optimizers; X1 — Matrix functions, roots and matrix geometry.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/d85a66edadd443ac2350e93c0287f4f9-Abstract-Conference.html>)

**Quantity:** Orthogonalized gradient updates in a tracked subspace.

**Computational idea:** SUMO computes an SVD in a low-dimensional adaptive subspace to reduce matrix orthogonalization cost.

**Scope:** Deep learning. **Qualification:** Orthogonalization is exact within the selected subspace, not the full ambient gradient space.

**Optimizer relevance:** SUMO performs exact SVD orthogonalization within an adaptive low-dimensional gradient subspace to reduce the cost of Muon-style updates.

**Evidence:** Official accepted-paper title and abstract.


## X2 — Eigenproblems, spectral computation and SVD analysis

### Accelerating Eigenvalue Dataset Generation via Chebyshev Subspace Filter

**ICLR 2026 · Accept (Poster)** · Hong Wang; Jie Wang; Jian Luo; huanshuo dong; Yeqiu Chen; Runmin Jiang; Zhen Huang

[OpenReview](<https://openreview.net/forum?id=rrbCQT7JKX>) · [Official program](<https://iclr.cc/virtual/2026/poster/10007112>) · [PDF](<https://openreview.net/pdf?id=rrbCQT7JKX>)

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

**Quantity:** Eigenpairs for related operators.

**Computational idea:** Sort operators using truncated FFT features; reuse previous eigenpairs through Chebyshev subspace filtering.

**Scope:** Scientific computing. **Qualification:** Targets eigenvalue dataset generation across a sequence of related problems.

**Evidence:** Official accepted-paper title and abstract.

### EigenScore: OOD Detection using Posterior Covariance in Diffusion Models

**ICLR 2026 · Accept (Poster)** · Shirin Shoushtari; Yi Wang; Xiao Shi; Salman Asif; Ulugbek Kamilov

[OpenReview](<https://openreview.net/forum?id=Dq64kthckN>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010743>) · [PDF](<https://openreview.net/pdf?id=Dq64kthckN>)

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

**Quantity:** Leading posterior-covariance eigenvalues in diffusion models.

**Computational idea:** Use Jacobian-free subspace iteration with forward denoiser evaluations for an OOD score.

**Scope:** Deep learning. **Qualification:** Iterative eigenvalue estimates; OOD performance is empirical.

**Evidence:** Official accepted-paper title and abstract.

### Falcon: Fast Proximal Linearization of Normalized Cuts for Unsupervised Image Segmentation

**ICLR 2026 · Accept (Poster)** · Xiao Zhang; Xiangyu Han; Xiwen Lai; Yao Sun; Pei Zhang; Xia Liu; Konrad P Kording

[OpenReview](<https://openreview.net/forum?id=PvWHzAf9qp>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009636>) · [PDF](<https://openreview.net/pdf?id=PvWHzAf9qp>)

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

**Quantity:** Discrete multiway normalized-cut assignments.

**Computational idea:** Replace repeated spectral relaxation/eigendecomposition with closed-form gradient scores and proximal one-hot updates.

**Scope:** General ML. **Qualification:** A different optimization formulation; convergence claims use stated assumptions.

**Evidence:** Official accepted-paper title and abstract.

### Sublinear Spectral Clustering Oracle with Little Memory

**ICLR 2026 · Accept (Poster)** · Ranran Shen; Xiaoyi Zhu; Pan Peng; Zengfeng Huang

[OpenReview](<https://openreview.net/forum?id=0GpolO2auw>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011950>) · [PDF](<https://openreview.net/pdf?id=0GpolO2auw>)

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

**Quantity:** Spectral cluster membership queries.

**Computational idea:** Build a compact clustering oracle with a tunable memory-query-time trade-off.

**Scope:** Theory / foundations. **Qualification:** Guarantees assume well-clusterable graphs and a specified query model.

**Evidence:** Official accepted-paper title and abstract.

### SVD Provably Denoises Nearest Neighbor Data

**ICLR 2026 · Accept (Poster)** · Ravindran Kannan; Kijun Shin; David Woodruff

[OpenReview](<https://openreview.net/forum?id=N1kiOll2EN>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009900>) · [PDF](<https://openreview.net/pdf?id=N1kiOll2EN>)

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

**Quantity:** Denoised nearest neighbors.

**Computational idea:** Project through SVD under a low-dimensional-subspace plus Gaussian-noise model.

**Scope:** Theory / foundations. **Qualification:** A statistical guarantee for spectral denoising; not a faster decomposition algorithm.

**Evidence:** Official accepted-paper title and abstract.

### L2G-NET: Local to Global Spectral Graph Neural Networks via Cauchy Factorizations

**ICML 2026 · Accept (spotlight)** · Samuel Fernandez; Eduardo Pavez; Antonio Ortega

[OpenReview](<https://openreview.net/forum?id=kD8iJmyn5l>) · [Official program](<https://icml.cc/virtual/2026/poster/62060>) · [PDF](<https://openreview.net/pdf?id=kD8iJmyn5l>)

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

**Quantity:** Graph Fourier transforms for spectral GNNs.

**Computational idea:** Factor the graph Fourier transform through subgraph operators and structured Cauchy matrices, avoiding a full graph eigendecomposition.

**Scope:** Deep learning. **Qualification:** Cost depends on graph interfaces; not a universally linear-time eigensolver.

**Evidence:** Official accepted-paper title and abstract.

### Learning-Guided Integration Contours Construction for Fast Large-Scale Generalized Eigensolvers

**ICML 2026 · Accept (regular)** · Yeqiu Chen; Ziyan Liu; Hong Wang; Lei Liu

[OpenReview](<https://openreview.net/forum?id=ZaOZDGJDAM>) · [Official program](<https://icml.cc/virtual/2026/poster/63150>) · [PDF](<https://openreview.net/pdf?id=ZaOZDGJDAM>)

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

**Quantity:** Generalized eigenpairs.

**Computational idea:** Predict spectral distributions with a neural operator, then construct integration contours with kernel density estimation.

**Scope:** Scientific computing. **Qualification:** Neural guidance accelerates a classical contour-integral solver; not an LLM training study.

**Evidence:** Official accepted-paper title and abstract.

### State Space Model with Continuous Limit of HiPPO Matrix: Eigenvalue Analysis and Explicit Solution Formula

**ICML 2026 · Accept (regular)** · Atsushi Takabatake; Takaharu Yaguchi

[OpenReview](<https://openreview.net/forum?id=eeRgTFtEjv>) · [Official program](<https://icml.cc/virtual/2026/poster/62656>) · [PDF](<https://openreview.net/pdf?id=eeRgTFtEjv>)

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

**Quantity:** HiPPO-related eigenvalue asymptotics and state-space solutions.

**Computational idea:** Pass to a continuous HiPPO operator to derive spectral asymptotics and an explicit solution formula.

**Scope:** Theory / foundations. **Qualification:** Analytical structure for a specific operator family.

**Evidence:** Official accepted-paper title and abstract.

### SVD as a Fast Interpretability Method for Transformers

**ICML 2026 · Accept (spotlight)** · Min Xue; Artur Andrzejak

[OpenReview](<https://openreview.net/forum?id=7tt8TwMjdJ>) · [Official program](<https://icml.cc/virtual/2026/poster/66016>) · [PDF](<https://openreview.net/pdf?id=7tt8TwMjdJ>)

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

**Quantity:** Native transformer MLP subspaces and contributions.

**Computational idea:** Decompose weight matrices into singular rank-one detector-effector units and analyze their contributions without training a proxy model.

**Scope:** Deep learning. **Qualification:** An interpretability use of SVD, not a new faster SVD routine.

**Evidence:** Official accepted-paper title and abstract.

### Swift-SVD: Theoretical Optimality Meets Practical Efficiency in Low-Rank LLM Compression

**ICML 2026 · Accept (regular)** · Ruoling Qi; Yirui Liu; Xuaner Wu; Xiangyu Wang; Ming Li; Chen Chen; Jian Chen; Yin Chen; Qizhen Weng

[OpenReview](<https://openreview.net/forum?id=nAQ4h8FpdM>) · [Official program](<https://icml.cc/virtual/2026/poster/61765>) · [PDF](<https://openreview.net/pdf?id=nAQ4h8FpdM>)

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

**Quantity:** Activation-aware low-rank layer approximation.

**Computational idea:** Accumulate output covariance incrementally, then perform one eigendecomposition; allocate ranks using effective rank and layer importance.

**Scope:** Deep learning. **Qualification:** Optimality is for the stated layerwise reconstruction objective, not global task loss.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/hiahei/Swift-SVD.>). Links extracted from the accepted abstract; code was not tested.

### Efficient Parametric SVD of Koopman Operator for Stochastic Dynamical Systems

**NeurIPS 2025 · Accept (poster)** · Minchan Jeong; Jongha (Jon) Ryu; Se-Young Yun; Gregory Wornell

[OpenReview](<https://openreview.net/forum?id=kL2pnzClyD>) · [Official program](<https://neurips.cc/virtual/2025/poster/116395>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/24826a1c623fe41706850748f3dc7370-Paper-Conference.pdf>)

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/24826a1c623fe41706850748f3dc7370-Abstract-Conference.html>)

**Quantity:** Leading singular functions of the Koopman operator.

**Computational idea:** Learns low-rank singular subspaces with an objective that avoids differentiating through unstable empirical-moment inverses and SVDs.

**Scope:** Deep learning. **Qualification:** Learns an approximation from trajectory data rather than exactly decomposing the true infinite-dimensional operator.

**Evidence:** Official accepted-paper title and abstract.

### Hankel Singular Value Regularization for Highly Compressible State Space Models

**NeurIPS 2025 · Accept (poster)** · Paul Schwerdtner; Jules Berman; Benjamin Peherstorfer

[OpenReview](<https://openreview.net/forum?id=WkztaHpjt1>) · [Official program](<https://neurips.cc/virtual/2025/poster/117569>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/c3070c3388552a08a3326f0d28dc2af9-Paper-Conference.pdf>)

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/c3070c3388552a08a3326f0d28dc2af9-Abstract-Conference.html>)

**Quantity:** Hankel singular values during state-space-model training.

**Computational idea:** Exploits block-diagonal system structure to compute Hankel singular values efficiently for compression regularization.

**Scope:** Deep learning. **Qualification:** The computation relies on the particular SSM parameterization; compression quality remains task-dependent.

**Evidence:** Official accepted-paper title and abstract.

### Spectral Estimation with Free Decompression

**NeurIPS 2025 · Accept (spotlight)** · Siavash Ameli; Chris van der Heide; Liam Hodgkinson; Michael Mahoney

[OpenReview](<https://openreview.net/forum?id=2CeGVUpOd7>) · [Official program](<https://neurips.cc/virtual/2025/poster/120164>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/02d425a464e48bda5e810f8f4914b77e-Paper-Conference.pdf>)

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/02d425a464e48bda5e810f8f4914b77e-Abstract-Conference.html>)

**Quantity:** Eigenspectra of matrices observed through small submatrices.

**Computational idea:** Free decompression uses free-probability structure to infer large-matrix spectral distributions from masked submatrices.

**Scope:** General ML. **Qualification:** An estimated spectrum under structural/statistical assumptions; it does not recover individual eigenvectors or arbitrary matrices exactly.

**Evidence:** Official accepted-paper title and abstract.

### Spectral Graph Coarsening Using Inner Product Preservation and the Grassmann Manifold

**NeurIPS 2025 · Accept (poster)** · Ido Cohen; Ronen Talmon

[OpenReview](<https://openreview.net/forum?id=aBUG2Phwdt>) · [Official program](<https://neurips.cc/virtual/2025/poster/117290>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/aa4bee5e2720d7e8f073d762ee8c7fd4-Paper-Conference.pdf>)

**Categories:** M3 — Applications that explicitly optimize or solve problems on manifolds; X2 — Eigenproblems, spectral computation and SVD analysis.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/aa4bee5e2720d7e8f073d762ee8c7fd4-Abstract-Conference.html>)

**Quantity:** Subspaces and inner products for graph coarsening.

**Computational idea:** Optimizes a low-dimensional Grassmann representation to preserve graph inner products.

**Scope:** General ML. **Qualification:** Coarsening changes the graph representation; the optimization controls distortion rather than eliminating it.

**Manifold relevance:** Optimizes graph-coarsening subspaces on a Grassmann manifold to control inner-product distortion.

**Geometry:** Grassmann manifold of subspaces. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### Spectral Perturbation Bounds for Low-Rank Approximation with Applications to Privacy

**NeurIPS 2025 · Accept (oral)** · Phuc Tran; Van Vu; Nisheeth K. Vishnoi

[OpenReview](<https://openreview.net/forum?id=F0JzotXYgC>) · [Official program](<https://neurips.cc/virtual/2025/poster/119075>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/0e2cf47a9f948f8e8f283d06c118e3ae-Paper-Conference.pdf>)

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/0e2cf47a9f948f8e8f283d06c118e3ae-Abstract-Conference.html>)

**Quantity:** Spectral-norm error in noisy low-rank approximations.

**Computational idea:** Contour-based perturbation analysis gives spectrum-aware bounds and consequences for private PCA.

**Scope:** Theory / foundations. **Qualification:** A robustness analysis, not a new universally faster factorization algorithm; eigengap and noise conditions matter.

**Evidence:** Official accepted-paper title and abstract.

### STNet: Spectral Transformation Network for Solving Operator Eigenvalue Problem

**NeurIPS 2025 · Accept (poster)** · Hong Wang; Yixuan Jiang; Jie Wang; Xinyi Li; Jian Luo; huanshuo dong

[OpenReview](<https://openreview.net/forum?id=nimTd1IJz1>) · [Official program](<https://neurips.cc/virtual/2025/poster/116110>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/48d467d310502791a97d05d1631c5b0f-Paper-Conference.pdf>)

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/48d467d310502791a97d05d1631c5b0f-Abstract-Conference.html>)

**Quantity:** Eigenfunctions and eigenvalues of differential operators.

**Computational idea:** STNet combines deflation and adaptive spectral filtering to ease neural eigenproblem optimization.

**Scope:** Scientific computing. **Qualification:** Approximate neural solutions; performance depends on the spectrum, learned approximations and filtering.

**Evidence:** Official accepted-paper title and abstract.

### SubTrack++ : Gradient Subspace Tracking for Scalable LLM Training

**NeurIPS 2025 · Accept (poster)** · Sahar Rajabi; Nayeema Nonta; Sirisha Rambhatla

[OpenReview](<https://openreview.net/forum?id=6geRIdlFWJ>) · [Official program](<https://neurips.cc/virtual/2025/poster/119775>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/2d62cb71e87ae340e3ab0e874befcbc2-Paper-Conference.pdf>)

**Categories:** D — Memory-efficient and low-precision optimizers; M2 — Manifold-based LLM training and low-rank adaptation; X2 — Eigenproblems, spectral computation and SVD analysis.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/2d62cb71e87ae340e3ab0e874befcbc2-Abstract-Conference.html>)

**Quantity:** Time-varying low-rank gradient subspaces.

**Computational idea:** SubTrack++ updates the projection subspace using Grassmann geometry and adjusts Adam statistics for projection changes.

**Scope:** Deep learning. **Qualification:** Gradient compression remains approximate; subspace tracking and statistic corrections address its changing geometry.

**Optimizer relevance:** SubTrack++ tracks gradient subspaces on a Grassmann manifold and corrects projected Adam statistics for memory-efficient language-model training.

**Manifold relevance:** SubTrack++ treats memory-efficient gradient subspace tracking as Grassmann optimization, with projection-aware adaptive optimizer statistics.

**Geometry:** Grassmann manifold of gradient subspaces. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://proceedings.neurips.cc/paper_files/paper/2025/file/2d62cb71e87ae340e3ab0e874befcbc2-Paper-Conference.pdf>): Section 3 and Algorithm 1, pages 2–4. Verified SVD initialization, rank-one Grassmann geodesic subspace updates, and changes to projected Adam statistics. Tracking still uses singular-vector computations.

**Code links listed by authors:** [Repository](<https://github.com/criticalml-uw/SubTrack.>). Links extracted from the accepted abstract; code was not tested.


## X3 — Fisher, Hessian, derivatives and implicit differentiation

### Avoid Catastrophic Forgetting with Rank-1 Fisher from Diffusion Models

**ICLR 2026 · Accept (Poster)** · Zekun Wang; Anant Gupta; Zihan Dong; Christopher MacLellan

[OpenReview](<https://openreview.net/forum?id=zCZcbRsc4g>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006476>) · [PDF](<https://openreview.net/pdf?id=zCZcbRsc4g>)

**Categories:** X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Dominant diffusion-model Fisher direction.

**Computational idea:** Exploit nearly collinear low-SNR gradients to construct a rank-one Fisher penalty for continual learning.

**Scope:** Deep learning. **Qualification:** Rank-one structure is regime-dependent; not a claim about all diffusion timesteps.

**Evidence:** Official accepted-paper title and abstract.

### Bayesian Influence Functions for Hessian-Free Data Attribution

**ICLR 2026 · Accept (Poster)** · Philipp Alexander Kreer; Wilson Wu; Maxwell Adam; Zach Furman; Jesse Hoogland

[OpenReview](<https://openreview.net/forum?id=YEBpZVm70i>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008904>) · [PDF](<https://openreview.net/pdf?id=YEBpZVm70i>)

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Data influence scores.

**Computational idea:** Replace inverse-Hessian operations with loss-landscape statistics estimated by stochastic-gradient MCMC.

**Scope:** Deep learning. **Qualification:** A Bayesian influence construction, not an algebraically exact classical influence-function evaluation.

**Optimizer relevance:** EKFAC comparison: Bayesian influence functions replace inverse-Hessian computations with stochastic-gradient MCMC loss statistics and evaluate against EK-FAC. A Hessian-free alternative, not an EKFAC variant.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://openreview.net/pdf?id=YEBpZVm70i>): Section 4 and Figure 4, BIF versus EK-FAC retraining experiments; indexed accepted-paper full text. Targeted check recorded in the earlier project catalog; not a complete paper review.

### Decomposing LLM Computation with Jets

**ICLR 2026 · Accept (Poster)** · Yihong Chen; Xiangxiang Xu; Pontus Stenetorp; Sebastian Riedel; Luca Franceschi

[OpenReview](<https://openreview.net/forum?id=u6JLh0BO5h>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006920>) · [PDF](<https://openreview.net/pdf?id=u6JLh0BO5h>)

**Categories:** X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Functional computational paths through LLMs.

**Computational idea:** Use jet operators generalizing truncated Taylor expansions to split paths from complementary remainders.

**Scope:** Deep learning. **Qualification:** A decomposition/interpretability framework; truncated terms alone are not the full model.

**Evidence:** Official accepted-paper title and abstract.

### Deterministic Bounds and Random Estimates of Metric Tensors on Neuromanifolds

**ICLR 2026 · Accept (Poster)** · Ke Sun

[OpenReview](<https://openreview.net/forum?id=Ssevs8KCsU>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009375>) · [PDF](<https://openreview.net/pdf?id=Ssevs8KCsU>)

**Categories:** X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Fisher metric-tensor quantities on neural parameter manifolds.

**Computational idea:** Derive bounds in the low-dimensional probability core space and use a Hutchinson-based estimator with one backward pass per batch.

**Scope:** Deep learning. **Qualification:** Does not explicitly reconstruct a dense full Fisher matrix at this cost.

**Evidence:** Official accepted-paper title and abstract.

### LoRA-S: An Efficient Low Rank Adaptation scheme via Sylvester equation

**ICLR 2026 · Accept (Poster)** · Jinyang ZHENG; Tong Wu

[OpenReview](<https://openreview.net/forum?id=Guo2XGgxZA>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010449>) · [PDF](<https://openreview.net/pdf?id=Guo2XGgxZA>)

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; M2 — Manifold-based LLM training and low-rank adaptation; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Geometry-aware low-rank adapter updates.

**Computational idea:** Use quotient-manifold horizontal lifts and a Sylvester-equation construction for LoRA optimizers.

**Scope:** Deep learning. **Qualification:** Specialized to the low-rank factor geometry; see the paper for metric and solver assumptions.

**Optimizer relevance:** LoRA-S uses quotient-manifold geometry and Sylvester equations to derive Adam-Sylvester and LRACS adapter optimizers.

**Manifold relevance:** LoRA-S uses horizontal lifts and Sylvester equations to derive Adam-Sylvester and LRACS optimizers for low-rank adapters.

**Geometry:** Quotient manifold of low-rank factors. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### Taming Curvature: Architecture Warm-up for Stable Transformer Training

**ICLR 2026 · Accept (Poster)** · Sameera Ramasinghe; Thalaiyasingam Ajanthan; Hadi Mohaghegh Dolatabadi; Chamin Hewa Koneputugodage; Gil Avraham; Violetta Shevchenko; Yan Zuo; Karol Pajak; Alexander Long

[OpenReview](<https://openreview.net/forum?id=DuNf2vPTTK>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010735>) · [PDF](<https://openreview.net/pdf?id=DuNf2vPTTK>)

**Categories:** E — Training stabilization and distributed optimization; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer; T5 — Stability, curvature and edge-of-stability dynamics; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Largest preconditioned Hessian eigenvalue during training.

**Computational idea:** Warm-start power iteration with Hessian-vector products for online curvature tracking.

**Scope:** Deep learning. **Qualification:** Approximate leading eigenvalue; used to motivate progressive depth warm-up.

**Optimizer relevance:** Architecture warm-up progressively grows Transformer depth to control preconditioned curvature; introduces an online Hessian-eigenvalue estimator for diagnosing training instability.

**Training dynamics relevance:** Architecture warm-up progressively grows Transformer depth to control preconditioned curvature; introduces an online Hessian-eigenvalue estimator for diagnosing training instability.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Depth warm-up; preconditioned curvature; instability.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Towards Efficient Optimizer Design for LLM via Structured Fisher Approximation with a Low-Rank Extension

**ICLR 2026 · Accept (Poster)** · Wenbo Gong; Meyer Scetbon; Chao Ma; Edward Meeds

[OpenReview](<https://openreview.net/forum?id=KUFZXdem5R>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010128>) · [PDF](<https://openreview.net/pdf?id=KUFZXdem5R>)

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Memory-efficient structured Fisher preconditioners.

**Computational idea:** Derive row/column-scaled and low-rank approximations, yielding RACS and Alice optimizers.

**Scope:** Deep learning. **Qualification:** Structural approximations trade curvature fidelity for storage and computation.

**Optimizer relevance:** Structured empirical-Fisher approximation unifies optimizer designs and yields RACS and Alice; includes low-rank tracking and residual compensation for memory-efficient LLaMA pretraining.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://openreview.net/pdf?id=KUFZXdem5R>): Figure 1 and Section 2: block-diagonal/Kronecker empirical-Fisher approximations and relation to K-FAC; indexed accepted-paper full text. Targeted check recorded in the earlier project catalog; not a complete paper review.

### Understanding and improving Shampoo and SOAP via Kullback-Leibler Minimization

**ICLR 2026 · Accept (Poster)** · Wu Lin; Scott C. Lowe; Felix Dangel; Runa Eschenhagen; Zikun Xu; Roger Grosse

[OpenReview](<https://openreview.net/forum?id=pQQuC1nIQq>) · [Official program](<https://iclr.cc/virtual/2026/poster/10007330>) · [PDF](<https://openreview.net/pdf?id=pQQuC1nIQq>)

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Structured covariance estimates for Shampoo and SOAP.

**Computational idea:** Replace Frobenius-motivated estimation with KL-divergence minimization to redesign the preconditioners.

**Scope:** Deep learning. **Qualification:** A different approximation objective; comparative speed and accuracy depend on experiments.

**Optimizer relevance:** KL-Shampoo and KL-SOAP reinterpret structured second moments through KL covariance estimation; KL-Shampoo avoids Adam grafting and its extra state memory.

**Evidence:** Official accepted-paper title and abstract.

### 3DGS$^2$-TR: A Scalable Second-Order Trust-Region Method for 3D Gaussian Splatting

**ICML 2026 · Accept (regular)** · Roger Hsiao; Yuchen Fang; Xiangru Huang; Ruilong Li; Hesam Rabeti; Zan Gojcic; Javad Lavaei; James Demmel; Sophia Shao

[OpenReview](<https://openreview.net/forum?id=Kaliw0BQL9>) · [Official program](<https://icml.cc/virtual/2026/poster/64716>) · [PDF](<https://openreview.net/pdf?id=Kaliw0BQL9>)

**Categories:** X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Hessian diagonal for 3D Gaussian Splatting.

**Computational idea:** Estimate diagonal curvature with Hutchinson probes and combine it with parameter-wise trust-region updates.

**Scope:** Deep learning. **Qualification:** Matrix-free stochastic diagonal approximation, not full second-order curvature.

**Evidence:** Official accepted-paper title and abstract.

### A Fully First-Order Layer for Differentiable Optimization

**ICML 2026 · Accept (spotlight)** · Zihao Zhao; Kai-Chia Mo; Shing-Hei Ho; Brandon Amos; Kai Wang

[OpenReview](<https://openreview.net/forum?id=jJur8Fq7IK>) · [Official program](<https://icml.cc/virtual/2026/poster/62152>) · [PDF](<https://openreview.net/pdf?id=jJur8Fq7IK>)

**Categories:** X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Hypergradients through constrained optimization layers.

**Computational idea:** Use an active-set Lagrangian proxy and first-order information instead of explicit Hessian calculations.

**Scope:** General ML. **Qualification:** Approximate hypergradient oracle under stated regularity conditions.

**Evidence:** Official accepted-paper title and abstract.

### A Penalty Approach For Differentiation Through Black-box Quadratic Programming Solvers

**ICML 2026 · Accept (regular)** · Yuxuan Linghu; Zhiyuan Liu; Qi Deng

[OpenReview](<https://openreview.net/forum?id=2jpMiRwsrL>) · [Official program](<https://icml.cc/virtual/2026/poster/66543>) · [PDF](<https://openreview.net/pdf?id=2jpMiRwsrL>)

**Categories:** X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Gradients through quadratic-program solutions.

**Computational idea:** Implicitly differentiate a smooth penalty problem using a smaller primal-variable linear system.

**Scope:** General ML. **Qualification:** Differentiates a smooth approximation rather than an arbitrary exact nonsmooth QP solution map.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/mmmmmmlinghu/dXPP.>). Links extracted from the accepted abstract; code was not tested.

### A Sketch-and-Project Analysis of Subsampled Natural Gradient Algorithms

**ICML 2026 · Accept (regular)** · Gil Goldshlager; Jiang Hu; Lin Lin

[OpenReview](<https://openreview.net/forum?id=2iDtIht7W4>) · [Official program](<https://icml.cc/virtual/2026/poster/66550>) · [PDF](<https://openreview.net/pdf?id=2iDtIht7W4>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Subsampled natural-gradient directions.

**Computational idea:** Interpret the update as sketch-and-project and analyze coupling with a squared-volume-sampling proxy.

**Scope:** Theory / foundations. **Qualification:** Primarily an analysis of natural-gradient algorithms; distinguishes the proxy from practical sampling.

**Optimizer relevance:** Analyzes subsampled natural gradient through sketch-and-project geometry, including coupled small minibatches and SPRING momentum; focus is scientific ML.

**Evidence:** Official accepted-paper title and abstract.

### Decision-Focused Learning via Tangent-Space Projection of Prediction Error

**ICML 2026 · Accept (regular)** · Junhyeong Lee; Sangjin Jin; Yongjae Lee

[OpenReview](<https://openreview.net/forum?id=ZDtFevjwin>) · [Official program](<https://icml.cc/virtual/2026/poster/63194>) · [PDF](<https://openreview.net/pdf?id=ZDtFevjwin>)

**Categories:** X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Decision-focused regret gradients.

**Computational idea:** Project prediction error onto the tangent space of active constraints via a reduced linear system.

**Scope:** General ML. **Qualification:** Closed-form characterization assumes regularity and locally stable active constraints.

**Evidence:** Official accepted-paper title and abstract.

### DP-KFC: Data-Free Preconditioning for Privacy-Preserving Deep Learning

**ICML 2026 · Accept (regular)** · Marc Molina Van den bosch; Riccardo Taiello; Albert Aillet; Andrea Protani; Miguel Angel Gonzalez Ballester; Luigi Serio

[OpenReview](<https://openreview.net/forum?id=Z6HxJqAzbp>) · [Official program](<https://icml.cc/virtual/2026/poster/63209>) · [PDF](<https://openreview.net/pdf?id=Z6HxJqAzbp>)

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** KFAC curvature factors without private data.

**Computational idea:** Probe architectural sensitivity with structured synthetic noise and approximate input correlations from modality statistics.

**Scope:** Deep learning. **Qualification:** A data-free structured Fisher approximation, not recovery of arbitrary data-dependent curvature.

**Optimizer relevance:** Direct KFAC optimizer: constructs preconditioners from structured synthetic noise for differentially private learning. The abstract does not establish LLM-scale evaluation.

**Evidence:** Official accepted-paper title and abstract.

### IO-Adam: Rethinking Memory-Efficient Adaptive Optimizers from Gradient Computation

**ICML 2026 · Accept (regular)** · Yiting Chen; Zongwei Huo; Junchi Yan

[OpenReview](<https://openreview.net/forum?id=z0m3EhzhOH>) · [Official program](<https://icml.cc/virtual/2026/poster/60558>) · [PDF](<https://openreview.net/pdf?id=z0m3EhzhOH>)

**Categories:** D — Memory-efficient and low-precision optimizers; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Adam-like first and second moments.

**Computational idea:** Track layer inputs and output gradients to estimate moments using the factorization of the weight gradient.

**Scope:** Deep learning. **Qualification:** Moment estimation differs from exact Adam; memory-performance trade-off is empirical.

**Optimizer relevance:** IO-Adam estimates moment information through layer inputs and output gradients rather than storing full parameter-wise moment tensors.

**Evidence:** Official accepted-paper title and abstract.

### Local Hessian Spectral Filtering for Robust Intrinsic Dimension Estimation

**ICML 2026 · Accept (regular)** · Genki Osada

[OpenReview](<https://openreview.net/forum?id=rJ2gMA21ZW>) · [Official program](<https://icml.cc/virtual/2026/poster/61325>) · [PDF](<https://openreview.net/pdf?id=rJ2gMA21ZW>)

**Categories:** X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Filtered log-density Hessian trace and local intrinsic dimension.

**Computational idea:** Apply stochastic Lanczos quadrature through Hessian-vector products to count near-zero-curvature tangent directions.

**Scope:** Deep learning. **Qualification:** A stochastic spectral-filter estimate; this is the input log-density Hessian, not the training-parameter Hessian.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2605.01221v1>): Algorithm 1 and Section 3; input-space Hessian-vector oracle, Rademacher probes and Lanczos quadrature. The filtered Hessian is derived from the diffusion score/log density, not the parameter-training loss.

### Model-Preserving Adaptive Rounding

**ICML 2026 · Accept (regular)** · Albert Tseng; Zhaofeng Sun; Chris De Sa

[OpenReview](<https://openreview.net/forum?id=PKFilPWjMI>) · [Official program](<https://icml.cc/virtual/2026/poster/64269>) · [PDF](<https://openreview.net/pdf?id=PKFilPWjMI>)

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Hessian geometry for adaptive rounding.

**Computational idea:** Use a Kronecker-factored approximation and Hessian sketches aligned with network-output error.

**Scope:** Deep learning. **Qualification:** An approximation supporting quantization; not full end-to-end Hessian construction.

**Optimizer relevance:** Related Kronecker-curvature method: YAQA uses Kronecker-factored Hessian sketches of end-to-end model error for adaptive quantization rounding.

**Evidence:** Official accepted-paper title and abstract.

### Natural Hypergradient Descent:  Algorithm Design, Convergence Analysis, and Parallel Implementation

**ICML 2026 · Accept (regular)** · Deyi Kong; Zaiwei Chen; Shuzhong Zhang; Shancong Mou

[OpenReview](<https://openreview.net/forum?id=4K54YHTG2i>) · [Official program](<https://icml.cc/virtual/2026/poster/66368>) · [PDF](<https://openreview.net/pdf?id=4K54YHTG2i>)

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Inverse-Hessian actions for bilevel hypergradients.

**Computational idea:** Use empirical Fisher as an asymptotically consistent Hessian surrogate and update the approximation alongside inner optimization.

**Scope:** General ML. **Qualification:** Fisher-Hessian agreement and convergence require the paper's statistical assumptions.

**Optimizer relevance:** Bilevel optimization: empirical-Fisher inverse estimates are updated alongside inner optimization; the full text explicitly incorporates K-FAC to reduce memory and computation.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2602.10905>): Section 3 Practical Considerations: K-FAC acceleration Targeted check recorded in the earlier project catalog; not a complete paper review.

### Randomized Advantage Transformation (RAT): Computing Natural Policy Gradients via Direct Backpropagation

**ICML 2026 · Accept (regular)** · Mingfei Sun

[OpenReview](<https://openreview.net/forum?id=oVtiySvpXz>) · [Official program](<https://icml.cc/virtual/2026/poster/61606>) · [PDF](<https://openreview.net/pdf?id=oVtiySvpXz>)

**Categories:** X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Regularized natural policy gradients.

**Computational idea:** Use Woodbury to move the solve to advantage space, approximate it with randomized block Kaczmarz, then use ordinary backpropagation.

**Scope:** Deep learning. **Qualification:** Regularized sampled natural-gradient target; finite solver iterations are approximate.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2605.18591v1>): Sections 4.2-4.3, equations 6-10; Woodbury advantage-space reformulation and randomized Kaczmarz. Distinguish the exact algebraic reformulation from the finite-iteration randomized estimate.

### Revisiting Zeroth-Order Hessian Approximation: A Single-Step Policy Optimization Lens

**ICML 2026 · Accept (regular)** · Junbin Qiu; Zhaowei Hong; Renzhe Xu; Yao Shu

[OpenReview](<https://openreview.net/forum?id=nEQYu4ndGA>) · [Official program](<https://icml.cc/virtual/2026/poster/61753>) · [PDF](<https://openreview.net/pdf?id=nEQYu4ndGA>)

**Categories:** X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Hessian, regularized inverse and inverse-Hessian-gradient estimates.

**Computational idea:** Recast zeroth-order estimation as policy optimization; use variance-minimizing baselines and reuse historical function queries.

**Scope:** General ML. **Qualification:** Unbiasedness is stated for the Hessian estimator; inverse quantities have their own bias/error analysis.

**Evidence:** Official accepted-paper title and abstract.

### Scalable Kronecker-Factored Fisher Approximation for Neural Network Parameter Sensitivity

**ICML 2026 · Accept (regular)** · Viktoriia Chekalina; Daniil Moskovskiy; Tatyana Matveeva; Andrey Kuznetsov; Evgeny Frolov

[OpenReview](<https://openreview.net/forum?id=pNe5fVK1tR>) · [Official program](<https://icml.cc/virtual/2026/poster/61515>) · [PDF](<https://openreview.net/pdf?id=pNe5fVK1tR>)

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Structured Fisher information and sensitivity-aware low-rank factors.

**Computational idea:** Matrix-free Fisher factorization retains off-diagonal structure; GFWSVD gives a curvature-weighted layer decomposition.

**Scope:** Deep learning. **Qualification:** Closed-form optimality relies on the stated matrix-variate normal assumptions.

**Optimizer relevance:** Structured Fisher approximation: matrix-free Fisher factorization (MFF) and GFWSVD preserve non-diagonal parameter sensitivity for neural-network and LLM compression.

**Evidence:** Official accepted-paper title and abstract.

### A Private Approximation of the 2nd-Moment Matrix of Any Subsamplable Input

**NeurIPS 2025 · Accept (poster)** · Bar Mahpud; Or Sheffet

[OpenReview](<https://openreview.net/forum?id=Ep4mYI7OLF>) · [Official program](<https://neurips.cc/virtual/2025/poster/119097>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/e61c3ae7d4ace10e1fb6f9fd25218fd7-Paper-Conference.pdf>)

**Categories:** X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/e61c3ae7d4ace10e1fb6f9fd25218fd7-Abstract-Conference.html>)

**Quantity:** Differentially private second-moment matrices.

**Computational idea:** A recursive estimator exploits subsamplability to preserve spectral structure while adding privacy protection.

**Scope:** General ML. **Qualification:** Accuracy guarantees require subsamplability and probabilistic conditions; the returned matrix is a private approximation.

**Evidence:** Official accepted-paper title and abstract.

### ASGO: Adaptive Structured Gradient Optimization

**NeurIPS 2025 · Accept (poster)** · Kang An; Yuxing Liu; Rui Pan; Yi Ren; Shiqian Ma; Donald Goldfarb; Tong Zhang

[OpenReview](<https://openreview.net/forum?id=fru52tkjHf>) · [Official program](<https://neurips.cc/virtual/2025/poster/116796>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/b862a40b617719cde47fa268b8d5c91d-Paper-Conference.pdf>)

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/b862a40b617719cde47fa268b8d5c91d-Abstract-Conference.html>)

**Quantity:** Structured adaptive matrix preconditioners.

**Computational idea:** ASGO exploits low-rank gradients and block-structured curvature in adaptive preconditioning.

**Scope:** Deep learning. **Qualification:** Structural assumptions and convergence conditions qualify the guarantees; matrix preconditioning need not equal a Newton step.

**Optimizer relevance:** ASGO uses structured preconditioning to exploit low-rank gradients and block-structured curvature, with convergence analysis and language-model experiments.

**Evidence:** Official accepted-paper title and abstract.

### Better Training Data Attribution via Better Inverse Hessian-Vector Products

**NeurIPS 2025 · Accept (poster)** · Andrew Wang; Elisa Nguyen; Runshi Yang; Juhan Bae; Sheila McIlraith; Roger Grosse

[OpenReview](<https://openreview.net/forum?id=7LTTzYXyJ1>) · [Official program](<https://neurips.cc/virtual/2025/poster/119714>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/936ce22b767cf1a1496083e4725d3b21-Paper-Conference.pdf>)

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/936ce22b767cf1a1496083e4725d3b21-Abstract-Conference.html>)

**Quantity:** Damped inverse-curvature-vector products for data attribution.

**Computational idea:** ASTRA applies EKFAC-preconditioned stochastic Neumann iterations, refining the initial structured approximation with additional curvature-vector products.

**Scope:** Deep learning. **Qualification:** The practical operator is a damped generalized Gauss-Newton approximation; finite iterations do not give an exact inverse of an arbitrary loss Hessian.

**Optimizer relevance:** ASTRA uses an EKFAC preconditioner to accelerate stochastic Neumann iterations for training-data attribution. This is a substantive EKFAC application, rather than a new LLM training optimizer.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://proceedings.neurips.cc/paper_files/paper/2025/file/936ce22b767cf1a1496083e4725d3b21-Paper-Conference.pdf>): Sections 2.1–3, equations (5)–(9), pages 3–6. Confirmed the damped GGN operator and EKFAC-preconditioned stochastic Neumann update; matrix-vector products avoid forming the full inverse.

### Efficient Data Selection at Scale via Influence Distillation

**NeurIPS 2025 · Accept (poster)** · Mahdi Nikdan; Vincent Cohen-Addad; Dan Alistarh; Vahab Mirrokni

[OpenReview](<https://openreview.net/forum?id=E6ZdfjtoiX>) · [Official program](<https://neurips.cc/virtual/2025/poster/119164>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/d2d4f6858cc2d21fd0230244fcb34f1d-Paper-Conference.pdf>)

**Categories:** X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/d2d4f6858cc2d21fd0230244fcb34f1d-Abstract-Conference.html>)

**Quantity:** Optimizer-aware influence scores for data selection.

**Computational idea:** Influence Distillation computes scores on landmark examples and propagates them to approximate second-order data selection under GD or Adam.

**Scope:** Deep learning. **Qualification:** Landmark distillation approximates influence scores and does not compute exact leave-one-out retraining effects.

**Evidence:** Official accepted-paper title and abstract.

### GradMetaNet: An Equivariant Architecture for Learning on Gradients

**NeurIPS 2025 · Accept (poster)** · Yoav Gelberg; Yam Eitan; Aviv Navon; Aviv Shamsian; Theo Putterman; Michael Bronstein; Haggai Maron

[OpenReview](<https://openreview.net/forum?id=Gvex75bPMI>) · [Official program](<https://neurips.cc/virtual/2025/poster/118925>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/e2d228a7479823e1fb12918f08f8955f-Paper-Conference.pdf>)

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/e2d228a7479823e1fb12918f08f8955f-Abstract-Conference.html>)

**Quantity:** Compact gradient representations for learned optimization.

**Computational idea:** GradMetaNet uses equivariant processing of gradient sets and rank-one representations to learn updates that exploit curvature structure.

**Scope:** Deep learning. **Qualification:** The update is learned from training tasks rather than computed as an exact inverse-curvature product.

**Optimizer relevance:** GradMetaNet learns equivariant gradient transformations using compact representations of per-example gradient structure.

**Evidence:** Official accepted-paper title and abstract.

### Improving Energy Natural Gradient Descent through Woodbury, Momentum, and Randomization

**NeurIPS 2025 · Accept (poster)** · Andrés Guzmán-Cordero; Felix Dangel; Gil Goldshlager; Marius Zeinhofer

[OpenReview](<https://openreview.net/forum?id=5YMZfufpfY>) · [Official program](<https://neurips.cc/virtual/2025/poster/119855>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/a5809a25c65040fd43e146126b45b150-Paper-Conference.pdf>)

**Categories:** J — Adjacent numerical, architectural, and specialized training methods; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/a5809a25c65040fd43e146126b45b150-Abstract-Conference.html>)

**Quantity:** Energy-natural-gradient linear solves in PINNs.

**Computational idea:** Uses Woodbury identities to reduce solve dimensions, then adds momentum and randomized approximations for larger problems.

**Scope:** Scientific computing. **Qualification:** Woodbury algebra can be exact, while randomization is approximate; reported benefits are strongest in particular PDE regimes.

**Optimizer relevance:** Improves energy natural gradient descent for PINNs through a Woodbury reformulation, SPRING-style momentum and randomized approximations. Specialized scientific training, not an LLM benchmark.

**Evidence:** Official accepted-paper title and abstract.

### KOALA++: Efficient Kalman-Based Optimization with Gradient-Covariance Products

**NeurIPS 2025 · Accept (poster)** · Zixuan XIa; Aram Davtyan; Paolo Favaro

[OpenReview](<https://openreview.net/forum?id=Pvoy6fWaRJ>) · [Official program](<https://neurips.cc/virtual/2025/poster/118176>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/323acd89d43df534db8d39da4c67a4b1-Paper-Conference.pdf>)

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/323acd89d43df534db8d39da4c67a4b1-Abstract-Conference.html>)

**Quantity:** Gradient-covariance operations for Kalman optimizer updates.

**Computational idea:** KOALA++ uses compact structured covariance representations to avoid dense covariance storage and inverse computation.

**Scope:** Deep learning. **Qualification:** The covariance model is structured and approximate; uncertainty estimates are not the exact loss Hessian.

**Optimizer relevance:** KOALA++ builds structured Kalman-filter updates from gradient uncertainty, with compact covariance operations for scalable neural-network training.

**Evidence:** Official accepted-paper title and abstract.

### Least squares variational inference

**NeurIPS 2025 · Accept (poster)** · Yvann Le Fay; Nicolas Chopin; Simon Barthelmé

[OpenReview](<https://openreview.net/forum?id=Gvh6sU0uUt>) · [Official program](<https://neurips.cc/virtual/2025/poster/118924>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/d51ceadaf09a4699f18986702df24987-Paper-Conference.pdf>)

**Categories:** J — Adjacent numerical, architectural, and specialized training methods; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/d51ceadaf09a4699f18986702df24987-Abstract-Conference.html>)

**Quantity:** Natural-gradient-like variational inference updates.

**Computational idea:** Replaces explicit large Fisher inverses with Monte Carlo ordinary least-squares regression of log-target quantities.

**Scope:** General ML. **Qualification:** Gradient-free does not mean exact: Monte Carlo regression produces stochastic, generally biased natural-gradient estimates.

**Optimizer relevance:** Least-squares variational inference recasts natural-gradient-like inference updates as Monte Carlo regression without constructing a large Fisher inverse.

**Evidence:** Official accepted-paper title and abstract.

### On the Optimal Construction of Unbiased Gradient Estimators for Zeroth-Order Optimization

**NeurIPS 2025 · Accept (spotlight)** · Shaocong Ma; Heng Huang

[OpenReview](<https://openreview.net/forum?id=rVT1GK60Nt>) · [Official program](<https://neurips.cc/virtual/2025/poster/115772>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/7f7eade8b69c853e3137cab80df3ccf6-Paper-Conference.pdf>)

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/7f7eade8b69c853e3137cab80df3ccf6-Abstract-Conference.html>)

**Quantity:** Unbiased function-evaluation gradient estimators.

**Computational idea:** Randomizes a telescoping expansion of directional derivatives to remove finite-difference bias.

**Scope:** Deep learning. **Qualification:** Unbiasedness and variance bounds require stated smoothness and sampling conditions; individual estimates remain noisy.

**Optimizer relevance:** Constructs unbiased zeroth-order gradient estimators through randomized telescoping series, with theory and language-model fine-tuning experiments.

**Evidence:** Official accepted-paper title and abstract.

### PaZO: Preconditioned Accelerated Zeroth-Order Optimization for Fine-Tuning LLMs

**NeurIPS 2025 · Accept (poster)** · Hanzhen Zhao; Ding Shihong; Cong Fang; Zhouchen Lin

[OpenReview](<https://openreview.net/forum?id=b2IU6QOOfo>) · [Official program](<https://neurips.cc/virtual/2025/poster/117216>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/a14193e9d9fb0b03af0b717de1cac8ac-Paper-Conference.pdf>)

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/a14193e9d9fb0b03af0b717de1cac8ac-Abstract-Conference.html>)

**Quantity:** Diagonal curvature estimates for zeroth-order updates.

**Computational idea:** PaZO estimates diagonal Hessian information and smooths it to precondition function-evaluation-based training.

**Scope:** Deep learning. **Qualification:** A noisy diagonal estimate, not a full Hessian or exact natural gradient.

**Optimizer relevance:** PaZO uses estimated diagonal curvature and momentum to precondition zeroth-order language-model fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

### PseuZO: Pseudo-Zeroth-Order Algorithm for Training Deep Neural Networks

**NeurIPS 2025 · Accept (poster)** · Pengyun Yue; Xuanlin Yang; Mingqing Xiao; Zhouchen Lin

[OpenReview](<https://openreview.net/forum?id=tM4cHBD7kD>) · [Official program](<https://neurips.cc/virtual/2025/poster/115604>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/9a9afa70eead1805f00e3a0df2a41157-Paper-Conference.pdf>)

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/9a9afa70eead1805f00e3a0df2a41157-Abstract-Conference.html>)

**Quantity:** Model-output Jacobian estimates for zeroth-order fine-tuning.

**Computational idea:** PseuZO separates the output Jacobian from the loss derivative and reuses stochastic estimates through temporal averaging.

**Scope:** Deep learning. **Qualification:** The Jacobian is estimated from function queries; bias and variance depend on the estimator and reuse scheme.

**Optimizer relevance:** PseuZO separates model-output Jacobian estimation from the outer loss gradient and reuses estimates for zeroth-order fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/YangBigMn/PseuZO.>). Links extracted from the accepted abstract; code was not tested.

### StreamBP: Memory-Efficient Exact Backpropagation for Long Sequence Training of LLMs

**NeurIPS 2025 · Accept (poster)** · Qijun Luo; Mengqi Li; Lei Zhao; Xiao Li

[OpenReview](<https://openreview.net/forum?id=EpgMSwJY8t>) · [Official program](<https://neurips.cc/virtual/2025/poster/119094>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/f092c84221d73387a6a5dd7517c500a5-Paper-Conference.pdf>)

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/f092c84221d73387a6a5dd7517c500a5-Abstract-Conference.html>)

**Quantity:** Backpropagation gradients for causal sequence models.

**Computational idea:** StreamBP reorganizes chain-rule evaluation to stream gradient computation with lower activation memory.

**Scope:** Deep learning. **Qualification:** Preserves the mathematical gradient for the supported computation; practical speed depends on recomputation and implementation.

**Optimizer relevance:** StreamBP reorganizes chain-rule computations for memory-efficient backpropagation in causal language models while preserving the underlying gradient computation.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/Ledzy/StreamBP.>). Links extracted from the accepted abstract; code was not tested.


## X4 — Randomized sketching and kernel approximations

### Graph Random Features for Scalable Gaussian Processes

**ICLR 2026 · Accept (Poster)** · Matthew Zhang; Jihao Andreas Lin; Krzysztof Choromanski; Adrian Weller; Richard E Turner; Isaac Reid

[OpenReview](<https://openreview.net/forum?id=89SQfLguNn>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011224>) · [PDF](<https://openreview.net/pdf?id=89SQfLguNn>)

**Categories:** X4 — Randomized sketching and kernel approximations.

**Quantity:** Graph-kernel Gaussian-process inference.

**Computational idea:** Use stochastic graph random features to reduce inference cost with probabilistic accuracy guarantees.

**Scope:** General ML. **Qualification:** Complexity guarantee is conditional on stated assumptions and is not for arbitrary dense GPs.

**Evidence:** Official accepted-paper title and abstract.

### Revisiting Matrix Sketching in Linear  Bandits: Achieving Sublinear Regret via Dyadic Block Sketching

**ICLR 2026 · Accept (Poster)** · Dongxie Wen; Hanyan Yin; Xiao Zhang; Peng Zhao; Lijun Zhang; Zhewei Wei

[OpenReview](<https://openreview.net/forum?id=FKEHiHU4bN>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010610>) · [PDF](<https://openreview.net/pdf?id=FKEHiHU4bN>)

**Categories:** X4 — Randomized sketching and kernel approximations.

**Quantity:** Streaming covariance sketches for linear bandits.

**Computational idea:** Grow sketch capacity through dyadic blocks to control spectral error without knowing the spectrum in advance.

**Scope:** General ML. **Qualification:** Online-learning guarantees; transfer to LLM optimization is a possible connection, not demonstrated here.

**Evidence:** Official accepted-paper title and abstract.

### Scalable Random Wavelet Features: Efficient Non-Stationary Kernel Approximation with Convergence Guarantees

**ICLR 2026 · Accept (Poster)** · Sawan Kumar; Souvik Chakraborty

[OpenReview](<https://openreview.net/forum?id=fWhRslwYri>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008227>) · [PDF](<https://openreview.net/pdf?id=fWhRslwYri>)

**Categories:** X4 — Randomized sketching and kernel approximations.

**Quantity:** Non-stationary kernel feature maps.

**Computational idea:** Sample localized wavelet families to construct explicit random features with unbiasedness and convergence guarantees.

**Scope:** General ML. **Qualification:** Random-feature approximation, rather than an exact dense kernel computation.

**Evidence:** Official accepted-paper title and abstract.

### Towards Sampling Data Structures for Tensor Products in Turnstile Streams

**ICLR 2026 · Accept (Poster)** · Zhao Song; Shenghao Xie; Samson Zhou

[OpenReview](<https://openreview.net/forum?id=ZgLEEp7AwL>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008784>) · [PDF](<https://openreview.net/pdf?id=ZgLEEp7AwL>)

**Categories:** X4 — Randomized sketching and kernel approximations.

**Quantity:** Important coordinates in attention tensor products.

**Computational idea:** Maintain attention-sampling data structures in turnstile streams instead of constructing the full attention matrix.

**Scope:** Theory / foundations. **Qualification:** A theoretical streaming model, not a drop-in GPU attention implementation.

**Evidence:** Official accepted-paper title and abstract.

### Computationally-efficient Graph Modeling with Refined Graph Random Features

**ICML 2026 · Accept (regular)** · Krzysztof Choromanski; Kumar Avinava Dubey; Arijit Sehanobish; Isaac Reid

[OpenReview](<https://openreview.net/forum?id=NvJPE1oiKd>) · [Official program](<https://icml.cc/virtual/2026/poster/64410>) · [PDF](<https://openreview.net/pdf?id=NvJPE1oiKd>)

**Categories:** X4 — Randomized sketching and kernel approximations.

**Quantity:** Graph kernel random features.

**Computational idea:** Stitch short random walks using parallel computation and matrix multiplication while preserving unbiasedness.

**Scope:** General ML. **Qualification:** Random-feature approximation of graph kernels.

**Evidence:** Official accepted-paper title and abstract.

### Even Faster Kernel Matrix Linear Algebra via Density Estimation

**ICML 2026 · Accept (spotlight)** · Rikhav Shah; Sandeep Silwal; Haike Xu

[OpenReview](<https://openreview.net/forum?id=ueNIrBXz7R>) · [Official program](<https://icml.cc/virtual/2026/poster/61003>) · [PDF](<https://openreview.net/pdf?id=ueNIrBXz7R>)

**Categories:** X4 — Randomized sketching and kernel approximations.

**Quantity:** Kernel matrix products, spectral norm and entry sums.

**Computational idea:** Access Gaussian and related kernel matrices through kernel-density queries instead of individual matrix entries.

**Scope:** Theory / foundations. **Qualification:** Approximation guarantees depend on kernel, accuracy and query-model assumptions.

**Evidence:** Official accepted-paper title and abstract.

### FlashSketch: Sketch-Kernel Co-Design for Fast Sparse Sketching on GPUs

**ICML 2026 · Accept (spotlight)** · Rajat Vadiraj Dwaraknath; Sungyoon Kim; Mert Pilanci

[OpenReview](<https://openreview.net/forum?id=cCwxV6rSXF>) · [Official program](<https://icml.cc/virtual/2026/oral/71181>) · [PDF](<https://openreview.net/pdf?id=cCwxV6rSXF>)

**Categories:** X4 — Randomized sketching and kernel approximations.

**Quantity:** Sparse sketches of large matrices.

**Computational idea:** Co-design block-permuted sparse Johnson-Lindenstrauss transforms and a CUDA kernel for local accumulation and efficient memory access.

**Scope:** Deep learning. **Qualification:** Probabilistic sketch quality; theory discusses assumptions on block wiring and coherence.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2602.06071v1>): Sections 4-6 and theoretical limitations; block-permuted SJLT, CUDA accumulation and coherence-dependent guarantees. The paper distinguishes independent-permutation analysis from practical edge-disjoint wiring.

### RL4RLA: Teaching ML to Discover Randomized Linear Algebra Algorithms Through Curriculum Design and Graph-Based Search

**ICML 2026 · Accept (regular)** · Jinglong Xiong; Xiaotian Liu; Ruoxin Wang; Zihang Liu; Yefan Zhou; Yujun Yan; Yaoqing Yang

[OpenReview](<https://openreview.net/forum?id=Oj2I1xdKpv>) · [Official program](<https://icml.cc/virtual/2026/poster/64326>) · [PDF](<https://openreview.net/pdf?id=Oj2I1xdKpv>)

**Categories:** X4 — Randomized sketching and kernel approximations.

**Quantity:** Randomized linear algebra algorithms.

**Computational idea:** Search symbolic linear algebra programs with reinforcement learning, a numerical curriculum and graph search that merges equivalent partial programs.

**Scope:** Theory / foundations. **Qualification:** Algorithm discovery framework; guarantees belong to the resulting algorithms and tested settings.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/Tim-Xiong/RL4RLA.>). Links extracted from the accepted abstract; code was not tested.

### Sketch-Based Low-Rank Model Merging with Shared Circulant Transforms

**ICML 2026 · Accept (regular)** · Zhiming Zhang; Rong Yin; Xiaoshuai Hao; Hansong Zhang; Hao Peng; Yong Liu; Can Ma; Dan Meng

[OpenReview](<https://openreview.net/forum?id=ytlRCCl7Pf>) · [Official program](<https://icml.cc/virtual/2026/poster/60572>) · [PDF](<https://openreview.net/pdf?id=ytlRCCl7Pf>)

**Categories:** X4 — Randomized sketching and kernel approximations.

**Quantity:** Merged low-rank adapters.

**Computational idea:** Apply shared circulant transforms and compact sketches to merge LoRA factors without dense deltas or expensive subspace factorizations.

**Scope:** Deep learning. **Qualification:** Sketch-based approximate merging; quality depends on retained information.

**Evidence:** Official accepted-paper title and abstract.

### SWING: Unlocking Implicit Graph Representations for Graph Random Features

**ICML 2026 · Accept (spotlight)** · Alessandro Manenti; Kumar Avinava Dubey; Arijit Sehanobish; Cesare Alippi; Krzysztof Choromanski

[OpenReview](<https://openreview.net/forum?id=LBcnybFVBp>) · [Official program](<https://icml.cc/virtual/2026/poster/64659>) · [PDF](<https://openreview.net/pdf?id=LBcnybFVBp>)

**Categories:** X4 — Randomized sketching and kernel approximations.

**Quantity:** Random features for implicitly represented graphs.

**Computational idea:** Replace graph-node walks with continuous-space walks, random-feature kernels and importance-sampled Gumbel-softmax mechanisms.

**Scope:** General ML. **Qualification:** Approximates implicit graph computations without materializing the graph.

**Evidence:** Official accepted-paper title and abstract.

### Breaking the Frozen Subspace: Importance Sampling for Low-Rank Optimization in LLM Pretraining

**NeurIPS 2025 · Accept (poster)** · Haochen Zhang; Junze Yin; Guanchu Wang; Zirui Liu; Lin Yang; Tianyi Zhang; Anshumali Shrivastava; Vladimir Braverman

[OpenReview](<https://openreview.net/forum?id=ZdmmOAN4h3>) · [Official program](<https://neurips.cc/virtual/2025/poster/117335>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/0edd294b7632fc96903abfbf3b264fc1-Paper-Conference.pdf>)

**Categories:** D — Memory-efficient and low-precision optimizers; X4 — Randomized sketching and kernel approximations.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/0edd294b7632fc96903abfbf3b264fc1-Abstract-Conference.html>)

**Quantity:** Adaptively sampled low-rank gradient projections.

**Computational idea:** Uses importance sampling to update gradient subspaces in memory-efficient LLM optimization.

**Scope:** Deep learning. **Qualification:** A low-rank approximation with assumptions behind the convergence analysis, not lossless compression of every gradient.

**Optimizer relevance:** Uses importance sampling to refresh low-rank optimization subspaces and avoid permanently restricting training to a frozen subspace.

**Evidence:** Official accepted-paper title and abstract.

### CTSketch: Compositional Tensor Sketching for Scalable Neurosymbolic Learning

**NeurIPS 2025 · Accept (poster)** · Seewon Choi; Alaia Solko-Breslin; Rajeev Alur; Eric Wong

[OpenReview](<https://openreview.net/forum?id=mor7s1NGBV>) · [Official program](<https://neurips.cc/virtual/2025/poster/116184>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/6d53193a098b982229340a7c3eb0ecbf-Paper-Conference.pdf>)

**Categories:** X4 — Randomized sketching and kernel approximations.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/6d53193a098b982229340a7c3eb0ecbf-Abstract-Conference.html>)

**Quantity:** Output distributions of composed symbolic programs.

**Computational idea:** CTSketch decomposes symbolic programs and represents subprogram behavior with tensor sketches for differentiable neurosymbolic learning.

**Scope:** Deep learning. **Qualification:** The distribution is approximated; sketch size and compositional structure control error.

**Evidence:** Official accepted-paper title and abstract.

### Differentially Private Federated Low Rank Adaptation Beyond Fixed-Matrix

**NeurIPS 2025 · Accept (poster)** · Ming Wen; Jiaqi Zhu; Yuedong Xu; Yipeng Zhou; DINGDING HAN

[OpenReview](<https://openreview.net/forum?id=TecJ926Vgn>) · [Official program](<https://neurips.cc/virtual/2025/poster/117836>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/a686ddca183f72ee9f3f04896eb11bcb-Paper-Conference.pdf>)

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; X4 — Randomized sketching and kernel approximations.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/a686ddca183f72ee9f3f04896eb11bcb-Abstract-Conference.html>)

**Quantity:** Private aggregation of two-factor low-rank adapters.

**Computational idea:** FedASK uses a double-sketch pipeline inspired by randomized SVD to reconstruct global low-rank factors.

**Scope:** Deep learning. **Qualification:** Its exact-aggregation property must be read together with the sketch construction and privacy noise; it is not exact noiseless centralized training.

**Optimizer relevance:** FedASK uses two stages of sketching to aggregate private federated LoRA updates while allowing both adapter factors to change.

**Evidence:** Official accepted-paper title and abstract.

### Sketch-Augmented Features Improve Learning Long-Range Dependencies in Graph Neural Networks

**NeurIPS 2025 · Accept (poster)** · Ryien Hosseini; Filippo Simini; Venkatram Vishwanath; Rebecca Willett; Henry Hoffmann

[OpenReview](<https://openreview.net/forum?id=gXoMU9YYdY>) · [Official program](<https://neurips.cc/virtual/2025/poster/116734>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/6ec23290bd9c728558ff882e44e2f28a-Paper-Conference.pdf>)

**Categories:** X4 — Randomized sketching and kernel approximations.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/6ec23290bd9c728558ff882e44e2f28a-Abstract-Conference.html>)

**Quantity:** Global node-feature embeddings for GNNs.

**Computational idea:** Randomized sketched features provide efficient access to nonlocal graph information.

**Scope:** Deep learning. **Qualification:** These are compressed global features, not exact all-pairs message passing.

**Evidence:** Official accepted-paper title and abstract.

### Sketched Adaptive Distributed Deep Learning: A Sharp Convergence Analysis

**NeurIPS 2025 · Accept (poster)** · Zhijie Chen; Qiaobo Li; Arindam Banerjee

[OpenReview](<https://openreview.net/forum?id=XIeE8jbM4K>) · [Official program](<https://neurips.cc/virtual/2025/poster/117527>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/308224aa2da89a3b4257d95b8b2be634-Paper-Conference.pdf>)

**Categories:** E — Training stabilization and distributed optimization; X4 — Randomized sketching and kernel approximations.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/308224aa2da89a3b4257d95b8b2be634-Abstract-Conference.html>)

**Quantity:** Sketched adaptive preconditioners in distributed training.

**Computational idea:** SADL compresses moment/preconditioner information using sketches, with guarantees expressed through intrinsic dimension.

**Scope:** Deep learning. **Qualification:** Sketching introduces approximation; probabilistic guarantees depend on the stated assumptions.

**Optimizer relevance:** SADL uses sketched adaptive preconditioning to reduce communication and memory costs in distributed learning.

**Evidence:** Official accepted-paper title and abstract.

### When Kernels Multiply, Clusters Unify: Fusing Embeddings with the Kronecker Product

**NeurIPS 2025 · Accept (poster)** · Youqi WU; Jingwei Zhang; Farzan Farnia

[OpenReview](<https://openreview.net/forum?id=XougXwZAHI>) · [Official program](<https://neurips.cc/virtual/2025/poster/117475>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/317565cd8f3e83be1163f6324b4a4569-Paper-Conference.pdf>)

**Categories:** X4 — Randomized sketching and kernel approximations.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/317565cd8f3e83be1163f6324b4a4569-Abstract-Conference.html>)

**Quantity:** Kronecker-product embedding and product-kernel approximation.

**Computational idea:** RP-KrossFuse uses random projections to compress the large feature space induced by multiplying kernels.

**Scope:** Deep learning. **Qualification:** The projected representation approximates the full product kernel; finite sketch size introduces error.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/yokiwuuu/KrossFuse.>). Links extracted from the accepted abstract; code was not tested.


## X5 — Attention, state-space algebra and parallel scans

### ConvT3: Structured State Kernels for Convolutional State Space Models

**ICLR 2026 · Accept (Poster)** · Jaeyoung Hong; YunYoung Choi; Joohwan Ko; Minseon Gwak

[OpenReview](<https://openreview.net/forum?id=w7csRoB5CO>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006756>) · [PDF](<https://openreview.net/pdf?id=w7csRoB5CO>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Convolutional state-space updates with spatial kernels.

**Computational idea:** Diagonalize structured tridiagonal Toeplitz tensors to parallelize extended spatial state kernels.

**Scope:** Deep learning. **Qualification:** Exact structural reformulation for the constrained kernel family.

**Evidence:** Official accepted-paper title and abstract.

### DASH: Deterministic Attention Scheduling for High-throughput Reproducible LLM Training

**ICLR 2026 · Accept (Poster)** · Xinwei Qiang; Hongmin chen; Shixuan Sun; Jingwen Leng; Xin Liu; Minyi Guo

[OpenReview](<https://openreview.net/forum?id=bMi5ssfPoM>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008616>) · [PDF](<https://openreview.net/pdf?id=bMi5ssfPoM>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Deterministic attention backward reductions.

**Computational idea:** Model computation as a DAG and reorder query tiles/reduction scheduling to reduce stalls.

**Scope:** Deep learning. **Qualification:** Scheduling optimality is within the stated DAG model; distinct from ICML DASH for Shampoo.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/SJTU-Liquid/deterministic-FA3.>). Links extracted from the accepted abstract; code was not tested.

### FlexLinearAttention: Compiling a Unified Abstraction into Scalable Kernels for Linear Attention

**ICLR 2026 · Accept (Poster)** · Haojie Duanmu; Size Zheng; Ningxin Zheng; Jianqiao Lu; Xuegui Zheng; Xingcheng Zhang; Li-Wen Chang; Xin Liu; Dahua Lin

[OpenReview](<https://openreview.net/forum?id=N4jJQvQSiN>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009893>) · [PDF](<https://openreview.net/pdf?id=N4jJQvQSiN>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** High-performance linear-attention kernels.

**Computational idea:** Compile intra-chunk computation, state propagation and output merging with fused computation/communication.

**Scope:** Deep learning. **Qualification:** Supports a class of linear-attention programs, not every attention operator.

**Evidence:** Official accepted-paper title and abstract.

### Householder-Diagonalized Linear Attention (HDLA): Utilizing Enhanced Decay Mechanism for Efficient Sequence Modeling

**ICLR 2026 · Accept (Poster)** · Jiefu Zhang; Qin Zhen; Jiabo Tong; Shijie Mei; Jiakui Hu; Yuqi Pan; Anjie Hu; Man Yao; Bo XU; Guoqi Li

[OpenReview](<https://openreview.net/forum?id=HVFjzaQeig>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010385>) · [PDF](<https://openreview.net/pdf?id=HVFjzaQeig>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Diagonal-plus-low-rank attention state updates.

**Computational idea:** Use Householder-based structure and a rank-generalized chunkwise parallel algorithm.

**Scope:** Deep learning. **Qualification:** Restricted structured decay matrices enable the efficient algorithm.

**Evidence:** Official accepted-paper title and abstract.

### LaplacianFormer:Rethinking Linear Attention with Laplacian Kernel

**ICLR 2026 · Accept (Poster)** · Zhe Feng; Sen Lian; Changwei Wang; Muyang Zhang; Tianlong Tan; Rongtao Xu; Weiliang Meng; Xiaopeng Zhang

[OpenReview](<https://openreview.net/forum?id=bJZExGYWqx>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008622>) · [PDF](<https://openreview.net/pdf?id=bJZExGYWqx>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Laplacian-kernel attention and inverse actions.

**Computational idea:** Combine a Nyström kernel approximation with a Newton-Schulz solver and custom CUDA implementation.

**Scope:** Deep learning. **Qualification:** Approximates a Laplacian-kernel attention operator, not standard softmax attention.

**Evidence:** Official accepted-paper title and abstract.

### Local Linear Attention: An Optimal Interpolation of Linear and Softmax Attention For Test-Time Regression

**ICLR 2026 · Accept (Poster)** · Yifei Zuo; Yutong Yin; Zhichen Zeng; Ang Li; Banghua Zhu; Zhaoran Wang

[OpenReview](<https://openreview.net/forum?id=WGpzi489XY>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009059>) · [PDF](<https://openreview.net/pdf?id=WGpzi489XY>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Local-linear test-time regression attention.

**Computational idea:** Derive memory-efficient primitives and blockwise FlashLLA kernels for local regression.

**Scope:** Deep learning. **Qualification:** A distinct attention estimator with its own compute and expressivity trade-offs.

**Evidence:** Official accepted-paper title and abstract.

### Log-Linear Attention

**ICLR 2026 · Accept (Poster)** · Guo; Songlin Yang; Tarushii Goel; Eric P Xing; Tri Dao; Yoon Kim

[OpenReview](<https://openreview.net/forum?id=mOJgZWkXKW>) · [Official program](<https://iclr.cc/virtual/2026/poster/10007581>) · [PDF](<https://openreview.net/pdf?id=mOJgZWkXKW>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Log-linear attention recurrences.

**Computational idea:** Maintain a logarithmically growing collection of hidden states with matrix-multiplication-rich parallel evaluation.

**Scope:** Deep learning. **Qualification:** A new attention family rather than exact softmax acceleration.

**Evidence:** Official accepted-paper title and abstract.

### MesaNet: Sequence Modeling by Locally Optimal Test-Time Training

**ICLR 2026 · Accept (Poster)** · Johannes von Oswald; Nino Scherrer; Seijin Kobayashi; Luca Versari; Songlin Yang; Maximilian Schlegel; Kaitlin Maile; Yanick Schimpf; Oliver Sieberling; Alexander Meulemans; Guillaume Lajoie; Rif A. Saurous; Charlotte Frenkel; Razvan Pascanu; Blaise Aguera y Arcas; Joao Sacramento

[OpenReview](<https://openreview.net/forum?id=xa3OnTb6c3>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006633>) · [PDF](<https://openreview.net/pdf?id=xa3OnTb6c3>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** In-context least-squares solutions at each token.

**Computational idea:** Use a numerically stable chunkwise Mesa layer and fast conjugate-gradient solves.

**Scope:** Deep learning. **Qualification:** Optimization solves require additional inference computation and finite tolerances.

**Evidence:** Official accepted-paper title and abstract.

### RACE Attention: A Strictly Linear-Time Attention for Long-Sequence Training

**ICLR 2026 · Accept (Poster)** · Sahil Joshi; Agniva Chowdhury; Amar Kanakamedala; Ekam Singh; Evan Tu; Anshumali Shrivastava

[OpenReview](<https://openreview.net/forum?id=RR8Lh8RHgA>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009492>) · [PDF](<https://openreview.net/pdf?id=RR8Lh8RHgA>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Long-context attention approximations.

**Computational idea:** Replace the exponential kernel with sharpened angular similarity and use Gaussian projections plus soft LSH.

**Scope:** Deep learning. **Qualification:** Changes the attention kernel; does not compute exact softmax attention in linear time.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Attention via Feature Sparsity

**ICLR 2026 · Accept (Poster)** · Yan Xie; Tiansheng Wen; Tang Da Huang; Bo Chen; Chenyu You; Stefanie Jegelka; Yifei Wang

[OpenReview](<https://openreview.net/forum?id=UspMJlGusi>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009189>) · [PDF](<https://openreview.net/pdf?id=UspMJlGusi>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Attention with sparse query/key features.

**Computational idea:** Operate directly on sparse feature overlaps in an IO-aware FlashSFA kernel.

**Scope:** Deep learning. **Qualification:** Uses sparse feature representations; not an exact replacement for arbitrary dense Q and K.

**Evidence:** Official accepted-paper title and abstract.

### Sequential Parallel Duality in Prefix Scannable Models

**ICLR 2026 · Accept (Poster)** · Morris Yau; Sharut Gupta; Valerie Engelmayer; Kazuki Irie; Stefanie Jegelka; Jacob Andreas

[OpenReview](<https://openreview.net/forum?id=tuLF84azND>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006941>) · [PDF](<https://openreview.net/pdf?id=tuLF84azND>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Sequential and parallel evaluations of sequence models.

**Computational idea:** Use prefix-scan structure and generalize state aggregation to prefix-scannable models.

**Scope:** Theory / foundations. **Qualification:** Complexity and equivalence depend on the particular aggregation construction.

**Evidence:** Official accepted-paper title and abstract.

### TyphoonMLA: A Mixed Naive-Absorb MLA Kernel For Shared Prefix

**ICLR 2026 · Accept (Poster)** · Ahmet Yüzügüler; Ahmet Çelik; Jiawei Zhuang; Lukas Cavigelli

[OpenReview](<https://openreview.net/forum?id=ZfCCwJ4Wcs>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008790>) · [PDF](<https://openreview.net/pdf?id=ZfCCwJ4Wcs>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Multi-head latent attention with shared prefixes.

**Computational idea:** Mix mathematically equivalent naive and absorbed formulations according to compute and bandwidth costs.

**Scope:** Deep learning. **Qualification:** Specialized to MLA and shared-prefix workloads.

**Evidence:** Official accepted-paper title and abstract.

### AdaSplash-2: Faster Differentiable Sparse Attention

**ICML 2026 · Accept (regular)** · Nuno M. T. Gonçalves; Hugo Pitorro; Vlad Niculae; Edoardo Ponti; Lei Li; Andre Martins; Marcos V. Treviso

[OpenReview](<https://openreview.net/forum?id=7qpvff2gWI>) · [Official program](<https://icml.cc/virtual/2026/poster/66022>) · [PDF](<https://openreview.net/pdf?id=7qpvff2gWI>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Entmax sparse-attention normalizer.

**Computational idea:** Use an on-chip score histogram to initialize root finding, then exploit zero blocks in GPU kernels.

**Scope:** Deep learning. **Qualification:** Computes entmax attention, which differs from softmax; iteration counts depend on inputs.

**Evidence:** Official accepted-paper title and abstract.

### Kalman Linear Attention: Parallel Bayesian Filtering For Efficient Language Modeling and State Tracking

**ICML 2026 · Accept (regular)** · Vaisakh Shaj; Cameron Barker; Aidan Scannell; Andras Szecsenyi; Elliot Crowley; Amos Storkey

[OpenReview](<https://openreview.net/forum?id=9h7sSJe4jN>) · [Official program](<https://icml.cc/virtual/2026/poster/65832>) · [PDF](<https://openreview.net/pdf?id=9h7sSJe4jN>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Kalman-style belief updates in sequence models.

**Computational idea:** Express filtering in information form to enable associative-scan parallel evaluation.

**Scope:** Deep learning. **Qualification:** Applies to the proposed reparameterized filtering layer.

**Evidence:** Official accepted-paper title and abstract.

### MDN: Parallelizing Stepwise Momentum for Delta Linear Attention

**ICML 2026 · Accept (regular)** · Yulong Huang; Xiang Liu; Hongxiang Huang; Xiaopeng LIN; Zunchang LIU; Xiaowen Chu; Zeke Xie; Bojun Cheng

[OpenReview](<https://openreview.net/forum?id=Sh3rKEAxlW>) · [Official program](<https://icml.cc/virtual/2026/poster/63901>) · [PDF](<https://openreview.net/pdf?id=Sh3rKEAxlW>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Delta-rule recurrences with stepwise momentum.

**Computational idea:** Geometrically reorder update coefficients to obtain a chunkwise parallel implementation with stable gating constraints.

**Scope:** Deep learning. **Qualification:** Changes recurrence dynamics and needs the proposed stability constraints.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/HuuYuLong/MomentumDeltaNet.>). Links extracted from the accepted abstract; code was not tested.

### MIMOMamba: From Scalar Duality to Matrix-Valued Attention

**ICML 2026 · Accept (regular)** · Yanbo Li; Richard Cornelius Suwandi; Feng Yin; Yiyong SUN; Wei Huang; Wenqiang Pu

[OpenReview](<https://openreview.net/forum?id=UmQ07sj13y>) · [Official program](<https://icml.cc/virtual/2026/poster/63671>) · [PDF](<https://openreview.net/pdf?id=UmQ07sj13y>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Matrix-valued state-space recurrences.

**Computational idea:** Use a shared matrix-polynomial parameterization to ensure commutativity and retain efficient dual computation.

**Scope:** Deep learning. **Qualification:** Defines a structured model family rather than accelerating arbitrary recurrences.

**Evidence:** Official accepted-paper title and abstract.

### On Structured State-Space Duality

**ICML 2026 · Accept (regular)** · Jerry Yao-Chieh Hu; Xiwen Zhang; Ali ElSheikh; Weimin Wu; Han Liu

[OpenReview](<https://openreview.net/forum?id=DKathyl3XN>) · [Official program](<https://icml.cc/virtual/2026/poster/65468>) · [PDF](<https://openreview.net/pdf?id=DKathyl3XN>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Equivalent state-space and attention operators.

**Computational idea:** Generalize structured state-space duality to diagonal state matrices using semiseparable structure.

**Scope:** Theory / foundations. **Qualification:** The paper identifies conditions for equivalence and failure for standard softmax attention.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/MAGICS-LAB/state_space_daulity.>). Links extracted from the accepted abstract; code was not tested.

### PLASH: Provably Linear-Time Attention with Selective Higher-Order Feature Sketching

**ICML 2026 · Accept (regular)** · Yuwen Huang; Xiang Pan

[OpenReview](<https://openreview.net/forum?id=CYg2w0YKM4>) · [Official program](<https://icml.cc/virtual/2026/poster/65541>) · [PDF](<https://openreview.net/pdf?id=CYg2w0YKM4>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Attention through enriched key-value prototypes.

**Computational idea:** Combine learned prototypes with randomized higher-order polynomial features and per-input error certificates.

**Scope:** Deep learning. **Qualification:** Softmax over prototypes is exact; the resulting operator approximates full-token softmax attention.

**Evidence:** Official accepted-paper title and abstract.

### Preconditioned DeltaNet: Curvature-aware Sequence Modeling for Linear Recurrences

**ICML 2026 · Accept (regular)** · Neehal Tumma; Noel Loo; Daniela Rus

[OpenReview](<https://openreview.net/forum?id=UC6YiTOeKb>) · [Official program](<https://icml.cc/virtual/2026/poster/63733>) · [PDF](<https://openreview.net/pdf?id=UC6YiTOeKb>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Curvature-aware delta-rule recurrences.

**Computational idea:** Derive online least-squares preconditioning and implement diagonal approximations with chunkwise parallel algorithms.

**Scope:** Deep learning. **Qualification:** Practical preconditioners are diagonal approximations.

**Evidence:** Official accepted-paper title and abstract.

### Push, Pop, Parallelize: Stack-Augmented Linear Attention via the Delta Rule

**ICML 2026 · Accept (regular)** · Anh T Nguyen; Saleh Momeni; Ashutosh Chaubey; Changnan Xiao; Bing Liu

[OpenReview](<https://openreview.net/forum?id=l1v359RKe0>) · [Official program](<https://icml.cc/virtual/2026/poster/61979>) · [PDF](<https://openreview.net/pdf?id=l1v359RKe0>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Differentiable stack updates in sequence models.

**Computational idea:** Represent push/pop behavior as linear delta-rule operations so it can be parallelized across tokens.

**Scope:** Deep learning. **Qualification:** A specialized stack-augmented architecture.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/teeann/DeltaStack.>). Links extracted from the accepted abstract; code was not tested.

### Scout Before You Attend: Sketch-and-Walk Sparse Attention for Efficient LLM Inference

**ICML 2026 · Accept (regular)** · Hoang Anh Duy Le; Sahil Joshi; Zeyu Yang; Zhaozhuo Xu; Anshumali Shrivastava

[OpenReview](<https://openreview.net/forum?id=uCLVPafHqd>) · [Official program](<https://icml.cc/virtual/2026/poster/61048>) · [PDF](<https://openreview.net/pdf?id=uCLVPafHqd>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Sparse attention block selection.

**Computational idea:** Estimate scores with Hadamard sketches and aggregate influence through deterministic walks across layers.

**Scope:** Deep learning. **Qualification:** Training-free sparse approximation; preserves only selected attention blocks.

**Evidence:** Official accepted-paper title and abstract.

### Sparser Block-Sparse Attention via Token Permutation

**ICML 2026 · Accept (regular)** · Xinghao Wang; Pengyu Wang; Dong Zhang; Chenkun Tan; Shaojun Zhou; Zhaoxiang Liu; Shiguo Lian; Fangxu Liu; Kai Song; Xipeng Qiu

[OpenReview](<https://openreview.net/forum?id=5u3Ra6Qf5C>) · [Official program](<https://icml.cc/virtual/2026/poster/66195>) · [PDF](<https://openreview.net/pdf?id=5u3Ra6Qf5C>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Block-sparse attention products.

**Computational idea:** Permute tokens to concentrate important entries into fewer blocks and apply custom permuted attention kernels.

**Scope:** Deep learning. **Qualification:** Permutation preserves the dense operator when handled consistently; sparsification remains approximate.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/xinghaow99/pbs-attn>). Links extracted from the accepted abstract; code was not tested.

### Training-Free Hashing-Based Attention via Binary Principal Components

**ICML 2026 · Accept (regular)** · Daohai Yu; Zhanpeng Zeng; Keyu Chen; Wenhao Li; Zhifeng Shen; Luxi Lin; Ruizhi Qiao; Xing Sun; Rongrong Ji

[OpenReview](<https://openreview.net/forum?id=4spHlgHY9x>) · [Official program](<https://icml.cc/virtual/2026/poster/66306>) · [PDF](<https://openreview.net/pdf?id=4spHlgHY9x>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Binary codes for attention retrieval.

**Computational idea:** Build data-aware binary principal components to retrieve key-value entries without gradient-based hash training.

**Scope:** Deep learning. **Qualification:** Sparse approximation of full attention.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/yudaohai666/BPC.>). Links extracted from the accepted abstract; code was not tested.

### WildCat: Near-Linear Attention in Theory and Practice

**ICML 2026 · Accept (regular)** · Tobias Schröder; Lester Mackey

[OpenReview](<https://openreview.net/forum?id=lfqyLp4hZm>) · [Official program](<https://icml.cc/virtual/2026/poster/61920>) · [PDF](<https://openreview.net/pdf?id=lfqyLp4hZm>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

**Quantity:** Approximate attention outputs.

**Computational idea:** Choose a small weighted coreset using randomly pivoted Cholesky and optimize its reconstruction weights.

**Scope:** Deep learning. **Qualification:** Near-linear/error results rely on bounded-input assumptions; approximates full attention.

**Evidence:** Official accepted-paper title and abstract.

### Degrees of Freedom for Linear Attention: Distilling Softmax Attention with Optimal Feature Efficiency

**NeurIPS 2025 · Accept (poster)** · Naoki Nishikawa; Rei Higuchi; Taiji Suzuki

[OpenReview](<https://openreview.net/forum?id=7qq1UeCYL6>) · [Official program](<https://neurips.cc/virtual/2025/poster/119670>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/c98ef086dc70d528e1c1aa1e66893365-Paper-Conference.pdf>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/c98ef086dc70d528e1c1aa1e66893365-Abstract-Conference.html>)

**Quantity:** Feature dimensions for approximating softmax attention.

**Computational idea:** Uses statistical degrees of freedom to allocate linear-attention feature dimensions and trains layer-specific features.

**Scope:** Deep learning. **Qualification:** Distillation approximates softmax attention; guarantees depend on the feature and data assumptions.

**Evidence:** Official accepted-paper title and abstract.

### Efficient Low Rank Attention for Long-Context Inference in Large Language Models

**NeurIPS 2025 · Accept (poster)** · Li Tenghui; Guoxu Zhou; Xuyang Zhao; Yuning Qiu; Qibin Zhao

[OpenReview](<https://openreview.net/forum?id=Mc0eJHZhW5>) · [Official program](<https://neurips.cc/virtual/2025/poster/118451>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/36db9d16a9f80ede9e69d5d174cfd6ea-Paper-Conference.pdf>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/36db9d16a9f80ede9e69d5d174cfd6ea-Abstract-Conference.html>)

**Quantity:** Proxy attention scores and KV-cache retrieval.

**Computational idea:** LRQK factorizes query/key matrices to rank low-cost proxy scores, then retrieves selected full-precision KV entries.

**Scope:** Deep learning. **Qualification:** Full precision on selected entries does not make token-sparse attention identical to full dense attention.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/tenghuilee/LRQK>). Links extracted from the accepted abstract; code was not tested.

### Flash Invariant Point Attention

**NeurIPS 2025 · Accept (spotlight)** · Andrew Liu; Axel Elaldi; Nicholas Franklin; Nathan Russell; Gurinder Atwal; Yih-En Ban; Olivia Viessmann

[OpenReview](<https://openreview.net/forum?id=gKsG5qR3Bt>) · [Official program](<https://neurips.cc/virtual/2025/poster/116755>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/07ea874e9e4f71ec6680a3574a485a36-Paper-Conference.pdf>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/07ea874e9e4f71ec6680a3574a485a36-Abstract-Conference.html>)

**Quantity:** Geometry-aware invariant point attention.

**Computational idea:** FlashIPA factorizes invariant point attention to reuse efficient FlashAttention operations.

**Scope:** Deep learning. **Qualification:** Efficiency and quality claims concern the proposed IPA formulation and evaluated structural-biology models.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/flagshippioneering/flash_ipa.>). Links extracted from the accepted abstract; code was not tested.

### FlashBias: Fast Computation of Attention with Bias

**NeurIPS 2025 · Accept (poster)** · Haixu Wu; Minghao Guo; Yuezhou Ma; Yuanxu Sun; Jianmin Wang; Wojciech Matusik; Mingsheng Long

[OpenReview](<https://openreview.net/forum?id=7L4NvUtZY3>) · [Official program](<https://neurips.cc/virtual/2025/poster/119716>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1dc3d70df51a218497529df998a8a8ce-Paper-Conference.pdf>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/1dc3d70df51a218497529df998a8a8ce-Abstract-Conference.html>)

**Quantity:** Attention with additive bias matrices.

**Computational idea:** FlashBias exploits low-rank structure to retain efficient fused attention for biased scores.

**Scope:** Deep learning. **Qualification:** Exact for supported bias families; general biases use approximation and must be distinguished from those exact cases.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/thuml/FlashBias.>). Links extracted from the accepted abstract; code was not tested.

### GSPN-2: Efficient Parallel Sequence Modeling

**NeurIPS 2025 · Accept (poster)** · Hongjun Wang; yitong jiang; Collin McCarthy; David Wehr; Hanrong Ye; Xinhao Li; Ka Chun Cheung; Wonmin Byeon; Jinwei Gu; Ke Chen; Kai Han; Hongxu Yin; Pavlo Molchanov; Jan Kautz; Sifei Liu

[OpenReview](<https://openreview.net/forum?id=9yG7LGYfHS>) · [Official program](<https://neurips.cc/virtual/2025/poster/119496>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/550ab405d0addd3de5b70e57b44878df-Paper-Conference.pdf>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/550ab405d0addd3de5b70e57b44878df-Abstract-Conference.html>)

**Quantity:** Two-dimensional spatial propagation.

**Computational idea:** GSPN-2 combines structured shared propagation matrices with a fused GPU kernel and shared-memory staging.

**Scope:** Deep learning. **Qualification:** A jointly redesigned model and implementation; runtime results cannot be interpreted as exact softmax-attention acceleration.

**Evidence:** Official accepted-paper title and abstract.

### Linear Attention for Efficient Bidirectional Sequence Modeling

**NeurIPS 2025 · Accept (poster)** · Arshia Afzal; Elias Abad Rocamora; Leyla Candogan; Pol Puigdemont; Francesco Tonin; Yongtao Wu; Mahsa Shoaran; Volkan Cevher

[OpenReview](<https://openreview.net/forum?id=Ar62cqTduE>) · [Official program](<https://neurips.cc/virtual/2025/poster/119431>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/71845d09f05d40d030fa3cde8b5dcd13-Paper-Conference.pdf>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/71845d09f05d40d030fa3cde8b5dcd13-Abstract-Conference.html>)

**Quantity:** Bidirectional linear-attention sequence operators.

**Computational idea:** LION gives equivalent full-matrix, bidirectional recurrent and chunkwise-parallel forms.

**Scope:** Deep learning. **Qualification:** Equivalence is within the supported linear-attention family, not with an arbitrary softmax Transformer.

**Evidence:** Official accepted-paper title and abstract.

### pLSTM: parallelizable Linear Source Transition Mark networks

**NeurIPS 2025 · Accept (poster)** · Korbinian Pöppel; Richard Freinschlag; Thomas Schmied; Wei Lin; Sepp Hochreiter

[OpenReview](<https://openreview.net/forum?id=2sa13vyCn0>) · [Official program](<https://neurips.cc/virtual/2025/poster/120092>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/0d5c9d43eb13c98db21eeb92c7c986d8-Paper-Conference.pdf>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/0d5c9d43eb13c98db21eeb92c7c986d8-Abstract-Conference.html>)

**Quantity:** Parallel recurrent computation on grids and DAGs.

**Computational idea:** pLSTM extends scan-like algebra to DAGs, with logarithmic-depth grid implementations using tensor operations.

**Scope:** Deep learning. **Qualification:** Applies to the proposed structured recurrence, not arbitrary nonlinear recurrent networks.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/ml-jku/plstm_experiments.>). Links extracted from the accepted abstract; code was not tested.

### Structured Sparse Transition Matrices to Enable State Tracking in State-Space Models

**NeurIPS 2025 · Accept (spotlight)** · Aleksandar Terzic; Nicolas Menet; Michael Hersche; Thomas Hofmann; Abbas Rahimi

[OpenReview](<https://openreview.net/forum?id=RDbuSCWhad>) · [Official program](<https://neurips.cc/virtual/2025/poster/118046>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/77b830c18836a9b2e1395a4936dd687a-Paper-Conference.pdf>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/77b830c18836a9b2e1395a4936dd687a-Abstract-Conference.html>)

**Quantity:** Structured state-transition products and scans.

**Computational idea:** PD-SSM combines column-one-hot and diagonal factors to make recurrent scans linear in state size.

**Scope:** Deep learning. **Qualification:** The transition structure restricts the operator class while providing specified finite-state expressivity guarantees.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/IBM/expressive-sparse-state-space-model.>). Links extracted from the accepted abstract; code was not tested.

### Tensor Product Attention Is All You Need

**NeurIPS 2025 · Accept (spotlight)** · Yifan Zhang; Yifeng Liu; Huizhuo Yuan; Zhen Qin; Yang Yuan; Quanquan Gu; Andrew Yao

[OpenReview](<https://openreview.net/forum?id=ECTxVRFhUa>) · [Official program](<https://neurips.cc/virtual/2025/poster/119152>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/a301ec7cb9e07dc050403e2eb11d0041-Paper-Conference.pdf>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/a301ec7cb9e07dc050403e2eb11d0041-Abstract-Conference.html>)

**Quantity:** Attention queries, keys, values and KV-cache representation.

**Computational idea:** Tensor Product Attention factorizes token-dependent Q/K/V representations into contextual low-rank components.

**Scope:** Deep learning. **Qualification:** A changed attention parameterization, not an exact compression of every pretrained dense attention layer.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/tensorgi/TPA.>). Links extracted from the accepted abstract; code was not tested.

### Tiled Flash Linear Attention: More Efficient Linear RNN and xLSTM Kernels

**NeurIPS 2025 · Accept (poster)** · Maximilian Beck; Korbinian Pöppel; Phillip Lippe; Sepp Hochreiter

[OpenReview](<https://openreview.net/forum?id=b6H64u6TqI>) · [Official program](<https://neurips.cc/virtual/2025/poster/117208>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/6cb81234ab47027e991728ed7dd76735-Paper-Conference.pdf>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/6cb81234ab47027e991728ed7dd76735-Abstract-Conference.html>)

**Quantity:** Chunkwise linear-RNN and mLSTM sequence operators.

**Computational idea:** Tiled Flash Linear Attention adds parallelism within chunks to increase arithmetic intensity and reduce intermediate state traffic.

**Scope:** Deep learning. **Qualification:** Kernel efficiency is hardware- and shape-dependent; an mLSTM variant also changes the model operator.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/NX-AI/mlstm_kernels>). Links extracted from the accepted abstract; code was not tested.

### ZeCO: Zero-Communication Overhead Sequence Parallelism for Linear Attention

**NeurIPS 2025 · Accept (poster)** · Yuhong CHOU; Zehao Liu; Rui-Jie Zhu; Xinyi Wan; Tianjian Li; Congying Chu; Qian Liu; Jibin Wu; Zejun MA

[OpenReview](<https://openreview.net/forum?id=eHRFb3DSZS>) · [Official program](<https://neurips.cc/virtual/2025/poster/116936>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/c7de4d7804077094c10c8f1ba960241c-Paper-Conference.pdf>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/c7de4d7804077094c10c8f1ba960241c-Abstract-Conference.html>)

**Quantity:** Distributed state propagation for linear attention.

**Computational idea:** ZeCO uses an All-Scan collective to provide each device the initial state needed for its sequence segment.

**Scope:** Deep learning. **Qualification:** Zero-overhead terminology denotes effectively hidden/negligible overhead under the analyzed setup, not an absence of communication.

**Evidence:** Official accepted-paper title and abstract.

### ZeroS: Zero‑Sum Linear Attention for Efficient Transformers

**NeurIPS 2025 · Accept (spotlight)** · Jiecheng Lu; Xu Han; Yan Sun; Viresh Pati; Yubin Kim; Siddhartha Somani; Shihao Yang

[OpenReview](<https://openreview.net/forum?id=Ms6IXbfzzX>) · [Official program](<https://neurips.cc/virtual/2025/poster/118425>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1363163299a172662dcf0c0f9932acf6-Paper-Conference.pdf>)

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/1363163299a172662dcf0c0f9932acf6-Abstract-Conference.html>)

**Quantity:** Signed linear-time attention aggregation.

**Computational idea:** ZeroS removes the constant softmax component and rescales the remaining zero-sum contribution.

**Scope:** Deep learning. **Qualification:** Defines a different linear-attention operator and expressivity class; it is not identical to general softmax attention.

**Evidence:** Official accepted-paper title and abstract.


## X6 — Matrix and tensor methods for compression

### ARMOR: High-Performance Semi-Structured Pruning via Adaptive Matrix Factorization

**ICLR 2026 · Accept (Poster)** · Lawrence Liu; Alexander Liu; Mengdi Wang; Tuo Zhao; Lin Yang

[OpenReview](<https://openreview.net/forum?id=8NE554wv0m>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011207>) · [PDF](<https://openreview.net/pdf?id=8NE554wv0m>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Semi-structured sparse weight factors.

**Computational idea:** Factor weights into a 2:4 sparse core with block-diagonal pre/post corrections; fit by block coordinate descent.

**Scope:** Deep learning. **Qualification:** Guarantee compares proxy losses; downstream accuracy is empirical.

**Evidence:** Official accepted-paper title and abstract.

### CARE: Covariance-Aware and Rank-Enhanced Decomposition for Enabling Multi-Head Latent Attention

**ICLR 2026 · Accept (Poster)** · Zhongzhu Zhou; Fengxiang Bie; Ziyan Chen; Zhenyu Zhang; Yibo Yang; Junxiong Wang; Ben Athiwaratkun; Xiaoxia (Shirley) Wu; Shuaiwen Song

[OpenReview](<https://openreview.net/forum?id=DVurf4kGag>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010773>) · [PDF](<https://openreview.net/pdf?id=DVurf4kGag>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Covariance-aware factors converting GQA to MLA.

**Computational idea:** Match activations with covariance-aware factorization, redistribute rank and reparameterize at a fixed KV budget.

**Scope:** Deep learning. **Qualification:** Conversion may require a short recovery fine-tune; it changes the architecture.

**Evidence:** Official accepted-paper title and abstract.

### HEAPr: Hessian-based Efficient Atomic Expert Pruning in Output Space

**ICLR 2026 · Accept (Poster)** · Ke Li; Zheng Yang; Zhongbin Zhou; Xuefeng; Zhonglin Jiang; Wenxiao Wang

[OpenReview](<https://openreview.net/forum?id=JAbMgS7gl6>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010227>) · [PDF](<https://openreview.net/pdf?id=JAbMgS7gl6>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Second-order importance of atomic MoE experts.

**Computational idea:** Move curvature computations from expert parameters to atomic-expert outputs, reducing the stated storage order.

**Scope:** Deep learning. **Qualification:** Pruning importance uses a second-order approximation.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/LLIKKE/HEAPr>). Links extracted from the accepted abstract; code was not tested.

### KBVQ-MoE: KLT-guided SVD with Bias-Corrected Vector Quantization for MoE Large Language Models

**ICLR 2026 · Accept (Poster)** · Zukang Xu; Zhixiong Zhao; Xing Hu; Zhixuan Chen; Dawei Yang

[OpenReview](<https://openreview.net/forum?id=veFs5UfYq9>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006798>) · [PDF](<https://openreview.net/pdf?id=veFs5UfYq9>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Shared and expert-specific MoE weight factors.

**Computational idea:** Use input-driven KLT-guided SVD to remove cross-expert redundancy before vector quantization and bias correction.

**Scope:** Deep learning. **Qualification:** Post-training compression with data-dependent calibration.

**Evidence:** Official accepted-paper title and abstract.

### LeSTD: LLM Compression via Learning-based Sparse Tensor Decomposition

**ICLR 2026 · Accept (Poster)** · Yi Li; Zhichun Guo; Miao Yin; Bingzhe Li

[OpenReview](<https://openreview.net/forum?id=0oHaazjMUX>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011895>) · [PDF](<https://openreview.net/pdf?id=0oHaazjMUX>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Sparse tensor cores for attention compression.

**Computational idea:** Learn shared orthogonal bases, then prune and refit an importance-selected sparse core.

**Scope:** Deep learning. **Qualification:** Approximate tensor compression; no claim of exact weight recovery.

**Evidence:** Official accepted-paper title and abstract.

### QKV Projections Require a Fraction of Their Memory

**ICLR 2026 · Accept (Poster)** · Malik Khalaf; Yara Shamshoum; Nitzan Hodos; Yuval Sieradzki; Assaf Schuster

[OpenReview](<https://openreview.net/forum?id=Xvpk1g02u2>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008929>) · [PDF](<https://openreview.net/pdf?id=Xvpk1g02u2>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Stored activations for Q/K/V projection gradients.

**Computational idea:** Use Point-Approximate Matrix Multiplication to compress projection activations while composing with efficient attention.

**Scope:** Deep learning. **Qualification:** Approximate saved-activation computation; compression and training quality are empirical.

**Evidence:** Official accepted-paper title and abstract.

### QWHA: Quantization-Aware Walsh-Hadamard Adaptation for Parameter-Efficient Fine-Tuning on Large Language Models

**ICLR 2026 · Accept (Poster)** · Hyesung Jeon; Seojune Lee; Beomseok Kang; Yulhwa Kim; jae-joon kim

[OpenReview](<https://openreview.net/forum?id=QMN4ERDdp4>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009595>) · [PDF](<https://openreview.net/pdf?id=QMN4ERDdp4>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Quantization-aware adapter updates.

**Computational idea:** Use Walsh-Hadamard transform adapters with adaptive parameter selection and refined initialization.

**Scope:** Deep learning. **Qualification:** A transform-structured adapter rather than unrestricted dense fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

### SAES-SVD: Self-Adaptive Suppression of Accumulated and Local Errors for SVD-based LLM Compression

**ICLR 2026 · Accept (Poster)** · Xing Hu; Dawei Yang; Yuan Cheng; Zhixuan Chen; Zukang Xu

[OpenReview](<https://openreview.net/forum?id=KMAYsQO8pU>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010139>) · [PDF](<https://openreview.net/pdf?id=KMAYsQO8pU>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Low-rank layers compensating accumulated compression error.

**Computational idea:** Derive a closed-form solution from second-order activation statistics and adapt local-versus-cumulative error weighting.

**Scope:** Deep learning. **Qualification:** Closed form solves the proposed surrogate objective, not the full end-to-end loss.

**Evidence:** Official accepted-paper title and abstract.

### SERQ: Saliency-Aware Low-Rank Error Reconstruction for LLM Quantization

**ICLR 2026 · Accept (Poster)** · Yeonsik Park; Hyeonseong Kim; Seungkyu Choi

[OpenReview](<https://openreview.net/forum?id=nFjj8NEBqv>) · [Official program](<https://iclr.cc/virtual/2026/poster/10007493>) · [PDF](<https://openreview.net/pdf?id=nFjj8NEBqv>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Low-rank quantization-error compensation.

**Computational idea:** Combine saliency-aware reconstruction, activation flattening and offline permutations with a single compensation path.

**Scope:** Deep learning. **Qualification:** Approximate reconstruction; evaluate latency in the intended low-bit execution setting.

**Evidence:** Official accepted-paper title and abstract.

### SSDi8: Accurate and Efficient 8-bit Quantization for State Space Duality

**ICLR 2026 · Accept (Poster)** · Hyunwoo Kim; BYOUNGCHAN KO; Minseok Kang; Minwoo Kim; Dongjin Lee; Jaehoon Lee; Sungroh Yoon; Dahuin Jung

[OpenReview](<https://openreview.net/forum?id=pjMDZJd4rT>) · [Official program](<https://iclr.cc/virtual/2026/poster/10007309>) · [PDF](<https://openreview.net/pdf?id=pjMDZJd4rT>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Persistent INT8 state-space-duality computations.

**Computational idea:** Separate elementwise from matrix multiplications to reuse quantized activations and add channelwise error correction.

**Scope:** Deep learning. **Qualification:** Low-precision approximation tailored to SSD/Mamba-2.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/cau-hai-lab/SSDi8.>). Links extracted from the accepted abstract; code was not tested.

### TD-MoE: Tensor Decomposition for MoE Models

**ICLR 2026 · Accept (Poster)** · Yuebin XU; YANHONG WANG; Xuemei Peng; Hui Zang; Minghao Chen; Pengfei Xia; Zeyi Wen

[OpenReview](<https://openreview.net/forum?id=D9cnZNZfxX>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010804>) · [PDF](<https://openreview.net/pdf?id=D9cnZNZfxX>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Jointly compressed MoE expert tensors.

**Computational idea:** Tensorize experts, apply multilinear whitening and allocate ranks across three dimensions.

**Scope:** Deep learning. **Qualification:** Low-rank tensor approximation of original expert weights.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/ust-xu/TD-MoE.>). Links extracted from the accepted abstract; code was not tested.

### TurboBoA: Faster and Exact Attention-aware Quantization without Backpropagation

**ICLR 2026 · Accept (Poster)** · Junhan Kim; Yeo Jeong Park; Seungwoo Son; Chungman Lee; Ho-young Kim; Joonyoung Kim; Yongkweon Jeon

[OpenReview](<https://openreview.net/forum?id=HA0TnV8r7x>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010426>) · [PDF](<https://openreview.net/pdf?id=HA0TnV8r7x>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Attention-aware quantization error compensation.

**Computational idea:** Jointly quantize output channels using closed-form compensation, propagated-error correction and coordinate-descent grid refinement.

**Scope:** Deep learning. **Qualification:** Exactness concerns the derived compensation rule/objective, not lossless model quantization.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2602.04929v1>): Section 3.1, Proposition 3.1, equations 4-5 and Algorithm 1; joint-channel compensation with Kronecker-structured Hessians. Exact compensation for the stated quadratic problem does not mean lossless quantization.

**Code links listed by authors:** [Repository](<https://github.com/SamsungLabs/TurboBoA.>). Links extracted from the accepted abstract; code was not tested.

### UniQL: Unified Quantization and Low-rank Compression for Adaptive Edge LLMs

**ICLR 2026 · Accept (Poster)** · Hung-Yueh Chiang; Chi-Chih Chang; Yu-Chen Lu; Chien-Yu Lin; Kai-Chiang Wu; Mohamed Abdelfattah; Diana Marculescu

[OpenReview](<https://openreview.net/forum?id=iOGu4wtDTF>) · [Official program](<https://iclr.cc/virtual/2026/poster/10007967>) · [PDF](<https://openreview.net/pdf?id=iOGu4wtDTF>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Jointly quantized and low-rank edge-model weights.

**Computational idea:** Use structured sorting, quantization-aware SVD and fused rotary-embedding computation.

**Scope:** Deep learning. **Qualification:** Combines several compression operations; no universal decomposition optimality claim.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/enyac-group/UniQL.>). Links extracted from the accepted abstract; code was not tested.

### WSVD: Weighted Low-Rank Approximation for Fast and Efficient Execution of Low-Precision Vision-Language Models

**ICLR 2026 · Accept (Poster)** · Haiyu Wang; Yutong Wang; Jack Jiang; Sai Qian Zhang

[OpenReview](<https://openreview.net/forum?id=zrmQ4koOw9>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006413>) · [PDF](<https://openreview.net/pdf?id=zrmQ4koOw9>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Low-rank low-precision VLM linear operations.

**Computational idea:** Use fine-grained weighted SVD and an execution pattern designed to translate factorization into latency savings.

**Scope:** Deep learning. **Qualification:** Application-specific weighted low-rank approximation.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/SAI-Lab-NYU/WSVD.>). Links extracted from the accepted abstract; code was not tested.

### Advancing SVD-based LLM Compression via Layer-Wise Error Model Search

**ICML 2026 · Accept (regular)** · Moritz Thoma; Maximilian Groezinger; Maximilian Forstenhäusler; Emad Aghajanzadeh; Manoj Rohit Vemparala; Christos Anagnostopoulos; Pierpaolo Mori; Nael Fasfous; Alexander Frickenstein; Daniel Mueller-Gritschneder; Ulf Schlichtmann

[OpenReview](<https://openreview.net/forum?id=IjIgNPFuCt>) · [Official program](<https://icml.cc/virtual/2026/poster/64908>) · [PDF](<https://openreview.net/pdf?id=IjIgNPFuCt>)

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X6 — Matrix and tensor methods for compression.

**Quantity:** Fisher-aware SVD factors and global rank allocation.

**Computational idea:** Use token-wise KFAC statistics to reduce rank collapse, then search ranks using a layerwise error model and integer programming.

**Scope:** Deep learning. **Qualification:** Curvature and end-to-end error models are approximations.

**Optimizer relevance:** LLM compression: KFAC-SVD uses token-wise statistics to address rank-deficient Fisher estimates, paired with layer-wise error modeling for rank allocation.

**Evidence:** Official accepted-paper title and abstract.

### CGSVD: Cascaded Granular Singular Value Decomposition for Large Language Model Compression

**ICML 2026 · Accept (regular)** · Yuli Chen; Shuhao Zhang; Jiale Han; Fanshen Meng; Haishen Jiang; Bo Cheng; Qiang Tong; Xiulei Liu

[OpenReview](<https://openreview.net/forum?id=x23DAFnbhi>) · [Official program](<https://icml.cc/virtual/2026/poster/60742>) · [PDF](<https://openreview.net/pdf?id=x23DAFnbhi>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Compressed low-rank LLM weights.

**Computational idea:** Allocate ranks using inter-layer angular significance and spectral entropy; fill residual budget gaps caused by integer ranks.

**Scope:** Deep learning. **Qualification:** Improves compression design; uses SVD rather than inventing a new SVD solver.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/ironartisan/CGSVD>). Links extracted from the accepted abstract; code was not tested.

### Principled SVD-based Delta Compression via Quantization Error Minimization

**ICML 2026 · Accept (regular)** · Boya Xiong; Shuo Wang; Weifeng Ge; Guanhua CHEN; Yun Chen

[OpenReview](<https://openreview.net/forum?id=ErqvESaJpk>) · [Official program](<https://icml.cc/virtual/2026/poster/65313>) · [PDF](<https://openreview.net/pdf?id=ErqvESaJpk>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Quantized low-rank fine-tuning deltas.

**Computational idea:** Allocate mixed precision via an integer program based on singular-value-dependent error and correct sequential factor quantization.

**Scope:** Deep learning. **Qualification:** Optimal bit allocation refers to the stated error model and budget.

**Evidence:** Official accepted-paper title and abstract.

### SHARP-Q: Spectral Hessian Alignment and Rectification for Post-training Quantization

**ICML 2026 · Accept (regular)** · Menghao Lv; Huiqiong Wang; Li Sun; Mingli Song

[OpenReview](<https://openreview.net/forum?id=Xn9Eu2x7Hw>) · [Official program](<https://icml.cc/virtual/2026/poster/63357>) · [PDF](<https://openreview.net/pdf?id=Xn9Eu2x7Hw>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Curvature-aligned low-bit quantization corrections.

**Computational idea:** Rectify Hessian geometry and compensate in a dynamically approximated Fisher subspace.

**Scope:** Deep learning. **Qualification:** Structured curvature approximation for quantization.

**Evidence:** Official accepted-paper title and abstract.

### Zero Sum SVD: Balancing Loss Sensitivity for Low Rank LLM Compression

**ICML 2026 · Accept (regular)** · Ali Abbasi; Chayne Thrash; Haoran Qin; Shansita Sharma; Sepehr Seifi; Soheil Kolouri

[OpenReview](<https://openreview.net/forum?id=tAdsDOkRBw>) · [Official program](<https://icml.cc/virtual/2026/poster/61159>) · [PDF](<https://openreview.net/pdf?id=tAdsDOkRBw>)

**Categories:** X6 — Matrix and tensor methods for compression.

**Quantity:** Global singular-component selection for LLM compression.

**Computational idea:** Whiten activations and use first-order loss estimates to balance predicted loss changes across singular components.

**Scope:** Deep learning. **Qualification:** Zero-sum condition concerns predicted calibration loss, not guaranteed zero actual loss.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/mint-vu/Zero-Sum-SVD>). Links extracted from the accepted abstract; code was not tested.

### 3BASiL: An Algorithmic Framework for Sparse plus Low-Rank Compression of LLMs

**NeurIPS 2025 · Accept (poster)** · Mehdi Makni; Xiang Meng; Rahul Mazumder

[OpenReview](<https://openreview.net/forum?id=byNNv5Et10>) · [Official program](<https://neurips.cc/virtual/2025/poster/117134>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/fe498359454d826def8a847fad753dc2-Paper-Conference.pdf>)

**Categories:** X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/fe498359454d826def8a847fad753dc2-Abstract-Conference.html>)

**Quantity:** Sparse-plus-low-rank reconstruction of transformer weights.

**Computational idea:** 3BASiL uses three-block ADMM followed by transformer-level matching to refine sparse and low-rank components.

**Scope:** Deep learning. **Qualification:** Convergence claims concern the formulated subproblems; compressed models still have approximation error.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/mazumder-lab/3BASiL.>). Links extracted from the accepted abstract; code was not tested.

### Binary Quadratic Quantization: Beyond First-Order Quantization for Real-Valued Matrix Compression

**NeurIPS 2025 · Accept (poster)** · Kyo Kuroki; Yasuyuki Okoshi; Thiem Van Chu; Kazushi Kawamura; Masato Motomura

[OpenReview](<https://openreview.net/forum?id=5MGClYw1cR>) · [Official program](<https://neurips.cc/virtual/2025/poster/119877>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/e7cf82c8f34920d20299a84b16b720e8-Paper-Conference.pdf>)

**Categories:** X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/e7cf82c8f34920d20299a84b16b720e8-Abstract-Conference.html>)

**Quantity:** Compact real-valued matrix approximation.

**Computational idea:** Binary Quadratic Quantization represents matrices with quadratic expressions in binary bases.

**Scope:** Deep learning. **Qualification:** A lossy representation with reconstruction and downstream-task trade-offs, not lossless low-bit arithmetic.

**Evidence:** Official accepted-paper title and abstract.

### Compress Large Language Models via  Collaboration Between Learning and Matrix Approximation

**NeurIPS 2025 · Accept (poster)** · Yuesen Liao; Zhiwei Li; Binrui Wu; Zihao Cheng; Su Zhao; Shuai Chen; Weizhong Zhang

[OpenReview](<https://openreview.net/forum?id=4EkEL77k6O>) · [Official program](<https://neurips.cc/virtual/2025/poster/119963>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/5752f9fd2d5c40174738d6f02c202e72-Paper-Conference.pdf>)

**Categories:** X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/5752f9fd2d5c40174738d6f02c202e72-Abstract-Conference.html>)

**Quantity:** Sparse-plus-low-rank LLM weight approximation.

**Computational idea:** A bilevel framework learns layer sparsity and retained ranks while an adapted QR algorithm accelerates inner matrix approximation.

**Scope:** Deep learning. **Qualification:** Compression is approximate, with an outer stochastic allocation procedure and task-dependent accuracy.

**Evidence:** Official accepted-paper title and abstract.

### Distribution-Aware Tensor Decomposition for Compression of Convolutional Neural Networks

**NeurIPS 2025 · Accept (poster)** · Alper KALLE; Théo Rudkiewicz; Mohamed Ouerfelli; Mohamed Tamaazousti

[OpenReview](<https://openreview.net/forum?id=ODgWBaErst>) · [Official program](<https://neurips.cc/virtual/2025/poster/118313>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/7f6901ebab786e43b21530328fc989ca-Paper-Conference.pdf>)

**Categories:** X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/7f6901ebab786e43b21530328fc989ca-Abstract-Conference.html>)

**Quantity:** Input-covariance-weighted tensor compression.

**Computational idea:** Alternating least squares for Tucker and CP decompositions minimizes layer-output error under a covariance-weighted norm.

**Scope:** Deep learning. **Qualification:** Uses estimated input statistics; good transfer across datasets is empirical rather than universal.

**Evidence:** Official accepted-paper title and abstract.

### Dynamical Low-Rank Compression of Neural Networks with Robustness under Adversarial Attacks

**NeurIPS 2025 · Accept (oral)** · Steffen Schotthöfer; Lexie Yang; Stefan Schnake

[OpenReview](<https://openreview.net/forum?id=7AwFJzgIUW>) · [Official program](<https://neurips.cc/virtual/2025/poster/119731>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/cd5c450b7b3a004380cba0ff704a0cc9-Paper-Conference.pdf>)

**Categories:** J — Adjacent numerical, architectural, and specialized training methods; X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/cd5c450b7b3a004380cba0ff704a0cc9-Abstract-Conference.html>)

**Quantity:** Dynamically compressed neural-network weights.

**Computational idea:** Dynamical low-rank training with condition-number regularization adapts compact layer factors while controlling sensitivity.

**Scope:** Deep learning. **Qualification:** Compression and robustness are empirically assessed; spectral regularization is not a universal adversarial certificate.

**Optimizer relevance:** Combines dynamical low-rank neural-network training with spectral regularization of the low-rank core to improve compression and adversarial robustness.

**Evidence:** Official accepted-paper title and abstract.

### FedSVD: Adaptive Orthogonalization for Private Federated Learning with LoRA

**NeurIPS 2025 · Accept (poster)** · Seanie Lee; Sangwoo Park; Dong Bok Lee; Dominik Wagner; Haebin Seong; Tobias Bocklet; Juho Lee; Sung Ju Hwang

[OpenReview](<https://openreview.net/forum?id=Qq19n9LZ97>) · [Official program](<https://neurips.cc/virtual/2025/poster/118097>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/ad922aa85d4027ff3502e8e5f406e828-Paper-Conference.pdf>)

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/ad922aa85d4027ff3502e8e5f406e828-Abstract-Conference.html>)

**Quantity:** Orthogonalized aggregate LoRA updates.

**Computational idea:** FedSVD refactorizes the server-aggregated update by SVD to refresh one orthonormal adapter factor.

**Scope:** Deep learning. **Qualification:** A privacy-aware update reparameterization, not a faster generic SVD routine.

**Optimizer relevance:** FedSVD periodically refactorizes aggregated LoRA updates to adapt orthonormal directions and control differential-privacy noise amplification.

**Evidence:** Official accepted-paper title and abstract.

### Learning Grouped Lattice Vector Quantizers for Low-Bit LLM Compression

**NeurIPS 2025 · Accept (poster)** · Xi Zhang; Xiaolin Wu; Jiamang Wang; Weisi Lin

[OpenReview](<https://openreview.net/forum?id=Ynwl0V1YH0>) · [Official program](<https://neurips.cc/virtual/2025/poster/117396>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/a0183ad2088503d707669e1d222bc8c4-Paper-Conference.pdf>)

**Categories:** X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/a0183ad2088503d707669e1d222bc8c4-Abstract-Conference.html>)

**Quantity:** Low-bit lattice codebooks and weight reconstruction.

**Computational idea:** GLVQ learns generation matrices, uses Babai rounding for approximate nearest-lattice search, and decodes with matrix-vector products.

**Scope:** Deep learning. **Qualification:** Babai rounding approximates nearest-lattice search and quantization is lossy.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/xzhang9308/GLVQ.>). Links extracted from the accepted abstract; code was not tested.

### Q3R: Quadratic Reweighted Rank Regularizer for Effective Low-Rank Training

**NeurIPS 2025 · Accept (poster)** · Ipsita Ghosh; Ethan Nguyen; Christian Kümmerle

[OpenReview](<https://openreview.net/forum?id=ZtzWvNKOCr>) · [Official program](<https://neurips.cc/virtual/2025/poster/117315>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/c1e6da1f619fe4b2e00cb5ca98392ec4-Paper-Conference.pdf>)

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/c1e6da1f619fe4b2e00cb5ca98392ec4-Abstract-Conference.html>)

**Quantity:** Low-rank-inducing regularization during training.

**Computational idea:** Q3R majorizes a smoothed log-determinant rank surrogate with iteratively reweighted quadratic penalties.

**Scope:** Deep learning. **Qualification:** The surrogate encourages low rank; truncation and approximation quality require empirical validation.

**Optimizer relevance:** Q3R uses iteratively reweighted quadratic regularization of a smoothed log-determinant rank surrogate for low-rank training and fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

### QSVD: Efficient Low-rank Approximation for Unified Query-Key-Value Weight Compression in Low-Precision Vision-Language Models

**NeurIPS 2025 · Accept (spotlight)** · Yutong Wang; Haiyu Wang; Sai Qian Zhang

[OpenReview](<https://openreview.net/forum?id=sEFDhxF1mG>) · [Official program](<https://neurips.cc/virtual/2025/poster/115710>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/028ef7e68a5ea25fc26cd6abf3a5c147-Paper-Conference.pdf>)

**Categories:** X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/028ef7e68a5ea25fc26cd6abf3a5c147-Abstract-Conference.html>)

**Quantity:** Joint query-key-value weight compression.

**Computational idea:** QSVD factorizes joint Q/K/V weights with adaptive rank allocation and combines this with quantization.

**Scope:** Deep learning. **Qualification:** Both low-rank truncation and quantization are lossy; quality is evaluated for vision-language models.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/SAI-Lab-NYU/QSVD.>). Links extracted from the accepted abstract; code was not tested.

### RSAVQ: Riemannian Sensitivity-Aware Vector Quantization for Large Language Models

**NeurIPS 2025 · Accept (poster)** · Zukang Xu; Xing Hu; Qiang Wu; Dawei Yang

[OpenReview](<https://openreview.net/forum?id=8Ounc8L4F7>) · [Official program](<https://neurips.cc/virtual/2025/poster/119625>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/022a921af644da887f5930377f9d53d6-Paper-Conference.pdf>)

**Categories:** M4 — Related constrained and geometry-aware optimization; X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/022a921af644da887f5930377f9d53d6-Abstract-Conference.html>)

**Quantity:** Curvature-weighted quantization errors and bit allocation.

**Computational idea:** RSAVQ uses Fisher-Rao geometry to guide adaptive vector quantization.

**Scope:** Deep learning. **Qualification:** The metric is estimated and quantization remains lossy; this is not exact model preservation.

**Manifold relevance:** RSAVQ uses the Fisher metric to guide weight-quantization directions and precision allocation; this is geometry-aware quantization, not a generic constrained manifold optimizer.

**Geometry:** Fisher-Rao metric for quantization. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

### The Primacy of Magnitude in Low-Rank Adaptation

**NeurIPS 2025 · Accept (spotlight)** · Zicheng Zhang; Haoran Li; Yifeng Zhang; Guoqiang Gong; Jiaxing Wang; Pengzhang Liu; Qixia Jiang; Junxing Hu

[OpenReview](<https://openreview.net/forum?id=s4LnWgjacg>) · [Official program](<https://neurips.cc/virtual/2025/poster/115720>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/0010665e949927b74faf6e3ada6d7f72-Paper-Conference.pdf>)

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; T1 — Learning-rate selection, warm-up and schedules; T7 — Initialization, normalization, weight decay and regularization; X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/0010665e949927b74faf6e3ada6d7f72-Abstract-Conference.html>)

**Quantity:** Low-rank adapter initialization without SVD.

**Computational idea:** LoRAM scales deterministic orthogonal bases using pretrained weight magnitudes to reproduce useful update scales.

**Scope:** Deep learning. **Qualification:** Avoids spectral initialization but does not reconstruct the pretrained top singular subspace.

**Optimizer relevance:** LoRAM uses deterministic orthogonal bases scaled by weight magnitudes to obtain effective LoRA initialization without computing a spectral decomposition.

**Training dynamics relevance:** LoRAM uses deterministic orthogonal bases scaled by weight magnitudes to obtain effective LoRA initialization without computing a spectral decomposition.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** LoRA initialization; magnitude; scaling factor.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.


## X7 — Structured products, transforms and GPU kernels

### Hierarchical Multi-Stage Recovery Framework for Kronecker Compressed Sensing

**ICLR 2026 · Accept (Poster)** · Yanbin He; Geethu Joseph

[OpenReview](<https://openreview.net/forum?id=40e58sTE5F>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011587>) · [PDF](<https://openreview.net/pdf?id=40e58sTE5F>)

**Categories:** X7 — Structured products, transforms and GPU kernels.

**Quantity:** Sparse recovery from Kronecker-structured measurements.

**Computational idea:** Exploit hierarchical levels in Kronecker products for multistage recovery.

**Scope:** General ML. **Qualification:** Recovery guarantees depend on sparsity models and restricted-isometry assumptions.

**Evidence:** Official accepted-paper title and abstract.

### Trion: FFT-based Dynamic Subspace Selection for Low-Rank Adaptive Optimization of LLMs

**ICLR 2026 · Accept (Poster)** · Ionut-Vlad Modoranu; Mher Safaryan; Erik Schultheis; Maksim Riabinin; Artem Chumachenko; Dan Alistarh

[OpenReview](<https://openreview.net/forum?id=TkHjRwbMNl>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009288>) · [PDF](<https://openreview.net/pdf?id=TkHjRwbMNl>)

**Categories:** D — Memory-efficient and low-precision optimizers; X7 — Structured products, transforms and GPU kernels.

**Quantity:** Dynamic low-rank gradient projections.

**Computational idea:** Select columns from a fixed discrete-cosine basis using gradient alignment; use FFT-based DCT computation for large layers.

**Scope:** Deep learning. **Qualification:** Approximates adaptive SVD/QR subspaces with a structured fixed basis.

**Optimizer relevance:** Trion selects low-rank gradient subspaces from a fixed DCT basis, using FFT computation to avoid costly per-layer SVD/QR and reduce optimizer memory.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/IST-DASLab/Trion>). Links extracted from the accepted abstract; code was not tested.

### Asymptotically Fast Clebsch-Gordan Tensor Products with Vector Spherical Harmonics

**ICML 2026 · Accept (regular)** · YuQing Xie; Ameya Daigavane; Mit Kotak; Tess Smidt

[OpenReview](<https://openreview.net/forum?id=8UzZ0CbPsk>) · [Official program](<https://icml.cc/virtual/2026/poster/65961>) · [PDF](<https://openreview.net/pdf?id=8UzZ0CbPsk>)

**Categories:** X7 — Structured products, transforms and GPU kernels.

**Quantity:** Complete Clebsch-Gordan tensor products.

**Computational idea:** Use Fourier-style convolution and vector spherical harmonics to recover interactions missing from scalar Gaunt products.

**Scope:** Deep learning. **Qualification:** Asymptotic benefit applies to the specified complete tensor-product computation.

**Evidence:** Official accepted-paper title and abstract.

### DELTA4: Sparse Matrix-Vector Multiplication for Low Sparsity

**ICML 2026 · Accept (spotlight)** · Vladimír Macko; Vladimír Boža

[OpenReview](<https://openreview.net/forum?id=ah9xkFXCV6>) · [Official program](<https://icml.cc/virtual/2026/poster/63039>) · [PDF](<https://openreview.net/pdf?id=ah9xkFXCV6>)

**Categories:** X7 — Structured products, transforms and GPU kernels.

**Quantity:** Sparse matrix-vector products in pruned LLMs.

**Computational idea:** Co-design a compact sparse format and GPU kernel to reduce bandwidth overhead at moderate unstructured sparsity.

**Scope:** Deep learning. **Qualification:** Hardware and sparsity regime matter for speedups.

**Evidence:** Official accepted-paper title and abstract.

### Deterministic Inference across Tensor Parallel Sizes That Eliminates Training-Inference Mismatch

**ICML 2026 · Accept (regular)** · Ziyang Zhang; Xinheng Ding; Jiayi Yuan; Rixin Liu; Huizi Mao; Jiarong Xing; Zirui Liu

[OpenReview](<https://openreview.net/forum?id=5eZmlUyFpl>) · [Official program](<https://icml.cc/virtual/2026/poster/66224>) · [PDF](<https://openreview.net/pdf?id=5eZmlUyFpl>)

**Categories:** X7 — Structured products, transforms and GPU kernels.

**Quantity:** Reproducible matrix multiplication and reductions.

**Computational idea:** Use invariant tree reduction orders across tensor-parallel sizes in custom kernels.

**Scope:** Deep learning. **Qualification:** Targets bitwise reproducibility under the supported execution settings.

**Evidence:** Official accepted-paper title and abstract.

### E2Former-V2: On-the-Fly Equivariant Attention  with Linear Activation Memory

**ICML 2026 · Accept (regular)** · Lin Huang; Chengxiang Huang; Ziang Wang; Yiyue Du; Chu Wang; Haocheng Lu; Yunyang Li; Xiaoli LIU; Arthur JIANG; Jia Zhang

[OpenReview](<https://openreview.net/forum?id=gIUVdEAa3l>) · [Official program](<https://icml.cc/virtual/2026/poster/62474>) · [PDF](<https://openreview.net/pdf?id=gIUVdEAa3l>)

**Categories:** X7 — Structured products, transforms and GPU kernels.

**Quantity:** Equivariant attention tensor contractions.

**Computational idea:** Change from SO(3) to an axis-aligned SO(2) basis, use sparse parity re-indexing and fuse node-centric computation.

**Scope:** Deep learning. **Qualification:** A specific equivariant architecture and kernel design.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/IQuestLab/UBio-MolFM/tree/main>). Links extracted from the accepted abstract; code was not tested.

### Near-Universal Multiplicative Updates for Nonnegative Einsum Factorization

**ICML 2026 · Accept (regular)** · John Hood; Aaron Schein

[OpenReview](<https://openreview.net/forum?id=SdKzHplaIq>) · [Official program](<https://icml.cc/virtual/2026/poster/63907>) · [PDF](<https://openreview.net/pdf?id=SdKzHplaIq>)

**Categories:** X7 — Structured products, transforms and GPU kernels.

**Quantity:** Nonnegative tensor factorizations expressed as einsum.

**Computational idea:** Generate multiplicative updates for a broad family of tensor contractions and loss functions.

**Scope:** General ML. **Qualification:** Stationarity and supported losses follow the paper's assumptions.

**Evidence:** Official accepted-paper title and abstract.

### WBMM: Windowed Batch Matrix Multiplication for Efficient Large Receptive Field Convolution

**ICML 2026 · Accept (spotlight)** · Wan Song; Zhou Wei; Rui Wang; Jun Yu; Toru Kurihara; Xu Jiajia; shu zhan

[OpenReview](<https://openreview.net/forum?id=Qg9Jcy788i>) · [Official program](<https://icml.cc/virtual/2026/poster/64126>) · [PDF](<https://openreview.net/pdf?id=Qg9Jcy788i>)

**Categories:** X7 — Structured products, transforms and GPU kernels.

**Quantity:** Large-receptive-field convolution-like operators.

**Computational idea:** Construct local weight matrices from compact relative-position tables and compute contiguous-window batched matrix products.

**Scope:** Deep learning. **Qualification:** Proposes an operator/architecture implementation; not an identity for every arbitrary convolution.

**Evidence:** Official accepted-paper title and abstract.

### CDFlow: Building Invertible Layers with Circulant and Diagonal Matrices

**NeurIPS 2025 · Accept (poster)** · XUCHEN FENG; Siyu Liao

[OpenReview](<https://openreview.net/forum?id=XF4JM2MTSF>) · [Official program](<https://neurips.cc/virtual/2025/poster/117530>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/054a9c9f6249eee0093a85ccee5b3313-Paper-Conference.pdf>)

**Categories:** X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/054a9c9f6249eee0093a85ccee5b3313-Abstract-Conference.html>)

**Quantity:** Linear-layer inverses and log-determinants in normalizing flows.

**Computational idea:** CDFlow factors layers into circulant and diagonal matrices, using FFT algebra for cheap inverse application and determinants.

**Scope:** Deep learning. **Qualification:** The identities are exact for the structured invertible layer; representing an arbitrary dense layer may require many factors.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://proceedings.neurips.cc/paper_files/paper/2025/file/054a9c9f6249eee0093a85ccee5b3313-Paper-Conference.pdf>): Sections 3.1–3.2, equations (13)–(19), pages 4–5. Confirmed FFT-diagonalized circulant factors and factorwise log-determinants. The fast inverse operation is applying the structured inverse to a vector, not materializing an arbitrary dense inverse.

### E2Former: An Efficient and Equivariant Transformer with Linear-Scaling Tensor Products

**NeurIPS 2025 · Accept (spotlight)** · Yunyang Li; Lin Huang; Zhihao Ding; Xinran Wei; Chu Wang; Han Yang; Zun Wang; Chang Liu; Yu Shi; Peiran Jin; Tao Qin; Mark Gerstein; Jia Zhang

[OpenReview](<https://openreview.net/forum?id=ls5L4IMEwt>) · [Official program](<https://neurips.cc/virtual/2025/poster/116254>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/21f7b745f73ce0d1f9bcea7f40b1388e-Paper-Conference.pdf>)

**Categories:** X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/21f7b745f73ce0d1f9bcea7f40b1388e-Abstract-Conference.html>)

**Quantity:** Equivariant spherical tensor products.

**Computational idea:** E2Former uses Wigner 6j identities to transfer expensive contractions from edges to nodes.

**Scope:** Deep learning. **Qualification:** The computational advantage depends on the equivariant architecture and graph structure; it is not a general dense-matrix speedup.

**Evidence:** Official accepted-paper title and abstract.

### FlashMoE: Fast Distributed MoE in a Single Kernel

**NeurIPS 2025 · Accept (poster)** · Osayamen Aimuyo; Byungsoo Oh; Rachee Singh

[OpenReview](<https://openreview.net/forum?id=EZfDHprhZM>) · [Official program](<https://neurips.cc/virtual/2025/poster/119124>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/918d938bd209e5b56072777366f8a211-Paper-Conference.pdf>)

**Categories:** X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/918d938bd209e5b56072777366f8a211-Abstract-Conference.html>)

**Quantity:** Distributed mixture-of-experts matrix operations and routing.

**Computational idea:** FlashMoE fuses expert computation and device-initiated communication in a persistent GPU kernel.

**Scope:** Deep learning. **Qualification:** Performance depends on the GPU topology, shapes and precision; reported comparisons are not universal speedup factors.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/osayamenja/FlashMoE.>). Links extracted from the accepted abstract; code was not tested.

### Gradient Multi-Normalization for Efficient LLM Training

**NeurIPS 2025 · Accept (poster)** · Meyer Scetbon; Chao Ma; Wenbo Gong; Ted Meeds

[OpenReview](<https://openreview.net/forum?id=oanhUGY6un>) · [Official program](<https://neurips.cc/virtual/2025/poster/116024>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/3d6235707dbc91acda049a0ccd641a7e-Paper-Conference.pdf>)

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/3d6235707dbc91acda049a0ccd641a7e-Abstract-Conference.html>)

**Quantity:** Matrix-gradient normalization without persistent moment states.

**Computational idea:** SinkGD alternates normalization constraints on gradients instead of maintaining Adam-style statistics.

**Scope:** Deep learning. **Qualification:** Multi-normalization changes the update geometry; it is not generally identical to a matrix inverse root or polar factor.

**Optimizer relevance:** SinkGD replaces stored adaptive statistics with iterative gradient multi-normalization, using matrix structure for language-model optimization.

**Evidence:** Official accepted-paper title and abstract.

### Irrational Complex Rotations Empower Low-bit Optimizers

**NeurIPS 2025 · Accept (poster)** · Zhen Tian; Xin Zhao; Ji-Rong Wen

[OpenReview](<https://openreview.net/forum?id=fSFgcEVDT2>) · [Official program](<https://neurips.cc/virtual/2025/poster/116843>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/f943a0abbfe9fb6e46a01411fc7372c9-Paper-Conference.pdf>)

**Categories:** D — Memory-efficient and low-precision optimizers; X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/f943a0abbfe9fb6e46a01411fc7372c9-Abstract-Conference.html>)

**Quantity:** Low-bit optimizer-state encoding and reconstruction.

**Computational idea:** pi-Quant uses irrational complex rotations to represent optimizer states compactly.

**Scope:** Deep learning. **Qualification:** Lossy numerical encoding; reported quality and memory trade-offs depend on bit width and training setup.

**Optimizer relevance:** pi-Quant compresses optimizer states using low-bit encodings based on irrational complex rotations.

**Evidence:** Official accepted-paper title and abstract.

### Memory-Efficient Training with In-Place FFT Implementation

**NeurIPS 2025 · Accept (poster)** · XINYU DING; Bangtian Liu; Siyu Liao; Zhongfeng Wang

[OpenReview](<https://openreview.net/forum?id=oWnAlRn3X1>) · [Official program](<https://neurips.cc/virtual/2025/poster/116030>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/b07091c16719ad3990e3d1ccee6641f1-Paper-Conference.pdf>)

**Categories:** X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/b07091c16719ad3990e3d1ccee6641f1-Abstract-Conference.html>)

**Quantity:** FFT transforms and frequency-domain parameter updates.

**Computational idea:** A real-domain in-place FFT encoding preserves input/output dimension and reduces intermediate storage.

**Scope:** Deep learning. **Qualification:** Memory claims concern the proposed representation and implementation, not every FFT library or training workload.

**Evidence:** Official accepted-paper title and abstract.

### Tensor Decomposition Networks for Fast Machine Learning Interatomic Potential Computations

**NeurIPS 2025 · Accept (poster)** · Yuchao Lin; Cong Fu; Zachary Krueger; Haiyang Yu; Maho Nakata; Jianwen Xie; Emine Kucukbenli; Xiaofeng Qian; Shuiwang Ji

[OpenReview](<https://openreview.net/forum?id=9vKJyCUfMH>) · [Official program](<https://neurips.cc/virtual/2025/poster/119499>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/7fe3f83c15c1c96daf4689d358c9cadf-Paper-Conference.pdf>)

**Categories:** X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/7fe3f83c15c1c96daf4689d358c9cadf-Abstract-Conference.html>)

**Earlier program title:** Tensor Decomposition Networks for Accelerating Machine Learning Force Field Computations.

**Quantity:** Clebsch-Gordan tensor products in equivariant networks.

**Computational idea:** Replaces expensive tensor products with low-rank tensor decompositions and shares path weights.

**Scope:** Deep learning. **Qualification:** Low-rank decomposition gives approximate equivariance with bounds; exact equivariance and universality claims apply under their specified constructions.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/divelab/AIRS/tree/main/OpenMol/TDN>). Links extracted from the accepted abstract; code was not tested.

### The Structural Complexity of Matrix-Vector Multiplication

**NeurIPS 2025 · Accept (poster)** · Emile Anand; Jan van den Brand; Rose McCarty

[OpenReview](<https://openreview.net/forum?id=tGLZj8GWx3>) · [Official program](<https://neurips.cc/virtual/2025/poster/115613>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/3545b95bd8bdab38c71bcdfa8a91859e-Paper-Conference.pdf>)

**Categories:** X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/3545b95bd8bdab38c71bcdfa8a91859e-Abstract-Conference.html>)

**Quantity:** Repeated matrix-vector products for structured matrices.

**Computational idea:** Preprocesses matrices with bounded VC dimension or pseudodimension to enable subquadratic product queries.

**Scope:** Theory / foundations. **Qualification:** Structure-dependent theoretical algorithms; arbitrary dense matrices do not receive the same guarantee.

**Evidence:** Official accepted-paper title and abstract.

### Universal Sequence Preconditioning

**NeurIPS 2025 · Accept (spotlight)** · Annie Marsden; Elad Hazan

[OpenReview](<https://openreview.net/forum?id=rwmVd8BKW5>) · [Official program](<https://neurips.cc/virtual/2025/poster/115735>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/9b25312145e55be426ee7071e845cb90-Paper-Conference.pdf>)

**Categories:** J — Adjacent numerical, architectural, and specialized training methods; X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/9b25312145e55be426ee7071e845cb90-Abstract-Conference.html>)

**Quantity:** Polynomial preconditioning of temporal transition operators.

**Computational idea:** Applies convolution filters from Chebyshev or Legendre polynomials to transform sequence learning problems.

**Scope:** General ML. **Qualification:** The strongest guarantees concern structured dynamical-system settings; this is not a universal LLM-training guarantee.

**Optimizer relevance:** Universal sequence preconditioning uses orthogonal-polynomial convolution filters to improve learning of dynamical sequences.

**Evidence:** Official accepted-paper title and abstract.


## X8 — Linear systems, sparse solvers and Gaussian processes

### Differentiable Model Predictive Control on the GPU

**ICLR 2026 · Accept (Oral)** · Emre Adabag; Marcus Greiff; John Subosits; Thomas Lew

[OpenReview](<https://openreview.net/forum?id=bFYfV6c9zu>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008630>) · [PDF](<https://openreview.net/pdf?id=bFYfV6c9zu>)

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

**Quantity:** Differentiable MPC optimization steps.

**Computational idea:** Exploit structured systems using sequential quadratic programming and GPU PCG with tridiagonal preconditioning.

**Scope:** Deep learning. **Qualification:** Iterative constrained-control solver; convergence and gradients depend on tolerances and regularity.

**Evidence:** Official accepted-paper title and abstract.

### Splat Feature Solver

**ICLR 2026 · Accept (Poster)** · Butian Xiong; Rong Liu; Kenneth Xu; Meida Chen; Andrew Feng

[OpenReview](<https://openreview.net/forum?id=AepuXqQM4X>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011014>) · [PDF](<https://openreview.net/pdf?id=AepuXqQM4X>)

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

**Quantity:** Feature lifting onto 3D splat representations.

**Computational idea:** Formulate feature assignment as a sparse linear inverse problem with Tikhonov guidance and post-lifting aggregation.

**Scope:** Deep learning. **Qualification:** Closed-form formulation does not imply zero-cost inversion; numerical solution is still required.

**Evidence:** Official accepted-paper title and abstract.

### Understanding and Relaxing the Limitations of Transformers for Linear Algebra

**ICLR 2026 · Accept (Poster)** · Andres Potapczynski; Alex Ali; Andrew Gordon Wilson

[OpenReview](<https://openreview.net/forum?id=GBkRMi3qjD>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010523>) · [PDF](<https://openreview.net/pdf?id=GBkRMi3qjD>)

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

**Quantity:** Learned matrix operations and iterative downstream computations.

**Computational idea:** RangeFormer combines matrix-aware embeddings, linear attention, looping and structured training distributions.

**Scope:** Deep learning. **Qualification:** Studies learned approximations and OOD limitations; not a replacement for guaranteed numerical solvers.

**Evidence:** Official accepted-paper title and abstract.

### Causal Structure Learning for Sparse Matrix Fill-in Reduction

**ICML 2026 · Accept (regular)** · Ziwei Li; Shuzi Niu; Tao Yuan; Huiyuan Li

[OpenReview](<https://openreview.net/forum?id=VbMi2zFVlk>) · [Official program](<https://icml.cc/virtual/2026/poster/63598>) · [PDF](<https://openreview.net/pdf?id=VbMi2zFVlk>)

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

**Quantity:** Low-fill sparse LU factorizations.

**Computational idea:** Learn a matrix reordering using causal triplet structures derived from the fill-path theorem.

**Scope:** Scientific computing. **Qualification:** A learned heuristic for ordering; not an exact solution of the NP-hard minimum-fill problem.

**Evidence:** Official accepted-paper title and abstract.

### Fast kernel methods: Sobolev, physics-informed, and additive models

**ICML 2026 · Accept (regular)** · Nathan Doumèche; Francis Bach; Gérard Biau; Claire Boyer

[OpenReview](<https://openreview.net/forum?id=QiDicUd6PB>) · [Official program](<https://icml.cc/virtual/2026/poster/64123>) · [PDF](<https://openreview.net/pdf?id=QiDicUd6PB>)

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

**Quantity:** Kernel regression operators.

**Computational idea:** Use Fourier representations and non-uniform FFTs to exploit structured kernels on accelerators.

**Scope:** General ML. **Qualification:** Fast implemented Sobolev case is restricted to low ambient dimension; approximation/discretization choices still matter.

**Evidence:** Official accepted-paper title and abstract.

### G-RANS: Generalizable Residual-Aware Neural Solvers for Sparse Systems

**ICML 2026 · Accept (regular)** · Weixin Liao; Mingquan Feng; Zhizhou Zhang; Youjia Wu; Yifan Fu; Junchi Yan

[OpenReview](<https://openreview.net/forum?id=uizi6lvkSW>) · [Official program](<https://icml.cc/virtual/2026/poster/60991>) · [PDF](<https://openreview.net/pdf?id=uizi6lvkSW>)

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

**Quantity:** Sparse linear-system solutions.

**Computational idea:** Learn residual-aware correction subspaces and project residual updates in a neural iterative solver.

**Scope:** Scientific computing. **Qualification:** Evaluated on specified PDE/FEM families; generalization is empirical.

**Evidence:** Official accepted-paper title and abstract.

### gp2Scale: A Class of Compactly Supported Non-Stationary Kernels and Distributed Computing for Exact Gaussian Processes on 10 Million Data Points

**ICML 2026 · Accept (regular)** · Marcus Noack; Mark Risser; HENGRUI LUO; Vardaan Tekriwal; Ronald Pandolfi

[OpenReview](<https://openreview.net/forum?id=xLnzdfOS6r>) · [Official program](<https://icml.cc/virtual/2026/poster/60707>) · [PDF](<https://openreview.net/pdf?id=xLnzdfOS6r>)

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

**Quantity:** Gaussian-process linear solves and log determinants.

**Computational idea:** Design compactly supported non-stationary kernels that yield sparse covariance matrices, then use distributed sparse computation.

**Scope:** General ML. **Qualification:** Exactness is relative to the chosen sparse-kernel GP, not an exact acceleration of arbitrary dense kernels.

**Evidence:** Official accepted-paper title and abstract.

### Inference of Online Newton Methods with Nesterov's Accelerated Sketching

**ICML 2026 · Accept (regular)** · Haoxuan Wang; Xinchen Du; Sen Na

[OpenReview](<https://openreview.net/forum?id=h2uxKKK4WZ>) · [Official program](<https://icml.cc/virtual/2026/poster/62394>) · [PDF](<https://openreview.net/pdf?id=h2uxKKK4WZ>)

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

**Quantity:** Online Newton directions and covariance estimates.

**Computational idea:** Use Nesterov-accelerated sketch-and-project solves alongside Hessian averaging.

**Scope:** General ML. **Qualification:** Approximate Newton systems; inference theory assumes stated smoothness and moment conditions.

**Evidence:** Official accepted-paper title and abstract.

### RAPNet: Accelerating Algebraic Multigrid with Learned Sparse Corrections

**ICML 2026 · Accept (regular)** · Yali Fink; Ido Ben-Yair; Lars Ruthotto; Eran Treister

[OpenReview](<https://openreview.net/forum?id=iiNPaOvuwj>) · [Official program](<https://icml.cc/virtual/2026/poster/62202>) · [PDF](<https://openreview.net/pdf?id=iiNPaOvuwj>)

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

**Quantity:** Sparse coarse operators for algebraic multigrid.

**Computational idea:** Learn sparse corrections during solver setup with levelwise GNN training.

**Scope:** Scientific computing. **Qualification:** Accelerates setup/operator design; retains a classical multigrid solve phase.

**Evidence:** Official accepted-paper title and abstract.

### A faster training algorithm for regression trees with linear leaves, and an analysis of its complexity

**NeurIPS 2025 · Accept (poster)** · Kuat Gazizov; Miguel A. Carreira-Perpinan

[OpenReview](<https://openreview.net/forum?id=urDdBuhbLx>) · [Official program](<https://neurips.cc/virtual/2025/poster/115461>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/c023f4ec4c567ad48188e9b2ce6bdba7-Paper-Conference.pdf>)

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/c023f4ec4c567ad48188e9b2ce6bdba7-Abstract-Conference.html>)

**Quantity:** Least-squares leaf updates in regression trees.

**Computational idea:** Applies Sherman-Morrison-Woodbury reformulations to solve the same leaf optimization problems using smaller data subsets.

**Scope:** General ML. **Qualification:** Exact algebra under the required invertibility conditions; this is a tree-training application rather than deep learning.

**Evidence:** Official accepted-paper title and abstract.

### Learning Sparse Approximate Inverse Preconditioners for Conjugate Gradient Solvers on GPUs

**NeurIPS 2025 · Accept (poster)** · Zhehao Li; Zhehao Li; Kangbo Lyu; Yixuan Li; Tao Du; Ligang Liu

[OpenReview](<https://openreview.net/forum?id=jtMDzggo6M>) · [Official program](<https://neurips.cc/virtual/2025/poster/116429>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/23fcc63005ac1a6e460ec4e209d17607-Paper-Conference.pdf>)

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/23fcc63005ac1a6e460ec4e209d17607-Abstract-Conference.html>)

**Quantity:** GPU-friendly preconditioning for conjugate gradients.

**Computational idea:** A GNN predicts sparse approximate inverse preconditioners, replacing triangular solves with matrix-vector products.

**Scope:** Scientific computing. **Qualification:** The matrix must satisfy the solver assumptions; generalization and speed depend on sparsity and problem distribution.

**Evidence:** Official accepted-paper title and abstract.

### Partial Correlation Network Estimation by Semismooth Newton Methods

**NeurIPS 2025 · Accept (poster)** · DongWon Kim; Sungdong Lee; Joong-Ho (Johann) Won

[OpenReview](<https://openreview.net/forum?id=L3UfIfNxb7>) · [Official program](<https://neurips.cc/virtual/2025/poster/118580>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/f003e17e2fe9aac7667a1b4407ccef46-Paper-Conference.pdf>)

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/f003e17e2fe9aac7667a1b4407ccef46-Abstract-Conference.html>)

**Quantity:** Sparse partial-correlation estimation updates.

**Computational idea:** Semismooth Newton methods reduce updates to small linear systems or complementarity subproblems.

**Scope:** General ML. **Qualification:** Local quadratic convergence requires the specified conditions; a graphical-model solver rather than an LLM optimizer.

**Evidence:** Official accepted-paper title and abstract.

### Robust and Computation-Aware Gaussian Processes

**NeurIPS 2025 · Accept (poster)** · Marshal Sinaga; Julien Martinelli; Samuel Kaski

[OpenReview](<https://openreview.net/forum?id=tJZKaDSSTX>) · [Official program](<https://neurips.cc/virtual/2025/poster/115607>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/0122ad3e4a752438562297553bbf9049-Paper-Conference.pdf>)

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/0122ad3e4a752438562297553bbf9049-Abstract-Conference.html>)

**Quantity:** GP inference with low-rank computational approximations.

**Computational idea:** RCaGP combines robust generalized Bayesian updates with uncertainty about approximate matrix computations.

**Scope:** General ML. **Qualification:** An approximate, robustness-aware inference model; it does not compute the standard dense GP posterior exactly.

**Evidence:** Official accepted-paper title and abstract.

### SymMaP: Improving Computational Efficiency in Linear Solvers through Symbolic Preconditioning

**NeurIPS 2025 · Accept (poster)** · Hong Wang; Jie Wang; Minghao Ma; Haoran Shao; Haoyang Liu

[OpenReview](<https://openreview.net/forum?id=Oupeovfx0L>) · [Official program](<https://neurips.cc/virtual/2025/poster/118256>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/5c17c18c1dea5a0c00907824bbb80449-Paper-Conference.pdf>)

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/5c17c18c1dea5a0c00907824bbb80449-Abstract-Conference.html>)

**Quantity:** Instance-specific preconditioner parameters.

**Computational idea:** SymMaP discovers compact symbolic formulas to select preconditioning parameters cheaply at inference.

**Scope:** Scientific computing. **Qualification:** A learned parameter-selection rule, not an exact symbolic inverse or a uniform convergence guarantee.

**Evidence:** Official accepted-paper title and abstract.

### Turbocharging Gaussian Process Inference with Approximate Sketch-and-Project

**NeurIPS 2025 · Accept (poster)** · Pratik Rathore; Zachary Frangella; Sachin Garg; Shaghayegh Fazliani; Michal Derezinski; Madeleine Udell

[OpenReview](<https://openreview.net/forum?id=GaL0ja9ygG>) · [Official program](<https://neurips.cc/virtual/2025/poster/118958>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/cf8b2205e39f81726a8d828ecbe00ad0-Paper-Conference.pdf>)

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/cf8b2205e39f81726a8d828ecbe00ad0-Abstract-Conference.html>)

**Quantity:** Large kernel-system solves and GP posterior means.

**Computational idea:** ADASAP combines approximate sketch-and-project with acceleration and distributed computation.

**Scope:** General ML. **Qualification:** The condition-number-free result concerns specified leading spectral components; finite solves are approximate.

**Evidence:** Official accepted-paper title and abstract.


## X9 — Related numerical primitives and computation

### AutoNumerics-Zero: Automated Discovery of State-of-the-Art Mathematical Functions

**ICML 2026 · Accept (regular)** · Esteban Real; Mirko Rossini; Connal de Souza; Manav Garg; Moritz Firsching; Quoc Le; Yao Chen; Akhil Verghese; Ekin Dogus Cubuk; David Park

[OpenReview](<https://openreview.net/forum?id=n7F2nwPcYB>) · [Official program](<https://icml.cc/virtual/2026/poster/61770>) · [PDF](<https://openreview.net/pdf?id=n7F2nwPcYB>)

**Categories:** X9 — Related numerical primitives and computation.

**Quantity:** Finite-precision transcendental functions.

**Computational idea:** Use symbolic regression to search low-operation-count arithmetic approximations.

**Scope:** Numerical foundations. **Qualification:** Scalar numerical primitives, not a matrix algorithm or an LLM optimizer.

**Evidence:** Official accepted-paper title and abstract.

### CLARITree: Cholesky and Lookahead Accelerations for Regression with Interpretable Piecewise Linear Trees

**ICML 2026 · Accept (regular)** · Yixiao Wang; Hayden McTavish; Varun Babbar; Margo Seltzer; Cynthia Rudin

[OpenReview](<https://openreview.net/forum?id=JjBozF4i2w>) · [Official program](<https://icml.cc/virtual/2026/poster/64794>) · [PDF](<https://openreview.net/pdf?id=JjBozF4i2w>)

**Categories:** X9 — Related numerical primitives and computation.

**Quantity:** Gram-matrix updates during linear-tree search.

**Computational idea:** Reuse rank-one Cholesky updates with lookahead search to fit sparse piecewise-linear regression trees.

**Scope:** General ML. **Qualification:** Classical ML application; included as a reusable numerical idea.

**Evidence:** Official accepted-paper title and abstract.

### Fast Estimation for Forest Matrix of Signed Graphs

**ICML 2026 · Accept (regular)** · Haoxin Sun; Zhongzhi Zhang

[OpenReview](<https://openreview.net/forum?id=0ujhEWEeAc>) · [Official program](<https://icml.cc/virtual/2026/poster/66739>) · [PDF](<https://openreview.net/pdf?id=0ujhEWEeAc>)

**Categories:** X9 — Related numerical primitives and computation.

**Quantity:** Diagonal entries of signed-graph forest matrices.

**Computational idea:** Sample generalized spanning forests through loop-erased random walks and average diagonal estimates.

**Scope:** General ML. **Qualification:** Monte Carlo estimator; graph computation rather than an LLM-specific method.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/HaoxinSun98/SignedForestDiagonal>). Links extracted from the accepted abstract; code was not tested.

### FlashSinkhorn: IO-Aware Entropic Optimal Transport on GPU

**ICML 2026 · Accept (spotlight)** · Felix X.-F. Ye; Xingjie Li; An Yu; Ming-Ching Chang; LINSONG CHU; Davis Wertheimer

[OpenReview](<https://openreview.net/forum?id=VzIA4MASxK>) · [Official program](<https://icml.cc/virtual/2026/oral/71180>) · [PDF](<https://openreview.net/pdf?id=VzIA4MASxK>)

**Categories:** X9 — Related numerical primitives and computation.

**Quantity:** Entropic optimal-transport updates and transport application.

**Computational idea:** Rewrite log-domain Sinkhorn as biased dot-product LogSumExp reductions, enabling FlashAttention-style tiling and streaming.

**Scope:** Deep learning. **Qualification:** Specific squared-Euclidean cost and entropic objective; finite Sinkhorn iterations have residual error.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/ot-triton-lab/flash-sinkhorn.>). Links extracted from the accepted abstract; code was not tested.

### Generalizing Stochastic Smoothing for Differentiation and Gradient Estimation

**ICML 2026 · Accept (regular)** · Felix Petersen; Christian Borgelt; Aashwin Mishra; Stefano Ermon

[OpenReview](<https://openreview.net/forum?id=okzQ1x71pS>) · [Official program](<https://icml.cc/virtual/2026/poster/61580>) · [PDF](<https://openreview.net/pdf?id=okzQ1x71pS>)

**Categories:** X9 — Related numerical primitives and computation.

**Quantity:** Black-box gradients for non-differentiable functions.

**Computational idea:** Generalize stochastic smoothing and combine variance-reduction strategies.

**Scope:** General ML. **Qualification:** Smoothed-objective gradient estimation rather than exact differentiation of the original hard function.

**Evidence:** Official accepted-paper title and abstract.

### Rex: A Family of Reversible Exponential (Stochastic) Runge-Kutta Solvers

**ICML 2026 · Accept (spotlight)** · Zander Blasingame; Chen Liu

[OpenReview](<https://openreview.net/forum?id=7pQIzVNctu>) · [Official program](<https://icml.cc/virtual/2026/poster/66025>) · [PDF](<https://openreview.net/pdf?id=7pQIzVNctu>)

**Categories:** X9 — Related numerical primitives and computation.

**Quantity:** Reversible neural ODE/SDE trajectories.

**Computational idea:** Apply Lawson constructions to build reversible exponential stochastic Runge-Kutta schemes.

**Scope:** Deep learning. **Qualification:** Numerical integration rather than matrix factorization; reversibility does not remove all floating-point error.

**Evidence:** Official accepted-paper title and abstract.

### Robust Parallel Diffusion Sampling via Dynamic Jacobian Bandwidth

**ICML 2026 · Accept (regular)** · Zile Huang; Ser-Nam Lim

[OpenReview](<https://openreview.net/forum?id=pRsFAKBQKz>) · [Official program](<https://icml.cc/virtual/2026/poster/61508>) · [PDF](<https://openreview.net/pdf?id=pRsFAKBQKz>)

**Categories:** X9 — Related numerical primitives and computation.

**Quantity:** Parallel diffusion sampling trajectories.

**Computational idea:** Reformulate denoising as a nonlinear system and solve with adaptive local sparsity in the Jacobian structure.

**Scope:** Deep learning. **Qualification:** Approximate parallel sampling; quality and speed depend on the generation setup.

**Evidence:** Official accepted-paper title and abstract.

### SoftJAX & SoftTorch: Empowering Automatic Differentiation Libraries with Informative Gradients

**ICML 2026 · Accept (spotlight)** · Anselm Paulus; Andreas René Geist; Vit Musil; Sebastian Hoffmann; Georg Martius

[OpenReview](<https://openreview.net/forum?id=RKHDV40omz>) · [Official program](<https://icml.cc/virtual/2026/poster/64057>) · [PDF](<https://openreview.net/pdf?id=RKHDV40omz>)

**Categories:** X9 — Related numerical primitives and computation.

**Quantity:** Useful gradients for discrete and hard primitives.

**Computational idea:** Provide soft replacements for sorting, indexing and logic, including optimal-transport and permutahedron-based operators.

**Scope:** General ML. **Qualification:** Gradients are for relaxations or straight-through estimators, not exact derivatives of discrete maps.

**Evidence:** Official accepted-paper title and abstract.

### The benefits of full data shuffle, now with optimal I/O cost: $k$-wise independence and matrix transposition to the rescue

**ICML 2026 · Accept (regular)** · Peyman Afshani; Rezaul Chowdhury; Mayank Goswami; Jens Kristian R Schou; Francesco Silvestri; Mariafiore Tognon

[OpenReview](<https://openreview.net/forum?id=oHxq8g8Wy1>) · [Official program](<https://icml.cc/virtual/2026/poster/61632>) · [PDF](<https://openreview.net/pdf?id=oHxq8g8Wy1>)

**Categories:** X9 — Related numerical primitives and computation.

**Quantity:** Low-IO randomized data shuffling for SGD.

**Computational idea:** Use matrix transposition and limited-independence permutations to achieve linear IO cost.

**Scope:** Theory / foundations. **Qualification:** Guarantees concern the stated memory model and permutation distributions.

**Evidence:** Official accepted-paper title and abstract.
