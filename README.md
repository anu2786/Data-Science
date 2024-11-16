# Data Science Portfolio

Welcome to my Data Science Portfolio! This repository contains various projects and assignments I have completed as part of my Master of Professional Studies in Data Science at the University of Auckland. Below, you'll find descriptions of each project along with links to the relevant files.

## Projects and Assignments

### 1. Auckland Weather Analysis
- **Description:** Analysis of Auckland Airport weather data, including temperature conversion, data quality assessment, average calculations, trend plotting, and precipitation evaluation using the Gamma distribution.
- **Files:**
  - [Auckland Weather Analysis1.html](Auckland%20Weather%20Analysis1.html)

### 2. Data Cleaning & Analysis
- **Description:** Cleaning and analyzing patient visit data using regular expressions in R. The project involves creating CSV files, computing visit statistics, and scheduling follow-up appointments.
- **Files:**
  - [Data Cleaning & Analysis.html](Data%20Cleaning%20%26%20Analysis.html)

### 3. Data Visualization
- **Description:** Advanced R programming and data visualization techniques, including the implementation of functions for Stirling numbers and parallel coordinates plots.
- **Files:**
  - [Data Visualization.html](Data%20Visualization.html)

### 4. Decision Tree Implementation and Analysis
- **Description:** Implementation and analysis of decision trees, including handling missing values, selecting hyperparameters, and performing significance tests on multiple datasets to evaluate model performance.
- **Files:**
  - [Decision Tree.html](Decision%20Tree.html)

### 5. Enhanced Naive Bayes for Yelp Data Classification
- **Description:** Improved Naive Bayes algorithm to classify Yelp points of interest into Restaurants, Shopping, and Nightlife categories. Includes model application to a test set, category prediction, and accuracy evaluation.
- **Files:**
  - [Enhanced Naive Bayes for Yelp Data Classification.html](Enhanced%20Naive%20Bayes%20for%20Yelp%20Data%20Classification.html)
  - [Enhanced Naive Bayes for Yelp Data Classification.ipynb](Enhanced%20Naive%20Bayes%20for%20Yelp%20Data%20Classification.ipynb)

### 6. Multiple Regression Models
- **Description:** Analysis of relationships between lake water phosphorus and various measurements using multiple linear regression, step-wise regression, and model selection techniques.
- **Files:**
  - [Multiple Regression Models.pdf](Multiple%20Regression%20Models.pdf)

### 7. PageRank Algorithm Implementation
- **Description:** Implementation of the PageRank algorithm in Python to rank web pages based on their link structure.
- **Files:**
  - [PageRank using python.html](PageRank%20using%20python.html)

### 8. Support Vector Machine (SVM) Implementation and Optimization
- **Description:** Design and training of SVMs on custom datasets, cross-validation, hyperparameter optimization, performance evaluation with different kernels and C values, and decision boundary plotting.
- **Files:**
  - [SVM.html](SVM.html)

### 9. Statistical Analysis and Hypothesis Testing
- **Description:** Conducted statistical analyses to estimate lottery ticket purchase proportions, compare tree growth across regions, determine clinical trial sample size, and investigate THC potency differences.
- **Files:**
  - [Statistical Analysis and Hypothesis Testing.pdf](Statistical%20Analysis%20and%20Hypothesis%20Testing.pdf)

### 10. Straight Line and Quadratic Regression Models
- **Description:** Generated scatterplots, fit straight-line and quadratic regression models, and performed variable transformations for slug lengths and weights.
- **Files:**
  - [Straight Line and Quadratic Regression Models.pdf](Straight%20Line%20and%20Quadratic%20Regression%20Models.pdf)

### 11. House Price Prediction Model
- **Description:** It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable.
- Model Used: GradientBoostingRegressor
- Accuracy obtained: 99%
- Platform: Kaggle
- **Files:**
- [House Price Prediction.ipynb ](https://github.com/anu2786/Data-Science/blob/ccb288d31e07e3d65f8bdc35a21c58dbfb68eab5/House%20Price%20Prediction.ipynb)


### 12. Titanic - Machine Learning from Disaster
- **Description:** Built a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).
- Model Used: RandomForestClassifier
- Prediction Score:  0.77511
- Platform: Kaggle
- **Files:**
[ Titanic.ipynb](https://github.com/anu2786/Data-Science/blob/bb2dae82e7f6994268fa4375ca515a14805e9bb0/Titanic.ipynb)


### 13. Sentiment Analysis on Movie Reviews
- **Description:** Classify the sentiment of sentences from the Rotten Tomatoes dataset. The dataset is comprised of tab-separated files with phrases from the Rotten Tomatoes dataset. The train/test split has been preserved for the purposes of benchmarking, but the sentences have been shuffled from their original order. Each Sentence has been parsed into many phrases by the Stanford parser. Each phrase has a PhraseId. Each sentence has a SentenceId. Phrases that are repeated (such as short/common words) are only included once in the data.

train.tsv contains the phrases and their associated sentiment labels. We have additionally provided a SentenceId so that you can track which phrases belong to a single sentence.
test.tsv contains just phrases. You must assign a sentiment label to each phrase.
The sentiment labels are:

0 - negative
1 - somewhat negative
2 - neutral
3 - somewhat positive
4 - positive
- Model Used: LogisticRegression
- Platform: Kaggle
- **Files:** https://github.com/anu2786/Data-Science/blob/1520df4f57ea15148e959a15e16204aed85f3de5/Logistic%20Reg%20sentim%20analysis%20(1).ipynb


### 14. Car Imports Analysis
- **Description:** Analyzed New Zealand car imports data by cleaning, transforming, and modeling the dataset to predict import values and explore country-wise patterns.
- Model Used: Simple Mean, Linear Regression
- Performance (RMSE): Mean Model: 6.257842, Linear Regression: 5.087111
- Tools Used: R, Base R Graphics
- Outcome: Demonstrated data processing, visualization, and model evaluation for effective insights.
- **Files** [https://github.com/anu2786/Data-Science/blob/cef4e66ca7e0aa6c485987c1930b38a4fffdaeb9/Lab-00-report.Rmd](https://github.com/anu2786/Data-Science/blob/cef4e66ca7e0aa6c485987c1930b38a4fffdaeb9/Lab-00-report.Rmd)


### 15. Vehicle Imports Analysis
- **Description:** Analyzed vehicle import data (HS codes 8703+) using Linux commands and R. Extracted and processed new car imports (select HS codes) from 2000–2021 and predicted import values over time.
- Shell Tools Used: grep, wc, awk, curl
- Models Used: Simple Mean, Linear Regression
- Performance (RMSE): Mean Model: 8.379609, Linear Regression: 11.52066
- Tools Used: Linux Shell, R, Base R Graphics
- Outcome: Developed Linux skills for processing large datasets and applied predictive modeling to study import trends.
- **Files** [Vehicle Imports Analysis.Rmd ](https://github.com/anu2786/Data-Science/blob/919090fed5c01d8333d87df61c645e2a8bc5d09e/Vehicle%20Imports%20Analysis.Rmd)


### 16. Currency Exchange Rate Analysis
- **Description:** Downloaded and analyzed historical Euro currency exchange rates via Frankfurter API. Conducted exploratory data analysis and modeled NZD exchange rates against AUD, GBP, and USD.
- Shell Tools Used: curl, Shell Scripting
- Models Used: Linear Regression for currency pair predictions
- Key Insights: Identified AUD as the currency behaving most similarly to NZD. USD model coefficients interpreted to show practical currency relationships.
- Tools Used: R, Base R Graphics, Frankfurter API, Shell
- Outcome: Demonstrated API interaction, structured data processing, exploratory data visualization, and predictive modeling with real-world currency data.
- **Files** https://github.com/anu2786/Data-Science/blob/614ea916f802d8ea657e805dec0ec7b7f382ac40/Currency%20Exchange%20Rate%20Analysis.Rmd


### 17. NYC Taxi Data Analysis 
- **Description:** Analyzed large NYC ride-sharing datasets to estimate data processing times, predict record counts, analyze monthly trip trends, and study vendor distribution changes over time.
- Shell Tools Used: bzip2, wc, sort, head, awk
- R Techniques: File size-based record prediction, RMSE computation, monthly trends plotting
- Key Insights:
Processing large datasets is computationally intensive but can be optimized with parallelization and efficient tools.
Monthly trip data shows significant variation, likely due to external factors like COVID-19.
Vendor distributions reflect industry dynamics over time.
- Outcome: Developed robust skills for handling and analyzing large-scale datasets efficiently using shell scripting and R.
- **Files** https://github.com/anu2786/Data-Science/blob/0003413517ec8718201841594885dfdbd2028c8d/NYC%20Taxi%20Data%20Analysis%20.Rmd


### 18. Exploratory and Large Data Analysis

- **Description:** Analyzed NYC HVFHV trip data (January–May 2024) to evaluate distributions, explore relationships between trip metrics, and fit a scalable regression model using chunk-wise processing for large data.
- Tools Used: R, Parquet Format, arrow::read_parquet(), iotools, biglm
- Tasks & Insights: Progressive chunk-wise processing using iotools and biglm. Coefficients stabilized with larger data, showing the scalability and robustness of chunk-wise modeling.
- Key Findings:
Scalability of Models: Large datasets require efficient processing techniques like chunk-wise analysis.
Driver Pay Factors: Trip length and time significantly influence pay; vendor-specific factors also contribute.
Final Model Interpretation: Coefficients for each variable provided actionable insights into pay dynamics.
- Outcome: Developed skills in analyzing large datasets, identifying meaningful patterns, and implementing scalable regression models. Efficient chunk-wise processing allowed fitting complex models with limited memory resources.
- **Files** https://github.com/anu2786/Data-Science/blob/c9cfcce1b39fb7a2888ca95ef364dd67a95f8976/Exploratory%20and%20Large%20Data%20Analysis.Rmd
