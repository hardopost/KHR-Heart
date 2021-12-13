# KHR-Heart
Data Science Project - Heart Failure Prediction

Goal 1 + secondary goal 2. Models.ipynb - training the models.
  *Balancing the data
  *Training a Random Forest Classifier and testing it on all the patients
  *Training a Random Forest Classifier and testing it for each subset of patients based on age and sex (Males aged 28-38, ...)
  *Finding out the accuracy, false positive rate, and false negative rate

Goal_2.ipynb - consists of finding most frequent feature values that occur with heart disease.
  * Categorizing numeric feature values and value ranges
  * One-hot encoding data with Transaction encoder to TRUE, FALSE values
  * Applying mlxtend apriori algorithm to find most frequent patterns
  * Finding association rules with mlxtend association_rules mining algorithm

Secondary goal 1. Associations between features.ipynb - Finding out which features are strongly associated with secondary features, 
where the first feature is directly influenceable by the patient.
  * Categorizing numeric feature values and value ranges + one-hot encoding
  * Creating association rules  with the Apriori algorithm
  * Digging out the rules that have high enough support (>0.33), where the antecedent is a feature that a patient can directly control