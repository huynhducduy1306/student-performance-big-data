# Predicting Student Academic Performance Using Big Data Analytics

This research presents a scalable Big Data framework for predicting student academic performance
using machine learning models implemented with Apache Spark.

## Abstract
This study evaluates multiple supervised learning algorithms—including Logistic Regression,
Random Forest, and Gradient Boosting—on the UCI Student Performance dataset.
Experimental results indicate that Gradient Boosting achieves the highest predictive performance,
with strong ROC-AUC and F1-score metrics.

## Methods & Technologies
- Apache Spark (MLlib)
- Logistic Regression
- Random Forest
- Gradient Boosting
- Feature Engineering & One-Hot Encoding
- Cross-Validation
- ROC-AUC, Precision, Recall, F1-score

## Dataset
- UCI Machine Learning Repository – Student Performance Dataset

## Results
- Gradient Boosting achieved the best overall performance
- ROC-AUC: 0.92
- Key predictive features: past failures, early grades (G1, G2)

## Paper
📄 **[Read the full paper (PDF)](Predicting_Student_Academic_Performance.pdf)**

## Author
**Duc Duy Huynh**  
Department of Applied Computing  
College of Business and Technology  
Lander University  

## Future Work
- Integrate larger, multi-institutional datasets
- Explore deep learning models
- Investigate fairness and bias in prediction models
- Develop a real-time analytics dashboard
