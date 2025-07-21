# Movie-Recommendation-System

## Required Python Packages

- numpy
- pandas
- scikit-learn
- surprise
- keras

## About the Dataset

https://www.kaggle.com/rounakbanik/movie-recommender-systems/data

The dataset consists of metadata for all 45,000 movies listed in the Full MovieLens Dataset. The dataset consists of movies released on or before July 2017. Data points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts, and vote averages.

### Dataset Files

- **movies_metadata.csv**: Main file. Includes info on 45,000 movies (posters, backdrops, revenue, release dates, etc.).
- **keywords.csv**: Movie plot keywords in a stringified JSON object.
- **credits.csv**: Cast and crew info in a stringified JSON object.
- **links.csv**: TMDB and IMDB IDs for all movies.
- **links_small.csv**: A small subset (9,000 movies) of the full dataset.
- **ratings_small.csv**: 100,000 ratings from 700 users on 9,000 movies.

---

## How to Run the Project

Make sure the dataset files and `code.ipynb` are in the same directory.

Then, open the Jupyter notebook and run the code:

```bash
jupyter notebook code.ipynb
