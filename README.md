# Online News Article Popularity Prediction 📰🔮

A machine learning project in R to predict the popularity of online news articles using regression and classification models. 
Built to explore real-world ML workflows and gain hands-on experience with ensemble methods.

## 🚀 Goals
- Build regression models to predict the number of shares an article will receive using content-based features.
- Develop classification models to categorize articles as 'popular' or 'non-popular' based on a defined threshold.
- Explore and interpret feature importance to understand what textual, structural, and topical elements drive article popularity.

## 🧠 Models

- **Regression**: Linear Model, Random Forest, Gradient Boosting (GBM), Bagging  
  → GBM performed best, effectively capturing non-linear relationships and outperforming the linear baseline in predicting share counts.

- **Classification**: Random Forest, Bagging  
  → Random Forest achieved the best balance of accuracy and AUC, making it the most reliable for identifying popular vs. non-popular articles.

Models were evaluated using RMSPE for regression and accuracy, AUC, and F1 Score for classification. Ensemble methods showed clear advantages in both prediction accuracy and feature insight over simpler models.


## 📚 Libraries Used
**Data Manipulation & Cleaning**  
- dplyr  
- tidyr  
- skimr  

**Visualization**  
- ggplot2  
- ROCR  

**Modeling & Machine Learning**  
- caret  
- randomForest  
- gbm  
- rpart  
- ISLR  

**Evaluation & Metrics**  
- pROC  
- ROCR  

**Reporting**  
- knitr  

## 💡 What I Learned

- **Ensemble Modeling & Tuning**  
  Built and optimized models like Random Forest, Gradient Boosting (GBM), and Bagging. Learned how ensemble methods improve prediction by reducing overfitting and capturing complex patterns in the data.

- **Model Evaluation**  
  Used metrics like RMSPE, AUC, accuracy, and F1 Score to assess regression and classification models. Gained clarity on choosing the right metric based on task type and data distribution.

- **Feature Importance & Interpretation**  
  Identified key features influencing article popularity:
  - Keyword metrics 
  - Content length 
  - Self-referencing and internal links 
  - LDA topic probabilities
  - Sentiment polarity scores

- **Graphical & Statistical Analysis**  
  Visualized feature importance, share distributions, and correlation heatmaps. These helped uncover non-obvious patterns and improve model understanding. Also explored variable correlations to detect multicollinearity and guide feature selection.

- **Working with Real-World Data**  
  Gained hands-on experience in preprocessing, handling missing/skewed values, and transforming a continuous target into binary classes for classification. Practiced end-to-end ML workflow on a complex, high-dimensional dataset.

## 🗂️ Files
[📄Project Report](./Predicting_Article_Popularity_Abhinethra.html)

---
