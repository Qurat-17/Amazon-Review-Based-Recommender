<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/8ee313ae-ff03-489f-bb19-4bf85690f498" /># Amazon-Review-Based-Recommender
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Qurat-17/Amazon-Review-Based-Recommender/blob/main/Amazon_produdct_recom.ipynb)


## Project Overview

This project focuses on analyzing Amazon Electronics product reviews and preparing the data for building a recommendation system. The project was developed entirely in Google Colab and involves data acquisition, exploratory data analysis (EDA), and visualization of customer review patterns.

## Objectives

* Download the Amazon Electronics Review dataset directly into Google Colab.
* Perform data cleaning and exploratory data analysis.
* Analyze customer ratings and review distributions.
* Generate visual insights using graphs and charts.
* Prepare the dataset for developing a recommendation engine.

## Dataset Acquisition

The dataset was obtained from Kaggle using the Kaggle API.

### Steps Performed

1. Installed the required Python libraries.
2. Generated a Kaggle API key (`kaggle.json`).
3. Authenticated Kaggle inside Google Colab using the API credentials.
4. Downloaded the dataset directly into the Colab environment without using a local machine.

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Kaggle API

## Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset inspection and understanding.
* Handling missing values and checking data quality.
* Statistical summary of the dataset.
* Analysis of product ratings and review patterns.
* Visualization using bar charts and other graphical representations.

## Key Visualizations

* Rating distribution of products.
* Top 10 Items by Average Rating.
* Most reviewed product categories.
* Distribution of review scores.


Example:

![Rating Distribution](images/rating_distribution.png)

![Review Count](images/review_count.png)

## Project Workflow

```text
Install Libraries
        ↓
Authenticate Kaggle API
        ↓
Download Dataset in Google Colab
        ↓
Data Cleaning and Inspection
        ↓
Exploratory Data Analysis (EDA)
        ↓
Data Visualization
        ↓
Recommendation System Preparation
```

## Repository Structure

```text
MS-Recommender/
│
├── Amazon_Electronics_Recommendation.ipynb
├── README.md
├── images/
│   ├── rating_distribution.png
│   └── review_count.png
└── requirements.txt
```

## Future Work

* Build a recommendation engine using the review data.
* Implement collaborative filtering techniques.
* Experiment with content-based recommendation methods.
* Deploy the recommendation system as a web application.

## Author

**Qurat Ul Rashid**

Machine Learning and AI Enthusiast
