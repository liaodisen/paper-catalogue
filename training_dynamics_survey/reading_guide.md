# Learning rates, scaling laws and training dynamics: reading guide

208 papers in the current training-dynamics collection. The paths below were drawn from the initial ICML 2026 / ICLR 2026 / NeurIPS 2025 collection. Updated 2026-09-24.

Start with the paths below. These 28 priorities reflect fit to the project, not a ranking of paper quality. New means absent from the preceding 472-paper catalogue. Links point to the accepted papers.

## What the filters mean

The study-context label identifies the main application or evidence setting; it is not a guarantee that every claim was validated on large models. For example, LLM papers may combine idealized analysis with experiments on particular model sizes. The qualification in each entry states the relevant boundary. Categories overlap.

| Category | Papers |
|---|---:|
| T1 — Learning-rate selection, warm-up and schedules | 75 |
| T2 — Batch size, gradient noise and training efficiency | 33 |
| T3 — Width/depth scaling and hyperparameter transfer | 36 |
| T4 — Compute, data and model scaling laws | 63 |
| T5 — Stability, curvature and edge-of-stability dynamics | 38 |
| T6 — Feature learning, implicit bias and generalization dynamics | 67 |
| T7 — Initialization, normalization, weight decay and regularization | 65 |
| T8 — Optimizer dynamics, comparisons and diagnostics | 46 |

## Transfer hyperparameters across scale

| Paper | Venue | Added | Main finding / question | Qualification |
|---|---|---|---|---|
| [Completed Hyperparameter Transfer across Modules, Width, Depth, Batch and Duration](<https://openreview.net/forum?id=elB9k4nTL1>) | ICLR 2026 | Existing | Studies hyperparameter transfer across width, depth, modules, batch size, and training duration, including Adam parameters and weight decay in LLM training. | Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions. |
| [Weight Decay may matter more than µP for Learning Rate Transfer in Practice](<https://openreview.net/forum?id=PvTxIdZc1E>) | ICLR 2026 | Existing | Empirically tests the roles of weight decay and maximal-update parameterization in learning-rate transfer across model widths. | Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions. |
| [How to Scale Second-Order Optimization](<https://openreview.net/forum?id=Ei6IsmxYrb>) | NeurIPS 2025 | Existing | Studies width/depth transfer of hyperparameters for Shampoo, SOAP and Muon, including blocking, grafting and weight decay in language-model training. | Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions. |
| [Don't be lazy: CompleteP enables compute-efficient deep transformers](<https://openreview.net/forum?id=lMU2kaMANl>) | NeurIPS 2025 | Existing | CompleteP develops depth/width parameterization rules for hyperparameter transfer in language-model training. | Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions. |
| [Scaling Diffusion Transformers Efficiently via $\mu$P](<https://openreview.net/forum?id=VfIOdGiBAv>) | NeurIPS 2025 | New | Extends maximal-update parameterization to diffusion Transformers and tests small-to-large hyperparameter transfer. | Architectural/objective conditions of the derivation matter; not every generative architecture is covered. |

## Choose learning rates, batch sizes and schedules

| Paper | Venue | Added | Main finding / question | Qualification |
|---|---|---|---|---|
| [Power Lines: Scaling laws for weight decay and batch size in LLM pre-training](<https://openreview.net/forum?id=bFXbLQzRoZ>) | NeurIPS 2025 | Existing | Analyzes joint batch-size and weight-decay scaling for language-model training; relevant to transferring optimizer settings across compute regimes. | Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions. |
| [Small Batch Size Training for Language Models: When Vanilla SGD Works, and Why Gradient Accumulation is Wasteful](<https://openreview.net/forum?id=52Ehpe0Lu5>) | NeurIPS 2025 | Existing | Examines small-batch language-model training and how Adam second-moment timescales should be measured in tokens; includes vanilla SGD comparisons. | Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions. |
| [Critical Batch Size Revisited: A Simple Empirical Approach to Large-Batch Language Model Training](<https://openreview.net/forum?id=XUKUx7Xu89>) | NeurIPS 2025 | Existing | Revisits critical batch size during language-model pretraining and motivates batch-size warmup from its changing training trajectory. | Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions. |
| [Fast Catch-Up, Late Switching: Optimal Batch Size Scheduling via Functional Scaling Laws](<https://openreview.net/forum?id=PXWgzUkVwo>) | ICLR 2026 | Existing | Uses functional scaling laws to derive batch-size schedules and explains late-switch fast catch-up; evaluates dense and MoE LLM pretraining. | Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions. |
| [Seesaw: Accelerating Training by Balancing Batch Size and Learning Rate Scheduling](<https://openreview.net/forum?id=Nj0XBF2o7z>) | ICLR 2026 | Existing | Seesaw couples batch-size ramp-up with learning-rate scheduling to preserve training dynamics and reduce serial steps in LM pretraining. | Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions. |
| [Scaling Law with Learning Rate Annealing](<https://openreview.net/forum?id=VBx4yMNtjt>) | NeurIPS 2025 | Existing | Models how learning-rate annealing changes language-model loss scaling, informing schedule and budget choices. | Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions. |
| [Functional Scaling Laws in Kernel Regression: Loss Dynamics and Learning Rate Schedules](<https://openreview.net/forum?id=dpllevHMbc>) | NeurIPS 2025 | Existing | Uses an intrinsic-time kernel-regression analysis to model full loss trajectories under learning-rate schedules, with LLM scaling experiments. | Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions. |
| [One LR Doesn’t Fit All: Heavy-Tail Guided Layerwise Learning Rates for LLMs](<https://openreview.net/forum?id=fs9KaJyhRO>) | ICML 2026 | Existing | Uses layer-wise heavy-tail spectral statistics to assign learning rates during LLM pretraining, including AdamW and Muon. | Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions. |
| [Rethinking Neural Network Learning Rates: A Stackelberg Perspective](<https://openreview.net/forum?id=TgohCXoblV>) | ICML 2026 | New | Interprets a faster final-layer learning rate through Stackelberg optimization and studies conditions for improved convergence. | Convergence results have stated problem assumptions; nonuniform rates are not always superior. |
| [Balancing Learning Rates Across Layers: Exact Two-Step Dynamics and Optimal Scaling in Linear Neural Networks](<https://openreview.net/forum?id=4vztmTrGhd>) | ICML 2026 | New | Derives one- and two-step linear-network dynamics showing when unequal layer rates help and when balanced rates become optimal. | The exact/surrogate results concern early steps of two- and three-layer linear networks. |

## Fit scaling laws and design data experiments

| Paper | Venue | Added | Main finding / question | Qualification |
|---|---|---|---|---|
| [Gemstones: A Model Suite for Multi-Faceted Scaling Laws](<https://openreview.net/forum?id=iZk78dZ1Ap>) | NeurIPS 2025 | New | Gemstones shows scaling prescriptions can depend strongly on architecture, hyperparameter choices and which checkpoints enter the fit. | A direct warning about experimental-design sensitivity; a fitted exponent is not recipe-independent. |
| [Predictable Scale (Part II) --- Farseer: A Refined Scaling Law in LLMs](<https://openreview.net/forum?id=2Gnp8sdwVe>) | NeurIPS 2025 | New | Farseer fits a refined loss surface to improve evaluation of training strategies and compute allocation across scales. | Prediction quality depends on the fitted model families and design of the scaling experiments. |
| [InfoLaw: Information Scaling Laws for Large Language Models with Quality-Weighted Mixture Data and Repetition](<https://openreview.net/forum?id=fQaVptMRCY>) | ICML 2026 | New | InfoLaw models information accumulation and diminishing returns from repeated data to predict loss under new training recipes. | Extrapolation is empirical within the evaluated families and repetition regimes. |
| [How Text Quality Interventions Reshape Neural Scaling Laws for LLMs: Empirical Study](<https://openreview.net/forum?id=ZC5QBfdOw7>) | ICLR 2026 | New | Shows that data-quality interventions can change scaling coefficients, exponents and compute-optimal data/model allocations. | Recipe rankings can reverse with scale; fitted laws should not be transferred blindly between corpora. |
| [Can Small Training Runs Reliably Guide Data Curation? Rethinking Proxy-Model Practice](<https://openreview.net/forum?id=2FZC0c06jP>) | ICLR 2026 | New | Shows small-model data rankings can flip with hyperparameters and studies reduced proxy rates as a more reliable comparison protocol. | A theoretical ordering result is for random-feature models; LLM reliability is empirically tested across recipes. |
| [How Learning Rate Decay Wastes Your Best Data in Curriculum-Based LLM Pretraining](<https://openreview.net/forum?id=T5wkZJqzkz>) | ICLR 2026 | Existing | Studies conflicts between learning-rate decay and data-quality curricula; tests moderate decay and checkpoint averaging in LLM pretraining. | Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions. |

## Understand initialization, stability and optimizer dynamics

| Paper | Venue | Added | Main finding / question | Qualification |
|---|---|---|---|---|
| [Two failure modes of deep transformers and how to avoid them: a unified theory of signal propagation at initialisation](<https://openreview.net/forum?id=utSqpxQHXq>) | ICLR 2026 | New | Derives Transformer trainability diagrams linking initialization to rank collapse, entropy collapse and vanishing gradients. | Signal-propagation theory at initialization is not a guarantee of the entire nonlinear training trajectory. |
| [Adaptive Preconditioners Trigger Loss Spikes in Adam](<https://openreview.net/forum?id=STWQoscanw>) | ICML 2026 | Existing | Explains Adam loss spikes through failure of the second-moment preconditioner to track instantaneous squared gradients; tests include large Transformers. | Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions. |
| [Momentum Further Constrains Sharpness at the Edge of Stochastic Stability](<https://openreview.net/forum?id=mL4i6z7Miy>) | ICML 2026 | Existing | Shows how batch size and momentum jointly determine stochastic stability thresholds and attained sharpness. | Reuses the earlier source-grounded annotation. Consult the linked paper for assumptions, tested scales and parameterization conventions. |
| [In Search of Adam’s Secret Sauce](<https://openreview.net/forum?id=CH72XyZs4y>) | NeurIPS 2025 | New | Compares carefully tuned Adam simplifications and explains why equal momentum parameters retain much of Adam's performance. | The equal-beta result is empirical over tested settings; the associated statistical interpretation has specified assumptions. |
| [Dropout Universality: Scaling Laws and Optimal Scheduling at the Edge-of-Chaos](<https://openreview.net/forum?id=FoDU47u2jk>) | ICML 2026 | New | Analyzes how dropout changes critical signal propagation and motivates front-loaded dropout schedules. | Mean-field critical exponents and the MLP/ViT experiments have different scopes; LLM transfer is not established. |
| [Training Dynamics Impact Post-Training Quantization Robustness](<https://openreview.net/forum?id=ZXr3Xx7Z1O>) | ICLR 2026 | New | Links post-training quantization degradation to the training recipe, especially learning-rate decay, through checkpoints and controlled runs. | Validation loss and quantization robustness are distinct objectives; the study does not imply data volume alone causes degradation. |
| [Data Mixing Can Induce Phase Transitions in Knowledge Acquisition](<https://openreview.net/forum?id=tQZK5frjVU>) | NeurIPS 2025 | New | Finds abrupt knowledge-acquisition transitions when dense knowledge data are mixed with web text. | The controlled biography study shows that mixture rankings can change with size; it is not a universal discontinuity claim. |

## Complete collection

[All 208 entries](<catalogue.md>) · [CSV](<catalogue.csv>) · [JSON](<catalogue.json>) · [Searchable index](<../paper_catalogue/index.html?theme=Training%20dynamics>)

Accepted status comes from the official program snapshots. Most notes summarize accepted abstracts; earlier targeted full-text checks remain labeled on individual records. This is a broad curated search, not an exhaustive full-text review. Reported improvements have not been independently reproduced.
