# IMDB_Movie-Data-Analysis


An exploratory data analysis (EDA) project on the IMDb Movie Data dataset, using pandas, seaborn, and matplotlib to clean the data and uncover trends in ratings, revenue, votes, and runtime.

## Project Structure
```
imdb-movie-data-analysis/
│
├── README.md
├── imdb_movie_analysis.ipynb
├── imdb_movie_data.csv
└── images/
    └── charts.png
```

## Dataset
`imdb_movie_data.csv` — contains movie titles, year, genre, director, runtime, rating, votes, and revenue.

## What This Project Covers

**Data Cleaning**
- Inspecting shape, columns, and data types
- Checking and visualizing missing values (`seaborn` heatmap)
- Removing rows with missing data
- Checking for duplicate records

**Exploratory Analysis**
- Summary statistics (`describe()`)
- Maximum revenue and revenue distribution
- Movies with a runtime of 180+ minutes
- Average votes per year
- Average revenue per year
- Average rating by director
- Top 10 longest-running movies
- Number of movies released per year
- Top 10 highest-rated movies (with director)
- Relationship between rating and revenue (scatter plot)
- Custom rating categories (`excellent`, `good`, `average`) based on score thresholds

## Visualizations
Includes bar plots, count plots, a scatter plot, and a missing-data heatmap, built with `seaborn` and `matplotlib`. Saved chart images are in the `images/` folder.

## How to Run

1. Clone or download this repository
2. Make sure `imdb_movie_data.csv` is in the same folder as the notebook
3. Open `imdb_movie_analysis.ipynb` in Jupyter Notebook or JupyterLab
4. Run the cells in order

```bash
git clone <your-repo-url>
cd imdb-movie-data-analysis
jupyter notebook imdb_movie_analysis.ipynb
```

## Requirements
- Python 3
- pandas
- numpy
- matplotlib
- seaborn

Install with:
```bash
pip install pandas numpy matplotlib seaborn
```

## Author
Muhammad Touseef Ahmad
