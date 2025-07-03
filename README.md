# predicting-article-popularity
# Predicting Article Popularity in Online News Media Using Machine Learning

This project explores machine learning models to predict the popularity of online news articles. Using a real-world dataset, the goal is to understand what makes an article go viral, forecast share counts, and classify articles as 'popular' or 'non-popular'.

## 📊 Project Overview

This is a solo, self-initiated project undertaken to deepen my understanding of machine learning, particularly in the areas of regression, classification, and model interpretation.

I wanted to challenge myself with a real-world dataset that involved text-related features, social media dynamics, and the need for both predictive accuracy and actionable insights. The domain of online content popularity was a natural fit, combining data science with an everyday application.

Through this project, I gained hands-on experience with:
- Data preprocessing and feature engineering
- Ensemble learning techniques (Random Forest, GBM, Bagging)
- Model evaluation metrics like RMSE, RMSPE, AUC, and F1 Score
- Feature importance analysis and extracting insights for real-world decision-making

## 🗃️ Dataset

- **Source**: UCI Machine Learning Repository – Online News Popularity Dataset
- **Instances**: 39,644 articles
- **Features**: 61 attributes (e.g., word counts, sentiment, keywords, publishing weekday, etc.)

## ⚙️ Models Used

### Regression
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Machine (GBM)
- Bagging Regressor

**Best Model**: GBM  
**Best RMSPE**: 11137.50

### Classification
- Bagging using Random Forest
- Random Forest Classifier

**Best Model**: Random Forest  
**Best AUC**: 0.692  
**Accuracy**: 79%

## 🔍 Feature Insights

- Articles with well-chosen average and niche keywords tend to perform better.
- Internal linking to previously successful articles correlates with higher shares.
- Certain topic combinations (from LDA analysis) are strong predictors of popularity.
- Sentiment polarity and article length also play an important role.

## 💡 Key Learnings

- The importance of bootstrapping and hyperparameter tuning in ensemble methods.
- How to evaluate classification and regression models in the context of imbalanced and noisy data.
- Extracting feature importance to generate actionable business insights from predictive models.

## 🔧 Tech Stack

- Python (Pandas, Scikit-learn, Matplotlib)
- Jupyter Notebooks
- Machine Learning: Regression, Classification, Ensemble Models

## 📁 Project Structure

