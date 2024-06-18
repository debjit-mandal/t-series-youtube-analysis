
# T-Series YouTube Channel Analysis

This repository contains an comprehensive analysis of the T-Series YouTube channel, the most popular YouTube channel in terms of views and subscribers. The analysis is performed on two datasets:

1. `all_stats_t_series.csv` - contains statistics of all videos on the T-Series channel.
2. `top_1000_details.csv` - contains details of the top 1000 videos by view count.

The analysis includes data cleaning, exploratory data analysis (EDA), visualization, sentiment analysis, and time series analysis.

## Repository Contents

- `advanced_t_series_analysis_with_insights.ipynb`: The Jupyter notebook performing the advanced analysis with detailed insights and conclusions.
- `all_stats_t_series.csv`: Dataset containing statistics for all videos on the T-Series channel.
- `top_1000_details.csv`: Dataset containing details of the top 1000 videos by view count.

## Key Insights

1. **Distribution of Views, Likes, and Comments**:
   - The majority of the videos have relatively low view counts, but there are some with exceptionally high views, indicating a few viral hits.
   - The distribution of likes and comments follows a similar pattern to views, with a few videos having extremely high engagement.

2. **Correlation Analysis**:
   - There is a strong positive correlation between views and likes, indicating that videos with higher views tend to receive more likes.
   - There is also a significant correlation between views and comments, suggesting that more popular videos generate more discussion.

3. **Top Videos**:
   - The top 10 videos by views, likes, and comments are dominated by popular songs and music videos, reflecting T-Series' primary focus on music content.
   - These videos feature popular Bollywood artists and have strong engagement, with millions of likes and thousands of comments.

4. **Sentiment Analysis**:
   - The sentiment of video descriptions tends to be positive or neutral, with very few negative sentiments.
   - This is expected as video descriptions are promotional in nature and aim to attract viewers.

5. **Time Series Analysis**:
   - The monthly average views show some seasonality and trends, with certain months experiencing higher view counts.
   - This could be attributed to the release of popular songs or festive seasons when people tend to consume more entertainment content.

## Conclusion

The T-Series YouTube channel's success is driven by a few key factors:
- **High Engagement**: Videos with high view counts also tend to receive a significant number of likes and comments, indicating strong audience engagement.
- **Popular Content**: Music videos and songs, especially those featuring well-known Bollywood artists, are the main drivers of high views and engagement.
- **Positive Sentiment**: The overall positive sentiment in video descriptions helps in promoting content effectively.
- **Seasonal Trends**: Understanding the seasonal trends in viewership can help in planning the release of new content to maximize views and engagement.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- seaborn
- matplotlib
- textblob

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/debjit-mandal/t-series-youtube-analysis.git
   cd t-series-youtube-analysis
   ```

2. Install the required packages:
   ```sh
   pip install pandas numpy seaborn matplotlib textblob
   ```

3. Open the Jupyter notebook:
   ```sh
   jupyter notebook advanced_t_series_analysis.ipynb
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The data used in this analysis was obtained from the T-Series YouTube channel.
- The dataset can be found in Kaggle: https://www.kaggle.com/datasets/vladimirmijatovic/t-series-indias-largest-music-record-label
- The analysis was performed using various Python libraries including pandas, numpy, seaborn, matplotlib, and textblob.

----------------------------------------------------------------

Feel free to suggest any kind of improvements.