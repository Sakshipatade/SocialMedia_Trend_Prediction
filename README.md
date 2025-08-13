# SocialMedia_Trend_Prediction

This project predicts whether a social media hashtag will become trending based on:
- Daily mentions
- 7-day growth rate (%)
- Engagement rate
- Verified user ratio

Dataset: https://raw.githubusercontent.com/Sakshipatade/SocialMedia_Trend_Prediction/refs/heads/main/trendcast_mini.csv

## Model
- **Algorithm:** RandomForestClassifier
- **Accuracy:** ~90% on test set

## Usage
1. Open `jupyter.ipynb` in Google Colab.
2. Upload the dataset to Colab.
3. Run all cells to train the model and predict new hashtags

## Example Output
Hashtag #1 → Not Trending
Hashtag #2 → Trending
Hashtag #3 → Not Trending
We need to provide hashtag value like(4000, 2000, 6000)
