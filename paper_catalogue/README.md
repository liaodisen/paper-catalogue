# All Papers

**598 curated papers**: 189 ICLR 2026, 233 ICML 2026, 176 NeurIPS 2025. Any conference, journal, workshop, preprint source or year is eligible. The initial three-conference collection is retained; 0 additional records have been added through the open-venue input.

Open [the searchable index](<index.html>). Reading guides: [learning rates, scaling laws and training dynamics](<../training_dynamics_survey/reading_guide.md>) · [matrix computation](<reading_guide.md>). The HTML works offline; external paper links require internet. This copy is packaged for static hosting.

| Venue | Unique papers | Optimizers | Manifolds | Matrix / numerics | Training dynamics |
|---|---:|---:|---:|---:|---:|
| ICLR 2026 | 189 | 121 | 28 | 51 | 69 |
| ICML 2026 | 233 | 147 | 33 | 65 | 75 |
| NeurIPS 2025 | 176 | 112 | 26 | 70 | 64 |
| **Total** | **598** | **380** | **87** | **186** | **208** |

Topic counts overlap. Training categories T1–T8 cover learning rates and schedules; batch size and noise; hyperparameter transfer; scaling laws; stability; feature learning and implicit bias; initialization and regularization; and optimizer dynamics. Each training entry records study context, hyperparameters, reported finding and qualification.

## Add or update papers

See [the update guide](<update_guide.html>). Add new records to `paper_catalogue/additional_papers.json`; any venue and year are supported. Optional source-provided citations go in `paper_catalogue/citation_overrides.json`. Preview with `python3 publish.py --prepare-only`, then publish with `python3 publish.py "Describe the update"`. Each paper has a Copy BibTeX button.

## Files

- Unified: [MD](<catalogue.md>) · [CSV](<catalogue.csv>) · [JSON](<catalogue.json>) · [BIB](<catalogue.bib>)
- Learning rates / scaling / dynamics: [Markdown](<../training_dynamics_survey/catalogue.md>) · [CSV](<../training_dynamics_survey/catalogue.csv>) · [reading guide](<../training_dynamics_survey/reading_guide.md>) · [method notes](<../training_dynamics_survey/README.md>)
- Optimizers: [Markdown](<optimizer_catalogue.md>) · [CSV](<optimizer_catalogue.csv>)
- Manifolds: [Markdown](<manifold_catalogue.md>) · [CSV](<manifold_catalogue.csv>)
- Matrix computation: [Markdown](<../matrix_computation_survey/matrix_catalogue.md>) · [CSV](<../matrix_computation_survey/matrix_catalogue.csv>)
- NeurIPS 2025: [Markdown](<../neurips2025_survey/catalogue.md>) · [CSV](<../neurips2025_survey/catalogue.csv>) · [original extension notes](<../neurips2025_survey/README.md>)
- Full accepted-program screening universe: 16,981 entries in [CSV](<accepted_program_index.csv>). Inclusion is not a topical-relevance endorsement.
- The earlier two-venue optimizer and manifold files in `optimization_2026_catalogs/` remain historical snapshots.

## Evidence and coverage

Updated **2026-09-24**. The accepted-program snapshots contain 6,341 ICML 2026 and 5,353 ICLR 2026 entries (2026-09-23), plus 5,287 NeurIPS 2025 entries (2026-09-24). Duplicate presentation events were removed in that historical scan. Its three-venue scope does not restrict future additions.

The new topic pass screened all 16,981 titles/abstracts and produced 1,253 broad candidates. New annotations summarize selected accepted abstracts; existing annotations and targeted passage checks are retained. This is **not an exhaustive full-text systematic review**. 26 entries have targeted full-text checks, labeled individually. Results are author-reported and code links were not tested.

The initial NeurIPS collection contains 176 program-confirmed papers; 174 are also matched to the proceedings index. Two revised proceedings titles retain their program titles as aliases. Additional records have their own source and publication-status fields.

Sources: [ICML program](<https://icml.cc/virtual/2026/papers.html>), [ICLR program](<https://iclr.cc/virtual/2026/papers.html>), [NeurIPS program](<https://neurips.cc/virtual/2025/papers.html>), [NeurIPS proceedings](<https://proceedings.neurips.cc/paper_files/paper/2025/vol38-main-conference>). Counts, snapshot dates and input hashes: [metadata.json](<metadata.json>).

## Rebuilding

Run `python3 paper_catalogue/build_catalogue.py` from the project root. It uses the Python standard library and rebuilds HTML, Markdown, CSV, JSON, BibTeX, topic subsets and documentation from saved sources.

For training selections, edit and run `training_dynamics_survey/curate.py`; run `neurips2025_survey/match_proceedings.py` before the catalogue builder to update proceedings matches. `training_dynamics_survey/screen.py` reproduces the broad search. The original NeurIPS selections are authored in `neurips2025_survey/curate_selection.py`, matrix selections in `matrix_computation_survey/selection.tsv`, and earlier optimizer/manifold notes in `optimization_2026_catalogs/`.

Edit `paper_catalogue/catalogue.template.html` for UI changes. Baseline assertions retain the 472 previous IDs. Every paper has an explicit publication year. Citations are generated conservatively from metadata or supplied through citation_overrides.json; all citation keys must be unique.
