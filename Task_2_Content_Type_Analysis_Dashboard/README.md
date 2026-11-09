# Task 2 (Easy) - Content Type Analysis Dashboard
**Auspify Technologies - Data Analysis Using Python Internship** | Intern: Akshit Kumar

**Description:** Analyze the distribution of Movies and TV Shows available on Netflix.

## Task workflow (from the official task list)
1. Load the cleaned dataset
2. Calculate the total number of Movies and TV Shows
3. Create visualizations for content distribution
4. Compare content proportions
5. Summarize key findings

The cleaned dataset from Task 1 is already included in `data/processed/`, so this project runs on its own.

## Folder structure
```
src/          Python source (task2_content_type_analysis.py + netflix_utils.py)
notebooks/    executed Jupyter notebook with outputs
data/         raw Dataset.csv and cleaned dataset
outputs/      charts, screenshots, dashboards, reports, metrics
run.py        run the task with one command
```

## How to run
```bash
pip install -r requirements.txt
python run.py
```
Or open `notebooks/task2_content_type_analysis.ipynb` in Jupyter (outputs are already saved).

---
## Results summary
# Task 2 – Content Type Analysis: Summary of Key Findings

| Type | Titles | Share |
|---|---|---|
| Movies | 6,123 | 69.7% |
| TV Shows | 2,663 | 30.3% |
| **Total** | **8,786** | 100% |

## Key findings
1. **Movies dominate the catalogue** – 6,123 movies vs 2,663 TV shows, a ratio of **2.3 movies for every TV show**.
2. **TV's share of additions is rising but still a minority.** TV shows were **21%** of additions in 2014,
   peaked at **41% in 2016**, dipped to about 25-30% in 2017-2019 and recovered to
   **34%** in the latest (partial) year. TV never exceeded half of a year's additions.
3. **Movies are standard length** – median runtime 98 minutes; only 19.5% run 2 hours or more.
4. **TV is mostly short-run** – 67.2% of series have a single season and only 17.0% have three or more,
   i.e. most series in the catalogue have not (yet) been renewed beyond their first run.
5. **Audience mix differs by type** – TV shows form 51% of Kids content but 29% of Adults content.
6. **Catalogue age** – the bulk of titles were released in the 2010s and 2020s; older decades are a small share (see decade chart).

## Visualizations produced
`outputs/charts/task2_01 … task2_06`, dashboard screenshot: `outputs/screenshots/task2_dashboard.png`.

*Note: the dataset ends in September 2021, so 2021 is a partial year.*

