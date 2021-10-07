#### Teleco-Churn-Data-Analysis

Download and Dataset Details - https://www.kaggle.com/yeanzc/telco-customer-churn-ibm-dataset.

Tools and software Packages - PowerBI, Tableau, R, AzureMLStudio.

Tableau Data Viz (Still working on it to figure out how to build the dashboard as I did using Power BI) - https://public.tableau.com/views/TelecoChurnDataAnalysis/MonthlyChargevsChurnLabel?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

## The Dataset is an Imbalanced Two-Class Classification Problem. 

The predefined models I selected while working with R to find the right model didn't perform very well. After a pretty hefty coding with the 'tidymodels' library, I tried to run the model with Azure Machine Learning Designer Resource. Using the AutoML Feature, the **MaxAbsScaler, LightGBM** (Weighted AUC = 0.98750) showed as the best fit for this data. I am so happy to get the cloud based- high speed computation privilage (AZURE ML STUDIO) from Microsoft while using the free learner's opportunity! I wish they would have given me the same privilage for the Azure Databricks usage too!

Life gets to easy sometimes, eh!! 

Working on a detailed report and analysis, as well as the deploy Python code too.

Happy Machine Learning!!
