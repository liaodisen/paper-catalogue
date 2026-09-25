# Learning-rate, scaling-law and training-dynamics extension

Updated 2026-09-24. **208 papers**: 69 ICLR 2026, 75 ICML 2026, 64 NeurIPS 2025. **126 new papers** were added to the preceding 472-paper project catalogue; **82 existing papers** gained topic annotations. All previous entries are retained.

[Reading guide](<reading_guide.md>) · [Complete catalogue](<catalogue.md>) · [CSV](<catalogue.csv>) · [JSON](<catalogue.json>) · [Interactive index](<../paper_catalogue/index.html?theme=Training%20dynamics>)

## Search and inclusion

`screen.py` screens the saved official accepted title/abstract records for all 16,981 unique main-conference papers. This pass produced 1,253 broad lexical candidates; `discovery_index.csv` records these and any supplemental selections. Keyword hits are not relevance endorsements. New selections were made from titles and accepted abstracts. The 82 existing entries retain their earlier source-grounded notes. `selection.json` records category, study context, hyperparameters or scaling axes, the reported finding and its qualification. Categories T1–T8 overlap. Separate workshops and non-main-conference tracks are excluded.

The focus is optimization and training: learning-rate schedules, batch size, width/depth transfer, compute/data/model scaling, stability, feature learning, initialization, normalization, regularization and optimizer dynamics. Papers solely about inference-time scaling were not added unless they also inform training allocation or dynamics. Main study contexts separate LLM training, other deep learning, theory or controlled models, reinforcement learning and general optimization. An LLM label does not imply all theoretical claims were proved for LLMs or validated at frontier scale.

## Provenance and rebuilding

ICML and ICLR source snapshots are dated 2026-09-23; NeurIPS is dated 2026-09-24. These are the project's existing official accepted-program snapshots, not newly downloaded acceptance decisions. Each selected ID is joined to this universe and must have an acceptance decision. NeurIPS proceedings links are additionally matched where possible. Per-paper primary-source links and evidence levels are retained in every export. No new full-text-review claim is made for this extension.

Run `python3 training_dynamics_survey/screen.py`, `python3 training_dynamics_survey/curate.py`, `python3 neurips2025_survey/match_proceedings.py`, then `python3 paper_catalogue/build_catalogue.py` from the project root. All use saved local sources. `baseline_keys.json` records the 472 pre-extension IDs for new/existing accounting. The unified metadata records source hashes and category counts.
