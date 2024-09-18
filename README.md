
# **Twitter Sentiment Analysis**

## **Overview**

This project analyzes and visualizes sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands. Using the Twitter Sentiment Analysis dataset, the goal is to uncover insights into how sentiment varies across different entities and overall sentiment distribution.

## **Methodology/Steps**

1. **Data Loading**: Load the dataset and assign column names.
2. **Data Cleaning**: Check for and handle missing values to ensure data quality.
3. **Sentiment Analysis**: Use NLTK’s VADER sentiment analyzer to compute sentiment scores for each tweet.
4. **Descriptive Statistics**: Calculate average sentiment scores and percentiles to understand sentiment distribution.
5. **Visualization**:
   - **Sentiment Distribution**: Create a histogram to visualize the distribution of sentiment scores.
   - **Sentiment by Entity**: Create a count plot to visualize sentiment distribution across different entities.

## **Requirements**

The following libraries are required to run the code:
- `pandas`
- `seaborn`
- `matplotlib`
- `nltk`


## **Exploratory Data Analysis (EDA)**

- **Missing Values**: Checked and handled missing values to ensure clean data.
- **Sentiment Analysis**: Applied NLTK’s VADER sentiment analyzer to compute sentiment scores for each tweet.
- **Percentiles and Average Sentiment**: Calculated to understand the overall sentiment distribution and the range of sentiment scores.

## **Results**

- **Average Sentiment Score**: Provides an overall sense of sentiment across the dataset.
- **Sentiment Score Percentiles**: Show the distribution and range of sentiment scores.
- **Distribution of Sentiment Scores**: A histogram visualizes how sentiment scores are distributed.
- **Sentiment by Entity**: A count plot shows the sentiment distribution across different entities or topics.

## **Conclusion**

The sentiment analysis provides insights into how different topics or brands are perceived on social media. 
The visualizations and statistics help in understanding the overall sentiment trends and the sentiments associated with various entities.

---
