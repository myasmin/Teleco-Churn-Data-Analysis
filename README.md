## Teleco-Churn-Data-Analysis

Download and Dataset Details - https://www.kaggle.com/yeanzc/telco-customer-churn-ibm-dataset.

Tools and software Packages - PowerBI, Tableau, R, AzureMLStudio.

Tableau Data Viz - https://public.tableau.com/app/profile/mahmuda.yasmin/viz/TelecoChurnDataAnalysis2/Dashboard2

## The Dataset is an Imbalanced Two-Class Classification Problem. 

I have written down the elaborate finding here - https://sites.google.com/view/myasmin/project-portfolio/an-ml-model-on-ibm-teleco-churn-data

The predefined models I selected while working with R to find the right model didn't perform very well.

After a pretty hefty coding with the 'tidymodels' library, I tried to run the model with Azure Machine Learning Designer Resource. Using the AutoML Feature, the **MaxAbsScaler, LightGBM** (Weighted AUC = 0.98750) showed as the best fit for this data. I found that AUTO-ML selects the best model based on the selection criteria, but couldn't help to explain the algorithm behind. Any suggestion will be highly appreciable!

The details are here - https://sites.google.com/view/myasmin/project-portfolio/an-ml-model-on-ibm-teleco-churn-data

Happy Machine Learning!!
