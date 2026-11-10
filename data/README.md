# Dataset access

The dataset for Lab 11 is `urban.csv` from [TidyTuesday (2026-09-22)](https://github.com/rfordatascience/tidytuesday/tree/main/data/2026/2026-09-22).

Read it in Python:

```python
import pandas as pd
url = "https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2026/2026-09-22/urban.csv"
urban = pd.read_csv(url)
```

The remote source is used rather than duplicating the raw 6 MB dataset.
