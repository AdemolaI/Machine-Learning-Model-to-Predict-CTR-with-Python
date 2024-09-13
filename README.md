# Machine-Learning-Model-to-Predict-CTR-with-Python

[This project](https://github.com/AdemolaI/Machine-Learning-Model-to-Predict-CTR-with-Python/blob/master/Machine_Learning_Models_to_Predict_CTR.ipynb) is aimed at building machine learning models to predict click-through rates (CTR) based on historical marketing data.
The model performances are measured using statistical metrics such as  MSE, RMSE, MAE and R-squared.

The problem was approached from a regression standpoint due to the CTR feature being a continuous variable. 
The machine learning algorithms implemented include:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor
  
The impact of the model features on prediction values was analysed using SHAP values and visualisation (beeswarm, waterfall)
Based on the results of this analysis, the XGBoost models showed great performances in the predictions on the different versions of the data frame used. 
The performance improved based on how outliers were handled in the data frames. This also made the Decision Tree Regressor have the best performance on
the “[mc4 b encoded](https://github.com/AdemolaI/Machine-Learning-Model-to-Predict-CTR-with-Python/blob/master/Machine_Learning_Models_to_Predict_CTR.ipynb)” data frame. 
This shows that the performance of a model can be influenced by data processing and feature engineering techniques. 

# Implications for Marketing Campaigns

Data-driven strategies and decisions have been proven to have a significant impact on marketing results. Historical data that is rich with all the relevant information from
marketing campaigns can be analysed using machine learning models to discover trends or patterns and also to make predictions for the future based on identified patterns and relationships in the data set. 
This technology through analytical tools combined with the necessary human involvement forms a very powerful mechanism for businesses or brands to achieve their marketing KPIs targets like increasing click-through rates when they are well tailored for their specific niche or situation.

## Data Information.

Source: https://www.kaggle.com/datasets/rahulchavan99/marketing-campaign-dataset 
