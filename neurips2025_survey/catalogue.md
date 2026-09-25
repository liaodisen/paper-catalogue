# NeurIPS 2025 catalogue

176 curated papers. Updated 2026-09-24. Topic membership overlaps; publication status and evidence are recorded for each entry.

### 3BASiL: An Algorithmic Framework for Sparse plus Low-Rank Compression of LLMs

**NeurIPS 2025 · Accept (poster)** · Mehdi Makni; Xiang Meng; Rahul Mazumder

[Primary source](<https://openreview.net/forum?id=byNNv5Et10>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117134>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/fe498359454d826def8a847fad753dc2-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/fe498359454d826def8a847fad753dc2-Abstract-Conference.html>)

**Quantity:** Sparse-plus-low-rank reconstruction of transformer weights.

**Computational idea:** 3BASiL uses three-block ADMM followed by transformer-level matching to refine sparse and low-rank components.

**Scope:** Deep learning. **Qualification:** Convergence claims concern the formulated subproblems; compressed models still have approximation error.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/mazumder-lab/3BASiL.>). Links extracted from the accepted abstract; code was not tested.

### A faster training algorithm for regression trees with linear leaves, and an analysis of its complexity

**NeurIPS 2025 · Accept (poster)** · Kuat Gazizov; Miguel A. Carreira-Perpinan

[Primary source](<https://openreview.net/forum?id=urDdBuhbLx>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115461>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/c023f4ec4c567ad48188e9b2ce6bdba7-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/c023f4ec4c567ad48188e9b2ce6bdba7-Abstract-Conference.html>)

**Quantity:** Least-squares leaf updates in regression trees.

**Computational idea:** Applies Sherman-Morrison-Woodbury reformulations to solve the same leaf optimization problems using smaller data subsets.

**Scope:** General ML. **Qualification:** Exact algebra under the required invertibility conditions; this is a tree-training application rather than deep learning.

**Evidence:** Official accepted-paper title and abstract.

### A Geometric Analysis of PCA

**NeurIPS 2025 · Accept (poster)** · Ayoub El Hanchi; Murat Erdogdu; Chris Maddison

[Primary source](<https://openreview.net/forum?id=KEVjRT4haB>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118663>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/e9638fbbd671a3361bc807e4e7a71400-Paper-Conference.pdf>)

**Topics:** Manifold.

**Categories:** M5 — Supporting geometry, statistics, and training-dynamics papers.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/e9638fbbd671a3361bc807e4e7a71400-Abstract-Conference.html>)

**Manifold relevance:** Analyzes PCA excess risk through manifold geometry and curvature; supporting statistical theory rather than a new LLM optimizer.

**Geometry:** Grassmann geometry of PCA. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

### A geometric framework for momentum-based optimizers for low-rank training

**NeurIPS 2025 · Accept (poster)** · Steffen Schotthöfer; Timon Klein; Jonas Kusch

[Primary source](<https://openreview.net/forum?id=cCefuzQrjK>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117118>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/81f1ae463ed30c5d44ff416d134f9071-Paper-Conference.pdf>)

**Topics:** Manifold; Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; M2 — Manifold-based LLM training and low-rank adaptation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/81f1ae463ed30c5d44ff416d134f9071-Abstract-Conference.html>)

**Optimizer relevance:** Derives geometry-respecting momentum methods through dynamical low-rank approximation, connecting low-rank training with standard optimizer dynamics.

**Manifold relevance:** Develops a geometric framework for momentum-based low-rank training rather than applying an unconstrained optimizer independently to arbitrary factors.

**Geometry:** Manifold of low-rank matrices; dynamical low-rank approximation. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### A Geometry-Aware Metric for Mode Collapse in Time Series Generative Models

**NeurIPS 2025 · Accept (poster)** · Yassine ABBAHADDOU; Amine Aboussalah

[Primary source](<https://openreview.net/forum?id=YAc0O13qMc>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117444>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/de4c2179a4ab3728f8a20aeb5a3f1bb6-Paper-Conference.pdf>)

**Topics:** Manifold.

**Categories:** M5 — Supporting geometry, statistics, and training-dynamics papers.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/de4c2179a4ab3728f8a20aeb5a3f1bb6-Abstract-Conference.html>)

**Manifold relevance:** DMD-GEN compares generated time series through mode subspaces and optimal transport; a geometric evaluation metric, not a manifold optimizer.

**Geometry:** Grassmann geometry of dynamic-mode subspaces. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

### A Minimalist Example of Edge-of-Stability and Progressive Sharpening

**NeurIPS 2025 · Accept (poster)** · Liming Liu; Zixuan Zhang; Simon Du; Tuo Zhao

[Primary source](<https://openreview.net/forum?id=yst8MHfcgP>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115100>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/15eac388458e8a577f96edf7a40d0cbc-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/15eac388458e8a577f96edf7a40d0cbc-Abstract-Conference.html>)

**Training dynamics relevance:** Proves progressive sharpening and self-stabilization along the trajectory of a minimal network.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Large learning rate; input structure; sharpness.

**Training qualification:** The model has two input dimensions and is designed as a controlled explanatory example.

**Evidence:** Official accepted-paper title and abstract.

### A Private Approximation of the 2nd-Moment Matrix of Any Subsamplable Input

**NeurIPS 2025 · Accept (poster)** · Bar Mahpud; Or Sheffet

[Primary source](<https://openreview.net/forum?id=Ep4mYI7OLF>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119097>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/e61c3ae7d4ace10e1fb6f9fd25218fd7-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/e61c3ae7d4ace10e1fb6f9fd25218fd7-Abstract-Conference.html>)

**Quantity:** Differentially private second-moment matrices.

**Computational idea:** A recursive estimator exploits subsamplability to preserve spectral structure while adding privacy protection.

**Scope:** General ML. **Qualification:** Accuracy guarantees require subsamplability and probabilistic conditions; the returned matrix is a private approximation.

**Evidence:** Official accepted-paper title and abstract.

### A Stable Whitening Optimizer for Efficient Neural Network Training

**NeurIPS 2025 · Accept (poster)** · Kevin Frans; Sergey Levine; Pieter Abbeel

[Primary source](<https://openreview.net/forum?id=0T8i3uXq3O>) · [Venue page](<https://neurips.cc/virtual/2025/poster/120317>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/fe722dac731f46d30b043c6b0db9a3ef-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X1 — Matrix functions, roots and matrix geometry.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/fe722dac731f46d30b043c6b0db9a3ef-Abstract-Conference.html>)

**Quantity:** Whitened and normalized matrix-gradient updates.

**Computational idea:** SPlus reuses a historical Shampoo eigenbasis and normalizes current gradients in that basis.

**Scope:** Deep learning. **Qualification:** Cached eigenbases and bounded updates define a particular optimizer; they are not exact inversion of the current full Hessian.

**Optimizer relevance:** SPlus combines cached Shampoo eigenbases with current-gradient normalization, shape-aware scaling and iterate averaging to stabilize language-model training.

**Evidence:** Official accepted-paper title and abstract.

### A Theoretical Framework for Grokking: Interpolation followed by Riemannian Norm Minimisation

**NeurIPS 2025 · Accept (poster)** · Etienne Boursier; Scott Pesme; Radu-Alexandru Dragomir

[Primary source](<https://openreview.net/forum?id=iSvAAHGFSw>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116559>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/de18052eb17cce56554a9637dd5aadba-Paper-Conference.pdf>)

**Topics:** Manifold; Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; M5 — Supporting geometry, statistics, and training-dynamics papers; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/de18052eb17cce56554a9637dd5aadba-Abstract-Conference.html>)

**Optimizer relevance:** Analyzes grokking through slow norm reduction on a manifold of minimizers induced by weight decay.

**Manifold relevance:** Explains grokking through weight-decay-induced slow Riemannian norm minimization; primarily an analysis of training dynamics.

**Training dynamics relevance:** Analyzes grokking through slow norm reduction on a manifold of minimizers induced by weight decay.

**Geometry:** Manifold of loss minimizers. **Manifold scope:** Related/supporting.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Weight decay; minimizer geometry; grokking delay.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Acceleration via silver step-size on Riemannian manifolds with applications to Wasserstein space

**NeurIPS 2025 · Accept (poster)** · Jiyoung Park; Abhishek Roy; Jonathan W. Siegel; Anirban Bhattacharya

[Primary source](<https://openreview.net/forum?id=Nl02znfTCT>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118337>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/347dae37f42ba41506cf7af753f98560-Paper-Conference.pdf>)

**Topics:** Manifold.

**Categories:** M1 — General manifold algorithms and convergence theory.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/347dae37f42ba41506cf7af753f98560-Abstract-Conference.html>)

**Manifold relevance:** Transfers silver-step acceleration ideas to manifold gradient descent using vector transport, including positive-definite matrix examples.

**Geometry:** Riemannian and Wasserstein geometry. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### ACCO: Accumulate While You Communicate for Communication-Overlapped Sharded LLM Training

**NeurIPS 2025 · Accept (poster)** · Adel Nabli; Louis Fournier; Pierre ERBACHER; Louis Serrano; Eugene Belilovsky; Edouard Oyallon

[Primary source](<https://openreview.net/forum?id=1qKUVyymXs>) · [Venue page](<https://neurips.cc/virtual/2025/poster/120191>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/6454dcd80b5373daaa97e53ce32c78a1-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/6454dcd80b5373daaa97e53ce32c78a1-Abstract-Conference.html>)

**Optimizer relevance:** ACCO overlaps communication and computation in sharded LLM training using delayed gradients with convergence analysis.

**Evidence:** Official accepted-paper title and abstract.

### AdaLRS: Loss-Guided Adaptive Learning Rate Search for Efficient Foundation Model Pretraining

**NeurIPS 2025 · Accept (poster)** · Hongyuan Dong; Dingkang Yang; Xiao Liang; ChaoFeng; Ran Jiao

[Primary source](<https://openreview.net/forum?id=Rc489jcc30>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118011>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/8516e0109e6c4a3cdd17645dd61af7c7-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/8516e0109e6c4a3cdd17645dd61af7c7-Abstract-Conference.html>)

**Optimizer relevance:** AdaLRS automatically adjusts learning rates using loss-descent velocity, with theoretical analysis and language-model pretraining experiments.

**Training dynamics relevance:** AdaLRS automatically adjusts learning rates using loss-descent velocity, with theoretical analysis and language-model pretraining experiments.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Loss-descent velocity; online rate selection.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Adam Reduces a Unique Form of Sharpness: Theoretical Insights Near the Minimizer Manifold

**NeurIPS 2025 · Accept (poster)** · Xinghan Li; Haodong Wen; Kaifeng Lyu

[Primary source](<https://openreview.net/forum?id=kCUDzyKQ7G>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116405>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/a82b0c6d19e4f53c5f2252a742ae8d5e-Paper-Conference.pdf>)

**Topics:** Manifold; Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; M5 — Supporting geometry, statistics, and training-dynamics papers; T5 — Stability, curvature and edge-of-stability dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/a82b0c6d19e4f53c5f2252a742ae8d5e-Abstract-Conference.html>)

**Optimizer relevance:** Analyzes Adam sharpness and implicit regularization near manifolds of minimizers using stochastic dynamics; distinguishes Adam and SGD curvature criteria.

**Manifold relevance:** Studies how Adam and SGD select different notions of sharpness near a manifold of minima.

**Training dynamics relevance:** Analyzes Adam sharpness and implicit regularization near manifolds of minimizers using stochastic dynamics; distinguishes Adam and SGD curvature criteria.

**Geometry:** Manifolds of minimizers and stochastic dynamics. **Manifold scope:** Related/supporting.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Adam noise; minimizer manifold; sharpness criterion.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Adaptive Riemannian ADMM for Nonsmooth Optimization: Optimal Complexity without Smoothing

**NeurIPS 2025 · Accept (poster)** · Kangkang Deng; Jiachen Jin; Jiang Hu; Hongxia Wang

[Primary source](<https://openreview.net/forum?id=lni933mlvF>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116261>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/bc46f5d72f432de4c58e1a311bad011b-Paper-Conference.pdf>)

**Topics:** Manifold.

**Categories:** M1 — General manifold algorithms and convergence theory.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/bc46f5d72f432de4c58e1a311bad011b-Abstract-Conference.html>)

**Manifold relevance:** ARADMM combines Riemannian-gradient and proximal steps in an adaptive augmented-Lagrangian splitting method.

**Geometry:** Riemannian constraints; nonsmooth composite objectives. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### AlphaDecay: Module-wise Weight Decay for Heavy-Tailed Balancing in LLMs

**NeurIPS 2025 · Accept (poster)** · Di He; Songjun Tu; Ajay Jaiswal; Li Shen; Ganzhao Yuan; Shiwei Liu; Lu Yin

[Primary source](<https://openreview.net/forum?id=MKEDsVWHd0>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118480>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/2aacf95ddc1ebd79832474bb41d13943-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/2aacf95ddc1ebd79832474bb41d13943-Abstract-Conference.html>)

**Training dynamics relevance:** AlphaDecay adapts decay strengths to module spectra rather than using uniform decay.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Module-wise weight decay; spectral tail statistics.

**Training qualification:** Heavy-tailed spectral scores motivate the rule; gains depend on the evaluated models and recipes.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/hed-ucas/AlphaDecay.>). Links extracted from the accepted abstract; code was not tested.

### Alternating Gradient Flows: A Theory of Feature Learning in Two-layer Neural Networks

**NeurIPS 2025 · Accept (poster)** · Daniel Kunin; Giovanni Luca Marchetti; Feng Chen; Dhruva Karkada; James Simon; Michael Deweese; Surya Ganguli; Nina Miolane

[Primary source](<https://openreview.net/forum?id=t7LKc0MMW6>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115627>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/06cbd2e81dfbd3bb4cb0abce95b32584-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/06cbd2e81dfbd3bb4cb0abce95b32584-Abstract-Conference.html>)

**Training dynamics relevance:** Alternating Gradient Flows approximates successive feature acquisition and loss drops from small initialization.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Initialization scale; feature activation times.

**Training qualification:** Rigorous limiting results concern specified network classes and vanishing initialization.

**Evidence:** Official accepted-paper title and abstract.

### AltLoRA: Towards Better Gradient Approximation in Low-Rank Adaptation with Alternating Projections

**NeurIPS 2025 · Accept (poster)** · Xin Yu; Yujia Wang; Jinghui Chen; Lingzhou Xue

[Primary source](<https://openreview.net/forum?id=9YNJ03jYsU>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119533>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/35c3db8db1b962538b0958af56ba329b-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/35c3db8db1b962538b0958af56ba329b-Abstract-Conference.html>)

**Optimizer relevance:** AltLoRA alternates low-rank projections to approximate full gradients more effectively while retaining small optimizer states.

**Evidence:** Official accepted-paper title and abstract.

### An Adaptive Algorithm for Bilevel Optimization on Riemannian Manifolds

**NeurIPS 2025 · Accept (poster)** · Xu Shi; Rufeng Xiao; Rujun Jiang

[Primary source](<https://openreview.net/forum?id=9r3OQhPiqT>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119506>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/867bc56be95b320a3a7af20bb4cbd9a8-Paper-Conference.pdf>)

**Topics:** Manifold.

**Categories:** M1 — General manifold algorithms and convergence theory.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/867bc56be95b320a3a7af20bb4cbd9a8-Abstract-Conference.html>)

**Manifold relevance:** AdaRHD adapts hypergradient steps in bilevel manifold optimization and analyzes the effect of retraction geometry.

**Geometry:** Riemannian bilevel optimization and retractions. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### An Analytical Theory of Spectral Bias in the Learning Dynamics of Diffusion Models

**NeurIPS 2025 · Accept (spotlight)** · Binxu Wang; Cengiz Pehlevan

[Primary source](<https://openreview.net/forum?id=SDhOClkyqC>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117950>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/8a0d3f77bb435817807d463c5dcef1ab-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/8a0d3f77bb435817807d463c5dcef1ab-Abstract-Conference.html>)

**Training dynamics relevance:** Solves spectral learning dynamics for simple denoisers and studies their implications for diffusion-model generation.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Training time; data spectrum; stopping time.

**Training qualification:** Exact formulas concern linear/linear-convolutional denoisers; deeper-model extensions are empirical.

**Evidence:** Official accepted-paper title and abstract.

### Any-stepsize Gradient Descent for Separable Data under Fenchel–Young Losses

**NeurIPS 2025 · Accept (spotlight)** · Han Bao; Shinsaku Sakaue; Yuki Takezawa

[Primary source](<https://openreview.net/forum?id=D6aCr4RRdt>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119241>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/69f98acf161316ed896047e45da3bc0c-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/69f98acf161316ed896047e45da3bc0c-Abstract-Conference.html>)

**Training dynamics relevance:** Studies convergence with arbitrarily chosen fixed steps under Fenchel-Young losses on separable data.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Constant step size; loss choice; separation margin.

**Training qualification:** Arbitrary-step convergence relies on separability/loss structure and is not a guarantee for arbitrary neural losses.

**Evidence:** Official accepted-paper title and abstract.

### ASGO: Adaptive Structured Gradient Optimization

**NeurIPS 2025 · Accept (poster)** · Kang An; Yuxing Liu; Rui Pan; Yi Ren; Shiqian Ma; Donald Goldfarb; Tong Zhang

[Primary source](<https://openreview.net/forum?id=fru52tkjHf>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116796>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/b862a40b617719cde47fa268b8d5c91d-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/b862a40b617719cde47fa268b8d5c91d-Abstract-Conference.html>)

**Quantity:** Structured adaptive matrix preconditioners.

**Computational idea:** ASGO exploits low-rank gradients and block-structured curvature in adaptive preconditioning.

**Scope:** Deep learning. **Qualification:** Structural assumptions and convergence conditions qualify the guarantees; matrix preconditioning need not equal a Newton step.

**Optimizer relevance:** ASGO uses structured preconditioning to exploit low-rank gradients and block-structured curvature, with convergence analysis and language-model experiments.

**Evidence:** Official accepted-paper title and abstract.

### Asymptotic theory of SGD with a general learning-rate

**NeurIPS 2025 · Accept (poster)** · Or Goldreich; Ziyang Wei; SOHAM BONNERJEE; Jiaqi Li; Wei Biao Wu

[Primary source](<https://openreview.net/forum?id=y5Diyh9XEQ>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115186>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/21ad9738bb0d93eb2e9ade69ff809da0-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/21ad9738bb0d93eb2e9ade69ff809da0-Abstract-Conference.html>)

**Training dynamics relevance:** Develops asymptotic SGD uncertainty theory for schedules beyond polynomial decay.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Cyclical learning rates; linear decay; general schedules.

**Training qualification:** The results are asymptotic under regularity conditions; they do not select a universally optimal practical schedule.

**Evidence:** Official accepted-paper title and abstract.

### Better Training Data Attribution via Better Inverse Hessian-Vector Products

**NeurIPS 2025 · Accept (poster)** · Andrew Wang; Elisa Nguyen; Runshi Yang; Juhan Bae; Sheila McIlraith; Roger Grosse

[Primary source](<https://openreview.net/forum?id=7LTTzYXyJ1>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119714>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/936ce22b767cf1a1496083e4725d3b21-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/936ce22b767cf1a1496083e4725d3b21-Abstract-Conference.html>)

**Quantity:** Damped inverse-curvature-vector products for data attribution.

**Computational idea:** ASTRA applies EKFAC-preconditioned stochastic Neumann iterations, refining the initial structured approximation with additional curvature-vector products.

**Scope:** Deep learning. **Qualification:** The practical operator is a damped generalized Gauss-Newton approximation; finite iterations do not give an exact inverse of an arbitrary loss Hessian.

**Optimizer relevance:** ASTRA uses an EKFAC preconditioner to accelerate stochastic Neumann iterations for training-data attribution. This is a substantive EKFAC application, rather than a new LLM training optimizer.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://proceedings.neurips.cc/paper_files/paper/2025/file/936ce22b767cf1a1496083e4725d3b21-Paper-Conference.pdf>): Sections 2.1–3, equations (5)–(9), pages 3–6. Confirmed the damped GGN operator and EKFAC-preconditioned stochastic Neumann update; matrix-vector products avoid forming the full inverse.

### Bilevel ZOFO: Efficient LLM Fine-Tuning and Meta-Training

**NeurIPS 2025 · Accept (poster)** · Reza Shirkavand; Peiran Yu; Qi He; Heng Huang

[Primary source](<https://openreview.net/forum?id=v6vBK4t8vB>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115441>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/5f999632c48f87cffb214e575581e4a9-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/5f999632c48f87cffb214e575581e4a9-Abstract-Conference.html>)

**Optimizer relevance:** Combines first-order low-rank adapter optimization with zeroth-order backbone updates in a bilevel fine-tuning scheme.

**Evidence:** Official accepted-paper title and abstract.

### Binary Quadratic Quantization: Beyond First-Order Quantization for Real-Valued Matrix Compression

**NeurIPS 2025 · Accept (poster)** · Kyo Kuroki; Yasuyuki Okoshi; Thiem Van Chu; Kazushi Kawamura; Masato Motomura

[Primary source](<https://openreview.net/forum?id=5MGClYw1cR>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119877>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/e7cf82c8f34920d20299a84b16b720e8-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/e7cf82c8f34920d20299a84b16b720e8-Abstract-Conference.html>)

**Quantity:** Compact real-valued matrix approximation.

**Computational idea:** Binary Quadratic Quantization represents matrices with quadratic expressions in binary bases.

**Scope:** Deep learning. **Qualification:** A lossy representation with reconstruction and downstream-task trade-offs, not lossless low-bit arithmetic.

**Evidence:** Official accepted-paper title and abstract.

### Breaking the Frozen Subspace: Importance Sampling for Low-Rank Optimization in LLM Pretraining

**NeurIPS 2025 · Accept (poster)** · Haochen Zhang; Junze Yin; Guanchu Wang; Zirui Liu; Lin Yang; Tianyi Zhang; Anshumali Shrivastava; Vladimir Braverman

[Primary source](<https://openreview.net/forum?id=ZdmmOAN4h3>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117335>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/0edd294b7632fc96903abfbf3b264fc1-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers; X4 — Randomized sketching and kernel approximations.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/0edd294b7632fc96903abfbf3b264fc1-Abstract-Conference.html>)

**Quantity:** Adaptively sampled low-rank gradient projections.

**Computational idea:** Uses importance sampling to update gradient subspaces in memory-efficient LLM optimization.

**Scope:** Deep learning. **Qualification:** A low-rank approximation with assumptions behind the convergence analysis, not lossless compression of every gradient.

**Optimizer relevance:** Uses importance sampling to refresh low-rank optimization subspaces and avoid permanently restricting training to a frozen subspace.

**Evidence:** Official accepted-paper title and abstract.

### CDFlow: Building Invertible Layers with Circulant and Diagonal Matrices

**NeurIPS 2025 · Accept (poster)** · XUCHEN FENG; Siyu Liao

[Primary source](<https://openreview.net/forum?id=XF4JM2MTSF>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117530>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/054a9c9f6249eee0093a85ccee5b3313-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/054a9c9f6249eee0093a85ccee5b3313-Abstract-Conference.html>)

**Quantity:** Linear-layer inverses and log-determinants in normalizing flows.

**Computational idea:** CDFlow factors layers into circulant and diagonal matrices, using FFT algebra for cheap inverse application and determinants.

**Scope:** Deep learning. **Qualification:** The identities are exact for the structured invertible layer; representing an arbitrary dense layer may require many factors.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://proceedings.neurips.cc/paper_files/paper/2025/file/054a9c9f6249eee0093a85ccee5b3313-Paper-Conference.pdf>): Sections 3.1–3.2, equations (13)–(19), pages 4–5. Confirmed FFT-diagonalized circulant factors and factorwise log-determinants. The fast inverse operation is applying the structured inverse to a vector, not materializing an arbitrary dense inverse.

### Closed-Form Training Dynamics Reveal Learned Features and Linear Structure in Word2Vec-like Models

**NeurIPS 2025 · Accept (poster)** · Dhruva Karkada; James Simon; Yasaman Bahri; Michael Deweese

[Primary source](<https://openreview.net/forum?id=VS9N6q6b0k>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117686>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/060f64f690417a5cc6a882479478fd96-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/060f64f690417a5cc6a882479478fd96-Abstract-Conference.html>)

**Training dynamics relevance:** Solves approximate Word2Vec-like gradient-flow dynamics and explains sequential acquisition of corpus-derived subspaces.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Initialization; training time; embedding dimension.

**Training qualification:** Closed forms use a quartic loss approximation; resemblance to Word2Vec is empirically assessed.

**Evidence:** Official accepted-paper title and abstract.

### Communication-Efficient Language Model Training Scales Reliably and Robustly: Scaling Laws for DiLoCo

**NeurIPS 2025 · Accept (spotlight)** · Zachary Charles; Gabriel Teston; Lucio Dery; John Rush; Nova Fallen; Zachary Garrett; Arthur Szlam; Arthur Douillard

[Primary source](<https://openreview.net/forum?id=X4SCxcgb3O>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117548>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/99acb4c087266e80b547aed79247266b-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T2 — Batch size, gradient noise and training efficiency; T4 — Compute, data and model scaling laws; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/99acb4c087266e80b547aed79247266b-Abstract-Conference.html>)

**Training dynamics relevance:** Studies how DiLoCo scaling changes with model size and tuning under fixed compute.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Replica count; local-update settings; token budget; batch size.

**Training qualification:** Advantages over data parallelism are conditional on tuning and the evaluated communication/training regime.

**Evidence:** Official accepted-paper title and abstract.

### Complexity Scaling Laws for Neural Models using Combinatorial Optimization

**NeurIPS 2025 · Accept (poster)** · Lowell Weissman; Michael Krumdick; A. Abbott

[Primary source](<https://openreview.net/forum?id=EdKl4PulMX>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119119>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1c9dbe4d49fa0ac833959230a9895c06-Paper-Conference.pdf>)

**Topics:** Training dynamics.

**Categories:** T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/1c9dbe4d49fa0ac833959230a9895c06-Abstract-Conference.html>)

**Training dynamics relevance:** Studies predictable suboptimality trends as combinatorial task complexity grows.

**Training study context:** Reinforcement learning.

**Hyperparameters / scaling axes:** Problem size/complexity; model capacity.

**Training qualification:** The case study is TSP; this is task-complexity scaling rather than Chinchilla-style LLM pretraining.

**Evidence:** Official accepted-paper title and abstract.

### Compress Large Language Models via  Collaboration Between Learning and Matrix Approximation

**NeurIPS 2025 · Accept (poster)** · Yuesen Liao; Zhiwei Li; Binrui Wu; Zihao Cheng; Su Zhao; Shuai Chen; Weizhong Zhang

[Primary source](<https://openreview.net/forum?id=4EkEL77k6O>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119963>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/5752f9fd2d5c40174738d6f02c202e72-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/5752f9fd2d5c40174738d6f02c202e72-Abstract-Conference.html>)

**Quantity:** Sparse-plus-low-rank LLM weight approximation.

**Computational idea:** A bilevel framework learns layer sparsity and retained ranks while an adapted QR algorithm accelerates inner matrix approximation.

**Scope:** Deep learning. **Qualification:** Compression is approximate, with an outer stochastic allocation procedure and task-dependent accuracy.

**Evidence:** Official accepted-paper title and abstract.

### Compute-Optimal Scaling for Value-Based Deep RL

**NeurIPS 2025 · Accept (poster)** · Preston Fu; Oleh Rybkin; Zhiyuan (Paul) Zhou; Michal Nauman; Pieter Abbeel; Sergey Levine; Aviral Kumar

[Primary source](<https://openreview.net/forum?id=9GzyCtlngK>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119555>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/eaf550b6c727bc065244513f2260a30e-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T2 — Batch size, gradient noise and training efficiency; T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/eaf550b6c727bc065244513f2260a30e-Abstract-Conference.html>)

**Training dynamics relevance:** Studies compute allocation in value-based RL and explains when large batches induce TD overfitting.

**Training study context:** Reinforcement learning.

**Hyperparameters / scaling axes:** Model size; batch size; update-to-data ratio.

**Training qualification:** The compute-optimal trade-offs are RL-specific and differ from token-based pretraining.

**Evidence:** Official accepted-paper title and abstract.

### Continual Optimization with Symmetry Teleportation for Multi-Task Learning

**NeurIPS 2025 · Accept (poster)** · Zhipeng Zhou; Ziqiao Meng; Pengcheng Wu; Peilin Zhao; Chunyan Miao

[Primary source](<https://openreview.net/forum?id=8P5MUySaqi>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119621>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/fa30825df7ceaba452d5533538ea29c2-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/fa30825df7ceaba452d5533538ea29c2-Abstract-Conference.html>)

**Optimizer relevance:** COST uses loss-preserving symmetry transformations and past trajectories to improve optimization for multi-task learning, including LoRA.

**Evidence:** Official accepted-paper title and abstract.

### Continuous-time Riemannian SGD and SVRG Flows on Wasserstein Probabilistic Space

**NeurIPS 2025 · Accept (poster)** · Mingyang Yi; Bohan Wang

[Primary source](<https://openreview.net/forum?id=PlQqwb7Bte>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118190>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/551d050b0e351ad566e00a088d1e7b1f-Paper-Conference.pdf>)

**Topics:** Manifold.

**Categories:** M1 — General manifold algorithms and convergence theory.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/551d050b0e351ad566e00a088d1e7b1f-Abstract-Conference.html>)

**Manifold relevance:** Analyzes continuous-time Riemannian SGD and variance-reduced flows in Wasserstein geometry.

**Geometry:** Wasserstein space of probability measures. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### Controlling the Flow: Stability and Convergence for Stochastic Gradient Descent with Decaying Regularization

**NeurIPS 2025 · Accept (poster)** · Sebastian Kassing; Simon Weissmann; Leif Döring

[Primary source](<https://openreview.net/forum?id=hMZnFo0FLF>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116658>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/6cf05c14e645df408001fbb669976ec0-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/6cf05c14e645df408001fbb669976ec0-Abstract-Conference.html>)

**Training dynamics relevance:** Analyzes how step sizes and decaying Tikhonov regularization jointly control SGD convergence to minimum-norm solutions.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Step-size schedule; vanishing regularization.

**Training qualification:** Convex smooth Hilbert-space theory, with inverse-problem examples, rather than arbitrary deep learning.

**Evidence:** Official accepted-paper title and abstract.

### Convergence Rates for Gradient Descent on the Edge of Stability for Overparametrised Least Squares

**NeurIPS 2025 · Accept (poster)** · Lachlan MacDonald; Hancheng Min; Leandro Palma; Salma Tarmoun; Ziqing Xu; Rene Vidal

[Primary source](<https://openreview.net/forum?id=MU0JuT0A54>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118466>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/d9af4d6ac714626b652da5616ca71f99-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/d9af4d6ac714626b652da5616ca71f99-Abstract-Conference.html>)

**Training dynamics relevance:** Decomposes GD into motion along and across a minimizer manifold and characterizes three stability regimes.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Learning rate; overparameterization; minimizer geometry.

**Training qualification:** Formal rates concern overparameterized least squares, with different limits across subcritical, critical and supercritical rates.

**Evidence:** Official accepted-paper title and abstract.

### Critical Batch Size Revisited: A Simple Empirical Approach to Large-Batch Language Model Training

**NeurIPS 2025 · Accept (spotlight)** · Will Merrill; Shane Arora; Dirk Groeneveld; Hanna Hajishirzi

[Primary source](<https://openreview.net/forum?id=XUKUx7Xu89>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117500>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/a99f732df9b668284b449da0214a3286-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/a99f732df9b668284b449da0214a3286-Abstract-Conference.html>)

**Optimizer relevance:** Revisits critical batch size during language-model pretraining and motivates batch-size warmup from its changing training trajectory.

**Training dynamics relevance:** Revisits critical batch size during language-model pretraining and motivates batch-size warmup from its changing training trajectory.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Critical batch size; batch warm-up; Adam normalization.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### CTSketch: Compositional Tensor Sketching for Scalable Neurosymbolic Learning

**NeurIPS 2025 · Accept (poster)** · Seewon Choi; Alaia Solko-Breslin; Rajeev Alur; Eric Wong

[Primary source](<https://openreview.net/forum?id=mor7s1NGBV>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116184>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/6d53193a098b982229340a7c3eb0ecbf-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X4 — Randomized sketching and kernel approximations.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/6d53193a098b982229340a7c3eb0ecbf-Abstract-Conference.html>)

**Quantity:** Output distributions of composed symbolic programs.

**Computational idea:** CTSketch decomposes symbolic programs and represents subprogram behavior with tensor sketches for differentiable neurosymbolic learning.

**Scope:** Deep learning. **Qualification:** The distribution is approximated; sketch size and compositional structure control error.

**Evidence:** Official accepted-paper title and abstract.

### Data Mixing Can Induce Phase Transitions in Knowledge Acquisition

**NeurIPS 2025 · Accept (spotlight)** · Xinran Gu; Kaifeng Lyu; Jiazheng Li; Jingzhao Zhang

[Primary source](<https://openreview.net/forum?id=tQZK5frjVU>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115595>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/eee7ae5cf0c4356c2aeca400771791aa-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/eee7ae5cf0c4356c2aeca400771791aa-Abstract-Conference.html>)

**Training dynamics relevance:** Finds abrupt knowledge-acquisition transitions when dense knowledge data are mixed with web text.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Data mixing ratio; model capacity; training duration.

**Training qualification:** The controlled biography study shows that mixture rankings can change with size; it is not a universal discontinuity claim.

**Evidence:** Official accepted-paper title and abstract.

### Degrees of Freedom for Linear Attention: Distilling Softmax Attention with Optimal Feature Efficiency

**NeurIPS 2025 · Accept (poster)** · Naoki Nishikawa; Rei Higuchi; Taiji Suzuki

[Primary source](<https://openreview.net/forum?id=7qq1UeCYL6>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119670>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/c98ef086dc70d528e1c1aa1e66893365-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/c98ef086dc70d528e1c1aa1e66893365-Abstract-Conference.html>)

**Quantity:** Feature dimensions for approximating softmax attention.

**Computational idea:** Uses statistical degrees of freedom to allocate linear-attention feature dimensions and trains layer-specific features.

**Scope:** Deep learning. **Qualification:** Distillation approximates softmax attention; guarantees depend on the feature and data assumptions.

**Evidence:** Official accepted-paper title and abstract.

### Differentially Private Federated Low Rank Adaptation Beyond Fixed-Matrix

**NeurIPS 2025 · Accept (poster)** · Ming Wen; Jiaqi Zhu; Yuedong Xu; Yipeng Zhou; DINGDING HAN

[Primary source](<https://openreview.net/forum?id=TecJ926Vgn>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117836>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/a686ddca183f72ee9f3f04896eb11bcb-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; X4 — Randomized sketching and kernel approximations.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/a686ddca183f72ee9f3f04896eb11bcb-Abstract-Conference.html>)

**Quantity:** Private aggregation of two-factor low-rank adapters.

**Computational idea:** FedASK uses a double-sketch pipeline inspired by randomized SVD to reconstruct global low-rank factors.

**Scope:** Deep learning. **Qualification:** Its exact-aggregation property must be read together with the sketch construction and privacy noise; it is not exact noiseless centralized training.

**Optimizer relevance:** FedASK uses two stages of sketching to aggregate private federated LoRA updates while allowing both adapter factors to change.

**Evidence:** Official accepted-paper title and abstract.

### Distribution-Aware Tensor Decomposition for Compression of Convolutional Neural Networks

**NeurIPS 2025 · Accept (poster)** · Alper KALLE; Théo Rudkiewicz; Mohamed Ouerfelli; Mohamed Tamaazousti

[Primary source](<https://openreview.net/forum?id=ODgWBaErst>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118313>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/7f6901ebab786e43b21530328fc989ca-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/7f6901ebab786e43b21530328fc989ca-Abstract-Conference.html>)

**Quantity:** Input-covariance-weighted tensor compression.

**Computational idea:** Alternating least squares for Tucker and CP decompositions minimizes layer-output error under a covariance-weighted norm.

**Scope:** Deep learning. **Qualification:** Uses estimated input statistics; good transfer across datasets is empirical rather than universal.

**Evidence:** Official accepted-paper title and abstract.

### Don't be lazy: CompleteP enables compute-efficient deep transformers

**NeurIPS 2025 · Accept (poster)** · Nolan Dey; Bin Zhang; Lorenzo Noci; Mufan Li; Blake Bordelon; Shane Bergsma; Cengiz Pehlevan; Boris Hanin; Joel Hestness

[Primary source](<https://openreview.net/forum?id=lMU2kaMANl>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116289>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/c917d8b9e01427f3184d80ade22f4d1f-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/c917d8b9e01427f3184d80ade22f4d1f-Abstract-Conference.html>)

**Optimizer relevance:** CompleteP develops depth/width parameterization rules for hyperparameter transfer in language-model training.

**Training dynamics relevance:** CompleteP develops depth/width parameterization rules for hyperparameter transfer in language-model training.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Depth/width parameterization; feature learning; rate transfer.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/EleutherAI/nanoGPT-mup/tree/completep.>). Links extracted from the accepted abstract; code was not tested.

### Dynamical Low-Rank Compression of Neural Networks with Robustness under Adversarial Attacks

**NeurIPS 2025 · Accept (oral)** · Steffen Schotthöfer; Lexie Yang; Stefan Schnake

[Primary source](<https://openreview.net/forum?id=7AwFJzgIUW>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119731>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/cd5c450b7b3a004380cba0ff704a0cc9-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods; X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/cd5c450b7b3a004380cba0ff704a0cc9-Abstract-Conference.html>)

**Quantity:** Dynamically compressed neural-network weights.

**Computational idea:** Dynamical low-rank training with condition-number regularization adapts compact layer factors while controlling sensitivity.

**Scope:** Deep learning. **Qualification:** Compression and robustness are empirically assessed; spectral regularization is not a universal adversarial certificate.

**Optimizer relevance:** Combines dynamical low-rank neural-network training with spectral regularization of the low-rank core to improve compression and adversarial robustness.

**Evidence:** Official accepted-paper title and abstract.

### E2Former: An Efficient and Equivariant Transformer with Linear-Scaling Tensor Products

**NeurIPS 2025 · Accept (spotlight)** · Yunyang Li; Lin Huang; Zhihao Ding; Xinran Wei; Chu Wang; Han Yang; Zun Wang; Chang Liu; Yu Shi; Peiran Jin; Tao Qin; Mark Gerstein; Jia Zhang

[Primary source](<https://openreview.net/forum?id=ls5L4IMEwt>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116254>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/21f7b745f73ce0d1f9bcea7f40b1388e-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/21f7b745f73ce0d1f9bcea7f40b1388e-Abstract-Conference.html>)

**Quantity:** Equivariant spherical tensor products.

**Computational idea:** E2Former uses Wigner 6j identities to transfer expensive contractions from edges to nodes.

**Scope:** Deep learning. **Qualification:** The computational advantage depends on the equivariant architecture and graph structure; it is not a general dense-matrix speedup.

**Evidence:** Official accepted-paper title and abstract.

### Efficient Adaptive Federated Optimization

**NeurIPS 2025 · Accept (poster)** · Su Hyeong Lee; Sidharth Sharma; Manzil Zaheer; Tian Li

[Primary source](<https://openreview.net/forum?id=dopfjQFr65>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116984>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/fab71c08b15508fd6c435e59b0e82b68-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/fab71c08b15508fd6c435e59b0e82b68-Abstract-Conference.html>)

**Optimizer relevance:** FedAda2 and FedAda2++ reduce communication of adaptive preconditioners and memory use in federated learning, with image and text experiments.

**Evidence:** Official accepted-paper title and abstract.

### Efficient Data Selection at Scale via Influence Distillation

**NeurIPS 2025 · Accept (poster)** · Mahdi Nikdan; Vincent Cohen-Addad; Dan Alistarh; Vahab Mirrokni

[Primary source](<https://openreview.net/forum?id=E6ZdfjtoiX>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119164>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/d2d4f6858cc2d21fd0230244fcb34f1d-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/d2d4f6858cc2d21fd0230244fcb34f1d-Abstract-Conference.html>)

**Quantity:** Optimizer-aware influence scores for data selection.

**Computational idea:** Influence Distillation computes scores on landmark examples and propagates them to approximate second-order data selection under GD or Adam.

**Scope:** Deep learning. **Qualification:** Landmark distillation approximates influence scores and does not compute exact leave-one-out retraining effects.

**Evidence:** Official accepted-paper title and abstract.

### Efficient Low Rank Attention for Long-Context Inference in Large Language Models

**NeurIPS 2025 · Accept (poster)** · Li Tenghui; Guoxu Zhou; Xuyang Zhao; Yuning Qiu; Qibin Zhao

[Primary source](<https://openreview.net/forum?id=Mc0eJHZhW5>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118451>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/36db9d16a9f80ede9e69d5d174cfd6ea-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/36db9d16a9f80ede9e69d5d174cfd6ea-Abstract-Conference.html>)

**Quantity:** Proxy attention scores and KV-cache retrieval.

**Computational idea:** LRQK factorizes query/key matrices to rank low-cost proxy scores, then retrieves selected full-precision KV entries.

**Scope:** Deep learning. **Qualification:** Full precision on selected entries does not make token-sparse attention identical to full dense attention.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/tenghuilee/LRQK>). Links extracted from the accepted abstract; code was not tested.

### Efficient Parametric SVD of Koopman Operator for Stochastic Dynamical Systems

**NeurIPS 2025 · Accept (poster)** · Minchan Jeong; Jongha (Jon) Ryu; Se-Young Yun; Gregory Wornell

[Primary source](<https://openreview.net/forum?id=kL2pnzClyD>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116395>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/24826a1c623fe41706850748f3dc7370-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/24826a1c623fe41706850748f3dc7370-Abstract-Conference.html>)

**Quantity:** Leading singular functions of the Koopman operator.

**Computational idea:** Learns low-rank singular subspaces with an objective that avoids differentiating through unstable empirical-moment inverses and SVDs.

**Scope:** Deep learning. **Qualification:** Learns an approximation from trajectory data rather than exactly decomposing the true infinite-dimensional operator.

**Evidence:** Official accepted-paper title and abstract.

### Emergence and scaling laws in SGD learning of shallow neural networks

**NeurIPS 2025 · Accept (poster)** · Yunwei Ren; Eshaan Nichani; Denny Wu; Jason Lee

[Primary source](<https://openreview.net/forum?id=kA2H90nm26>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116407>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/36d13b71487b29965a2d3f5fcc109afc-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/36d13b71487b29965a2d3f5fcc109afc-Abstract-Conference.html>)

**Training dynamics relevance:** Shows many abrupt feature-learning transitions can combine into smooth aggregate scaling laws.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Teacher/student width; signal strengths; SGD time.

**Training qualification:** The theory uses shallow networks, Gaussian inputs and specified activation structure.

**Evidence:** Official accepted-paper title and abstract.

### Enhancing Optimizer Stability: Momentum Adaptation of The NGN Step-size

**NeurIPS 2025 · Accept (poster)** · Rustem Islamov; Niccolò Ajroldi; Antonio Orvieto; Aurelien Lucchi

[Primary source](<https://openreview.net/forum?id=9t2OtyQ9mf>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119505>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1470947b2ecc3a877ef124b50efc4d37-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/1470947b2ecc3a877ef124b50efc4d37-Abstract-Conference.html>)

**Optimizer relevance:** NGN-M combines momentum and adaptive step sizes to improve stability of normalized-gradient optimization.

**Evidence:** Official accepted-paper title and abstract.

### Escaping saddle points without Lipschitz smoothness: the power of nonlinear preconditioning

**NeurIPS 2025 · Accept (spotlight)** · Alexander Bodard; Panagiotis Patrinos

[Primary source](<https://openreview.net/forum?id=7qrhHzZpTA>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119669>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/b3bfae1e280ded2c7b441108a28c293e-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/b3bfae1e280ded2c7b441108a28c293e-Abstract-Conference.html>)

**Optimizer relevance:** Studies saddle-point escape under weaker smoothness assumptions with nonlinear preconditioning; theoretical relevance to optimizer design.

**Evidence:** Official accepted-paper title and abstract.

### EvoLM: In Search of Lost Language Model Training Dynamics

**NeurIPS 2025 · Accept (oral)** · Zhenting Qi; Fan Nie; Alexandre Alahi; James Zou; Himabindu Lakkaraju; Yilun Du; Eric Xing; Sham Kakade; Hanlin Zhang

[Primary source](<https://openreview.net/forum?id=B6bE2GC71a>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119408>) · [PDF](<https://openreview.net/pdf?id=B6bE2GC71a>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

**Training dynamics relevance:** EvoLM provides controlled multi-stage trajectories to study diminishing returns, forgetting and stage transitions.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Pretraining duration; continued training; SFT/RL design.

**Training qualification:** Its 1B/4B model suite supports specific empirical comparisons, not all production-scale training regimes.

**Evidence:** Official accepted-paper title and abstract.

### FedSVD: Adaptive Orthogonalization for Private Federated Learning with LoRA

**NeurIPS 2025 · Accept (poster)** · Seanie Lee; Sangwoo Park; Dong Bok Lee; Dominik Wagner; Haebin Seong; Tobias Bocklet; Juho Lee; Sung Ju Hwang

[Primary source](<https://openreview.net/forum?id=Qq19n9LZ97>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118097>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/ad922aa85d4027ff3502e8e5f406e828-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/ad922aa85d4027ff3502e8e5f406e828-Abstract-Conference.html>)

**Quantity:** Orthogonalized aggregate LoRA updates.

**Computational idea:** FedSVD refactorizes the server-aggregated update by SVD to refresh one orthonormal adapter factor.

**Scope:** Deep learning. **Qualification:** A privacy-aware update reparameterization, not a faster generic SVD routine.

**Optimizer relevance:** FedSVD periodically refactorizes aggregated LoRA updates to adapt orthonormal directions and control differential-privacy noise amplification.

**Evidence:** Official accepted-paper title and abstract.

### Finding Low-Rank Matrix Weights in DNNs via Riemannian Optimization: RAdaGrad and RAdamW

**NeurIPS 2025 · Accept (poster)** · Fengmiao Bian; Jinyang ZHENG; Ziyun Liu; Jianzhou Luo; Jian-Feng CAI

[Primary source](<https://openreview.net/forum?id=tiGFiCrmKm>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115564>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/5679173c400b332796426e443ab5ea0d-Paper-Conference.pdf>)

**Topics:** Manifold; Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; M2 — Manifold-based LLM training and low-rank adaptation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/5679173c400b332796426e443ab5ea0d-Abstract-Conference.html>)

**Optimizer relevance:** RAdaGrad and RAdamW optimize fixed-rank weight matrices with adaptive Riemannian metrics; experiments include LLM and diffusion-model adaptation.

**Manifold relevance:** RAdaGrad and RAdamW perform adaptive Riemannian optimization directly on fixed-rank matrix weights.

**Geometry:** Fixed-rank matrix manifold with adaptive metrics. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### Finite-Time Analysis of Stochastic Nonconvex Nonsmooth  Optimization on the Riemannian Manifolds

**NeurIPS 2025 · Accept (poster)** · Emre Sahinoglu; Youbang Sun; Shahin Shahrampour

[Primary source](<https://openreview.net/forum?id=cbWApYUvZ9>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117078>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/c2bd9242609219deb380f161682f4568-Paper-Conference.pdf>)

**Topics:** Manifold.

**Categories:** M1 — General manifold algorithms and convergence theory.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/c2bd9242609219deb380f161682f4568-Abstract-Conference.html>)

**Manifold relevance:** Develops stochastic and zeroth-order algorithms with complexity guarantees for nonsmooth nonconvex manifold optimization.

**Geometry:** General Riemannian manifolds. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### Fira: Can We Achieve Full-rank Training of LLMs Under Low-rank Constraint?

**NeurIPS 2025 · Accept (poster)** · Xi Chen; Kaituo Feng; Changsheng Li; Xunhao Lai; Xiangyu Yue; Ye Yuan; Guoren Wang

[Primary source](<https://openreview.net/forum?id=7aSBAw7tJf>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119690>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/aeae2c860cbe283ef73344c4ecd52567-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/aeae2c860cbe283ef73344c4ecd52567-Abstract-Conference.html>)

**Optimizer relevance:** Fira combines full-rank weight updates with low-rank optimizer states, norm scaling and growth control.

**Evidence:** Official accepted-paper title and abstract.

### Flash Invariant Point Attention

**NeurIPS 2025 · Accept (spotlight)** · Andrew Liu; Axel Elaldi; Nicholas Franklin; Nathan Russell; Gurinder Atwal; Yih-En Ban; Olivia Viessmann

[Primary source](<https://openreview.net/forum?id=gKsG5qR3Bt>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116755>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/07ea874e9e4f71ec6680a3574a485a36-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/07ea874e9e4f71ec6680a3574a485a36-Abstract-Conference.html>)

**Quantity:** Geometry-aware invariant point attention.

**Computational idea:** FlashIPA factorizes invariant point attention to reuse efficient FlashAttention operations.

**Scope:** Deep learning. **Qualification:** Efficiency and quality claims concern the proposed IPA formulation and evaluated structural-biology models.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/flagshippioneering/flash_ipa.>). Links extracted from the accepted abstract; code was not tested.

### FlashBias: Fast Computation of Attention with Bias

**NeurIPS 2025 · Accept (poster)** · Haixu Wu; Minghao Guo; Yuezhou Ma; Yuanxu Sun; Jianmin Wang; Wojciech Matusik; Mingsheng Long

[Primary source](<https://openreview.net/forum?id=7L4NvUtZY3>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119716>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1dc3d70df51a218497529df998a8a8ce-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/1dc3d70df51a218497529df998a8a8ce-Abstract-Conference.html>)

**Quantity:** Attention with additive bias matrices.

**Computational idea:** FlashBias exploits low-rank structure to retain efficient fused attention for biased scores.

**Scope:** Deep learning. **Qualification:** Exact for supported bias families; general biases use approximation and must be distinguished from those exact cases.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/thuml/FlashBias.>). Links extracted from the accepted abstract; code was not tested.

### FlashMoE: Fast Distributed MoE in a Single Kernel

**NeurIPS 2025 · Accept (poster)** · Osayamen Aimuyo; Byungsoo Oh; Rachee Singh

[Primary source](<https://openreview.net/forum?id=EZfDHprhZM>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119124>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/918d938bd209e5b56072777366f8a211-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/918d938bd209e5b56072777366f8a211-Abstract-Conference.html>)

**Quantity:** Distributed mixture-of-experts matrix operations and routing.

**Computational idea:** FlashMoE fuses expert computation and device-initiated communication in a persistent GPU kernel.

**Scope:** Deep learning. **Qualification:** Performance depends on the GPU topology, shapes and precision; reported comparisons are not universal speedup factors.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/osayamenja/FlashMoE.>). Links extracted from the accepted abstract; code was not tested.

### Follow the Energy, Find the Path: Riemannian Metrics from Energy-Based Models

**NeurIPS 2025 · Accept (poster)** · Louis Bethune; David Vigouroux; Yilun Du; Rufin VanRullen; Thomas Serre; Victor Boutin

[Primary source](<https://openreview.net/forum?id=BOiQ7Kd5Lx>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119377>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/8cc4d34998c0b4006641ccd1341022b7-Paper-Conference.pdf>)

**Topics:** Manifold.

**Categories:** M5 — Supporting geometry, statistics, and training-dynamics papers.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/8cc4d34998c0b4006641ccd1341022b7-Abstract-Conference.html>)

**Manifold relevance:** Constructs data-dependent geometry and studies geodesics; relevant geometric computation, with a different target from training an optimizer on a fixed manifold.

**Geometry:** Riemannian metric induced by an energy model. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

### FP64 is All You Need: Rethinking Failure Modes in Physics-Informed Neural Networks

**NeurIPS 2025 · Accept (poster)** · Chenhui Xu; Dancheng Liu; Amir Nassereldine; Jinjun Xiong

[Primary source](<https://openreview.net/forum?id=2aotKzkOCm>) · [Venue page](<https://neurips.cc/virtual/2025/poster/120125>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/d274ea8b3c7f526f79ac9ce75ee3c8df-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/d274ea8b3c7f526f79ac9ce75ee3c8df-Abstract-Conference.html>)

**Optimizer relevance:** Diagnoses numerical-precision-induced L-BFGS termination in PINNs and demonstrates improvements from FP64 in the studied PDE tasks.

**Evidence:** Official accepted-paper title and abstract.

### From Condensation to Rank Collapse: A Two-Stage Analysis of Transformer Training Dynamics

**NeurIPS 2025 · Accept (oral)** · Zheng-An Chen; Tao Luo

[Primary source](<https://openreview.net/forum?id=gm5mkiTGOy>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116705>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/3b576711b12ab036b45130fc8eb78504-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/3b576711b12ab036b45130fc8eb78504-Abstract-Conference.html>)

**Training dynamics relevance:** Analyzes early condensation followed by late rank collapse in Transformer attention factors.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Initialization scale; attention-factor dynamics.

**Training qualification:** A linearized gradient-flow model rather than a full nonlinear Transformer training theorem.

**Evidence:** Official accepted-paper title and abstract.

### From Information to Generative Exponent: Learning Rate Induces Phase Transitions in SGD

**NeurIPS 2025 · Accept (poster)** · Konstantinos Tsiolis; Alireza Mousavi-Hosseini; Murat Erdogdu

[Primary source](<https://openreview.net/forum?id=Pf3SVNhAQB>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118200>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/77b7d565f2370979b898d76d7ea27288-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/77b7d565f2370979b898d76d7ea27288-Abstract-Conference.html>)

**Training dynamics relevance:** Shows learning rates can switch single-index learning between information-exponent and generative-exponent regimes.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Learning rate; layer timescales; sample reuse.

**Training qualification:** The sample-complexity transition is proved for structured Gaussian single-index models.

**Evidence:** Official accepted-paper title and abstract.

### Functional Scaling Laws in Kernel Regression: Loss Dynamics and Learning Rate Schedules

**NeurIPS 2025 · Accept (spotlight)** · Binghui Li; Fengling Chen; Zixun Huang; Lean Wang; Lei Wu

[Primary source](<https://openreview.net/forum?id=dpllevHMbc>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116983>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/92abec9d3f278c648dfe99c8b8f35954-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/92abec9d3f278c648dfe99c8b8f35954-Abstract-Conference.html>)

**Optimizer relevance:** Uses an intrinsic-time kernel-regression analysis to model full loss trajectories under learning-rate schedules, with LLM scaling experiments.

**Training dynamics relevance:** Uses an intrinsic-time kernel-regression analysis to model full loss trajectories under learning-rate schedules, with LLM scaling experiments.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Learning-rate schedule; training time; data/compute budget.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Gaussian Approximation and Concentration of Constant Learning-Rate Stochastic Gradient Descent

**NeurIPS 2025 · Accept (poster)** · Ziyang Wei; Jiaqi Li; Zhipeng Lou; Wei Biao Wu

[Primary source](<https://openreview.net/forum?id=aCPFvEg22L>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117289>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/7aae9e3ec211249e05bd07271a6b1441-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/7aae9e3ec211249e05bd07271a6b1441-Abstract-Conference.html>)

**Training dynamics relevance:** Gives Gaussian approximations and concentration results for constant-rate SGD iterates.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Constant learning rate; initialization; stochastic fluctuations.

**Training qualification:** The conclusions require the paper's regularity/noise assumptions, rather than arbitrary nonconvex LLM trajectories.

**Evidence:** Official accepted-paper title and abstract.

### Gemstones: A Model Suite for Multi-Faceted Scaling Laws

**NeurIPS 2025 · Accept (poster)** · Sean McLeish; John Kirchenbauer; David Miller; Siddharth Singh; Abhinav Bhatele; Micah Goldblum; Ashwinee Panda; Tom Goldstein

[Primary source](<https://openreview.net/forum?id=iZk78dZ1Ap>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116550>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/b2b781badeeb49896c4b324c466ec442-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/b2b781badeeb49896c4b324c466ec442-Abstract-Conference.html>)

**Training dynamics relevance:** Gemstones shows scaling prescriptions can depend strongly on architecture, hyperparameter choices and which checkpoints enter the fit.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Width/depth shape; learning rate; cooldown; fit design.

**Training qualification:** A direct warning about experimental-design sensitivity; a fitted exponent is not recipe-independent.

**Evidence:** Official accepted-paper title and abstract.

### Gradient Alignment in Physics-informed Neural Networks: A Second-Order Optimization Perspective

**NeurIPS 2025 · Accept (poster)** · Sifan Wang; Ananyae bhartari; Bowen Li; Paris Perdikaris

[Primary source](<https://openreview.net/forum?id=iweeVl1RHU>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116510>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/f655706547885b8e32ef46f1c067ece2-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** B — Shampoo, structured curvature, and matrix-function computation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/f655706547885b8e32ef46f1c067ece2-Abstract-Conference.html>)

**Optimizer relevance:** Studies gradient conflicts in PINNs and explains the effectiveness of SOAP using a connection to Newton updates.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/PredictiveIntelligenceLab/jaxpi/tree/pirate>). Links extracted from the accepted abstract; code was not tested.

### Gradient Descent as Loss Landscape Navigation: a Normative Framework for Deriving Learning Rules

**NeurIPS 2025 · Accept (poster)** · John Vastola; Samuel J Gershman; Kanaka Rajan

[Primary source](<https://openreview.net/forum?id=oMi4uyNOlL>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116043>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/ad557daf1552a14dd0c26c11d3a72676-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/ad557daf1552a14dd0c26c11d3a72676-Abstract-Conference.html>)

**Optimizer relevance:** Derives learning rules as policies for navigating uncertain loss landscapes, relating gradient descent, momentum, natural gradients and Adam to a common control framework.

**Evidence:** Official accepted-paper title and abstract.

### Gradient Multi-Normalization for Efficient LLM Training

**NeurIPS 2025 · Accept (poster)** · Meyer Scetbon; Chao Ma; Wenbo Gong; Ted Meeds

[Primary source](<https://openreview.net/forum?id=oanhUGY6un>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116024>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/3d6235707dbc91acda049a0ccd641a7e-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/3d6235707dbc91acda049a0ccd641a7e-Abstract-Conference.html>)

**Quantity:** Matrix-gradient normalization without persistent moment states.

**Computational idea:** SinkGD alternates normalization constraints on gradients instead of maintaining Adam-style statistics.

**Scope:** Deep learning. **Qualification:** Multi-normalization changes the update geometry; it is not generally identical to a matrix inverse root or polar factor.

**Optimizer relevance:** SinkGD replaces stored adaptive statistics with iterative gradient multi-normalization, using matrix structure for language-model optimization.

**Evidence:** Official accepted-paper title and abstract.

### GradMetaNet: An Equivariant Architecture for Learning on Gradients

**NeurIPS 2025 · Accept (poster)** · Yoav Gelberg; Yam Eitan; Aviv Navon; Aviv Shamsian; Theo Putterman; Michael Bronstein; Haggai Maron

[Primary source](<https://openreview.net/forum?id=Gvex75bPMI>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118925>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/e2d228a7479823e1fb12918f08f8955f-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/e2d228a7479823e1fb12918f08f8955f-Abstract-Conference.html>)

**Quantity:** Compact gradient representations for learned optimization.

**Computational idea:** GradMetaNet uses equivariant processing of gradient sets and rank-one representations to learn updates that exploit curvature structure.

**Scope:** Deep learning. **Qualification:** The update is learned from training tasks rather than computed as an exact inverse-curvature product.

**Optimizer relevance:** GradMetaNet learns equivariant gradient transformations using compact representations of per-example gradient structure.

**Evidence:** Official accepted-paper title and abstract.

### GSPN-2: Efficient Parallel Sequence Modeling

**NeurIPS 2025 · Accept (poster)** · Hongjun Wang; yitong jiang; Collin McCarthy; David Wehr; Hanrong Ye; Xinhao Li; Ka Chun Cheung; Wonmin Byeon; Jinwei Gu; Ke Chen; Kai Han; Hongxu Yin; Pavlo Molchanov; Jan Kautz; Sifei Liu

[Primary source](<https://openreview.net/forum?id=9yG7LGYfHS>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119496>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/550ab405d0addd3de5b70e57b44878df-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/550ab405d0addd3de5b70e57b44878df-Abstract-Conference.html>)

**Quantity:** Two-dimensional spatial propagation.

**Computational idea:** GSPN-2 combines structured shared propagation matrices with a fused GPU kernel and shared-memory staging.

**Scope:** Deep learning. **Qualification:** A jointly redesigned model and implementation; runtime results cannot be interpreted as exact softmax-attention acceleration.

**Evidence:** Official accepted-paper title and abstract.

### Hankel Singular Value Regularization for Highly Compressible State Space Models

**NeurIPS 2025 · Accept (poster)** · Paul Schwerdtner; Jules Berman; Benjamin Peherstorfer

[Primary source](<https://openreview.net/forum?id=WkztaHpjt1>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117569>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/c3070c3388552a08a3326f0d28dc2af9-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/c3070c3388552a08a3326f0d28dc2af9-Abstract-Conference.html>)

**Quantity:** Hankel singular values during state-space-model training.

**Computational idea:** Exploits block-diagonal system structure to compute Hankel singular values efficiently for compression regularization.

**Scope:** Deep learning. **Qualification:** The computation relies on the particular SSM parameterization; compression quality remains task-dependent.

**Evidence:** Official accepted-paper title and abstract.

### Harmony in Divergence: Towards Fast, Accurate, and Memory-efficient Zeroth-order LLM Fine-tuning

**NeurIPS 2025 · Accept (poster)** · Qitao Tan; Jun Liu; Zheng Zhan; Caiwen Ding; Yanzhi Wang; Xiaolong Ma; Jaewoo Lee; Jin Lu; Geng Yuan

[Primary source](<https://openreview.net/forum?id=Rx6m16By6l>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117979>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/ffd4f5a2ea6b93e9bf5af9264d568cf2-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/ffd4f5a2ea6b93e9bf5af9264d568cf2-Abstract-Conference.html>)

**Optimizer relevance:** DiZO scales zeroth-order updates layer by layer using divergence from the pretrained model.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/Skilteee/DiZO>). Links extracted from the accepted abstract; code was not tested.

### How to Scale Second-Order Optimization

**NeurIPS 2025 · Accept (poster)** · Charlie Chen; Shikai Qiu; Hoang Phan; Qi Lei; Andrew Wilson

[Primary source](<https://openreview.net/forum?id=Ei6IsmxYrb>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119109>) · [PDF](<https://openreview.net/pdf?id=Ei6IsmxYrb>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Studies width/depth transfer of hyperparameters for Shampoo, SOAP and Muon, including blocking, grafting and weight decay in language-model training.

**Training dynamics relevance:** Studies width/depth transfer of hyperparameters for Shampoo, SOAP and Muon, including blocking, grafting and weight decay in language-model training.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Width/depth; weight decay; Shampoo/SOAP/Muon; grafting.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Implicit Bias of Spectral Descent and Muon on Multiclass Separable Data

**NeurIPS 2025 · Accept (spotlight)** · Chen Fan; Mark Schmidt; Christos Thrampoulidis

[Primary source](<https://openreview.net/forum?id=Zn2ajV1kTQ>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117324>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/386432c7534eec9a1cd7cbeea90d7e9f-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/386432c7534eec9a1cd7cbeea90d7e9f-Abstract-Conference.html>)

**Optimizer relevance:** Characterizes implicit bias of spectral descent and Muon-like updates through matrix maximum-margin solutions in linear classification.

**Training dynamics relevance:** Characterizes implicit bias of spectral descent and Muon-like updates through matrix maximum-margin solutions in linear classification.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Spectral descent; Muon; max-margin bias.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Improved Scaling Laws in Linear Regression via Data Reuse

**NeurIPS 2025 · Accept (poster)** · Licong Lin; Jingfeng Wu; Peter Bartlett

[Primary source](<https://openreview.net/forum?id=jeen4x145W>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116442>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/82b76a72a9df183498cf0be3df6eef71-Paper-Conference.pdf>)

**Topics:** Training dynamics.

**Categories:** T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/82b76a72a9df183498cf0be3df6eef71-Abstract-Conference.html>)

**Training dynamics relevance:** Shows multiple SGD passes can improve data-constrained scaling in sketched linear regression.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Epochs/data reuse; model dimension; spectral decay.

**Training qualification:** Power-law covariance and target alignment assumptions qualify the improved exponents.

**Evidence:** Official accepted-paper title and abstract.

### Improving Energy Natural Gradient Descent through Woodbury, Momentum, and Randomization

**NeurIPS 2025 · Accept (poster)** · Andrés Guzmán-Cordero; Felix Dangel; Gil Goldshlager; Marius Zeinhofer

[Primary source](<https://openreview.net/forum?id=5YMZfufpfY>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119855>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/a5809a25c65040fd43e146126b45b150-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/a5809a25c65040fd43e146126b45b150-Abstract-Conference.html>)

**Quantity:** Energy-natural-gradient linear solves in PINNs.

**Computational idea:** Uses Woodbury identities to reduce solve dimensions, then adds momentum and randomized approximations for larger problems.

**Scope:** Scientific computing. **Qualification:** Woodbury algebra can be exact, while randomization is approximate; reported benefits are strongest in particular PDE regimes.

**Optimizer relevance:** Improves energy natural gradient descent for PINNs through a Woodbury reformulation, SPRING-style momentum and randomized approximations. Specialized scientific training, not an LLM benchmark.

**Evidence:** Official accepted-paper title and abstract.

### In Search of Adam’s Secret Sauce

**NeurIPS 2025 · Accept (oral)** · Antonio Orvieto; Robert Gower

[Primary source](<https://openreview.net/forum?id=CH72XyZs4y>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119297>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/5bd9aa206d782e4e1f7ab5d177a10828-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/5bd9aa206d782e4e1f7ab5d177a10828-Abstract-Conference.html>)

**Training dynamics relevance:** Compares carefully tuned Adam simplifications and explains why equal momentum parameters retain much of Adam's performance.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Adam beta1/beta2; clipping; learning rate; optimizer choice.

**Training qualification:** The equal-beta result is empirical over tested settings; the associated statistical interpretation has specified assumptions.

**Evidence:** Official accepted-paper title and abstract.

### Infinite-Width Limit of a Single Attention Layer: Analysis via Tensor Programs

**NeurIPS 2025 · Accept (poster)** · Mana Sakai; Ryo Karakida; Masaaki Imaizumi

[Primary source](<https://openreview.net/forum?id=gZzLjIYzH1>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116729>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/33201f38001dd381aba2c462051449ba-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/33201f38001dd381aba2c462051449ba-Abstract-Conference.html>)

**Training dynamics relevance:** Derives a non-Gaussian infinite-width limit for finite-head attention under standard score scaling.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Attention width; head count; score scaling.

**Training qualification:** A single-layer initialization/limit result, not a full trained Transformer dynamics theorem.

**Evidence:** Official accepted-paper title and abstract.

### Irrational Complex Rotations Empower Low-bit Optimizers

**NeurIPS 2025 · Accept (poster)** · Zhen Tian; Xin Zhao; Ji-Rong Wen

[Primary source](<https://openreview.net/forum?id=fSFgcEVDT2>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116843>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/f943a0abbfe9fb6e46a01411fc7372c9-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers; X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/f943a0abbfe9fb6e46a01411fc7372c9-Abstract-Conference.html>)

**Quantity:** Low-bit optimizer-state encoding and reconstruction.

**Computational idea:** pi-Quant uses irrational complex rotations to represent optimizer states compactly.

**Scope:** Deep learning. **Qualification:** Lossy numerical encoding; reported quality and memory trade-offs depend on bit width and training setup.

**Optimizer relevance:** pi-Quant compresses optimizer states using low-bit encodings based on irrational complex rotations.

**Evidence:** Official accepted-paper title and abstract.

### Is Grokking a Computational Glass Relaxation?

**NeurIPS 2025 · Accept (spotlight)** · Xiaotian Zhang; Yue Shang; Entao Yang; Ge Zhang

[Primary source](<https://openreview.net/forum?id=Tk5nQnTGmP>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117824>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/92f67b9047fa7a43d7506054b5f0ec6a-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/92f67b9047fa7a43d7506054b5f0ec6a-Abstract-Conference.html>)

**Training dynamics relevance:** Interprets grokking as nonequilibrium glass relaxation and studies counterexamples to simple weight-norm explanations.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Training time; entropy; optimizer dynamics.

**Training qualification:** The physical analogy and optimizer demonstration use controlled arithmetic tasks.

**Evidence:** Official accepted-paper title and abstract.

### KOALA++: Efficient Kalman-Based Optimization with Gradient-Covariance Products

**NeurIPS 2025 · Accept (poster)** · Zixuan XIa; Aram Davtyan; Paolo Favaro

[Primary source](<https://openreview.net/forum?id=Pvoy6fWaRJ>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118176>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/323acd89d43df534db8d39da4c67a4b1-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/323acd89d43df534db8d39da4c67a4b1-Abstract-Conference.html>)

**Quantity:** Gradient-covariance operations for Kalman optimizer updates.

**Computational idea:** KOALA++ uses compact structured covariance representations to avoid dense covariance storage and inverse computation.

**Scope:** Deep learning. **Qualification:** The covariance model is structured and approximate; uncertainty estimates are not the exact loss Hessian.

**Optimizer relevance:** KOALA++ builds structured Kalman-filter updates from gradient uncertainty, with compact covariance operations for scalable neural-network training.

**Evidence:** Official accepted-paper title and abstract.

### L$^2$M: Mutual Information Scaling Law for Long-Context Language Modeling

**NeurIPS 2025 · Accept (poster)** · Zhuo Chen; Oriol Comas; Zhuotao Jin; Di Luo; Marin Soljacic

[Primary source](<https://openreview.net/forum?id=s3maemwE5M>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115721>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/c9da56addea9c977cf4ba873e1da979d-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/c9da56addea9c977cf4ba873e1da979d-Abstract-Conference.html>)

**Training dynamics relevance:** Relates long-context model capacity to bipartite mutual-information scaling in language.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Context length; history-state capacity; architecture.

**Training qualification:** A capacity requirement rather than an optimized learning-rate schedule or convergence guarantee.

**Evidence:** Official accepted-paper title and abstract.

### Large Stepsizes Accelerate Gradient Descent for Regularized Logistic Regression

**NeurIPS 2025 · Accept (poster)** · Jingfeng Wu; Pierre Marion; Peter Bartlett

[Primary source](<https://openreview.net/forum?id=w22e5MrS4X>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115359>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/96b8167534ef3cc30c230bbeb55a524d-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/96b8167534ef3cc30c230bbeb55a524d-Abstract-Conference.html>)

**Training dynamics relevance:** Shows nonmonotone large-step GD can accelerate regularized logistic regression.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Large constant step size; l2 regularization.

**Training qualification:** The guarantees require separable data and the stated loss structure.

**Evidence:** Official accepted-paper title and abstract.

### Learning Grouped Lattice Vector Quantizers for Low-Bit LLM Compression

**NeurIPS 2025 · Accept (poster)** · Xi Zhang; Xiaolin Wu; Jiamang Wang; Weisi Lin

[Primary source](<https://openreview.net/forum?id=Ynwl0V1YH0>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117396>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/a0183ad2088503d707669e1d222bc8c4-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/a0183ad2088503d707669e1d222bc8c4-Abstract-Conference.html>)

**Quantity:** Low-bit lattice codebooks and weight reconstruction.

**Computational idea:** GLVQ learns generation matrices, uses Babai rounding for approximate nearest-lattice search, and decodes with matrix-vector products.

**Scope:** Deep learning. **Qualification:** Babai rounding approximates nearest-lattice search and quantization is lossy.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/xzhang9308/GLVQ.>). Links extracted from the accepted abstract; code was not tested.

### Learning in Compact Spaces with Approximately Normalized Transformer

**NeurIPS 2025 · Accept (poster)** · Jörg Franke; Urs Spiegelhalter; Marianna Nezhurina; Jenia Jitsev; Frank Hutter; Michael Hefenbrock

[Primary source](<https://openreview.net/forum?id=dH8mKmvADv>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117015>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/6dcdf117a037f459e53205d3f3af4a77-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/6dcdf117a037f459e53205d3f3af4a77-Abstract-Conference.html>)

**Training dynamics relevance:** Approximately normalized Transformers study a training recipe that reduces normalization overhead and removes some tuning knobs.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Norm constraints; warm-up; weight decay; batch size.

**Training qualification:** The claimed removal of warm-up/decay is architecture-specific, not a prescription for ordinary Transformers.

**Evidence:** Official accepted-paper title and abstract.

### Learning quadratic neural networks in high dimensions: SGD dynamics and scaling laws

**NeurIPS 2025 · Accept (poster)** · Gerard Ben Arous; Murat Erdogdu; Nuri Mert Vural; Denny Wu

[Primary source](<https://openreview.net/forum?id=m3Sz3tFxIV>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116241>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/d7ce06e9293c3d8e6cb3f80b4157f875-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/d7ce06e9293c3d8e6cb3f80b4157f875-Abstract-Conference.html>)

**Training dynamics relevance:** Derives learning dynamics and risk scaling in high-dimensional quadratic neural networks.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Width; SGD steps; samples; signal spectrum.

**Training qualification:** The exact dynamics rely on orthogonal signals and structured Gaussian data.

**Evidence:** Official accepted-paper title and abstract.

### Learning Sparse Approximate Inverse Preconditioners for Conjugate Gradient Solvers on GPUs

**NeurIPS 2025 · Accept (poster)** · Zhehao Li; Zhehao Li; Kangbo Lyu; Yixuan Li; Tao Du; Ligang Liu

[Primary source](<https://openreview.net/forum?id=jtMDzggo6M>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116429>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/23fcc63005ac1a6e460ec4e209d17607-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/23fcc63005ac1a6e460ec4e209d17607-Abstract-Conference.html>)

**Quantity:** GPU-friendly preconditioning for conjugate gradients.

**Computational idea:** A GNN predicts sparse approximate inverse preconditioners, replacing triangular solves with matrix-vector products.

**Scope:** Scientific computing. **Qualification:** The matrix must satisfy the solver assumptions; generalization and speed depend on sparsity and problem distribution.

**Evidence:** Official accepted-paper title and abstract.

### Least squares variational inference

**NeurIPS 2025 · Accept (poster)** · Yvann Le Fay; Nicolas Chopin; Simon Barthelmé

[Primary source](<https://openreview.net/forum?id=Gvh6sU0uUt>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118924>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/d51ceadaf09a4699f18986702df24987-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/d51ceadaf09a4699f18986702df24987-Abstract-Conference.html>)

**Quantity:** Natural-gradient-like variational inference updates.

**Computational idea:** Replaces explicit large Fisher inverses with Monte Carlo ordinary least-squares regression of log-target quantities.

**Scope:** General ML. **Qualification:** Gradient-free does not mean exact: Monte Carlo regression produces stochastic, generally biased natural-gradient estimates.

**Optimizer relevance:** Least-squares variational inference recasts natural-gradient-like inference updates as Monte Carlo regression without constructing a large Fisher inverse.

**Evidence:** Official accepted-paper title and abstract.

### Linear Attention for Efficient Bidirectional Sequence Modeling

**NeurIPS 2025 · Accept (poster)** · Arshia Afzal; Elias Abad Rocamora; Leyla Candogan; Pol Puigdemont; Francesco Tonin; Yongtao Wu; Mahsa Shoaran; Volkan Cevher

[Primary source](<https://openreview.net/forum?id=Ar62cqTduE>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119431>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/71845d09f05d40d030fa3cde8b5dcd13-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/71845d09f05d40d030fa3cde8b5dcd13-Abstract-Conference.html>)

**Quantity:** Bidirectional linear-attention sequence operators.

**Computational idea:** LION gives equivalent full-matrix, bidirectional recurrent and chunkwise-parallel forms.

**Scope:** Deep learning. **Qualification:** Equivalence is within the supported linear-attention family, not with an arbitrary softmax Transformer.

**Evidence:** Official accepted-paper title and abstract.

### Local Curvature Descent: Squeezing More Curvature out of Standard and Polyak Gradient Descent

**NeurIPS 2025 · Accept (poster)** · Peter Richtarik; Simone Maria Giancola; Dymitr Lubczyk; Robin Yadav

[Primary source](<https://openreview.net/forum?id=EqWZ1yVRfN>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119093>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/107aaa54d9481515e981e332e2e115b1-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/107aaa54d9481515e981e332e2e115b1-Abstract-Conference.html>)

**Optimizer relevance:** Local Curvature Descent uses matrix-valued local curvature models for convex optimization; useful foundations rather than a demonstrated general LLM optimizer.

**Evidence:** Official accepted-paper title and abstract.

### Memory-Efficient Training with In-Place FFT Implementation

**NeurIPS 2025 · Accept (poster)** · XINYU DING; Bangtian Liu; Siyu Liao; Zhongfeng Wang

[Primary source](<https://openreview.net/forum?id=oWnAlRn3X1>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116030>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/b07091c16719ad3990e3d1ccee6641f1-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/b07091c16719ad3990e3d1ccee6641f1-Abstract-Conference.html>)

**Quantity:** FFT transforms and frequency-domain parameter updates.

**Computational idea:** A real-domain in-place FFT encoding preserves input/output dimension and reduces intermediate storage.

**Scope:** Deep learning. **Qualification:** Memory claims concern the proposed representation and implementation, not every FFT library or training workload.

**Evidence:** Official accepted-paper title and abstract.

### MGUP: A Momentum-Gradient Alignment Update Policy for Stochastic Optimization

**NeurIPS 2025 · Accept (spotlight)** · Da Chang; Ganzhao Yuan

[Primary source](<https://openreview.net/forum?id=TDFSKAspoQ>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117868>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1d769a56c0fd47b03cfa491bdc3be9ba-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/1d769a56c0fd47b03cfa491bdc3be9ba-Abstract-Conference.html>)

**Optimizer relevance:** MGUP uses gradient-momentum alignment to choose update magnitudes, with general neural-network optimization experiments.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/MaeChd/MGUP.>). Links extracted from the accepted abstract; code was not tested.

### MISA: Memory-Efficient LLMs Optimization with Module-wise Importance Sampling

**NeurIPS 2025 · Accept (poster)** · Yuxi Liu; Renjia Deng; Yutong He; xue wang; Tao Yao; Kun Yuan

[Primary source](<https://openreview.net/forum?id=yISJGSdzdd>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115158>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/73efab19ebde03ff0958f4f155483f57-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/73efab19ebde03ff0958f4f155483f57-Abstract-Conference.html>)

**Optimizer relevance:** MISA allocates memory-efficient updates through module-wise importance sampling for language-model training.

**Evidence:** Official accepted-paper title and abstract.

### Natural Gradient VI: Guarantees for Non-Conjugate Models

**NeurIPS 2025 · Accept (poster)** · Fangyuan Sun; Ilyas Fatkhullin; Niao He

[Primary source](<https://openreview.net/forum?id=Cfd5S9108a>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119276>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/9a07bb7288caaea2ecc4c367188bc6db-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/9a07bb7288caaea2ecc4c367188bc6db-Abstract-Conference.html>)

**Optimizer relevance:** Proves convergence results for mean-field natural-gradient variational inference in non-conjugate models, including projected modifications and conditional hidden convexity.

**Evidence:** Official accepted-paper title and abstract.

### New Perspectives on the Polyak Stepsize: Surrogate Functions and Negative Results

**NeurIPS 2025 · Accept (poster)** · Francesco Orabona; Ryan D&#x27;Orazio

[Primary source](<https://openreview.net/forum?id=7GwcxPIkip>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119719>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/e45879046fd900c2536e419e361c94c0-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/e45879046fd900c2536e419e361c94c0-Abstract-Conference.html>)

**Training dynamics relevance:** Unifies Polyak rules as descent on surrogate losses and establishes concrete non-convergence cases.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Polyak step-size variants; local curvature.

**Training qualification:** Variant-specific assumptions matter; adaptive step-size rules are not universally safe.

**Evidence:** Official accepted-paper title and abstract.

### Nonlinearly Preconditioned Gradient Methods: Momentum and Stochastic Analysis

**NeurIPS 2025 · Accept (poster)** · Konstantinos Oikonomidis; Jan Quan; Panagiotis Patrinos

[Primary source](<https://openreview.net/forum?id=xGmS1i0pDq>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115256>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/3768bb822e5c024b408dd930c4aafe67-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/3768bb822e5c024b408dd930c4aafe67-Abstract-Conference.html>)

**Optimizer relevance:** Studies momentum with nonlinear gradient preconditioning, including clipping-type transformations under generalized smoothness.

**Evidence:** Official accepted-paper title and abstract.

### On the $O(\frac{\sqrt{d}}{K^{1/4}})$ Convergence Rate of AdamW Measured by $\ell_1$ Norm

**NeurIPS 2025 · Accept (poster)** · Huan Li; Yiming Dong; Zhouchen Lin

[Primary source](<https://openreview.net/forum?id=eYKz5M7Aws>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116906>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/bf9b7879998f32982db708136dcb174b-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/bf9b7879998f32982db708136dcb174b-Abstract-Conference.html>)

**Optimizer relevance:** Studies convergence behavior of AdamW through an l1-based perspective; an optimizer-theory entry rather than a new preconditioner.

**Evidence:** Official accepted-paper title and abstract.

### On the Optimal Construction of Unbiased Gradient Estimators for Zeroth-Order Optimization

**NeurIPS 2025 · Accept (spotlight)** · Shaocong Ma; Heng Huang

[Primary source](<https://openreview.net/forum?id=rVT1GK60Nt>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115772>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/7f7eade8b69c853e3137cab80df3ccf6-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/7f7eade8b69c853e3137cab80df3ccf6-Abstract-Conference.html>)

**Quantity:** Unbiased function-evaluation gradient estimators.

**Computational idea:** Randomizes a telescoping expansion of directional derivatives to remove finite-difference bias.

**Scope:** Deep learning. **Qualification:** Unbiasedness and variance bounds require stated smoothness and sampling conditions; individual estimates remain noisy.

**Optimizer relevance:** Constructs unbiased zeroth-order gradient estimators through randomized telescoping series, with theory and language-model fine-tuning experiments.

**Evidence:** Official accepted-paper title and abstract.

### On the Surprising Effectiveness of Large Learning Rates under Standard Width Scaling

**NeurIPS 2025 · Accept (spotlight)** · Moritz Haas; Sebastian Bordt; Ulrike Luxburg; Leena Chennuru Vankadara

[Primary source](<https://openreview.net/forum?id=hTxnm6H93P>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116648>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/3eec5006051d9544e717067de3220198-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/3eec5006051d9544e717067de3220198-Abstract-Conference.html>)

**Optimizer relevance:** Studies large learning rates and width scaling, including feature learning during controlled loss growth under cross-entropy.

**Training dynamics relevance:** Studies large learning rates and width scaling, including feature learning during controlled loss growth under cross-entropy.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Large learning rate; standard width scaling; feature learning.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### ParetoQ: Improving Scaling Laws in Extremely Low-bit LLM Quantization

**NeurIPS 2025 · Accept (poster)** · Zechun Liu; Changsheng Zhao; Hanxian Huang; Sijia Chen; Jing Zhang; Jiawei Zhao; Scott Roy; Lisa Jin; Yunyang Xiong; Yangyang Shi; Lin Xiao; Yuandong Tian; Bilge Soran; Raghuraman Krishnamoorthi; Tijmen Blankevoort; Vikas Chandra

[Primary source](<https://openreview.net/forum?id=PMSNd8xTHp>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118224>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/83b17fb3369b1effa97ca5409526b02e-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/83b17fb3369b1effa97ca5409526b02e-Abstract-Conference.html>)

**Training dynamics relevance:** ParetoQ compares low-bit regimes and identifies qualitatively different representation changes below three bits.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Quantization bit width; training scheme; model size.

**Training qualification:** Accuracy/size trade-offs are implementation- and hardware-dependent; one bit width is not universally optimal.

**Evidence:** Official accepted-paper title and abstract.

### Partial Correlation Network Estimation by Semismooth Newton Methods

**NeurIPS 2025 · Accept (poster)** · DongWon Kim; Sungdong Lee; Joong-Ho (Johann) Won

[Primary source](<https://openreview.net/forum?id=L3UfIfNxb7>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118580>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/f003e17e2fe9aac7667a1b4407ccef46-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/f003e17e2fe9aac7667a1b4407ccef46-Abstract-Conference.html>)

**Quantity:** Sparse partial-correlation estimation updates.

**Computational idea:** Semismooth Newton methods reduce updates to small linear systems or complementarity subproblems.

**Scope:** General ML. **Qualification:** Local quadratic convergence requires the specified conditions; a graphical-model solver rather than an LLM optimizer.

**Evidence:** Official accepted-paper title and abstract.

### PaZO: Preconditioned Accelerated Zeroth-Order Optimization for Fine-Tuning LLMs

**NeurIPS 2025 · Accept (poster)** · Hanzhen Zhao; Ding Shihong; Cong Fang; Zhouchen Lin

[Primary source](<https://openreview.net/forum?id=b2IU6QOOfo>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117216>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/a14193e9d9fb0b03af0b717de1cac8ac-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/a14193e9d9fb0b03af0b717de1cac8ac-Abstract-Conference.html>)

**Quantity:** Diagonal curvature estimates for zeroth-order updates.

**Computational idea:** PaZO estimates diagonal Hessian information and smooths it to precondition function-evaluation-based training.

**Scope:** Deep learning. **Qualification:** A noisy diagonal estimate, not a full Hessian or exact natural gradient.

**Optimizer relevance:** PaZO uses estimated diagonal curvature and momentum to precondition zeroth-order language-model fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

### Perturbation Bounds for Low-Rank Inverse Approximations under Noise

**NeurIPS 2025 · Accept (poster)** · Phuc Tran; Nisheeth K. Vishnoi

[Primary source](<https://openreview.net/forum?id=bPNzBXl1n7>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117183>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/953d276d037e701fcd97dbb34ebb2394-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X1 — Matrix functions, roots and matrix geometry.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/953d276d037e701fcd97dbb34ebb2394-Abstract-Conference.html>)

**Quantity:** Noise sensitivity of truncated inverse approximations.

**Computational idea:** Contour-integral analysis of reciprocal spectral functions gives refined bounds for low-rank inverse perturbations.

**Scope:** Theory / foundations. **Qualification:** A theory contribution, not a faster inverse algorithm; spectral gaps and noise alignment qualify the estimates.

**Evidence:** Official accepted-paper title and abstract.

### pLSTM: parallelizable Linear Source Transition Mark networks

**NeurIPS 2025 · Accept (poster)** · Korbinian Pöppel; Richard Freinschlag; Thomas Schmied; Wei Lin; Sepp Hochreiter

[Primary source](<https://openreview.net/forum?id=2sa13vyCn0>) · [Venue page](<https://neurips.cc/virtual/2025/poster/120092>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/0d5c9d43eb13c98db21eeb92c7c986d8-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/0d5c9d43eb13c98db21eeb92c7c986d8-Abstract-Conference.html>)

**Quantity:** Parallel recurrent computation on grids and DAGs.

**Computational idea:** pLSTM extends scan-like algebra to DAGs, with logarithmic-depth grid implementations using tensor operations.

**Scope:** Deep learning. **Qualification:** Applies to the proposed structured recurrence, not arbitrary nonlinear recurrent networks.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/ml-jku/plstm_experiments.>). Links extracted from the accepted abstract; code was not tested.

### PoLAR: Polar-Decomposed Low-Rank Adapter Representation

**NeurIPS 2025 · Accept (poster)** · Kai Lion; Liang Zhang; Bingcong Li; Niao He

[Primary source](<https://openreview.net/forum?id=jDxFD45kkc>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116485>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/db79b6c50430a52fbab9d63efb8433ca-Paper-Conference.pdf>)

**Topics:** Manifold; Matrix computation; Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; M2 — Manifold-based LLM training and low-rank adaptation; X1 — Matrix functions, roots and matrix geometry.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/db79b6c50430a52fbab9d63efb8433ca-Abstract-Conference.html>)

**Quantity:** Geometrically separated low-rank directions and scales.

**Computational idea:** PoLAR uses a polar-inspired three-factor representation and Riemannian updates for orthonormal factors.

**Scope:** Deep learning. **Qualification:** A fine-tuning parameterization; it is not a new general-purpose polar-decomposition solver.

**Optimizer relevance:** PoLAR uses two orthonormal factors and a scale factor with Riemannian optimization for parameter-efficient fine-tuning.

**Manifold relevance:** PoLAR uses a polar-inspired low-rank parameterization and Riemannian factor updates for fine-tuning.

**Geometry:** Two Stiefel factors with a separate scale. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### Power Lines: Scaling laws for weight decay and batch size in LLM pre-training

**NeurIPS 2025 · Accept (poster)** · Shane Bergsma; Nolan Dey; Gurpreet Gosal; Gavia Gray; Daria Soboleva; Joel Hestness

[Primary source](<https://openreview.net/forum?id=bFXbLQzRoZ>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117191>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/b5f78a17a94da3e34c935515d1b6adae-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/b5f78a17a94da3e34c935515d1b6adae-Abstract-Conference.html>)

**Optimizer relevance:** Analyzes joint batch-size and weight-decay scaling for language-model training; relevant to transferring optimizer settings across compute regimes.

**Training dynamics relevance:** Analyzes joint batch-size and weight-decay scaling for language-model training; relevant to transferring optimizer settings across compute regimes.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Batch size; weight decay; model size.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Predictable Scale (Part II) --- Farseer: A Refined Scaling Law in LLMs

**NeurIPS 2025 · Accept (spotlight)** · Houyi Li; Wenzhen Zheng; Qiufeng Wang; Zhenyu Ding; Haoying Wang; Zili Wang; Shijie Xuyang; Ning DING; Shuigeng Zhou; Xiangyu Zhang; Daxin Jiang

[Primary source](<https://openreview.net/forum?id=2Gnp8sdwVe>) · [Venue page](<https://neurips.cc/virtual/2025/poster/120156>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/ae9f1d3b89a81fcb1c45b4fc1afbd4fe-Paper-Conference.pdf>)

**Topics:** Training dynamics.

**Categories:** T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/ae9f1d3b89a81fcb1c45b4fc1afbd4fe-Abstract-Conference.html>)

**Training dynamics relevance:** Farseer fits a refined loss surface to improve evaluation of training strategies and compute allocation across scales.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Parameters; tokens; small-to-large extrapolation.

**Training qualification:** Prediction quality depends on the fitted model families and design of the scaling experiments.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/Farseer-Scaling-Law/Farseer>). Links extracted from the accepted abstract; code was not tested.

### PROFIT: A Specialized Optimizer for Deep Fine Tuning

**NeurIPS 2025 · Accept (poster)** · Anirudh Chakravarthy; Shuai Zheng; Xin Huang; Sachithra Hemachandra; Xiao Zhang; Yuning Chai; Zhao Chen

[Primary source](<https://openreview.net/forum?id=Yyb1Gi8e36>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117387>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/130534d1b9f0a54bb59b529589123cb4-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/130534d1b9f0a54bb59b529589123cb4-Abstract-Conference.html>)

**Optimizer relevance:** PROFIT uses temporal gradient orthogonalization to regularize fine-tuning and mitigate forgetting.

**Evidence:** Official accepted-paper title and abstract.

### Provable Meta-Learning with Low-Rank Adaptations

**NeurIPS 2025 · Accept (poster)** · Jacob Block; Sundararajan Srinivasan; Liam Collins; Aryan Mokhtari; Sanjay Shakkottai

[Primary source](<https://openreview.net/forum?id=QUN6uidabr>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118126>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/369d5d79908d1f7d4b4ac42e68037a13-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/369d5d79908d1f7d4b4ac42e68037a13-Abstract-Conference.html>)

**Optimizer relevance:** Provides theory and experiments for meta-learning a model that can adapt effectively through low-rank updates.

**Evidence:** Official accepted-paper title and abstract.

### PseuZO: Pseudo-Zeroth-Order Algorithm for Training Deep Neural Networks

**NeurIPS 2025 · Accept (poster)** · Pengyun Yue; Xuanlin Yang; Mingqing Xiao; Zhouchen Lin

[Primary source](<https://openreview.net/forum?id=tM4cHBD7kD>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115604>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/9a9afa70eead1805f00e3a0df2a41157-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/9a9afa70eead1805f00e3a0df2a41157-Abstract-Conference.html>)

**Quantity:** Model-output Jacobian estimates for zeroth-order fine-tuning.

**Computational idea:** PseuZO separates the output Jacobian from the loss derivative and reuses stochastic estimates through temporal averaging.

**Scope:** Deep learning. **Qualification:** The Jacobian is estimated from function queries; bias and variance depend on the estimator and reuse scheme.

**Optimizer relevance:** PseuZO separates model-output Jacobian estimation from the outer loss gradient and reuses estimates for zeroth-order fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/YangBigMn/PseuZO.>). Links extracted from the accepted abstract; code was not tested.

### Purifying Shampoo: Investigating Shampoo's Heuristics by Decomposing its Preconditioner

**NeurIPS 2025 · Accept (spotlight)** · Runa Eschenhagen; Aaron Defazio; Tsung-Hsien Lee; Richard Turner; Hao-Jun Shi

[Primary source](<https://openreview.net/forum?id=kePsKwxvaV>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116361>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/f14f4eda29a74c02c803699a09529bb9-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer; Training dynamics.

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

### Q3R: Quadratic Reweighted Rank Regularizer for Effective Low-Rank Training

**NeurIPS 2025 · Accept (poster)** · Ipsita Ghosh; Ethan Nguyen; Christian Kümmerle

[Primary source](<https://openreview.net/forum?id=ZtzWvNKOCr>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117315>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/c1e6da1f619fe4b2e00cb5ca98392ec4-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/c1e6da1f619fe4b2e00cb5ca98392ec4-Abstract-Conference.html>)

**Quantity:** Low-rank-inducing regularization during training.

**Computational idea:** Q3R majorizes a smoothed log-determinant rank surrogate with iteratively reweighted quadratic penalties.

**Scope:** Deep learning. **Qualification:** The surrogate encourages low rank; truncation and approximation quality require empirical validation.

**Optimizer relevance:** Q3R uses iteratively reweighted quadratic regularization of a smoothed log-determinant rank surrogate for low-rank training and fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

### QSVD: Efficient Low-rank Approximation for Unified Query-Key-Value Weight Compression in Low-Precision Vision-Language Models

**NeurIPS 2025 · Accept (spotlight)** · Yutong Wang; Haiyu Wang; Sai Qian Zhang

[Primary source](<https://openreview.net/forum?id=sEFDhxF1mG>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115710>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/028ef7e68a5ea25fc26cd6abf3a5c147-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/028ef7e68a5ea25fc26cd6abf3a5c147-Abstract-Conference.html>)

**Quantity:** Joint query-key-value weight compression.

**Computational idea:** QSVD factorizes joint Q/K/V weights with adaptive rank allocation and combines this with quantization.

**Scope:** Deep learning. **Qualification:** Both low-rank truncation and quantization are lossy; quality is evaluated for vision-language models.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/SAI-Lab-NYU/QSVD.>). Links extracted from the accepted abstract; code was not tested.

### RefLoRA: Refactored Low-Rank Adaptation for Efficient Fine-Tuning of Large Models

**NeurIPS 2025 · Accept (poster)** · Yilang Zhang; Bingcong Li; Georgios Giannakis

[Primary source](<https://openreview.net/forum?id=zefDc9oi5T>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115034>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/85c1ee0b3cdf49b84f14b163b01f2711-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/85c1ee0b3cdf49b84f14b163b01f2711-Abstract-Conference.html>)

**Optimizer relevance:** RefLoRA refactorizes updates to optimize a loss upper bound and balance low-rank factors during fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

### Revisiting Glorot Initialization for Long-Range Linear Recurrences

**NeurIPS 2025 · Accept (poster)** · Noga Bar; Mariia Seleznova; ‪Yotam Alexander‬‏; Gitta Kutyniok; Raja Giryes

[Primary source](<https://openreview.net/forum?id=bd8kppxyB3>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117163>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/4fbc7f29151b7c1f0e1f1e5c51c4f5b3-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/4fbc7f29151b7c1f0e1f1e5c51c4f5b3-Abstract-Conference.html>)

**Training dynamics relevance:** Shows finite-width spectral-radius deviations can destabilize long recurrences and proposes dimension-aware rescaling.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Recurrent width; sequence length; initialization scale.

**Training qualification:** The formal setting is linear recurrence; sequence length and width must be considered jointly.

**Evidence:** Official accepted-paper title and abstract.

### Revisiting Residual Connections: Orthogonal Updates for Stable and Efficient Deep Networks

**NeurIPS 2025 · Accept (poster)** · Giyeong Oh; Woohyun Cho; Siyeol Kim; Suhwan Choi; Youngjae Yu

[Primary source](<https://openreview.net/forum?id=LWmfHjJnrx>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118548>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/67c15da4a9340140c60783d9a175fd3f-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/67c15da4a9340140c60783d9a175fd3f-Abstract-Conference.html>)

**Training dynamics relevance:** Projects residual contributions orthogonally to the current stream to improve stability and feature diversity.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Residual-update geometry; depth.

**Training qualification:** Results are for the studied vision architectures; LLM hyperparameter transfer is not demonstrated.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/BootsofLagrangian/ortho-residual.>). Links extracted from the accepted abstract; code was not tested.

### Revitalizing SVD for Global Covariance Pooling: Halley’s Method to Overcome Over-Flattening

**NeurIPS 2025 · Accept (poster)** · Jiawei Gu; Ziyue Qiao; Xinming Li; Zechao Li

[Primary source](<https://openreview.net/forum?id=fqpbXJ2QtC>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116798>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1292cf2ff215e3c857c34c32336413a5-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X1 — Matrix functions, roots and matrix geometry.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/1292cf2ff215e3c857c34c32336413a5-Abstract-Conference.html>)

**Quantity:** Matrix power normalization and stable SVD derivatives for covariance pooling.

**Computational idea:** Halley-SVD combines higher-order iteration with a stabilized backward treatment to address spectral over-flattening.

**Scope:** Deep learning. **Qualification:** Designed for covariance-pooling layers; finite numerical iterations and stabilized derivatives require separate accuracy assessment.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1292cf2ff215e3c857c34c32336413a5-Paper-Conference.pdf>): Sections 3.2–3.4, equations (7)–(8), pages 5–6. The reported layer iterates a covariance square-root approximation and differentiates through the iterations, avoiding explicit inverse eigenvalue-gap factors. This passage check does not independently validate the iteration or claimed convergence rate.

### RidgeLoRA: Matrix Ridge Enhanced Low-Rank Adaptation of Large Language Models

**NeurIPS 2025 · Accept (spotlight)** · Junda Zhu; Jun Ai; Yujun Li; Yichun Yin; Yasheng Wang; Lifeng Shang; Qun Liu

[Primary source](<https://openreview.net/forum?id=0RF80tUWuv>) · [Venue page](<https://neurips.cc/virtual/2025/poster/120320>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/31dc7ab2a83641aa58b57017545f0e7e-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/31dc7ab2a83641aa58b57017545f0e7e-Abstract-Conference.html>)

**Optimizer relevance:** RidgeLoRA uses a ridge-based formulation to improve how low-rank fine-tuning approximates full-rank adaptation.

**Evidence:** Official accepted-paper title and abstract.

### Riemannian Consistency Model

**NeurIPS 2025 · Accept (poster)** · Chaoran Cheng; Yusong Wang; Yuxin Chen; Xiangxin Zhou; Nanning Zheng; Ge Liu

[Primary source](<https://openreview.net/forum?id=SAlCQdk5lx>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117955>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/7422317f84e8c83e4c1ad2ff87e1e88e-Paper-Conference.pdf>)

**Topics:** Manifold.

**Categories:** M5 — Supporting geometry, statistics, and training-dynamics papers.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/7422317f84e8c83e4c1ad2ff87e1e88e-Abstract-Conference.html>)

**Manifold relevance:** Riemannian consistency modeling simplifies geometric generative objectives using covariant derivatives and exponential-map structure; adjacent to optimization.

**Geometry:** SO(3), spheres and flat tori. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

### Riemannian Flow Matching for Brain Connectivity Matrices via Pullback Geometry

**NeurIPS 2025 · Accept (poster)** · Antoine Collas; Ce Ju; Nicolas Salvy; Bertrand Thirion

[Primary source](<https://openreview.net/forum?id=NY3LzmUXl7>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118350>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/5616112a0120c15bf7d47a6bccc21bc3-Paper-Conference.pdf>)

**Topics:** Manifold; Matrix computation.

**Categories:** M4 — Related constrained and geometry-aware optimization; X1 — Matrix functions, roots and matrix geometry.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/5616112a0120c15bf7d47a6bccc21bc3-Abstract-Conference.html>)

**Quantity:** Flow-matching computations on SPD and correlation matrices.

**Computational idea:** DiffeoCFM uses matrix diffeomorphisms and pullback metrics to transform geometric flow matching into Euclidean computations.

**Scope:** Deep learning. **Qualification:** Equivalence is tied to the selected diffeomorphism and pullback metric, not every canonical matrix-manifold metric.

**Manifold relevance:** DiffeoCFM transports matrix-manifold flow matching through diffeomorphisms so that the training objective can be implemented in Euclidean coordinates.

**Geometry:** SPD and correlation matrices with pullback geometry. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/antoinecollas/DiffeoCFM>). Links extracted from the accepted abstract; code was not tested.

### Riemannian Proximal Sampler for High-accuracy Sampling on Manifolds

**NeurIPS 2025 · Accept (poster)** · Yunrui Guan; Krishnakumar Balasubramanian; Shiqian Ma

[Primary source](<https://openreview.net/forum?id=KxhCJc8BOg>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118588>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/8e185f16e458ef5e666901260079cd42-Paper-Conference.pdf>)

**Topics:** Manifold.

**Categories:** M5 — Supporting geometry, statistics, and training-dynamics papers.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/8e185f16e458ef5e666901260079cd42-Abstract-Conference.html>)

**Manifold relevance:** Develops high-accuracy sampling using manifold heat-kernel oracles; relevant to geometric numerical methods but targets sampling.

**Geometry:** Riemannian heat kernels and proximal sampling. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

### Robust and Computation-Aware Gaussian Processes

**NeurIPS 2025 · Accept (poster)** · Marshal Sinaga; Julien Martinelli; Samuel Kaski

[Primary source](<https://openreview.net/forum?id=tJZKaDSSTX>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115607>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/0122ad3e4a752438562297553bbf9049-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/0122ad3e4a752438562297553bbf9049-Abstract-Conference.html>)

**Quantity:** GP inference with low-rank computational approximations.

**Computational idea:** RCaGP combines robust generalized Bayesian updates with uncertainty about approximate matrix computations.

**Scope:** General ML. **Qualification:** An approximate, robustness-aware inference model; it does not compute the standard dense GP posterior exactly.

**Evidence:** Official accepted-paper title and abstract.

### Robust Hyperbolic Learning with Curvature-Aware Optimization

**NeurIPS 2025 · Accept (poster)** · Ahmad Bdeir; Johannes Burchert; Lars Schmidt-Thieme; Niels Landwehr

[Primary source](<https://openreview.net/forum?id=lJ5WCJZfQn>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116292>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/75817c38dd91ccef8add921b2eb4284a-Paper-Conference.pdf>)

**Topics:** Manifold; Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods; M3 — Applications that explicitly optimize or solve problems on manifolds.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/75817c38dd91ccef8add921b2eb4284a-Abstract-Conference.html>)

**Optimizer relevance:** Develops curvature-aware Riemannian AdamW updates for robust hyperbolic learning.

**Manifold relevance:** Introduces curvature-aware Riemannian AdamW for stable hyperbolic-model learning.

**Geometry:** Hyperbolic manifolds with variable curvature. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### RSAVQ: Riemannian Sensitivity-Aware Vector Quantization for Large Language Models

**NeurIPS 2025 · Accept (poster)** · Zukang Xu; Xing Hu; Qiang Wu; Dawei Yang

[Primary source](<https://openreview.net/forum?id=8Ounc8L4F7>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119625>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/022a921af644da887f5930377f9d53d6-Paper-Conference.pdf>)

**Topics:** Manifold; Matrix computation.

**Categories:** M4 — Related constrained and geometry-aware optimization; X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/022a921af644da887f5930377f9d53d6-Abstract-Conference.html>)

**Quantity:** Curvature-weighted quantization errors and bit allocation.

**Computational idea:** RSAVQ uses Fisher-Rao geometry to guide adaptive vector quantization.

**Scope:** Deep learning. **Qualification:** The metric is estimated and quantization remains lossy; this is not exact model preservation.

**Manifold relevance:** RSAVQ uses the Fisher metric to guide weight-quantization directions and precision allocation; this is geometry-aware quantization, not a generic constrained manifold optimizer.

**Geometry:** Fisher-Rao metric for quantization. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Diffusion Transformers Efficiently via $\mu$P

**NeurIPS 2025 · Accept (poster)** · Chenyu Zheng; Xinyu Zhang; Rongzhen Wang; Wei Huang; Zhi Tian; Weilin Huang; Jun Zhu; Chongxuan LI

[Primary source](<https://openreview.net/forum?id=VfIOdGiBAv>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117664>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1bf3dbbd6346f50627e2ab1795f90435-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/1bf3dbbd6346f50627e2ab1795f90435-Abstract-Conference.html>)

**Training dynamics relevance:** Extends maximal-update parameterization to diffusion Transformers and tests small-to-large hyperparameter transfer.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** MuP parameterization; width; transferred learning rate.

**Training qualification:** Architectural/objective conditions of the derivation matter; not every generative architecture is covered.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Law with Learning Rate Annealing

**NeurIPS 2025 · Accept (poster)** · Howe Tissue; Venus Wang; Lu Wang

[Primary source](<https://openreview.net/forum?id=VBx4yMNtjt>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117707>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/830b1abc6d2da85f23d41169fa44d185-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/830b1abc6d2da85f23d41169fa44d185-Abstract-Conference.html>)

**Optimizer relevance:** Models how learning-rate annealing changes language-model loss scaling, informing schedule and budget choices.

**Training dynamics relevance:** Models how learning-rate annealing changes language-model loss scaling, informing schedule and budget choices.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Annealing schedule; model size; training loss.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Laws for Gradient Descent and Sign Descent for Linear Bigram Models under Zipf’s Law

**NeurIPS 2025 · Accept (poster)** · Frederik Kunstner; Francis Bach

[Primary source](<https://openreview.net/forum?id=VUbwLjLkws>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117684>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/d51397f67732d310809220b1236f4702-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/d51397f67732d310809220b1236f4702-Abstract-Conference.html>)

**Optimizer relevance:** Derives gradient-descent and sign-descent scaling laws in a linear bigram model with Zipf-distributed tokens; a controlled explanation of adaptive-optimizer advantages.

**Training dynamics relevance:** Derives gradient-descent and sign-descent scaling laws in a linear bigram model with Zipf-distributed tokens; a controlled explanation of adaptive-optimizer advantages.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Token-frequency exponent; gradient/sign descent; vocabulary size.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Laws for Optimal Data Mixtures

**NeurIPS 2025 · Accept (poster)** · Mustafa Shukor; Louis Bethune; Dan Busbridge; David Grangier; Enrico Fini; Alaaeldin El-Nouby; Pierre Ablin

[Primary source](<https://openreview.net/forum?id=vVU1KTOsju>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115404>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/bc1d640f841f752c689aae20b31198c1-Paper-Conference.pdf>)

**Topics:** Training dynamics.

**Categories:** T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/bc1d640f841f752c689aae20b31198c1-Abstract-Conference.html>)

**Training dynamics relevance:** Predicts losses and optimal mixtures using small runs across language, vision and multimodal pretraining.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Data-mixture weights; parameters; tokens.

**Training qualification:** Cross-scale extrapolation requires a suitable fitted mixture law and compatible domain definitions.

**Evidence:** Official accepted-paper title and abstract.

### Second-order Optimization under Heavy-Tailed Noise: Hessian Clipping and Sample Complexity Limits

**NeurIPS 2025 · Accept (poster)** · Abdurakhmon Sadiev; Peter Richtarik; Ilyas Fatkhullin

[Primary source](<https://openreview.net/forum?id=rgrpS4SFNF>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115749>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/be7b70477c8fca697f14b1dbb1c086d1-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/be7b70477c8fca697f14b1dbb1c086d1-Abstract-Conference.html>)

**Optimizer relevance:** Studies second-order optimization under heavy-tailed noise, including Hessian clipping and complexity bounds.

**Evidence:** Official accepted-paper title and abstract.

### Sharper Convergence Rates for Nonconvex Optimisation via Reduction Mappings

**NeurIPS 2025 · Accept (spotlight)** · Evan Markou; Thalaiyasingam Ajanthan; Stephen Gould

[Primary source](<https://openreview.net/forum?id=ZvqbNFWQkh>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117312>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/812f0e17bf0fa2a31a3d0b24dca49462-Paper-Conference.pdf>)

**Topics:** Manifold; Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; M5 — Supporting geometry, statistics, and training-dynamics papers.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/812f0e17bf0fa2a31a3d0b24dca49462-Abstract-Conference.html>)

**Optimizer relevance:** Uses reduction mappings near manifolds of minimizers to improve the geometry of reparameterized optimization problems.

**Manifold relevance:** Studies how reparameterizations near minimizer manifolds alter local curvature and optimization behavior.

**Geometry:** Manifold of minimizers and reduction mappings. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

### Siegel Neural Networks

**NeurIPS 2025 · Accept (poster)** · Xuan Son Nguyen; Aymeric Histace; Nistor Grozavu

[Primary source](<https://openreview.net/forum?id=HIV6t8BAZY>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118902>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/ca1c61a02f458bde48180fc15ae50631-Paper-Conference.pdf>)

**Topics:** Manifold.

**Categories:** M4 — Related constrained and geometry-aware optimization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/ca1c61a02f458bde48180fc15ae50631-Abstract-Conference.html>)

**Manifold relevance:** Uses quotient geometry and vector-valued distances to construct neural-network layers; a supporting representation method.

**Geometry:** Siegel spaces and quotient geometry. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

### SING: SDE Inference via Natural Gradients

**NeurIPS 2025 · Accept (poster)** · Amber Hu; Henry Smith; Scott Linderman

[Primary source](<https://openreview.net/forum?id=jmnt0F21K7>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116435>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/e23b1d49a1fe9732e6d6175006113010-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/e23b1d49a1fe9732e6d6175006113010-Abstract-Conference.html>)

**Optimizer relevance:** SING develops natural-gradient variational inference for latent SDEs, exploiting structure and parallel computation.

**Evidence:** Official accepted-paper title and abstract.

### Sketch-Augmented Features Improve Learning Long-Range Dependencies in Graph Neural Networks

**NeurIPS 2025 · Accept (poster)** · Ryien Hosseini; Filippo Simini; Venkatram Vishwanath; Rebecca Willett; Henry Hoffmann

[Primary source](<https://openreview.net/forum?id=gXoMU9YYdY>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116734>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/6ec23290bd9c728558ff882e44e2f28a-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X4 — Randomized sketching and kernel approximations.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/6ec23290bd9c728558ff882e44e2f28a-Abstract-Conference.html>)

**Quantity:** Global node-feature embeddings for GNNs.

**Computational idea:** Randomized sketched features provide efficient access to nonlocal graph information.

**Scope:** Deep learning. **Qualification:** These are compressed global features, not exact all-pairs message passing.

**Evidence:** Official accepted-paper title and abstract.

### Sketched Adaptive Distributed Deep Learning: A Sharp Convergence Analysis

**NeurIPS 2025 · Accept (poster)** · Zhijie Chen; Qiaobo Li; Arindam Banerjee

[Primary source](<https://openreview.net/forum?id=XIeE8jbM4K>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117527>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/308224aa2da89a3b4257d95b8b2be634-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** E — Training stabilization and distributed optimization; X4 — Randomized sketching and kernel approximations.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/308224aa2da89a3b4257d95b8b2be634-Abstract-Conference.html>)

**Quantity:** Sketched adaptive preconditioners in distributed training.

**Computational idea:** SADL compresses moment/preconditioner information using sketches, with guarantees expressed through intrinsic dimension.

**Scope:** Deep learning. **Qualification:** Sketching introduces approximation; probabilistic guarantees depend on the stated assumptions.

**Optimizer relevance:** SADL uses sketched adaptive preconditioning to reduce communication and memory costs in distributed learning.

**Evidence:** Official accepted-paper title and abstract.

### Sloth: scaling laws for LLM skills to predict multi-benchmark performance across families

**NeurIPS 2025 · Accept (poster)** · Felipe Maia Polo; Seamus Somerstep; Leshem Choshen; Yuekai Sun; Mikhail Yurochkin

[Primary source](<https://openreview.net/forum?id=9GN5Jsa3lv>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119556>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/3834d037cd6e29ac7649df42611c5d66-Paper-Conference.pdf>)

**Topics:** Training dynamics.

**Categories:** T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/3834d037cd6e29ac7649df42611c5d66-Abstract-Conference.html>)

**Training dynamics relevance:** Sloth shares latent-skill information across benchmarks and model families to predict downstream scaling.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Parameters; tokens; family-specific efficiency; latent skills.

**Training qualification:** Observational cross-family benchmark prediction does not isolate every training-recipe effect.

**Evidence:** Official accepted-paper title and abstract.

### Small Batch Size Training for Language Models: When Vanilla SGD Works, and Why Gradient Accumulation is Wasteful

**NeurIPS 2025 · Accept (poster)** · Martin Marek; Sanae Lotfi; Aditya Somasundaram; Andrew Wilson; Micah Goldblum

[Primary source](<https://openreview.net/forum?id=52Ehpe0Lu5>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119899>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/dabfbf500318462382aa70a95466ad85-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/dabfbf500318462382aa70a95466ad85-Abstract-Conference.html>)

**Optimizer relevance:** Examines small-batch language-model training and how Adam second-moment timescales should be measured in tokens; includes vanilla SGD comparisons.

**Training dynamics relevance:** Examines small-batch language-model training and how Adam second-moment timescales should be measured in tokens; includes vanilla SGD comparisons.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Small batches; second-moment half-life; accumulation.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Sparse MeZO: Less Parameters for Better Performance in Zeroth-Order LLM Fine-Tuning

**NeurIPS 2025 · Accept (poster)** · Yong Liu; Zirui Zhu; Chaoyu Gong; Minhao Cheng; Cho-Jui Hsieh; Yang You

[Primary source](<https://openreview.net/forum?id=Tjw0ACu3NL>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117825>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1e5c2efbddc02c1d971e2f19ccdb07d0-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/1e5c2efbddc02c1d971e2f19ccdb07d0-Abstract-Conference.html>)

**Optimizer relevance:** SparseMeZO combines sparse parameter selection with zeroth-order fine-tuning to reduce memory use.

**Evidence:** Official accepted-paper title and abstract.

### Sparse Polyak: an adaptive step size rule for high-dimensional M-estimation

**NeurIPS 2025 · Accept (poster)** · Tianqi Qiao; Marie Maros

[Primary source](<https://openreview.net/forum?id=ddyJqXyCxE>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116994>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/032c421541ad303d9cfa36161a381ed6-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/032c421541ad303d9cfa36161a381ed6-Abstract-Conference.html>)

**Training dynamics relevance:** Modifies Polyak adaptation to estimate smoothness in statistically relevant sparse directions.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Polyak step size; dimension; restricted smoothness.

**Training qualification:** Targets high-dimensional M-estimation rather than general foundation-model training.

**Evidence:** Official accepted-paper title and abstract.

### Spectral Estimation with Free Decompression

**NeurIPS 2025 · Accept (spotlight)** · Siavash Ameli; Chris van der Heide; Liam Hodgkinson; Michael Mahoney

[Primary source](<https://openreview.net/forum?id=2CeGVUpOd7>) · [Venue page](<https://neurips.cc/virtual/2025/poster/120164>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/02d425a464e48bda5e810f8f4914b77e-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/02d425a464e48bda5e810f8f4914b77e-Abstract-Conference.html>)

**Quantity:** Eigenspectra of matrices observed through small submatrices.

**Computational idea:** Free decompression uses free-probability structure to infer large-matrix spectral distributions from masked submatrices.

**Scope:** General ML. **Qualification:** An estimated spectrum under structural/statistical assumptions; it does not recover individual eigenvectors or arbitrary matrices exactly.

**Evidence:** Official accepted-paper title and abstract.

### Spectral Graph Coarsening Using Inner Product Preservation and the Grassmann Manifold

**NeurIPS 2025 · Accept (poster)** · Ido Cohen; Ronen Talmon

[Primary source](<https://openreview.net/forum?id=aBUG2Phwdt>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117290>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/aa4bee5e2720d7e8f073d762ee8c7fd4-Paper-Conference.pdf>)

**Topics:** Manifold; Matrix computation.

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

[Primary source](<https://openreview.net/forum?id=F0JzotXYgC>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119075>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/0e2cf47a9f948f8e8f283d06c118e3ae-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/0e2cf47a9f948f8e8f283d06c118e3ae-Abstract-Conference.html>)

**Quantity:** Spectral-norm error in noisy low-rank approximations.

**Computational idea:** Contour-based perturbation analysis gives spectrum-aware bounds and consequences for private PCA.

**Scope:** Theory / foundations. **Qualification:** A robustness analysis, not a new universally faster factorization algorithm; eigengap and noise conditions matter.

**Evidence:** Official accepted-paper title and abstract.

### StelLA: Subspace Learning in Low-rank Adaptation using Stiefel Manifold

**NeurIPS 2025 · Accept (spotlight)** · Zhizhong Li; Sina Sajadmanesh; Jingtao Li; Lingjuan Lyu

[Primary source](<https://openreview.net/forum?id=55Lv1unlUL>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119898>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/6cb0c6e7d50d5d65613f0456ca85e2db-Paper-Conference.pdf>)

**Topics:** Manifold; Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; M2 — Manifold-based LLM training and low-rank adaptation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/6cb0c6e7d50d5d65613f0456ca85e2db-Abstract-Conference.html>)

**Optimizer relevance:** StelLA separates low-rank directions and scales and converts Euclidean optimizers to Riemannian updates for orthonormal factors in fine-tuning.

**Manifold relevance:** StelLA trains orthonormal direction factors on Stiefel manifolds while separately optimizing the low-rank scale, including LLM fine-tuning.

**Geometry:** Stiefel manifolds for low-rank factors. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://proceedings.neurips.cc/paper_files/paper/2025/file/6cb0c6e7d50d5d65613f0456ca85e2db-Paper-Conference.pdf>): Sections 3–4 and Algorithm 1, pages 3–5. Verified Stiefel tangent projection and polar retraction. The implementation batches SVDs of equal-shaped factors to reduce retraction overhead.

**Code links listed by authors:** [Repository](<https://github.com/SonyResearch/stella.>). Links extracted from the accepted abstract; code was not tested.

### Stepsize anything: A unified learning rate schedule for budgeted-iteration training

**NeurIPS 2025 · Accept (poster)** · Anda Tang; Yiming Dong; Yutao Zeng; zhou Xun; Zhouchen Lin

[Primary source](<https://openreview.net/forum?id=rNcIJi7N65>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115783>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/dce0ad3bd4981fea9a5a5a274a2256d9-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/dce0ad3bd4981fea9a5a5a274a2256d9-Abstract-Conference.html>)

**Optimizer relevance:** Develops budget-aware learning-rate schedules designed to transfer across training lengths.

**Training dynamics relevance:** Develops budget-aware learning-rate schedules designed to transfer across training lengths.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Training budget; learning-rate schedule.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### STNet: Spectral Transformation Network for Solving Operator Eigenvalue Problem

**NeurIPS 2025 · Accept (poster)** · Hong Wang; Yixuan Jiang; Jie Wang; Xinyi Li; Jian Luo; huanshuo dong

[Primary source](<https://openreview.net/forum?id=nimTd1IJz1>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116110>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/48d467d310502791a97d05d1631c5b0f-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X2 — Eigenproblems, spectral computation and SVD analysis.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/48d467d310502791a97d05d1631c5b0f-Abstract-Conference.html>)

**Quantity:** Eigenfunctions and eigenvalues of differential operators.

**Computational idea:** STNet combines deflation and adaptive spectral filtering to ease neural eigenproblem optimization.

**Scope:** Scientific computing. **Qualification:** Approximate neural solutions; performance depends on the spectrum, learned approximations and filtering.

**Evidence:** Official accepted-paper title and abstract.

### StreamBP: Memory-Efficient Exact Backpropagation for Long Sequence Training of LLMs

**NeurIPS 2025 · Accept (poster)** · Qijun Luo; Mengqi Li; Lei Zhao; Xiao Li

[Primary source](<https://openreview.net/forum?id=EpgMSwJY8t>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119094>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/f092c84221d73387a6a5dd7517c500a5-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/f092c84221d73387a6a5dd7517c500a5-Abstract-Conference.html>)

**Quantity:** Backpropagation gradients for causal sequence models.

**Computational idea:** StreamBP reorganizes chain-rule evaluation to stream gradient computation with lower activation memory.

**Scope:** Deep learning. **Qualification:** Preserves the mathematical gradient for the supported computation; practical speed depends on recomputation and implementation.

**Optimizer relevance:** StreamBP reorganizes chain-rule computations for memory-efficient backpropagation in causal language models while preserving the underlying gradient computation.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/Ledzy/StreamBP.>). Links extracted from the accepted abstract; code was not tested.

### Structured Sparse Transition Matrices to Enable State Tracking in State-Space Models

**NeurIPS 2025 · Accept (spotlight)** · Aleksandar Terzic; Nicolas Menet; Michael Hersche; Thomas Hofmann; Abbas Rahimi

[Primary source](<https://openreview.net/forum?id=RDbuSCWhad>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118046>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/77b830c18836a9b2e1395a4936dd687a-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/77b830c18836a9b2e1395a4936dd687a-Abstract-Conference.html>)

**Quantity:** Structured state-transition products and scans.

**Computational idea:** PD-SSM combines column-one-hot and diagonal factors to make recurrent scans linear in state size.

**Scope:** Deep learning. **Qualification:** The transition structure restricts the operator class while providing specified finite-state expressivity guarantees.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/IBM/expressive-sparse-state-space-model.>). Links extracted from the accepted abstract; code was not tested.

### SubTrack++ : Gradient Subspace Tracking for Scalable LLM Training

**NeurIPS 2025 · Accept (poster)** · Sahar Rajabi; Nayeema Nonta; Sirisha Rambhatla

[Primary source](<https://openreview.net/forum?id=6geRIdlFWJ>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119775>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/2d62cb71e87ae340e3ab0e874befcbc2-Paper-Conference.pdf>)

**Topics:** Manifold; Matrix computation; Optimizer.

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

### SUMO: Subspace-Aware Moment-Orthogonalization for Accelerating Memory-Efficient LLM Training

**NeurIPS 2025 · Accept (poster)** · Yehonathan Refael; Guy Smorodinsky; Tom Tirer; Ofir Lindenbaum

[Primary source](<https://openreview.net/forum?id=DIjRvEKOeG>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119226>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/d85a66edadd443ac2350e93c0287f4f9-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers; X1 — Matrix functions, roots and matrix geometry.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/d85a66edadd443ac2350e93c0287f4f9-Abstract-Conference.html>)

**Quantity:** Orthogonalized gradient updates in a tracked subspace.

**Computational idea:** SUMO computes an SVD in a low-dimensional adaptive subspace to reduce matrix orthogonalization cost.

**Scope:** Deep learning. **Qualification:** Orthogonalization is exact within the selected subspace, not the full ambient gradient space.

**Optimizer relevance:** SUMO performs exact SVD orthogonalization within an adaptive low-dimensional gradient subspace to reduce the cost of Muon-style updates.

**Evidence:** Official accepted-paper title and abstract.

### Superposition Yields Robust Neural Scaling

**NeurIPS 2025 · Accept (oral)** · Yizhou Liu; Ziming Liu; Jeff Gore

[Primary source](<https://openreview.net/forum?id=knPz7gtjPW>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116346>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/e97ac22927560eb2de6b658498cbc575-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/e97ac22927560eb2de6b658498cbc575-Abstract-Conference.html>)

**Training dynamics relevance:** Links strong feature superposition to robust inverse-dimension loss scaling.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Representation dimension; weight decay; superposition strength.

**Training qualification:** The mechanism is established in a toy representation model with supporting observations on LLMs.

**Evidence:** Official accepted-paper title and abstract.

### SymMaP: Improving Computational Efficiency in Linear Solvers through Symbolic Preconditioning

**NeurIPS 2025 · Accept (poster)** · Hong Wang; Jie Wang; Minghao Ma; Haoran Shao; Haoyang Liu

[Primary source](<https://openreview.net/forum?id=Oupeovfx0L>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118256>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/5c17c18c1dea5a0c00907824bbb80449-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/5c17c18c1dea5a0c00907824bbb80449-Abstract-Conference.html>)

**Quantity:** Instance-specific preconditioner parameters.

**Computational idea:** SymMaP discovers compact symbolic formulas to select preconditioning parameters cheaply at inference.

**Scope:** Scientific computing. **Qualification:** A learned parameter-selection rule, not an exact symbolic inverse or a uniform convergence guarantee.

**Evidence:** Official accepted-paper title and abstract.

### Tensor Decomposition Networks for Fast Machine Learning Interatomic Potential Computations

**NeurIPS 2025 · Accept (poster)** · Yuchao Lin; Cong Fu; Zachary Krueger; Haiyang Yu; Maho Nakata; Jianwen Xie; Emine Kucukbenli; Xiaofeng Qian; Shuiwang Ji

[Primary source](<https://openreview.net/forum?id=9vKJyCUfMH>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119499>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/7fe3f83c15c1c96daf4689d358c9cadf-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/7fe3f83c15c1c96daf4689d358c9cadf-Abstract-Conference.html>)

**Earlier program title:** Tensor Decomposition Networks for Accelerating Machine Learning Force Field Computations.

**Quantity:** Clebsch-Gordan tensor products in equivariant networks.

**Computational idea:** Replaces expensive tensor products with low-rank tensor decompositions and shares path weights.

**Scope:** Deep learning. **Qualification:** Low-rank decomposition gives approximate equivariance with bounds; exact equivariance and universality claims apply under their specified constructions.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/divelab/AIRS/tree/main/OpenMol/TDN>). Links extracted from the accepted abstract; code was not tested.

### Tensor Product Attention Is All You Need

**NeurIPS 2025 · Accept (spotlight)** · Yifan Zhang; Yifeng Liu; Huizhuo Yuan; Zhen Qin; Yang Yuan; Quanquan Gu; Andrew Yao

[Primary source](<https://openreview.net/forum?id=ECTxVRFhUa>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119152>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/a301ec7cb9e07dc050403e2eb11d0041-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/a301ec7cb9e07dc050403e2eb11d0041-Abstract-Conference.html>)

**Quantity:** Attention queries, keys, values and KV-cache representation.

**Computational idea:** Tensor Product Attention factorizes token-dependent Q/K/V representations into contextual low-rank components.

**Scope:** Deep learning. **Qualification:** A changed attention parameterization, not an exact compression of every pretrained dense attention layer.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/tensorgi/TPA.>). Links extracted from the accepted abstract; code was not tested.

### The Primacy of Magnitude in Low-Rank Adaptation

**NeurIPS 2025 · Accept (spotlight)** · Zicheng Zhang; Haoran Li; Yifeng Zhang; Guoqiang Gong; Jiaxing Wang; Pengzhang Liu; Qixia Jiang; Junxing Hu

[Primary source](<https://openreview.net/forum?id=s4LnWgjacg>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115720>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/0010665e949927b74faf6e3ada6d7f72-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer; Training dynamics.

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

### The Quotient Bayesian Learning Rule

**NeurIPS 2025 · Accept (poster)** · Mykola Lukashchuk; Raphaël Trésor; Wouter Nuijten; Ismail Senoz; Bert Vries

[Primary source](<https://openreview.net/forum?id=XDisynd63Y>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117534>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/0ce1eb87dbb03fdfa872a93d15cfe333-Paper-Conference.pdf>)

**Topics:** Manifold; Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods; M1 — General manifold algorithms and convergence theory.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/0ce1eb87dbb03fdfa872a93d15cfe333-Abstract-Conference.html>)

**Optimizer relevance:** Defines quotient natural-gradient learning for non-exponential distribution families using an exponential-family covering space and inherited Fisher geometry.

**Manifold relevance:** Defines a quotient natural-gradient rule through a covering exponential family for learning with non-exponential distributions.

**Geometry:** Quotient Fisher-Rao geometry. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### The Rich and the Simple: On the Implicit Bias of Adam and SGD

**NeurIPS 2025 · Accept (poster)** · Bhavya Vasudeva; Jung Lee; Vatsal Sharan; Mahdi Soltanolkotabi

[Primary source](<https://openreview.net/forum?id=XLvHmzaHsx>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117522>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/ec9b2a6ad5444caeff75efaa6176b3e4-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/ec9b2a6ad5444caeff75efaa6176b3e4-Abstract-Conference.html>)

**Training dynamics relevance:** Explains how Adam can resist SGD simplicity bias and learn richer decision boundaries.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Adam versus SGD; learned feature complexity.

**Training qualification:** Formal analysis uses two-layer ReLU population gradients; robustness improvements are distribution-dependent.

**Evidence:** Official accepted-paper title and abstract.

### The Structural Complexity of Matrix-Vector Multiplication

**NeurIPS 2025 · Accept (poster)** · Emile Anand; Jan van den Brand; Rose McCarty

[Primary source](<https://openreview.net/forum?id=tGLZj8GWx3>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115613>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/3545b95bd8bdab38c71bcdfa8a91859e-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/3545b95bd8bdab38c71bcdfa8a91859e-Abstract-Conference.html>)

**Quantity:** Repeated matrix-vector products for structured matrices.

**Computational idea:** Preprocesses matrices with bounded VC dimension or pseudodimension to enable subquadratic product queries.

**Scope:** Theory / foundations. **Qualification:** Structure-dependent theoretical algorithms; arbitrary dense matrices do not receive the same guarantee.

**Evidence:** Official accepted-paper title and abstract.

### Through the River: Understanding the Benefit of Schedule-Free Methods for Language Model Training

**NeurIPS 2025 · Accept (poster)** · Minhak Song; Beomhan Baek; Kwangjun Ahn; Chulhee Yun

[Primary source](<https://openreview.net/forum?id=CGx4XU9rCA>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119299>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/b94ab4933fea38629a1308fb78cce2cc-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/b94ab4933fea38629a1308fb78cce2cc-Abstract-Conference.html>)

**Optimizer relevance:** Studies schedule-free optimization with theory and modifications intended to improve momentum behavior and large-batch robustness.

**Training dynamics relevance:** Studies schedule-free optimization with theory and modifications intended to improve momentum behavior and large-batch robustness.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Schedule-free momentum; batch size; averaging.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Tiled Flash Linear Attention: More Efficient Linear RNN and xLSTM Kernels

**NeurIPS 2025 · Accept (poster)** · Maximilian Beck; Korbinian Pöppel; Phillip Lippe; Sepp Hochreiter

[Primary source](<https://openreview.net/forum?id=b6H64u6TqI>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117208>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/6cb81234ab47027e991728ed7dd76735-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/6cb81234ab47027e991728ed7dd76735-Abstract-Conference.html>)

**Quantity:** Chunkwise linear-RNN and mLSTM sequence operators.

**Computational idea:** Tiled Flash Linear Attention adds parallelism within chunks to increase arithmetic intensity and reduce intermediate state traffic.

**Scope:** Deep learning. **Qualification:** Kernel efficiency is hardware- and shape-dependent; an mLSTM variant also changes the model operator.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/NX-AI/mlstm_kernels>). Links extracted from the accepted abstract; code was not tested.

### Towards a General Attention Framework on Gyrovector Spaces for Matrix Manifolds

**NeurIPS 2025 · Accept (poster)** · Rui Wang; Chen Hu; Xiaoning Song; Xiaojun Wu; Nicu Sebe; Ziheng Chen

[Primary source](<https://openreview.net/forum?id=lovTDtbsdZ>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116259>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/a2e3b4132ab2e0b7a21e6e75da7f91a9-Paper-Conference.pdf>)

**Topics:** Manifold.

**Categories:** M4 — Related constrained and geometry-aware optimization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/a2e3b4132ab2e0b7a21e6e75da7f91a9-Abstract-Conference.html>)

**Manifold relevance:** GyroAtt builds geometry-aware attention operators; relevant matrix-manifold architecture, not a general-purpose manifold optimization algorithm.

**Geometry:** SPD, semidefinite and Grassmann matrix geometries. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

### Turbocharging Gaussian Process Inference with Approximate Sketch-and-Project

**NeurIPS 2025 · Accept (poster)** · Pratik Rathore; Zachary Frangella; Sachin Garg; Shaghayegh Fazliani; Michal Derezinski; Madeleine Udell

[Primary source](<https://openreview.net/forum?id=GaL0ja9ygG>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118958>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/cf8b2205e39f81726a8d828ecbe00ad0-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X8 — Linear systems, sparse solvers and Gaussian processes.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/cf8b2205e39f81726a8d828ecbe00ad0-Abstract-Conference.html>)

**Quantity:** Large kernel-system solves and GP posterior means.

**Computational idea:** ADASAP combines approximate sketch-and-project with acceleration and distributed computation.

**Scope:** General ML. **Qualification:** The condition-number-free result concerns specified leading spectral components; finite solves are approximate.

**Evidence:** Official accepted-paper title and abstract.

### Understanding LLM Behaviors via Compression: Data Generation, Knowledge Acquisition and Scaling Laws

**NeurIPS 2025 · Accept (spotlight)** · Zhixuan Pan; Shaowen Wang; Liao Pengfei; Jian Li

[Primary source](<https://openreview.net/forum?id=853SwC2dMZ>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119655>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/f61d7778e89b9221d1ea0ce8428b7014-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/f61d7778e89b9221d1ea0ce8428b7014-Abstract-Conference.html>)

**Training dynamics relevance:** A compression-based syntax/knowledge model explains learning and scaling patterns from common to rare information.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Model/data size; knowledge frequency; fine-tuning.

**Training qualification:** Its Bayesian hierarchical data model is a conceptual theory rather than a literal implementation of LLM training.

**Evidence:** Official accepted-paper title and abstract.

### Understanding Outer Optimizers in Local SGD: Learning Rates, Momentum, and Acceleration

**NeurIPS 2025 · Accept (poster)** · Ahmed Khaled; Satyen Kale; Arthur Douillard; Chi Jin; Rob Fergus; Manzil Zaheer

[Primary source](<https://openreview.net/forum?id=2VX79YLT9s>) · [Venue page](<https://neurips.cc/virtual/2025/poster/120142>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/90ad0e850532986dff56da49bc599904-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** E — Training stabilization and distributed optimization; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/90ad0e850532986dff56da49bc599904-Abstract-Conference.html>)

**Earlier program title:** Understanding outer learning rates in Local SGD.

**Optimizer relevance:** Analyzes and tests outer learning rates in Local SGD, including momentum and language-model settings.

**Training dynamics relevance:** Analyzes and tests outer learning rates in Local SGD, including momentum and language-model settings.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Outer/inner rates; momentum; local SGD.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Understanding the Evolution of the Neural Tangent Kernel at the Edge of Stability

**NeurIPS 2025 · Accept (poster)** · Kaiqi Jiang; Jeremy Cohen; Yuanzhi Li

[Primary source](<https://openreview.net/forum?id=QKo4c3LAz3>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118146>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/2e091b1c71ac0e4b4a4cc39ed3d64fcc-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/2e091b1c71ac0e4b4a4cc39ed3d64fcc-Abstract-Conference.html>)

**Training dynamics relevance:** Studies how larger rates change kernel eigenvectors and alignment with the training target at the edge of stability.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Learning rate; NTK eigenvector alignment.

**Training qualification:** Theory uses a two-layer linear network; broader architectural evidence is empirical.

**Evidence:** Official accepted-paper title and abstract.

### Understanding the Generalization of Stochastic Gradient Adam in Learning Neural Networks

**NeurIPS 2025 · Accept (poster)** · Xuan Tang; Han Zhang; Yuan Cao; Difan Zou

[Primary source](<https://openreview.net/forum?id=ETgPUJfQE1>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119131>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1a54d9deffbb569151e8e4895f4ca162-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/1a54d9deffbb569151e8e4895f4ca162-Abstract-Conference.html>)

**Optimizer relevance:** Analyzes Adam generalization and the roles of batch size and weight decay in a specified convolutional model; conclusions are model-dependent.

**Training dynamics relevance:** Analyzes Adam generalization and the roles of batch size and weight decay in a specified convolutional model; conclusions are model-dependent.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Adam; batch size; weight decay.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Unified Scaling Laws for Compressed Representations

**NeurIPS 2025 · Accept (poster)** · Andrei Panferov; Alexandra Volkova; Ionut-Vlad Modoranu; Vage Egiazarian; Mher Safaryan; Dan Alistarh

[Primary source](<https://openreview.net/forum?id=24wDPGiDzA>) · [Venue page](<https://neurips.cc/virtual/2025/poster/120174>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/ddd7eae51dcd8bbfc936e5b19433d339-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/ddd7eae51dcd8bbfc936e5b19433d339-Abstract-Conference.html>)

**Training dynamics relevance:** Proposes unified/composable scaling laws for compressed representations and identifies failure conditions.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Sparsity; quantization type; effective model size.

**Training qualification:** Compression efficiency depends on the representation assumptions and regimes where the law remains valid.

**Evidence:** Official accepted-paper title and abstract.

### Universal Sequence Preconditioning

**NeurIPS 2025 · Accept (spotlight)** · Annie Marsden; Elad Hazan

[Primary source](<https://openreview.net/forum?id=rwmVd8BKW5>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115735>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/9b25312145e55be426ee7071e845cb90-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods; X7 — Structured products, transforms and GPU kernels.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/9b25312145e55be426ee7071e845cb90-Abstract-Conference.html>)

**Quantity:** Polynomial preconditioning of temporal transition operators.

**Computational idea:** Applies convolution filters from Chebyshev or Legendre polynomials to transform sequence learning problems.

**Scope:** General ML. **Qualification:** The strongest guarantees concern structured dynamical-system settings; this is not a universal LLM-training guarantee.

**Optimizer relevance:** Universal sequence preconditioning uses orthogonal-polynomial convolution filters to improve learning of dynamical sequences.

**Evidence:** Official accepted-paper title and abstract.

### Unveiling m-Sharpness Through the Structure of Stochastic Gradient Noise

**NeurIPS 2025 · Accept (poster)** · Haocheng Luo; Mehrtash Harandi; Dinh Phung; Trung Le

[Primary source](<https://openreview.net/forum?id=rMptAK0Xm8>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115785>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/623a1a9205ba93c5fbb8686df4256223-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T2 — Batch size, gradient noise and training efficiency; T5 — Stability, curvature and edge-of-stability dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/623a1a9205ba93c5fbb8686df4256223-Abstract-Conference.html>)

**Training dynamics relevance:** Explains microbatch-dependent sharpness regularization with an SDE model and motivates reweighted SAM.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** SAM microbatch size; gradient-noise structure.

**Training qualification:** The approximation and empirical effects concern the analyzed SAM variants.

**Evidence:** Official accepted-paper title and abstract.

### Variational Learning Finds Flatter Solutions at the Edge of Stability

**NeurIPS 2025 · Accept (spotlight)** · Avrajit Ghosh; Bai Cong; Rio Yokota; Saiprasad Ravishankar; Rongrong Wang; Molei Tao; Mohammad Emtiyaz Khan; Thomas Möllenhoff

[Primary source](<https://openreview.net/forum?id=nIFFMrDQ5w>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116148>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/6b61c278e483954fee502b49fe71cd14-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/6b61c278e483954fee502b49fe71cd14-Abstract-Conference.html>)

**Training dynamics relevance:** Extends edge-of-stability analysis to variational learning and relates posterior choices to flatter solutions.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Posterior shape; posterior sample count; learning rate.

**Training qualification:** The core derivation begins with quadratic problems and is empirically extended to deep networks.

**Evidence:** Official accepted-paper title and abstract.

### VGGT-SLAM: Dense RGB SLAM Optimized on the SL(4) Manifold

**NeurIPS 2025 · Accept (poster)** · Dominic Maggio; Hyungtae Lim; Luca Carlone

[Primary source](<https://openreview.net/forum?id=63ljkCGMhE>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119817>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/bc65ab11abfbad890171109686233f4e-Paper-Conference.pdf>)

**Topics:** Manifold.

**Categories:** M3 — Applications that explicitly optimize or solve problems on manifolds.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/bc65ab11abfbad890171109686233f4e-Abstract-Conference.html>)

**Manifold relevance:** VGGT-SLAM optimizes projective alignment on SL(4) to resolve reconstruction ambiguity in a SLAM pipeline.

**Geometry:** Special linear group SL(4). **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/MIT-SPARK/VGGT-SLAM.>). Links extracted from the accepted abstract; code was not tested.

### When Kernels Multiply, Clusters Unify: Fusing Embeddings with the Kronecker Product

**NeurIPS 2025 · Accept (poster)** · Youqi WU; Jingwei Zhang; Farzan Farnia

[Primary source](<https://openreview.net/forum?id=XougXwZAHI>) · [Venue page](<https://neurips.cc/virtual/2025/poster/117475>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/317565cd8f3e83be1163f6324b4a4569-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X4 — Randomized sketching and kernel approximations.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/317565cd8f3e83be1163f6324b4a4569-Abstract-Conference.html>)

**Quantity:** Kronecker-product embedding and product-kernel approximation.

**Computational idea:** RP-KrossFuse uses random projections to compress the large feature space induced by multiplying kernels.

**Scope:** Deep learning. **Qualification:** The projected representation approximates the full product kernel; finite sketch size introduces error.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/yokiwuuu/KrossFuse.>). Links extracted from the accepted abstract; code was not tested.

### ZeCO: Zero-Communication Overhead Sequence Parallelism for Linear Attention

**NeurIPS 2025 · Accept (poster)** · Yuhong CHOU; Zehao Liu; Rui-Jie Zhu; Xinyi Wan; Tianjian Li; Congying Chu; Qian Liu; Jibin Wu; Zejun MA

[Primary source](<https://openreview.net/forum?id=eHRFb3DSZS>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116936>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/c7de4d7804077094c10c8f1ba960241c-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/c7de4d7804077094c10c8f1ba960241c-Abstract-Conference.html>)

**Quantity:** Distributed state propagation for linear attention.

**Computational idea:** ZeCO uses an All-Scan collective to provide each device the initial state needed for its sequence segment.

**Scope:** Deep learning. **Qualification:** Zero-overhead terminology denotes effectively hidden/negligible overhead under the analyzed setup, not an absence of communication.

**Evidence:** Official accepted-paper title and abstract.

### Zero-Shot Performance Prediction for Probabilistic Scaling Laws

**NeurIPS 2025 · Accept (poster)** · Viktoria Schram; Markus Hiller; Daniel Beck; Trevor Cohn

[Primary source](<https://openreview.net/forum?id=paiyYD81Wr>) · [Venue page](<https://neurips.cc/virtual/2025/poster/115947>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/072769405a3c1b60171d09c0ade96ebf-Paper-Conference.pdf>)

**Topics:** Training dynamics.

**Categories:** T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/072769405a3c1b60171d09c0ade96ebf-Abstract-Conference.html>)

**Training dynamics relevance:** Uses multi-output Gaussian processes for probabilistic, low-cost scaling and learning-curve prediction.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Learning-curve query budget; model scale; task correlations.

**Training qualification:** Validation is small-scale; uncertainty calibration at frontier scales is not established.

**Evidence:** Official accepted-paper title and abstract.

### ZeroS: Zero‑Sum Linear Attention for Efficient Transformers

**NeurIPS 2025 · Accept (spotlight)** · Jiecheng Lu; Xu Han; Yan Sun; Viresh Pati; Yubin Kim; Siddhartha Somani; Shihao Yang

[Primary source](<https://openreview.net/forum?id=Ms6IXbfzzX>) · [Venue page](<https://neurips.cc/virtual/2025/poster/118425>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1363163299a172662dcf0c0f9932acf6-Paper-Conference.pdf>)

**Topics:** Matrix computation.

**Categories:** X5 — Attention, state-space algebra and parallel scans.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/1363163299a172662dcf0c0f9932acf6-Abstract-Conference.html>)

**Quantity:** Signed linear-time attention aggregation.

**Computational idea:** ZeroS removes the constant softmax component and rescales the remaining zero-sum contribution.

**Scope:** Deep learning. **Qualification:** Defines a different linear-attention operator and expressivity class; it is not identical to general softmax attention.

**Evidence:** Official accepted-paper title and abstract.

### Zeroth-Order Optimization Finds Flat Minima

**NeurIPS 2025 · Accept (poster)** · Liang Zhang; Bingcong Li; Kiran Thekumparampil; Sewoong Oh; Michael Muehlebach; Niao He

[Primary source](<https://openreview.net/forum?id=iXy0ncNepZ>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116554>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/ebc62a3af9342eb4ebc728e5c5bc4cca-Paper-Conference.pdf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/ebc62a3af9342eb4ebc728e5c5bc4cca-Abstract-Conference.html>)

**Optimizer relevance:** Studies the flat-minimum bias of two-point zeroth-order optimization and supports the analysis with language-model fine-tuning experiments.

**Training dynamics relevance:** Studies the flat-minimum bias of two-point zeroth-order optimization and supports the analysis with language-model fine-tuning experiments.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Zeroth-order estimator; implicit Hessian-trace bias.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.
