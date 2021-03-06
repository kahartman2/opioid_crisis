# County Level Analysis of Drug Related Deaths

#### Objectives

Use machine learning classification models to assist policy makers in the following ways: 
  
      1. Identify demographic factors highly correlated with a large proporition of drug-related deaths 
      2. Hypothesize ways in which plicies can most effectively curtail drug-related deaths 
      
 #### Data Selection
 
Gathered demographic and drug-related county-level data from a variety of sources shown in the below image. Cleaned data and binned data points through feature engineering. 
 
 ![](https://github.com/kahartman2/opioid_crisis/blob/master/readme_images/data_sources.png)

#### Model Selection 

Used Scikitlearn's Dummy Classifier to create a baseline model, which solely predicted the dominant class, generating 51% accuracy. 

 ![](https://github.com/kahartman2/opioid_crisis/blob/master/readme_images/baseline_model.png)
 
After using Tpot and various grid searches, found a random forest classifier to be the optimal model, generating 79% accuracy. 

![](https://github.com/kahartman2/opioid_crisis/blob/master/readme_images/model_comparison.png)

![](https://github.com/kahartman2/opioid_crisis/blob/master/readme_images/optimal_model.png)

#### Results 

Investigated feature importance to gain an understanding of the features most highly correlated with drug-related deaths. 

![](https://github.com/kahartman2/opioid_crisis/blob/master/readme_images/feature_importance.png)
