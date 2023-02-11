# Flu-Shot-Learning-Predict-H1N1-and-Seasonal-Flu-Vaccines


![My Image](./Pictures/5.jpg")


## INTRODUCTION

Immunization is a global health and development success story, saving millions of lives every year. Vaccines reduce the risks of getting a disease by working with your body’s natural defenses to build protection.Vaccines are among the greatest advances in global health and development. For over two centuries, vaccines have safely reduced the scourge of diseases like polio, measles and smallpox, helping children grow up healthy and happy. 

## Business Problem
### Problem Statement
Vaccines provide immunization for individuals, and enough immunization in a community can further reduce the spread of diseases through "herd immunity."As of the launch of this competition, vaccines for the COVID-19 virus are still under development and not yet available. The competition will instead revisit the public health response to a different recent major respiratory disease pandemic. Beginning in spring 2009, a pandemic caused by the H1N1 influenza virus, colloquially named "swine flu," swept across the world. Researchers estimate that in the first year, it was responsible for between 151,000 to 575,000 deaths globally. A vaccine for the H1N1 flu virus became publicly available in October 2009. In late 2009 and early 2010, the United States conducted the National 2009 H1N1 Flu Survey. This phone survey asked respondents whether they had received the H1N1 and seasonal flu vaccines, in conjunction with questions about themselves. These additional questions covered their social, economic, and demographic background, opinions on risks of illness and vaccine effectiveness, and behaviors towards mitigating transmission. A better understanding of how these characteristics are associated with personal vaccination patterns can provide guidance for future public health efforts.

### The Main Objective
- Predict how likely individuals are to receive their *H1N1* and *Seasonal flu* vaccines.

## Performance Metric
Performance will be evaluated according to the area under the receiver operating characteristic curve (ROC AUC) for each of the two target variables. The mean of these two scores will be the overall score. A higher value indicates stronger performance.


## Data Understanding
###  Data Source
The dataset used for this project was obtained from  [Drivendata website link] (https://www.drivendata.org/competitions/66/flu-shot-learning/)

### Data Preparation and EDA
- Loading of the Data using pandas library.
- Checking the data types and descriptive Statistics.
- Cleaning the data i.e. filling in the missing value, dropping unimportant features, checking of outliers.
- Univariate & Bivariate Analysis was done.

## Models
The models used to make predictions:
1. Logistic Regression.
2. Random Forest Classifier.
3. Decision Tree Clasifier.
4. XGBoost.

**NB** - *Standardization was done to the models while XGBoost was tuned.*

## Conclusions
- From the models created, the Seasonal Vaccine has a higher ROC AUC score compared to the h1n1 Vaccine.
- The performance of the predictive model was evaluated using several metrics where the best model produced had an average of 0.83 - 0.84 ROC AUC score i.e Logistic Regression and XGBoost models.
- According to the age- groups, the older the person is, the more they are likely to be vaccinated than the young population.
- Different races preferred to be vaccinated than the rest in the sample population i.e the Whites had most of their sampled population vaccinated.  
  
> Disclaimer: :grin: Feel free to tweak around any of the hyper-parameter values or fiddle with the models. These were the best results that I could obtain with the models I chose.  
  
## Recommendations
- Increase awareness and education to different races, so that they can see the benefit of being vaccinated in their respective races.
- The young should be vaccinated more than the old population. Partnering with the schools and governments can be considered therefore enabling the young population to be vaccinated at an early age as they say *"Prevention is better than Cure".*


# Repository Guide

- [Data Source](https://www.drivendata.org/competitions/66/flu-shot-learning/)
- [Data Report](https://docs.google.com/document/d/1IsAMbMRF3ex9mt15ZLmPeyY5h7LPOaKoULn382l96hk/edit#heading=h.p63tlwpychqj)
- [Canva Presentation slides](https://www.canva.com/design/DAFaJ-RNvgQ/mYYf4H-1m1h9cXYl6nrs0A/edit#)
- [Notebook](https://github.com/Antony-Kimanthi/Flu-Shot-Learning-Predict-H1N1-and-Seasonal-Flu-Vaccines/blob/main/Notebook.ipynb)