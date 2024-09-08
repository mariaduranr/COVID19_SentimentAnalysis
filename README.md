# COVID-19 Sentiment Analysis

## Project Overview
This repository contains a comprehensive analysis of the emotional and mental health impacts due to the COVID-19 pandemic in two major cities: New York and Milan. The main objective of this project was to understand public perceptions and emotions through survey data and social media (Twitter) sentiment analysis. The project involved the following steps:
- Data cleaning and processing of two datasets (survey data and tweets).
- Sentiment analysis using Python libraries and a custom GPT assistant.
- Comparative analysis between the two datasets to examine emotional patterns and public sentiment.

## Project Structure
### 1. Jupyter Notebook (`covid_analysis.ipynb`)
   - This notebook contains all the data cleaning, processing, and analysis steps.
   - The datasets were prepared, missing values were handled, and sentiment analysis was performed using Python libraries such as `TextBlob` and `NLTK`.
   - Sentiment analysis was conducted on COVID-19-related tweets in USA, while the survey data provided insights into the mental health of residents from New York and Milan.
   - Visualizations such as bar charts and word clouds were generated to show emotional distributions and sentiment patterns.

### 2. Report (`covid_analysis_report.pdf`)
   - A detailed report documenting the entire project, including:
     - Background information about the datasets.
     - The methodology used for data cleaning and processing.
     - Sentiment analysis results and comparisons between New York and Milan.
     - Conclusions drawn from the analysis, including insights on the impact of co-habitation during lockdowns, employment stress, and mental health issues.
   - Potential areas for future research, such as expanding the datasets and enhancing the GPT model for more nuanced classification.

### 3. Custom GPT Assitant
   - A GPT-based assistant was created to perform sentiment analysis on COVID-19 tweets.
   - The assistant uses machine learning techniques to classify tweets into different emotions such as "peaceful," "stressed," "frustrated," and "vulnerable."
   - **Link to GPT Assitant for use**: (https://chatgpt.com/g/g-BYJwsjj6G-sentiment-analyst)
   - For more information on how to customize your own GPT go to https://help.openai.com/en/articles/8554397-creating-a-gpt

### 4. Video (`gpt_overview.mp4`)
   - A video overview of how the GPT model was developed and integrated into the analysis.

## Datasets
### Main Dataset (Survey Data) for Data Analysis
- **Source**: Harvard Dataverse
- **Content**: Survey responses from residents of New York and Milan regarding their perceptions and emotions during the pandemic.
- **Data Cleaning**: After cleaning, the dataset was reduced from 123 columns to 93 relevant columns for analysis.

### Secondary Dataset (COVID-19 Tweets) to perform sentiment Analysis using python libraries and a custom GPT assistant
- **Source**: Kaggle
- **Content**: Tweets related to the COVID-19 pandemic were collected using the Twitter API. Tweets mentioning keywords like "COVID-19" and "coronavirus" were analyzed.
- **Data Cleaning**: 37% of the data was excluded during cleaning to focus on tweets with meaningful sentiment information.

## Key Findings
- **Mental Health**: Co-habitation during lockdowns was linked to better mental health outcomes compared to living alone.
- **Public Sentiment**: Twitter analysis revealed a mix of positive and neutral sentiments, though this may be due to limitations in the data and sentiment analysis tools.
- **City Comparison**: Milan residents exhibited greater adaptability to the pandemic compared to New York residents.
- **Vaccine Reluctance**: Sentiments around vaccines were predominantly negative, with feelings of disappointment and hostility being most common.

## Future Work
- Expand the datasets to include more years and cities.
- Improve the GPT model for higher accuracy by integrating advanced language learning models.
- Perform deeper emotional analysis to capture subtle differences in sentiments across various demographics.

---

Feel free to explore the repository, and check out the GPT Sentiment Model for more insights into public emotions during the COVID-19 pandemic.

