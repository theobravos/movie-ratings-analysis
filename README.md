# movie-ratings-analysis

# Movie Ratings Analysis (DSO 510 Final Project)

This repository contains all files for the USC DSO 510 final project, where we:

- Explored and cleaned movie rating data  
- Performed descriptive analysis (missing values, summary stats) in Jupyter  
- Built regression models to predict movie ratings  
- Compiled a final report with methodology and results

## Folder Structure

- **docs/**  
  - `510 Final Project.pdf`  
    The final written report detailing objectives, methods, and conclusions.

- **notebooks/**  
  - `510_Project.ipynb`  
    End-to-end notebook tying together data cleansing, exploratory analysis, and regression modeling.  
  - `Descriptive.ipynb`  
    Notebook containing exploratory data analysis and missing-value checks.  
  - `Regression.ipynb`  
    Notebook with regression model training and evaluation.

- **data/**  
  - `Movie_data.csv`  
    Raw dataset of movies and features.  
  - `clean_movie_rating.csv`  
    Cleaned, preprocessed version of the data for modeling.

## Getting the Data

The full datasets (CSV/TSV) are too large to store directly in Git. Please download them from Dropbox and place each into the `data/` folder before running the notebooks:

**Dropbox link:**  
[Download raw data files from Dropbox](https://www.dropbox.com/scl/fo/he12bk66s01ig44k7g0j8/AMaIocGZnBrWOvke90aaIAk?rlkey=wlkukg7tl5uly21s2uaq3wj57&st=8v57zaxv&dl=0)

After clicking that link, you’ll see your Dropbox folder with the following files:

- `Movie_data.csv`  
- `clean_movie_rating.csv`  
- `title.ratings.tsv`  
- `TMDB_movie_dataset_v11 (1).csv`  

**Steps to place them locally:**

1. Create (or confirm you already have) the `data/` folder at the repo root:
   ```bash
   cd movie-ratings-analysis
   mkdir -p data

## How to Run

1. **Clone the repo**  
   ```bash
   git clone https://github.com/theobravos/movie-ratings-analysis.git
   cd movie-ratings-analysis