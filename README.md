# STAT 159 / 259 — Lab 11: Urban Green Space Across Cities

This repository is for UC Berkeley STAT 159/259 Lab 11. Our dataset is the [September 22, 2026 TidyTuesday urban green space dataset](https://github.com/rfordatascience/tidytuesday/tree/main/data/2026/2026-09-22).

## Author

**Zhecen Zhou**

UC Berkeley — STAT 159/259

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

## Research Question

Which city has the most green area per capita in each year?

## Analysis Workflow

1. Load and explore the TidyTuesday dataset.
2. Check data quality and handle missing values.
3. Identify the city with the highest green area per capita for each year.
4. Visualize the results using Matplotlib.
5. Publish the analysis using MyST and GitHub Pages.
6. Present the findings using RevealJS.

## Structure
- `data/`: dataset source and access instructions
- `notebooks/`: individual analyses
- `slides/`: presentation files

## Project Components

- Data analysis: `notebooks/analysis_zhecen.ipynb`
- MyST website: `myst.yml`
- GitHub Pages deployment: `.github/workflows/deploy.yml`
- RevealJS presentation: `slides/presentation.md`

## Credits
Data: [UN-Habitat](https://data.unhabitat.org/pages/open-spaces-and-green-areas). TidyTuesday curation: Gabriela Palomo-Munoz.
