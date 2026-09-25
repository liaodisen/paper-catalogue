# Learning rates, scaling laws and training dynamics

208 accepted main-conference papers. Updated 2026-09-24. Topic membership overlaps; most annotations are based on accepted abstracts, with targeted full-text checks labeled.

### $\mathbf{Li_2}$: A Framework on Dynamics of Feature Emergence and Delayed Generalization

**ICLR 2026 · Accept (Poster)** · Yuandong Tian

[OpenReview](<https://openreview.net/forum?id=ceIBRhJpUr>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008484>) · [PDF](<https://openreview.net/pdf?id=ceIBRhJpUr>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Li2 models feature emergence and delayed generalization, including a mechanistic explanation for the effectiveness of Muon-like optimization.

**Training dynamics relevance:** Li2 models feature emergence and delayed generalization, including a mechanistic explanation for the effectiveness of Muon-like optimization.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Feature emergence; delayed generalization; optimizer.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### $\mu$LO: Compute-Efficient Meta-Generalization of Learned Optimizers

**ICLR 2026 · Accept (Poster)** · Benjamin Thérien; Charles-Étienne Joseph; Boris Knyazev; Edouard Oyallon; Irina Rish; Eugene Belilovsky

[OpenReview](<https://openreview.net/forum?id=f8z2bzOLK2>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008268>) · [PDF](<https://openreview.net/pdf?id=f8z2bzOLK2>)

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; T3 — Width/depth scaling and hyperparameter transfer.

**Optimizer relevance:** MuLO derives maximal-update parameterizations for learned optimizers to improve generalization to wider networks and longer training horizons.

**Training dynamics relevance:** MuLO derives maximal-update parameterizations for learned optimizers to improve generalization to wider networks and longer training horizons.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Learned-optimizer parameterization; width; training horizon.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### A Theoretical Analysis of Mamba’s Training Dynamics: Filtering Relevant Features for Generalization in State Space Models

**ICLR 2026 · Accept (Poster)** · Mugunthan Shandirasegaran; Hongkang Li; Songyang Zhang; Meng Wang; Shuai Zhang

[OpenReview](<https://openreview.net/forum?id=hvpKqEYJjj>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008011>) · [PDF](<https://openreview.net/pdf?id=hvpKqEYJjj>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Explains feature selection by a simplified Mamba block through non-asymptotic learning dynamics.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Signal/noise ratio; training time; sample size.

**Training qualification:** The model is single-layer/single-head with structured synthetic data.

**Evidence:** Official accepted-paper title and abstract.

### A universal compression theory for lottery ticket hypothesis and neural scaling laws

**ICLR 2026 · Accept (Poster)** · Hong-Yi Wang; Di Luo; Tomaso Poggio; Isaac Chuang; Liu Ziyin

[OpenReview](<https://openreview.net/forum?id=vxkzW4ljeX>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006767>) · [PDF](<https://openreview.net/pdf?id=vxkzW4ljeX>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Develops permutation-invariant compression theory with consequences for learning dynamics and scaling laws.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Width; sample size; compression level.

**Training qualification:** Asymptotic existence/construction results are not an off-the-shelf compression recipe for any pretrained LLM.

**Evidence:** Official accepted-paper title and abstract.

### Adaptive Methods Are Preferable in High Privacy Settings: An SDE Perspective

**ICLR 2026 · Accept (Poster)** · Enea Monzio Compagnoni; Alessandro Stanghellini; Rustem Islamov; Aurelien Lucchi; Anastasia Koloskova

[OpenReview](<https://openreview.net/forum?id=hSpA4DAoMk>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008058>) · [PDF](<https://openreview.net/pdf?id=hSpA4DAoMk>)

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** SDE analysis compares private SGD and sign/adaptive methods under privacy noise and studies hyperparameter transfer across privacy levels.

**Training dynamics relevance:** SDE analysis compares private SGD and sign/adaptive methods under privacy noise and studies hyperparameter transfer across privacy levels.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Privacy noise; adaptive updates; hyperparameter transfer.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### ATLAS: Adaptive Transfer Scaling Laws for Multilingual Pretraining, Finetuning, and Decoding the Curse of Multilinguality

**ICLR 2026 · Accept (Poster)** · Shayne Longpre; Sneha Kudugunta; Niklas Muennighoff; I-Hung Hsu; Isaac Caswell; Alex Pentland; Sercan Arik; Chen-Yu Lee; Sayna Ebrahimi

[OpenReview](<https://openreview.net/forum?id=0BkvUY61MX>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011962>) · [PDF](<https://openreview.net/pdf?id=0BkvUY61MX>)

**Categories:** T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** ATLAS models multilingual transfer and resource allocation, including when multilingual fine-tuning beats training from scratch.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Language mixture; model size; data size; pretrain/fine-tune allocation.

**Training qualification:** Cross-language transfer is estimated empirically and varies by the evaluated languages and data.

**Evidence:** Official accepted-paper title and abstract.

### Beyond Outliers: A Study of Optimizers Under Quantization

**ICLR 2026 · Accept (Poster)** · Georgios Vlassis; Saleh Ashkboos; Alexandra Volkova; Torsten Hoefler; Dan Alistarh

[OpenReview](<https://openreview.net/forum?id=mVldAuDAn5>) · [Official program](<https://iclr.cc/virtual/2026/poster/10007569>) · [PDF](<https://openreview.net/pdf?id=mVldAuDAn5>)

**Categories:** D — Memory-efficient and low-precision optimizers; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Systematic study of how optimizer choice affects post-training quantization and quantization-aware training; compares six optimizers and analyzes quantization scaling.

**Training dynamics relevance:** Systematic study of how optimizer choice affects post-training quantization and quantization-aware training; compares six optimizers and analyzes quantization scaling.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Optimizer choice; quantization; precision.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Can Small Training Runs Reliably Guide Data Curation? Rethinking Proxy-Model Practice

**ICLR 2026 · Accept (Poster)** · Jiachen (Tianhao) Wang; Tong Wu; Kaifeng Lyu; James Y Zou; Dawn Song; Ruoxi Jia; Prateek Mittal

[OpenReview](<https://openreview.net/forum?id=2FZC0c06jP>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011765>) · [PDF](<https://openreview.net/pdf?id=2FZC0c06jP>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Shows small-model data rankings can flip with hyperparameters and studies reduced proxy rates as a more reliable comparison protocol.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Proxy learning rate; data recipe; tuning budget; scale.

**Training qualification:** A theoretical ordering result is for random-feature models; LLM reliability is empirically tested across recipes.

**Evidence:** Official accepted-paper title and abstract.

### Cautious Weight Decay

**ICLR 2026 · Accept (Poster)** · Lizhang Chen; Jonathan Li; Kaizhao Liang; Baiyu Su; Cong Xie; Chen Liang; Ni Lao; Qiang Liu

[OpenReview](<https://openreview.net/forum?id=Gwe6gbGng5>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010446>) · [PDF](<https://openreview.net/pdf?id=Gwe6gbGng5>)

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Cautious Weight Decay applies decay only where parameter and optimizer-update signs agree; a drop-in modification tested with AdamW, Lion, and Muon in LM pretraining.

**Training dynamics relevance:** Cautious Weight Decay applies decay only where parameter and optimizer-update signs agree; a drop-in modification tested with AdamW, Lion, and Muon in LM pretraining.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Weight-decay masking; update signs.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Comparing the learning dynamics of in-context learning and fine-tuning in language models

**ICLR 2026 · Accept (Poster)** · Basile Confavreux; Aaditya Singh; Jin Hwa Lee; Amaury Sabran; Andrew Saxe

[OpenReview](<https://openreview.net/forum?id=cJAtzOcAnd>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008523>) · [PDF](<https://openreview.net/pdf?id=cJAtzOcAnd>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Compares how ICL and SFT change representations and inherited task priors.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** In-context examples; fine-tuning; training stage.

**Training qualification:** The study uses medium-sized models and distinguishes activation adaptation from weight training.

**Evidence:** Official accepted-paper title and abstract.

### Completed Hyperparameter Transfer across Modules, Width, Depth, Batch and Duration

**ICLR 2026 · Accept (Poster)** · Bruno Mlodozeniec; Pierre Ablin; Louis Béthune; Dan Busbridge; Michal Klein; Jason Ramapuram; marco cuturi

[OpenReview](<https://openreview.net/forum?id=elB9k4nTL1>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008289>) · [PDF](<https://openreview.net/pdf?id=elB9k4nTL1>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T3 — Width/depth scaling and hyperparameter transfer; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Studies hyperparameter transfer across width, depth, modules, batch size, and training duration, including Adam parameters and weight decay in LLM training.

**Training dynamics relevance:** Studies hyperparameter transfer across width, depth, modules, batch size, and training duration, including Adam parameters and weight decay in LLM training.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Modules; width; depth; batch size; duration; Adam betas; weight decay.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Compute-Optimal Quantization-Aware Training

**ICLR 2026 · Accept (Poster)** · Aleksandr Dremov; David Grangier; Angelos Katharopoulos; Awni Hannun

[OpenReview](<https://openreview.net/forum?id=QpbtT95S95>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009552>) · [PDF](<https://openreview.net/pdf?id=QpbtT95S95>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Models the optimal precision-training allocation and combines learning-rate cooldown with QAT.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** QAT duration; FP/QAT compute split; bit width; cooldown.

**Training qualification:** Optimal ratios depend on budget, precision and model size; fixed ratios need not transfer.

**Evidence:** Official accepted-paper title and abstract.

### Convex Dominance in Deep Learning I: A Scaling Law of Loss and Learning Rate

**ICLR 2026 · Accept (Poster)** · Zhiqi Bu; Shiyun Xu; Jialin Mao

[OpenReview](<https://openreview.net/forum?id=dSdLqg02tx>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008408>) · [PDF](<https://openreview.net/pdf?id=dSdLqg02tx>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T4 — Compute, data and model scaling laws.

**Optimizer relevance:** Models loss and optimal learning-rate scaling using approximately convex training dynamics across model sizes and training horizons.

**Training dynamics relevance:** Models loss and optimal learning-rate scaling using approximately convex training dynamics across model sizes and training horizons.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Learning rate; model scale; training horizon.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### DNT: a Deeply Normalized Transformer that can be trained by Momentum SGD

**ICLR 2026 · Accept (Poster)** · Xianbiao Qi; Marco Chen; Wenjie Xiao; Jiaquan Ye; Yelin He; Chun-Guang Li; Zhouchen Lin

[OpenReview](<https://openreview.net/forum?id=62pn18XmAg>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011405>) · [PDF](<https://openreview.net/pdf?id=62pn18XmAg>)

**Categories:** E — Training stabilization and distributed optimization; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** DNT modifies Transformer normalization to make gradients more suitable for momentum SGD; includes GPT and ViT training experiments.

**Training dynamics relevance:** DNT modifies Transformer normalization to make gradients more suitable for momentum SGD; includes GPT and ViT training experiments.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Transformer normalization; momentum SGD.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Egalitarian Gradient Descent: A Simple Approach to Accelerated Grokking

**ICLR 2026 · Accept (Poster)** · Ali Saheb Pasand; Elvis Dohmatob

[OpenReview](<https://openreview.net/forum?id=wCnHeql3ow>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006751>) · [PDF](<https://openreview.net/pdf?id=wCnHeql3ow>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Egalitarian Gradient Descent equalizes movement across gradient singular directions to accelerate grokking; general optimizer theory rather than an LLM-scale result.

**Training dynamics relevance:** Egalitarian Gradient Descent equalizes movement across gradient singular directions to accelerate grokking; general optimizer theory rather than an LLM-scale result.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Gradient singular directions; delayed generalization.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Explaining Grokking and Information Bottleneck through Neural Collapse Emergence

**ICLR 2026 · Accept (Poster)** · Keitaro Sakamoto; Issei Sato

[OpenReview](<https://openreview.net/forum?id=sLX5P7FTfT>) · [Official program](<https://iclr.cc/virtual/2026/poster/10007064>) · [PDF](<https://openreview.net/pdf?id=sLX5P7FTfT>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Explains late generalization and information compression through different timescales of data fitting and neural collapse.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Training timescales; within-class representation variance.

**Training qualification:** The proposed explanation is evaluated under its model and dataset assumptions.

**Evidence:** Official accepted-paper title and abstract.

### Fantastic Pretraining Optimizers and Where to Find Them

**ICLR 2026 · Accept (Poster)** · Kaiyue Wen; David Hall; Tengyu Ma; Percy Liang

[OpenReview](<https://openreview.net/forum?id=2J51qUZ0iG>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011758>) · [PDF](<https://openreview.net/pdf?id=2J51qUZ0iG>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T3 — Width/depth scaling and hyperparameter transfer; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Controlled benchmark of ten pretraining optimizers across model and token budgets; stresses fair tuning and final-budget evaluation when comparing Muon, SOAP, AdamW, and alternatives.

**Training dynamics relevance:** Controlled benchmark of ten pretraining optimizers across model and token budgets; stresses fair tuning and final-budget evaluation when comparing Muon, SOAP, AdamW, and alternatives.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Optimizer comparison; hyperparameter budget; final training budget.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Fast Catch-Up, Late Switching: Optimal Batch Size Scheduling via Functional Scaling Laws

**ICLR 2026 · Accept (Poster)** · Jinbo Wang; Binghui Li; Zhanpeng Zhou; Mingze Wang; yuxuan sun; Jiaqi Zhang; Xunliang Cai; Lei Wu

[OpenReview](<https://openreview.net/forum?id=PXWgzUkVwo>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009661>) · [PDF](<https://openreview.net/pdf?id=PXWgzUkVwo>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T2 — Batch size, gradient noise and training efficiency; T4 — Compute, data and model scaling laws.

**Optimizer relevance:** Uses functional scaling laws to derive batch-size schedules and explains late-switch fast catch-up; evaluates dense and MoE LLM pretraining.

**Training dynamics relevance:** Uses functional scaling laws to derive batch-size schedules and explains late-switch fast catch-up; evaluates dense and MoE LLM pretraining.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Batch-size scheduling; late switching; training budget.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Fast Escape, Slow Convergence: Learning Dynamics of Phase Retrieval under Power-Law Data

**ICLR 2026 · Accept (Oral)** · Guillaume Braun; Bruno Loureiro; Minh Ha Quang; Masaaki Imaizumi

[OpenReview](<https://openreview.net/forum?id=Ae4eZpkXBX>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011017>) · [PDF](<https://openreview.net/pdf?id=Ae4eZpkXBX>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Derives fast-escape, slow-convergence and spectral-tail phases that determine scaling of nonlinear regression error.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Training time; data anisotropy; spectral decay.

**Training qualification:** The formal problem is phase retrieval with power-law Gaussian covariance.

**Evidence:** Official accepted-paper title and abstract.

### Generalization Below the Edge of Stability: The Role of Data Geometry

**ICLR 2026 · Accept (Poster)** · Tongtong Liang; Alexander Cloninger; Rahul Parhi; Yu-Xiang Wang

[OpenReview](<https://openreview.net/forum?id=zVmS7G6Dyi>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006451>) · [PDF](<https://openreview.net/pdf?id=zVmS7G6Dyi>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T5 — Stability, curvature and edge-of-stability dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Shows how data geometry changes generalization and memorization for stable two-layer ReLU training.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Step size; input geometry; intrinsic dimension.

**Training qualification:** The guarantees apply below the edge of stability under specified data distributions.

**Evidence:** Official accepted-paper title and abstract.

### Gradient Descent with Large Step Sizes: Chaos and Fractal Convergence Region

**ICLR 2026 · Accept (Poster)** · Shuang Liang; Guido Montufar

[OpenReview](<https://openreview.net/forum?id=wsxGCaBjWC>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006694>) · [PDF](<https://openreview.net/pdf?id=wsxGCaBjWC>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Analyzes chaotic sensitivity and fractal convergence boundaries near critical learning rates.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Step size; initialization; regularization.

**Training qualification:** Results concern scalar-vector and matrix factorization with specified initialization structure.

**Evidence:** Official accepted-paper title and abstract.

### Grokking in LLM Pretraining? Monitor Memorization-to-Generalization without Test

**ICLR 2026 · Accept (Poster)** · Ziyue Li; Chenrui Fan; Tianyi Zhou

[OpenReview](<https://openreview.net/forum?id=blfwRondjY>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008581>) · [PDF](<https://openreview.net/pdf?id=blfwRondjY>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Training dynamics relevance:** Uses expert-pathway similarity and consistency to monitor local memorization-to-generalization transitions.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Pretraining duration; MoE routing geometry.

**Training qualification:** Reported grokking is distribution-dependent within near-single-pass MoE training, not identical to classic multi-epoch toy grokking.

**Evidence:** Official accepted-paper title and abstract.

### High-dimensional limit theorems for SGD: Momentum and Adaptive Step-sizes

**ICLR 2026 · Accept (Poster)** · Aukosh Jagannath; Taj Jones-McCormick; Varnan Sarangian

[OpenReview](<https://openreview.net/forum?id=5OJLOwwXV4>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011471>) · [PDF](<https://openreview.net/pdf?id=5OJLOwwXV4>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T1 — Learning-rate selection, warm-up and schedules; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** High-dimensional limits compare SGD, momentum, and adaptive step sizes on tensor PCA and single-index models; supporting theory, not an LLM benchmark.

**Training dynamics relevance:** High-dimensional limits compare SGD, momentum, and adaptive step sizes on tensor PCA and single-index models; supporting theory, not an LLM benchmark.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Momentum; adaptive steps; dimension.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### How does the optimizer implicitly bias the model merging loss landscape?

**ICLR 2026 · Accept (Poster)** · Chenxiang Zhang; Alexander Theus; Damien Teney; Antonio Orvieto; Jun Pang; Sjouke Mauw

[OpenReview](<https://openreview.net/forum?id=RU76KTF1Da>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009486>) · [PDF](<https://openreview.net/pdf?id=RU76KTF1Da>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Relates learning rate, weight decay, batch size, and augmentation to effective optimizer noise and the mergeability of independently fine-tuned models.

**Training dynamics relevance:** Relates learning rate, weight decay, batch size, and augmentation to effective optimizer noise and the mergeability of independently fine-tuned models.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Learning rate; weight decay; batch size; model merging.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### How Learning Rate Decay Wastes Your Best Data in Curriculum-Based LLM Pretraining

**ICLR 2026 · Accept (Oral)** · Kairong Luo; Zhenbo Sun; Haodong Wen; Xinyu Shi; Jiarui Cui; Chenyi Dang; Kaifeng Lyu; Wenguang Chen

[OpenReview](<https://openreview.net/forum?id=T5wkZJqzkz>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009351>) · [PDF](<https://openreview.net/pdf?id=T5wkZJqzkz>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T4 — Compute, data and model scaling laws.

**Optimizer relevance:** Studies conflicts between learning-rate decay and data-quality curricula; tests moderate decay and checkpoint averaging in LLM pretraining.

**Training dynamics relevance:** Studies conflicts between learning-rate decay and data-quality curricula; tests moderate decay and checkpoint averaging in LLM pretraining.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Rate decay; data curriculum; checkpoint averaging.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### How Text Quality Interventions Reshape Neural Scaling Laws for LLMs: Empirical Study

**ICLR 2026 · Accept (Poster)** · Newsha Ardalani; Feiyang Kang; Michael Kuchnik; Mostafa Elhoushi; Shubho Sengupta; Shang-Wen Li; Carole-Jean Wu

[OpenReview](<https://openreview.net/forum?id=ZC5QBfdOw7>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008830>) · [PDF](<https://openreview.net/pdf?id=ZC5QBfdOw7>)

**Categories:** T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Shows that data-quality interventions can change scaling coefficients, exponents and compute-optimal data/model allocations.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Deduplication; filtering; rewriting; token/parameter ratio.

**Training qualification:** Recipe rankings can reverse with scale; fitted laws should not be transferred blindly between corpora.

**Evidence:** Official accepted-paper title and abstract.

### Implicit Bias and Loss of Plasticity in Matrix Completion: Depth Promotes Low-Rankness

**ICLR 2026 · Accept (Poster)** · Baekrok Shin; Chulhee Yun

[OpenReview](<https://openreview.net/forum?id=NYOYJr988x>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009856>) · [PDF](<https://openreview.net/pdf?id=NYOYJr988x>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Explains depth-dependent low-rank bias and loss of plasticity through coupled matrix-factorization dynamics.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Depth; initialization; pretraining observations.

**Training qualification:** Formal conclusions use block-diagonal observations and structured initializations.

**Evidence:** Official accepted-paper title and abstract.

### Implicit Bias of Per-sample Adam on Separable Data: Departure from the Full-batch Regime

**ICLR 2026 · Accept (Poster)** · Beomhan Baek; Minhak Song; Chulhee Yun

[OpenReview](<https://openreview.net/forum?id=LJdAdCo3BN>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010047>) · [PDF](<https://openreview.net/pdf?id=LJdAdCo3BN>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T2 — Batch size, gradient noise and training efficiency; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Shows that per-sample Adam can have a different implicit max-margin bias from full-batch Adam; contrasts its batch dependence with Signum.

**Training dynamics relevance:** Shows that per-sample Adam can have a different implicit max-margin bias from full-batch Adam; contrasts its batch dependence with Signum.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Per-sample versus full-batch Adam; implicit bias.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Implicit bias produces neural scaling laws in learning curves, from perceptrons to deep networks

**ICLR 2026 · Accept (Poster)** · Francesco DAmico; Dario Bocchi; Matteo Negri

[OpenReview](<https://openreview.net/forum?id=qBAV2DEvAC>) · [Official program](<https://iclr.cc/virtual/2026/poster/10007275>) · [PDF](<https://openreview.net/pdf?id=qBAV2DEvAC>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Finds dynamical scaling laws along learning curves and relates them to implicit bias.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Training time; parameter norm; model complexity.

**Training qualification:** Formal support uses logistic perceptrons, with empirical CNN/ResNet/ViT extensions.

**Evidence:** Official accepted-paper title and abstract.

### Implicit Regularization of SGD Reduces Shortcut Learning

**ICLR 2026 · Accept (Poster)** · Nahal Mirzaie; Alireza Alipanah; Ali Abbasi; Amirmahdi Farzane; Hossein Jafarinia; Erfan Sobhaei; Mahdi Ghaznavi; Amir Najafi; Mahdieh Baghshah; Mohammad Hossein Rohban

[OpenReview](<https://openreview.net/forum?id=CPdAB7H8mU>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010861>) · [PDF](<https://openreview.net/pdf?id=CPdAB7H8mU>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Links larger learning rates and smaller batches to stronger SGD regularization against shortcut features.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Learning rate; batch size; stochastic versus full gradients.

**Training qualification:** The theory is linear, with supporting deep-network experiments; GD need not share the effect.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/mirzanahal/sgd-implicit-regularization-shortcuts>). Links extracted from the accepted abstract; code was not tested.

### Intrinsic training dynamics of deep neural networks

**ICLR 2026 · Accept (Poster)** · Sibylle Marcotte; Gabriel Peyré; Rémi Gribonval

[OpenReview](<https://openreview.net/forum?id=IlyesljaNb>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010269>) · [PDF](<https://openreview.net/pdf?id=IlyesljaNb>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; M5 — Supporting geometry, statistics, and training-dynamics papers; T6 — Feature learning, implicit bias and generalization dynamics.

**Optimizer relevance:** Characterizes when parameter gradient flow induces intrinsic lower-dimensional dynamics, with results for ReLU path lifting and relaxed-balanced linear networks.

**Manifold relevance:** Analyzes when ordinary gradient flow can be rewritten intrinsically, including relaxed-balanced deep linear networks; optimization geometry theory rather than a new constrained solver.

**Training dynamics relevance:** Characterizes when parameter gradient flow induces intrinsic lower-dimensional dynamics, with results for ReLU path lifting and relaxed-balanced linear networks.

**Geometry:** Intrinsic metrics and lower-dimensional lifted parameter dynamics. **Manifold scope:** Related/supporting.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Parameterization; intrinsic gradient-flow trajectories.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Minor First, Major Last: A Depth-Induced Implicit Bias of Sharpness-Aware Minimization

**ICLR 2026 · Accept (Poster)** · Chaewon Moon; Dongkuk Si; Chulhee Yun

[OpenReview](<https://openreview.net/forum?id=ErnnE2UNI2>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010640>) · [PDF](<https://openreview.net/pdf?id=ErnnE2UNI2>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T5 — Stability, curvature and edge-of-stability dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Shows sequential feature amplification and initialization-dependent implicit bias under SAM.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** SAM norm/radius; depth; initialization; training duration.

**Training qualification:** The formal setting is linear diagonal networks; finite-time and infinite-time conclusions differ.

**Evidence:** Official accepted-paper title and abstract.

### Never Saddle for Reparameterized Steepest Descent as Mirror Flow

**ICLR 2026 · Accept (Poster)** · Tom Jacobs; Chao Zhou; Rebekka Burkholz

[OpenReview](<https://openreview.net/forum?id=YgudIlQ9nC>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008875>) · [PDF](<https://openreview.net/pdf?id=YgudIlQ9nC>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Steepest mirror flows explain optimizer-dependent feature learning and saddle escape in diagonal networks, with implications for Adam/AdamW fine-tuning.

**Training dynamics relevance:** Steepest mirror flows explain optimizer-dependent feature learning and saddle escape in diagonal networks, with implications for Adam/AdamW fine-tuning.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Reparameterization; mirror geometry; saddle escape.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### On Optimal Hyperparameters for Differentially Private Deep Transfer Learning

**ICLR 2026 · Accept (Poster)** · Aki Rehn; Linzh Zhao; Mikko Heikkilä; Antti Honkela

[OpenReview](<https://openreview.net/forum?id=V3fEo612nE>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009176>) · [PDF](<https://openreview.net/pdf?id=V3fEo612nE>)

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; T2 — Batch size, gradient noise and training efficiency; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Studies clipping thresholds and batch sizes for differentially private transfer learning, including interaction with privacy level and compute budget.

**Training dynamics relevance:** Studies clipping thresholds and batch sizes for differentially private transfer learning, including interaction with privacy level and compute budget.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Private fine-tuning batch size; clipping; privacy budget.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### On Predictability of Reinforcement Learning Dynamics for Large Language Models

**ICLR 2026 · Accept (Poster)** · Cai Yuchen; Ding Cao; Xin Xu; Zijun Yao; Yuqing Huang; Benyi Zhang; Zhenyu Tan; Guiquan Liu; Junfeng Fang

[OpenReview](<https://openreview.net/forum?id=SdHmA6BYVJ>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009393>) · [PDF](<https://openreview.net/pdf?id=SdHmA6BYVJ>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Training dynamics relevance:** Reports dominant low-rank, approximately linear parameter-update dynamics and uses them for early extrapolation.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** RL training horizon; early-checkpoint updates.

**Training qualification:** Predictability is empirical over tested models and RL algorithms, not universal exact rank-one dynamics.

**Evidence:** Official accepted-paper title and abstract.

### On the Convergence Behavior of Preconditioned Gradient Descent Toward the Rich Learning Regime

**ICLR 2026 · Accept (Poster)** · Shuai Jiang; Eric Cyr; Ben Southworth; Alexey Voronin

[OpenReview](<https://openreview.net/forum?id=CXlsqTAf1E>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010848>) · [PDF](<https://openreview.net/pdf?id=CXlsqTAf1E>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Studies how preconditioned gradient descent changes spectral bias and grokking, including Gauss-Newton methods; separates conjectures about rich learning from proved results.

**Training dynamics relevance:** Studies how preconditioned gradient descent changes spectral bias and grokking, including Gauss-Newton methods; separates conjectures about rich learning from proved results.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Preconditioning; feature-learning regime; grokking.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### On the Convergence Direction of Gradient Descent

**ICLR 2026 · Accept (Poster)** · Shuo Chen; Xiaolong Li; Jiaying Peng; Yao Zhao

[OpenReview](<https://openreview.net/forum?id=3U6wH7uAPZ>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011642>) · [PDF](<https://openreview.net/pdf?id=3U6wH7uAPZ>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Optimizer relevance:** Analyzes directional convergence and oscillatory behavior of gradient descent and connects it to edge-of-stability dynamics; SGD and Adam are studied empirically.

**Training dynamics relevance:** Analyzes directional convergence and oscillatory behavior of gradient descent and connects it to edge-of-stability dynamics; SGD and Adam are studied empirically.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Step size; oscillatory convergence direction.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Optimizer Choice Matters For The Emergence of Neural Collapse

**ICLR 2026 · Accept (Poster)** · Jim Zhao; Tin Sum Cheng; Wojciech Masarczyk; Aurelien Lucchi

[OpenReview](<https://openreview.net/forum?id=9EPYWJrib1>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011133>) · [PDF](<https://openreview.net/pdf?id=9EPYWJrib1>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Studies how optimizer choice and coupled versus decoupled weight decay affect neural collapse, including momentum effects.

**Training dynamics relevance:** Studies how optimizer choice and coupled versus decoupled weight decay affect neural collapse, including momentum effects.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Optimizer; momentum; coupled/decoupled decay; neural collapse.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Pre-training LLM without Learning Rate Decay Enhances Supervised Fine-Tuning

**ICLR 2026 · Accept (Poster)** · Kazuki Yano; Shun Kiyono; Sosuke Kobayashi; Sho Takase; Jun Suzuki

[OpenReview](<https://openreview.net/forum?id=JnebU2QLdH>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010172>) · [PDF](<https://openreview.net/pdf?id=JnebU2QLdH>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Compares constant-after-warmup and decaying pretraining learning rates through downstream SFT adaptability on 1B and 8B models.

**Training dynamics relevance:** Compares constant-after-warmup and decaying pretraining learning rates through downstream SFT adaptability on 1B and 8B models.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Pretraining decay; SFT adaptability.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Pre-training under infinite compute

**ICLR 2026 · Accept (Oral)** · Konwoo Kim; Suhas Kotha; Percy Liang; Tatsunori Hashimoto

[OpenReview](<https://openreview.net/forum?id=ck0aZTAnwK>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008473>) · [PDF](<https://openreview.net/pdf?id=ck0aZTAnwK>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Studies data-constrained pretraining and finds stronger regularization and ensembling change the attainable loss asymptote.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Epoch count; model size; weight decay; ensemble size.

**Training qualification:** Infinite compute is an extrapolative framing; finite empirical runs support the fitted asymptotes.

**Evidence:** Official accepted-paper title and abstract.

### Pretraining Scaling Laws for Generative Evaluations of Language Models

**ICLR 2026 · Accept (Poster)** · Rylan Schaeffer; Noam Levi; Brando Miranda; Sanmi Koyejo

[OpenReview](<https://openreview.net/forum?id=Ym33xJYINV>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008870>) · [PDF](<https://openreview.net/pdf?id=Ym33xJYINV>)

**Categories:** T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Fits scaling of generative benchmark pass-at-k and compares compute-based, size/data-based and reference-likelihood predictors.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Pretraining compute; tokens; parameters; evaluation k.

**Training qualification:** The chosen evaluation k changes fitted behavior; prediction of benchmark outcomes is not a training guarantee.

**Evidence:** Official accepted-paper title and abstract.

### Reshaping Reasoning in LLMs: A Theoretical Analysis of RL Training Dynamics through Pattern Selection

**ICLR 2026 · Accept (Poster)** · Xingwu Chen; Tianle Li; Difan Zou

[OpenReview](<https://openreview.net/forum?id=2OO399hRD6>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011748>) · [PDF](<https://openreview.net/pdf?id=2OO399hRD6>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Training dynamics relevance:** Models how RL changes reasoning-pattern distributions through sparse critical-token updates.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Reward type; base-model quality; RL training duration.

**Training qualification:** Theoretical cases distinguish verifiable from internal feedback and do not cover every RL objective.

**Evidence:** Official accepted-paper title and abstract.

### RL Grokking Recipe: How Does RL Unlock and Transfer New Algorithms in LLMs?

**ICLR 2026 · Accept (Poster)** · Yiyou Sun; Yuhan Cao; Pohao Huang; Haoyue Bai; Hanna Hajishirzi; Nouha Dziri; Dawn Song

[OpenReview](<https://openreview.net/forum?id=CJJ8VxOWbG>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010871>) · [PDF](<https://openreview.net/pdf?id=CJJ8VxOWbG>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Studies abrupt acquisition of new coding strategies and which training ingredients enable it.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** RL warm-up; replay; curriculum; verification.

**Training qualification:** Results use controlled synthetic coding families; transfer remains uneven across out-of-distribution tests.

**Evidence:** Official accepted-paper title and abstract.

### Saddle-to-Saddle Dynamics Explains A Simplicity Bias Across Neural Network Architectures

**ICLR 2026 · Accept (Poster)** · Yedi Zhang; Andrew Saxe; Peter Latham

[OpenReview](<https://openreview.net/forum?id=Vit5M0G5Gb>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009110>) · [PDF](<https://openreview.net/pdf?id=Vit5M0G5Gb>)

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

[OpenReview](<https://openreview.net/forum?id=GDYaNzxt9T>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010520>) · [PDF](<https://openreview.net/pdf?id=GDYaNzxt9T>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Shows that masked and uniform diffusion can have different compute-optimal parameter/data allocations.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Diffusion noise type; learning rate; batch size; model/data ratio.

**Training qualification:** Requires tuning the diffusion-specific recipe; autoregressive scaling prescriptions need not apply unchanged.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Laws and Spectra of Shallow Neural Networks in the Feature Learning Regime

**ICLR 2026 · Accept (Oral)** · Leonardo Defilippis; Yizhou Xu; Julius Girardin; Vittorio Erba; Emanuele Troiani; Lenka Zdeborova; Bruno Loureiro; Florent Krzakala

[OpenReview](<https://openreview.net/forum?id=Q3yLIIkt7z>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009624>) · [PDF](<https://openreview.net/pdf?id=Q3yLIIkt7z>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Derives scaling regimes and plateaus in feature-learning networks and relates them to learned spectra.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Sample complexity; weight decay; weight spectrum.

**Training qualification:** The detailed phase diagrams concern quadratic and diagonal models.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Laws for Diffusion Transformers

**ICLR 2026 · Accept (Poster)** · Zhengyang Liang; Hao He; Ceyuan Yang; Bo DAI

[OpenReview](<https://openreview.net/forum?id=T985gm4sDA>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009343>) · [PDF](<https://openreview.net/pdf?id=T985gm4sDA>)

**Categories:** T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Studies compute-optimal DiT scaling and connects training loss with image-generation quality.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Diffusion-transformer size; data volume; compute.

**Training qualification:** Vision-generation results are distinct from autoregressive language-model scaling.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Laws Meet Model Architecture: Toward Inference-Efficient LLMs

**ICLR 2026 · Accept (Poster)** · Song Bian; Tao Yu; Shivaram Venkataraman; Youngsuk Park

[OpenReview](<https://openreview.net/forum?id=0TmVqOpBbK>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011936>) · [PDF](<https://openreview.net/pdf?id=0TmVqOpBbK>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Adds architecture to scaling laws to jointly predict accuracy and inference efficiency.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Hidden width; MLP/attention ratio; GQA; training budget.

**Training qualification:** The conditional law is fitted over specific architecture/data ranges.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Laws of SignSGD in Linear Regression: When Does It Outperform SGD?

**ICLR 2026 · Accept (Poster)** · Jihwan Kim; Dogyoon Song; Chulhee Yun

[OpenReview](<https://openreview.net/forum?id=zVwRP0ikrx>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006450>) · [PDF](<https://openreview.net/pdf?id=zVwRP0ikrx>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Derives compute-optimal signSGD scaling and identifies drift normalization and noise reshaping relative to SGD.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Learning rate; WSD schedule; model size; spectrum.

**Training qualification:** The analysis uses power-law random-feature linear regression.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Laws Revisited: Modeling the Role of Data Quality in Language Model Pretraining

**ICLR 2026 · Accept (Poster)** · Anirudh Subramanyam; Yuxin Chen; Robert Grossman

[OpenReview](<https://openreview.net/forum?id=x54wwB6QvL>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006678>) · [PDF](<https://openreview.net/pdf?id=x54wwB6QvL>)

**Categories:** T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Extends Chinchilla-style scaling with an explicit quality variable estimated through corpus corruption/deficiency.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Data quality; tokens; parameters.

**Training qualification:** Controlled quality interventions do not capture every aspect of real-web data quality.

**Evidence:** Official accepted-paper title and abstract.

### Scaling with Collapse: Efficient and Predictable Training of LLM Families

**ICLR 2026 · Accept (Poster)** · Shane Bergsma; Bin Zhang; Nolan Dey; Shaheer Muhammad; Gurpreet Gosal; Joel Hestness

[OpenReview](<https://openreview.net/forum?id=3YKeB9R1g9>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011632>) · [PDF](<https://openreview.net/pdf?id=3YKeB9R1g9>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T4 — Compute, data and model scaling laws; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Uses normalized training-curve collapse to diagnose optimization pathologies and stop hyperparameter searches early when training LLM families.

**Training dynamics relevance:** Uses normalized training-curve collapse to diagnose optimization pathologies and stop hyperparameter searches early when training LLM families.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Training-curve collapse; tuning budget; model families.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Seesaw: Accelerating Training by Balancing Batch Size and Learning Rate Scheduling

**ICLR 2026 · Accept (Poster)** · Alexandru Meterez; Depen Morwani; Jingfeng Wu; Costin-Andrei Oncescu; Cengiz Pehlevan; Sham Kakade

[OpenReview](<https://openreview.net/forum?id=Nj0XBF2o7z>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009838>) · [PDF](<https://openreview.net/pdf?id=Nj0XBF2o7z>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency.

**Optimizer relevance:** Seesaw couples batch-size ramp-up with learning-rate scheduling to preserve training dynamics and reduce serial steps in LM pretraining.

**Training dynamics relevance:** Seesaw couples batch-size ramp-up with learning-rate scheduling to preserve training dynamics and reduce serial steps in LM pretraining.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Batch ramp-up; learning-rate schedule.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Shuffling the Data, Extrapolating the Step: Sharper Bias In Constant Step-Size SGD

**ICLR 2026 · Accept (Poster)** · Konstantinos Emmanouilidis; Emmanouil-Vasileios Vlatakis-Gkaragkounis; Rene Vidal

[OpenReview](<https://openreview.net/forum?id=QQZ53UtXgf>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009589>) · [PDF](<https://openreview.net/pdf?id=QQZ53UtXgf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency.

**Training dynamics relevance:** Combines random reshuffling and Richardson-Romberg extrapolation to reduce stationary bias in stochastic methods.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Constant step size; reshuffling; iterate extrapolation.

**Training qualification:** Guarantees concern structured variational inequalities and their regularity assumptions.

**Evidence:** Official accepted-paper title and abstract.

### Sign-SGD via Parameter-Free Optimization

**ICLR 2026 · Accept (Poster)** · Daniil Medyakov; Stanko Sergey; Gleb Molodtsov; Philip Zmushko; Grigoriy Evseev; Egor Petrov; Aleksandr Beznosikov

[OpenReview](<https://openreview.net/forum?id=yDLD3D95w3>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006577>) · [PDF](<https://openreview.net/pdf?id=yDLD3D95w3>)

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; T1 — Learning-rate selection, warm-up and schedules.

**Optimizer relevance:** Parameter-free Sign-SGD removes manual step-size selection, with momentum and sign-only memory variants; evaluated on LLaMA pretraining.

**Training dynamics relevance:** Parameter-free Sign-SGD removes manual step-size selection, with momentum and sign-only memory variants; evaluated on LLaMA pretraining.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Parameter-free step sizes; sign updates; momentum.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Stable-LoRA: Stabilizing Feature Learning of Low-Rank Adaptation

**ICLR 2026 · Accept (Poster)** · Yize Wu; KE GAO; Ling Li; Yanjun WU

[OpenReview](<https://openreview.net/forum?id=xSa19DAieH>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006643>) · [PDF](<https://openreview.net/pdf?id=xSa19DAieH>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Analyzes stable feature learning in LoRA and introduces early factor shrinkage to manage initialization-induced instability.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** LoRA factor initialization; scaling; early shrinkage.

**Training qualification:** The result concerns the specified LoRA parameterization and adaptation settings.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/Yize-Wu/Stable-LoRA.>). Links extracted from the accepted abstract; code was not tested.

### Study of Training Dynamics for Memory-Constrained Fine-Tuning

**ICLR 2026 · Accept (Poster)** · Aël Quélennec; Nour Hezbri; Pavlo Mozharovskyi; Van-Tam Nguyen; Enzo Tartaglione

[OpenReview](<https://openreview.net/forum?id=BhfIg0tuti>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010926>) · [PDF](<https://openreview.net/pdf?id=BhfIg0tuti>)

**Categories:** J — Adjacent numerical, architectural, and specialized training methods; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** TraDy combines layer selection and stochastic channel updates for memory-constrained fine-tuning; general transfer learning rather than a dedicated LLM optimizer.

**Training dynamics relevance:** TraDy combines layer selection and stochastic channel updates for memory-constrained fine-tuning; general transfer learning rather than a dedicated LLM optimizer.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Layer/channel selection; memory-limited fine-tuning.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

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

### Theoretical Modeling of Large Language Model Self-Improvement Training Dynamics Through Solver-Verifier Gap

**ICLR 2026 · Accept (Poster)** · Yifan Sun; Yushan Liang; Zhen Zhang; Xin Liu; Jiaye Teng

[OpenReview](<https://openreview.net/forum?id=Hh7x3c0cZl>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010371>) · [PDF](<https://openreview.net/pdf?id=Hh7x3c0cZl>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Models self-improvement trajectories and saturation through the gap between solving and verification abilities.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Solver-verifier gap; self-improvement stage; external data.

**Training qualification:** The fitted dynamics are conditional on the framework and available verifier signal.

**Evidence:** Official accepted-paper title and abstract.

### Theory of Scaling Laws for In-Context Regression: Depth, Width, Context and Time

**ICLR 2026 · Accept (Poster)** · Blake Bordelon; Mary Letey; Cengiz Pehlevan

[OpenReview](<https://openreview.net/forum?id=qA42mWsnbl>) · [Official program](<https://iclr.cc/virtual/2026/poster/10007276>) · [PDF](<https://openreview.net/pdf?id=qA42mWsnbl>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T2 — Batch size, gradient noise and training efficiency; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Derives resource-dependent in-context regression performance and optimal model shapes.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Depth; width; context length; batch size; training steps.

**Training qualification:** The solvable model is deep linear self-attention with structured Gaussian covariates.

**Evidence:** Official accepted-paper title and abstract.

### Towards Greater Leverage: Scaling Laws for Efficient Mixture-of-Experts Language Models

**ICLR 2026 · Accept (Poster)** · Changxin Tian; Kunlong Chen; Jia Liu; Ziqi Liu; Zhiqiang Zhang; JUN ZHOU

[OpenReview](<https://openreview.net/forum?id=7r2lkhDGUj>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011257>) · [PDF](<https://openreview.net/pdf?id=7r2lkhDGUj>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Fits MoE efficiency leverage relative to dense models and uses it to select architectures.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Expert activation ratio; granularity; compute.

**Training qualification:** The optimal expert granularity and efficiency depend on the training setup and budget.

**Evidence:** Official accepted-paper title and abstract.

### Training Dynamics Impact Post-Training Quantization Robustness

**ICLR 2026 · Accept (Poster)** · Albert Catalan-Tatjer; Niccolò Ajroldi; Jonas Geiping

[OpenReview](<https://openreview.net/forum?id=ZXr3Xx7Z1O>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008797>) · [PDF](<https://openreview.net/pdf?id=ZXr3Xx7Z1O>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Links post-training quantization degradation to the training recipe, especially learning-rate decay, through checkpoints and controlled runs.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Learning-rate decay; training duration; quantization.

**Training qualification:** Validation loss and quantization robustness are distinct objectives; the study does not imply data volume alone causes degradation.

**Evidence:** Official accepted-paper title and abstract.

### Transfer Learning in Infinite Width Feature Learning Networks

**ICLR 2026 · Accept (Poster)** · Clarissa Lauditi; Blake Bordelon; Cengiz Pehlevan

[OpenReview](<https://openreview.net/forum?id=Oox4QOhmi9>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009752>) · [PDF](<https://openreview.net/pdf?id=Oox4QOhmi9>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Quantifies transfer from pretraining through adaptive kernels in infinite-width feature-learning networks.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Source/target data; task alignment; feature-learning strength.

**Training qualification:** The asymptotic gradient-flow theory uses specified transfer settings; finite LLM adaptation is not directly guaranteed.

**Evidence:** Official accepted-paper title and abstract.

### Two failure modes of deep transformers and how to avoid them: a unified theory of signal propagation at initialisation

**ICLR 2026 · Accept (Poster)** · Alessio Giorlandino; Sebastian Goldt

[OpenReview](<https://openreview.net/forum?id=utSqpxQHXq>) · [Official program](<https://iclr.cc/virtual/2026/poster/10006858>) · [PDF](<https://openreview.net/pdf?id=utSqpxQHXq>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Derives Transformer trainability diagrams linking initialization to rank collapse, entropy collapse and vanishing gradients.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Weight scale; residual scale; depth; attention initialization.

**Training qualification:** Signal-propagation theory at initialization is not a guarantee of the entire nonlinear training trajectory.

**Evidence:** Official accepted-paper title and abstract.

### Understanding the Implicit Biases of Design Choices for Time Series Foundation Models

**ICLR 2026 · Accept (Poster)** · Annan Yu; Danielle Maddix; Boran Han; Xiyuan Zhang; Abdul Fatir Ansari; Oleksandr Shchur; Christos Faloutsos; Andrew Gordon Wilson; Michael W Mahoney; Bernie Wang

[OpenReview](<https://openreview.net/forum?id=5jkzTzV5Ao>) · [Official program](<https://iclr.cc/virtual/2026/poster/10011425>) · [PDF](<https://openreview.net/pdf?id=5jkzTzV5Ao>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Analyzes how model-design choices induce interacting biases in time-series foundation models.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Patch size; embeddings; training objective.

**Training qualification:** Time-series-specific findings are supporting evidence rather than LLM training rules.

**Evidence:** Official accepted-paper title and abstract.

### Understanding the Mechanisms of Fast Hyperparameter Transfer

**ICLR 2026 · Accept (Poster)** · Nikhil Ghosh; Denny Wu; Alberto Bietti

[OpenReview](<https://openreview.net/forum?id=Q7mLKxQ8qk>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009619>) · [PDF](<https://openreview.net/pdf?id=Q7mLKxQ8qk>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer.

**Optimizer relevance:** Analyzes mechanisms that permit fast hyperparameter transfer, with theoretical examples and an empirically tested trajectory-decomposition conjecture for LLMs.

**Training dynamics relevance:** Analyzes mechanisms that permit fast hyperparameter transfer, with theoretical examples and an empirically tested trajectory-decomposition conjecture for LLMs.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Proxy-model size; training trajectory; hyperparameter transfer.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Weight Decay may matter more than µP for Learning Rate Transfer in Practice

**ICLR 2026 · Accept (Poster)** · Atli Kosson; Jeremy Welborn; Yang Liu; Martin Jaggi; Xi Chen

[OpenReview](<https://openreview.net/forum?id=PvTxIdZc1E>) · [Official program](<https://iclr.cc/virtual/2026/poster/10009637>) · [PDF](<https://openreview.net/pdf?id=PvTxIdZc1E>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Empirically tests the roles of weight decay and maximal-update parameterization in learning-rate transfer across model widths.

**Training dynamics relevance:** Empirically tests the roles of weight decay and maximal-update parameterization in learning-rate transfer across model widths.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Weight decay; MuP; width; learning-rate transfer.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### What Scales in Cross-Entropy Scaling Law?

**ICLR 2026 · Accept (Poster)** · Junxi Yan; Zixi Wei; Qingyao Ai; Yiqun LIU; Jingtao Zhan

[OpenReview](<https://openreview.net/forum?id=o94xgM0sWJ>) · [Official program](<https://iclr.cc/virtual/2026/poster/10007437>) · [PDF](<https://openreview.net/pdf?id=o94xgM0sWJ>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Separates cross-entropy into components and finds that error-entropy better tracks power-law scaling in the studied models.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Model scale; training time; evaluation loss decomposition.

**Training qualification:** This is a proposed decomposition-based explanation with empirical support, not a universal replacement law.

**Evidence:** Official accepted-paper title and abstract.

### WSM: Decay-Free Learning Rate Schedule via Checkpoint Merging for LLM Pre-training

**ICLR 2026 · Accept (Oral)** · Changxin Tian; Jiapeng Wang; Qian Zhao; Kunlong Chen; Jia Liu; Ziqi Liu; Jiaxin Mao; Xin Zhao; Zhiqiang Zhang; JUN ZHOU

[OpenReview](<https://openreview.net/forum?id=HhThhjKyfw>) · [Official program](<https://iclr.cc/virtual/2026/poster/10010369>) · [PDF](<https://openreview.net/pdf?id=HhThhjKyfw>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules.

**Optimizer relevance:** Warmup-Stable and Merge replaces an explicit decay phase with principled checkpoint averaging, linking merging weights to learning-rate schedules.

**Training dynamics relevance:** Warmup-Stable and Merge replaces an explicit decay phase with principled checkpoint averaging, linking merging weights to learning-rate schedules.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Warm-up; constant rate; checkpoint merging.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### xLSTM Scaling Laws: Competitive Performance with Linear Time-Complexity

**ICLR 2026 · Accept (Poster)** · Maximilian Beck; Kajetan Schweighofer; Sebastian Böck; Sebastian Lehner; Sepp Hochreiter

[OpenReview](<https://openreview.net/forum?id=bpbU549sSg>) · [Official program](<https://iclr.cc/virtual/2026/poster/10008569>) · [PDF](<https://openreview.net/pdf?id=bpbU549sSg>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Compares Transformer and xLSTM compute-optimal and overtrained scaling, including context-dependent optimal size.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Architecture; context length; parameters; token budget.

**Training qualification:** Performance rankings are tied to the evaluated architectures, training recipes and compute accounting.

**Evidence:** Official accepted-paper title and abstract.

### $\mu$pscaling small models: Principled warm starts and hyperparameter transfer

**ICML 2026 · Accept (regular)** · Yuxin Ma; Nan Chen; Mateo D Diaz; Soufiane Hayou; Dmitriy Kunisky; Soledad Villar

[OpenReview](<https://openreview.net/forum?id=bAqpZRzlTg>) · [Official program](<https://icml.cc/virtual/2026/poster/62988>) · [PDF](<https://openreview.net/pdf?id=bAqpZRzlTg>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Extends maximal-update ideas to widening pretrained models, with principled perturbation scaling and optimizer hyperparameter transfer.

**Training dynamics relevance:** Extends maximal-update ideas to widening pretrained models, with principled perturbation scaling and optimizer hyperparameter transfer.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Width expansion; initialization perturbation; hyperparameter transfer.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### A Fourier perspective on the learning dynamics of neural networks: from sample complexities to mechanistic insights

**ICML 2026 · Accept (regular)** · Fabiola Ricci; Claudia Merger; Sebastian Goldt

[OpenReview](<https://openreview.net/forum?id=RQECNEUcbJ>) · [Official program](<https://icml.cc/virtual/2026/poster/64045>) · [PDF](<https://openreview.net/pdf?id=RQECNEUcbJ>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Explains why amplitude features precede phase features and how power-law spectra alter feature-learning times.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Data spectrum; training time; feature complexity.

**Training qualification:** Formal complexity results use a controlled translation-invariant data model.

**Evidence:** Official accepted-paper title and abstract.

### A unified theory of feature learning in RNNs and DNNs

**ICML 2026 · Accept (regular)** · Jan Bauer; Kirsten Fischer; Moritz Helias; Agostina Palmigiano

[OpenReview](<https://openreview.net/forum?id=nkVt0sY9HJ>) · [Official program](<https://icml.cc/virtual/2026/poster/61686>) · [PDF](<https://openreview.net/pdf?id=nkVt0sY9HJ>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Develops mean-field feature-learning theory for recurrent and feedforward networks and identifies a signal-to-noise transition in learned representations.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Width; feature-learning strength; weight sharing.

**Training qualification:** The analysis concerns its asymptotic/Bayesian formulation, not every finite-width optimizer trajectory.

**Evidence:** Official accepted-paper title and abstract.

### Active Budget Allocation for Efficient Scaling Law Estimation via Surrogate-Guided Pruning

**ICML 2026 · Accept (regular)** · Viktoria Schram; Markus Hiller; Daniel Beck; Trevor Cohn

[OpenReview](<https://openreview.net/forum?id=DXnLu7qu75>) · [Official program](<https://icml.cc/virtual/2026/poster/65451>) · [PDF](<https://openreview.net/pdf?id=DXnLu7qu75>)

**Categories:** T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Uses successive halving and surrogate learning curves to reduce the cost of fitting compute-loss frontiers.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Scaling-study compute allocation; early pruning.

**Training qualification:** An experimental-design method; aggressive pruning can depend on surrogate accuracy.

**Evidence:** Official accepted-paper title and abstract.

### AdaGC: Enhancing LLM Pretraining Stability via Adaptive Gradient Clipping

**ICML 2026 · Accept (regular)** · Guoxia Wang; Shuai Li; Congliang Chen; Jinle Zeng; Jiabin Yang; Dianhai Yu; Yanjun Ma; Li Shen

[OpenReview](<https://openreview.net/forum?id=uBYlCu8b8Z>) · [Official program](<https://icml.cc/virtual/2026/poster/61050>) · [PDF](<https://openreview.net/pdf?id=uBYlCu8b8Z>)

**Categories:** E — Training stabilization and distributed optimization; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** AdaGC uses adaptive per-tensor gradient clipping to prevent gradient spikes from contaminating optimizer states during LLM pretraining.

**Training dynamics relevance:** AdaGC uses adaptive per-tensor gradient clipping to prevent gradient spikes from contaminating optimizer states during LLM pretraining.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Gradient clipping; moment contamination.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/PaddlePaddle/PaddleFleet>). Links extracted from the accepted abstract; code was not tested.

### Adaptive Batch Sizes Using Non-Euclidean Gradient Noise Scales for Stochastic Sign and Spectral Descent

**ICML 2026 · Accept (regular)** · Hiroki Naganuma; Shagun Gupta; Youssef Briki; Ioannis Mitliagkas; Irina Rish; Parameswaran Raman; Hao-Jun Shi

[OpenReview](<https://openreview.net/forum?id=XMSaWRpEPS>) · [Official program](<https://icml.cc/virtual/2026/poster/63415>) · [PDF](<https://openreview.net/pdf?id=XMSaWRpEPS>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T2 — Batch size, gradient noise and training efficiency.

**Optimizer relevance:** Derives gradient-noise scales for sign and spectral descent and uses them for adaptive batch sizing with Signum and Muon.

**Training dynamics relevance:** Derives gradient-noise scales for sign and spectral descent and uses them for adaptive batch sizing with Signum and Muon.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Sign/spectral gradient noise scale; adaptive batch size.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Adaptive Momentum and Nonlinear Damping for Neural Network Training

**ICML 2026 · Accept (regular)** · Aikaterini Karoni; Rajit Rajpal; Benedict Leimkuhler; Gabriel Stoltz

[OpenReview](<https://openreview.net/forum?id=JWWpV4StVf>) · [Official program](<https://icml.cc/virtual/2026/poster/64813>) · [PDF](<https://openreview.net/pdf?id=JWWpV4StVf>)

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; T5 — Stability, curvature and edge-of-stability dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Introduces per-parameter adaptive momentum and cubic damping variants of momentum SGD and Adam; evaluates BERT, GPT-2, and ViT.

**Training dynamics relevance:** Introduces per-parameter adaptive momentum and cubic damping variants of momentum SGD and Adam; evaluates BERT, GPT-2, and ViT.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Momentum; nonlinear damping.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Adaptive Preconditioners Trigger Loss Spikes in Adam

**ICML 2026 · Accept (regular)** · Zhiwei Bai; Zhangchen Zhou; Jiajie Zhao; Xiaolong Li; Zhiyu li; Feiyu Xiong; Hongkang Yang; Yaoyu Zhang; Zhi-Qin John Xu

[OpenReview](<https://openreview.net/forum?id=STWQoscanw>) · [Official program](<https://icml.cc/virtual/2026/poster/63930>) · [PDF](<https://openreview.net/pdf?id=STWQoscanw>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T5 — Stability, curvature and edge-of-stability dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Explains Adam loss spikes through failure of the second-moment preconditioner to track instantaneous squared gradients; tests include large Transformers.

**Training dynamics relevance:** Explains Adam loss spikes through failure of the second-moment preconditioner to track instantaneous squared gradients; tests include large Transformers.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Second-moment timescale; instantaneous curvature; loss spikes.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Adaptive Sharpness-Aware Minimization with a Polyak-type Step size: A Theory-Grounded Scheduler

**ICML 2026 · Accept (regular)** · Dimitris Oikonomou; Nicolas Loizou

[OpenReview](<https://openreview.net/forum?id=On2B3By7PT>) · [Official program](<https://icml.cc/virtual/2026/poster/64318>) · [PDF](<https://openreview.net/pdf?id=On2B3By7PT>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Training dynamics relevance:** Derives adaptive Polyak-style schedules for SAM and compares them with tuned schedules.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Polyak step size; SAM perturbation; stochasticity.

**Training qualification:** The strongest rates are for convex/strongly convex objectives; stochastic bounds include a residual neighborhood.

**Evidence:** Official accepted-paper title and abstract.

### An Exploration of Non-Euclidean Gradient Descent: Muon and its Many Variants

**ICML 2026 · Accept (regular)** · Michael Crawshaw; Chirag Modi; Mingrui Liu; Robert Gower

[OpenReview](<https://openreview.net/forum?id=O5xoqSmNzc>) · [Official program](<https://icml.cc/virtual/2026/poster/64390>) · [PDF](<https://openreview.net/pdf?id=O5xoqSmNzc>)

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Systematically varies layer norm aggregation and normalization; introduces MuonMax and Momo variants with improved hyperparameter robustness.

**Training dynamics relevance:** Systematically varies layer norm aggregation and normalization; introduces MuonMax and Momo variants with improved hyperparameter robustness.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Layer-norm aggregation; update normalization; tuning robustness.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Balancing Learning Rates Across Layers: Exact Two-Step Dynamics and Optimal Scaling in Linear Neural Networks

**ICML 2026 · Accept (regular)** · Tianyu Pang; Vignesh Kothapalli; Shenyang Deng; Haohui Wang; Dawei Zhou; Yaoqing Yang

[OpenReview](<https://openreview.net/forum?id=4vztmTrGhd>) · [Official program](<https://icml.cc/virtual/2026/poster/66301>) · [PDF](<https://openreview.net/pdf?id=4vztmTrGhd>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer.

**Training dynamics relevance:** Derives one- and two-step linear-network dynamics showing when unequal layer rates help and when balanced rates become optimal.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Layer-wise learning rates; initialization; early training steps.

**Training qualification:** The exact/surrogate results concern early steps of two- and three-layer linear networks.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/TDCSZ327/Layer-Balancing>). Links extracted from the accepted abstract; code was not tested.

### Can Muon Fine-tune Adam-Pretrained Models?

**ICML 2026 · Accept (regular)** · Xingyu Qu; Peigeng Huang; Samuel Horváth

[OpenReview](<https://openreview.net/forum?id=NKKwTEYdAm>) · [Official program](<https://icml.cc/virtual/2026/poster/64467>) · [PDF](<https://openreview.net/pdf?id=NKKwTEYdAm>)

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

[OpenReview](<https://openreview.net/forum?id=3uXAGWqCny>) · [Official program](<https://icml.cc/virtual/2026/poster/66419>) · [PDF](<https://openreview.net/pdf?id=3uXAGWqCny>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer.

**Training dynamics relevance:** Compares rich CompleteP and lazy NTK parameterizations for hyperparameter transfer and compute efficiency in deep RL.

**Training study context:** Reinforcement learning.

**Hyperparameters / scaling axes:** Width/depth parameterization; learning rate; model size.

**Training qualification:** Evidence is from control agents with nonstationary data, rather than autoregressive pretraining.

**Evidence:** Official accepted-paper title and abstract.

### Conflicting Biases at the Edge of Stability: Norm versus Sharpness Regularization

**ICML 2026 · Accept (regular)** · Maria Matveev; Vit Fojtik; Hung-Hsu Chou; Gitta Kutyniok; Johannes Maly

[OpenReview](<https://openreview.net/forum?id=6eI4YHFyON>) · [Official program](<https://icml.cc/virtual/2026/poster/66129>) · [PDF](<https://openreview.net/pdf?id=6eI4YHFyON>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Shows that learning rate trades off norm and sharpness biases, and neither alone guarantees best generalization.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Learning rate; parameter norm; sharpness.

**Training qualification:** The formal counterexample uses diagonal linear regression.

**Evidence:** Official accepted-paper title and abstract.

### Delving into Muon and Beyond: Deep Analysis and Extensions

**ICML 2026 · Accept (spotlight)** · Xianbiao Qi; Marco Chen; Jiaquan Ye; Yelin He; Rong Xiao

[OpenReview](<https://openreview.net/forum?id=xUQ0Gw11NL>) · [Official program](<https://icml.cc/virtual/2026/poster/60694>) · [PDF](<https://openreview.net/pdf?id=xUQ0Gw11NL>)

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Studies Muon and related spectral-power transformations, including RMS-normalized variants and SVD-free computation; examines when orthogonalization helps.

**Training dynamics relevance:** Studies Muon and related spectral-power transformations, including RMS-normalized variants and SVD-free computation; examines when orthogonalization helps.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Spectral-power normalization; optimizer choice.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Deriving Neural Scaling Laws from the Statistics of Natural Language

**ICML 2026 · Accept (regular)** · Francesco Cagnetta; Allan Raventos; Surya Ganguli; Matthieu Wyart

[OpenReview](<https://openreview.net/forum?id=VXlniX0C5y>) · [Official program](<https://icml.cc/virtual/2026/poster/63606>) · [PDF](<https://openreview.net/pdf?id=VXlniX0C5y>)

**Categories:** T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Predicts data-limited scaling exponents from token-correlation and conditional-entropy statistics, with GPT/LLaMA-style experiments.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Training data size; language correlation decay; context length.

**Training qualification:** The quantitative tests use TinyStories and WikiText; other corpora and compute-limited regimes require verification.

**Evidence:** Official accepted-paper title and abstract.

### Dichotomy of Feature Learning and Unlearning: Fast-Slow Analysis on Neural Networks with Stochastic Gradient Descent

**ICML 2026 · Accept (regular)** · Shota Imai; Sota Nishiyama; Masaaki Imaizumi

[OpenReview](<https://openreview.net/forum?id=wg02GN1ygj>) · [Official program](<https://icml.cc/virtual/2026/poster/60792>) · [PDF](<https://openreview.net/pdf?id=wg02GN1ygj>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** A fast-slow analysis explains when feature alignment develops and is subsequently lost during training.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Output-layer initialization; width; batch size; training duration.

**Training qualification:** The effect is population-level feature unlearning in an infinite-width two-layer model, not ordinary finite-sample overfitting.

**Evidence:** Official accepted-paper title and abstract.

### Do We Need Adam? Surprisingly Strong and Sparse Reinforcement Learning with SGD in LLMs

**ICML 2026 · Accept (spotlight)** · Sagnik Mukherjee; Lifan Yuan; Pavan Jayasinha; Dilek Hakkani-Tür; Hao Peng

[OpenReview](<https://openreview.net/forum?id=z31fdV4WRu>) · [Official program](<https://icml.cc/virtual/2026/oral/71027>) · [PDF](<https://openreview.net/pdf?id=z31fdV4WRu>)

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Compares SGD and AdamW for LLM reinforcement learning; finds SGD competitive with highly sparse updates in the tested RLVR settings.

**Training dynamics relevance:** Compares SGD and AdamW for LLM reinforcement learning; finds SGD competitive with highly sparse updates in the tested RLVR settings.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Adam versus SGD; RL tuning.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Dropout Universality: Scaling Laws and Optimal Scheduling at the Edge-of-Chaos

**ICML 2026 · Accept (regular)** · Lucas Fernandez-Sarmiento

[OpenReview](<https://openreview.net/forum?id=FoDU47u2jk>) · [Official program](<https://icml.cc/virtual/2026/poster/65205>) · [PDF](<https://openreview.net/pdf?id=FoDU47u2jk>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Analyzes how dropout changes critical signal propagation and motivates front-loaded dropout schedules.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Dropout strength and schedule; depth; initialization.

**Training qualification:** Mean-field critical exponents and the MLP/ViT experiments have different scopes; LLM transfer is not established.

**Evidence:** Official accepted-paper title and abstract.

### Dynamics of neural scaling laws in random feature regression with powerlaw-distributed kernel eigenvalues

**ICML 2026 · Accept (regular)** · Jakob Kramp; Javed Lindner; Moritz Helias

[OpenReview](<https://openreview.net/forum?id=Ge3VtuCvZ7>) · [Official program](<https://icml.cc/virtual/2026/poster/65116>) · [PDF](<https://openreview.net/pdf?id=Ge3VtuCvZ7>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** A dynamical mean-field model connects spectral modes to generalization curves under gradient flow, regularization and Langevin dynamics.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Training time; weight decay; early stopping; kernel spectrum.

**Training qualification:** Results concern random-feature/GP regression and prescribed power-law spectra.

**Evidence:** Official accepted-paper title and abstract.

### Explaining Data Mixing Scaling Laws

**ICML 2026 · Accept (regular)** · rui dai; SHURAN ZHENG

[OpenReview](<https://openreview.net/forum?id=joReaAnwnH>) · [Official program](<https://icml.cc/virtual/2026/poster/62102>) · [PDF](<https://openreview.net/pdf?id=joReaAnwnH>)

**Categories:** T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Explains mixture-dependent losses through competition for shared capacity and noise reduction, enabling mixture extrapolation.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Data-mixture weights; model capacity; scale.

**Training qualification:** The domain/skill assumptions and fitted parameters qualify predictions on unseen mixtures.

**Evidence:** Official accepted-paper title and abstract.

### Flatland: The Adventures of Gradient Descent with Large Step Sizes

**ICML 2026 · Accept (regular)** · Leonardo Galli; Curtis Fox; Wiebke Bartolomaeus; Mark Schmidt; Holger Rauhut

[OpenReview](<https://openreview.net/forum?id=NpSI4x2vBS>) · [Official program](<https://icml.cc/virtual/2026/poster/64420>) · [PDF](<https://openreview.net/pdf?id=NpSI4x2vBS>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Training dynamics relevance:** Develops adaptive large-step methods and studies self-stabilization beyond classical monotone descent.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Large learning rates; local smoothness; sharpness.

**Training qualification:** Global flatness alone need not improve generalization; algorithm guarantees depend on local regularity assumptions.

**Evidence:** Official accepted-paper title and abstract.

### From Optimization to Generalization under Heavy-Tailed Data: The Role of Gradient Clipping

**ICML 2026 · Accept (regular)** · Aleksandr Shestakov; Martin Takac; Eduard Gorbunov

[OpenReview](<https://openreview.net/forum?id=FGHVEJ2Jz9>) · [Official program](<https://icml.cc/virtual/2026/poster/65262>) · [PDF](<https://openreview.net/pdf?id=FGHVEJ2Jz9>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Separates data-sampling and optimization noise to explain why clipping helps under heavy-tailed data.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Step size; clipping schedule; dataset size; tail index.

**Training qualification:** Generalization results use strongly convex smooth objectives; infinite-data noise and finite-dataset moments are distinct.

**Evidence:** Official accepted-paper title and abstract.

### Generalization and Scaling Laws for Mixture-of-ExpertsTransformers

**ICML 2026 · Accept (regular)** · Mansour ZOUBEIROU A MAYAKI

[OpenReview](<https://openreview.net/forum?id=WxmL5UjtNm>) · [Official program](<https://icml.cc/virtual/2026/poster/63463>) · [PDF](<https://openreview.net/pdf?id=WxmL5UjtNm>)

**Categories:** T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Separates active capacity from routing complexity to derive MoE generalization and scaling trade-offs.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Active parameters; expert count; data size; compute.

**Training qualification:** Worst-case statistical/approximation guarantees do not directly prescribe optimal empirical LLM training recipes.

**Evidence:** Official accepted-paper title and abstract.

### Gradient Descent with Large Step Size Restores Symmetry in Deep Linear Networks with Multi-Pathway

**ICML 2026 · Accept (regular)** · Hee-Sung Kim; Sungyoon Lee

[OpenReview](<https://openreview.net/forum?id=CVXqBkLF5y>) · [Official program](<https://icml.cc/virtual/2026/poster/65550>) · [PDF](<https://openreview.net/pdf?id=CVXqBkLF5y>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Shows that discrete large-step GD can reverse gradient-flow symmetry breaking and redistribute features across network paths.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Large step size; depth; number of pathways.

**Training qualification:** The theory uses multipath deep linear networks.

**Evidence:** Official accepted-paper title and abstract.

### Gradient Flow Dynamics and Implicit Bias of Diagonal Linear Networks under Infinitesimal Initialization

**ICML 2026 · Accept (regular)** · Jiajie Zhao; Jianxing Wang; Junjie Yang; Zhiwei Bai; Yaoyu Zhang

[OpenReview](<https://openreview.net/forum?id=IJph1t3Egr>) · [Official program](<https://icml.cc/virtual/2026/poster/64965>) · [PDF](<https://openreview.net/pdf?id=IJph1t3Egr>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Characterizes infinitesimal-initialization dynamics and modified l1 implicit bias in diagonal linear networks.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Initialization scale; depth; gradient-flow time.

**Training qualification:** Continuous-time and vanishing-initialization limits need not describe finite-step adaptive optimizers.

**Evidence:** Official accepted-paper title and abstract.

### GradientStabilizer: Fix the Norm, Not the Gradient

**ICML 2026 · Accept (regular)** · Tianjin Huang; Zhangyang “Atlas” Wang; Haotian Hu; Zhenyu Zhang; Gaojie Jin; Xiang Li; Li Shen; Jiaxing Shang; Tianlong Chen; Ke Li; Lu Liu; Qingsong Wen; Shiwei Liu

[OpenReview](<https://openreview.net/forum?id=UZ8e5kivVf>) · [Official program](<https://icml.cc/virtual/2026/poster/63695>) · [PDF](<https://openreview.net/pdf?id=UZ8e5kivVf>)

**Categories:** E — Training stabilization and distributed optimization; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** GradientStabilizer preserves gradient direction but stabilizes its magnitude using running norm statistics; includes low-precision LLM training.

**Training dynamics relevance:** GradientStabilizer preserves gradient direction but stabilizes its magnitude using running norm statistics; includes low-precision LLM training.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Gradient norm; normalization; numerical precision.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Grokking Finite-Dimensional Algebra

**ICML 2026 · Accept (regular)** · Pascal Jr Tikeng Notsawo; Guillaume Dumas; Guillaume Rabusseau

[OpenReview](<https://openreview.net/forum?id=5Cvh976L09>) · [Official program](<https://icml.cc/virtual/2026/poster/66276>) · [PDF](<https://openreview.net/pdf?id=5Cvh976L09>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Studies memorization-to-generalization transitions when networks learn multiplication in finite-dimensional algebras.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Training duration; algebraic structure; implicit rank bias.

**Training qualification:** A controlled algorithmic-learning setting rather than an LLM pretraining recipe.

**Evidence:** Official accepted-paper title and abstract.

### High-Dimensional Learning Dynamics of Quantized Models with Straight-Through Estimator

**ICML 2026 · Accept (regular)** · Yuma Ichikawa; Shuhei Kashiwamura; Ayaka Sakata

[OpenReview](<https://openreview.net/forum?id=bI9moH3UZw>) · [Official program](<https://icml.cc/virtual/2026/poster/62979>) · [PDF](<https://openreview.net/pdf?id=bI9moH3UZw>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Derives high-dimensional STE dynamics and explains plateaus and sharp generalization changes induced by quantization settings.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Quantization range; bit width; training time.

**Training qualification:** The deterministic limit and fixed-point results concern the specified quantized model.

**Evidence:** Official accepted-paper title and abstract.

### Hyperparameter Transfer Laws for Non-Recurrent Multi-Path Neural Networks

**ICML 2026 · Accept (regular)** · Haosong Zhang; Shenxi Wu; Xingjian Ma; Shirui Bian; Yichi Zhang; Xi Chen; Wei Lin

[OpenReview](<https://openreview.net/forum?id=Q2tAR1xDFQ>) · [Official program](<https://icml.cc/virtual/2026/poster/64199>) · [PDF](<https://openreview.net/pdf?id=Q2tAR1xDFQ>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer.

**Optimizer relevance:** Studies effective-depth scaling rules for learning-rate transfer across non-recurrent multi-path architectures, including Transformers.

**Training dynamics relevance:** Studies effective-depth scaling rules for learning-rate transfer across non-recurrent multi-path architectures, including Transformers.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Effective depth; multipath architecture; transfer rules.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Hyperparameter Transfer with Mixture-of-Expert Layers

**ICML 2026 · Accept (regular)** · Tianze Jiang; Blake Bordelon; Cengiz Pehlevan; Boris Hanin

[OpenReview](<https://openreview.net/forum?id=fD36uwJ5oV>) · [Official program](<https://icml.cc/virtual/2026/poster/62595>) · [PDF](<https://openreview.net/pdf?id=fD36uwJ5oV>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer.

**Optimizer relevance:** Parameterization and mean-field analysis for transferring hyperparameters across MoE width, depth, expert count, and expert size.

**Training dynamics relevance:** Parameterization and mean-field analysis for transferring hyperparameters across MoE width, depth, expert count, and expert size.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Width; depth; expert count; expert size.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### InfoLaw: Information Scaling Laws for Large Language Models with Quality-Weighted Mixture Data and Repetition

**ICML 2026 · Accept (regular)** · Weidong Zhou; Fengze Liu; LIU; Ping Guo; Zijun Wang; Bingni Zhang; Yifan Zhang; Yifeng Yu; Xiaohuan ZHOU; Taifeng Wang

[OpenReview](<https://openreview.net/forum?id=fQaVptMRCY>) · [Official program](<https://icml.cc/virtual/2026/poster/62574>) · [PDF](<https://openreview.net/pdf?id=fQaVptMRCY>)

**Categories:** T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** InfoLaw models information accumulation and diminishing returns from repeated data to predict loss under new training recipes.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Mixture weights; data quality; repetition; tokens; model size.

**Training qualification:** Extrapolation is empirical within the evaluated families and repetition regimes.

**Evidence:** Official accepted-paper title and abstract.

### Inverse Depth Scaling From Most Layers Being Similar

**ICML 2026 · Accept (regular)** · Yizhou Liu; Sara Kangaslahti; Ziming Liu; Jeff Gore

[OpenReview](<https://openreview.net/forum?id=CEpCpxJqAt>) · [Official program](<https://icml.cc/virtual/2026/poster/65580>) · [PDF](<https://openreview.net/pdf?id=CEpCpxJqAt>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Relates inverse-depth loss scaling to repeated, similar residual layers and studies inefficient use of depth.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Depth; residual architecture; layer similarity.

**Training qualification:** The ensemble-averaging explanation is a proposed mechanism, not a universal proof about deep LLMs.

**Evidence:** Official accepted-paper title and abstract.

### Item Response Scaling Laws: A Measurement Theory Approach for Efficient and Generalizable Neural Scaling Estimation

**ICML 2026 · Accept (regular)** · Sang Truong; Yuheng Tu; Rylan Schaeffer; Sanmi Koyejo

[OpenReview](<https://openreview.net/forum?id=QFgM1iNKmg>) · [Official program](<https://icml.cc/virtual/2026/poster/64176>) · [PDF](<https://openreview.net/pdf?id=QFgM1iNKmg>)

**Categories:** T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Uses item-response theory to share information across models and questions when estimating downstream scaling behavior.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Model scale; evaluation sample budget; benchmark composition.

**Training qualification:** A performance-estimation framework rather than a training optimizer; it also studies test-time sampling.

**Evidence:** Official accepted-paper title and abstract.

### Learning Dynamics of Zeroth-Order Optimization: A Kernel Perspective

**ICML 2026 · Accept (regular)** · Zhe Li; Bicheng Ying; Zidong Liu; Haibo Yang

[OpenReview](<https://openreview.net/forum?id=UTIylOfVUb>) · [Official program](<https://icml.cc/virtual/2026/poster/63704>) · [PDF](<https://openreview.net/pdf?id=UTIylOfVUb>)

**Categories:** F — Zeroth-order and backpropagation alternatives for LLMs; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Analyzes zeroth-order learning through an empirical-NTK perspective, connecting perturbation count to kernel fidelity in LLM fine-tuning.

**Training dynamics relevance:** Analyzes zeroth-order learning through an empirical-NTK perspective, connecting perturbation count to kernel fidelity in LLM fine-tuning.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Zeroth-order perturbation count; kernel fidelity.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Learning Rate Annealing Improves Tuning Robustness in Stochastic Optimization

**ICML 2026 · Accept (regular)** · Amit Attia; Tomer Koren

[OpenReview](<https://openreview.net/forum?id=usZLsN3Dnv>) · [Official program](<https://icml.cc/virtual/2026/poster/60981>) · [PDF](<https://openreview.net/pdf?id=usZLsN3Dnv>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules.

**Optimizer relevance:** Analyzes why annealing schedules improve robustness to initial learning-rate misspecification and coarse tuning grids.

**Training dynamics relevance:** Analyzes why annealing schedules improve robustness to initial learning-rate misspecification and coarse tuning grids.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Annealing; initial-rate misspecification; tuning grid.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Learning Rate Scaling across LoRA Ranks and Transfer to Full Finetuning

**ICML 2026 · Accept (regular)** · Nan Chen; Soledad Villar; Soufiane Hayou

[OpenReview](<https://openreview.net/forum?id=vCAIwEJZQ6>) · [Official program](<https://icml.cc/virtual/2026/poster/60938>) · [PDF](<https://openreview.net/pdf?id=vCAIwEJZQ6>)

**Categories:** I — Fine-tuning, LoRA, privacy, and specialized post-training; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer.

**Optimizer relevance:** Maximal-Update Adaptation studies learning-rate scaling across LoRA ranks and transfer from LoRA tuning to full fine-tuning.

**Training dynamics relevance:** Maximal-Update Adaptation studies learning-rate scaling across LoRA ranks and transfer from LoRA tuning to full fine-tuning.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** LoRA rank; adapter learning rate; full fine-tuning transfer.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### LLMs as Noisy Channels: A Shannon Perspective on Model Capacity and Scaling Laws

**ICML 2026 · Accept (regular)** · Xu Ouyang; Deyi Liu; Yuhang Cai; Jing Liu; Yuan Yang; Chen Zheng; Thomas Hartvigsen; Yiyuan Ma

[OpenReview](<https://openreview.net/forum?id=nuwO8FBadZ>) · [Official program](<https://icml.cc/virtual/2026/poster/61671>) · [PDF](<https://openreview.net/pdf?id=nuwO8FBadZ>)

**Categories:** T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Models training as information transmission to explain non-monotonic scaling and degradation after overtraining or perturbation.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Model size; token budget; perturbation and quantization noise.

**Training qualification:** A proposed scaling model validated on selected model families; not a universal capacity theorem for arbitrary LLMs.

**Evidence:** Official accepted-paper title and abstract.

### Memory-Efficient LLM Training with Dynamic Sparsity: From Stability to Practical Scaling

**ICML 2026 · Accept (regular)** · Qiao Xiao; Boqian Wu; Patrik Okanovic; Tomasz Sternal; Maurice Keulen; Elena Mocanu; Mykola Pechenizkiy; Decebal Constantin Mocanu; Torsten Hoefler

[OpenReview](<https://openreview.net/forum?id=ivVPgBZewP>) · [Official program](<https://icml.cc/virtual/2026/poster/62187>) · [PDF](<https://openreview.net/pdf?id=ivVPgBZewP>)

**Categories:** E — Training stabilization and distributed optimization; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Optimizer relevance:** SMET addresses cold-start instability of newly regrown sparse parameters with optimizer warm-up, density-aware learning-rate scaling, and sparse state storage.

**Training dynamics relevance:** SMET addresses cold-start instability of newly regrown sparse parameters with optimizer warm-up, density-aware learning-rate scaling, and sparse state storage.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Sparsity; regrowth; optimizer warm-up.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/QiaoXiao7282/SMET.>). Links extracted from the accepted abstract; code was not tested.

### Momentum Further Constrains Sharpness at the Edge of Stochastic Stability

**ICML 2026 · Accept (regular)** · Arseniy Andreyev; Advikar Ananthkumar; Marc Walden; Tomaso A Poggio; Pierfrancesco Beneventano

[OpenReview](<https://openreview.net/forum?id=mL4i6z7Miy>) · [Official program](<https://icml.cc/virtual/2026/poster/61855>) · [PDF](<https://openreview.net/pdf?id=mL4i6z7Miy>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T2 — Batch size, gradient noise and training efficiency; T5 — Stability, curvature and edge-of-stability dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Shows how batch size and momentum jointly determine stochastic stability thresholds and attained sharpness.

**Training dynamics relevance:** Shows how batch size and momentum jointly determine stochastic stability thresholds and attained sharpness.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Batch size; momentum; stochastic sharpness.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Muon in Associative Memory Learning: Training Dynamics and Scaling Laws

**ICML 2026 · Accept (regular)** · Kaifei Wang; Binghui Li; Han Zhong; Pinyan Lu; Liwei Wang

[OpenReview](<https://openreview.net/forum?id=tn00ERVdgL>) · [Official program](<https://icml.cc/virtual/2026/poster/61087>) · [PDF](<https://openreview.net/pdf?id=tn00ERVdgL>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Studies Muon through associative-memory training dynamics and scaling laws; a theoretical model rather than a new general LLM optimizer.

**Training dynamics relevance:** Studies Muon through associative-memory training dynamics and scaling laws; a theoretical model rather than a new general LLM optimizer.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Muon; training time; associative-memory scaling.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Non-Euclidean Gradient Descent Operates at the Edge of Stability

**ICML 2026 · Accept (spotlight)** · Rustem Islamov; Michael Crawshaw; Jeremy Cohen; Robert Gower

[OpenReview](<https://openreview.net/forum?id=piWlEHb4Db>) · [Official program](<https://icml.cc/virtual/2026/oral/71156>) · [PDF](<https://openreview.net/pdf?id=piWlEHb4Db>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Optimizer relevance:** Extends edge-of-stability diagnostics to non-Euclidean geometries, including spectral and sign descent.

**Training dynamics relevance:** Extends edge-of-stability diagnostics to non-Euclidean geometries, including spectral and sign descent.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Learning rate; descent geometry.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### On the Interaction of Batch Noise, Adaptivity, and Compression, under $(L_0,L_1)$-Smoothness: An SDE Approach

**ICML 2026 · Accept (regular)** · Enea Monzio Compagnoni; Rustem Islamov; Frank Proske; Aurelien Lucchi; Antonio Orvieto; Eduard Gorbunov

[OpenReview](<https://openreview.net/forum?id=Pmsc4yytlf>) · [Official program](<https://icml.cc/virtual/2026/poster/64227>) · [PDF](<https://openreview.net/pdf?id=Pmsc4yytlf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T5 — Stability, curvature and edge-of-stability dynamics.

**Training dynamics relevance:** Constructs curvature-aware SDE models for the joint stability effects of compressed and normalized stochastic optimization.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Learning rate; batch noise; compression; update normalization.

**Training qualification:** Modified-equation approximations require their stated smoothness/noise assumptions.

**Evidence:** Official accepted-paper title and abstract.

### On the origin of neural scaling laws:  from random graphs to natural language

**ICML 2026 · Accept (spotlight)** · Maissam Barkeshli; Alberto Alfarano; Andrey Gromov

[OpenReview](<https://openreview.net/forum?id=mu17VSX8q9>) · [Official program](<https://icml.cc/virtual/2026/poster/61791>) · [PDF](<https://openreview.net/pdf?id=mu17VSX8q9>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Uses graph-walk and simplified-language experiments to show scaling laws can arise without power-law input correlations.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Data complexity; model size; parameterization.

**Training qualification:** The proposed mechanisms are studied in controlled data and small Transformers; extrapolation to all language is not proved.

**Evidence:** Official accepted-paper title and abstract.

### One LR Doesn’t Fit All: Heavy-Tail Guided Layerwise Learning Rates for LLMs

**ICML 2026 · Accept (regular)** · Di He; Songjun Tu; Keyu Wang; Lu Yin; Shiwei Liu

[OpenReview](<https://openreview.net/forum?id=fs9KaJyhRO>) · [Official program](<https://icml.cc/virtual/2026/poster/62519>) · [PDF](<https://openreview.net/pdf?id=fs9KaJyhRO>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules.

**Optimizer relevance:** Uses layer-wise heavy-tail spectral statistics to assign learning rates during LLM pretraining, including AdamW and Muon.

**Training dynamics relevance:** Uses layer-wise heavy-tail spectral statistics to assign learning rates during LLM pretraining, including AdamW and Muon.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Layer-wise learning rates; spectral tail statistics.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/hed-ucas/Layer-wise-Learning-Rate.>). Links extracted from the accepted abstract; code was not tested.

### Over-Alignment vs Over-Fitting: The Role of Feature Learning Strength in Generalization

**ICML 2026 · Accept (regular)** · Taesun Yeom; Taehyeok Ha; Jaeho Lee

[OpenReview](<https://openreview.net/forum?id=Ak8sl1w550>) · [Official program](<https://icml.cc/virtual/2026/poster/65728>) · [PDF](<https://openreview.net/pdf?id=Ak8sl1w550>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Finds an intermediate feature-learning strength that balances over-alignment against overfitting.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Initialization/output scale; feature-learning strength; stopping rule.

**Training qualification:** Theory is for two-layer ReLU gradient flow; optimal settings depend on the training-risk stopping criterion.

**Evidence:** Official accepted-paper title and abstract.

### Per-example Gradients: a New Frontier for Understanding and Improving Optimizers

**ICML 2026 · Accept (regular)** · Vincent Roulet; Atish Agarwala

[OpenReview](<https://openreview.net/forum?id=YB6U1yWcGy>) · [Official program](<https://icml.cc/virtual/2026/poster/63313>) · [PDF](<https://openreview.net/pdf?id=YB6U1yWcGy>)

**Categories:** C — General-purpose matrix, spectral, adaptive, and learned optimizers; T2 — Batch size, gradient noise and training efficiency; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Uses efficient per-example/per-token gradient statistics to analyze and improve signSGD and Adam-style preconditioning.

**Training dynamics relevance:** Uses efficient per-example/per-token gradient statistics to analyze and improve signSGD and Adam-style preconditioning.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Per-example gradient statistics; adaptive normalization.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Preconditioning Neural Tangent Kernel for Adaptive Optimization

**ICML 2026 · Accept (regular)** · Xiyuan Yang; Wenxuan Bao; Katherine Tieu; Jingrui He

[OpenReview](<https://openreview.net/forum?id=CKzW9g2x3g>) · [Official program](<https://icml.cc/virtual/2026/poster/65570>) · [PDF](<https://openreview.net/pdf?id=CKzW9g2x3g>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Optimizer Aware Kernel (OAK) extends NTK analysis to preconditioned fine-tuning and studies when the kernel approximation breaks down.

**Training dynamics relevance:** Optimizer Aware Kernel (OAK) extends NTK analysis to preconditioned fine-tuning and studies when the kernel approximation breaks down.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Preconditioner; fine-tuning; kernel approximation.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Rethinking Neural Network Learning Rates: A Stackelberg Perspective

**ICML 2026 · Accept (regular)** · Sihan Zeng; Sujay Bhatt; Sumitra Ganesh

[OpenReview](<https://openreview.net/forum?id=TgohCXoblV>) · [Official program](<https://icml.cc/virtual/2026/poster/63794>) · [PDF](<https://openreview.net/pdf?id=TgohCXoblV>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T8 — Optimizer dynamics, comparisons and diagnostics.

**Training dynamics relevance:** Interprets a faster final-layer learning rate through Stackelberg optimization and studies conditions for improved convergence.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Layer-wise learning rates; output/body timescales.

**Training qualification:** Convergence results have stated problem assumptions; nonuniform rates are not always superior.

**Evidence:** Official accepted-paper title and abstract.

### Revisiting Anisotropy in Language Transformers: The Geometry of Learning Dynamics

**ICML 2026 · Accept (regular)** · Raphael Bernas; Fanny Jourdan; Antonin Poché; Céline Hudelot

[OpenReview](<https://openreview.net/forum?id=BxSubxbbNc>) · [Official program](<https://icml.cc/virtual/2026/poster/65605>) · [PDF](<https://openreview.net/pdf?id=BxSubxbbNc>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Training dynamics relevance:** Uses training checkpoints to relate embedding geometry, anisotropy and entropy across language-model families.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Training stage; representation anisotropy.

**Training qualification:** Primarily a descriptive analysis; correlations do not isolate causal hyperparameter effects.

**Evidence:** Official accepted-paper title and abstract.

### Scalable Reinforcement Learning via Adaptive Batch Scaling

**ICML 2026 · Accept (regular)** · Jongchan Park

[OpenReview](<https://openreview.net/forum?id=YI9wSqfz7W>) · [Official program](<https://icml.cc/virtual/2026/poster/63301>) · [PDF](<https://openreview.net/pdf?id=YI9wSqfz7W>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T2 — Batch size, gradient noise and training efficiency.

**Training dynamics relevance:** Adjusts batch size with behavioral divergence to accommodate early plasticity and later stable RL training.

**Training study context:** Reinforcement learning.

**Hyperparameters / scaling axes:** Batch size; model size; policy nonstationarity.

**Training qualification:** The reported validation uses PQN and Atari/ALE tasks.

**Evidence:** Official accepted-paper title and abstract.

### Scaling depth capacity via zero/one-layer model expansion

**ICML 2026 · Accept (regular)** · Zhiqi Bu

[OpenReview](<https://openreview.net/forum?id=WP5q6Hn3Cv>) · [Official program](<https://icml.cc/virtual/2026/poster/63529>) · [PDF](<https://openreview.net/pdf?id=WP5q6Hn3Cv>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Studies progressive model expansion and proposes zero/one-layer strategies that balance training cost and final loss.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Depth-expansion timing; new-layer initialization; learning-rate transfer.

**Training qualification:** Compute gains and transfer rules depend on the expansion protocol and tested architectures.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Law for Quantization-Aware Training

**ICML 2026 · Accept (spotlight)** · Mengzhao Chen; Chaoyi Zhang; Jing Liu; Zeng; Zeyue Xue; Zhiheng Liu; Yunshui Li; Jin Ma; Jie Huang; zhou Xun; Ping Luo

[OpenReview](<https://openreview.net/forum?id=fXr3uPr1G5>) · [Official program](<https://icml.cc/virtual/2026/poster/62561>) · [PDF](<https://openreview.net/pdf?id=fXr3uPr1G5>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Fits quantization-aware training laws that separate weight and activation errors and expose their different token sensitivities.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** QAT precision; quantization group size; tokens; model size.

**Training qualification:** The main study concerns W4A4 and its mixed-precision interventions.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Laws for Precision in High-Dimensional Linear Regression

**ICML 2026 · Accept (regular)** · Dechen Zhang; Xuan Tang; Yingyu Liang; Difan Zou

[OpenReview](<https://openreview.net/forum?id=LyhBIrNBXv>) · [Official program](<https://icml.cc/virtual/2026/poster/64582>) · [PDF](<https://openreview.net/pdf?id=LyhBIrNBXv>)

**Categories:** T4 — Compute, data and model scaling laws.

**Training dynamics relevance:** Derives different scaling effects for additive and multiplicative quantization in sketched linear regression.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Precision; model dimension; data size; quantization type.

**Training qualification:** Linear-model and worst-case results are not direct empirical scaling laws for LLMs.

**Evidence:** Official accepted-paper title and abstract.

### Sharpness-Aware Minimization Can Hallucinate Minimizers

**ICML 2026 · Accept (regular)** · Chanwoong Park; Uijeong Jang; Ernest Ryu; Insoon Yang

[OpenReview](<https://openreview.net/forum?id=7xwOy8C00l>) · [Official program](<https://icml.cc/virtual/2026/poster/66010>) · [PDF](<https://openreview.net/pdf?id=7xwOy8C00l>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Identifies nonstationary points where SAM can stall and finds that SGD warm-starts reduce sensitivity to large perturbations.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** SAM perturbation radius; SGD warm-start.

**Training qualification:** A failure mechanism under particular landscape/radius conditions, not a claim that SAM always fails.

**Evidence:** Official accepted-paper title and abstract.

### Sharpness-Aware Pretraining Mitigates Catastrophic Forgetting

**ICML 2026 · Accept (regular)** · Ishaan Watts; Catherine Li; Sachin Goyal; Jacob Mitchell Springer; Aditi Raghunathan

[OpenReview](<https://openreview.net/forum?id=CHvRfubYke>) · [Official program](<https://icml.cc/virtual/2026/poster/65575>) · [PDF](<https://openreview.net/pdf?id=CHvRfubYke>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Studies SAM, larger learning rates, and shorter annealing as pretraining interventions that improve retention after LLM post-training or quantization.

**Training dynamics relevance:** Studies SAM, larger learning rates, and shorter annealing as pretraining interventions that improve retention after LLM post-training or quantization.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Pretraining rate; annealing duration; SAM; retention.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Single-Head Attention in High Dimensions: A Theory of Generalization, Weights Spectra, and Scaling Laws

**ICML 2026 · Accept (spotlight)** · Fabrizio Boncoraglio; Vittorio Erba; Emanuele Troiani; Yizhou Xu; FLORENT KRZAKALA; Lenka Zdeborova

[OpenReview](<https://openreview.net/forum?id=3qan4Zg9rA>) · [Official program](<https://icml.cc/virtual/2026/poster/66429>) · [PDF](<https://openreview.net/pdf?id=3qan4Zg9rA>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Connects attention weight spectra and sequential recovery of signal modes to generalization and power-law scaling.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Attention dimension; sample size; target spectrum.

**Training qualification:** Theory uses a single tied attention head and synthetic high-dimensional tasks.

**Evidence:** Official accepted-paper title and abstract.

### SpanNorm: Reconciling Training Stability and Performance in Deep Transformers

**ICML 2026 · Accept (regular)** · Chao Wang; Bei Li; Jiaqi Zhang; Xinyu Liu; Yuchun Fan; Linkun Lyu; Xin Chen; Jingang Wang; Tong Xiao; Peng Pei; Xunliang Cai

[OpenReview](<https://openreview.net/forum?id=9bLiqb6Vec>) · [Official program](<https://icml.cc/virtual/2026/poster/65837>) · [PDF](<https://openreview.net/pdf?id=9bLiqb6Vec>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** SpanNorm combines a stable residual path with output normalization to control variance and reduce representation collapse.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Normalization placement; residual scaling; depth.

**Training qualification:** Evidence concerns the proposed architecture; bounded signal variance alone does not establish universal optimization stability.

**Evidence:** Official accepted-paper title and abstract.

### SPARKLING: Balancing Signal Preservation and Symmetry Breaking for Width-Progressive Learning

**ICML 2026 · Accept (regular)** · Qifan Yu; Xinyu Ma; Zhijian Zhuo; Minrui Wang; Deyi Liu; Shiyi Zhan; Yiyuan Ma; liang xiang; Xingyan Bin; Di He

[OpenReview](<https://openreview.net/forum?id=SXJBFREkWi>) · [Official program](<https://icml.cc/virtual/2026/poster/63922>) · [PDF](<https://openreview.net/pdf?id=SXJBFREkWi>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer; T5 — Stability, curvature and edge-of-stability dynamics.

**Training dynamics relevance:** SPARKLING preserves activation scale while breaking copied-neuron symmetry during mid-training width growth.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Width expansion; optimizer-state reset; learning-rate re-warmup.

**Training qualification:** The empirical benefits concern the evaluated expansion axes and ratios.

**Evidence:** Official accepted-paper title and abstract.

### Spectral Reach: Understanding Neural Scaling as Progress into the Spectral Tail

**ICML 2026 · Accept (regular)** · Konstantin Nikolaou; Jonas Scheunemann; Sven Krippendorf; Samuel Tovey; Christian Holm

[OpenReview](<https://openreview.net/forum?id=ECdZxuI9Hf>) · [Official program](<https://icml.cc/virtual/2026/poster/65378>) · [PDF](<https://openreview.net/pdf?id=ECdZxuI9Hf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

**Optimizer relevance:** Analyzes neural scaling as progress into the empirical-NTK spectral tail; relevant to optimizer/feature-learning mechanisms, not a new optimizer.

**Training dynamics relevance:** Analyzes neural scaling as progress into the empirical-NTK spectral tail; relevant to optimizer/feature-learning mechanisms, not a new optimizer.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Training progress; NTK spectral tail.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Steady-State Behavior of Constant-Stepsize Stochastic Approximation: Gaussian Approximation and Tail Bounds

**ICML 2026 · Accept (regular)** · Yuyang Wang; Felix Wang; Zedong Wang; Ijay Narang; Yuzhou Wang; Siva Maguluri

[OpenReview](<https://openreview.net/forum?id=m4TAzup6Yc>) · [Official program](<https://icml.cc/virtual/2026/poster/61876>) · [PDF](<https://openreview.net/pdf?id=m4TAzup6Yc>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency.

**Training dynamics relevance:** Bounds how well Gaussian distributions approximate stationary stochastic-approximation iterates at finite step size.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Constant step size; dimension; temporal noise dependence.

**Training qualification:** Requires the stated convexity, contraction and noise conditions; general nonconvex training is outside the main result.

**Evidence:** Official accepted-paper title and abstract.

### Step-Size Stability in Stochastic Optimization: A Theoretical Perspective

**ICML 2026 · Accept (regular)** · Fabian Schaipp; Robert Gower; Adrien Taylor

[OpenReview](<https://openreview.net/forum?id=yhvzMLgpdV>) · [Official program](<https://icml.cc/virtual/2026/poster/60591>) · [PDF](<https://openreview.net/pdf?id=yhvzMLgpdV>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Training dynamics relevance:** Quantifies how optimization degrades when steps are too large and explains robustness advantages of adaptive rules.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Step-size misspecification; adaptive step rules.

**Training qualification:** Convex guarantees and nonconvex empirical behavior should be distinguished.

**Evidence:** Official accepted-paper title and abstract.

### The Geometric Origin of Grokking: Accelerating Generalization via Active Structural Reorganization

**ICML 2026 · Accept (regular)** · Kefei Tao; Zhang Zhang; Mingze Qi; Xiaojun Duan

[OpenReview](<https://openreview.net/forum?id=GMdvtJz5Ez>) · [Official program](<https://icml.cc/virtual/2026/poster/65146>) · [PDF](<https://openreview.net/pdf?id=GMdvtJz5Ez>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

**Training dynamics relevance:** Attributes delayed generalization to angular reorganization and proposes an intervention that accelerates it.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Representation geometry; repulsive regularization; training time.

**Training qualification:** The mechanism and intervention are assessed on the studied algorithmic and linguistic tasks.

**Evidence:** Official accepted-paper title and abstract.

### The Implicit Bias of Adam and Muon on Smooth Homogeneous Neural Networks

**ICML 2026 · Accept (regular)** · Eitan Gronich; Gal Vardi

[OpenReview](<https://openreview.net/forum?id=DpIc1cpNKG>) · [Official program](<https://icml.cc/virtual/2026/poster/65420>) · [PDF](<https://openreview.net/pdf?id=DpIc1cpNKG>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Characterizes the implicit max-margin biases of momentum steepest descent, Adam, Muon, and hybrid methods under stated homogeneous-model assumptions.

**Training dynamics relevance:** Characterizes the implicit max-margin biases of momentum steepest descent, Adam, Muon, and hybrid methods under stated homogeneous-model assumptions.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Optimizer geometry; momentum; max-margin bias.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### The Implicit Bias of Depth: From Neural Collapse to Softmax Codes

**ICML 2026 · Accept (regular)** · Connall Garrod; Jonathan Keating; Christos Thrampoulidis

[OpenReview](<https://openreview.net/forum?id=TDaVoBfTjY>) · [Official program](<https://icml.cc/virtual/2026/poster/63845>) · [PDF](<https://openreview.net/pdf?id=TDaVoBfTjY>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Analyzes how depth induces low-rank bias and alters the attraction to neural-collapse versus softmax-code solutions.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Depth; width; spectral/random initialization.

**Training qualification:** Uses the deep unconstrained feature model/deep linear setting.

**Evidence:** Official accepted-paper title and abstract.

### The Implicit Bias of Steepest Descent with Mini-batch Stochastic Gradient

**ICML 2026 · Accept (regular)** · Jichu Li; Xuan Tang; Difan Zou

[OpenReview](<https://openreview.net/forum?id=OT9cxeWbEO>) · [Official program](<https://icml.cc/virtual/2026/poster/64352>) · [PDF](<https://openreview.net/pdf?id=OT9cxeWbEO>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T2 — Batch size, gradient noise and training efficiency; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Studies how minibatching, momentum, and variance reduction affect the implicit bias of sign and spectral steepest descent.

**Training dynamics relevance:** Studies how minibatching, momentum, and variance reduction affect the implicit bias of sign and spectral steepest descent.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Minibatching; momentum; variance reduction; descent norm.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### The Stability of Singular Distribution: A Spectral Perspective on the Two-Phase Dynamics of Language Model Pre-training

**ICML 2026 · Accept (regular)** · Hongtao Zhang; WenJie Zhou; Chenxi Jia; Wei Chen; Xueqi Cheng

[OpenReview](<https://openreview.net/forum?id=gVPwive1z6>) · [Official program](<https://icml.cc/virtual/2026/poster/62448>) · [PDF](<https://openreview.net/pdf?id=gVPwive1z6>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Connects early stabilization of normalized singular spectra to slow pretraining dynamics across AdamW, Muon, and learning-rate schedules.

**Training dynamics relevance:** Connects early stabilization of normalized singular spectra to slow pretraining dynamics across AdamW, Muon, and learning-rate schedules.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Training stage; singular spectrum; optimizer choice.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Theoretical Analysis of Sparse Optimization with Reparameterization, Weight Decay, and Adaptive Learning Rate

**ICML 2026 · Accept (regular)** · Huangyu Xu; Jingqin Yang; Qianqian Xu; Jiaye Teng

[OpenReview](<https://openreview.net/forum?id=74PNBqBKPA>) · [Official program](<https://icml.cc/virtual/2026/poster/66097>) · [PDF](<https://openreview.net/pdf?id=74PNBqBKPA>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** ReWA connects these choices to sparse optimization and mitigates instability of nonconvex sparsity penalties.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Reparameterization; weight decay; adaptive learning rate.

**Training qualification:** The application is sparse ResNet training; sparse-regularization conclusions need not transfer unchanged to LLMs.

**Evidence:** Official accepted-paper title and abstract.

### To Grok Grokking: Provable Grokking in Ridge Regression

**ICML 2026 · Accept (spotlight)** · Mingyue Xu; Gal Vardi; Itay Safran

[OpenReview](<https://openreview.net/forum?id=5nNNVY8NW4>) · [Official program](<https://icml.cc/virtual/2026/oral/71134>) · [PDF](<https://openreview.net/pdf?id=5nNNVY8NW4>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Proves grokking in ridge regression and quantifies how training hyperparameters amplify or eliminate the delay.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Weight decay; learning rate; generalization delay.

**Training qualification:** End-to-end guarantees are linear; nonlinear support is empirical.

**Evidence:** Official accepted-paper title and abstract.

### Towards Efficient LLMs Annealing with Principled Sample Selection

**ICML 2026 · Accept (spotlight)** · Yuanjian Xu; Jianing Hao; Wanbo Zhang; Zhong Li; Guang Zhang

[OpenReview](<https://openreview.net/forum?id=2UH01A9Za0>) · [Official program](<https://icml.cc/virtual/2026/poster/66576>) · [PDF](<https://openreview.net/pdf?id=2UH01A9Za0>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency.

**Training dynamics relevance:** Selects annealing data to suppress noise in sharp directions while retaining useful descent signals in flatter subspaces.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Annealing schedule; sample selection; gradient noise.

**Training qualification:** The proposed selection rule depends on curvature/noise estimates; reported improvements are workload-specific.

**Evidence:** Official accepted-paper title and abstract.

### Towards Understanding Adam Convergence on Highly Degenerate Polynomials

**ICML 2026 · Accept (spotlight)** · Zhiwei Bai; Jiajie Zhao; Zhangchen Zhou; Zhi-Qin John Xu; Yaoyu Zhang

[OpenReview](<https://openreview.net/forum?id=uYWVGk1Qt0>) · [Official program](<https://icml.cc/virtual/2026/poster/61014>) · [PDF](<https://openreview.net/pdf?id=uYWVGk1Qt0>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

**Optimizer relevance:** Analyzes Adam's local convergence and oscillatory regimes on highly degenerate polynomials; useful optimizer theory, not an LLM-scale result.

**Training dynamics relevance:** Analyzes Adam's local convergence and oscillatory regimes on highly degenerate polynomials; useful optimizer theory, not an LLM-scale result.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Adam learning rate; degenerate-polynomial geometry.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Weight Decay Improves Language Model Plasticity

**ICML 2026 · Accept (regular)** · Tessa Han; Sebastian Bordt; Hanlin Zhang; Sham Kakade

[OpenReview](<https://openreview.net/forum?id=zMO9H4hLyR>) · [Official program](<https://icml.cc/virtual/2026/poster/60527>) · [PDF](<https://openreview.net/pdf?id=zMO9H4hLyR>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Studies how pretraining weight decay changes downstream plasticity, showing that base validation loss alone need not predict fine-tuning quality.

**Training dynamics relevance:** Studies how pretraining weight decay changes downstream plasticity, showing that base validation loss alone need not predict fine-tuning quality.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Pretraining weight decay; downstream plasticity.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### When Does Sparsity Mitigate the Curse of Depth in LLMs

**ICML 2026 · Accept (regular)** · Yao Yao; Xinyuan Song; Sebastian Pokutta; Max Zimmer; Nico Pelleriti; Thomas Hofmann; Shiwei Liu

[OpenReview](<https://openreview.net/forum?id=7boy4Ipbyn>) · [Official program](<https://icml.cc/virtual/2026/poster/66043>) · [PDF](<https://openreview.net/pdf?id=7boy4Ipbyn>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T7 — Initialization, normalization, weight decay and regularization.

**Training dynamics relevance:** Studies how sparsity-like mechanisms reduce residual variance and improve the usefulness of later Transformer layers.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Depth; sparsity; weight decay; context length; expert activation.

**Training qualification:** The link is supported by interventions but is not a universal depth-scaling theorem.

**Evidence:** Official accepted-paper title and abstract.

### Why Do We Need Warm-up? A Theoretical Perspective

**ICML 2026 · Accept (regular)** · Foivos Alimisis; Rustem Islamov; Aurelien Lucchi

[OpenReview](<https://openreview.net/forum?id=a6fo32UnpU>) · [Official program](<https://icml.cc/virtual/2026/poster/63104>) · [PDF](<https://openreview.net/pdf?id=a6fo32UnpU>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Optimizer relevance:** Derives a curvature-motivated learning-rate warm-up schedule, with theory and language/vision experiments.

**Training dynamics relevance:** Derives a curvature-motivated learning-rate warm-up schedule, with theory and language/vision experiments.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Learning-rate warm-up; curvature.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Zeroth-Order Optimization at the Edge of Stability

**ICML 2026 · Accept (regular)** · Minhak Song; Liang Zhang; Bingcong Li; Niao He; Michael Muehlebach; Sewoong Oh

[OpenReview](<https://openreview.net/forum?id=s87tQaKAER>) · [Official program](<https://icml.cc/virtual/2026/poster/61252>) · [PDF](<https://openreview.net/pdf?id=s87tQaKAER>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

**Optimizer relevance:** Analyzes zeroth-order edge-of-stability behavior using the full Hessian spectrum and tractable spectral bounds; empirical focus is vision.

**Training dynamics relevance:** Analyzes zeroth-order edge-of-stability behavior using the full Hessian spectrum and tractable spectral bounds; empirical focus is vision.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Zeroth-order perturbations; step size; curvature.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### A Minimalist Example of Edge-of-Stability and Progressive Sharpening

**NeurIPS 2025 · Accept (poster)** · Liming Liu; Zixuan Zhang; Simon Du; Tuo Zhao

[OpenReview](<https://openreview.net/forum?id=yst8MHfcgP>) · [Official program](<https://neurips.cc/virtual/2025/poster/115100>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/15eac388458e8a577f96edf7a40d0cbc-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/15eac388458e8a577f96edf7a40d0cbc-Abstract-Conference.html>)

**Training dynamics relevance:** Proves progressive sharpening and self-stabilization along the trajectory of a minimal network.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Large learning rate; input structure; sharpness.

**Training qualification:** The model has two input dimensions and is designed as a controlled explanatory example.

**Evidence:** Official accepted-paper title and abstract.

### A Theoretical Framework for Grokking: Interpolation followed by Riemannian Norm Minimisation

**NeurIPS 2025 · Accept (poster)** · Etienne Boursier; Scott Pesme; Radu-Alexandru Dragomir

[OpenReview](<https://openreview.net/forum?id=iSvAAHGFSw>) · [Official program](<https://neurips.cc/virtual/2025/poster/116559>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/de18052eb17cce56554a9637dd5aadba-Paper-Conference.pdf>)

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

### AdaLRS: Loss-Guided Adaptive Learning Rate Search for Efficient Foundation Model Pretraining

**NeurIPS 2025 · Accept (poster)** · Hongyuan Dong; Dingkang Yang; Xiao Liang; ChaoFeng; Ran Jiao

[OpenReview](<https://openreview.net/forum?id=Rc489jcc30>) · [Official program](<https://neurips.cc/virtual/2025/poster/118011>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/8516e0109e6c4a3cdd17645dd61af7c7-Paper-Conference.pdf>)

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

[OpenReview](<https://openreview.net/forum?id=kCUDzyKQ7G>) · [Official program](<https://neurips.cc/virtual/2025/poster/116405>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/a82b0c6d19e4f53c5f2252a742ae8d5e-Paper-Conference.pdf>)

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

[OpenReview](<https://openreview.net/forum?id=MKEDsVWHd0>) · [Official program](<https://neurips.cc/virtual/2025/poster/118480>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/2aacf95ddc1ebd79832474bb41d13943-Paper-Conference.pdf>)

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

[OpenReview](<https://openreview.net/forum?id=t7LKc0MMW6>) · [Official program](<https://neurips.cc/virtual/2025/poster/115627>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/06cbd2e81dfbd3bb4cb0abce95b32584-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/06cbd2e81dfbd3bb4cb0abce95b32584-Abstract-Conference.html>)

**Training dynamics relevance:** Alternating Gradient Flows approximates successive feature acquisition and loss drops from small initialization.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Initialization scale; feature activation times.

**Training qualification:** Rigorous limiting results concern specified network classes and vanishing initialization.

**Evidence:** Official accepted-paper title and abstract.

### An Analytical Theory of Spectral Bias in the Learning Dynamics of Diffusion Models

**NeurIPS 2025 · Accept (spotlight)** · Binxu Wang; Cengiz Pehlevan

[OpenReview](<https://openreview.net/forum?id=SDhOClkyqC>) · [Official program](<https://neurips.cc/virtual/2025/poster/117950>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/8a0d3f77bb435817807d463c5dcef1ab-Paper-Conference.pdf>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/8a0d3f77bb435817807d463c5dcef1ab-Abstract-Conference.html>)

**Training dynamics relevance:** Solves spectral learning dynamics for simple denoisers and studies their implications for diffusion-model generation.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Training time; data spectrum; stopping time.

**Training qualification:** Exact formulas concern linear/linear-convolutional denoisers; deeper-model extensions are empirical.

**Evidence:** Official accepted-paper title and abstract.

### Any-stepsize Gradient Descent for Separable Data under Fenchel–Young Losses

**NeurIPS 2025 · Accept (spotlight)** · Han Bao; Shinsaku Sakaue; Yuki Takezawa

[OpenReview](<https://openreview.net/forum?id=D6aCr4RRdt>) · [Official program](<https://neurips.cc/virtual/2025/poster/119241>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/69f98acf161316ed896047e45da3bc0c-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/69f98acf161316ed896047e45da3bc0c-Abstract-Conference.html>)

**Training dynamics relevance:** Studies convergence with arbitrarily chosen fixed steps under Fenchel-Young losses on separable data.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Constant step size; loss choice; separation margin.

**Training qualification:** Arbitrary-step convergence relies on separability/loss structure and is not a guarantee for arbitrary neural losses.

**Evidence:** Official accepted-paper title and abstract.

### Asymptotic theory of SGD with a general learning-rate

**NeurIPS 2025 · Accept (poster)** · Or Goldreich; Ziyang Wei; SOHAM BONNERJEE; Jiaqi Li; Wei Biao Wu

[OpenReview](<https://openreview.net/forum?id=y5Diyh9XEQ>) · [Official program](<https://neurips.cc/virtual/2025/poster/115186>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/21ad9738bb0d93eb2e9ade69ff809da0-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/21ad9738bb0d93eb2e9ade69ff809da0-Abstract-Conference.html>)

**Training dynamics relevance:** Develops asymptotic SGD uncertainty theory for schedules beyond polynomial decay.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Cyclical learning rates; linear decay; general schedules.

**Training qualification:** The results are asymptotic under regularity conditions; they do not select a universally optimal practical schedule.

**Evidence:** Official accepted-paper title and abstract.

### Closed-Form Training Dynamics Reveal Learned Features and Linear Structure in Word2Vec-like Models

**NeurIPS 2025 · Accept (poster)** · Dhruva Karkada; James Simon; Yasaman Bahri; Michael Deweese

[OpenReview](<https://openreview.net/forum?id=VS9N6q6b0k>) · [Official program](<https://neurips.cc/virtual/2025/poster/117686>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/060f64f690417a5cc6a882479478fd96-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/060f64f690417a5cc6a882479478fd96-Abstract-Conference.html>)

**Training dynamics relevance:** Solves approximate Word2Vec-like gradient-flow dynamics and explains sequential acquisition of corpus-derived subspaces.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Initialization; training time; embedding dimension.

**Training qualification:** Closed forms use a quartic loss approximation; resemblance to Word2Vec is empirically assessed.

**Evidence:** Official accepted-paper title and abstract.

### Communication-Efficient Language Model Training Scales Reliably and Robustly: Scaling Laws for DiLoCo

**NeurIPS 2025 · Accept (spotlight)** · Zachary Charles; Gabriel Teston; Lucio Dery; John Rush; Nova Fallen; Zachary Garrett; Arthur Szlam; Arthur Douillard

[OpenReview](<https://openreview.net/forum?id=X4SCxcgb3O>) · [Official program](<https://neurips.cc/virtual/2025/poster/117548>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/99acb4c087266e80b547aed79247266b-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T2 — Batch size, gradient noise and training efficiency; T4 — Compute, data and model scaling laws; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/99acb4c087266e80b547aed79247266b-Abstract-Conference.html>)

**Training dynamics relevance:** Studies how DiLoCo scaling changes with model size and tuning under fixed compute.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Replica count; local-update settings; token budget; batch size.

**Training qualification:** Advantages over data parallelism are conditional on tuning and the evaluated communication/training regime.

**Evidence:** Official accepted-paper title and abstract.

### Complexity Scaling Laws for Neural Models using Combinatorial Optimization

**NeurIPS 2025 · Accept (poster)** · Lowell Weissman; Michael Krumdick; A. Abbott

[OpenReview](<https://openreview.net/forum?id=EdKl4PulMX>) · [Official program](<https://neurips.cc/virtual/2025/poster/119119>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1c9dbe4d49fa0ac833959230a9895c06-Paper-Conference.pdf>)

**Categories:** T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/1c9dbe4d49fa0ac833959230a9895c06-Abstract-Conference.html>)

**Training dynamics relevance:** Studies predictable suboptimality trends as combinatorial task complexity grows.

**Training study context:** Reinforcement learning.

**Hyperparameters / scaling axes:** Problem size/complexity; model capacity.

**Training qualification:** The case study is TSP; this is task-complexity scaling rather than Chinchilla-style LLM pretraining.

**Evidence:** Official accepted-paper title and abstract.

### Compute-Optimal Scaling for Value-Based Deep RL

**NeurIPS 2025 · Accept (poster)** · Preston Fu; Oleh Rybkin; Zhiyuan (Paul) Zhou; Michal Nauman; Pieter Abbeel; Sergey Levine; Aviral Kumar

[OpenReview](<https://openreview.net/forum?id=9GzyCtlngK>) · [Official program](<https://neurips.cc/virtual/2025/poster/119555>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/eaf550b6c727bc065244513f2260a30e-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T2 — Batch size, gradient noise and training efficiency; T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/eaf550b6c727bc065244513f2260a30e-Abstract-Conference.html>)

**Training dynamics relevance:** Studies compute allocation in value-based RL and explains when large batches induce TD overfitting.

**Training study context:** Reinforcement learning.

**Hyperparameters / scaling axes:** Model size; batch size; update-to-data ratio.

**Training qualification:** The compute-optimal trade-offs are RL-specific and differ from token-based pretraining.

**Evidence:** Official accepted-paper title and abstract.

### Controlling the Flow: Stability and Convergence for Stochastic Gradient Descent with Decaying Regularization

**NeurIPS 2025 · Accept (poster)** · Sebastian Kassing; Simon Weissmann; Leif Döring

[OpenReview](<https://openreview.net/forum?id=hMZnFo0FLF>) · [Official program](<https://neurips.cc/virtual/2025/poster/116658>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/6cf05c14e645df408001fbb669976ec0-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/6cf05c14e645df408001fbb669976ec0-Abstract-Conference.html>)

**Training dynamics relevance:** Analyzes how step sizes and decaying Tikhonov regularization jointly control SGD convergence to minimum-norm solutions.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Step-size schedule; vanishing regularization.

**Training qualification:** Convex smooth Hilbert-space theory, with inverse-problem examples, rather than arbitrary deep learning.

**Evidence:** Official accepted-paper title and abstract.

### Convergence Rates for Gradient Descent on the Edge of Stability for Overparametrised Least Squares

**NeurIPS 2025 · Accept (poster)** · Lachlan MacDonald; Hancheng Min; Leandro Palma; Salma Tarmoun; Ziqing Xu; Rene Vidal

[OpenReview](<https://openreview.net/forum?id=MU0JuT0A54>) · [Official program](<https://neurips.cc/virtual/2025/poster/118466>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/d9af4d6ac714626b652da5616ca71f99-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/d9af4d6ac714626b652da5616ca71f99-Abstract-Conference.html>)

**Training dynamics relevance:** Decomposes GD into motion along and across a minimizer manifold and characterizes three stability regimes.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Learning rate; overparameterization; minimizer geometry.

**Training qualification:** Formal rates concern overparameterized least squares, with different limits across subcritical, critical and supercritical rates.

**Evidence:** Official accepted-paper title and abstract.

### Critical Batch Size Revisited: A Simple Empirical Approach to Large-Batch Language Model Training

**NeurIPS 2025 · Accept (spotlight)** · Will Merrill; Shane Arora; Dirk Groeneveld; Hanna Hajishirzi

[OpenReview](<https://openreview.net/forum?id=XUKUx7Xu89>) · [Official program](<https://neurips.cc/virtual/2025/poster/117500>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/a99f732df9b668284b449da0214a3286-Paper-Conference.pdf>)

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

[OpenReview](<https://openreview.net/forum?id=tQZK5frjVU>) · [Official program](<https://neurips.cc/virtual/2025/poster/115595>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/eee7ae5cf0c4356c2aeca400771791aa-Paper-Conference.pdf>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/eee7ae5cf0c4356c2aeca400771791aa-Abstract-Conference.html>)

**Training dynamics relevance:** Finds abrupt knowledge-acquisition transitions when dense knowledge data are mixed with web text.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Data mixing ratio; model capacity; training duration.

**Training qualification:** The controlled biography study shows that mixture rankings can change with size; it is not a universal discontinuity claim.

**Evidence:** Official accepted-paper title and abstract.

### Don't be lazy: CompleteP enables compute-efficient deep transformers

**NeurIPS 2025 · Accept (poster)** · Nolan Dey; Bin Zhang; Lorenzo Noci; Mufan Li; Blake Bordelon; Shane Bergsma; Cengiz Pehlevan; Boris Hanin; Joel Hestness

[OpenReview](<https://openreview.net/forum?id=lMU2kaMANl>) · [Official program](<https://neurips.cc/virtual/2025/poster/116289>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/c917d8b9e01427f3184d80ade22f4d1f-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/c917d8b9e01427f3184d80ade22f4d1f-Abstract-Conference.html>)

**Optimizer relevance:** CompleteP develops depth/width parameterization rules for hyperparameter transfer in language-model training.

**Training dynamics relevance:** CompleteP develops depth/width parameterization rules for hyperparameter transfer in language-model training.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Depth/width parameterization; feature learning; rate transfer.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/EleutherAI/nanoGPT-mup/tree/completep.>). Links extracted from the accepted abstract; code was not tested.

### Emergence and scaling laws in SGD learning of shallow neural networks

**NeurIPS 2025 · Accept (poster)** · Yunwei Ren; Eshaan Nichani; Denny Wu; Jason Lee

[OpenReview](<https://openreview.net/forum?id=kA2H90nm26>) · [Official program](<https://neurips.cc/virtual/2025/poster/116407>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/36d13b71487b29965a2d3f5fcc109afc-Paper-Conference.pdf>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/36d13b71487b29965a2d3f5fcc109afc-Abstract-Conference.html>)

**Training dynamics relevance:** Shows many abrupt feature-learning transitions can combine into smooth aggregate scaling laws.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Teacher/student width; signal strengths; SGD time.

**Training qualification:** The theory uses shallow networks, Gaussian inputs and specified activation structure.

**Evidence:** Official accepted-paper title and abstract.

### EvoLM: In Search of Lost Language Model Training Dynamics

**NeurIPS 2025 · Accept (oral)** · Zhenting Qi; Fan Nie; Alexandre Alahi; James Zou; Himabindu Lakkaraju; Yilun Du; Eric Xing; Sham Kakade; Hanlin Zhang

[OpenReview](<https://openreview.net/forum?id=B6bE2GC71a>) · [Official program](<https://neurips.cc/virtual/2025/poster/119408>) · [PDF](<https://openreview.net/pdf?id=B6bE2GC71a>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

**Training dynamics relevance:** EvoLM provides controlled multi-stage trajectories to study diminishing returns, forgetting and stage transitions.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Pretraining duration; continued training; SFT/RL design.

**Training qualification:** Its 1B/4B model suite supports specific empirical comparisons, not all production-scale training regimes.

**Evidence:** Official accepted-paper title and abstract.

### From Condensation to Rank Collapse: A Two-Stage Analysis of Transformer Training Dynamics

**NeurIPS 2025 · Accept (oral)** · Zheng-An Chen; Tao Luo

[OpenReview](<https://openreview.net/forum?id=gm5mkiTGOy>) · [Official program](<https://neurips.cc/virtual/2025/poster/116705>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/3b576711b12ab036b45130fc8eb78504-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T6 — Feature learning, implicit bias and generalization dynamics; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/3b576711b12ab036b45130fc8eb78504-Abstract-Conference.html>)

**Training dynamics relevance:** Analyzes early condensation followed by late rank collapse in Transformer attention factors.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Initialization scale; attention-factor dynamics.

**Training qualification:** A linearized gradient-flow model rather than a full nonlinear Transformer training theorem.

**Evidence:** Official accepted-paper title and abstract.

### From Information to Generative Exponent: Learning Rate Induces Phase Transitions in SGD

**NeurIPS 2025 · Accept (poster)** · Konstantinos Tsiolis; Alireza Mousavi-Hosseini; Murat Erdogdu

[OpenReview](<https://openreview.net/forum?id=Pf3SVNhAQB>) · [Official program](<https://neurips.cc/virtual/2025/poster/118200>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/77b7d565f2370979b898d76d7ea27288-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/77b7d565f2370979b898d76d7ea27288-Abstract-Conference.html>)

**Training dynamics relevance:** Shows learning rates can switch single-index learning between information-exponent and generative-exponent regimes.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Learning rate; layer timescales; sample reuse.

**Training qualification:** The sample-complexity transition is proved for structured Gaussian single-index models.

**Evidence:** Official accepted-paper title and abstract.

### Functional Scaling Laws in Kernel Regression: Loss Dynamics and Learning Rate Schedules

**NeurIPS 2025 · Accept (spotlight)** · Binghui Li; Fengling Chen; Zixun Huang; Lean Wang; Lei Wu

[OpenReview](<https://openreview.net/forum?id=dpllevHMbc>) · [Official program](<https://neurips.cc/virtual/2025/poster/116983>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/92abec9d3f278c648dfe99c8b8f35954-Paper-Conference.pdf>)

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

[OpenReview](<https://openreview.net/forum?id=aCPFvEg22L>) · [Official program](<https://neurips.cc/virtual/2025/poster/117289>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/7aae9e3ec211249e05bd07271a6b1441-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/7aae9e3ec211249e05bd07271a6b1441-Abstract-Conference.html>)

**Training dynamics relevance:** Gives Gaussian approximations and concentration results for constant-rate SGD iterates.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Constant learning rate; initialization; stochastic fluctuations.

**Training qualification:** The conclusions require the paper's regularity/noise assumptions, rather than arbitrary nonconvex LLM trajectories.

**Evidence:** Official accepted-paper title and abstract.

### Gemstones: A Model Suite for Multi-Faceted Scaling Laws

**NeurIPS 2025 · Accept (poster)** · Sean McLeish; John Kirchenbauer; David Miller; Siddharth Singh; Abhinav Bhatele; Micah Goldblum; Ashwinee Panda; Tom Goldstein

[OpenReview](<https://openreview.net/forum?id=iZk78dZ1Ap>) · [Official program](<https://neurips.cc/virtual/2025/poster/116550>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/b2b781badeeb49896c4b324c466ec442-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/b2b781badeeb49896c4b324c466ec442-Abstract-Conference.html>)

**Training dynamics relevance:** Gemstones shows scaling prescriptions can depend strongly on architecture, hyperparameter choices and which checkpoints enter the fit.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Width/depth shape; learning rate; cooldown; fit design.

**Training qualification:** A direct warning about experimental-design sensitivity; a fitted exponent is not recipe-independent.

**Evidence:** Official accepted-paper title and abstract.

### How to Scale Second-Order Optimization

**NeurIPS 2025 · Accept (poster)** · Charlie Chen; Shikai Qiu; Hoang Phan; Qi Lei; Andrew Wilson

[OpenReview](<https://openreview.net/forum?id=Ei6IsmxYrb>) · [Official program](<https://neurips.cc/virtual/2025/poster/119109>) · [PDF](<https://openreview.net/pdf?id=Ei6IsmxYrb>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

**Optimizer relevance:** Studies width/depth transfer of hyperparameters for Shampoo, SOAP and Muon, including blocking, grafting and weight decay in language-model training.

**Training dynamics relevance:** Studies width/depth transfer of hyperparameters for Shampoo, SOAP and Muon, including blocking, grafting and weight decay in language-model training.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Width/depth; weight decay; Shampoo/SOAP/Muon; grafting.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Implicit Bias of Spectral Descent and Muon on Multiclass Separable Data

**NeurIPS 2025 · Accept (spotlight)** · Chen Fan; Mark Schmidt; Christos Thrampoulidis

[OpenReview](<https://openreview.net/forum?id=Zn2ajV1kTQ>) · [Official program](<https://neurips.cc/virtual/2025/poster/117324>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/386432c7534eec9a1cd7cbeea90d7e9f-Paper-Conference.pdf>)

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

[OpenReview](<https://openreview.net/forum?id=jeen4x145W>) · [Official program](<https://neurips.cc/virtual/2025/poster/116442>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/82b76a72a9df183498cf0be3df6eef71-Paper-Conference.pdf>)

**Categories:** T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/82b76a72a9df183498cf0be3df6eef71-Abstract-Conference.html>)

**Training dynamics relevance:** Shows multiple SGD passes can improve data-constrained scaling in sketched linear regression.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Epochs/data reuse; model dimension; spectral decay.

**Training qualification:** Power-law covariance and target alignment assumptions qualify the improved exponents.

**Evidence:** Official accepted-paper title and abstract.

### In Search of Adam’s Secret Sauce

**NeurIPS 2025 · Accept (oral)** · Antonio Orvieto; Robert Gower

[OpenReview](<https://openreview.net/forum?id=CH72XyZs4y>) · [Official program](<https://neurips.cc/virtual/2025/poster/119297>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/5bd9aa206d782e4e1f7ab5d177a10828-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T7 — Initialization, normalization, weight decay and regularization; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/5bd9aa206d782e4e1f7ab5d177a10828-Abstract-Conference.html>)

**Training dynamics relevance:** Compares carefully tuned Adam simplifications and explains why equal momentum parameters retain much of Adam's performance.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Adam beta1/beta2; clipping; learning rate; optimizer choice.

**Training qualification:** The equal-beta result is empirical over tested settings; the associated statistical interpretation has specified assumptions.

**Evidence:** Official accepted-paper title and abstract.

### Infinite-Width Limit of a Single Attention Layer: Analysis via Tensor Programs

**NeurIPS 2025 · Accept (poster)** · Mana Sakai; Ryo Karakida; Masaaki Imaizumi

[OpenReview](<https://openreview.net/forum?id=gZzLjIYzH1>) · [Official program](<https://neurips.cc/virtual/2025/poster/116729>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/33201f38001dd381aba2c462051449ba-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/33201f38001dd381aba2c462051449ba-Abstract-Conference.html>)

**Training dynamics relevance:** Derives a non-Gaussian infinite-width limit for finite-head attention under standard score scaling.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Attention width; head count; score scaling.

**Training qualification:** A single-layer initialization/limit result, not a full trained Transformer dynamics theorem.

**Evidence:** Official accepted-paper title and abstract.

### Is Grokking a Computational Glass Relaxation?

**NeurIPS 2025 · Accept (spotlight)** · Xiaotian Zhang; Yue Shang; Entao Yang; Ge Zhang

[OpenReview](<https://openreview.net/forum?id=Tk5nQnTGmP>) · [Official program](<https://neurips.cc/virtual/2025/poster/117824>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/92f67b9047fa7a43d7506054b5f0ec6a-Paper-Conference.pdf>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/92f67b9047fa7a43d7506054b5f0ec6a-Abstract-Conference.html>)

**Training dynamics relevance:** Interprets grokking as nonequilibrium glass relaxation and studies counterexamples to simple weight-norm explanations.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Training time; entropy; optimizer dynamics.

**Training qualification:** The physical analogy and optimizer demonstration use controlled arithmetic tasks.

**Evidence:** Official accepted-paper title and abstract.

### L$^2$M: Mutual Information Scaling Law for Long-Context Language Modeling

**NeurIPS 2025 · Accept (poster)** · Zhuo Chen; Oriol Comas; Zhuotao Jin; Di Luo; Marin Soljacic

[OpenReview](<https://openreview.net/forum?id=s3maemwE5M>) · [Official program](<https://neurips.cc/virtual/2025/poster/115721>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/c9da56addea9c977cf4ba873e1da979d-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/c9da56addea9c977cf4ba873e1da979d-Abstract-Conference.html>)

**Training dynamics relevance:** Relates long-context model capacity to bipartite mutual-information scaling in language.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Context length; history-state capacity; architecture.

**Training qualification:** A capacity requirement rather than an optimized learning-rate schedule or convergence guarantee.

**Evidence:** Official accepted-paper title and abstract.

### Large Stepsizes Accelerate Gradient Descent for Regularized Logistic Regression

**NeurIPS 2025 · Accept (poster)** · Jingfeng Wu; Pierre Marion; Peter Bartlett

[OpenReview](<https://openreview.net/forum?id=w22e5MrS4X>) · [Official program](<https://neurips.cc/virtual/2025/poster/115359>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/96b8167534ef3cc30c230bbeb55a524d-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/96b8167534ef3cc30c230bbeb55a524d-Abstract-Conference.html>)

**Training dynamics relevance:** Shows nonmonotone large-step GD can accelerate regularized logistic regression.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Large constant step size; l2 regularization.

**Training qualification:** The guarantees require separable data and the stated loss structure.

**Evidence:** Official accepted-paper title and abstract.

### Learning in Compact Spaces with Approximately Normalized Transformer

**NeurIPS 2025 · Accept (poster)** · Jörg Franke; Urs Spiegelhalter; Marianna Nezhurina; Jenia Jitsev; Frank Hutter; Michael Hefenbrock

[OpenReview](<https://openreview.net/forum?id=dH8mKmvADv>) · [Official program](<https://neurips.cc/virtual/2025/poster/117015>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/6dcdf117a037f459e53205d3f3af4a77-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/6dcdf117a037f459e53205d3f3af4a77-Abstract-Conference.html>)

**Training dynamics relevance:** Approximately normalized Transformers study a training recipe that reduces normalization overhead and removes some tuning knobs.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Norm constraints; warm-up; weight decay; batch size.

**Training qualification:** The claimed removal of warm-up/decay is architecture-specific, not a prescription for ordinary Transformers.

**Evidence:** Official accepted-paper title and abstract.

### Learning quadratic neural networks in high dimensions: SGD dynamics and scaling laws

**NeurIPS 2025 · Accept (poster)** · Gerard Ben Arous; Murat Erdogdu; Nuri Mert Vural; Denny Wu

[OpenReview](<https://openreview.net/forum?id=m3Sz3tFxIV>) · [Official program](<https://neurips.cc/virtual/2025/poster/116241>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/d7ce06e9293c3d8e6cb3f80b4157f875-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/d7ce06e9293c3d8e6cb3f80b4157f875-Abstract-Conference.html>)

**Training dynamics relevance:** Derives learning dynamics and risk scaling in high-dimensional quadratic neural networks.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Width; SGD steps; samples; signal spectrum.

**Training qualification:** The exact dynamics rely on orthogonal signals and structured Gaussian data.

**Evidence:** Official accepted-paper title and abstract.

### New Perspectives on the Polyak Stepsize: Surrogate Functions and Negative Results

**NeurIPS 2025 · Accept (poster)** · Francesco Orabona; Ryan D&#x27;Orazio

[OpenReview](<https://openreview.net/forum?id=7GwcxPIkip>) · [Official program](<https://neurips.cc/virtual/2025/poster/119719>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/e45879046fd900c2536e419e361c94c0-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/e45879046fd900c2536e419e361c94c0-Abstract-Conference.html>)

**Training dynamics relevance:** Unifies Polyak rules as descent on surrogate losses and establishes concrete non-convergence cases.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Polyak step-size variants; local curvature.

**Training qualification:** Variant-specific assumptions matter; adaptive step-size rules are not universally safe.

**Evidence:** Official accepted-paper title and abstract.

### On the Surprising Effectiveness of Large Learning Rates under Standard Width Scaling

**NeurIPS 2025 · Accept (spotlight)** · Moritz Haas; Sebastian Bordt; Ulrike Luxburg; Leena Chennuru Vankadara

[OpenReview](<https://openreview.net/forum?id=hTxnm6H93P>) · [Official program](<https://neurips.cc/virtual/2025/poster/116648>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/3eec5006051d9544e717067de3220198-Paper-Conference.pdf>)

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

[OpenReview](<https://openreview.net/forum?id=PMSNd8xTHp>) · [Official program](<https://neurips.cc/virtual/2025/poster/118224>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/83b17fb3369b1effa97ca5409526b02e-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/83b17fb3369b1effa97ca5409526b02e-Abstract-Conference.html>)

**Training dynamics relevance:** ParetoQ compares low-bit regimes and identifies qualitatively different representation changes below three bits.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Quantization bit width; training scheme; model size.

**Training qualification:** Accuracy/size trade-offs are implementation- and hardware-dependent; one bit width is not universally optimal.

**Evidence:** Official accepted-paper title and abstract.

### Power Lines: Scaling laws for weight decay and batch size in LLM pre-training

**NeurIPS 2025 · Accept (poster)** · Shane Bergsma; Nolan Dey; Gurpreet Gosal; Gavia Gray; Daria Soboleva; Joel Hestness

[OpenReview](<https://openreview.net/forum?id=bFXbLQzRoZ>) · [Official program](<https://neurips.cc/virtual/2025/poster/117191>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/b5f78a17a94da3e34c935515d1b6adae-Paper-Conference.pdf>)

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

[OpenReview](<https://openreview.net/forum?id=2Gnp8sdwVe>) · [Official program](<https://neurips.cc/virtual/2025/poster/120156>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/ae9f1d3b89a81fcb1c45b4fc1afbd4fe-Paper-Conference.pdf>)

**Categories:** T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/ae9f1d3b89a81fcb1c45b4fc1afbd4fe-Abstract-Conference.html>)

**Training dynamics relevance:** Farseer fits a refined loss surface to improve evaluation of training strategies and compute allocation across scales.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Parameters; tokens; small-to-large extrapolation.

**Training qualification:** Prediction quality depends on the fitted model families and design of the scaling experiments.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/Farseer-Scaling-Law/Farseer>). Links extracted from the accepted abstract; code was not tested.

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

### Revisiting Glorot Initialization for Long-Range Linear Recurrences

**NeurIPS 2025 · Accept (poster)** · Noga Bar; Mariia Seleznova; ‪Yotam Alexander‬‏; Gitta Kutyniok; Raja Giryes

[OpenReview](<https://openreview.net/forum?id=bd8kppxyB3>) · [Official program](<https://neurips.cc/virtual/2025/poster/117163>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/4fbc7f29151b7c1f0e1f1e5c51c4f5b3-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/4fbc7f29151b7c1f0e1f1e5c51c4f5b3-Abstract-Conference.html>)

**Training dynamics relevance:** Shows finite-width spectral-radius deviations can destabilize long recurrences and proposes dimension-aware rescaling.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Recurrent width; sequence length; initialization scale.

**Training qualification:** The formal setting is linear recurrence; sequence length and width must be considered jointly.

**Evidence:** Official accepted-paper title and abstract.

### Revisiting Residual Connections: Orthogonal Updates for Stable and Efficient Deep Networks

**NeurIPS 2025 · Accept (poster)** · Giyeong Oh; Woohyun Cho; Siyeol Kim; Suhwan Choi; Youngjae Yu

[OpenReview](<https://openreview.net/forum?id=LWmfHjJnrx>) · [Official program](<https://neurips.cc/virtual/2025/poster/118548>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/67c15da4a9340140c60783d9a175fd3f-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/67c15da4a9340140c60783d9a175fd3f-Abstract-Conference.html>)

**Training dynamics relevance:** Projects residual contributions orthogonally to the current stream to improve stability and feature diversity.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Residual-update geometry; depth.

**Training qualification:** Results are for the studied vision architectures; LLM hyperparameter transfer is not demonstrated.

**Evidence:** Official accepted-paper title and abstract.

**Code links listed by authors:** [Repository](<https://github.com/BootsofLagrangian/ortho-residual.>). Links extracted from the accepted abstract; code was not tested.

### Scaling Diffusion Transformers Efficiently via $\mu$P

**NeurIPS 2025 · Accept (poster)** · Chenyu Zheng; Xinyu Zhang; Rongzhen Wang; Wei Huang; Zhi Tian; Weilin Huang; Jun Zhu; Chongxuan LI

[OpenReview](<https://openreview.net/forum?id=VfIOdGiBAv>) · [Official program](<https://neurips.cc/virtual/2025/poster/117664>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1bf3dbbd6346f50627e2ab1795f90435-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T3 — Width/depth scaling and hyperparameter transfer.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/1bf3dbbd6346f50627e2ab1795f90435-Abstract-Conference.html>)

**Training dynamics relevance:** Extends maximal-update parameterization to diffusion Transformers and tests small-to-large hyperparameter transfer.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** MuP parameterization; width; transferred learning rate.

**Training qualification:** Architectural/objective conditions of the derivation matter; not every generative architecture is covered.

**Evidence:** Official accepted-paper title and abstract.

### Scaling Law with Learning Rate Annealing

**NeurIPS 2025 · Accept (poster)** · Howe Tissue; Venus Wang; Lu Wang

[OpenReview](<https://openreview.net/forum?id=VBx4yMNtjt>) · [Official program](<https://neurips.cc/virtual/2025/poster/117707>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/830b1abc6d2da85f23d41169fa44d185-Paper-Conference.pdf>)

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

[OpenReview](<https://openreview.net/forum?id=VUbwLjLkws>) · [Official program](<https://neurips.cc/virtual/2025/poster/117684>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/d51397f67732d310809220b1236f4702-Paper-Conference.pdf>)

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

[OpenReview](<https://openreview.net/forum?id=vVU1KTOsju>) · [Official program](<https://neurips.cc/virtual/2025/poster/115404>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/bc1d640f841f752c689aae20b31198c1-Paper-Conference.pdf>)

**Categories:** T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/bc1d640f841f752c689aae20b31198c1-Abstract-Conference.html>)

**Training dynamics relevance:** Predicts losses and optimal mixtures using small runs across language, vision and multimodal pretraining.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Data-mixture weights; parameters; tokens.

**Training qualification:** Cross-scale extrapolation requires a suitable fitted mixture law and compatible domain definitions.

**Evidence:** Official accepted-paper title and abstract.

### Sloth: scaling laws for LLM skills to predict multi-benchmark performance across families

**NeurIPS 2025 · Accept (poster)** · Felipe Maia Polo; Seamus Somerstep; Leshem Choshen; Yuekai Sun; Mikhail Yurochkin

[OpenReview](<https://openreview.net/forum?id=9GN5Jsa3lv>) · [Official program](<https://neurips.cc/virtual/2025/poster/119556>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/3834d037cd6e29ac7649df42611c5d66-Paper-Conference.pdf>)

**Categories:** T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/3834d037cd6e29ac7649df42611c5d66-Abstract-Conference.html>)

**Training dynamics relevance:** Sloth shares latent-skill information across benchmarks and model families to predict downstream scaling.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Parameters; tokens; family-specific efficiency; latent skills.

**Training qualification:** Observational cross-family benchmark prediction does not isolate every training-recipe effect.

**Evidence:** Official accepted-paper title and abstract.

### Small Batch Size Training for Language Models: When Vanilla SGD Works, and Why Gradient Accumulation is Wasteful

**NeurIPS 2025 · Accept (poster)** · Martin Marek; Sanae Lotfi; Aditya Somasundaram; Andrew Wilson; Micah Goldblum

[OpenReview](<https://openreview.net/forum?id=52Ehpe0Lu5>) · [Official program](<https://neurips.cc/virtual/2025/poster/119899>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/dabfbf500318462382aa70a95466ad85-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T2 — Batch size, gradient noise and training efficiency; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/dabfbf500318462382aa70a95466ad85-Abstract-Conference.html>)

**Optimizer relevance:** Examines small-batch language-model training and how Adam second-moment timescales should be measured in tokens; includes vanilla SGD comparisons.

**Training dynamics relevance:** Examines small-batch language-model training and how Adam second-moment timescales should be measured in tokens; includes vanilla SGD comparisons.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Small batches; second-moment half-life; accumulation.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Sparse Polyak: an adaptive step size rule for high-dimensional M-estimation

**NeurIPS 2025 · Accept (poster)** · Tianqi Qiao; Marie Maros

[OpenReview](<https://openreview.net/forum?id=ddyJqXyCxE>) · [Official program](<https://neurips.cc/virtual/2025/poster/116994>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/032c421541ad303d9cfa36161a381ed6-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/032c421541ad303d9cfa36161a381ed6-Abstract-Conference.html>)

**Training dynamics relevance:** Modifies Polyak adaptation to estimate smoothness in statistically relevant sparse directions.

**Training study context:** General optimization.

**Hyperparameters / scaling axes:** Polyak step size; dimension; restricted smoothness.

**Training qualification:** Targets high-dimensional M-estimation rather than general foundation-model training.

**Evidence:** Official accepted-paper title and abstract.

### Stepsize anything: A unified learning rate schedule for budgeted-iteration training

**NeurIPS 2025 · Accept (poster)** · Anda Tang; Yiming Dong; Yutao Zeng; zhou Xun; Zhouchen Lin

[OpenReview](<https://openreview.net/forum?id=rNcIJi7N65>) · [Official program](<https://neurips.cc/virtual/2025/poster/115783>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/dce0ad3bd4981fea9a5a5a274a2256d9-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/dce0ad3bd4981fea9a5a5a274a2256d9-Abstract-Conference.html>)

**Optimizer relevance:** Develops budget-aware learning-rate schedules designed to transfer across training lengths.

**Training dynamics relevance:** Develops budget-aware learning-rate schedules designed to transfer across training lengths.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Training budget; learning-rate schedule.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.

### Superposition Yields Robust Neural Scaling

**NeurIPS 2025 · Accept (oral)** · Yizhou Liu; Ziming Liu; Jeff Gore

[OpenReview](<https://openreview.net/forum?id=knPz7gtjPW>) · [Official program](<https://neurips.cc/virtual/2025/poster/116346>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/e97ac22927560eb2de6b658498cbc575-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/e97ac22927560eb2de6b658498cbc575-Abstract-Conference.html>)

**Training dynamics relevance:** Links strong feature superposition to robust inverse-dimension loss scaling.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Representation dimension; weight decay; superposition strength.

**Training qualification:** The mechanism is established in a toy representation model with supporting observations on LLMs.

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

### The Rich and the Simple: On the Implicit Bias of Adam and SGD

**NeurIPS 2025 · Accept (poster)** · Bhavya Vasudeva; Jung Lee; Vatsal Sharan; Mahdi Soltanolkotabi

[OpenReview](<https://openreview.net/forum?id=XLvHmzaHsx>) · [Official program](<https://neurips.cc/virtual/2025/poster/117522>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/ec9b2a6ad5444caeff75efaa6176b3e4-Paper-Conference.pdf>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/ec9b2a6ad5444caeff75efaa6176b3e4-Abstract-Conference.html>)

**Training dynamics relevance:** Explains how Adam can resist SGD simplicity bias and learn richer decision boundaries.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Adam versus SGD; learned feature complexity.

**Training qualification:** Formal analysis uses two-layer ReLU population gradients; robustness improvements are distribution-dependent.

**Evidence:** Official accepted-paper title and abstract.

### Through the River: Understanding the Benefit of Schedule-Free Methods for Language Model Training

**NeurIPS 2025 · Accept (poster)** · Minhak Song; Beomhan Baek; Kwangjun Ahn; Chulhee Yun

[OpenReview](<https://openreview.net/forum?id=CGx4XU9rCA>) · [Official program](<https://neurips.cc/virtual/2025/poster/119299>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/b94ab4933fea38629a1308fb78cce2cc-Paper-Conference.pdf>)

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

[OpenReview](<https://openreview.net/forum?id=853SwC2dMZ>) · [Official program](<https://neurips.cc/virtual/2025/poster/119655>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/f61d7778e89b9221d1ea0ce8428b7014-Paper-Conference.pdf>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T4 — Compute, data and model scaling laws; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/f61d7778e89b9221d1ea0ce8428b7014-Abstract-Conference.html>)

**Training dynamics relevance:** A compression-based syntax/knowledge model explains learning and scaling patterns from common to rare information.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Model/data size; knowledge frequency; fine-tuning.

**Training qualification:** Its Bayesian hierarchical data model is a conceptual theory rather than a literal implementation of LLM training.

**Evidence:** Official accepted-paper title and abstract.

### Understanding Outer Optimizers in Local SGD: Learning Rates, Momentum, and Acceleration

**NeurIPS 2025 · Accept (poster)** · Ahmed Khaled; Satyen Kale; Arthur Douillard; Chi Jin; Rob Fergus; Manzil Zaheer

[OpenReview](<https://openreview.net/forum?id=2VX79YLT9s>) · [Official program](<https://neurips.cc/virtual/2025/poster/120142>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/90ad0e850532986dff56da49bc599904-Paper-Conference.pdf>)

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

[OpenReview](<https://openreview.net/forum?id=QKo4c3LAz3>) · [Official program](<https://neurips.cc/virtual/2025/poster/118146>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/2e091b1c71ac0e4b4a4cc39ed3d64fcc-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T1 — Learning-rate selection, warm-up and schedules; T5 — Stability, curvature and edge-of-stability dynamics; T6 — Feature learning, implicit bias and generalization dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/2e091b1c71ac0e4b4a4cc39ed3d64fcc-Abstract-Conference.html>)

**Training dynamics relevance:** Studies how larger rates change kernel eigenvectors and alignment with the training target at the edge of stability.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Learning rate; NTK eigenvector alignment.

**Training qualification:** Theory uses a two-layer linear network; broader architectural evidence is empirical.

**Evidence:** Official accepted-paper title and abstract.

### Understanding the Generalization of Stochastic Gradient Adam in Learning Neural Networks

**NeurIPS 2025 · Accept (poster)** · Xuan Tang; Han Zhang; Yuan Cao; Difan Zou

[OpenReview](<https://openreview.net/forum?id=ETgPUJfQE1>) · [Official program](<https://neurips.cc/virtual/2025/poster/119131>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/1a54d9deffbb569151e8e4895f4ca162-Paper-Conference.pdf>)

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

[OpenReview](<https://openreview.net/forum?id=24wDPGiDzA>) · [Official program](<https://neurips.cc/virtual/2025/poster/120174>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/ddd7eae51dcd8bbfc936e5b19433d339-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T4 — Compute, data and model scaling laws; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/ddd7eae51dcd8bbfc936e5b19433d339-Abstract-Conference.html>)

**Training dynamics relevance:** Proposes unified/composable scaling laws for compressed representations and identifies failure conditions.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Sparsity; quantization type; effective model size.

**Training qualification:** Compression efficiency depends on the representation assumptions and regimes where the law remains valid.

**Evidence:** Official accepted-paper title and abstract.

### Unveiling m-Sharpness Through the Structure of Stochastic Gradient Noise

**NeurIPS 2025 · Accept (poster)** · Haocheng Luo; Mehrtash Harandi; Dinh Phung; Trung Le

[OpenReview](<https://openreview.net/forum?id=rMptAK0Xm8>) · [Official program](<https://neurips.cc/virtual/2025/poster/115785>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/623a1a9205ba93c5fbb8686df4256223-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T2 — Batch size, gradient noise and training efficiency; T5 — Stability, curvature and edge-of-stability dynamics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/623a1a9205ba93c5fbb8686df4256223-Abstract-Conference.html>)

**Training dynamics relevance:** Explains microbatch-dependent sharpness regularization with an SDE model and motivates reweighted SAM.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** SAM microbatch size; gradient-noise structure.

**Training qualification:** The approximation and empirical effects concern the analyzed SAM variants.

**Evidence:** Official accepted-paper title and abstract.

### Variational Learning Finds Flatter Solutions at the Edge of Stability

**NeurIPS 2025 · Accept (spotlight)** · Avrajit Ghosh; Bai Cong; Rio Yokota; Saiprasad Ravishankar; Rongrong Wang; Molei Tao; Mohammad Emtiyaz Khan; Thomas Möllenhoff

[OpenReview](<https://openreview.net/forum?id=nIFFMrDQ5w>) · [Official program](<https://neurips.cc/virtual/2025/poster/116148>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/6b61c278e483954fee502b49fe71cd14-Paper-Conference.pdf>)

**Categories:** H — Learning rates, batch sizes, parameterization, and plasticity; T5 — Stability, curvature and edge-of-stability dynamics; T7 — Initialization, normalization, weight decay and regularization.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/6b61c278e483954fee502b49fe71cd14-Abstract-Conference.html>)

**Training dynamics relevance:** Extends edge-of-stability analysis to variational learning and relates posterior choices to flatter solutions.

**Training study context:** Other deep learning.

**Hyperparameters / scaling axes:** Posterior shape; posterior sample count; learning rate.

**Training qualification:** The core derivation begins with quadratic problems and is empirically extended to deep networks.

**Evidence:** Official accepted-paper title and abstract.

### Zero-Shot Performance Prediction for Probabilistic Scaling Laws

**NeurIPS 2025 · Accept (poster)** · Viktoria Schram; Markus Hiller; Daniel Beck; Trevor Cohn

[OpenReview](<https://openreview.net/forum?id=paiyYD81Wr>) · [Official program](<https://neurips.cc/virtual/2025/poster/115947>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/072769405a3c1b60171d09c0ade96ebf-Paper-Conference.pdf>)

**Categories:** T4 — Compute, data and model scaling laws.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/072769405a3c1b60171d09c0ade96ebf-Abstract-Conference.html>)

**Training dynamics relevance:** Uses multi-output Gaussian processes for probabilistic, low-cost scaling and learning-curve prediction.

**Training study context:** LLM training.

**Hyperparameters / scaling axes:** Learning-curve query budget; model scale; task correlations.

**Training qualification:** Validation is small-scale; uncertainty calibration at frontier scales is not established.

**Evidence:** Official accepted-paper title and abstract.

### Zeroth-Order Optimization Finds Flat Minima

**NeurIPS 2025 · Accept (poster)** · Liang Zhang; Bingcong Li; Kiran Thekumparampil; Sewoong Oh; Michael Muehlebach; Niao He

[OpenReview](<https://openreview.net/forum?id=iXy0ncNepZ>) · [Official program](<https://neurips.cc/virtual/2025/poster/116554>) · [PDF](<https://proceedings.neurips.cc/paper_files/paper/2025/file/ebc62a3af9342eb4ebc728e5c5bc4cca-Paper-Conference.pdf>)

**Categories:** G — Optimizer theory, benchmarks, and training dynamics; T6 — Feature learning, implicit bias and generalization dynamics; T8 — Optimizer dynamics, comparisons and diagnostics.

[Accepted proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/hash/ebc62a3af9342eb4ebc728e5c5bc4cca-Abstract-Conference.html>)

**Optimizer relevance:** Studies the flat-minimum bias of two-point zeroth-order optimization and supports the analysis with language-model fine-tuning experiments.

**Training dynamics relevance:** Studies the flat-minimum bias of two-point zeroth-order optimization and supports the analysis with language-model fine-tuning experiments.

**Training study context:** Theory / controlled models.

**Hyperparameters / scaling axes:** Zeroth-order estimator; implicit Hessian-trace bias.

**Training qualification:** Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions.

**Evidence:** Official accepted-paper title and abstract.
