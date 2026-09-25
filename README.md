# All Papers

**603 curated research papers**. Open to any venue, source or year, including journals, workshops and preprints.
Snapshot updated 2026-09-24.

[Open All Papers](paper_catalogue/index.html) ·
[Add & update papers](paper_catalogue/update_guide.html) ·
[Training reading guide](training_dynamics_survey/reading_guide.md) ·
[Matrix reading guide](paper_catalogue/reading_guide.md) ·
[CSV](paper_catalogue/catalogue.csv) · [BibTeX](paper_catalogue/catalogue.bib)

## Publishing

GitHub Pages publishes this repository's `main` branch from `/(root)`.
After committing generated changes, run `git push` to publish an update.
The `.nojekyll` file keeps the site static.

This is a static snapshot. Search, filters, paper notes and CSV export run in the
browser. Markdown files remain downloadable Markdown; the interactive site is
`paper_catalogue/index.html`.

The source scripts and research snapshots are kept in the local research project.
To rebuild, commit and push an update from the local project directory, run:

```sh
python3 publish.py "Update paper catalogue"
```

The publishing repository contains generated site files. Make permanent changes
in the original local project, then publish. The helper uses existing Git
authentication and contains no credentials.

Standard GitHub Pages sites are public. GitHub Free supports Pages from public
repositories. [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).
