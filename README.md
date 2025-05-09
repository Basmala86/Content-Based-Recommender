# Content-Based News Recommendation System

This project recommends news articles to users based on the similarity between article content and user preferences.

## Structure

- `data/`: Contains `news.csv`.
- `notebooks/`: Jupyter Notebooks for each project stage.
- `results/`: Outputs and visualizations.

## How to Run

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run notebooks in order:
- 01_data_preprocessing
- 02_user_profile_construction
- 03_content_similarity
- 04_ranking_and_recommendation

## Dataset

Download and extract the [MIND dataset](https://www.kaggle.com/datasets/arashnic/mind-news-dataset/data) into the `data/` folder.
