> The current NeurIPS subset contains **176 papers** after the learning-rate, scaling-law and training-dynamics extension (44 additional entries). The 132-paper counts below describe the original extension. [New topic guide](<../training_dynamics_survey/reading_guide.md>).

# NeurIPS 2025 extension

This extension adds **132 accepted main-track papers**: 74 optimizer papers, 26 manifold papers and 70 matrix/numerical-computation papers. Topic counts overlap. The manifold subset contains 14 direct algorithm/theory/application papers and 12 supporting geometric papers.

The combined project catalogue now contains **472 unique papers**. Open [the NeurIPS view](<../paper_catalogue/index.html?venue=NeurIPS%202025>), [Markdown](<catalogue.md>), [CSV](<catalogue.csv>) or [JSON](<catalogue.json>). The browser link opens the hosted catalogue.

## Source and selection

The saved [official program feed](<https://neurips.cc/static/virtual/data/neurips-2025-orals-posters.json>) contains 6,002 event records. On 2026-09-24, filtering to the exact `NeurIPS.cc/2025/Conference` source, accepted decisions and canonical poster records yields **5,287 unique main-track papers**. Their decisions retain oral/spotlight/poster distinctions. This removes duplicated oral events, the duplicate Mexico presentation listings, datasets/benchmarks and position tracks, and journal presentations. The number describes this available program snapshot, rather than every historical acceptance before withdrawals or program changes.

`screen_program.py` searches all accepted titles and abstracts using optimizer, geometry and numerical-computation patterns, plus a broader title pass. It produces 292 candidates. Curated annotations are based on manual reading of the selected abstracts, with six targeted full-text checks. This is a broad, reproducible curated selection, not a certified exhaustive review of every paper’s full text. Unselected candidates have not all been adjudicated irrelevant.

All 132 entries have an accepted main-track program record. An additional match against the [official proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/vol38-main-conference>) verifies 131 entries. Two title changes were matched by author list and subject:

- “Understanding outer learning rates in Local SGD” → “Understanding Outer Optimizers in Local SGD: Learning Rates, Momentum, and Acceleration”.
- “Tensor Decomposition Networks for Accelerating Machine Learning Force Field Computations” → “Tensor Decomposition Networks for Fast Machine Learning Interatomic Potential Computations”.

The index displays the proceedings titles and keeps the program titles searchable. “How to Scale Second-Order Optimization” is verified through its official program record and OpenReview paper; an exact proceedings-index match was not located. It is not silently assigned another paper’s proceedings URL.

## Useful starting points

- **KFAC/EKFAC:** ASTRA uses EKFAC-preconditioned stochastic Neumann iterations for data attribution. Its practical inverse-curvature target uses damped generalized Gauss–Newton curvature.
- **Optimizers:** Purifying Shampoo, SPlus, SUMO, ASGO, SinkGD, KOALA++, SubTrack++ and How to Scale Second-Order Optimization.
- **Manifold optimization:** StelLA, SubTrack++, PoLAR, adaptive fixed-rank Riemannian methods, quotient natural-gradient learning and general Riemannian bilevel/nonsmooth algorithms.
- **Matrix computation:** CDFlow, Halley-SVD, Spectral Estimation with Free Decompression, in-place FFT training, FlashBias, Tiled Flash Linear Attention, sketched GP solves and low-rank inverse perturbation theory.

These are reading suggestions, not independent validation of the numerical or empirical claims. Each catalogue entry supplies its official program/OpenReview links, and proceedings/PDF links where matched. Full-text checks are explicitly limited to the passages recorded in `fulltext_checks.json`.

## Reproduction

From the project root:

```sh
python3 neurips2025_survey/screen_program.py
python3 neurips2025_survey/curate_selection.py
python3 neurips2025_survey/match_proceedings.py
python3 paper_catalogue/build_catalogue.py
```

The scripts use the saved public sources and Python’s standard library. `curate_selection.py` is the editorial source for `selection.json`; classifications are not inferred automatically from keyword hits. `discovery_index.csv` records candidates and selection flags. `fulltext/` contains locally retrieved primary-paper PDFs and extracted text used for targeted checks. Earlier ICML/ICLR source snapshots and membership are preserved.
