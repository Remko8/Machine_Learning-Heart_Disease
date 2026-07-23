# Machine_Learning-Heart_Disease

Identifying whether a patient has a  heart disease.

Data contains 303 samples.

## Features

    1. age - age in years

    2. sex - sex (1 = male; 0 = female)

    3. cp - chest pain type (1 = typical angina; 2 = atypical angina; 3 = non-anginal pain; 0 = asymptomatic)

    4. trestbps - resting blood pressure (in mm Hg on admission to the hospital)

    5. chol - serum cholestoral in mg/dl

    6. fbs - fasting blood sugar > 120 mg/dl (1 = true; 0 = false)

    7. restecg - resting electrocardiographic results (1 = normal; 2 = having ST-T wave abnormality; 0 = hypertrophy)

    8. thalach - maximum heart rate achieved

    9. exang - exercise induced angina (1 = yes; 0 = no)

    10. oldpeak - ST depression induced by exercise relative to rest

    11. slope - the slope of the peak exercise ST segment (2 = upsloping; 1 = flat; 0 = downsloping)

    12. caa - number of major vessels (0-3) colored by flourosopy

    13. thall - Thallium Stress Test (2 = normal; 1 = fixed defect; 3 = reversable defect)

    14. output - the predicted attribute - heart disease diagnosis, 0 - patient is healthy, 1 - patient has the disease


## Raw Data

|id	|age	|sex	|cp	    |trtbps	|chol	|fbs	|restecg|thalachh	|exng	|oldpeak|slp	|caa	|thall	|output|
|---|-------|-------|-------|-------|-------|-------|-------|-----------|-------|-------|-------|-------|-------|---|
|0	|59.0	|1.0	|1.0	|134.0	|204.0	|0.0	|0.0	|162.0	    |0.0	|0.8	|1.0	|2.0	|3.0	|1.0|
|1	|43.0	|1.0	|3.0	|130.0	|315.0	|0.0	|0.0	|162.0	    |0.0	|1.9	|1.0	|1.0	|3.0	|0.0|
|2	|55.0	|1.0	|4.0	|160.0	|289.0	|0.0	|2.0	|145.0	    |1.0	|0.8	|2.0	|1.0	|7.0	|4.0|
|3	|63.0	|1.0	|4.0	|130.0	|254.0	|0.0	|2.0	|147.0	    |0.0	|1.4	|2.0	|1.0	|7.0	|2.0|
|4	|48.0	|1.0	|2.0	|130.0	|245.0	|0.0	|2.0	|180.0	    |0.0	|0.2	|2.0	|0.0	|3.0	|0.0|
|5	|66.0	|1.0	|4.0	|120.0	|302.0	|0.0	|2.0	|151.0	    |0.0	|0.4	|2.0	|0.0	|3.0	|0.0|
|6	|53.0	|1.0	|4.0	|142.0	|226.0	|0.0	|2.0	|111.0	    |1.0	|0.0	|1.0	|0.0	|7.0	|0.0|
|7	|58.0	|1.0	|4.0	|114.0	|318.0	|0.0	|1.0	|140.0	    |0.0	|4.4	|3.0	|3.0	|6.0	|4.0|
|8	|43.0	|0.0	|4.0	|132.0	|341.0	|1.0	|2.0	|136.0	    |1.0	|3.0	|2.0	|0.0	|7.0	|2.0|
|9	|48.0	|1.0	|4.0	|130.0	|256.0	|1.0	|2.0	|150.0	    |1.0	|0.0	|1.0	|2.0	|7.0	|3.0|
|10	|61.0	|1.0	|1.0	|134.0	|234.0	|0.0	|0.0	|145.0	    |0.0	|2.6	|2.0	|2.0	|3.0	|2.0|
|11	|74.0	|0.0	|2.0	|120.0	|269.0	|0.0	|2.0	|121.0	    |1.0	|0.2	|1.0	|1.0	|3.0	|0.0|

## Unique values
### Per feature count
![Nunique](/Project_Screenshots/3_Nunique.png)

### Categorical data per value counts
![Unique](/Project_Screenshots/3_Unique.png)

## Nulls
![Nulls](/Project_Screenshots/4_Nans.png)

# Data Distributions
![Output](/Project_Screenshots/Graphs/1_Output.png)
![Age_dist](/Project_Screenshots/Graphs/2_Age.png)
![Sex_dist](/Project_Screenshots/Graphs/2_Sex.png)

## Correlations
![Correlation1](/Project_Screenshots/5_Correlation.png)
![Correlation2](/Project_Screenshots/6_Correlation.png)

# Model Training
![Model](/Project_Screenshots/97_Model.png)
![Training](/Project_Screenshots/99_Training.png)

Rows marked in red are misclassified predictions
![Prediction](/Project_Screenshots/100_Prediction.png)
![Scores](/Project_Screenshots/101_Scores.png)
![Confusion_Matrix](/Project_Screenshots/102_Confusion_Matrix.png)

