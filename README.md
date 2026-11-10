# OTT Content Analytics and Recommendation System Using Python

## Project Overview

The **OTT Content Analytics and Recommendation System** is a Python-based data analytics and machine learning project designed to analyze content across OTT platforms such as Netflix, Amazon Prime Video, and Disney+ Hotstar.

The project focuses on identifying content trends, analyzing genre distribution, comparing platform ratings, and understanding viewer preferences. It also implements a content-based recommendation system using TF-IDF and Cosine Similarity to recommend similar movies and TV shows.

Additionally, Random Forest Classification is used for popularity prediction, and TextBlob is explored for sentiment analysis.

## Objectives

- Analyze OTT content across multiple streaming platforms.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Identify genre-wise and platform-wise content trends.
- Visualize ratings and release-year distributions.
- Develop a content-based recommendation system.
- Predict content popularity using machine learning.
- Perform sentiment analysis on textual data.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning |
| TF-IDF | Text feature extraction |
| Cosine Similarity | Content recommendation |
| Random Forest | Popularity classification |
| TextBlob | Sentiment analysis |
| Jupyter Notebook | Development environment |

## System Workflow

```text
Dataset Collection
       |
       ▼
Data Cleaning
       |
       ▼
Exploratory Data Analysis
       |
       ▼
Feature Engineering
       |
       ▼
Machine Learning
       |
       ▼
Recommendation System
       |
       ▼
Visualization & Results
```

## Key Features

**1. Data Preprocessing**
- Handling missing values.
- Removing duplicate records.
- Standardizing categorical values.
- Converting data types.

**2. Exploratory Data Analysis**
- Genre distribution analysis.
- Platform-wise content comparison.
- Rating analysis.
- Release-year trend analysis.
- Correlation analysis.

**3. Recommendation System**

Uses TF-IDF Vectorization and Cosine Similarity to identify and recommend movies and TV shows based on their descriptions.

**4. Popularity Prediction**

Uses a Random Forest Classifier to categorize OTT content into high-popularity and low-popularity classes.

**5. Sentiment Analysis**

Uses TextBlob to classify textual data into positive, negative, and neutral sentiments.

## Project Structure

```text
OTT-Content-Analytics/
│
├── dataset/
│   └── ott_dataset.csv
│
├── notebooks/
│   └── OTT_Content_Analysis.ipynb
│
├── visualizations/
│
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation and Execution

**1. Clone the repository**

```bash
git clone https://github.com/ayyappa-05/OTT-Content-Analytics.git
```

**2. Navigate to the project directory**

```bash
cd OTT-Content-Analytics
```

**3. Install dependencies**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn textblob nltk jupyter
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

Open the project notebook and execute the cells.

## Expected Outputs

- Genre distribution visualizations.
- Platform-wise content analysis.
- Rating distribution charts.
- Release-year trend analysis.
- Similar movie and TV show recommendations.
- Popularity classification results.
- Sentiment analysis results.

## Future Enhancements

- Develop an interactive dashboard using Streamlit.
- Implement collaborative filtering.
- Integrate real-time OTT datasets.
- Improve recommendation accuracy.
- Enhance sentiment analysis using advanced NLP techniques.

## Author

**Chirumamilla Manikanta**

B.Tech – Information Technology  
Vasireddy Venkatadri Institute of Technology

GitHub: [ayyappa-05](https://github.com/ayyappa-05)

LinkedIn: [Chirumamilla Manikanta](https://www.linkedin.com/in/chirumamilla-manikanta-006292336/)
