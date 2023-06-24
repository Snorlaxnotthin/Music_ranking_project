# Music_ranking_project

We use machine learning to predict the danceability of music track.

We evaluated the performance between different models, including precision, scalability and efficiency. Most of the parameters we use is tested by cross-validation.

### Data Preprocess

We used different transformation including log-transform and ont-hot to encode some useful feature, then impute missing data by K-nearest neighbor imputer. We also tested polynomial feature to increase the generalization power of the model.

### Models
We used LASSO, Random Forest Regression and XGBoost. We also include the detail of XGBoost in the report.
