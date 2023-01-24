
# Practical Application III: Comparing Classifiers

### Overview:
In this practical application, the goal is to compare the performance of the classifiers we encountered in this section, namely K Nearest Neighbor, Logistic Regression, Decision Trees, and Support Vector Machines.  We will utilize a dataset related to marketing bank products over the telephone.

### Data:
The dataset comes from the UCI Machine Learning repository [link](https://archive.ics.uci.edu/ml/datasets/bank+marketing). The data is from a Portuguese banking institution and is a collection of the results of multiple marketing campaigns.

### Deliverables:
Jupiter notebook [link](https://github.com/ivan-troy-2001/Comparing-Classifiers/blob/main/prompt_III.ipynb).

### Results

#### Model:
+ The bank campaign dataset presented an imbalanced target class, the issue was addressed by down sampling the majority class.
+ Balancing the target class helped to improve the accuracy since some models performed poorly by falling to classify the minority class.
+ During improvement phase, several data quality issues were addressed such as outliers and adding more features to the model.
+ Best model from the score standpoint was Support Vector Machine, however, it is also significantly slower when compared to the other models.

#### Success factors:
+ The month in which the client was contacted, being March the month with higher probability of success.
+ Metrics related to campaign such as:
  * How many times has the client been contacted during previous campaigns.
  * How many days since the last time the client was contacted.
  * The result of the last contact.
+ Economics and social factors such as consumer and employment indexes increase confidence and therefore probability of a client subscribing a deposit.
