# STAT 159 / 259 — Lab 11: Urban Green Space Across Cities

This repository is for UC Berkeley STAT 159/259 Lab 11. Our dataset is the [September 22, 2026 TidyTuesday urban green space dataset](https://github.com/rfordatascience/tidytuesday/tree/main/data/2026/2026-09-22).

## Team
- Zhecen Zhou
- Teammate: TBD

## Dataset
- **Topic:** Average share of green areas across cities
- **Source:** UN-Habitat Urban Indicators Database, curated by TidyTuesday
- **CSV:** [urban.csv](https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2026/2026-09-22/urban.csv)
- **Documentation:** [TidyTuesday README](https://github.com/rfordatascience/tidytuesday/blob/main/data/2026/2026-09-22/readme.md)

City-level measurements include green area per capita (square meters) and green area share (%) for 1990, 2000, 2010, 2020, and 2025. Urban areas here are defined using the Degree of Urbanization approach, which may differ from municipal boundaries.

## Questions provided by TidyTuesday
1. Which city has the most green area per capita in each year?
2. Which city has lost the largest percentage of its green area since 1990?
3. Which city has gained the largest percentage of green area since 1990?

**Tentative Part II split:**
- Zhecen: Question 1 — highest green area per capita in each year
- Teammate: Question 2 or 3 — change in green area since 1990

## Structure
- `data/`: dataset source and access instructions
- `notebooks/`: individual analyses
- `slides/`: presentation files

## Remaining Lab 11 tasks
1. Each teammate answers one question from the source README.
2. Build a MyST website.
3. Deploy to GitHub Pages with GitHub Actions (`myst init --gh-pages`).
4. Prepare RevealJS slides and present findings.

## Credits
Data: [UN-Habitat](https://data.unhabitat.org/pages/open-spaces-and-green-areas). TidyTuesday curation: Gabriela Palomo-Munoz.
