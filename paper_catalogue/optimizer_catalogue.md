# Optimizer Catalogue

385 curated papers. Updated 2026-09-24. Topic membership overlaps; publication status and evidence are recorded for each entry.

### SKFAC: Training Neural Networks With Faster Kronecker-Factored Approximate Curvature

**CVPR 2021 · Published** · Zedong Tang; Fenlong Jiang; Maoguo Gong; Hao Li; Yue Wu; Fan Yu; Zidong Wang; Min Wang

[Primary source](<https://openaccess.thecvf.com/content/CVPR2021/html/Tang_SKFAC_Training_Neural_Networks_With_Faster_Kronecker-Factored_Approximate_Curvature_CVPR_2021_paper.html>) · [PDF](<https://openaccess.thecvf.com/content/CVPR2021/papers/Tang_SKFAC_Training_Neural_Networks_With_Faster_Kronecker-Factored_Approximate_Curvature_CVPR_2021_paper.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X8 — Linear systems, sparse solvers and Gaussian processes.

**Quantity:** Damped inverses of minibatch KFAC factors.

**Computational idea:** For a factor lambda I + Y^T Y / M, invert M lambda I + YY^T when the minibatch size M is smaller than the layer dimension; use direct inversion otherwise.

**Scope:** Deep learning. **Qualification:** The fully connected-layer inversion is exact for the chosen damped minibatch factors. The Fisher/Kronecker model and convolutional extensions introduce approximations. This is not an online eigenspace tracker for full EMA factors; the benefit depends on batch size versus width.

**Research note relevance:** Swift KFAC (SKFAC) exploits the low rank of minibatch activation and output-derivative Gram matrices. A Woodbury-form identity moves damped factor inversion to a batch-sized system, connecting low-rank preconditioning to efficient KFAC computation.

**Evidence:** Official CVPR proceedings metadata and abstract; targeted full-text passage checked.

- [Targeted passage](<https://openaccess.thecvf.com/content/CVPR2021/papers/Tang_SKFAC_Training_Neural_Networks_With_Faster_Kronecker-Factored_Approximate_Curvature_CVPR_2021_paper.pdf>): Section 3.1, Theorem 1, equations (13)-(17), Algorithm 1; Section 3.2. Checked the batch-sized inversion formula, the batch-size condition and the need for additional convolutional approximations.

### $\mathbf{Li_2}$: A Framework on Dynamics of Feature Emergence and Delayed Generalization

**ICLR 2026 · Accept (Poster)** · Yuandong Tian

[Primary source](<https://openreview.net/forum?id=ceIBRhJpUr>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008484>) · [PDF](<https://openreview.net/pdf?id=ceIBRhJpUr>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Li2 models feature emergence and delayed generalization, including a mechanistic explanation for the effectiveness of Muon-like optimization.

**Training dynamics relevance:** Li2 models feature emergence and delayed generalization, including a mechanistic explanation for the effectiveness of Muon-like optimization.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Feature emergence; delayed generalization; optimizer.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### $\mu$LO: Compute-Efficient Meta-Generalization of Learned Optimizers

**ICLR 2026 · Accept (Poster)** · Benjamin Thérien; Charles-Étienne Joseph; Boris Knyazev; Edouard Oyallon; Irina Rish; Eugene Belilovsky

[Primary source](<https://openreview.net/forum?id=f8z2bzOLK2>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008268>) · [PDF](<https://openreview.net/pdf?id=f8z2bzOLK2>)

**Topics:** Optimizer; Training dynamics.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; T3 — Width/depth scaling and hyperparameter transfer.

**Optimizer relevance:** MuLO derives maximal-update parameterizations for learned optimizers to improve generalization to wider networks and longer training horizons.

**Training dynamics relevance:** MuLO derives maximal-update parameterizations for learned optimizers to improve generalization to wider networks and longer training horizons.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Learned-optimizer parameterization; width; training horizon.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### A Convergence Analysis of Adaptive Optimizers under Floating-point Quantization

**ICLR 2026 · Accept (Poster)** · Xuan Tang; Jichu Li; Difan Zou

[Primary source](<https://openreview.net/forum?id=wwP1SCACee>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10006690>) · [PDF](<https://openreview.net/pdf?id=wwP1SCACee>)

**Topics:** Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers.

**Optimizer relevance:** Convergence theory for Adam and Muon with floating-point quantization of weights, gradients, and optimizer states; distinguishes their sensitivity to different error sources.

**Evidence:** Official accepted-paper title and abstract.

### A Physics-Inspired Optimizer: Velocity Regularized Adam

**ICLR 2026 · Accept (Poster)** · Pranav Vaidhyanathan; Lucas Schorling; Natalia Ares; Michael Osborne

[Primary source](<https://openreview.net/forum?id=6BhduwrCp3>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011394>) · [PDF](<https://openreview.net/pdf?id=6BhduwrCp3>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

**Optimizer relevance:** Velocity-Regularized Adam adds velocity-dependent damping to suppress oscillatory large updates; includes language-model and vision experiments.

**Evidence:** Official accepted-paper title and abstract.

### A Tale of Two Geometries: Adaptive Optimizers and Non-Euclidean Descent

**ICLR 2026 · Accept (Poster)** · Shuo Xie; Tianhao Wang; Beining Wu; Zhiyuan Li

[Primary source](<https://openreview.net/forum?id=iaoAKDRAJQ>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10007952>) · [PDF](<https://openreview.net/pdf?id=iaoAKDRAJQ>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

**Optimizer relevance:** Compares adaptive optimizers and non-Euclidean normalized steepest descent through adaptive smoothness and gradient-variance assumptions.

**Evidence:** Official accepted-paper title and abstract.

### A Theoretical Analysis of Mamba’s Training Dynamics: Filtering Relevant Features for Generalization in State Space Models

**ICLR 2026 · Accept (Poster)** · Mugunthan Shandirasegaran; Hongkang Li; Songyang Zhang; Meng Wang; Shuai Zhang

[Primary source](<https://openreview.net/forum?id=hvpKqEYJjj>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008011>) · [PDF](<https://openreview.net/pdf?id=hvpKqEYJjj>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Explains feature selection by a simplified Mamba block through non-asymptotic learning dynamics.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Signal/noise ratio; training time; sample size.

**Training qualification:** The model is single-layer/single-head with structured synthetic data.

**Evidence:** Official accepted-paper title and abstract.

### A universal compression theory for lottery ticket hypothesis and neural scaling laws

**ICLR 2026 · Accept (Poster)** · Hong-Yi Wang; Di Luo; Tomaso Poggio; Isaac Chuang; Liu Ziyin

[Primary source](<https://openreview.net/forum?id=vxkzW4ljeX>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10006767>) · [PDF](<https://openreview.net/pdf?id=vxkzW4ljeX>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Develops permutation-invariant compression theory with consequences for learning dynamics and scaling laws.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Width; sample size; compression level.

**Training qualification:** Asymptotic existence/construction results are not an off-the-shelf compression recipe for any pretrained LLM.

**Evidence:** Official accepted-paper title and abstract.

### Achieving low-bit Muon through subspace preservation and grid quantization

**ICLR 2026 · Accept (Poster)** · Huaijin Wu; Bingrui Li; Yebin Yang; Yi Tu; Zhanpeng Zhou; Jianfei Chen; Junchi Yan

[Primary source](<https://openreview.net/forum?id=g2l9bg9DWx>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008183>) · [PDF](<https://openreview.net/pdf?id=g2l9bg9DWx>)

**Topics:** Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers.

**Optimizer relevance:** 4-bit-Muon-GRASP compresses momentum using grid quantization while preserving the leading singular subspace; evaluated on LLaMA pretraining and 7B fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/wuhuaijin/lowbit-Muon>). Links extracted from the accepted abstract; code was not tested.

### Adaptive Methods Are Preferable in High Privacy Settings: An SDE Perspective

**ICLR 2026 · Accept (Poster)** · Enea Monzio Compagnoni; Alessandro Stanghellini; Rustem Islamov; Aurelien Lucchi; Anastasia Koloskova

[Primary source](<https://openreview.net/forum?id=hSpA4DAoMk>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008058>) · [PDF](<https://openreview.net/pdf?id=hSpA4DAoMk>)

**Topics:** Optimizer; Training dynamics.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** SDE analysis compares private SGD and sign/adaptive methods under privacy noise and studies hyperparameter transfer across privacy levels.

**Training dynamics relevance:** SDE analysis compares private SGD and sign/adaptive methods under privacy noise and studies hyperparameter transfer across privacy levels.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Privacy noise; adaptive updates; hyperparameter transfer.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Barriers for Learning in an Evolving World:  Mathematical Understanding of Loss of Plasticity

**ICLR 2026 · Accept (Poster)** · Amir Joudaki; Giulia Lanzillotta; Mohammad Samragh; Iman Mirzadeh; Keivan Alizadeh-Vahid; Thomas Hofmann; Mehrdad Farajtabar; Fartash Faghri

[Primary source](<https://openreview.net/forum?id=g6kof5fSba>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008176>) · [PDF](<https://openreview.net/pdf?id=g6kof5fSba>)

**Topics:** Manifold; Optimizer.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; M5 — Supporting geometry, statistics, and training-dynamics papers.

**Optimizer relevance:** Analyzes plasticity loss as gradient dynamics becoming trapped in invariant parameter manifolds and studies architectural interventions; supporting theory rather than a new LLM optimizer.

**Manifold relevance:** Explains loss of plasticity through trapping near frozen- and cloned-unit manifolds. These are dynamical-system obstructions, not a prescribed feasible manifold.

**Geometry:** Invariant submanifolds of parameter dynamics. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

### Bayesian Influence Functions for Hessian-Free Data Attribution

**ICLR 2026 · Accept (Poster)** · Philipp Alexander Kreer; Wilson Wu; Maxwell Adam; Zach Furman; Jesse Hoogland

[Primary source](<https://openreview.net/forum?id=YEBpZVm70i>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008904>) · [PDF](<https://openreview.net/pdf?id=YEBpZVm70i>)

**Topics:** Matrix computation; Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Data influence scores.

**Computational idea:** Replace inverse-Hessian operations with loss-landscape statistics estimated by stochastic-gradient MCMC.

**Scope:** Deep learning. **Qualification:** A Bayesian influence construction, not an algebraically exact classical influence-function evaluation.

**Optimizer relevance:** EKFAC comparison: Bayesian influence functions replace inverse-Hessian computations with stochastic-gradient MCMC loss statistics and evaluate against EK-FAC. A Hessian-free alternative, not an EKFAC variant.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://openreview.net/pdf?id=YEBpZVm70i>): Section 4 and Figure 4, BIF versus EK-FAC retraining experiments; indexed accepted-paper full text. Targeted check recorded in the earlier project catalog; not a complete paper review.

### Beyond Outliers: A Study of Optimizers Under Quantization

**ICLR 2026 · Accept (Poster)** · Georgios Vlassis; Saleh Ashkboos; Alexandra Volkova; Torsten Hoefler; Dan Alistarh

[Primary source](<https://openreview.net/forum?id=mVldAuDAn5>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10007569>) · [PDF](<https://openreview.net/pdf?id=mVldAuDAn5>)

**Topics:** Optimizer; Training dynamics.

**Categories:** D — Memory-efficient and low-precision optimizers; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Systematic study of how optimizer choice affects post-training quantization and quantization-aware training; compares six optimizers and analyzes quantization scaling.

**Training dynamics relevance:** Systematic study of how optimizer choice affects post-training quantization and quantization-aware training; compares six optimizers and analyzes quantization scaling.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Optimizer choice; quantization; precision.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Boosting Multi-Domain Reasoning of LLMs via Curvature-Guided Policy Optimization

**ICLR 2026 · Accept (Poster)** · Xize Liang; Lin Yang; Jie Wang; Rui Liu; Yang Lu; Jinliang Zeng; Hanzhu Chen; Dong Li; Jianye Hao

[Primary source](<https://openreview.net/forum?id=R2EZtdHWJT>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009536>) · [PDF](<https://openreview.net/pdf?id=R2EZtdHWJT>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

**Optimizer relevance:** Curvature-Guided Policy Optimization adds diagonal curvature regularization to multi-domain LLM reinforcement learning; a specialized post-training method.

**Evidence:** Official accepted-paper title and abstract.

### Can Small Training Runs Reliably Guide Data Curation? Rethinking Proxy-Model Practice

**ICLR 2026 · Accept (Poster)** · Jiachen (Tianhao) Wang; Tong Wu; Kaifeng Lyu; James Y Zou; Dawn Song; Ruoxi Jia; Prateek Mittal

[Primary source](<https://openreview.net/forum?id=2FZC0c06jP>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011765>) · [PDF](<https://openreview.net/pdf?id=2FZC0c06jP>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Shows small-model data rankings can flip with hyperparameters and studies reduced proxy rates as a more reliable comparison protocol.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Proxy learning rate; data recipe; tuning budget; scale.

**Training qualification:** A theoretical ordering result is for random-feature models; LLM reliability is empirically tested across recipes.

**Evidence:** Official accepted-paper title and abstract.

### Cautious Optimizers: Improving Training with One Line of Code

**ICLR 2026 · Accept (Poster)** · Kaizhao Liang; Lizhang Chen; Bo Liu; Qiang Liu

[Primary source](<https://openreview.net/forum?id=zBPZeRjfgu>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10006480>) · [PDF](<https://openreview.net/pdf?id=zBPZeRjfgu>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

**Optimizer relevance:** Cautious optimizers apply a one-line modification to momentum-based update rules, including AdamW and Lion; evaluated on language-model pretraining and post-training.

**Evidence:** Official accepted-paper title and abstract.

### Cautious Weight Decay

**ICLR 2026 · Accept (Poster)** · Lizhang Chen; Jonathan Li; Kaizhao Liang; Baiyu Su; Cong Xie; Chen Liang; Ni Lao; Qiang Liu

[Primary source](<https://openreview.net/forum?id=Gwe6gbGng5>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010446>) · [PDF](<https://openreview.net/pdf?id=Gwe6gbGng5>)

**Topics:** Optimizer; Training dynamics.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Cautious Weight Decay applies decay only where parameter and optimizer-update signs agree; a drop-in modification tested with AdamW, Lion, and Muon in LM pretraining.

**Training dynamics relevance:** Cautious Weight Decay applies decay only where parameter and optimizer-update signs agree; a drop-in modification tested with AdamW, Lion, and Muon in LM pretraining.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Weight-decay masking; update signs.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Celo2: Towards Learned Optimization Free Lunch

**ICLR 2026 · Accept (Poster)** · Abhinav Moudgil; Boris Knyazev; Eugene Belilovsky

[Primary source](<https://openreview.net/forum?id=hxDB30LwVe>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008009>) · [PDF](<https://openreview.net/pdf?id=hxDB30LwVe>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

**Optimizer relevance:** Celo2 learns a normalized update rule with inexpensive meta-training and studies transfer to billion-parameter pretraining tasks.

**Evidence:** Official accepted-paper title and abstract.

### Comparing the learning dynamics of in-context learning and fine-tuning in language models

**ICLR 2026 · Accept (Poster)** · Basile Confavreux; Aaditya Singh; Jin Hwa Lee; Amaury Sabran; Andrew Saxe

[Primary source](<https://openreview.net/forum?id=cJAtzOcAnd>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008523>) · [PDF](<https://openreview.net/pdf?id=cJAtzOcAnd>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Compares how ICL and SFT change representations and inherited task priors.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** In-context examples; fine-tuning; training stage.

**Training qualification:** The study uses medium-sized models and distinguishes activation adaptation from weight training.

**Evidence:** Official accepted-paper title and abstract.

### Completed Hyperparameter Transfer across Modules, Width, Depth, Batch and Duration

**ICLR 2026 · Accept (Poster)** · Bruno Mlodozeniec; Pierre Ablin; Louis Béthune; Dan Busbridge; Michal Klein; Jason Ramapuram; marco cuturi

[Primary source](<https://openreview.net/forum?id=elB9k4nTL1>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008289>) · [PDF](<https://openreview.net/pdf?id=elB9k4nTL1>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T3 — Width/depth scaling and hyperparameter transfer; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Studies hyperparameter transfer across width, depth, modules, batch size, and training duration, including Adam parameters and weight decay in LLM training.

**Training dynamics relevance:** Studies hyperparameter transfer across width, depth, modules, batch size, and training duration, including Adam parameters and weight decay in LLM training.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Modules; width; depth; batch size; duration; Adam betas; weight decay.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Compute-Optimal Quantization-Aware Training

**ICLR 2026 · Accept (Poster)** · Aleksandr Dremov; David Grangier; Angelos Katharopoulos; Awni Hannun

[Primary source](<https://openreview.net/forum?id=QpbtT95S95>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009552>) · [PDF](<https://openreview.net/pdf?id=QpbtT95S95>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Models the optimal precision-training allocation and combines learning-rate cooldown with QAT.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** QAT duration; FP/QAT compute split; bit width; cooldown.

**Training qualification:** Optimal ratios depend on budget, precision and model size; fixed ratios need not transfer.

**Evidence:** Official accepted-paper title and abstract.

### Converge Faster, Talk Less: Hessian-Informed Federated Zeroth-Order Optimization

**ICLR 2026 · Accept (Poster)** · Zhe Li; Bicheng Ying; Zidong Liu; Chaosheng Dong; Haibo Yang

[Primary source](<https://openreview.net/forum?id=lJqssVKeR7>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10007694>) · [PDF](<https://openreview.net/pdf?id=lJqssVKeR7>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** HiSo uses global diagonal-Hessian approximations to accelerate federated zeroth-order LLM fine-tuning while retaining scalar-only communication.

**Evidence:** Official accepted-paper title and abstract.

### Convergence of Muon with Newton-Schulz

**ICLR 2026 · Accept (Poster)** · Gyu Yeol Kim; Min-hwan Oh

[Primary source](<https://openreview.net/forum?id=lJSfxtLpLm>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10007695>) · [PDF](<https://openreview.net/pdf?id=lJSfxtLpLm>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

**Optimizer relevance:** Proves convergence of practical Muon using finitely many Newton-Schulz iterations and quantifies the approximation gap to exact SVD-based polar updates.

**Evidence:** Official accepted-paper title and abstract.

### Convex Dominance in Deep Learning I: A Scaling Law of Loss and Learning Rate

**ICLR 2026 · Accept (Poster)** · Zhiqi Bu; Shiyun Xu; Jialin Mao

[Primary source](<https://openreview.net/forum?id=dSdLqg02tx>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008408>) · [PDF](<https://openreview.net/pdf?id=dSdLqg02tx>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T4 — Compute, data and model scaling laws.

**Optimizer relevance:** Models loss and optimal learning-rate scaling using approximately convex training dynamics across model sizes and training horizons.

**Training dynamics relevance:** Models loss and optimal learning-rate scaling using approximately convex training dynamics across model sizes and training horizons.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Learning rate; model scale; training horizon.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### COSMOS: A Hybrid Adaptive Optimizer for Efficient Training of Large Language Models

**ICLR 2026 · Accept (Poster)** · Liming Liu; Zhenghao Xu; Zixuan Zhang; Hao Kang; Zichong Li; Chen Liang; Weizhu Chen; Tuo Zhao

[Primary source](<https://openreview.net/forum?id=j2QTOOtM8R>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10007916>) · [PDF](<https://openreview.net/pdf?id=j2QTOOtM8R>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

**Optimizer relevance:** COSMOS applies SOAP in the leading gradient eigensubspace and Muon in the residual space, targeting memory-efficient LLM training.

**Evidence:** Official accepted-paper title and abstract.

### Dataless Weight Disentanglement in Task Arithmetic via Kronecker-Factored Approximate Curvature

**ICLR 2026 · Accept (Poster)** · Angelo Porrello; Pietro Buzzega; Felix Dangel; Thomas Sommariva; Riccardo Salami; Lorenzo Bonicelli; Simone Calderara

[Primary source](<https://openreview.net/forum?id=32mrjmaeMP>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011679>) · [PDF](<https://openreview.net/pdf?id=32mrjmaeMP>)

**Topics:** Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations.

**Optimizer relevance:** KFAC method/application: TAK constructs a dataless curvature regularizer to reduce interference in task arithmetic and model merging.

**Evidence:** Official accepted-paper title and abstract.

### DeMo: Decoupled Momentum Optimization

**ICLR 2026 · Accept (Poster)** · Bowen Peng; Lizhang Chen; Baiyu Su; Jeffrey Quesnelle; Diederik (Durk) Kingma; Qiang Liu

[Primary source](<https://openreview.net/forum?id=U9oewpa7cn>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009256>) · [PDF](<https://openreview.net/pdf?id=U9oewpa7cn>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

**Optimizer relevance:** DeMo decouples local momentum, sparsifies transformed updates, and reuses momentum for error feedback to reduce language-model training communication.

**Evidence:** Official accepted-paper title and abstract.

### DES-LOC: Desynced Low Communication Adaptive Optimizers for Foundation Models

**ICLR 2026 · Accept (Poster)** · Alex Iacob; Lorenzo Sani; Mher Safaryan; Paris Giampouras; Samuel Horváth; Andrej Jovanovic; Meghdad Kurmanji; Preslav Aleksandrov; William Shen; Xinchi Qiu; Nic Lane

[Primary source](<https://openreview.net/forum?id=6N2qFixxYZ>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011382>) · [PDF](<https://openreview.net/pdf?id=6N2qFixxYZ>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

**Optimizer relevance:** DES-LOC synchronizes parameters and momenta at different periods, with convergence analysis and distributed language-model experiments.

**Evidence:** Official accepted-paper title and abstract.

### DNT: a Deeply Normalized Transformer that can be trained by Momentum SGD

**ICLR 2026 · Accept (Poster)** · Xianbiao Qi; Marco Chen; Wenjie Xiao; Jiaquan Ye; Yelin He; Chun-Guang Li; Zhouchen Lin

[Primary source](<https://openreview.net/forum?id=62pn18XmAg>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011405>) · [PDF](<https://openreview.net/pdf?id=62pn18XmAg>)

**Topics:** Optimizer; Training dynamics.

**Categories:** E — Training stabilization and distributed optimization; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** DNT modifies Transformer normalization to make gradients more suitable for momentum SGD; includes GPT and ViT training experiments.

**Training dynamics relevance:** DNT modifies Transformer normalization to make gradients more suitable for momentum SGD; includes GPT and ViT training experiments.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Transformer normalization; momentum SGD.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Downgrade to Upgrade: Optimizer Simplification Enhances Robustness in LLM Unlearning

**ICLR 2026 · Accept (Poster)** · Yicheng Lang; Yihua Zhang; Chongyu Fan; Changsheng Wang; Jinghan Jia; Sijia Liu

[Primary source](<https://openreview.net/forum?id=Sswng2ToR4>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009373>) · [PDF](<https://openreview.net/pdf?id=Sswng2ToR4>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

**Optimizer relevance:** Studies optimizer order and noise in robust LLM unlearning and proposes a hybrid first-/zeroth-order optimizer.

**Evidence:** Official accepted-paper title and abstract.

### Efficient Orthogonal Fine-Tuning with Principal Subspace Adaptation

**ICLR 2026 · Accept (Poster)** · Fei Wu; Jia Hu; Geyong Min; Shiqiang Wang

[Primary source](<https://openreview.net/forum?id=FSHrinMArK>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010597>) · [PDF](<https://openreview.net/pdf?id=FSHrinMArK>)

**Topics:** Manifold; Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; M4 — Related constrained and geometry-aware optimization.

**Optimizer relevance:** PSOFT restricts orthogonal fine-tuning transformations to a principal weight subspace and gradually relaxes orthogonality for adaptation.

**Manifold relevance:** PSOFT uses constrained/reparameterized orthogonal fine-tuning and tunable relaxations; useful for manifold-inspired PEFT, with deliberate departure from strict orthogonality.

**Geometry:** Principal-subspace orthogonal transformations, gradually relaxed. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

### Efficient Resource-Constrained Training of Transformers via Subspace Optimization

**ICLR 2026 · Accept (Oral)** · Le-Trung Nguyen; Enzo Tartaglione; Van-Tam Nguyen

[Primary source](<https://openreview.net/forum?id=0nvQ5kHXf4>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011896>) · [PDF](<https://openreview.net/pdf?id=0nvQ5kHXf4>)

**Topics:** Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods.

**Optimizer relevance:** WASI restricts Transformer training to a weight-activation subspace to reduce on-device memory and computation; a specialized resource-constrained training method.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/Le-TrungNguyen/ICLR2026-WASI.git.>). Links extracted from the accepted abstract; code was not tested.

### Egalitarian Gradient Descent: A Simple Approach to Accelerated Grokking

**ICLR 2026 · Accept (Poster)** · Ali Saheb Pasand; Elvis Dohmatob

[Primary source](<https://openreview.net/forum?id=wCnHeql3ow>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10006751>) · [PDF](<https://openreview.net/pdf?id=wCnHeql3ow>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Egalitarian Gradient Descent equalizes movement across gradient singular directions to accelerate grokking; general optimizer theory rather than an LLM-scale result.

**Training dynamics relevance:** Egalitarian Gradient Descent equalizes movement across gradient singular directions to accelerate grokking; general optimizer theory rather than an LLM-scale result.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Gradient singular directions; delayed generalization.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Error Feedback for Muon and Friends

**ICLR 2026 · Accept (Poster)** · Kaja Gruntkowska; Alexander Gaponov; Zhirayr Tovmasyan; Peter Richtarik

[Primary source](<https://openreview.net/forum?id=rex7s82Iav>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10007128>) · [PDF](<https://openreview.net/pdf?id=rex7s82Iav>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

**Optimizer relevance:** EF21-Muon extends bidirectional error-feedback compression to non-Euclidean LMO optimizers such as Muon, Scion, and Gluon, with convergence guarantees and NanoGPT experiments.

**Evidence:** Official accepted-paper title and abstract.

### Evaluating Data Influence in Meta Learning

**ICLR 2026 · Accept (Poster)** · Chenyang Ren; Huanyi Xie; Shu Yang; Meng Ding; Dongrui Liu; Lijie Hu; Di Wang

[Primary source](<https://openreview.net/forum?id=0gh7haE5tc>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011910>) · [PDF](<https://openreview.net/pdf?id=0gh7haE5tc>)

**Topics:** Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations.

**Optimizer relevance:** EKFAC application: task-IF and instance-IF handle bilevel meta-learning attribution; EK-FAC accelerates inner inverse-Hessian products, while a Neumann approximation handles the total Hessian.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2501.15963>): Section 5.1, EK-FAC for inner iHVPs and Neumann expansion for the total Hessian; arXiv preprint, acceptance independently verified in the conference program. Targeted check recorded in the earlier project catalog; not a complete paper review.

### Explaining Grokking and Information Bottleneck through Neural Collapse Emergence

**ICLR 2026 · Accept (Poster)** · Keitaro Sakamoto; Issei Sato

[Primary source](<https://openreview.net/forum?id=sLX5P7FTfT>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10007064>) · [PDF](<https://openreview.net/pdf?id=sLX5P7FTfT>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Explains late generalization and information compression through different timescales of data fitting and neural collapse.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Training timescales; within-class representation variance.

**Training qualification:** The proposed explanation is evaluated under its model and dataset assumptions.

**Evidence:** Official accepted-paper title and abstract.

### Fantastic Pretraining Optimizers and Where to Find Them

**ICLR 2026 · Accept (Poster)** · Kaiyue Wen; David Hall; Tengyu Ma; Percy Liang

[Primary source](<https://openreview.net/forum?id=2J51qUZ0iG>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011758>) · [PDF](<https://openreview.net/pdf?id=2J51qUZ0iG>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T3 — Width/depth scaling and hyperparameter transfer; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Controlled benchmark of ten pretraining optimizers across model and token budgets; stresses fair tuning and final-budget evaluation when comparing Muon, SOAP, AdamW, and alternatives.

**Training dynamics relevance:** Controlled benchmark of ten pretraining optimizers across model and token budgets; stresses fair tuning and final-budget evaluation when comparing Muon, SOAP, AdamW, and alternatives.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Optimizer comparison; hyperparameter budget; final training budget.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Fast Catch-Up, Late Switching: Optimal Batch Size Scheduling via Functional Scaling Laws

**ICLR 2026 · Accept (Poster)** · Jinbo Wang; Binghui Li; Zhanpeng Zhou; Mingze Wang; yuxuan sun; Jiaqi Zhang; Xunliang Cai; Lei Wu

[Primary source](<https://openreview.net/forum?id=PXWgzUkVwo>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009661>) · [PDF](<https://openreview.net/pdf?id=PXWgzUkVwo>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T2 — Batch size, gradient noise and training efficiency; T4 — Compute, data and model scaling laws.

**Optimizer relevance:** Uses functional scaling laws to derive batch-size schedules and explains late-switch fast catch-up; evaluates dense and MoE LLM pretraining.

**Training dynamics relevance:** Uses functional scaling laws to derive batch-size schedules and explains late-switch fast catch-up; evaluates dense and MoE LLM pretraining.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Batch-size scheduling; late switching; training budget.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Fast Escape, Slow Convergence: Learning Dynamics of Phase Retrieval under Power-Law Data

**ICLR 2026 · Accept (Oral)** · Guillaume Braun; Bruno Loureiro; Minh Ha Quang; Masaaki Imaizumi

[Primary source](<https://openreview.net/forum?id=Ae4eZpkXBX>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011017>) · [PDF](<https://openreview.net/pdf?id=Ae4eZpkXBX>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Derives fast-escape, slow-convergence and spectral-tail phases that determine scaling of nonlinear regression error.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Training time; data anisotropy; spectral decay.

**Training qualification:** The formal problem is phase retrieval with power-law Gaussian covariance.

**Evidence:** Official accepted-paper title and abstract.

### FedMuon: Federated Learning with Bias-corrected LMO-based Optimization

**ICLR 2026 · Accept (Poster)** · Yuki Takezawa; Anastasia Koloskova; Xiaowen Jiang; Sebastian Stich

[Primary source](<https://openreview.net/forum?id=9k7bvBVenZ>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011085>) · [PDF](<https://openreview.net/pdf?id=9k7bvBVenZ>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

**Optimizer relevance:** FedMuon corrects the bias of LMO-based local updates in federated learning and analyzes approximate Newton-Schulz solves; no LLM-scale claim is established by the abstract.

**Evidence:** Official accepted-paper title and abstract.

### Fine-tuning Quantized Neural Networks with Zeroth-order Optimization

**ICLR 2026 · Accept (Poster)** · Sifeng SHANG; JIAYI ZHOU; Chenyu Lin; Minxian Li; Kaiyang Zhou

[Primary source](<https://openreview.net/forum?id=mGeeRFToaW>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10007599>) · [PDF](<https://openreview.net/pdf?id=mGeeRFToaW>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** Quantized Zeroth-order Optimization perturbs continuous quantization scales and clips directional derivatives, enabling low-memory fine-tuning of quantized LLMs.

**Evidence:** Official accepted-paper title and abstract.

### First is Not Really Better Than Last: Evaluating Layer Choice and Aggregation Strategies in Language Model Data Influence Estimation

**ICLR 2026 · Accept (Poster)** · Dmytro Vitel; Anshuman Chhabra

[Primary source](<https://openreview.net/forum?id=Dkgw08Z4sj>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010747>) · [PDF](<https://openreview.net/pdf?id=Dkgw08Z4sj>)

**Topics:** Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations.

**Optimizer relevance:** EKFAC evaluation: studies layer selection and score aggregation for LLM influence estimation, including Kronfluence/EKFAC. Relevant to using EKFAC reliably, not a new curvature approximation.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://openreview.net/pdf?id=Dkgw08Z4sj>): Additional LLM attribution experiments comparing Kronfluence/EKFAC across layers; indexed accepted-paper full text. Targeted check recorded in the earlier project catalog; not a complete paper review.

### FZOO: Fast Zeroth-Order Optimizer for Fine‑Tuning Large Language Models towards Adam‑Scale Speed

**ICLR 2026 · Accept (Poster)** · Sizhe Dang; yangyangGuo; Yanjun Zhao; Xiaodong Zheng; Guang Dai; Ivor Tsang; Haishan Ye

[Primary source](<https://openreview.net/forum?id=NMlF3YjS8E>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009867>) · [PDF](<https://openreview.net/pdf?id=NMlF3YjS8E>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** FZOO uses batched one-sided Rademacher perturbations and loss-variance-adaptive step sizes to accelerate forward-only LLM fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/DKmiyan/FZOO>). Links extracted from the accepted abstract; code was not tested.

### Generalization Below the Edge of Stability: The Role of Data Geometry

**ICLR 2026 · Accept (Poster)** · Tongtong Liang; Alexander Cloninger; Rahul Parhi; Yu-Xiang Wang

[Primary source](<https://openreview.net/forum?id=zVmS7G6Dyi>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10006451>) · [PDF](<https://openreview.net/pdf?id=zVmS7G6Dyi>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T5 — Stability, curvature and edge-of-stability dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Shows how data geometry changes generalization and memorization for stable two-layer ReLU training.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Step size; input geometry; intrinsic dimension.

**Training qualification:** The guarantees apply below the edge of stability under specified data distributions.

**Evidence:** Official accepted-paper title and abstract.

### Gradient Descent with Large Step Sizes: Chaos and Fractal Convergence Region

**ICLR 2026 · Accept (Poster)** · Shuang Liang; Guido Montufar

[Primary source](<https://openreview.net/forum?id=wsxGCaBjWC>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10006694>) · [PDF](<https://openreview.net/pdf?id=wsxGCaBjWC>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Analyzes chaotic sensitivity and fractal convergence boundaries near critical learning rates.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Step size; initialization; regularization.

**Training qualification:** Results concern scalar-vector and matrix factorization with specified initialization structure.

**Evidence:** Official accepted-paper title and abstract.

### Gradient Intrinsic Dimensionality Alignment：Narrowing The Gap Between Low-Rank Adaptation and Full Fine-Tuning

**ICLR 2026 · Accept (Poster)** · Jingqi Ye; Haonan He; Minglei Li; Fujun Han; Tao Chen; Peng Ye

[Primary source](<https://openreview.net/forum?id=kObvnQ6pUx>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10007793>) · [PDF](<https://openreview.net/pdf?id=kObvnQ6pUx>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

**Optimizer relevance:** RaLoRA aligns adapter ranks with estimated gradient intrinsic dimensionality; RaLoRA-Pro additionally reallocates ranks across layers using loss sensitivity.

**Evidence:** Official accepted-paper title and abstract.

### Gradient-Normalized Smoothness for Optimization with Approximate Hessians

**ICLR 2026 · Accept (Poster)** · Andrei Semenov; Martin Jaggi; Nikita Doikov

[Primary source](<https://openreview.net/forum?id=Epu8Lm6VMK>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010642>) · [PDF](<https://openreview.net/pdf?id=Epu8Lm6VMK>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

**Optimizer relevance:** Gradient-normalized smoothness provides convergence guarantees for approximate second-order methods, including Fisher and Gauss-Newton approximations; broader supporting theory.

**Evidence:** Official accepted-paper title and abstract.

### Grokking in LLM Pretraining? Monitor Memorization-to-Generalization without Test

**ICLR 2026 · Accept (Poster)** · Ziyue Li; Chenrui Fan; Tianyi Zhou

[Primary source](<https://openreview.net/forum?id=blfwRondjY>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008581>) · [PDF](<https://openreview.net/pdf?id=blfwRondjY>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Training dynamics relevance:** Uses expert-pathway similarity and consistency to monitor local memorization-to-generalization transitions.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Pretraining duration; MoE routing geometry.

**Training qualification:** Reported grokking is distribution-dependent within near-single-pass MoE training, not identical to classic multi-epoch toy grokking.

**Evidence:** Official accepted-paper title and abstract.

### High-dimensional limit theorems for SGD: Momentum and Adaptive Step-sizes

**ICLR 2026 · Accept (Poster)** · Aukosh Jagannath; Taj Jones-McCormick; Varnan Sarangian

[Primary source](<https://openreview.net/forum?id=5OJLOwwXV4>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011471>) · [PDF](<https://openreview.net/pdf?id=5OJLOwwXV4>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T1 — Learning-rate selection, warm-up and schedules; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** High-dimensional limits compare SGD, momentum, and adaptive step sizes on tensor PCA and single-index models; supporting theory, not an LLM benchmark.

**Training dynamics relevance:** High-dimensional limits compare SGD, momentum, and adaptive step sizes on tensor PCA and single-index models; supporting theory, not an LLM benchmark.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Momentum; adaptive steps; dimension.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### How does the optimizer implicitly bias the model merging loss landscape?

**ICLR 2026 · Accept (Poster)** · Chenxiang Zhang; Alexander Theus; Damien Teney; Antonio Orvieto; Jun Pang; Sjouke Mauw

[Primary source](<https://openreview.net/forum?id=RU76KTF1Da>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009486>) · [PDF](<https://openreview.net/pdf?id=RU76KTF1Da>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Relates learning rate, weight decay, batch size, and augmentation to effective optimizer noise and the mergeability of independently fine-tuned models.

**Training dynamics relevance:** Relates learning rate, weight decay, batch size, and augmentation to effective optimizer noise and the mergeability of independently fine-tuned models.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Learning rate; weight decay; batch size; model merging.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### How Learning Rate Decay Wastes Your Best Data in Curriculum-Based LLM Pretraining

**ICLR 2026 · Accept (Oral)** · Kairong Luo; Zhenbo Sun; Haodong Wen; Xinyu Shi; Jiarui Cui; Chenyi Dang; Kaifeng Lyu; Wenguang Chen

[Primary source](<https://openreview.net/forum?id=T5wkZJqzkz>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009351>) · [PDF](<https://openreview.net/pdf?id=T5wkZJqzkz>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T4 — Compute, data and model scaling laws.

**Optimizer relevance:** Studies conflicts between learning-rate decay and data-quality curricula; tests moderate decay and checkpoint averaging in LLM pretraining.

**Training dynamics relevance:** Studies conflicts between learning-rate decay and data-quality curricula; tests moderate decay and checkpoint averaging in LLM pretraining.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Rate decay; data curriculum; checkpoint averaging.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### How Muon’s Spectral Design Benefits Generalization: A Study on Imbalanced Data

**ICLR 2026 · Accept (Poster)** · Bhavya Vasudeva; Puneesh Deora; Yize Zhao; Vatsal Sharan; Christos Thrampoulidis

[Primary source](<https://openreview.net/forum?id=YzjS4jcfmS>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008850>) · [PDF](<https://openreview.net/pdf?id=YzjS4jcfmS>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

**Optimizer relevance:** Analyzes spectral gradient descent on imbalanced data and connects balanced learning of principal components to Muon/Shampoo generalization.

**Evidence:** Official accepted-paper title and abstract.

### Hyper-SET: Designing Transformers via Hyperspherical Energy Minimization

**ICLR 2026 · Accept (Poster)** · Yunzhe Hu; Difan Zou; Dong Xu

[Primary source](<https://openreview.net/forum?id=FinhjyDgYA>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010570>) · [PDF](<https://openreview.net/pdf?id=FinhjyDgYA>)

**Topics:** Manifold; Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods; M4 — Related constrained and geometry-aware optimization.

**Optimizer relevance:** Hyper-SET derives recurrent Transformer modules from constrained token-energy minimization on a hypersphere; an architecture with an optimization interpretation, not a parameter optimizer.

**Manifold relevance:** Hyper-SET derives attention/feedforward modules as iterative constrained energy minimization; this is an architecture interpretation, not a general parameter optimizer.

**Geometry:** Hypersphere of token states. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/huyunzhe/hyper-set.>). Links extracted from the accepted abstract; code was not tested.

### Hyperbolic Aware Minimization: Implicit Bias for Sparsity

**ICLR 2026 · Accept (Poster)** · Tom Jacobs; Advait Gadhikar; Celia Rubio-Madrigal; Rebekka Burkholz

[Primary source](<https://openreview.net/forum?id=XKB5Hu0ACY>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008982>) · [PDF](<https://openreview.net/pdf?id=XKB5Hu0ACY>)

**Topics:** Manifold; Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; M4 — Related constrained and geometry-aware optimization.

**Optimizer relevance:** Hyperbolic Aware Minimization alternates ordinary optimizer updates with hyperbolic mirror steps to promote sparse feature learning; the abstract reports vision experiments.

**Manifold relevance:** HAM alternates standard optimizer steps with hyperbolic mirror steps to promote sparsity. It is geometry-aware optimization, not evidence that all model weights lie on a fixed hyperboloid.

**Geometry:** Hyperbolic mirror geometry. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

### Implicit Bias and Loss of Plasticity in Matrix Completion: Depth Promotes Low-Rankness

**ICLR 2026 · Accept (Poster)** · Baekrok Shin; Chulhee Yun

[Primary source](<https://openreview.net/forum?id=NYOYJr988x>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009856>) · [PDF](<https://openreview.net/pdf?id=NYOYJr988x>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Explains depth-dependent low-rank bias and loss of plasticity through coupled matrix-factorization dynamics.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Depth; initialization; pretraining observations.

**Training qualification:** Formal conclusions use block-diagonal observations and structured initializations.

**Evidence:** Official accepted-paper title and abstract.

### Implicit Bias of Per-sample Adam on Separable Data: Departure from the Full-batch Regime

**ICLR 2026 · Accept (Poster)** · Beomhan Baek; Minhak Song; Chulhee Yun

[Primary source](<https://openreview.net/forum?id=LJdAdCo3BN>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010047>) · [PDF](<https://openreview.net/pdf?id=LJdAdCo3BN>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T2 — Batch size, gradient noise and training efficiency; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Shows that per-sample Adam can have a different implicit max-margin bias from full-batch Adam; contrasts its batch dependence with Signum.

**Training dynamics relevance:** Shows that per-sample Adam can have a different implicit max-margin bias from full-batch Adam; contrasts its batch dependence with Signum.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Per-sample versus full-batch Adam; implicit bias.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Implicit bias produces neural scaling laws in learning curves, from perceptrons to deep networks

**ICLR 2026 · Accept (Poster)** · Francesco DAmico; Dario Bocchi; Matteo Negri

[Primary source](<https://openreview.net/forum?id=qBAV2DEvAC>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10007275>) · [PDF](<https://openreview.net/pdf?id=qBAV2DEvAC>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Finds dynamical scaling laws along learning curves and relates them to implicit bias.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Training time; parameter norm; model complexity.

**Training qualification:** Formal support uses logistic perceptrons, with empirical CNN/ResNet/ViT extensions.

**Evidence:** Official accepted-paper title and abstract.

### Implicit Regularization of SGD Reduces Shortcut Learning

**ICLR 2026 · Accept (Poster)** · Nahal Mirzaie; Alireza Alipanah; Ali Abbasi; Amirmahdi Farzane; Hossein Jafarinia; Erfan Sobhaei; Mahdi Ghaznavi; Amir Najafi; Mahdieh Baghshah; Mohammad Hossein Rohban

[Primary source](<https://openreview.net/forum?id=CPdAB7H8mU>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010861>) · [PDF](<https://openreview.net/pdf?id=CPdAB7H8mU>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Links larger learning rates and smaller batches to stronger SGD regularization against shortcut features.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Learning rate; batch size; stochastic versus full gradients.

**Training qualification:** The theory is linear, with supporting deep-network experiments; GD need not share the effect.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/mirzanahal/sgd-implicit-regularization-shortcuts>). Links extracted from the accepted abstract; code was not tested.

### INSTANT: Compressing Gradients and Activations for Resource-Efficient Training

**ICLR 2026 · Accept (Poster)** · Tuan-Kiet Doan; Trung-Hieu Tran; Enzo Tartaglione; Nikola Simidjievski; Van-Tam Nguyen

[Primary source](<https://openreview.net/forum?id=P2q6Y7UweV>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009720>) · [PDF](<https://openreview.net/pdf?id=P2q6Y7UweV>)

**Topics:** Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods.

**Optimizer relevance:** INSTANT compresses gradients and activations into low-rank subspaces to reduce backpropagation cost; adjacent to optimizer-state compression.

**Evidence:** Official accepted-paper title and abstract.

### Intrinsic training dynamics of deep neural networks

**ICLR 2026 · Accept (Poster)** · Sibylle Marcotte; Gabriel Peyré; Rémi Gribonval

[Primary source](<https://openreview.net/forum?id=IlyesljaNb>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010269>) · [PDF](<https://openreview.net/pdf?id=IlyesljaNb>)

**Topics:** Manifold; Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; M5 — Supporting geometry, statistics, and training-dynamics papers; T6 — Feature learning, implicit bias and generalization dynamics.

**Optimizer relevance:** Characterizes when parameter gradient flow induces intrinsic lower-dimensional dynamics, with results for ReLU path lifting and relaxed-balanced linear networks.

**Manifold relevance:** Analyzes when ordinary gradient flow can be rewritten intrinsically, including relaxed-balanced deep linear networks; optimization geometry theory rather than a new constrained solver.

**Training dynamics relevance:** Characterizes when parameter gradient flow induces intrinsic lower-dimensional dynamics, with results for ReLU path lifting and relaxed-balanced linear networks.

**Geometry:** Intrinsic metrics and lower-dimensional lifted parameter dynamics. **Manifold scope:** Related/supporting.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Parameterization; intrinsic gradient-flow trajectories.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### LoFT: Low-Rank Adaptation That Behaves Like Full Fine-Tuning

**ICLR 2026 · Accept (Poster)** · Nurbek Tastan; Stefanos Laskaridis; Martin Takáč; Karthik Nandakumar; Samuel Horváth

[Primary source](<https://openreview.net/forum?id=86P3sb1dpr>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011234>) · [PDF](<https://openreview.net/pdf?id=86P3sb1dpr>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

**Optimizer relevance:** LoFT projects Adam's first and second moments consistently into the adapter subspace to better reproduce full fine-tuning dynamics.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/tnurbek/loft.>). Links extracted from the accepted abstract; code was not tested.

### LoRA meets Riemannion: Muon Optimizer for Parametrization-independent Low-Rank Adapters

**ICLR 2026 · Accept (Poster)** · Vladimir Bogachev; Vladimir Aletov; Alexander Molozhavenko; Denis Bobkov; Vera Soboleva; Aibek Alanov; Maxim Rakhuba

[Primary source](<https://openreview.net/forum?id=WtbXgc9GVA>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009014>) · [PDF](<https://openreview.net/pdf?id=WtbXgc9GVA>)

**Topics:** Manifold; Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; M2 — Manifold-based LLM training and low-rank adaptation.

**Optimizer relevance:** Riemannion extends Muon to the fixed-rank matrix manifold and combines parametrization-independent LoRA optimization with Riemannian initialization.

**Manifold relevance:** Riemannion extends Muon to direct, parametrization-independent LoRA optimization and introduces a Riemannian gradient-informed initialization; evaluated on LLMs and diffusion models.

**Geometry:** Fixed-rank matrix manifold. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### LoRA-S: An Efficient Low Rank Adaptation scheme via Sylvester equation

**ICLR 2026 · Accept (Poster)** · Jinyang ZHENG; Tong Wu

[Primary source](<https://openreview.net/forum?id=Guo2XGgxZA>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010449>) · [PDF](<https://openreview.net/pdf?id=Guo2XGgxZA>)

**Topics:** Manifold; Matrix computation; Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; M2 — Manifold-based LLM training and low-rank adaptation; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Geometry-aware low-rank adapter updates.

**Computational idea:** Use quotient-manifold horizontal lifts and a Sylvester-equation construction for LoRA optimizers.

**Scope:** Deep learning. **Qualification:** Specialized to the low-rank factor geometry; see the paper for metric and solver assumptions.

**Optimizer relevance:** LoRA-S uses quotient-manifold geometry and Sylvester equations to derive Adam-Sylvester and LRACS adapter optimizers.

**Manifold relevance:** LoRA-S uses horizontal lifts and Sylvester equations to derive Adam-Sylvester and LRACS optimizers for low-rank adapters.

**Geometry:** Quotient manifold of low-rank factors. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### MergOPT: A Merge-Aware Optimizer for Robust Model Merging

**ICLR 2026 · Accept (Poster)** · Enneng Yang; Qun Yang; Peng Wang; Anke Tang; Guibing Guo; Xiaochun Cao; Li Shen

[Primary source](<https://openreview.net/forum?id=C21rz8mo65>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010891>) · [PDF](<https://openreview.net/pdf?id=C21rz8mo65>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

**Optimizer relevance:** MergOPT incorporates merge-induced parameter offsets during fine-tuning to improve subsequent model merging; tested on LLM and vision experts.

**Evidence:** Official accepted-paper title and abstract.

### Minor First, Major Last: A Depth-Induced Implicit Bias of Sharpness-Aware Minimization

**ICLR 2026 · Accept (Poster)** · Chaewon Moon; Dongkuk Si; Chulhee Yun

[Primary source](<https://openreview.net/forum?id=ErnnE2UNI2>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010640>) · [PDF](<https://openreview.net/pdf?id=ErnnE2UNI2>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T5 — Stability, curvature and edge-of-stability dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Shows sequential feature amplification and initialization-dependent implicit bias under SAM.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** SAM norm/radius; depth; initialization; training duration.

**Training qualification:** The formal setting is linear diagonal networks; finite-time and infinite-time conclusions differ.

**Evidence:** Official accepted-paper title and abstract.

### Mitigating Non-IID Drift in Zeroth-Order Federated LLM Fine-Tuning with Transferable Sparsity

**ICLR 2026 · Accept (Poster)** · Yide Ran; Wentao Guo; Jingwei Sun; Yanzhou Pan; Xiaodong Yu; Hao Wang; Jianwen Xie; Yiran Chen; Denghui Zhang; Zhaozhuo Xu

[Primary source](<https://openreview.net/forum?id=2DuMBKVbX2>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011768>) · [PDF](<https://openreview.net/pdf?id=2DuMBKVbX2>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** Meerkat uses an extremely sparse transferable parameter subset for federated zeroth-order fine-tuning; a virtual-path extension detects and limits heterogeneous-client drift.

**Evidence:** Official accepted-paper title and abstract.

### MT-DAO: Multi-Timescale Distributed Adaptive Optimizers with Local Updates

**ICLR 2026 · Accept (Poster)** · Alex Iacob; Andrej Jovanovic; Mher Safaryan; Meghdad Kurmanji; Lorenzo Sani; Samuel Horváth; William Shen; Xinchi Qiu; Nic Lane

[Primary source](<https://openreview.net/forum?id=5yPP238v4c>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011409>) · [PDF](<https://openreview.net/pdf?id=5yPP238v4c>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

**Optimizer relevance:** MT-DAO uses momentum at multiple timescales to improve adaptive optimizers with infrequent synchronization and local updates in distributed LM pretraining.

**Evidence:** Official accepted-paper title and abstract.

### Muon Outperforms Adam in Tail-End Associative Memory Learning

**ICLR 2026 · Accept (Poster)** · Shuche Wang; Fengzhuo Zhang; Jiaxiang Li; Cunxiao Du; Chao Du; Tianyu Pang; Zhuoran Yang; Mingyi Hong; Vincent Tan

[Primary source](<https://openreview.net/forum?id=twbMFL0DMp>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10006936>) · [PDF](<https://openreview.net/pdf?id=twbMFL0DMp>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

**Optimizer relevance:** Explains Muon's advantage over Adam through associative-memory parameters and more balanced learning of rare classes in heavy-tailed data.

**Evidence:** Official accepted-paper title and abstract.

### MuonBP: Faster Muon via Block-Periodic Orthogonalization

**ICLR 2026 · Accept (Poster)** · Ahmed Khaled; Kaan Ozkara; Tao Yu; Mingyi Hong; Youngsuk Park

[Primary source](<https://openreview.net/forum?id=mHouLSUQP5>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10007594>) · [PDF](<https://openreview.net/pdf?id=mHouLSUQP5>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

**Optimizer relevance:** MuonBP performs shard-local orthogonalization with periodic full-matrix steps to reduce tensor-parallel communication; derives separate blockwise and full-step learning rates.

**Evidence:** Official accepted-paper title and abstract.

### NerVE: Nonlinear Eigenspectrum Dynamics in LLM Feed-Forward Networks

**ICLR 2026 · Accept (Poster)** · Nandan Kumar Jha; Brandon Reagen

[Primary source](<https://openreview.net/forum?id=W5BPGXR9jf>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009079>) · [PDF](<https://openreview.net/pdf?id=W5BPGXR9jf>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

**Optimizer relevance:** NerVE tracks FFN eigenspectrum dynamics and studies how architecture and optimizer geometry affect representation capacity and generalization in LLMs.

**Evidence:** Official accepted-paper title and abstract.

### Never Saddle for Reparameterized Steepest Descent as Mirror Flow

**ICLR 2026 · Accept (Poster)** · Tom Jacobs; Chao Zhou; Rebekka Burkholz

[Primary source](<https://openreview.net/forum?id=YgudIlQ9nC>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008875>) · [PDF](<https://openreview.net/pdf?id=YgudIlQ9nC>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Steepest mirror flows explain optimizer-dependent feature learning and saddle escape in diagonal networks, with implications for Adam/AdamW fine-tuning.

**Training dynamics relevance:** Steepest mirror flows explain optimizer-dependent feature learning and saddle escape in diagonal networks, with implications for Adam/AdamW fine-tuning.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Reparameterization; mirror geometry; saddle escape.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### New Hybrid Fine-Tuning Paradigm for LLMs:  Algorithm Design and Convergence Analysis Framework

**ICLR 2026 · Accept (Poster)** · Shaocong Ma; Peiran Yu; Heng Huang

[Primary source](<https://openreview.net/forum?id=avgMb57IP5>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008660>) · [PDF](<https://openreview.net/pdf?id=avgMb57IP5>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** Combines zeroth-order updates to the base LLM with first-order PEFT updates; develops hybrid smoothness and convergence analysis for heterogeneous learning rates.

**Evidence:** Official accepted-paper title and abstract.

### On Optimal Hyperparameters for Differentially Private Deep Transfer Learning

**ICLR 2026 · Accept (Poster)** · Aki Rehn; Linzh Zhao; Mikko Heikkilä; Antti Honkela

[Primary source](<https://openreview.net/forum?id=V3fEo612nE>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009176>) · [PDF](<https://openreview.net/pdf?id=V3fEo612nE>)

**Topics:** Optimizer; Training dynamics.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; T2 — Batch size, gradient noise and training efficiency; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Studies clipping thresholds and batch sizes for differentially private transfer learning, including interaction with privacy level and compute budget.

**Training dynamics relevance:** Studies clipping thresholds and batch sizes for differentially private transfer learning, including interaction with privacy level and compute budget.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Private fine-tuning batch size; clipping; privacy budget.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### On Predictability of Reinforcement Learning Dynamics for Large Language Models

**ICLR 2026 · Accept (Poster)** · Cai Yuchen; Ding Cao; Xin Xu; Zijun Yao; Yuqing Huang; Benyi Zhang; Zhenyu Tan; Guiquan Liu; Junfeng Fang

[Primary source](<https://openreview.net/forum?id=SdHmA6BYVJ>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009393>) · [PDF](<https://openreview.net/pdf?id=SdHmA6BYVJ>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Training dynamics relevance:** Reports dominant low-rank, approximately linear parameter-update dynamics and uses them for early extrapolation.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** RL training horizon; early-checkpoint updates.

**Training qualification:** Predictability is empirical over tested models and RL algorithms, not universal exact rank-one dynamics.

**Evidence:** Official accepted-paper title and abstract.

### On the Convergence Behavior of Preconditioned Gradient Descent Toward the Rich Learning Regime

**ICLR 2026 · Accept (Poster)** · Shuai Jiang; Eric Cyr; Ben Southworth; Alexey Voronin

[Primary source](<https://openreview.net/forum?id=CXlsqTAf1E>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010848>) · [PDF](<https://openreview.net/pdf?id=CXlsqTAf1E>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Studies how preconditioned gradient descent changes spectral bias and grokking, including Gauss-Newton methods; separates conjectures about rich learning from proved results.

**Training dynamics relevance:** Studies how preconditioned gradient descent changes spectral bias and grokking, including Gauss-Newton methods; separates conjectures about rich learning from proved results.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Preconditioning; feature-learning regime; grokking.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### On the Convergence Direction of Gradient Descent

**ICLR 2026 · Accept (Poster)** · Shuo Chen; Xiaolong Li; Jiaying Peng; Yao Zhao

[Primary source](<https://openreview.net/forum?id=3U6wH7uAPZ>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011642>) · [PDF](<https://openreview.net/pdf?id=3U6wH7uAPZ>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Optimizer relevance:** Analyzes directional convergence and oscillatory behavior of gradient descent and connects it to edge-of-stability dynamics; SGD and Adam are studied empirically.

**Training dynamics relevance:** Analyzes directional convergence and oscillatory behavior of gradient descent and connects it to edge-of-stability dynamics; SGD and Adam are studied empirically.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Step size; oscillatory convergence direction.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Optimizer Choice Matters For The Emergence of Neural Collapse

**ICLR 2026 · Accept (Poster)** · Jim Zhao; Tin Sum Cheng; Wojciech Masarczyk; Aurelien Lucchi

[Primary source](<https://openreview.net/forum?id=9EPYWJrib1>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011133>) · [PDF](<https://openreview.net/pdf?id=9EPYWJrib1>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Studies how optimizer choice and coupled versus decoupled weight decay affect neural collapse, including momentum effects.

**Training dynamics relevance:** Studies how optimizer choice and coupled versus decoupled weight decay affect neural collapse, including momentum effects.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Optimizer; momentum; coupled/decoupled decay; neural collapse.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### PE-SGD: Differentially Private Deep Learning via Evolution of Gradient Subspace for Text

**ICLR 2026 · Accept (Poster)** · TIANYUAN ZOU; Zinan Lin; Sivakanth Gopi; Yang Liu; Ya-Qin Zhang; Robert Sim; Xin Deng; Sergey Yekhanin

[Primary source](<https://openreview.net/forum?id=713ywmTZHv>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011337>) · [PDF](<https://openreview.net/pdf?id=713ywmTZHv>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

**Optimizer relevance:** PE-SGD evolves a public-data gradient subspace and chooses where to inject privacy noise for differentially private text-model training.

**Evidence:** Official accepted-paper title and abstract.

### Post-hoc Probabilistic Vision-Language Models

**ICLR 2026 · Accept (Poster)** · Anton Baumann; Rui Li; Marcus Klasson; Santeri Mentu; Shyamgopal Karthik; Zeynep Akata; Arno Solin; Martin Trapp

[Primary source](<https://openreview.net/forum?id=XLiUcvHfzS>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008979>) · [PDF](<https://openreview.net/pdf?id=XLiUcvHfzS>)

**Topics:** Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations.

**Optimizer relevance:** KFAC application: BayesVLM uses Kronecker-factored generalized Gauss-Newton curvature for a Laplace posterior over VLM projection layers; uncertainty estimation rather than a replacement optimizer.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2412.06014>): Section 3, Hessian approximation, Eq. (5)-(6); appendix derivation of KFAC GGN. Targeted check recorded in the earlier project catalog; not a complete paper review.

### Pre-training LLM without Learning Rate Decay Enhances Supervised Fine-Tuning

**ICLR 2026 · Accept (Poster)** · Kazuki Yano; Shun Kiyono; Sosuke Kobayashi; Sho Takase; Jun Suzuki

[Primary source](<https://openreview.net/forum?id=JnebU2QLdH>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010172>) · [PDF](<https://openreview.net/pdf?id=JnebU2QLdH>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Compares constant-after-warmup and decaying pretraining learning rates through downstream SFT adaptability on 1B and 8B models.

**Training dynamics relevance:** Compares constant-after-warmup and decaying pretraining learning rates through downstream SFT adaptability on 1B and 8B models.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Pretraining decay; SFT adaptability.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Pre-training under infinite compute

**ICLR 2026 · Accept (Oral)** · Konwoo Kim; Suhas Kotha; Percy Liang; Tatsunori Hashimoto

[Primary source](<https://openreview.net/forum?id=ck0aZTAnwK>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008473>) · [PDF](<https://openreview.net/pdf?id=ck0aZTAnwK>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Studies data-constrained pretraining and finds stronger regularization and ensembling change the attainable loss asymptote.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Epoch count; model size; weight decay; ensemble size.

**Training qualification:** Infinite compute is an extrapolative framing; finite empirical runs support the fitted asymptotes.

**Evidence:** Official accepted-paper title and abstract.

### Predictive Differential Training Guided by Training Dynamics

**ICLR 2026 · Accept (Poster)** · Fanqi Wang; Weisheng Tang; Landon Harris; Hairong Qi; Dan Wilson; Igor Mezic

[Primary source](<https://openreview.net/forum?id=zSTgrLkpRi>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10006455>) · [PDF](<https://openreview.net/pdf?id=zSTgrLkpRi>)

**Topics:** Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods.

**Optimizer relevance:** Predictive Differential Training selects dynamically consistent weight predictions to accelerate ordinary optimizers; broad neural-training method without a specific LLM-scale claim in the abstract.

**Evidence:** Official accepted-paper title and abstract.

### Reshaping Reasoning in LLMs: A Theoretical Analysis of RL Training Dynamics through Pattern Selection

**ICLR 2026 · Accept (Poster)** · Xingwu Chen; Tianle Li; Difan Zou

[Primary source](<https://openreview.net/forum?id=2OO399hRD6>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011748>) · [PDF](<https://openreview.net/pdf?id=2OO399hRD6>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Training dynamics relevance:** Models how RL changes reasoning-pattern distributions through sparse critical-token updates.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Reward type; base-model quality; RL training duration.

**Training qualification:** Theoretical cases distinguish verifiable from internal feedback and do not cover every RL objective.

**Evidence:** Official accepted-paper title and abstract.

### RL Grokking Recipe: How Does RL Unlock and Transfer New Algorithms in LLMs?

**ICLR 2026 · Accept (Poster)** · Yiyou Sun; Yuhan Cao; Pohao Huang; Haoyue Bai; Hanna Hajishirzi; Nouha Dziri; Dawn Song

[Primary source](<https://openreview.net/forum?id=CJJ8VxOWbG>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010871>) · [PDF](<https://openreview.net/pdf?id=CJJ8VxOWbG>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Studies abrupt acquisition of new coding strategies and which training ingredients enable it.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** RL warm-up; replay; curriculum; verification.

**Training qualification:** Results use controlled synthetic coding families; transfer remains uneven across out-of-distribution tests.

**Evidence:** Official accepted-paper title and abstract.

### Robust Training of Neural Networks at Arbitrary Precision and Sparsity

**ICLR 2026 · Accept (Poster)** · Chengxi Ye; Grace Chu; Yanfeng Liu; Yichi Zhang; Lukasz Lew; Li Zhang; Mark Sandler; Andrew Howard

[Primary source](<https://openreview.net/forum?id=e6nZrzSccj>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008354>) · [PDF](<https://openreview.net/pdf?id=e6nZrzSccj>)

**Topics:** Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers.

**Optimizer relevance:** Replaces straight-through estimation with an explicit denoising dequantization gradient path for training at low precision and high sparsity, including LLMs.

**Evidence:** Official accepted-paper title and abstract.

### Saddle-to-Saddle Dynamics Explains A Simplicity Bias Across Neural Network Architectures

**ICLR 2026 · Accept (Poster)** · Yedi Zhang; Andrew Saxe; Peter Latham

[Primary source](<https://openreview.net/forum?id=Vit5M0G5Gb>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009110>) · [PDF](<https://openreview.net/pdf?id=Vit5M0G5Gb>)

**Topics:** Manifold; Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; M5 — Supporting geometry, statistics, and training-dynamics papers; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Explains optimizer simplicity bias through saddle-to-saddle gradient dynamics near invariant manifolds, including attention architectures.

**Manifold relevance:** Explains a simplicity bias of ordinary gradient descent across architectures; related geometry of training, not an algorithm for an externally specified manifold constraint.

**Training dynamics relevance:** Explains optimizer simplicity bias through saddle-to-saddle gradient dynamics near invariant manifolds, including attention architectures.

**Geometry:** Invariant manifolds and saddle-to-saddle dynamics. **Manifold scope:** Related/supporting.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Initialization; saddle-to-saddle dynamics.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Behavior of Discrete Diffusion Language Models

**ICLR 2026 · Accept (Poster)** · Dimitri von Rütte; Janis Fluri; Omead Pooladzandi; Bernhard Schölkopf; Thomas Hofmann; Antonio Orvieto

[Primary source](<https://openreview.net/forum?id=GDYaNzxt9T>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010520>) · [PDF](<https://openreview.net/pdf?id=GDYaNzxt9T>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Shows that masked and uniform diffusion can have different compute-optimal parameter/data allocations.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Diffusion noise type; learning rate; batch size; model/data ratio.

**Training qualification:** Requires tuning the diffusion-specific recipe; autoregressive scaling prescriptions need not apply unchanged.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Laws and Spectra of Shallow Neural Networks in the Feature Learning Regime

**ICLR 2026 · Accept (Oral)** · Leonardo Defilippis; Yizhou Xu; Julius Girardin; Vittorio Erba; Emanuele Troiani; Lenka Zdeborova; Bruno Loureiro; Florent Krzakala

[Primary source](<https://openreview.net/forum?id=Q3yLIIkt7z>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009624>) · [PDF](<https://openreview.net/pdf?id=Q3yLIIkt7z>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Derives scaling regimes and plateaus in feature-learning networks and relates them to learned spectra.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Sample complexity; weight decay; weight spectrum.

**Training qualification:** The detailed phase diagrams concern quadratic and diagonal models.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Laws Meet Model Architecture: Toward Inference-Efficient LLMs

**ICLR 2026 · Accept (Poster)** · Song Bian; Tao Yu; Shivaram Venkataraman; Youngsuk Park

[Primary source](<https://openreview.net/forum?id=0TmVqOpBbK>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011936>) · [PDF](<https://openreview.net/pdf?id=0TmVqOpBbK>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Adds architecture to scaling laws to jointly predict accuracy and inference efficiency.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Hidden width; MLP/attention ratio; GQA; training budget.

**Training qualification:** The conditional law is fitted over specific architecture/data ranges.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Laws of SignSGD in Linear Regression: When Does It Outperform SGD?

**ICLR 2026 · Accept (Poster)** · Jihwan Kim; Dogyoon Song; Chulhee Yun

[Primary source](<https://openreview.net/forum?id=zVwRP0ikrx>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10006450>) · [PDF](<https://openreview.net/pdf?id=zVwRP0ikrx>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Derives compute-optimal signSGD scaling and identifies drift normalization and noise reshaping relative to SGD.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Learning rate; WSD schedule; model size; spectrum.

**Training qualification:** The analysis uses power-law random-feature linear regression.

**Evidence:** Official accepted-paper title and abstract.

### Scaling with Collapse: Efficient and Predictable Training of LLM Families

**ICLR 2026 · Accept (Poster)** · Shane Bergsma; Bin Zhang; Nolan Dey; Shaheer Muhammad; Gurpreet Gosal; Joel Hestness

[Primary source](<https://openreview.net/forum?id=3YKeB9R1g9>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011632>) · [PDF](<https://openreview.net/pdf?id=3YKeB9R1g9>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T4 — Compute, data and model scaling laws; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Uses normalized training-curve collapse to diagnose optimization pathologies and stop hyperparameter searches early when training LLM families.

**Training dynamics relevance:** Uses normalized training-curve collapse to diagnose optimization pathologies and stop hyperparameter searches early when training LLM families.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Training-curve collapse; tuning budget; model families.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### SecP-Tuning: Efficient Privacy-Preserving Prompt Tuning for Large Language Models via MPC

**ICLR 2026 · Accept (Poster)** · Jinglong Luo; Zhuo Zhang; Yehong Zhang; Shiyu Liu; Ye Dong; HUI WANG; Yue Yu; Xun Zhou; Zenglin Xu

[Primary source](<https://openreview.net/forum?id=iJNM7KY8FD>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10007974>) · [PDF](<https://openreview.net/pdf?id=iJNM7KY8FD>)

**Topics:** Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods.

**Optimizer relevance:** SecP-Tuning combines forward-only prompt tuning and secure multiparty computation; specialized privacy-preserving tuning rather than a general optimizer.

**Evidence:** Official accepted-paper title and abstract.

### Seesaw: Accelerating Training by Balancing Batch Size and Learning Rate Scheduling

**ICLR 2026 · Accept (Poster)** · Alexandru Meterez; Depen Morwani; Jingfeng Wu; Costin-Andrei Oncescu; Cengiz Pehlevan; Sham Kakade

[Primary source](<https://openreview.net/forum?id=Nj0XBF2o7z>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009838>) · [PDF](<https://openreview.net/pdf?id=Nj0XBF2o7z>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency.

**Optimizer relevance:** Seesaw couples batch-size ramp-up with learning-rate scheduling to preserve training dynamics and reduce serial steps in LM pretraining.

**Training dynamics relevance:** Seesaw couples batch-size ramp-up with learning-rate scheduling to preserve training dynamics and reduce serial steps in LM pretraining.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Batch ramp-up; learning-rate schedule.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### SGD with Adaptive Preconditioning: Unified Analysis and Momentum Acceleration

**ICLR 2026 · Accept (Poster)** · Dmitry Kovalev

[Primary source](<https://openreview.net/forum?id=XhXMzPJJ7J>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008948>) · [PDF](<https://openreview.net/pdf?id=XhXMzPJJ7J>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

**Optimizer relevance:** Unified analysis of AdaGrad-type preconditioning, including one-sided Shampoo and DASGO, with provable benefits from Nesterov momentum.

**Evidence:** Official accepted-paper title and abstract.

### Shuffling the Data, Extrapolating the Step: Sharper Bias In Constant Step-Size SGD

**ICLR 2026 · Accept (Poster)** · Konstantinos Emmanouilidis; Emmanouil-Vasileios Vlatakis-Gkaragkounis; Rene Vidal

[Primary source](<https://openreview.net/forum?id=QQZ53UtXgf>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009589>) · [PDF](<https://openreview.net/pdf?id=QQZ53UtXgf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency.

**Training dynamics relevance:** Combines random reshuffling and Richardson-Romberg extrapolation to reduce stationary bias in stochastic methods.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Constant step size; reshuffling; iterate extrapolation.

**Training qualification:** Guarantees concern structured variational inequalities and their regularity assumptions.

**Evidence:** Official accepted-paper title and abstract.

### Sign-SGD via Parameter-Free Optimization

**ICLR 2026 · Accept (Poster)** · Daniil Medyakov; Stanko Sergey; Gleb Molodtsov; Philip Zmushko; Grigoriy Evseev; Egor Petrov; Aleksandr Beznosikov

[Primary source](<https://openreview.net/forum?id=yDLD3D95w3>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10006577>) · [PDF](<https://openreview.net/pdf?id=yDLD3D95w3>)

**Topics:** Optimizer; Training dynamics.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; T1 — Learning-rate selection, warm-up and schedules.

**Optimizer relevance:** Parameter-free Sign-SGD removes manual step-size selection, with momentum and sign-only memory variants; evaluated on LLaMA pretraining.

**Training dynamics relevance:** Parameter-free Sign-SGD removes manual step-size selection, with momentum and sign-only memory variants; evaluated on LLaMA pretraining.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Parameter-free step sizes; sign updates; momentum.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### SocialHarmBench: Revealing LLM Vulnerabilities  to Socially Harmful Requests

**ICLR 2026 · Accept (Poster)** · Punya Syon Pandey; Lê Sơn; Devansh Bhardwaj; Zhijing Jin

[Primary source](<https://openreview.net/forum?id=xWTjMkkjrO>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10006638>) · [PDF](<https://openreview.net/pdf?id=xWTjMkkjrO>)

**Topics:** Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations.

**Optimizer relevance:** EKFAC application: SocialHarmBench uses Kronfluence/EK-FAC to attribute harmful LLM outputs to training examples. The main contribution is a safety benchmark, not an optimizer.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://openreview.net/pdf?id=xWTjMkkjrO>): Appendix H.1-H.2, EK-FAC/Kronfluence attribution; indexed accepted-paper full-text passage. Targeted check recorded in the earlier project catalog; not a complete paper review.

### Stable-LoRA: Stabilizing Feature Learning of Low-Rank Adaptation

**ICLR 2026 · Accept (Poster)** · Yize Wu; KE GAO; Ling Li; Yanjun WU

[Primary source](<https://openreview.net/forum?id=xSa19DAieH>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10006643>) · [PDF](<https://openreview.net/pdf?id=xSa19DAieH>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Analyzes stable feature learning in LoRA and introduces early factor shrinkage to manage initialization-induced instability.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** LoRA factor initialization; scaling; early shrinkage.

**Training qualification:** The result concerns the specified LoRA parameterization and adaptation settings.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/Yize-Wu/Stable-LoRA.>). Links extracted from the accepted abstract; code was not tested.

### Study of Training Dynamics for Memory-Constrained Fine-Tuning

**ICLR 2026 · Accept (Poster)** · Aël Quélennec; Nour Hezbri; Pavlo Mozharovskyi; Van-Tam Nguyen; Enzo Tartaglione

[Primary source](<https://openreview.net/forum?id=BhfIg0tuti>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010926>) · [PDF](<https://openreview.net/pdf?id=BhfIg0tuti>)

**Topics:** Optimizer; Training dynamics.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** TraDy combines layer selection and stochastic channel updates for memory-constrained fine-tuning; general transfer learning rather than a dedicated LLM optimizer.

**Training dynamics relevance:** TraDy combines layer selection and stochastic channel updates for memory-constrained fine-tuning; general transfer learning rather than a dedicated LLM optimizer.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Layer/channel selection; memory-limited fine-tuning.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Taming Curvature: Architecture Warm-up for Stable Transformer Training

**ICLR 2026 · Accept (Poster)** · Sameera Ramasinghe; Thalaiyasingam Ajanthan; Hadi Mohaghegh Dolatabadi; Chamin Hewa Koneputugodage; Gil Avraham; Violetta Shevchenko; Yan Zuo; Karol Pajak; Alexander Long

[Primary source](<https://openreview.net/forum?id=DuNf2vPTTK>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010735>) · [PDF](<https://openreview.net/pdf?id=DuNf2vPTTK>)

**Topics:** Matrix computation; Optimizer; Training dynamics.

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

### Taming Momentum: Rethinking Optimizer States Through Low-Rank Approximation

**ICLR 2026 · Accept (Oral)** · Zhengbo Wang; Jian Liang; Ran He; Zilei Wang; Tieniu Tan

[Primary source](<https://openreview.net/forum?id=9Q0dNBYeEY>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011115>) · [PDF](<https://openreview.net/pdf?id=9Q0dNBYeEY>)

**Topics:** Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers.

**Optimizer relevance:** LoRA-Pre interprets momentum EMA as an online linear learner and compresses momentum in a learned low-rank subspace; evaluated in pretraining and fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/mrflogs/LoRA-Pre.>). Links extracted from the accepted abstract; code was not tested.

### Test-Time Training Done Right

**ICLR 2026 · Accept (Poster)** · Tianyuan Zhang; Sai Bi; Yicong Hong; Kai Zhang; Fujun Luan; Songlin Yang; Kalyan Sunkavalli; William Freeman; Hao Tan

[Primary source](<https://openreview.net/forum?id=Tb9qAxT3xv>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009303>) · [PDF](<https://openreview.net/pdf?id=Tb9qAxT3xv>)

**Topics:** Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods.

**Optimizer relevance:** Large Chunk Test-Time Training improves fast-weight update efficiency and supports Muon online updates; an architecture/training application rather than a new general optimizer.

**Evidence:** Official accepted-paper title and abstract.

### The Polar Express: Optimal Matrix Sign Methods and their Application to the Muon Algorithm

**ICLR 2026 · Accept (Oral)** · Noah Amsel; David Persson; Christopher Musco; Robert M. Gower

[Primary source](<https://openreview.net/forum?id=yRtgZ1K8hO>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10006553>) · [PDF](<https://openreview.net/pdf?id=yRtgZ1K8hO>)

**Topics:** Matrix computation; Optimizer.

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X1 — Matrix functions, roots and matrix geometry.

**Quantity:** Polar factor and matrix sign for Muon.

**Computational idea:** Use matrix-multiplication-only polynomial iterations with minimax-designed coefficients and finite-precision stabilization.

**Scope:** Deep learning. **Qualification:** Optimality refers to the paper's polynomial/minimax setting; finite iterations approximate the polar factor.

**Optimizer relevance:** Polar Express computes matrix polar factors with GPU-friendly polynomial iterations and finite-precision safeguards; improves the orthogonalization subroutine used by Muon.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2505.16932v4>): Sections 3.2-3.3; minimax polynomial design and singular-value interval selection. The interval-based optimality claim is more specific than universal optimality over all matrix algorithms.

### The Potential of Second-Order Optimization for LLMs: A Study with Full Gauss-Newton

**ICLR 2026 · Accept (Poster)** · Natalie Abreu; Nikhil Vyas; Sham Kakade; Depen Morwani

[Primary source](<https://openreview.net/forum?id=yxEop1S5le>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10006504>) · [PDF](<https://openreview.net/pdf?id=yxEop1S5le>)

**Topics:** Optimizer.

**Categories:** B — Shampoo, structured curvature, and matrix-function computation.

**Optimizer relevance:** Full Gauss-Newton preconditioning experiments on Transformers up to 150M parameters assess iteration savings and the gap between practical optimizers and layerwise curvature oracles; iteration savings are not wall-clock speedups.

**Evidence:** Official accepted-paper title and abstract.

### Theoretical Modeling of Large Language Model Self-Improvement Training Dynamics Through Solver-Verifier Gap

**ICLR 2026 · Accept (Poster)** · Yifan Sun; Yushan Liang; Zhen Zhang; Xin Liu; Jiaye Teng

[Primary source](<https://openreview.net/forum?id=Hh7x3c0cZl>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010371>) · [PDF](<https://openreview.net/pdf?id=Hh7x3c0cZl>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Models self-improvement trajectories and saturation through the gap between solving and verification abilities.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Solver-verifier gap; self-improvement stage; external data.

**Training qualification:** The fitted dynamics are conditional on the framework and available verifier signal.

**Evidence:** Official accepted-paper title and abstract.

### Theory of Scaling Laws for In-Context Regression: Depth, Width, Context and Time

**ICLR 2026 · Accept (Poster)** · Blake Bordelon; Mary Letey; Cengiz Pehlevan

[Primary source](<https://openreview.net/forum?id=qA42mWsnbl>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10007276>) · [PDF](<https://openreview.net/pdf?id=qA42mWsnbl>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T2 — Batch size, gradient noise and training efficiency; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Derives resource-dependent in-context regression performance and optimal model shapes.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Depth; width; context length; batch size; training steps.

**Training qualification:** The solvable model is deep linear self-attention with structured Gaussian covariates.

**Evidence:** Official accepted-paper title and abstract.

### Three Forward, One Backward: Memory-Efficient Full-Rank Fine-Tuning of Large Models via Extra Forward Passes

**ICLR 2026 · Accept (Poster)** · Jia Zhang; Yu Bai; Hualin Zhang; Tianshuo Chen; Zhaogeng Liu; Zhiqiang Xu; Yi Chang; Bin Gu

[Primary source](<https://openreview.net/forum?id=373rsDQsq4>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011671>) · [PDF](<https://openreview.net/pdf?id=373rsDQsq4>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** LMAO alternates low-rank and zeroth-order directions, combining three forward passes with one backward pass for memory-efficient full-rank fine-tuning updates.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/workelaina/LMAO>). Links extracted from the accepted abstract; code was not tested.

### Towards Dynamic Interleaving Optimizers

**ICLR 2026 · Accept (Poster)** · Yile Chen; Zeyi Wen; Jian Chen; Jin Huang

[Primary source](<https://openreview.net/forum?id=AII8ADdDHt>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011049>) · [PDF](<https://openreview.net/pdf?id=AII8ADdDHt>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

**Optimizer relevance:** DOIT learns surrogate models for choosing among optimizers dynamically during training; general neural optimization with text and translation experiments, not specifically a large-scale LLM result.

**Evidence:** Official accepted-paper title and abstract.

### Towards Efficient Optimizer Design for LLM via Structured Fisher Approximation with a Low-Rank Extension

**ICLR 2026 · Accept (Poster)** · Wenbo Gong; Meyer Scetbon; Chao Ma; Edward Meeds

[Primary source](<https://openreview.net/forum?id=KUFZXdem5R>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010128>) · [PDF](<https://openreview.net/pdf?id=KUFZXdem5R>)

**Topics:** Matrix computation; Optimizer.

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Structured Fisher preconditioners and projected EMA states for LLMs.

**Computational idea:** RACS uses row/column scaling; Alice uses subspace iteration, low-rank state tracking, subspace switching and compensation to extend Eigen-Adam.

**Scope:** Deep learning. **Qualification:** Alice is a low-rank extension of Eigen-Adam, not an implemented low-rank SOAP method. The new detailed method check uses arXiv:2502.07752v2 (2025); the ICLR 2026 venue comes from the accepted-program record.

**Optimizer relevance:** Structured Fisher approximation motivates RACS (Row and Column Scaled SGD) and Alice (Adaptive low-dimensional subspace estimation). Alice extends Eigen-Adam through low-rank tracking of projected EMA states, subspace switching and compensation. This connects memory-efficient LLM optimization to low-rank curvature tracking; Sections 5 and 8 of the arXiv version explicitly leave a low-rank SOAP extension for future work.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://openreview.net/pdf?id=KUFZXdem5R>): Figure 1 and Section 2: block-diagonal/Kronecker empirical-Fisher approximations and relation to K-FAC; indexed accepted-paper full text. Targeted check recorded in the earlier project catalog; not a complete paper review.

- [Targeted passage](<https://arxiv.org/pdf/2502.07752v2>): Section 5 (tracking, subspace switching and compensation), Section 8 (future work), arXiv version 2, 20 February 2025. Checked Alice as a low-rank Eigen-Adam extension and the explicit future-work statement for low-rank SOAP. This additional check is of the preprint, not the accepted OpenReview PDF.

### Towards Greater Leverage: Scaling Laws for Efficient Mixture-of-Experts Language Models

**ICLR 2026 · Accept (Poster)** · Changxin Tian; Kunlong Chen; Jia Liu; Ziqi Liu; Zhiqiang Zhang; JUN ZHOU

[Primary source](<https://openreview.net/forum?id=7r2lkhDGUj>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011257>) · [PDF](<https://openreview.net/pdf?id=7r2lkhDGUj>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Fits MoE efficiency leverage relative to dense models and uses it to select architectures.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Expert activation ratio; granularity; compute.

**Training qualification:** The optimal expert granularity and efficiency depend on the training setup and budget.

**Evidence:** Official accepted-paper title and abstract.

### Training Dynamics Impact Post-Training Quantization Robustness

**ICLR 2026 · Accept (Poster)** · Albert Catalan-Tatjer; Niccolò Ajroldi; Jonas Geiping

[Primary source](<https://openreview.net/forum?id=ZXr3Xx7Z1O>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008797>) · [PDF](<https://openreview.net/pdf?id=ZXr3Xx7Z1O>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Links post-training quantization degradation to the training recipe, especially learning-rate decay, through checkpoints and controlled runs.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Learning-rate decay; training duration; quantization.

**Training qualification:** Validation loss and quantization robustness are distinct objectives; the study does not imply data volume alone causes degradation.

**Evidence:** Official accepted-paper title and abstract.

### Transfer Learning in Infinite Width Feature Learning Networks

**ICLR 2026 · Accept (Poster)** · Clarissa Lauditi; Blake Bordelon; Cengiz Pehlevan

[Primary source](<https://openreview.net/forum?id=Oox4QOhmi9>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009752>) · [PDF](<https://openreview.net/pdf?id=Oox4QOhmi9>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Quantifies transfer from pretraining through adaptive kernels in infinite-width feature-learning networks.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Source/target data; task alignment; feature-learning strength.

**Training qualification:** The asymptotic gradient-flow theory uses specified transfer settings; finite LLM adaptation is not directly guaranteed.

**Evidence:** Official accepted-paper title and abstract.

### Trion: FFT-based Dynamic Subspace Selection for Low-Rank Adaptive Optimization of LLMs

**ICLR 2026 · Accept (Poster)** · Ionut-Vlad Modoranu; Mher Safaryan; Erik Schultheis; Maksim Riabinin; Artem Chumachenko; Dan Alistarh

[Primary source](<https://openreview.net/forum?id=TkHjRwbMNl>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009288>) · [PDF](<https://openreview.net/pdf?id=TkHjRwbMNl>)

**Topics:** Matrix computation; Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers; X7 — Structured products, transforms and GPU kernels.

**Quantity:** Dynamic low-rank gradient projections.

**Computational idea:** Select columns from a fixed discrete-cosine basis using gradient alignment; use FFT-based DCT computation for large layers.

**Scope:** Deep learning. **Qualification:** Approximates adaptive SVD/QR subspaces with a structured fixed basis.

**Optimizer relevance:** Trion selects low-rank gradient subspaces from a fixed DCT basis, using FFT computation to avoid costly per-layer SVD/QR and reduce optimizer memory.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/IST-DASLab/Trion>). Links extracted from the accepted abstract; code was not tested.

### Two failure modes of deep transformers and how to avoid them: a unified theory of signal propagation at initialisation

**ICLR 2026 · Accept (Poster)** · Alessio Giorlandino; Sebastian Goldt

[Primary source](<https://openreview.net/forum?id=utSqpxQHXq>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10006858>) · [PDF](<https://openreview.net/pdf?id=utSqpxQHXq>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Derives Transformer trainability diagrams linking initialization to rank collapse, entropy collapse and vanishing gradients.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Weight scale; residual scale; depth; attention initialization.

**Training qualification:** Signal-propagation theory at initialization is not a guarantee of the entire nonlinear training trajectory.

**Evidence:** Official accepted-paper title and abstract.

### Uncertainty-driven Embedding Convolution

**ICLR 2026 · Accept (Poster)** · Sungjun Lim; Kangjun Noh; Youngjun Choi; Heeyoung Lee; Kyungwoo Song

[Primary source](<https://openreview.net/forum?id=7fdcVi2fTJ>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011274>) · [PDF](<https://openreview.net/pdf?id=7fdcVi2fTJ>)

**Topics:** Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations.

**Optimizer relevance:** KFAC ablation: compares diagonal and KFAC Laplace covariance for embedding uncertainty. Main experiments use diagonal covariance; KFAC is a comparison, not the main UEC method.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2507.20718>): Covariance-structure ablation, Table 17: diagonal versus KFAC; main experiments adopt diagonal covariance. Targeted check recorded in the earlier project catalog; not a complete paper review.

### Understanding and improving Shampoo and SOAP via Kullback-Leibler Minimization

**ICLR 2026 · Accept (Poster)** · Wu Lin; Scott C. Lowe; Felix Dangel; Runa Eschenhagen; Zikun Xu; Roger Grosse

[Primary source](<https://openreview.net/forum?id=pQQuC1nIQq>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10007330>) · [PDF](<https://openreview.net/pdf?id=pQQuC1nIQq>)

**Topics:** Matrix computation; Optimizer.

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Structured covariance estimates for Shampoo and SOAP.

**Computational idea:** Replace Frobenius-motivated estimation with KL-divergence minimization to redesign the preconditioners.

**Scope:** Deep learning. **Qualification:** A different approximation objective; comparative speed and accuracy depend on experiments.

**Optimizer relevance:** KL-Shampoo and KL-SOAP reinterpret structured second moments through KL covariance estimation; KL-Shampoo avoids Adam grafting and its extra state memory.

**Evidence:** Official accepted-paper title and abstract.

### Understanding the Implicit Biases of Design Choices for Time Series Foundation Models

**ICLR 2026 · Accept (Poster)** · Annan Yu; Danielle Maddix; Boran Han; Xiyuan Zhang; Abdul Fatir Ansari; Oleksandr Shchur; Christos Faloutsos; Andrew Gordon Wilson; Michael W Mahoney; Bernie Wang

[Primary source](<https://openreview.net/forum?id=5jkzTzV5Ao>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10011425>) · [PDF](<https://openreview.net/pdf?id=5jkzTzV5Ao>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Analyzes how model-design choices induce interacting biases in time-series foundation models.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Patch size; embeddings; training objective.

**Training qualification:** Time-series-specific findings are supporting evidence rather than LLM training rules.

**Evidence:** Official accepted-paper title and abstract.

### Understanding the Mechanisms of Fast Hyperparameter Transfer

**ICLR 2026 · Accept (Poster)** · Nikhil Ghosh; Denny Wu; Alberto Bietti

[Primary source](<https://openreview.net/forum?id=Q7mLKxQ8qk>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009619>) · [PDF](<https://openreview.net/pdf?id=Q7mLKxQ8qk>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer.

**Optimizer relevance:** Analyzes mechanisms that permit fast hyperparameter transfer, with theoretical examples and an empirically tested trajectory-decomposition conjecture for LLMs.

**Training dynamics relevance:** Analyzes mechanisms that permit fast hyperparameter transfer, with theoretical examples and an empirically tested trajectory-decomposition conjecture for LLMs.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Proxy-model size; training trajectory; hyperparameter transfer.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Weight Decay may matter more than µP for Learning Rate Transfer in Practice

**ICLR 2026 · Accept (Poster)** · Atli Kosson; Jeremy Welborn; Yang Liu; Martin Jaggi; Xi Chen

[Primary source](<https://openreview.net/forum?id=PvTxIdZc1E>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10009637>) · [PDF](<https://openreview.net/pdf?id=PvTxIdZc1E>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Empirically tests the roles of weight decay and maximal-update parameterization in learning-rate transfer across model widths.

**Training dynamics relevance:** Empirically tests the roles of weight decay and maximal-update parameterization in learning-rate transfer across model widths.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Weight decay; MuP; width; learning-rate transfer.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### What Scales in Cross-Entropy Scaling Law?

**ICLR 2026 · Accept (Poster)** · Junxi Yan; Zixi Wei; Qingyao Ai; Yiqun LIU; Jingtao Zhan

[Primary source](<https://openreview.net/forum?id=o94xgM0sWJ>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10007437>) · [PDF](<https://openreview.net/pdf?id=o94xgM0sWJ>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Separates cross-entropy into components and finds that error-entropy better tracks power-law scaling in the studied models.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Model scale; training time; evaluation loss decomposition.

**Training qualification:** This is a proposed decomposition-based explanation with empirical support, not a universal replacement law.

**Evidence:** Official accepted-paper title and abstract.

### WSM: Decay-Free Learning Rate Schedule via Checkpoint Merging for LLM Pre-training

**ICLR 2026 · Accept (Oral)** · Changxin Tian; Jiapeng Wang; Qian Zhao; Kunlong Chen; Jia Liu; Ziqi Liu; Jiaxin Mao; Xin Zhao; Zhiqiang Zhang; JUN ZHOU

[Primary source](<https://openreview.net/forum?id=HhThhjKyfw>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10010369>) · [PDF](<https://openreview.net/pdf?id=HhThhjKyfw>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules.

**Optimizer relevance:** Warmup-Stable and Merge replaces an explicit decay phase with principled checkpoint averaging, linking merging weights to learning-rate schedules.

**Training dynamics relevance:** Warmup-Stable and Merge replaces an explicit decay phase with principled checkpoint averaging, linking merging weights to learning-rate schedules.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Warm-up; constant rate; checkpoint merging.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### xLSTM Scaling Laws: Competitive Performance with Linear Time-Complexity

**ICLR 2026 · Accept (Poster)** · Maximilian Beck; Kajetan Schweighofer; Sebastian Böck; Sebastian Lehner; Sepp Hochreiter

[Primary source](<https://openreview.net/forum?id=bpbU549sSg>) · [Venue page](<https://iclr.cc/virtual/2026/poster/10008569>) · [PDF](<https://openreview.net/pdf?id=bpbU549sSg>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Compares Transformer and xLSTM compute-optimal and overtrained scaling, including context-dependent optimal size.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Architecture; context length; parameters; token budget.

**Training qualification:** Performance rankings are tied to the evaluated architectures, training recipes and compute accounting.

**Evidence:** Official accepted-paper title and abstract.

### GaLore: Memory-Efficient LLM Training by Gradient Low-Rank Projection

**ICML 2024 · Published** · Jiawei Zhao; Zhenyu Zhang; Beidi Chen; Zhangyang Wang; Anima Anandkumar; Yuandong Tian

[Primary source](<https://proceedings.mlr.press/v235/zhao24s.html>) · [PDF](<https://raw.githubusercontent.com/mlresearch/v235/main/assets/zhao24s/zhao24s.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers; X6 — Matrix and tensor methods for compression.

[Accepted proceedings](<https://proceedings.mlr.press/v235/zhao24s.html>)

**Quantity:** Projected gradients and compressed optimizer states.

**Computational idea:** Use leading singular vectors of the current gradient to form low-rank projections, apply an optimizer such as Adam in the projected space, then lift its update to the original weight matrix.

**Scope:** Deep learning. **Qualification:** GaLore compresses gradients and optimizer states rather than KFAC factors or a Fisher approximation. Weights remain full-sized; low-rank projection changes the update and periodic SVD refreshes have a computational cost.

**Research note relevance:** GaLore projects gradients into a low-rank subspace, maintains optimizer states there, and maps updates back to the full parameter space. Periodically refreshed projection bases allow full-parameter learning while reducing optimizer-state memory, making it relevant to LLM low-rank optimizer design.

**Evidence:** Official ICML 2024 PMLR proceedings metadata and abstract; targeted full-text passage checked.

- [Targeted passage](<https://raw.githubusercontent.com/mlresearch/v235/main/assets/zhao24s/zhao24s.pdf>): Algorithm 1; Sections 3.3 and 4.1, equations (12)-(14). Checked projected optimization, SVD basis refresh and composition of updates across changing subspaces.

### $\mu$pscaling small models: Principled warm starts and hyperparameter transfer

**ICML 2026 · Accept (regular)** · Yuxin Ma; Nan Chen; Mateo D Diaz; Soufiane Hayou; Dmitriy Kunisky; Soledad Villar

[Primary source](<https://openreview.net/forum?id=bAqpZRzlTg>) · [Venue page](<https://icml.cc/virtual/2026/poster/62988>) · [PDF](<https://openreview.net/pdf?id=bAqpZRzlTg>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Extends maximal-update ideas to widening pretrained models, with principled perturbation scaling and optimizer hyperparameter transfer.

**Training dynamics relevance:** Extends maximal-update ideas to widening pretrained models, with principled perturbation scaling and optimizer hyperparameter transfer.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Width expansion; initialization perturbation; hyperparameter transfer.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### A Fourier perspective on the learning dynamics of neural networks: from sample complexities to mechanistic insights

**ICML 2026 · Accept (regular)** · Fabiola Ricci; Claudia Merger; Sebastian Goldt

[Primary source](<https://openreview.net/forum?id=RQECNEUcbJ>) · [Venue page](<https://icml.cc/virtual/2026/poster/64045>) · [PDF](<https://openreview.net/pdf?id=RQECNEUcbJ>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Explains why amplitude features precede phase features and how power-law spectra alter feature-learning times.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Data spectrum; training time; feature complexity.

**Training qualification:** Formal complexity results use a controlled translation-invariant data model.

**Evidence:** Official accepted-paper title and abstract.

### A Sketch-and-Project Analysis of Subsampled Natural Gradient Algorithms

**ICML 2026 · Accept (regular)** · Gil Goldshlager; Jiang Hu; Lin Lin

[Primary source](<https://openreview.net/forum?id=2iDtIht7W4>) · [Venue page](<https://icml.cc/virtual/2026/poster/66550>) · [PDF](<https://openreview.net/pdf?id=2iDtIht7W4>)

**Topics:** Matrix computation; Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Subsampled natural-gradient directions.

**Computational idea:** Interpret the update as sketch-and-project and analyze coupling with a squared-volume-sampling proxy.

**Scope:** Theory / foundations. **Qualification:** Primarily an analysis of natural-gradient algorithms; distinguishes the proxy from practical sampling.

**Optimizer relevance:** Analyzes subsampled natural gradient through sketch-and-project geometry, including coupled small minibatches and SPRING momentum; focus is scientific ML.

**Evidence:** Official accepted-paper title and abstract.

### A unified theory of feature learning in RNNs and DNNs

**ICML 2026 · Accept (regular)** · Jan Bauer; Kirsten Fischer; Moritz Helias; Agostina Palmigiano

[Primary source](<https://openreview.net/forum?id=nkVt0sY9HJ>) · [Venue page](<https://icml.cc/virtual/2026/poster/61686>) · [PDF](<https://openreview.net/pdf?id=nkVt0sY9HJ>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Develops mean-field feature-learning theory for recurrent and feedforward networks and identifies a signal-to-noise transition in learned representations.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Width; feature-learning strength; weight sharing.

**Training qualification:** The analysis concerns its asymptotic/Bayesian formulation, not every finite-width optimizer trajectory.

**Evidence:** Official accepted-paper title and abstract.

### AdaGC: Enhancing LLM Pretraining Stability via Adaptive Gradient Clipping

**ICML 2026 · Accept (regular)** · Guoxia Wang; Shuai Li; Congliang Chen; Jinle Zeng; Jiabin Yang; Dianhai Yu; Yanjun Ma; Li Shen

[Primary source](<https://openreview.net/forum?id=uBYlCu8b8Z>) · [Venue page](<https://icml.cc/virtual/2026/poster/61050>) · [PDF](<https://openreview.net/pdf?id=uBYlCu8b8Z>)

**Topics:** Optimizer; Training dynamics.

**Categories:** E — Training stabilization and distributed optimization; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** AdaGC uses adaptive per-tensor gradient clipping to prevent gradient spikes from contaminating optimizer states during LLM pretraining.

**Training dynamics relevance:** AdaGC uses adaptive per-tensor gradient clipping to prevent gradient spikes from contaminating optimizer states during LLM pretraining.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Gradient clipping; moment contamination.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/PaddlePaddle/PaddleFleet>). Links extracted from the accepted abstract; code was not tested.

### AdaMeZO: Adam-style Zeroth-Order Optimizer for LLM Fine-tuning Without Maintaining the Moments

**ICML 2026 · Accept (regular)** · Zhijie Cai; Haolong Chen; Guangxu Zhu

[Primary source](<https://openreview.net/forum?id=XLc102wbnT>) · [Venue page](<https://icml.cc/virtual/2026/poster/63417>) · [PDF](<https://openreview.net/pdf?id=XLc102wbnT>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** AdaMeZO approximates Adam-style zeroth-order adaptation without retaining full first- and second-moment tensors.

**Evidence:** Official accepted-paper title and abstract.

### Adaptive Batch Sizes Using Non-Euclidean Gradient Noise Scales for Stochastic Sign and Spectral Descent

**ICML 2026 · Accept (regular)** · Hiroki Naganuma; Shagun Gupta; Youssef Briki; Ioannis Mitliagkas; Irina Rish; Parameswaran Raman; Hao-Jun Shi

[Primary source](<https://openreview.net/forum?id=XMSaWRpEPS>) · [Venue page](<https://icml.cc/virtual/2026/poster/63415>) · [PDF](<https://openreview.net/pdf?id=XMSaWRpEPS>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T2 — Batch size, gradient noise and training efficiency.

**Optimizer relevance:** Derives gradient-noise scales for sign and spectral descent and uses them for adaptive batch sizing with Signum and Muon.

**Training dynamics relevance:** Derives gradient-noise scales for sign and spectral descent and uses them for adaptive batch sizing with Signum and Muon.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Sign/spectral gradient noise scale; adaptive batch size.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Adaptive Momentum and Nonlinear Damping for Neural Network Training

**ICML 2026 · Accept (regular)** · Aikaterini Karoni; Rajit Rajpal; Benedict Leimkuhler; Gabriel Stoltz

[Primary source](<https://openreview.net/forum?id=JWWpV4StVf>) · [Venue page](<https://icml.cc/virtual/2026/poster/64813>) · [PDF](<https://openreview.net/pdf?id=JWWpV4StVf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; T5 — Stability, curvature and edge-of-stability dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Introduces per-parameter adaptive momentum and cubic damping variants of momentum SGD and Adam; evaluates BERT, GPT-2, and ViT.

**Training dynamics relevance:** Introduces per-parameter adaptive momentum and cubic damping variants of momentum SGD and Adam; evaluates BERT, GPT-2, and ViT.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Momentum; nonlinear damping.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Adaptive Preconditioners Trigger Loss Spikes in Adam

**ICML 2026 · Accept (regular)** · Zhiwei Bai; Zhangchen Zhou; Jiajie Zhao; Xiaolong Li; Zhiyu li; Feiyu Xiong; Hongkang Yang; Yaoyu Zhang; Zhi-Qin John Xu

[Primary source](<https://openreview.net/forum?id=STWQoscanw>) · [Venue page](<https://icml.cc/virtual/2026/poster/63930>) · [PDF](<https://openreview.net/pdf?id=STWQoscanw>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T5 — Stability, curvature and edge-of-stability dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Explains Adam loss spikes through failure of the second-moment preconditioner to track instantaneous squared gradients; tests include large Transformers.

**Training dynamics relevance:** Explains Adam loss spikes through failure of the second-moment preconditioner to track instantaneous squared gradients; tests include large Transformers.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Second-moment timescale; instantaneous curvature; loss spikes.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Adaptive Sharpness-Aware Minimization with a Polyak-type Step size: A Theory-Grounded Scheduler

**ICML 2026 · Accept (regular)** · Dimitris Oikonomou; Nicolas Loizou

[Primary source](<https://openreview.net/forum?id=On2B3By7PT>) · [Venue page](<https://icml.cc/virtual/2026/poster/64318>) · [PDF](<https://openreview.net/pdf?id=On2B3By7PT>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Training dynamics relevance:** Derives adaptive Polyak-style schedules for SAM and compares them with tuned schedules.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Polyak step size; SAM perturbation; stochasticity.

**Training qualification:** The strongest rates are for convex/strongly convex objectives; stochastic bounds include a residual neighborhood.

**Evidence:** Official accepted-paper title and abstract.

### Advancing SVD-based LLM Compression via Layer-Wise Error Model Search

**ICML 2026 · Accept (regular)** · Moritz Thoma; Maximilian Groezinger; Maximilian Forstenhäusler; Emad Aghajanzadeh; Manoj Rohit Vemparala; Christos Anagnostopoulos; Pierpaolo Mori; Nael Fasfous; Alexander Frickenstein; Daniel Mueller-Gritschneder; Ulf Schlichtmann

[Primary source](<https://openreview.net/forum?id=IjIgNPFuCt>) · [Venue page](<https://icml.cc/virtual/2026/poster/64908>) · [PDF](<https://openreview.net/pdf?id=IjIgNPFuCt>)

**Topics:** Matrix computation; Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X6 — Matrix and tensor methods for compression.

**Quantity:** Fisher-aware SVD factors and global rank allocation.

**Computational idea:** Use token-wise KFAC statistics to reduce rank collapse, then search ranks using a layerwise error model and integer programming.

**Scope:** Deep learning. **Qualification:** Curvature and end-to-end error models are approximations.

**Optimizer relevance:** LLM compression: KFAC-SVD uses token-wise statistics to address rank-deficient Fisher estimates, paired with layer-wise error modeling for rank allocation.

**Evidence:** Official accepted-paper title and abstract.

### AGZO: Activation-Guided Zeroth-Order Optimization for LLM Fine-Tuning

**ICML 2026 · Accept (regular)** · Wei LIN; Yining Jiang; Qingyu Song; Qiao Xiang; Hong Xu

[Primary source](<https://openreview.net/forum?id=zfVxpXEZti>) · [Venue page](<https://icml.cc/virtual/2026/poster/60499>) · [PDF](<https://openreview.net/pdf?id=zfVxpXEZti>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** AGZO restricts zeroth-order perturbations to activation-informed low-rank subspaces computed during forward passes.

**Evidence:** Official accepted-paper title and abstract.

### AI Engram: In Search of Memory Traces in Artificial Intelligence

**ICML 2026 · Accept (spotlight)** · Jea Kwon; Dong-Kyum Kim; Jiwon Kim; Yonghyun Kim; Woong Kook; MEEYOUNG CHA

[Primary source](<https://openreview.net/forum?id=QZO3oby12w>) · [Venue page](<https://icml.cc/virtual/2026/oral/71045>) · [PDF](<https://openreview.net/pdf?id=QZO3oby12w>)

**Topics:** Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations.

**Optimizer relevance:** Theoretical connection: relates memory-trace identification to Fisher projections and natural gradients under K-FAC plus isotropic output curvature; the estimator itself uses input statistics.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2606.14997>): Section 6: K-FAC/isotropic-curvature interpretation and its limitations Targeted check recorded in the earlier project catalog; not a complete paper review.

### An Embarrassingly Simple Way to Optimize Orthogonal Matrices at Scale

**ICML 2026 · Accept (regular)** · Adrián Javaloy; Antonio Vergari

[Primary source](<https://openreview.net/forum?id=rlvnG8oKmN>) · [Venue page](<https://icml.cc/virtual/2026/poster/61285>) · [PDF](<https://openreview.net/pdf?id=rlvnG8oKmN>)

**Topics:** Manifold; Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods; M1 — General manifold algorithms and convergence theory.

**Optimizer relevance:** POGO is a scalable, GPU-friendly optimizer for orthogonal matrices; an adjacent numerical building block, with LLM relevance not established by the abstract.

**Manifold relevance:** POGO improves Landing-style optimization with adaptive optimizers and five matrix products. The abstract reports effective practical orthogonality; do not interpret this as an exact-feasibility theorem for every iterate.

**Geometry:** Orthogonal matrices. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/adrianjav/pogo.>). Links extracted from the accepted abstract; code was not tested.

### An Exploration of Non-Euclidean Gradient Descent: Muon and its Many Variants

**ICML 2026 · Accept (regular)** · Michael Crawshaw; Chirag Modi; Mingrui Liu; Robert Gower

[Primary source](<https://openreview.net/forum?id=O5xoqSmNzc>) · [Venue page](<https://icml.cc/virtual/2026/poster/64390>) · [PDF](<https://openreview.net/pdf?id=O5xoqSmNzc>)

**Topics:** Optimizer; Training dynamics.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Systematically varies layer norm aggregation and normalization; introduces MuonMax and Momo variants with improved hyperparameter robustness.

**Training dynamics relevance:** Systematically varies layer norm aggregation and normalization; introduces MuonMax and Momo variants with improved hyperparameter robustness.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Layer-norm aggregation; update normalization; tuning robustness.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Balanced LoRA: Removing Parameter Invariance to Accelerate Convergence

**ICML 2026 · Accept (regular)** · Valérie Castin; Kimia Nadjahi; Pierre Ablin; Gabriel Peyré

[Primary source](<https://openreview.net/forum?id=kHInw3cjCP>) · [Venue page](<https://icml.cc/virtual/2026/poster/62055>) · [PDF](<https://openreview.net/pdf?id=kHInw3cjCP>)

**Topics:** Manifold; Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; M2 — Manifold-based LLM training and low-rank adaptation.

**Optimizer relevance:** BaLoRA balances low-rank factors to remove parameterization-related ill-conditioning and accelerate fine-tuning.

**Manifold relevance:** BaLoRA projects factor pairs onto a balanced manifold while preserving their product, improving conditioning and adapter convergence.

**Geometry:** Balanced low-rank factor manifold. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### Balancing Learning Rates Across Layers: Exact Two-Step Dynamics and Optimal Scaling in Linear Neural Networks

**ICML 2026 · Accept (regular)** · Tianyu Pang; Vignesh Kothapalli; Shenyang Deng; Haohui Wang; Dawei Zhou; Yaoqing Yang

[Primary source](<https://openreview.net/forum?id=4vztmTrGhd>) · [Venue page](<https://icml.cc/virtual/2026/poster/66301>) · [PDF](<https://openreview.net/pdf?id=4vztmTrGhd>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer.

**Training dynamics relevance:** Derives one- and two-step linear-network dynamics showing when unequal layer rates help and when balanced rates become optimal.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Layer-wise learning rates; initialization; early training steps.

**Training qualification:** The exact/surrogate results concern early steps of two- and three-layer linear networks.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/TDCSZ327/Layer-Balancing>). Links extracted from the accepted abstract; code was not tested.

### BAS: Bridging Adam and SignSGD for Memory-Efficient LLM Training

**ICML 2026 · Accept (regular)** · Yijie Zhou; Mingliang Zhang; Jiaqi Zhang; Xunliang Cai; Shi Pu

[Primary source](<https://openreview.net/forum?id=Agiagru6BM>) · [Venue page](<https://icml.cc/virtual/2026/poster/65735>) · [PDF](<https://openreview.net/pdf?id=Agiagru6BM>)

**Topics:** Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers.

**Optimizer relevance:** BAS uses block-scaled sign updates and compressed momentum, aiming to inherit AdamW hyperparameters with much smaller optimizer states.

**Evidence:** Official accepted-paper title and abstract.

### Beyond Euclidean Clipping: Overcoming Exploration Collapse in LLM RL via Riemannian Isometric Policy Optimization

**ICML 2026 · Accept (regular)** · Zhicheng Cai; Xinyuan Guo; Hanlin Wu; Mingxuan Wang; Wei-Ying Ma; Ya-Qin Zhang; Hao Zhou

[Primary source](<https://openreview.net/forum?id=nSRbKvrmsH>) · [Venue page](<https://icml.cc/virtual/2026/poster/61727>) · [PDF](<https://openreview.net/pdf?id=nSRbKvrmsH>)

**Topics:** Manifold; Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; M3 — Applications that explicitly optimize or solve problems on manifolds.

**Optimizer relevance:** RIPO uses the Riemannian geometry of policy distributions to reformulate clipping for LLM reinforcement learning and mitigate exploration collapse.

**Manifold relevance:** RIPO reformulates policy clipping to obtain isometric policy updates and mitigate exploration collapse in LLM reinforcement learning; a policy-optimization application.

**Geometry:** Riemannian geometry of policy distributions. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### Can Muon Fine-tune Adam-Pretrained Models?

**ICML 2026 · Accept (regular)** · Xingyu Qu; Peigeng Huang; Samuel Horváth

[Primary source](<https://openreview.net/forum?id=NKKwTEYdAm>) · [Venue page](<https://icml.cc/virtual/2026/poster/64467>) · [PDF](<https://openreview.net/pdf?id=NKKwTEYdAm>)

**Topics:** Optimizer; Training dynamics.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Studies Adam-to-Muon optimizer mismatch during fine-tuning and how restricting update strength with LoRA mitigates it.

**Training dynamics relevance:** Studies Adam-to-Muon optimizer mismatch during fine-tuning and how restricting update strength with LoRA mitigates it.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Pretraining/fine-tuning optimizer mismatch; update strength.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/XingyuQu/muon-finetune>). Links extracted from the accepted abstract; code was not tested.

### CompleteP for RL: Maintaining Feature Learning When Scaling Deep Reinforcement Learning

**ICML 2026 · Accept (regular)** · Adam Lee; M Ganesh Kumar; Blake Bordelon; Cengiz Pehlevan

[Primary source](<https://openreview.net/forum?id=3uXAGWqCny>) · [Venue page](<https://icml.cc/virtual/2026/poster/66419>) · [PDF](<https://openreview.net/pdf?id=3uXAGWqCny>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer.

**Training dynamics relevance:** Compares rich CompleteP and lazy NTK parameterizations for hyperparameter transfer and compute efficiency in deep RL.

**Training study context:** Reinforcement learning.

**Hyperparameters / scaling axes:** Width/depth parameterization; learning rate; model size.

**Training qualification:** Evidence is from control agents with nonstationary data, rather than autoregressive pretraining.

**Evidence:** Official accepted-paper title and abstract.

### Conflicting Biases at the Edge of Stability: Norm versus Sharpness Regularization

**ICML 2026 · Accept (regular)** · Maria Matveev; Vit Fojtik; Hung-Hsu Chou; Gitta Kutyniok; Johannes Maly

[Primary source](<https://openreview.net/forum?id=6eI4YHFyON>) · [Venue page](<https://icml.cc/virtual/2026/poster/66129>) · [PDF](<https://openreview.net/pdf?id=6eI4YHFyON>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Shows that learning rate trades off norm and sharpness biases, and neither alone guarantees best generalization.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Learning rate; parameter norm; sharpness.

**Training qualification:** The formal counterexample uses diagonal linear regression.

**Evidence:** Official accepted-paper title and abstract.

### Controlled LLM Training on Spectral Sphere

**ICML 2026 · Accept (spotlight)** · Tian Xie; Haoming Luo; Haoyu Tang; Hu Yiwen; Jason Liu; Qingnan Ren; Yang Wang; Xin Zhao; Rui Yan; Bing Su; Chong Luo; Baining Guo

[Primary source](<https://openreview.net/forum?id=5kTn1c3vtt>) · [Venue page](<https://icml.cc/virtual/2026/poster/66212>) · [PDF](<https://openreview.net/pdf?id=5kTn1c3vtt>)

**Topics:** Manifold; Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; M4 — Related constrained and geometry-aware optimization.

**Optimizer relevance:** Spectral Sphere Optimizer (SSO) constrains both weights and updates, linking optimizer design to maximal-update parameterization; evaluates dense, MoE, and very deep LLMs.

**Manifold relevance:** SSO derives constrained steepest-descent updates for stable LLM training. A spectral-norm sphere need not be a globally smooth Riemannian manifold; keep it distinct from Stiefel optimization.

**Geometry:** Spectral-norm sphere constraints on weights and updates. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

### Convergence Analysis of the Lion Optimizer in Centralized and Distributed Settings

**ICML 2026 · Accept (regular)** · Wei Jiang; Mao Xu; Wenhao Yang; Yibo Wang; Zechao Li; Lijun Zhang

[Primary source](<https://openreview.net/forum?id=32NvV5zixD>) · [Venue page](<https://icml.cc/virtual/2026/poster/66516>) · [PDF](<https://openreview.net/pdf?id=32NvV5zixD>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

**Optimizer relevance:** Convergence and variance-reduction theory for Lion in centralized and distributed settings, including communication-efficient sign compression.

**Evidence:** Official accepted-paper title and abstract.

### Convergence of Steepest Descent and Adam under Non-Uniform Smoothness

**ICML 2026 · Accept (regular)** · Sharan Vaswani; Yifan Sun; Reza Babanezhad

[Primary source](<https://openreview.net/forum?id=vwTTp11PTD>) · [Venue page](<https://icml.cc/virtual/2026/poster/60861>) · [PDF](<https://openreview.net/pdf?id=vwTTp11PTD>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

**Optimizer relevance:** Convergence guarantees for steepest descent and deterministic diagonal Adam/RMSProp variants under non-uniform smoothness and additional structural assumptions.

**Evidence:** Official accepted-paper title and abstract.

### Convergence Rate Analysis of the AdamW-Style Shampoo: Unifying One-Sided and Two-Sided Preconditioning

**ICML 2026 · Accept (regular)** · Huan Li; Yiming Dong; Zhouchen Lin

[Primary source](<https://openreview.net/forum?id=gvWsViQBYB>) · [Venue page](<https://icml.cc/virtual/2026/poster/62404>) · [PDF](<https://openreview.net/pdf?id=gvWsViQBYB>)

**Topics:** Optimizer.

**Categories:** B — Shampoo, structured curvature, and matrix-function computation.

**Optimizer relevance:** Convergence analysis of AdamW-style Shampoo unifies one-sided and two-sided matrix preconditioning.

**Evidence:** Official accepted-paper title and abstract.

### CrispEdit: Low-Curvature Projections for Scalable Non-Destructive LLM Editing

**ICML 2026 · Accept (regular)** · Zarif Ikram; Arad Firouzkouhi; Stephen Tu; Mahdi Soltanolkotabi; Paria Rashidinejad

[Primary source](<https://openreview.net/forum?id=gTHlB3WK0l>) · [Venue page](<https://icml.cc/virtual/2026/poster/62453>) · [PDF](<https://openreview.net/pdf?id=gTHlB3WK0l>)

**Topics:** Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations.

**Optimizer relevance:** LLM editing: projects edits into low-curvature capability-preserving subspaces using K-FAC and a matrix-free projector.

**Evidence:** Official accepted-paper title and abstract.

### CurvZO: Adaptive Curvature-Guided Sparse Zeroth-Order Optimization for Efficient LLM Fine-Tuning

**ICML 2026 · Accept (regular)** · Shuo Wang; Ziyu Chen; Ming Tang

[Primary source](<https://openreview.net/forum?id=L35b2JZ8gS>) · [Venue page](<https://icml.cc/virtual/2026/poster/64669>) · [PDF](<https://openreview.net/pdf?id=L35b2JZ8gS>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** CurvZO uses online curvature signals from scalar feedback to guide sparse coordinate sampling and the perturbation budget.

**Evidence:** Official accepted-paper title and abstract.

### DASH: Faster Shampoo via Batched Block Preconditioning and Efficient Inverse-Root Solvers

**ICML 2026 · Accept (regular)** · Ionut-Vlad Modoranu; Philip Zmushko; Erik Schultheis; Mher Safaryan; Dan Alistarh

[Primary source](<https://openreview.net/forum?id=ujeyxKwTGM>) · [Venue page](<https://icml.cc/virtual/2026/poster/60988>) · [PDF](<https://openreview.net/pdf?id=ujeyxKwTGM>)

**Topics:** Matrix computation; Optimizer.

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X1 — Matrix functions, roots and matrix geometry.

**Quantity:** Shampoo inverse-root preconditioners.

**Computational idea:** Batch preconditioner blocks into tensors; use Newton-DB iteration and Chebyshev approximations for inverse roots.

**Scope:** Deep learning. **Qualification:** Accuracy and convergence depend on scaling, damping and solver choice.

**Optimizer relevance:** DASH accelerates Distributed Shampoo through batched preconditioner blocks and faster inverse-root algorithms; directly relevant to practical structured preconditioning.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2602.02016v1>): Sections 2-4 and Appendix A; batched blocks, Newton-Denman-Beavers, scaling and Chebyshev inverse roots. Preprint v1 reports different headline timing from the accepted abstract; the catalog deliberately does not merge these speedup figures.

**Code links listed by authors:** [Repository](<https://github.com/IST-DASLab/DASH.>). Links extracted from the accepted abstract; code was not tested.

### Decoupling Variance and Scale-Invariant Updates in Adaptive Gradient Descent for Unified Vector and Matrix Optimization

**ICML 2026 · Accept (regular)** · Zitao Song; Cedar Site Bai; Zhe Zhang; Brian Bullins; David Gleich

[Primary source](<https://openreview.net/forum?id=bCxkeiNGxZ>) · [Venue page](<https://icml.cc/virtual/2026/poster/62986>) · [PDF](<https://openreview.net/pdf?id=bCxkeiNGxZ>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

**Optimizer relevance:** DeVA separates variance adaptation from scale-invariant updates to connect Adam-style vector adaptation with matrix spectral optimization.

**Evidence:** Official accepted-paper title and abstract.

### Delving into Muon and Beyond: Deep Analysis and Extensions

**ICML 2026 · Accept (spotlight)** · Xianbiao Qi; Marco Chen; Jiaquan Ye; Yelin He; Rong Xiao

[Primary source](<https://openreview.net/forum?id=xUQ0Gw11NL>) · [Venue page](<https://icml.cc/virtual/2026/poster/60694>) · [PDF](<https://openreview.net/pdf?id=xUQ0Gw11NL>)

**Topics:** Optimizer; Training dynamics.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Studies Muon and related spectral-power transformations, including RMS-normalized variants and SVD-free computation; examines when orthogonalization helps.

**Training dynamics relevance:** Studies Muon and related spectral-power transformations, including RMS-normalized variants and SVD-free computation; examines when orthogonalization helps.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Spectral-power normalization; optimizer choice.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Dichotomy of Feature Learning and Unlearning: Fast-Slow Analysis on Neural Networks with Stochastic Gradient Descent

**ICML 2026 · Accept (regular)** · Shota Imai; Sota Nishiyama; Masaaki Imaizumi

[Primary source](<https://openreview.net/forum?id=wg02GN1ygj>) · [Venue page](<https://icml.cc/virtual/2026/poster/60792>) · [PDF](<https://openreview.net/pdf?id=wg02GN1ygj>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** A fast-slow analysis explains when feature alignment develops and is subsequently lost during training.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Output-layer initialization; width; batch size; training duration.

**Training qualification:** The effect is population-level feature unlearning in an infinite-width two-layer model, not ordinary finite-sample overfitting.

**Evidence:** Official accepted-paper title and abstract.

### Do We Need Adam? Surprisingly Strong and Sparse Reinforcement Learning with SGD in LLMs

**ICML 2026 · Accept (spotlight)** · Sagnik Mukherjee; Lifan Yuan; Pavan Jayasinha; Dilek Hakkani-Tür; Hao Peng

[Primary source](<https://openreview.net/forum?id=z31fdV4WRu>) · [Venue page](<https://icml.cc/virtual/2026/oral/71027>) · [PDF](<https://openreview.net/pdf?id=z31fdV4WRu>)

**Topics:** Optimizer; Training dynamics.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Compares SGD and AdamW for LLM reinforcement learning; finds SGD competitive with highly sparse updates in the tested RLVR settings.

**Training dynamics relevance:** Compares SGD and AdamW for LLM reinforcement learning; finds SGD competitive with highly sparse updates in the tested RLVR settings.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Adam versus SGD; RL tuning.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### DP-KFC: Data-Free Preconditioning for Privacy-Preserving Deep Learning

**ICML 2026 · Accept (regular)** · Marc Molina Van den bosch; Riccardo Taiello; Albert Aillet; Andrea Protani; Miguel Angel Gonzalez Ballester; Luigi Serio

[Primary source](<https://openreview.net/forum?id=Z6HxJqAzbp>) · [Venue page](<https://icml.cc/virtual/2026/poster/63209>) · [PDF](<https://openreview.net/pdf?id=Z6HxJqAzbp>)

**Topics:** Matrix computation; Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** KFAC curvature factors without private data.

**Computational idea:** Probe architectural sensitivity with structured synthetic noise and approximate input correlations from modality statistics.

**Scope:** Deep learning. **Qualification:** A data-free structured Fisher approximation, not recovery of arbitrary data-dependent curvature.

**Optimizer relevance:** Direct KFAC optimizer: constructs preconditioners from structured synthetic noise for differentially private learning. The abstract does not establish LLM-scale evaluation.

**Evidence:** Official accepted-paper title and abstract.

### Dropout Universality: Scaling Laws and Optimal Scheduling at the Edge-of-Chaos

**ICML 2026 · Accept (regular)** · Lucas Fernandez-Sarmiento

[Primary source](<https://openreview.net/forum?id=FoDU47u2jk>) · [Venue page](<https://icml.cc/virtual/2026/poster/65205>) · [PDF](<https://openreview.net/pdf?id=FoDU47u2jk>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Analyzes how dropout changes critical signal propagation and motivates front-loaded dropout schedules.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Dropout strength and schedule; depth; initialization.

**Training qualification:** Mean-field critical exponents and the MLP/ViT experiments have different scopes; LLM transfer is not established.

**Evidence:** Official accepted-paper title and abstract.

### DualOptim+: Bridging Shared and Decoupled Optimizer States for Better Machine Unlearning in Large Language Models

**ICML 2026 · Accept (regular)** · Xuyang Zhong; Qizhang Li; Yiwen Guo; Chen Liu

[Primary source](<https://openreview.net/forum?id=xGfnQajGPQ>) · [Venue page](<https://icml.cc/virtual/2026/poster/60714>) · [PDF](<https://openreview.net/pdf?id=xGfnQajGPQ>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

**Optimizer relevance:** DualOptim+ separates shared and objective-specific optimizer states to handle forgetting/retention conflicts in LLM unlearning.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/CityU-MLO/DualOptimPlus.>). Links extracted from the accepted abstract; code was not tested.

### Dynamic Regret via Discounted-to-Dynamic Reduction with Applications to Curved Losses and Adam Optimizer

**ICML 2026 · Accept (regular)** · Yan-Feng Xie; Yu-Jie Zhang; Peng Zhao; Zhi-Hua Zhou

[Primary source](<https://openreview.net/forum?id=cGOX9bOWnj>) · [Venue page](<https://icml.cc/virtual/2026/poster/62883>) · [PDF](<https://openreview.net/pdf?id=cGOX9bOWnj>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

**Optimizer relevance:** Uses dynamic-regret reductions to analyze Adam, including the roles of two discount parameters and clipped versus clip-free variants.

**Evidence:** Official accepted-paper title and abstract.

### Dynamics of neural scaling laws in random feature regression with powerlaw-distributed kernel eigenvalues

**ICML 2026 · Accept (regular)** · Jakob Kramp; Javed Lindner; Moritz Helias

[Primary source](<https://openreview.net/forum?id=Ge3VtuCvZ7>) · [Venue page](<https://icml.cc/virtual/2026/poster/65116>) · [PDF](<https://openreview.net/pdf?id=Ge3VtuCvZ7>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** A dynamical mean-field model connects spectral modes to generalization curves under gradient flow, regularization and Langevin dynamics.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Training time; weight decay; early stopping; kernel spectrum.

**Training qualification:** Results concern random-feature/GP regression and prescribed power-law spectra.

**Evidence:** Official accepted-paper title and abstract.

### ECO: Quantized Training without Full-Precision Master Weights

**ICML 2026 · Accept (regular)** · Mahdi Nikdan; Amir Zandieh; Dan Alistarh; Vahab Mirrokni

[Primary source](<https://openreview.net/forum?id=dfVm5yZZ6G>) · [Venue page](<https://icml.cc/virtual/2026/poster/62753>) · [PDF](<https://openreview.net/pdf?id=dfVm5yZZ6G>)

**Topics:** Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers.

**Optimizer relevance:** ECO removes full-precision master weights and feeds quantization error into momentum; evaluates dense and MoE language models.

**Evidence:** Official accepted-paper title and abstract.

### Efficient DP-SGD for LLMs with Randomized Clipping

**ICML 2026 · Accept (regular)** · Enayat Ullah; Sai Aparna Aketi; Devansh Gupta; Huanyu Zhang; Meisam Razaviyayn

[Primary source](<https://openreview.net/forum?id=eTO6G25Jbo>) · [Venue page](<https://icml.cc/virtual/2026/poster/62676>) · [PDF](<https://openreview.net/pdf?id=eTO6G25Jbo>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

**Optimizer relevance:** DP-SGD-RC uses randomized per-example gradient-norm estimation to reduce clipping overhead in private LLM fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

### Enhancing LLM Training via Spectral Clipping

**ICML 2026 · Accept (regular)** · Xiaowen Jiang; Andrei Semenov; Sebastian Stich

[Primary source](<https://openreview.net/forum?id=RF1YUA8plS>) · [Venue page](<https://icml.cc/virtual/2026/poster/64066>) · [PDF](<https://openreview.net/pdf?id=RF1YUA8plS>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

**Optimizer relevance:** SPECTRA applies post-update spectral clipping and optional gradient spectral clipping across base optimizers; distinct from the spike-aware Spectra optimizer in group C.

**Evidence:** Official accepted-paper title and abstract.

### Escaping the Subspace Trap: The Role of Optimizer Geometry in Model Width Expansion

**ICML 2026 · Accept (regular)** · Jiabei Chen; Haoyu Wang; Yang Yu; Yao Xu; Liangdong Wang; Guang Liu; Shizhu He; Jun Zhao; Kang Liu

[Primary source](<https://openreview.net/forum?id=RUgiEJJ9Fo>) · [Venue page](<https://icml.cc/virtual/2026/poster/64041>) · [PDF](<https://openreview.net/pdf?id=RUgiEJJ9Fo>)

**Topics:** Optimizer.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity.

**Optimizer relevance:** Studies how optimizer update geometry affects escape from initialization-aligned subspaces after model width expansion.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/A-PolarBear/Model-Width-Expansion.>). Links extracted from the accepted abstract; code was not tested.

### Evolution Strategies at Scale: LLM Fine-Tuning Beyond Reinforcement Learning

**ICML 2026 · Accept (regular)** · Xin Qiu; Yulu Gan; Conor Hayes; Qiyao Liang; Yinggan XU; Roberto Dailey; Elliot Meyerson; Babak Hodjat; Risto Miikkulainen

[Primary source](<https://openreview.net/forum?id=i0P4ew9GpS>) · [Venue page](<https://icml.cc/virtual/2026/poster/62279>) · [PDF](<https://openreview.net/pdf?id=i0P4ew9GpS>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** Demonstrates full-parameter, billion-scale LLM fine-tuning with evolution strategies as an alternative to backpropagation-based RL.

**Evidence:** Official accepted-paper title and abstract.

### Evolution Strategies at the Hyperscale

**ICML 2026 · Accept (regular)** · Bidipta Sarkar; Mattie Fellows; Juan Duque; Alistair Letcher; Antonio León Villares; Anya Sims; Clarisse Wibault; Dmitry Samsonov; Dylan Cope; Jarek Liesen; Kang Li; Lukas Seier; Theo Wolf; Uljad Berdica; Valentin Mohl; Alexander D. Goldie; Aaron Courville; Karin Sevegnani; Shimon Whiteson; Jakob Foerster

[Primary source](<https://openreview.net/forum?id=bfVJ4GsHrO>) · [Venue page](<https://icml.cc/virtual/2026/poster/62943>) · [PDF](<https://openreview.net/pdf?id=bfVJ4GsHrO>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** EGGROLL uses low-rank perturbations to make evolution strategies efficient at billion-parameter scale; includes language pretraining and post-training.

**Evidence:** Official accepted-paper title and abstract.

### Exploiting weight-space symmetries for approximating curvature

**ICML 2026 · Accept (regular)** · Artem Artemev; Rui Xia; Benjamin M. Boyd; Youjing Yu; Felix Dangel; Guillaume Hennequin; Alberto Bernacchia

[Primary source](<https://openreview.net/forum?id=yiq2tZojBK>) · [Venue page](<https://icml.cc/virtual/2026/poster/60589>) · [PDF](<https://openreview.net/pdf?id=yiq2tZojBK>)

**Topics:** Optimizer.

**Categories:** B — Shampoo, structured curvature, and matrix-function computation.

**Optimizer relevance:** Constructs structured curvature estimates by averaging over weight-space symmetries; recovers Shampoo/Muon-like estimates for a particular symmetry choice and evaluates a small language model.

**Evidence:** Official accepted-paper title and abstract.

### FedFit: Federated Dynamic Sparse Training via Fisher Information scoring

**ICML 2026 · Accept (regular)** · Meng Bi; Hong Huang; Jinlong Song; Charles Wang; Chengming Hu; Xi Chen; Ting Yu; Xue Liu

[Primary source](<https://openreview.net/forum?id=NhW0m7BLPG>) · [Venue page](<https://icml.cc/virtual/2026/poster/64435>) · [PDF](<https://openreview.net/pdf?id=NhW0m7BLPG>)

**Topics:** Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations.

**Optimizer relevance:** Federated sparse training: uses K-FAC-based Fisher scoring for sparse structure adjustment. This is a specialized application, not a general LLM optimizer.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://openreview.net/attachment?id=NhW0m7BLPG&name=originally_submitted_PDF>): Appendix B.2: K-FAC approximation used for Fisher scoring Targeted check recorded in the earlier project catalog; not a complete paper review.

**Code links listed by authors:** [Repository](<https://github.com/Serena-28/Fedfit.git.>). Links extracted from the accepted abstract; code was not tested.

### FlashOptim: Memory Efficient Optimizers for Large-Scale Training

**ICML 2026 · Accept (spotlight)** · Jose Javier Gonzalez Ortiz; Abhay Gupta; Christopher Rinard; Davis Blalock

[Primary source](<https://openreview.net/forum?id=Wfe1iJocjF>) · [Venue page](<https://icml.cc/virtual/2026/poster/63497>) · [PDF](<https://openreview.net/pdf?id=Wfe1iJocjF>)

**Topics:** Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers.

**Optimizer relevance:** FlashOptim combines master-weight splitting and quantized optimizer states to reduce memory for SGD, AdamW, and Lion while preserving their APIs.

**Evidence:** Official accepted-paper title and abstract.

### Flatland: The Adventures of Gradient Descent with Large Step Sizes

**ICML 2026 · Accept (regular)** · Leonardo Galli; Curtis Fox; Wiebke Bartolomaeus; Mark Schmidt; Holger Rauhut

[Primary source](<https://openreview.net/forum?id=NpSI4x2vBS>) · [Venue page](<https://icml.cc/virtual/2026/poster/64420>) · [PDF](<https://openreview.net/pdf?id=NpSI4x2vBS>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Training dynamics relevance:** Develops adaptive large-step methods and studies self-stabilization beyond classical monotone descent.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Large learning rates; local smoothness; sharpness.

**Training qualification:** Global flatness alone need not improve generalization; algorithm guarantees depend on local regularity assumptions.

**Evidence:** Official accepted-paper title and abstract.

### FOAM: Blocked State Folding for Memory-Efficient LLM Training

**ICML 2026 · Accept (regular)** · Ziqing Wen; Jiahuan Wang; ping luo; Dongsheng Li; Tao Sun

[Primary source](<https://openreview.net/forum?id=k7XzObg9Hy>) · [Venue page](<https://icml.cc/virtual/2026/poster/62070>) · [PDF](<https://openreview.net/pdf?id=k7XzObg9Hy>)

**Topics:** Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers.

**Optimizer relevance:** Folded Optimizer with Approximate Moment (FOAM) compresses states through block means with residual correction; distinct from Shampoo-damping FOAM in group B.

**Evidence:** Official accepted-paper title and abstract.

### FOAM: Frequency and Operator-Error Based Adaptive Damping Method for Reducing Staleness-Oriented Error for Shampoo

**ICML 2026 · Accept (regular)** · Kyunghun Nam; Sumyeong Ahn

[Primary source](<https://openreview.net/forum?id=ZwFJbTzJP9>) · [Venue page](<https://icml.cc/virtual/2026/poster/63117>) · [PDF](<https://openreview.net/pdf?id=ZwFJbTzJP9>)

**Topics:** Matrix computation; Optimizer.

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X1 — Matrix functions, roots and matrix geometry.

**Quantity:** Stale Shampoo preconditioners.

**Computational idea:** Adapt damping and eigendecomposition frequency using an estimate of operator error from stale preconditioners.

**Scope:** Deep learning. **Qualification:** Controls a computation-versus-staleness trade-off; does not eliminate matrix decompositions entirely.

**Optimizer relevance:** Adaptive damping and eigendecomposition frequency address errors from stale Shampoo preconditioners. This FOAM differs from the state-folding FOAM in group D.

**Evidence:** Official accepted-paper title and abstract.

### From Muon to Gluon: Bridging Theory and Practice of LMO-based Optimizers for LLMs

**ICML 2026 · Accept (regular)** · Artem Riabinin; Egor Shulgin; Kaja Gruntkowska; Peter Richtarik

[Primary source](<https://openreview.net/forum?id=IelAHU5MVz>) · [Venue page](<https://icml.cc/virtual/2026/poster/64921>) · [PDF](<https://openreview.net/pdf?id=IelAHU5MVz>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

**Optimizer relevance:** Gluon supplies a layer-wise LMO framework and refined smoothness assumptions connecting practical Muon/Scion updates to convergence theory.

**Evidence:** Official accepted-paper title and abstract.

### From Optimization to Generalization under Heavy-Tailed Data: The Role of Gradient Clipping

**ICML 2026 · Accept (regular)** · Aleksandr Shestakov; Martin Takac; Eduard Gorbunov

[Primary source](<https://openreview.net/forum?id=FGHVEJ2Jz9>) · [Venue page](<https://icml.cc/virtual/2026/poster/65262>) · [PDF](<https://openreview.net/pdf?id=FGHVEJ2Jz9>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Separates data-sampling and optimization noise to explain why clipping helps under heavy-tailed data.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Step size; clipping schedule; dataset size; tail index.

**Training qualification:** Generalization results use strongly convex smooth objectives; infinite-data noise and finite-dataset moments are distinct.

**Evidence:** Official accepted-paper title and abstract.

### General Analysis of LMO-based Optimizers: Beyond Bounded Variance

**ICML 2026 · Accept (regular)** · Egor Shulgin; Mohamed Awad; Peter Richtarik; Eduard Gorbunov

[Primary source](<https://openreview.net/forum?id=s0Q8nVsrMu>) · [Venue page](<https://icml.cc/virtual/2026/poster/61267>) · [PDF](<https://openreview.net/pdf?id=s0Q8nVsrMu>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

**Optimizer relevance:** Unified momentum-LMO convergence analysis under expected smoothness, covering Muon and sign-based directions with batch-size/momentum scaling.

**Evidence:** Official accepted-paper title and abstract.

### Geometric Convergence of Gauss–Newton for Neural Networks: Riemannian Geometry and Adaptive Damping

**ICML 2026 · Accept (regular)** · Semih Cayci

[Primary source](<https://openreview.net/forum?id=IoGEXDFVEb>) · [Venue page](<https://icml.cc/virtual/2026/poster/64891>) · [PDF](<https://openreview.net/pdf?id=IoGEXDFVEb>)

**Topics:** Manifold; Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; M1 — General manifold algorithms and convergence theory.

**Optimizer relevance:** Gauss-Newton convergence and adaptive damping theory for neural networks under over- and underparameterization; adjacent second-order theory.

**Manifold relevance:** Relates parameter-space Gauss-Newton flow to Riemannian gradient flow and proves conditioning-independent convergence under stated output-scaling and regularity assumptions.

**Geometry:** Neural-network function-space submanifold. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### Geometry-Preserving Orthonormal Initialization for Low-Rank Adaptation in RLVR

**ICML 2026 · Accept (regular)** · Ruijia Zhang; Jiacheng Zhu; Hanqing Zhu; Laixi Shi

[Primary source](<https://openreview.net/forum?id=Xo95FS2GTK>) · [Venue page](<https://icml.cc/virtual/2026/poster/63355>) · [PDF](<https://openreview.net/pdf?id=Xo95FS2GTK>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

**Optimizer relevance:** Derives geometry-preserving orthonormal LoRA initialization for RLVR, leading to LoRA-RLPO and LoRA-RLMO.

**Evidence:** Official accepted-paper title and abstract.

### Gradient Descent with Large Step Size Restores Symmetry in Deep Linear Networks with Multi-Pathway

**ICML 2026 · Accept (regular)** · Hee-Sung Kim; Sungyoon Lee

[Primary source](<https://openreview.net/forum?id=CVXqBkLF5y>) · [Venue page](<https://icml.cc/virtual/2026/poster/65550>) · [PDF](<https://openreview.net/pdf?id=CVXqBkLF5y>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Shows that discrete large-step GD can reverse gradient-flow symmetry breaking and redistribute features across network paths.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Large step size; depth; number of pathways.

**Training qualification:** The theory uses multipath deep linear networks.

**Evidence:** Official accepted-paper title and abstract.

### Gradient Flow Dynamics and Implicit Bias of Diagonal Linear Networks under Infinitesimal Initialization

**ICML 2026 · Accept (regular)** · Jiajie Zhao; Jianxing Wang; Junjie Yang; Zhiwei Bai; Yaoyu Zhang

[Primary source](<https://openreview.net/forum?id=IJph1t3Egr>) · [Venue page](<https://icml.cc/virtual/2026/poster/64965>) · [PDF](<https://openreview.net/pdf?id=IJph1t3Egr>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Characterizes infinitesimal-initialization dynamics and modified l1 implicit bias in diagonal linear networks.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Initialization scale; depth; gradient-flow time.

**Training qualification:** Continuous-time and vanishing-initialization limits need not describe finite-step adaptive optimizers.

**Evidence:** Official accepted-paper title and abstract.

### Gradient Smoothing: Coupling Layer-wise Updates for Improved Optimization

**ICML 2026 · Accept (regular)** · Haoming Meng; Anton Sugolov; Vardan Papyan

[Primary source](<https://openreview.net/forum?id=xOFHGE60fr>) · [Venue page](<https://icml.cc/virtual/2026/poster/60702>) · [PDF](<https://openreview.net/pdf?id=xOFHGE60fr>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

**Optimizer relevance:** Gradient Smoothing couples optimizer updates across network depth and can augment SGD, Adam, or Muon; evaluates LLM pretraining and RL post-training.

**Evidence:** Official accepted-paper title and abstract.

### GradientStabilizer: Fix the Norm, Not the Gradient

**ICML 2026 · Accept (regular)** · Tianjin Huang; Zhangyang “Atlas” Wang; Haotian Hu; Zhenyu Zhang; Gaojie Jin; Xiang Li; Li Shen; Jiaxing Shang; Tianlong Chen; Ke Li; Lu Liu; Qingsong Wen; Shiwei Liu

[Primary source](<https://openreview.net/forum?id=UZ8e5kivVf>) · [Venue page](<https://icml.cc/virtual/2026/poster/63695>) · [PDF](<https://openreview.net/pdf?id=UZ8e5kivVf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** E — Training stabilization and distributed optimization; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** GradientStabilizer preserves gradient direction but stabilizes its magnitude using running norm statistics; includes low-precision LLM training.

**Training dynamics relevance:** GradientStabilizer preserves gradient direction but stabilizes its magnitude using running norm statistics; includes low-precision LLM training.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Gradient norm; normalization; numerical precision.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### GradPower: Powering Gradients for Faster Language Model Pre-Training

**ICML 2026 · Accept (regular)** · Jinbo Wang; Mingze Wang; Jiaqi Zhang; Wei Wang; Peng Pei; Xunliang Cai; Weinan E; Lei Wu

[Primary source](<https://openreview.net/forum?id=I9pDKCWYXk>) · [Venue page](<https://icml.cc/virtual/2026/poster/64980>) · [PDF](<https://openreview.net/pdf?id=I9pDKCWYXk>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

**Optimizer relevance:** GradPower applies an elementwise sign-power transform before a base optimizer to improve language-model pretraining.

**Evidence:** Official accepted-paper title and abstract.

### Grokking Finite-Dimensional Algebra

**ICML 2026 · Accept (regular)** · Pascal Jr Tikeng Notsawo; Guillaume Dumas; Guillaume Rabusseau

[Primary source](<https://openreview.net/forum?id=5Cvh976L09>) · [Venue page](<https://icml.cc/virtual/2026/poster/66276>) · [PDF](<https://openreview.net/pdf?id=5Cvh976L09>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Studies memorization-to-generalization transitions when networks learn multiplication in finite-dimensional algebras.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Training duration; algebraic structure; implicit rank bias.

**Training qualification:** A controlled algorithmic-learning setting rather than an LLM pretraining recipe.

**Evidence:** Official accepted-paper title and abstract.

### High-Dimensional Learning Dynamics of Quantized Models with Straight-Through Estimator

**ICML 2026 · Accept (regular)** · Yuma Ichikawa; Shuhei Kashiwamura; Ayaka Sakata

[Primary source](<https://openreview.net/forum?id=bI9moH3UZw>) · [Venue page](<https://icml.cc/virtual/2026/poster/62979>) · [PDF](<https://openreview.net/pdf?id=bI9moH3UZw>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Derives high-dimensional STE dynamics and explains plateaus and sharp generalization changes induced by quantization settings.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Quantization range; bit width; training time.

**Training qualification:** The deterministic limit and fixed-point results concern the specified quantized model.

**Evidence:** Official accepted-paper title and abstract.

### Hyperparameter Transfer Laws for Non-Recurrent Multi-Path Neural Networks

**ICML 2026 · Accept (regular)** · Haosong Zhang; Shenxi Wu; Xingjian Ma; Shirui Bian; Yichi Zhang; Xi Chen; Wei Lin

[Primary source](<https://openreview.net/forum?id=Q2tAR1xDFQ>) · [Venue page](<https://icml.cc/virtual/2026/poster/64199>) · [PDF](<https://openreview.net/pdf?id=Q2tAR1xDFQ>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer.

**Optimizer relevance:** Studies effective-depth scaling rules for learning-rate transfer across non-recurrent multi-path architectures, including Transformers.

**Training dynamics relevance:** Studies effective-depth scaling rules for learning-rate transfer across non-recurrent multi-path architectures, including Transformers.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Effective depth; multipath architecture; transfer rules.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Hyperparameter Transfer with Mixture-of-Expert Layers

**ICML 2026 · Accept (regular)** · Tianze Jiang; Blake Bordelon; Cengiz Pehlevan; Boris Hanin

[Primary source](<https://openreview.net/forum?id=fD36uwJ5oV>) · [Venue page](<https://icml.cc/virtual/2026/poster/62595>) · [PDF](<https://openreview.net/pdf?id=fD36uwJ5oV>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer.

**Optimizer relevance:** Parameterization and mean-field analysis for transferring hyperparameters across MoE width, depth, expert count, and expert size.

**Training dynamics relevance:** Parameterization and mean-field analysis for transferring hyperparameters across MoE width, depth, expert count, and expert size.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Width; depth; expert count; expert size.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Inverse Depth Scaling From Most Layers Being Similar

**ICML 2026 · Accept (regular)** · Yizhou Liu; Sara Kangaslahti; Ziming Liu; Jeff Gore

[Primary source](<https://openreview.net/forum?id=CEpCpxJqAt>) · [Venue page](<https://icml.cc/virtual/2026/poster/65580>) · [PDF](<https://openreview.net/pdf?id=CEpCpxJqAt>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Relates inverse-depth loss scaling to repeated, similar residual layers and studies inefficient use of depth.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Depth; residual architecture; layer similarity.

**Training qualification:** The ensemble-averaging explanation is a proposed mechanism, not a universal proof about deep LLMs.

**Evidence:** Official accepted-paper title and abstract.

### IO-Adam: Rethinking Memory-Efficient Adaptive Optimizers from Gradient Computation

**ICML 2026 · Accept (regular)** · Yiting Chen; Zongwei Huo; Junchi Yan

[Primary source](<https://openreview.net/forum?id=z0m3EhzhOH>) · [Venue page](<https://icml.cc/virtual/2026/poster/60558>) · [PDF](<https://openreview.net/pdf?id=z0m3EhzhOH>)

**Topics:** Matrix computation; Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Adam-like first and second moments.

**Computational idea:** Track layer inputs and output gradients to estimate moments using the factorization of the weight gradient.

**Scope:** Deep learning. **Qualification:** Moment estimation differs from exact Adam; memory-performance trade-off is empirical.

**Optimizer relevance:** IO-Adam estimates moment information through layer inputs and output gradients rather than storing full parameter-wise moment tensors.

**Evidence:** Official accepted-paper title and abstract.

### KromHC: Manifold-Constrained Hyper-Connections with Kronecker-Product Residual Matrices

**ICML 2026 · Accept (regular)** · Wuyang Zhou; Yuxuan Gu; Giorgos Iacovides; Danilo Mandic

[Primary source](<https://openreview.net/forum?id=TI7Q2o6EIa>) · [Venue page](<https://icml.cc/virtual/2026/poster/63836>) · [PDF](<https://openreview.net/pdf?id=TI7Q2o6EIa>)

**Topics:** Manifold; Optimizer.

**Categories:** E — Training stabilization and distributed optimization; M4 — Related constrained and geometry-aware optimization.

**Optimizer relevance:** KromHC uses Kronecker products of small doubly stochastic matrices to enforce hyper-connection constraints efficiently; Kronecker parameterization here is not KFAC.

**Manifold relevance:** KromHC parameterizes constrained residual mixing with small factors. The Birkhoff polytope has a boundary; its use of Kronecker products is unrelated to KFAC curvature.

**Geometry:** Kronecker products of doubly stochastic factors. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/wz1119/KromHC.>). Links extracted from the accepted abstract; code was not tested.

### Learning a Zeroth-Order Optimizer for Fine-Tuning LLMs

**ICML 2026 · Accept (regular)** · Kairun Zhang; Haoyu Li; Yanjun Zhao; Yifan Sun; Huan Zhang

[Primary source](<https://openreview.net/forum?id=bRS5iwbqlC>) · [Venue page](<https://icml.cc/virtual/2026/poster/62961>) · [PDF](<https://openreview.net/pdf?id=bRS5iwbqlC>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** ZO-Finetuner learns reusable, model-specific perturbation strategies for memory-efficient zeroth-order LLM fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

### Learning Dynamics of Zeroth-Order Optimization: A Kernel Perspective

**ICML 2026 · Accept (regular)** · Zhe Li; Bicheng Ying; Zidong Liu; Haibo Yang

[Primary source](<https://openreview.net/forum?id=UTIylOfVUb>) · [Venue page](<https://icml.cc/virtual/2026/poster/63704>) · [PDF](<https://openreview.net/pdf?id=UTIylOfVUb>)

**Topics:** Optimizer; Training dynamics.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Analyzes zeroth-order learning through an empirical-NTK perspective, connecting perturbation count to kernel fidelity in LLM fine-tuning.

**Training dynamics relevance:** Analyzes zeroth-order learning through an empirical-NTK perspective, connecting perturbation count to kernel fidelity in LLM fine-tuning.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Zeroth-order perturbation count; kernel fidelity.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Learning in the Fisher Subspace: A Guided Initialization for LoRA Fine-Tuning

**ICML 2026 · Accept (regular)** · Zhi-Quan Feng; Ying-Jia Lin; Hung-Yu Kao

[Primary source](<https://openreview.net/forum?id=P76Q8Pi1E9>) · [Venue page](<https://icml.cc/virtual/2026/poster/64288>) · [PDF](<https://openreview.net/pdf?id=P76Q8Pi1E9>)

**Topics:** Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations.

**Optimizer relevance:** LoRA initialization: FILet uses a K-FAC approximation to select low-Fisher-energy directions using downstream data; it is an initialization method rather than a replacement training optimizer.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2605.01046>): Section 3.3, equations 11-13: K-FAC approximation in FILet Targeted check recorded in the earlier project catalog; not a complete paper review.

### Learning Rate Annealing Improves Tuning Robustness in Stochastic Optimization

**ICML 2026 · Accept (regular)** · Amit Attia; Tomer Koren

[Primary source](<https://openreview.net/forum?id=usZLsN3Dnv>) · [Venue page](<https://icml.cc/virtual/2026/poster/60981>) · [PDF](<https://openreview.net/pdf?id=usZLsN3Dnv>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules.

**Optimizer relevance:** Analyzes why annealing schedules improve robustness to initial learning-rate misspecification and coarse tuning grids.

**Training dynamics relevance:** Analyzes why annealing schedules improve robustness to initial learning-rate misspecification and coarse tuning grids.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Annealing; initial-rate misspecification; tuning grid.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Learning Rate Scaling across LoRA Ranks and Transfer to Full Finetuning

**ICML 2026 · Accept (regular)** · Nan Chen; Soledad Villar; Soufiane Hayou

[Primary source](<https://openreview.net/forum?id=vCAIwEJZQ6>) · [Venue page](<https://icml.cc/virtual/2026/poster/60938>) · [PDF](<https://openreview.net/pdf?id=vCAIwEJZQ6>)

**Topics:** Optimizer; Training dynamics.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer.

**Optimizer relevance:** Maximal-Update Adaptation studies learning-rate scaling across LoRA ranks and transfer from LoRA tuning to full fine-tuning.

**Training dynamics relevance:** Maximal-Update Adaptation studies learning-rate scaling across LoRA ranks and transfer from LoRA tuning to full fine-tuning.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** LoRA rank; adapter learning rate; full fine-tuning transfer.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### LiMuon: Light and Fast Muon Optimizer for Large Models

**ICML 2026 · Accept (regular)** · Feihu Huang; Yuning Luo; Songcan Chen

[Primary source](<https://openreview.net/forum?id=mf8N8PTUAa>) · [Venue page](<https://icml.cc/virtual/2026/poster/61819>) · [PDF](<https://openreview.net/pdf?id=mf8N8PTUAa>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

**Optimizer relevance:** LiMuon combines momentum variance reduction with randomized SVD for lower-memory matrix optimization; includes language-model and vision experiments.

**Evidence:** Official accepted-paper title and abstract.

### Lions and Muons: Optimization via Stochastic Frank-Wolfe under Heavy-Tailed Noise

**ICML 2026 · Accept (regular)** · Maria-Eleni Sfyraki; Jun-Kun Wang

[Primary source](<https://openreview.net/forum?id=gvroXZ0HS8>) · [Venue page](<https://icml.cc/virtual/2026/poster/62403>) · [PDF](<https://openreview.net/pdf?id=gvroXZ0HS8>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

**Optimizer relevance:** Interprets Lion and Muon with weight decay through stochastic Frank-Wolfe and derives robust variants under heavy-tailed noise.

**Evidence:** Official accepted-paper title and abstract.

### LoRA-DA: Data-Aware Initialization for Low-Rank Adaptation via Asymptotic Analysis

**ICML 2026 · Accept (regular)** · Qingyue Zhang; Chang Chu; Tianren Peng; Qi Li; Xiangyang Luo; Zhihao Jiang; Shao-Lun Huang

[Primary source](<https://openreview.net/forum?id=LvKSVUbXc9>) · [Venue page](<https://icml.cc/virtual/2026/poster/64590>) · [PDF](<https://openreview.net/pdf?id=LvKSVUbXc9>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

**Optimizer relevance:** LoRA-DA uses an asymptotic Fisher-gradient bias/variance formulation to derive data-aware low-rank initialization.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/zqy0126/LoRA-DA.>). Links extracted from the accepted abstract; code was not tested.

### LoRDO: Distributed Low-Rank Optimization with Infrequent Communication

**ICML 2026 · Accept (regular)** · Andrej Jovanović; Alex Iacob; Mher Safaryan; Ionut-Vlad Modoranu; Lorenzo Sani; Shen; Xinchi Qiu; Dan Alistarh; Nicholas Lane

[Primary source](<https://openreview.net/forum?id=TTAxB2IL2y>) · [Venue page](<https://icml.cc/virtual/2026/poster/63818>) · [PDF](<https://openreview.net/pdf?id=TTAxB2IL2y>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

**Optimizer relevance:** LoRDO combines low-rank optimizer states and infrequent synchronization, with full-rank corrections to avoid restricted subspace exploration.

**Evidence:** Official accepted-paper title and abstract.

### LOZO+: Provably Efficient Zeroth-Order Fine-Tuning via Greedy Low-Rank Subspace Selection

**ICML 2026 · Accept (regular)** · Jinjie Fang; Chengxun Jin; Tianxing Man; Yi Chang; Bin Gu

[Primary source](<https://openreview.net/forum?id=QNScXX6osL>) · [Venue page](<https://icml.cc/virtual/2026/poster/64159>) · [PDF](<https://openreview.net/pdf?id=QNScXX6osL>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** LOZO+ selects useful low-rank perturbation subspaces greedily using loss feedback rather than relying solely on random subspaces.

**Evidence:** Official accepted-paper title and abstract.

### M+Adam: Low-Precision Training via Additive–Multiplicative Optimization

**ICML 2026 · Accept (regular)** · Xiaoyuan Liang; Sebastian Loeschcke; Mads Toftrup; Anima Anandkumar

[Primary source](<https://openreview.net/forum?id=XgVv56Y829>) · [Venue page](<https://icml.cc/virtual/2026/poster/63374>) · [PDF](<https://openreview.net/pdf?id=XgVv56Y829>)

**Topics:** Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers.

**Optimizer relevance:** M+Adam combines additive and multiplicative updates to mitigate complementary rounding failures in low-precision LLM training.

**Evidence:** Official accepted-paper title and abstract.

### Mechanistic Data Attribution: Tracing the Training Origins of Interpretable LLM Units

**ICML 2026 · Accept (spotlight)** · Jianhui Chen; Yuzhang Luo; Liangming Pan

[Primary source](<https://openreview.net/forum?id=PQaxfoEcRc>) · [Venue page](<https://icml.cc/virtual/2026/poster/64259>) · [PDF](<https://openreview.net/pdf?id=PQaxfoEcRc>)

**Topics:** Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations.

**Optimizer relevance:** EKFAC application: uses EK-FAC influence estimates within attention-head parameter subspaces to trace the training origins of interpretable LLM units; includes joint query/key treatment.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2601.21996>): Section 3 and Appendix A.2-A.3: EK-FAC and joint Q/K subspaces Targeted check recorded in the earlier project catalog; not a complete paper review.

### Memory Savings at What Cost? A Study of Alternatives to Backpropagation

**ICML 2026 · Accept (regular)** · Kunjal Panchal; Sunav Choudhary; Yuriy Brun; Hui Guan

[Primary source](<https://openreview.net/forum?id=QS0ZROPx8u>) · [Venue page](<https://icml.cc/virtual/2026/poster/64148>) · [PDF](<https://openreview.net/pdf?id=QS0ZROPx8u>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** Compares zeroth-order and forward-mode methods against backpropagation including checkpointed baselines; important for evaluating actual memory/time trade-offs.

**Evidence:** Official accepted-paper title and abstract.

### Memory-Efficient LLM Pretraining via Minimalist Optimizer Design

**ICML 2026 · Accept (regular)** · Athanasios Glentis; Jiaxiang Li; Andi Han; Mingyi Hong

[Primary source](<https://openreview.net/forum?id=prvGhNz39e>) · [Venue page](<https://icml.cc/virtual/2026/poster/61469>) · [PDF](<https://openreview.net/pdf?id=prvGhNz39e>)

**Topics:** Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers.

**Optimizer relevance:** SCALE uses column-wise gradient normalization and momentum only in the output layer for minimalist, memory-efficient LLM pretraining.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/OptimAI-Lab/Minimalist_LLM_Pretraining.>). Links extracted from the accepted abstract; code was not tested.

### Memory-Efficient LLM Training with Dynamic Sparsity: From Stability to Practical Scaling

**ICML 2026 · Accept (regular)** · Qiao Xiao; Boqian Wu; Patrik Okanovic; Tomasz Sternal; Maurice Keulen; Elena Mocanu; Mykola Pechenizkiy; Decebal Constantin Mocanu; Torsten Hoefler

[Primary source](<https://openreview.net/forum?id=ivVPgBZewP>) · [Venue page](<https://icml.cc/virtual/2026/poster/62187>) · [PDF](<https://openreview.net/pdf?id=ivVPgBZewP>)

**Topics:** Optimizer; Training dynamics.

**Categories:** E — Training stabilization and distributed optimization; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Optimizer relevance:** SMET addresses cold-start instability of newly regrown sparse parameters with optimizer warm-up, density-aware learning-rate scaling, and sparse state storage.

**Training dynamics relevance:** SMET addresses cold-start instability of newly regrown sparse parameters with optimizer warm-up, density-aware learning-rate scaling, and sparse state storage.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Sparsity; regrowth; optimizer warm-up.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/QiaoXiao7282/SMET.>). Links extracted from the accepted abstract; code was not tested.

### mHC: Manifold-Constrained Hyper-Connections

**ICML 2026 · Accept (spotlight)** · Zhenda Xie; Yixuan Wei; Huanqi Cao; Chenggang Zhao; Chengqi Deng; Jiashi Li; Damai Dai; Huazuo Gao; Mingyu Xu; Kuai Yu; Liang Zhao; Shangyan Zhou; Zhean Xu; Zhengyan Zhang; Wangding Zeng; Shengding Hu; Yuqing Wang; Jingyang Yuan; Lean Wang; Wenfeng Liang

[Primary source](<https://openreview.net/forum?id=mDhyxu8WRb>) · [Venue page](<https://icml.cc/virtual/2026/poster/61870>) · [PDF](<https://openreview.net/pdf?id=mDhyxu8WRb>)

**Topics:** Manifold; Optimizer.

**Categories:** E — Training stabilization and distributed optimization; M4 — Related constrained and geometry-aware optimization.

**Optimizer relevance:** mHC projects hyper-connection residual mixing into a constrained set to stabilize large-model training; an architectural constraint mechanism rather than a replacement optimizer.

**Manifold relevance:** mHC constrains residual connections to improve large-model training stability. This is a constrained architecture, not a general Riemannian optimization algorithm.

**Geometry:** Doubly stochastic residual mixing / Birkhoff constraints. **Manifold scope:** Related/supporting.

**Evidence:** Official accepted-paper title and abstract.

### Mitigating Staleness in Asynchronous Pipeline Parallelism via Basis Rotation

**ICML 2026 · Accept (regular)** · Hyunji Jung; Sungbin Shin; Namhoon Lee

[Primary source](<https://openreview.net/forum?id=31iky6wFu5>) · [Venue page](<https://icml.cc/virtual/2026/poster/66517>) · [PDF](<https://openreview.net/pdf?id=31iky6wFu5>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

**Optimizer relevance:** Rotates an adaptive optimizer's basis toward the Hessian eigenbasis to mitigate stale-gradient instability in asynchronous LLM training.

**Evidence:** Official accepted-paper title and abstract.

### Model-Preserving Adaptive Rounding

**ICML 2026 · Accept (regular)** · Albert Tseng; Zhaofeng Sun; Chris De Sa

[Primary source](<https://openreview.net/forum?id=PKFilPWjMI>) · [Venue page](<https://icml.cc/virtual/2026/poster/64269>) · [PDF](<https://openreview.net/pdf?id=PKFilPWjMI>)

**Topics:** Matrix computation; Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Hessian geometry for adaptive rounding.

**Computational idea:** Use a Kronecker-factored approximation and Hessian sketches aligned with network-output error.

**Scope:** Deep learning. **Qualification:** An approximation supporting quantization; not full end-to-end Hessian construction.

**Optimizer relevance:** Related Kronecker-curvature method: YAQA uses Kronecker-factored Hessian sketches of end-to-end model error for adaptive quantization rounding.

**Evidence:** Official accepted-paper title and abstract.

### Momentum Further Constrains Sharpness at the Edge of Stochastic Stability

**ICML 2026 · Accept (regular)** · Arseniy Andreyev; Advikar Ananthkumar; Marc Walden; Tomaso A Poggio; Pierfrancesco Beneventano

[Primary source](<https://openreview.net/forum?id=mL4i6z7Miy>) · [Venue page](<https://icml.cc/virtual/2026/poster/61855>) · [PDF](<https://openreview.net/pdf?id=mL4i6z7Miy>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T2 — Batch size, gradient noise and training efficiency; T5 — Stability, curvature and edge-of-stability dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Shows how batch size and momentum jointly determine stochastic stability thresholds and attained sharpness.

**Training dynamics relevance:** Shows how batch size and momentum jointly determine stochastic stability thresholds and attained sharpness.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Batch size; momentum; stochastic sharpness.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### MuLoCo: Muon is a Practical Inner Optimizer for DiLoCo

**ICML 2026 · Accept (regular)** · Benjamin Thérien; Xiaolong Huang; Aaron Defazio; Irina Rish; Eugene Belilovsky

[Primary source](<https://openreview.net/forum?id=OBXBXSgwcD>) · [Venue page](<https://icml.cc/virtual/2026/poster/64378>) · [PDF](<https://openreview.net/pdf?id=OBXBXSgwcD>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

**Optimizer relevance:** MuLoCo studies Muon as DiLoCo's inner optimizer, linking update geometry to more reliable distributed pseudogradients.

**Evidence:** Official accepted-paper title and abstract.

### Muon in Associative Memory Learning: Training Dynamics and Scaling Laws

**ICML 2026 · Accept (regular)** · Kaifei Wang; Binghui Li; Han Zhong; Pinyan Lu; Liwei Wang

[Primary source](<https://openreview.net/forum?id=tn00ERVdgL>) · [Venue page](<https://icml.cc/virtual/2026/poster/61087>) · [PDF](<https://openreview.net/pdf?id=tn00ERVdgL>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Studies Muon through associative-memory training dynamics and scaling laws; a theoretical model rather than a new general LLM optimizer.

**Training dynamics relevance:** Studies Muon through associative-memory training dynamics and scaling laws; a theoretical model rather than a new general LLM optimizer.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Muon; training time; associative-memory scaling.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### MuonSSM: Orthogonalizing State Space Models for Sequence Modeling

**ICML 2026 · Accept (spotlight)** · Thai Khanh Nguyen; Uyen N.B. Vo; Thieu Vo; Tan Nguyen; Cuong Pham

[Primary source](<https://openreview.net/forum?id=GmP3VcfHi0>) · [Venue page](<https://icml.cc/virtual/2026/oral/71058>) · [PDF](<https://openreview.net/pdf?id=GmP3VcfHi0>)

**Topics:** Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods.

**Optimizer relevance:** MuonSSM applies momentum and orthogonalization inside an SSM's memory updates; this is an architectural mechanism rather than the external parameter optimizer.

**Evidence:** Official accepted-paper title and abstract.

### Natural Hypergradient Descent:  Algorithm Design, Convergence Analysis, and Parallel Implementation

**ICML 2026 · Accept (regular)** · Deyi Kong; Zaiwei Chen; Shuzhong Zhang; Shancong Mou

[Primary source](<https://openreview.net/forum?id=4K54YHTG2i>) · [Venue page](<https://icml.cc/virtual/2026/poster/66368>) · [PDF](<https://openreview.net/pdf?id=4K54YHTG2i>)

**Topics:** Matrix computation; Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Inverse-Hessian actions for bilevel hypergradients.

**Computational idea:** Use empirical Fisher as an asymptotically consistent Hessian surrogate and update the approximation alongside inner optimization.

**Scope:** General ML. **Qualification:** Fisher-Hessian agreement and convergence require the paper's statistical assumptions.

**Optimizer relevance:** Bilevel optimization: empirical-Fisher inverse estimates are updated alongside inner optimization; the full text explicitly incorporates K-FAC to reduce memory and computation.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2602.10905>): Section 3 Practical Considerations: K-FAC acceleration Targeted check recorded in the earlier project catalog; not a complete paper review.

### Non-Euclidean Gradient Descent Operates at the Edge of Stability

**ICML 2026 · Accept (spotlight)** · Rustem Islamov; Michael Crawshaw; Jeremy Cohen; Robert Gower

[Primary source](<https://openreview.net/forum?id=piWlEHb4Db>) · [Venue page](<https://icml.cc/virtual/2026/oral/71156>) · [PDF](<https://openreview.net/pdf?id=piWlEHb4Db>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Optimizer relevance:** Extends edge-of-stability diagnostics to non-Euclidean geometries, including spectral and sign descent.

**Training dynamics relevance:** Extends edge-of-stability diagnostics to non-Euclidean geometries, including spectral and sign descent.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Learning rate; descent geometry.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### NorMuon: Making Muon more efficient and scalable

**ICML 2026 · Accept (spotlight)** · Zichong Li; Liming Liu; Chen Liang; Weizhu Chen; Tuo Zhao

[Primary source](<https://openreview.net/forum?id=m1IRWFAMsa>) · [Venue page](<https://icml.cc/virtual/2026/poster/61880>) · [PDF](<https://openreview.net/pdf?id=m1IRWFAMsa>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

**Optimizer relevance:** NorMuon combines Muon orthogonalization with neuron-wise adaptive normalization and a distributed FSDP2 implementation.

**Evidence:** Official accepted-paper title and abstract.

### OLion: Approaching the Hadamard Ideal by Intersecting Spectral and L inf Implicit Biases

**ICML 2026 · Accept (regular)** · Zixiao Wang; Yifei Shen; Huishuai Zhang

[Primary source](<https://openreview.net/forum?id=fG4nXq9Ytm>) · [Venue page](<https://icml.cc/virtual/2026/poster/62586>) · [PDF](<https://openreview.net/pdf?id=fG4nXq9Ytm>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

**Optimizer relevance:** OLion combines orthogonalized update directions with entrywise sign control; evaluates GPT-2/Llama pretraining and fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

### On the Convergence Rate of LoRA Gradient Descent

**ICML 2026 · Accept (spotlight)** · Siqiao Mu; Diego Klabjan

[Primary source](<https://openreview.net/forum?id=9GRlBVAXq8>) · [Venue page](<https://icml.cc/virtual/2026/poster/65870>) · [PDF](<https://openreview.net/pdf?id=9GRlBVAXq8>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

**Optimizer relevance:** Provides non-asymptotic convergence analysis for original LoRA gradient descent without artificially imposing standard global smoothness assumptions.

**Evidence:** Official accepted-paper title and abstract.

### On the Interaction of Batch Noise, Adaptivity, and Compression, under $(L_0,L_1)$-Smoothness: An SDE Approach

**ICML 2026 · Accept (regular)** · Enea Monzio Compagnoni; Rustem Islamov; Frank Proske; Aurelien Lucchi; Antonio Orvieto; Eduard Gorbunov

[Primary source](<https://openreview.net/forum?id=Pmsc4yytlf>) · [Venue page](<https://icml.cc/virtual/2026/poster/64227>) · [PDF](<https://openreview.net/pdf?id=Pmsc4yytlf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T5 — Stability, curvature and edge-of-stability dynamics.

**Training dynamics relevance:** Constructs curvature-aware SDE models for the joint stability effects of compressed and normalized stochastic optimization.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Learning rate; batch noise; compression; update normalization.

**Training qualification:** Modified-equation approximations require their stated smoothness/noise assumptions.

**Evidence:** Official accepted-paper title and abstract.

### On the origin of neural scaling laws:  from random graphs to natural language

**ICML 2026 · Accept (spotlight)** · Maissam Barkeshli; Alberto Alfarano; Andrey Gromov

[Primary source](<https://openreview.net/forum?id=mu17VSX8q9>) · [Venue page](<https://icml.cc/virtual/2026/poster/61791>) · [PDF](<https://openreview.net/pdf?id=mu17VSX8q9>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Uses graph-walk and simplified-language experiments to show scaling laws can arise without power-law input correlations.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Data complexity; model size; parameterization.

**Training qualification:** The proposed mechanisms are studied in controlled data and small Transformers; extrapolation to all language is not proved.

**Evidence:** Official accepted-paper title and abstract.

### One LR Doesn’t Fit All: Heavy-Tail Guided Layerwise Learning Rates for LLMs

**ICML 2026 · Accept (regular)** · Di He; Songjun Tu; Keyu Wang; Lu Yin; Shiwei Liu

[Primary source](<https://openreview.net/forum?id=fs9KaJyhRO>) · [Venue page](<https://icml.cc/virtual/2026/poster/62519>) · [PDF](<https://openreview.net/pdf?id=fs9KaJyhRO>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules.

**Optimizer relevance:** Uses layer-wise heavy-tail spectral statistics to assign learning rates during LLM pretraining, including AdamW and Muon.

**Training dynamics relevance:** Uses layer-wise heavy-tail spectral statistics to assign learning rates during LLM pretraining, including AdamW and Muon.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Layer-wise learning rates; spectral tail statistics.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/hed-ucas/Layer-wise-Learning-Rate.>). Links extracted from the accepted abstract; code was not tested.

### One-Step Gradient Delay is Not a Barrier for Large-Scale Asynchronous Pipeline Parallel LLM Pretraining

**ICML 2026 · Accept (regular)** · Philip Zmushko; Egor Petrov; Nursultan Abdullaev; Khrushchev Mikhail; Samuel Horváth

[Primary source](<https://openreview.net/forum?id=dpWXlBRLKm>) · [Venue page](<https://icml.cc/virtual/2026/poster/62737>) · [PDF](<https://openreview.net/pdf?id=dpWXlBRLKm>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

**Optimizer relevance:** Studies optimizer-dependent sensitivity to one-step pipeline delay and proposes an error-feedback correction; finds Muon more robust than AdamW in the tested settings.

**Evidence:** Official accepted-paper title and abstract.

### Over-Alignment vs Over-Fitting: The Role of Feature Learning Strength in Generalization

**ICML 2026 · Accept (regular)** · Taesun Yeom; Taehyeok Ha; Jaeho Lee

[Primary source](<https://openreview.net/forum?id=Ak8sl1w550>) · [Venue page](<https://icml.cc/virtual/2026/poster/65728>) · [PDF](<https://openreview.net/pdf?id=Ak8sl1w550>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Finds an intermediate feature-learning strength that balances over-alignment against overfitting.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Initialization/output scale; feature-learning strength; stopping rule.

**Training qualification:** Theory is for two-layer ReLU gradient flow; optimal settings depend on the training-risk stopping criterion.

**Evidence:** Official accepted-paper title and abstract.

### OVLR: Efficient, Scalable, and Robust Training via Output-Level Variance-Reduced Likelihood Ratio

**ICML 2026 · Accept (regular)** · Minhao Zou; Tao Ren; Jinyang Jiang; Rui Tao; Zehao Li; Jiale Fu; Hui Shao; Xianhua Liu; Yijie Peng

[Primary source](<https://openreview.net/forum?id=RIase6VpF6>) · [Venue page](<https://icml.cc/virtual/2026/poster/64062>) · [PDF](<https://openreview.net/pdf?id=RIase6VpF6>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** OVLR uses low-dimensional output perturbations and variance-reduced likelihood-ratio estimates for objectives with unavailable or uninformative gradients; includes language modeling.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/MinhZou/OVLR.>). Links extracted from the accepted abstract; code was not tested.

### Per-example Gradients: a New Frontier for Understanding and Improving Optimizers

**ICML 2026 · Accept (regular)** · Vincent Roulet; Atish Agarwala

[Primary source](<https://openreview.net/forum?id=YB6U1yWcGy>) · [Venue page](<https://icml.cc/virtual/2026/poster/63313>) · [PDF](<https://openreview.net/pdf?id=YB6U1yWcGy>)

**Topics:** Optimizer; Training dynamics.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; T2 — Batch size, gradient noise and training efficiency; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Uses efficient per-example/per-token gradient statistics to analyze and improve signSGD and Adam-style preconditioning.

**Training dynamics relevance:** Uses efficient per-example/per-token gradient statistics to analyze and improve signSGD and Adam-style preconditioning.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Per-example gradient statistics; adaptive normalization.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### POET-X: Memory-efficient LLM Training by Scaling Orthogonal Transformation

**ICML 2026 · Accept (spotlight)** · Zeju Qiu; Lixin LIU; Adrian Weller; Han Shi; Weiyang Liu

[Primary source](<https://openreview.net/forum?id=et8jpWLUuD>) · [Venue page](<https://icml.cc/virtual/2026/oral/71112>) · [PDF](<https://openreview.net/pdf?id=et8jpWLUuD>)

**Topics:** Manifold; Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers; M2 — Manifold-based LLM training and low-rank adaptation.

**Optimizer relevance:** POET-X scales spectrum-preserving orthogonal-equivalence training to reduce LLM training memory and computation.

**Manifold relevance:** POET-X makes spectrum-preserving orthogonal reparameterized LLM training more memory- and compute-efficient; the abstract does not specify a new general Riemannian optimizer.

**Geometry:** Orthogonal-equivalence transformations of weight matrices. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### Preconditioning Neural Tangent Kernel for Adaptive Optimization

**ICML 2026 · Accept (regular)** · Xiyuan Yang; Wenxuan Bao; Katherine Tieu; Jingrui He

[Primary source](<https://openreview.net/forum?id=CKzW9g2x3g>) · [Venue page](<https://icml.cc/virtual/2026/poster/65570>) · [PDF](<https://openreview.net/pdf?id=CKzW9g2x3g>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Optimizer Aware Kernel (OAK) extends NTK analysis to preconditioned fine-tuning and studies when the kernel approximation breaks down.

**Training dynamics relevance:** Optimizer Aware Kernel (OAK) extends NTK analysis to preconditioned fine-tuning and studies when the kernel approximation breaks down.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Preconditioner; fine-tuning; kernel approximation.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### PRISM: Distribution-free Adaptive Computation of Matrix Functions for Accelerating Neural Network Training

**ICML 2026 · Accept (regular)** · Shenghao Yang; Zhichao Wang; Oleg Balabanov; N. Benjamin Erichson; Michael Mahoney

[Primary source](<https://openreview.net/forum?id=hwhvjhXC0m>) · [Venue page](<https://icml.cc/virtual/2026/poster/62288>) · [PDF](<https://openreview.net/pdf?id=hwhvjhXC0m>)

**Topics:** Matrix computation; Optimizer.

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X1 — Matrix functions, roots and matrix geometry.

**Quantity:** Matrix roots, inverse roots and polar factors.

**Computational idea:** Fit iteration polynomials to the current spectrum through randomized sketched least squares; use matrix multiplications for the main iteration.

**Scope:** Deep learning. **Qualification:** Iterative approximation; no explicit spectral bounds required by the proposed fitting scheme.

**Optimizer relevance:** PRISM combines adaptive polynomial approximation with randomized sketching to accelerate matrix functions used by Shampoo and Muon.

**Evidence:** Official accepted-paper title and abstract; targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/html/2601.22137v1>): Sections 3-5; adaptive polynomial fitting, randomized sketching, and supported matrix functions. Preprint version v1; accepted title and venue are taken from the official conference program.

### Privacy Amplification in Differentially Private Zeroth-Order Optimization with Hidden States

**ICML 2026 · Accept (regular)** · Eli Chien; Wei-Ning Chen; Pan Li

[Primary source](<https://openreview.net/forum?id=YBIGgUet07>) · [Venue page](<https://icml.cc/virtual/2026/poster/63312>) · [PDF](<https://openreview.net/pdf?id=YBIGgUet07>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

**Optimizer relevance:** Studies privacy amplification and algorithm design for differentially private zeroth-order optimization, motivated by LLM fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

### Quartet II: Accurate LLM Pre-Training in NVFP4 by Improved Unbiased Gradient Estimation

**ICML 2026 · Accept (regular)** · Andrei Panferov; Erik Schultheis; Soroush Tabesh; Dan Alistarh

[Primary source](<https://openreview.net/forum?id=CciWEZZDVb>) · [Venue page](<https://icml.cc/virtual/2026/poster/65532>) · [PDF](<https://openreview.net/pdf?id=CciWEZZDVb>)

**Topics:** Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods.

**Optimizer relevance:** Quartet II improves unbiased quantized gradient estimation for fully NVFP4 LLM training; primarily a numerical training method.

**Evidence:** Official accepted-paper title and abstract.

### Rethinking Neural Network Learning Rates: A Stackelberg Perspective

**ICML 2026 · Accept (regular)** · Sihan Zeng; Sujay Bhatt; Sumitra Ganesh

[Primary source](<https://openreview.net/forum?id=TgohCXoblV>) · [Venue page](<https://icml.cc/virtual/2026/poster/63794>) · [PDF](<https://openreview.net/pdf?id=TgohCXoblV>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T8 — Optimizer dynamics, comparisons and diagnostics.

**Training dynamics relevance:** Interprets a faster final-layer learning rate through Stackelberg optimization and studies conditions for improved convergence.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Layer-wise learning rates; output/body timescales.

**Training qualification:** Convergence results have stated problem assumptions; nonuniform rates are not always superior.

**Evidence:** Official accepted-paper title and abstract.

### Revisiting Anisotropy in Language Transformers: The Geometry of Learning Dynamics

**ICML 2026 · Accept (regular)** · Raphael Bernas; Fanny Jourdan; Antonin Poché; Céline Hudelot

[Primary source](<https://openreview.net/forum?id=BxSubxbbNc>) · [Venue page](<https://icml.cc/virtual/2026/poster/65605>) · [PDF](<https://openreview.net/pdf?id=BxSubxbbNc>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Training dynamics relevance:** Uses training checkpoints to relate embedding geometry, anisotropy and entropy across language-model families.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Training stage; representation anisotropy.

**Training qualification:** Primarily a descriptive analysis; correlations do not isolate causal hyperparameter effects.

**Evidence:** Official accepted-paper title and abstract.

### RMNP: Row-Momentum Normalized Preconditioning for Scalable Matrix-Based Optimization

**ICML 2026 · Accept (regular)** · Shenyang Deng; Zhuoli Ouyang; Tianyu Pang; Zihang Liu; Ruochen Jin; Shuhua Yu; Yaoqing Yang

[Primary source](<https://openreview.net/forum?id=BC5aRMdRwp>) · [Venue page](<https://icml.cc/virtual/2026/poster/65683>) · [PDF](<https://openreview.net/pdf?id=BC5aRMdRwp>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

**Optimizer relevance:** RMNP replaces Muon's Newton-Schulz orthogonalization with row-wise momentum normalization to reduce preconditioning cost in LLM pretraining.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/Dominator-Index/RMNP>). Links extracted from the accepted abstract; code was not tested.

### Romberg-Extrapolated Zeroth-Order Gradient Estimator: Higher-Order Bias Reduction with Preserved Leading Directional Variance

**ICML 2026 · Accept (regular)** · Hongcheng Dong; Wenqiang Pu; Licheng Zhao; Rui Zhou; Feng Yin

[Primary source](<https://openreview.net/forum?id=FiuJVpxuSX>) · [Venue page](<https://icml.cc/virtual/2026/poster/65215>) · [PDF](<https://openreview.net/pdf?id=FiuJVpxuSX>)

**Topics:** Optimizer.

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs.

**Optimizer relevance:** Romberg-ZOGE reduces finite-difference bias by combining radii while sharing directions; includes black-box prompt tuning of OPT-1.3B, not full-model LLM fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

### Scalable Kronecker-Factored Fisher Approximation for Neural Network Parameter Sensitivity

**ICML 2026 · Accept (regular)** · Viktoriia Chekalina; Daniil Moskovskiy; Tatyana Matveeva; Andrey Kuznetsov; Evgeny Frolov

[Primary source](<https://openreview.net/forum?id=pNe5fVK1tR>) · [Venue page](<https://icml.cc/virtual/2026/poster/61515>) · [PDF](<https://openreview.net/pdf?id=pNe5fVK1tR>)

**Topics:** Matrix computation; Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X3 — Fisher, Hessian, derivatives and implicit differentiation.

**Quantity:** Structured Fisher information and sensitivity-aware low-rank factors.

**Computational idea:** Matrix-free Fisher factorization retains off-diagonal structure; GFWSVD gives a curvature-weighted layer decomposition.

**Scope:** Deep learning. **Qualification:** Closed-form optimality relies on the stated matrix-variate normal assumptions.

**Optimizer relevance:** Structured Fisher approximation: matrix-free Fisher factorization (MFF) and GFWSVD preserve non-diagonal parameter sensitivity for neural-network and LLM compression.

**Evidence:** Official accepted-paper title and abstract.

### Scalable Reinforcement Learning via Adaptive Batch Scaling

**ICML 2026 · Accept (regular)** · Jongchan Park

[Primary source](<https://openreview.net/forum?id=YI9wSqfz7W>) · [Venue page](<https://icml.cc/virtual/2026/poster/63301>) · [PDF](<https://openreview.net/pdf?id=YI9wSqfz7W>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T2 — Batch size, gradient noise and training efficiency.

**Training dynamics relevance:** Adjusts batch size with behavioral divergence to accommodate early plasticity and later stable RL training.

**Training study context:** Reinforcement learning.

**Hyperparameters / scaling axes:** Batch size; model size; policy nonstationarity.

**Training qualification:** The reported validation uses PQN and Atari/ALE tasks.

**Evidence:** Official accepted-paper title and abstract.

### Scaling depth capacity via zero/one-layer model expansion

**ICML 2026 · Accept (regular)** · Zhiqi Bu

[Primary source](<https://openreview.net/forum?id=WP5q6Hn3Cv>) · [Venue page](<https://icml.cc/virtual/2026/poster/63529>) · [PDF](<https://openreview.net/pdf?id=WP5q6Hn3Cv>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Studies progressive model expansion and proposes zero/one-layer strategies that balance training cost and final loss.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Depth-expansion timing; new-layer initialization; learning-rate transfer.

**Training qualification:** Compute gains and transfer rules depend on the expansion protocol and tested architectures.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Law for Quantization-Aware Training

**ICML 2026 · Accept (spotlight)** · Mengzhao Chen; Chaoyi Zhang; Jing Liu; Zeng; Zeyue Xue; Zhiheng Liu; Yunshui Li; Jin Ma; Jie Huang; zhou Xun; Ping Luo

[Primary source](<https://openreview.net/forum?id=fXr3uPr1G5>) · [Venue page](<https://icml.cc/virtual/2026/poster/62561>) · [PDF](<https://openreview.net/pdf?id=fXr3uPr1G5>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Fits quantization-aware training laws that separate weight and activation errors and expose their different token sensitivities.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** QAT precision; quantization group size; tokens; model size.

**Training qualification:** The main study concerns W4A4 and its mixed-precision interventions.

**Evidence:** Official accepted-paper title and abstract.

### ScaLoRA: Optimally Scaled Low-Rank Adaptation for Efficient High-Rank Fine-Tuning

**ICML 2026 · Accept (regular)** · Yilang Zhang; Xiaodong Yang; Yiwei Cai; Georgios B. Giannakis

[Primary source](<https://openreview.net/forum?id=Skxb4UgTWU>) · [Venue page](<https://icml.cc/virtual/2026/poster/63892>) · [PDF](<https://openreview.net/pdf?id=Skxb4UgTWU>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

**Optimizer relevance:** ScaLoRA analytically scales consecutive low-rank increments to approximate full fine-tuning while progressively accumulating a high-rank update.

**Evidence:** Official accepted-paper title and abstract.

### Sharpness-Aware Minimization Can Hallucinate Minimizers

**ICML 2026 · Accept (regular)** · Chanwoong Park; Uijeong Jang; Ernest Ryu; Insoon Yang

[Primary source](<https://openreview.net/forum?id=7xwOy8C00l>) · [Venue page](<https://icml.cc/virtual/2026/poster/66010>) · [PDF](<https://openreview.net/pdf?id=7xwOy8C00l>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Identifies nonstationary points where SAM can stall and finds that SGD warm-starts reduce sensitivity to large perturbations.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** SAM perturbation radius; SGD warm-start.

**Training qualification:** A failure mechanism under particular landscape/radius conditions, not a claim that SAM always fails.

**Evidence:** Official accepted-paper title and abstract.

### Sharpness-Aware Pretraining Mitigates Catastrophic Forgetting

**ICML 2026 · Accept (regular)** · Ishaan Watts; Catherine Li; Sachin Goyal; Jacob Mitchell Springer; Aditi Raghunathan

[Primary source](<https://openreview.net/forum?id=CHvRfubYke>) · [Venue page](<https://icml.cc/virtual/2026/poster/65575>) · [PDF](<https://openreview.net/pdf?id=CHvRfubYke>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Studies SAM, larger learning rates, and shorter annealing as pretraining interventions that improve retention after LLM post-training or quantization.

**Training dynamics relevance:** Studies SAM, larger learning rates, and shorter annealing as pretraining interventions that improve retention after LLM post-training or quantization.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Pretraining rate; annealing duration; SAM; retention.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Single-Head Attention in High Dimensions: A Theory of Generalization, Weights Spectra, and Scaling Laws

**ICML 2026 · Accept (spotlight)** · Fabrizio Boncoraglio; Vittorio Erba; Emanuele Troiani; Yizhou Xu; FLORENT KRZAKALA; Lenka Zdeborova

[Primary source](<https://openreview.net/forum?id=3qan4Zg9rA>) · [Venue page](<https://icml.cc/virtual/2026/poster/66429>) · [PDF](<https://openreview.net/pdf?id=3qan4Zg9rA>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Connects attention weight spectra and sequential recovery of signal modes to generalization and power-law scaling.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Attention dimension; sample size; target spectrum.

**Training qualification:** Theory uses a single tied attention head and synthetic high-dimensional tasks.

**Evidence:** Official accepted-paper title and abstract.

### Softsign: Smooth Sign in Your Optimizer For Better Parameter Heterogeneity Handling

**ICML 2026 · Accept (regular)** · Dmitrii Feoktistov; Timofey Belinsky; Andrey Veprikov; Amir Zainullin; Aleksandr Beznosikov

[Primary source](<https://openreview.net/forum?id=n47bK7WM3U>) · [Venue page](<https://icml.cc/virtual/2026/poster/61776>) · [PDF](<https://openreview.net/pdf?id=n47bK7WM3U>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

**Optimizer relevance:** SoftSignum and SoftMuon replace hard sign-like maps with smooth, temperature-controlled transformations to improve terminal convergence.

**Evidence:** Official accepted-paper title and abstract.

### SpanNorm: Reconciling Training Stability and Performance in Deep Transformers

**ICML 2026 · Accept (regular)** · Chao Wang; Bei Li; Jiaqi Zhang; Xinyu Liu; Yuchun Fan; Linkun Lyu; Xin Chen; Jingang Wang; Tong Xiao; Peng Pei; Xunliang Cai

[Primary source](<https://openreview.net/forum?id=9bLiqb6Vec>) · [Venue page](<https://icml.cc/virtual/2026/poster/65837>) · [PDF](<https://openreview.net/pdf?id=9bLiqb6Vec>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** SpanNorm combines a stable residual path with output normalization to control variance and reduce representation collapse.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Normalization placement; residual scaling; depth.

**Training qualification:** Evidence concerns the proposed architecture; bounded signal variance alone does not establish universal optimization stability.

**Evidence:** Official accepted-paper title and abstract.

### SPARKLING: Balancing Signal Preservation and Symmetry Breaking for Width-Progressive Learning

**ICML 2026 · Accept (regular)** · Qifan Yu; Xinyu Ma; Zhijian Zhuo; Minrui Wang; Deyi Liu; Shiyi Zhan; Yiyuan Ma; liang xiang; Xingyan Bin; Di He

[Primary source](<https://openreview.net/forum?id=SXJBFREkWi>) · [Venue page](<https://icml.cc/virtual/2026/poster/63922>) · [PDF](<https://openreview.net/pdf?id=SXJBFREkWi>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer; T5 — Stability, curvature and edge-of-stability dynamics.

**Training dynamics relevance:** SPARKLING preserves activation scale while breaking copied-neuron symmetry during mid-training width growth.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Width expansion; optimizer-state reset; learning-rate re-warmup.

**Training qualification:** The empirical benefits concern the evaluated expansion axes and ratios.

**Evidence:** Official accepted-paper title and abstract.

### Spectra: Rethinking Optimizers for LLMs Under Spectral Anisotropy

**ICML 2026 · Accept (regular)** · Zhendong Huang; Hengjie Cao; Fang DONG(董方); Ruijun Huang; Mengyi Chen; Yifeng Yang; Xin Zhang; Anrui Chen; Mingzhi Dong; Yujiang Wang; Jinlong Hou; Qin Lv; Robert Dick; Yuan Cheng; Tun Lu; Fan Yang; Li Shang

[Primary source](<https://openreview.net/forum?id=uXHiVNJK25>) · [Venue page](<https://icml.cc/virtual/2026/poster/61015>) · [PDF](<https://openreview.net/pdf?id=uXHiVNJK25>)

**Topics:** Optimizer.

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers.

**Optimizer relevance:** Spectra suppresses dominant low-rank spectral spikes while avoiding amplification of the noisy tail; evaluates LLM pretraining and optimizer memory/runtime.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/kimmichtank/spectra.>). Links extracted from the accepted abstract; code was not tested.

### Spectral Bridge Variational Inference: Dynamic LoRA via Bures-Wasserstein Gradient Flows

**ICML 2026 · Accept (regular)** · Yuhang Xi; Yu-Feng Yu; Chuan-Xian Ren; Zhao-Rong Lai

[Primary source](<https://openreview.net/forum?id=KjF35IhQGS>) · [Venue page](<https://icml.cc/virtual/2026/poster/64699>) · [PDF](<https://openreview.net/pdf?id=KjF35IhQGS>)

**Topics:** Manifold; Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; M2 — Manifold-based LLM training and low-rank adaptation.

**Optimizer relevance:** SBVI treats LoRA as a Bures-Wasserstein gradient flow over Gaussian measures, adapting ranks with spectral dynamics and factorized Riemannian retractions.

**Manifold relevance:** SBVI models dynamic LoRA with Wasserstein gradient flows and factorized Riemannian retractions, adapting the distribution of ranks across layers.

**Geometry:** Gaussian measures / Bures-Wasserstein geometry. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### Spectral Collapse Drives Loss of Plasticity in Deep Continual Learning

**ICML 2026 · Accept (regular)** · Arjun Prakash; Naicheng He; Kaicheng Guo; Saket Tiwari; Tyrone Serapio; Ruo Yu Tao; Amy Greenwald; George Konidaris

[Primary source](<https://openreview.net/forum?id=O6rHSkpYJU>) · [Venue page](<https://icml.cc/virtual/2026/poster/64388>) · [PDF](<https://openreview.net/pdf?id=O6rHSkpYJU>)

**Topics:** Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations.

**Optimizer relevance:** Related analysis: uses Kronecker-factored Hessian structure to motivate effective-rank and L2 regularization against plasticity loss; not an LLM optimizer paper.

**Evidence:** Official accepted-paper title and abstract.

### Spectral Imbalance Causes Forgetting in Low-Rank Continual Adaptation

**ICML 2026 · Accept (regular)** · Hao Gu; Mao-Lin Luo; Zi-Hao Zhou; Han-Chen Zhang; Min-Ling Zhang; Tong Wei

[Primary source](<https://openreview.net/forum?id=kqE6GjpQTn>) · [Venue page](<https://icml.cc/virtual/2026/poster/61996>) · [PDF](<https://openreview.net/pdf?id=kqE6GjpQTn>)

**Topics:** Manifold; Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; M2 — Manifold-based LLM training and low-rank adaptation.

**Optimizer relevance:** Uses projected first-order optimization on a restricted Stiefel manifold to balance low-rank adaptation spectra and reduce continual-learning forgetting.

**Manifold relevance:** Decouples low-rank update magnitude and direction, then uses projected first-order optimization to balance spectra and reduce forgetting in continual adaptation.

**Geometry:** Restricted Stiefel manifold. **Manifold scope:** Direct algorithm/theory/application.

**Evidence:** Official accepted-paper title and abstract.

### Spectral Reach: Understanding Neural Scaling as Progress into the Spectral Tail

**ICML 2026 · Accept (regular)** · Konstantin Nikolaou; Jonas Scheunemann; Sven Krippendorf; Samuel Tovey; Christian Holm

[Primary source](<https://openreview.net/forum?id=ECdZxuI9Hf>) · [Venue page](<https://icml.cc/virtual/2026/poster/65378>) · [PDF](<https://openreview.net/pdf?id=ECdZxuI9Hf>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

**Optimizer relevance:** Analyzes neural scaling as progress into the empirical-NTK spectral tail; relevant to optimizer/feature-learning mechanisms, not a new optimizer.

**Training dynamics relevance:** Analyzes neural scaling as progress into the empirical-NTK spectral tail; relevant to optimizer/feature-learning mechanisms, not a new optimizer.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Training progress; NTK spectral tail.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Stabilizing Native Low-Rank LLM Pretraining

**ICML 2026 · Accept (regular)** · Paul Janson; Edouard Oyallon; Eugene Belilovsky

[Primary source](<https://openreview.net/forum?id=kb5wjkqu8q>) · [Venue page](<https://icml.cc/virtual/2026/poster/62024>) · [PDF](<https://openreview.net/pdf?id=kb5wjkqu8q>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

**Optimizer relevance:** Spectron controls the spectral norm of updates to low-rank factors, enabling stable native low-rank LLM pretraining.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/Pauljanson002/spectron>). Links extracted from the accepted abstract; code was not tested.

### Steady-State Behavior of Constant-Stepsize Stochastic Approximation: Gaussian Approximation and Tail Bounds

**ICML 2026 · Accept (regular)** · Yuyang Wang; Felix Wang; Zedong Wang; Ijay Narang; Yuzhou Wang; Siva Maguluri

[Primary source](<https://openreview.net/forum?id=m4TAzup6Yc>) · [Venue page](<https://icml.cc/virtual/2026/poster/61876>) · [PDF](<https://openreview.net/pdf?id=m4TAzup6Yc>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency.

**Training dynamics relevance:** Bounds how well Gaussian distributions approximate stationary stochastic-approximation iterates at finite step size.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Constant step size; dimension; temporal noise dependence.

**Training qualification:** Requires the stated convexity, contraction and noise conditions; general nonconvex training is outside the main result.

**Evidence:** Official accepted-paper title and abstract.

### Step-Size Stability in Stochastic Optimization: A Theoretical Perspective

**ICML 2026 · Accept (regular)** · Fabian Schaipp; Robert Gower; Adrien Taylor

[Primary source](<https://openreview.net/forum?id=yhvzMLgpdV>) · [Venue page](<https://icml.cc/virtual/2026/poster/60591>) · [PDF](<https://openreview.net/pdf?id=yhvzMLgpdV>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Training dynamics relevance:** Quantifies how optimization degrades when steps are too large and explains robustness advantages of adaptive rules.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Step-size misspecification; adaptive step rules.

**Training qualification:** Convex guarantees and nonconvex empirical behavior should be distinguished.

**Evidence:** Official accepted-paper title and abstract.

### SVRG and Beyond via Posterior Correction

**ICML 2026 · Accept (spotlight)** · Nico Daheim; Thomas Moellenhoff; James Ming Liang Ang; Mohammad Emtiyaz Khan

[Primary source](<https://openreview.net/forum?id=3NQSeJOfkz>) · [Venue page](<https://icml.cc/virtual/2026/oral/71109>) · [PDF](<https://openreview.net/pdf?id=3NQSeJOfkz>)

**Topics:** Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods.

**Optimizer relevance:** Derives SVRG from Bayesian posterior correction and develops Newton-like and Adam-like extensions; the abstract does not establish LLM experiments.

**Evidence:** Official accepted-paper title and abstract.

### TetraJet-v2: Accurate NVFP4 Training for Large Language Models with Oscillation Suppression and Outlier Control

**ICML 2026 · Accept (spotlight)** · Yuxiang Chen; Yifan Liu; Xiaoming Xu; Pengle Zhang; Michael Beyer; Martin Rapp; Jun Zhu; Jianfei Chen

[Primary source](<https://openreview.net/forum?id=7ZQhm5HnOA>) · [Venue page](<https://icml.cc/virtual/2026/poster/66046>) · [PDF](<https://openreview.net/pdf?id=7ZQhm5HnOA>)

**Topics:** Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods.

**Optimizer relevance:** TetraJet-v2 tackles oscillation and outliers in NVFP4 LLM training; a specialized low-precision training method rather than a general optimizer.

**Evidence:** Official accepted-paper title and abstract.

### The Geometric Origin of Grokking: Accelerating Generalization via Active Structural Reorganization

**ICML 2026 · Accept (regular)** · Kefei Tao; Zhang Zhang; Mingze Qi; Xiaojun Duan

[Primary source](<https://openreview.net/forum?id=GMdvtJz5Ez>) · [Venue page](<https://icml.cc/virtual/2026/poster/65146>) · [PDF](<https://openreview.net/pdf?id=GMdvtJz5Ez>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Attributes delayed generalization to angular reorganization and proposes an intervention that accelerates it.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Representation geometry; repulsive regularization; training time.

**Training qualification:** The mechanism and intervention are assessed on the studied algorithmic and linguistic tasks.

**Evidence:** Official accepted-paper title and abstract.

### The Implicit Bias of Adam and Muon on Smooth Homogeneous Neural Networks

**ICML 2026 · Accept (regular)** · Eitan Gronich; Gal Vardi

[Primary source](<https://openreview.net/forum?id=DpIc1cpNKG>) · [Venue page](<https://icml.cc/virtual/2026/poster/65420>) · [PDF](<https://openreview.net/pdf?id=DpIc1cpNKG>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Characterizes the implicit max-margin biases of momentum steepest descent, Adam, Muon, and hybrid methods under stated homogeneous-model assumptions.

**Training dynamics relevance:** Characterizes the implicit max-margin biases of momentum steepest descent, Adam, Muon, and hybrid methods under stated homogeneous-model assumptions.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Optimizer geometry; momentum; max-margin bias.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### The Implicit Bias of Depth: From Neural Collapse to Softmax Codes

**ICML 2026 · Accept (regular)** · Connall Garrod; Jonathan Keating; Christos Thrampoulidis

[Primary source](<https://openreview.net/forum?id=TDaVoBfTjY>) · [Venue page](<https://icml.cc/virtual/2026/poster/63845>) · [PDF](<https://openreview.net/pdf?id=TDaVoBfTjY>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Analyzes how depth induces low-rank bias and alters the attraction to neural-collapse versus softmax-code solutions.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Depth; width; spectral/random initialization.

**Training qualification:** Uses the deep unconstrained feature model/deep linear setting.

**Evidence:** Official accepted-paper title and abstract.

### The Implicit Bias of Steepest Descent with Mini-batch Stochastic Gradient

**ICML 2026 · Accept (regular)** · Jichu Li; Xuan Tang; Difan Zou

[Primary source](<https://openreview.net/forum?id=OT9cxeWbEO>) · [Venue page](<https://icml.cc/virtual/2026/poster/64352>) · [PDF](<https://openreview.net/pdf?id=OT9cxeWbEO>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T2 — Batch size, gradient noise and training efficiency; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Studies how minibatching, momentum, and variance reduction affect the implicit bias of sign and spectral steepest descent.

**Training dynamics relevance:** Studies how minibatching, momentum, and variance reduction affect the implicit bias of sign and spectral steepest descent.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Minibatching; momentum; variance reduction; descent norm.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### The Stability of Singular Distribution: A Spectral Perspective on the Two-Phase Dynamics of Language Model Pre-training

**ICML 2026 · Accept (regular)** · Hongtao Zhang; WenJie Zhou; Chenxi Jia; Wei Chen; Xueqi Cheng

[Primary source](<https://openreview.net/forum?id=gVPwive1z6>) · [Venue page](<https://icml.cc/virtual/2026/poster/62448>) · [PDF](<https://openreview.net/pdf?id=gVPwive1z6>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Connects early stabilization of normalized singular spectra to slow pretraining dynamics across AdamW, Muon, and learning-rate schedules.

**Training dynamics relevance:** Connects early stabilization of normalized singular spectra to slow pretraining dynamics across AdamW, Muon, and learning-rate schedules.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Training stage; singular spectrum; optimizer choice.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Theoretical Analysis of Sparse Optimization with Reparameterization, Weight Decay, and Adaptive Learning Rate

**ICML 2026 · Accept (regular)** · Huangyu Xu; Jingqin Yang; Qianqian Xu; Jiaye Teng

[Primary source](<https://openreview.net/forum?id=74PNBqBKPA>) · [Venue page](<https://icml.cc/virtual/2026/poster/66097>) · [PDF](<https://openreview.net/pdf?id=74PNBqBKPA>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** ReWA connects these choices to sparse optimization and mitigates instability of nonconvex sparsity penalties.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Reparameterization; weight decay; adaptive learning rate.

**Training qualification:** The application is sparse ResNet training; sparse-regularization conclusions need not transfer unchanged to LLMs.

**Evidence:** Official accepted-paper title and abstract.

### To Grok Grokking: Provable Grokking in Ridge Regression

**ICML 2026 · Accept (spotlight)** · Mingyue Xu; Gal Vardi; Itay Safran

[Primary source](<https://openreview.net/forum?id=5nNNVY8NW4>) · [Venue page](<https://icml.cc/virtual/2026/oral/71134>) · [PDF](<https://openreview.net/pdf?id=5nNNVY8NW4>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Proves grokking in ridge regression and quantifies how training hyperparameters amplify or eliminate the delay.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Weight decay; learning rate; generalization delay.

**Training qualification:** End-to-end guarantees are linear; nonlinear support is empirical.

**Evidence:** Official accepted-paper title and abstract.

### Towards Efficient LLMs Annealing with Principled Sample Selection

**ICML 2026 · Accept (spotlight)** · Yuanjian Xu; Jianing Hao; Wanbo Zhang; Zhong Li; Guang Zhang

[Primary source](<https://openreview.net/forum?id=2UH01A9Za0>) · [Venue page](<https://icml.cc/virtual/2026/poster/66576>) · [PDF](<https://openreview.net/pdf?id=2UH01A9Za0>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency.

**Training dynamics relevance:** Selects annealing data to suppress noise in sharp directions while retaining useful descent signals in flatter subspaces.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Annealing schedule; sample selection; gradient noise.

**Training qualification:** The proposed selection rule depends on curvature/noise estimates; reported improvements are workload-specific.

**Evidence:** Official accepted-paper title and abstract.

### Towards Understanding Adam Convergence on Highly Degenerate Polynomials

**ICML 2026 · Accept (spotlight)** · Zhiwei Bai; Jiajie Zhao; Zhangchen Zhou; Zhi-Qin John Xu; Yaoyu Zhang

[Primary source](<https://openreview.net/forum?id=uYWVGk1Qt0>) · [Venue page](<https://icml.cc/virtual/2026/poster/61014>) · [PDF](<https://openreview.net/pdf?id=uYWVGk1Qt0>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Analyzes Adam's local convergence and oscillatory regimes on highly degenerate polynomials; useful optimizer theory, not an LLM-scale result.

**Training dynamics relevance:** Analyzes Adam's local convergence and oscillatory regimes on highly degenerate polynomials; useful optimizer theory, not an LLM-scale result.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Adam learning rate; degenerate-polynomial geometry.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Understanding MARS: When Scaling Momentum Provably Helps

**ICML 2026 · Accept (regular)** · Egor Shulgin; Tamaz Gadaev; Sarit Khirirat; Peter Richtarik

[Primary source](<https://openreview.net/forum?id=jokamk4yGt>) · [Venue page](<https://icml.cc/virtual/2026/poster/62098>) · [PDF](<https://openreview.net/pdf?id=jokamk4yGt>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

**Optimizer relevance:** Explains when scaling MARS's momentum-variance-reduction correction improves convergence; includes GPT-style pretraining.

**Evidence:** Official accepted-paper title and abstract.

### Weight Decay Improves Language Model Plasticity

**ICML 2026 · Accept (regular)** · Tessa Han; Sebastian Bordt; Hanlin Zhang; Sham Kakade

[Primary source](<https://openreview.net/forum?id=zMO9H4hLyR>) · [Venue page](<https://icml.cc/virtual/2026/poster/60527>) · [PDF](<https://openreview.net/pdf?id=zMO9H4hLyR>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Studies how pretraining weight decay changes downstream plasticity, showing that base validation loss alone need not predict fine-tuning quality.

**Training dynamics relevance:** Studies how pretraining weight decay changes downstream plasticity, showing that base validation loss alone need not predict fine-tuning quality.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Pretraining weight decay; downstream plasticity.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### When Does Sparsity Mitigate the Curse of Depth in LLMs

**ICML 2026 · Accept (regular)** · Yao Yao; Xinyuan Song; Sebastian Pokutta; Max Zimmer; Nico Pelleriti; Thomas Hofmann; Shiwei Liu

[Primary source](<https://openreview.net/forum?id=7boy4Ipbyn>) · [Venue page](<https://icml.cc/virtual/2026/poster/66043>) · [PDF](<https://openreview.net/pdf?id=7boy4Ipbyn>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Studies how sparsity-like mechanisms reduce residual variance and improve the usefulness of later Transformer layers.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Depth; sparsity; weight decay; context length; expert activation.

**Training qualification:** The link is supported by interventions but is not a universal depth-scaling theorem.

**Evidence:** Official accepted-paper title and abstract.

### When Is Rank-1 Enough? Geometry-Guided Initialization for Parameter-Efficient Fine-Tuning

**ICML 2026 · Accept (regular)** · Haoran Zhao; Caren Han; Eduard Hovy

[Primary source](<https://openreview.net/forum?id=Umu6IsAUbS>) · [Venue page](<https://icml.cc/virtual/2026/poster/63669>) · [PDF](<https://openreview.net/pdf?id=Umu6IsAUbS>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

**Optimizer relevance:** Gap-Init aligns rank-1 LoRA with a modality-gap direction to stabilize very-low-rank vision-language fine-tuning.

**Evidence:** Official accepted-paper title and abstract.

### Why Do We Need Warm-up? A Theoretical Perspective

**ICML 2026 · Accept (regular)** · Foivos Alimisis; Rustem Islamov; Aurelien Lucchi

[Primary source](<https://openreview.net/forum?id=a6fo32UnpU>) · [Venue page](<https://icml.cc/virtual/2026/poster/63104>) · [PDF](<https://openreview.net/pdf?id=a6fo32UnpU>)

**Topics:** Optimizer; Training dynamics.

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Optimizer relevance:** Derives a curvature-motivated learning-rate warm-up schedule, with theory and language/vision experiments.

**Training dynamics relevance:** Derives a curvature-motivated learning-rate warm-up schedule, with theory and language/vision experiments.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Learning-rate warm-up; curvature.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### WinQ: Accelerating Quantization-Aware Training of Language Models Around Saddle Points

**ICML 2026 · Accept (regular)** · Dongyue Li; Zechun Liu; Kai Yi; Zhenshuo Zhang; Changsheng Zhao; Raghuraman Krishnamoorthi; Harshit Khaitan; Hongyang Zhang; Steven Li

[Primary source](<https://openreview.net/forum?id=lIQnUtwWVb>) · [Venue page](<https://icml.cc/virtual/2026/poster/61959>) · [PDF](<https://openreview.net/pdf?id=lIQnUtwWVb>)

**Topics:** Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods.

**Optimizer relevance:** WinQ accelerates language-model quantization-aware training through periodic weight resets and noise-injected gradients motivated by Hessian analysis.

**Evidence:** Official accepted-paper title and abstract.

### Zeroth-Order Optimization at the Edge of Stability

**ICML 2026 · Accept (regular)** · Minhak Song; Liang Zhang; Bingcong Li; Niao He; Michael Muehlebach; Sewoong Oh

[Primary source](<https://openreview.net/forum?id=s87tQaKAER>) · [Venue page](<https://icml.cc/virtual/2026/poster/61252>) · [PDF](<https://openreview.net/pdf?id=s87tQaKAER>)

**Topics:** Optimizer; Training dynamics.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Optimizer relevance:** Analyzes zeroth-order edge-of-stability behavior using the full Hessian spectrum and tractable spectral bounds; empirical focus is vision.

**Training dynamics relevance:** Analyzes zeroth-order edge-of-stability behavior using the full Hessian spectrum and tractable spectral bounds; empirical focus is vision.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Zeroth-order perturbations; step size; curvature.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Block Low-Rank Preconditioner with Shared Basis for Stochastic Optimization

**NeurIPS 2023 · Published** · Jui-Nan Yen; Sai Surya Duvvuri; Inderjit S. Dhillon; Cho-Jui Hsieh

[Primary source](<https://proceedings.neurips.cc/paper_files/paper/2023/hash/389cfad711d2b1e2128e931feee80230-Abstract-Conference.html>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2023/file/389cfad711d2b1e2128e931feee80230-Paper-Conference.pdf>)

**Topics:** Matrix computation; Optimizer.

**Categories:** B — Shampoo, structured curvature, and matrix-function computation; X2 — Eigenproblems, spectral computation and SVD analysis; X3 — Fisher, Hessian, derivatives and implicit differentiation.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2023/hash/389cfad711d2b1e2128e931feee80230-Abstract-Conference.html>)

**Quantity:** Block-diagonal gradient second-moment matrices and their preconditioners.

**Computational idea:** Represent each block as B R_i B^T. Update the common basis through randomized subspace iteration, reusing the previous basis and structured matrix products without materializing the full blocks.

**Scope:** Deep learning. **Qualification:** The approximation concerns gradient second-moment blocks, not the two EMA Kronecker factors of KFAC. Shared-basis and block-diagonal restrictions discard information. Reported experiments include autoencoders and a 19.3M-parameter Transformer, not billion-parameter LLM pretraining.

**Research note relevance:** Approximates second-moment blocks using one shared low-rank basis per layer and a separate small coefficient matrix for each block. An online update maintains this structure during training, providing a related design for low-rank preconditioning beyond KFAC.

**Evidence:** Official NeurIPS 2023 proceedings metadata and abstract; targeted full-text passage checked.

- [Targeted passage](<https://proceedings.neurips.cc/paper_files/paper/2023/file/389cfad711d2b1e2128e931feee80230-Paper-Conference.pdf>): Section 2.2, equation (4), online shared-basis update and equation (5), pages 4-5; introduction for benchmark scope. Checked shared basis with per-block dense coefficients and implicit randomized basis updates.

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

### Efficient Adaptive Federated Optimization

**NeurIPS 2025 · Accept (poster)** · Su Hyeong Lee; Sidharth Sharma; Manzil Zaheer; Tian Li

[Primary source](<https://openreview.net/forum?id=dopfjQFr65>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116984>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/fab71c08b15508fd6c435e59b0e82b68-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** E — Training stabilization and distributed optimization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/fab71c08b15508fd6c435e59b0e82b68-Abstract-Conference.html>)

**Optimizer relevance:** FedAda2 and FedAda2++ reduce communication of adaptive preconditioners and memory use in federated learning, with image and text experiments.

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

### Fira: Can We Achieve Full-rank Training of LLMs Under Low-rank Constraint?

**NeurIPS 2025 · Accept (poster)** · Xi Chen; Kaituo Feng; Changsheng Li; Xunhao Lai; Xiangyu Yue; Ye Yuan; Guoren Wang

[Primary source](<https://openreview.net/forum?id=7aSBAw7tJf>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119690>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/aeae2c860cbe283ef73344c4ecd52567-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** D — Memory-efficient and low-precision optimizers.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/aeae2c860cbe283ef73344c4ecd52567-Abstract-Conference.html>)

**Optimizer relevance:** Fira combines full-rank weight updates with low-rank optimizer states, norm scaling and growth control.

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

### Local Curvature Descent: Squeezing More Curvature out of Standard and Polyak Gradient Descent

**NeurIPS 2025 · Accept (poster)** · Peter Richtarik; Simone Maria Giancola; Dymitr Lubczyk; Robin Yadav

[Primary source](<https://openreview.net/forum?id=EqWZ1yVRfN>) · [Venue page](<https://neurips.cc/virtual/2025/poster/119093>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/107aaa54d9481515e981e332e2e115b1-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** G — Optimizer theory, benchmarks, and training dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/107aaa54d9481515e981e332e2e115b1-Abstract-Conference.html>)

**Optimizer relevance:** Local Curvature Descent uses matrix-valued local curvature models for convex optimization; useful foundations rather than a demonstrated general LLM optimizer.

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

### RidgeLoRA: Matrix Ridge Enhanced Low-Rank Adaptation of Large Language Models

**NeurIPS 2025 · Accept (spotlight)** · Junda Zhu; Jun Ai; Yujun Li; Yichun Yin; Yasheng Wang; Lifeng Shang; Qun Liu

[Primary source](<https://openreview.net/forum?id=0RF80tUWuv>) · [Venue page](<https://neurips.cc/virtual/2025/poster/120320>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/31dc7ab2a83641aa58b57017545f0e7e-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/31dc7ab2a83641aa58b57017545f0e7e-Abstract-Conference.html>)

**Optimizer relevance:** RidgeLoRA uses a ridge-based formulation to improve how low-rank fine-tuning approximates full-rank adaptation.

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

### SING: SDE Inference via Natural Gradients

**NeurIPS 2025 · Accept (poster)** · Amber Hu; Henry Smith; Scott Linderman

[Primary source](<https://openreview.net/forum?id=jmnt0F21K7>) · [Venue page](<https://neurips.cc/virtual/2025/poster/116435>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/e23b1d49a1fe9732e6d6175006113010-Paper-Conference.pdf>)

**Topics:** Optimizer.

**Categories:** J — Adjacent numerical, architectural, and specialized training methods.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/e23b1d49a1fe9732e6d6175006113010-Abstract-Conference.html>)

**Optimizer relevance:** SING develops natural-gradient variational inference for latent SDEs, exploiting structure and parallel computation.

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

### Brand New K-FACs: Speeding up K-FAC with Online Decomposition Updates

**arXiv · 2022 · Preprint** · Constantin Octavian Puiu

[Primary source](<https://arxiv.org/abs/2210.08494>) · [PDF](<https://arxiv.org/pdf/2210.08494v2>)

**Topics:** Matrix computation; Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X2 — Eigenproblems, spectral computation and SVD analysis.

**Quantity:** Online low-rank representations and inverse applications for EMA KFAC factors.

**Computational idea:** Scale the retained eigenvalues by the EMA decay and apply a symmetric Brand update for the incoming factor. Algorithm 4 truncates to rank r before the update and uses the expanded rank r + minibatch-size representation for preconditioning.

**Scope:** Deep learning. **Qualification:** Truncation accumulates approximation error; speed depends on rank plus minibatch size being small relative to layer width. First posted in 2022, revised in September 2023; the source-provided BibTeX cites the 2023 revision. Listed as a preprint.

**Research note relevance:** B-KFAC maintains a low-rank eigendecomposition of EMA KFAC factors using a symmetric version of Brand's online SVD update. It reuses the previous decomposition and incorporates incoming minibatch factors, making it directly relevant to online low-rank curvature tracking.

**Evidence:** arXiv metadata and abstract, version 2 (12 September 2023); targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/pdf/2210.08494v2>): Section 2.3 (symmetric Brand update), Section 3.1 and Algorithm 4, pages 6-8. Checked EMA scaling, truncation before the update, the expanded representation used for the inverse, and the conditional width-scaling claim.

### Randomized K-FACs: Speeding up K-FAC with Randomized Numerical Linear Algebra

**arXiv · 2022 · Preprint** · Constantin Octavian Puiu

[Primary source](<https://arxiv.org/abs/2206.15397>) · [PDF](<https://arxiv.org/pdf/2206.15397v3>)

**Topics:** Matrix computation; Optimizer.

**Categories:** A — KFAC / EKFAC methods, applications, and substantive evaluations; X2 — Eigenproblems, spectral computation and SVD analysis; X4 — Randomized sketching and kernel approximations.

**Quantity:** Leading eigenspaces and approximate damped inverses of EMA KFAC factors.

**Computational idea:** Replace a full factor eigendecomposition with randomized low-rank decomposition. Unlike Brand New K-FACs, the decomposition is recomputed rather than maintained through online Brand updates.

**Scope:** Deep learning. **Qualification:** Low-rank truncation and randomized projection introduce error. The spectral result assumes bounds on incoming factors and a lower bound on the leading eigenvalue; it is not an unconditional fixed-rank guarantee. Verified as a 2022 arXiv preprint, not an accepted conference paper.

**Research note relevance:** RS-KFAC and SRE-KFAC use randomized SVD or symmetric randomized eigendecomposition to retain leading modes of exponentially averaged KFAC factors. The paper motivates this approximation using spectral decay induced by EMA updates, with theory under stated assumptions and empirical evidence.

**Evidence:** arXiv metadata and abstract, version 3 (25 November 2022); targeted full-text passage checked.

- [Targeted passage](<https://arxiv.org/pdf/2206.15397v3>): Sections 2.2-2.3 and Section 3, Proposition 3.1. Checked randomized SVD/EVD, the two approximation-error sources, and the assumptions in the EMA eigenspectrum bound.
