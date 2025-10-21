# Heart Failure Prediction

Cardiovascular diseases (CVD) are the leading cause of death worldwide, accounting for about 17.9 million deaths per year (approximately 31% of all global deaths). Four out of five CVD deaths are due to heart attacks and strokes, and one third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common outcome of CVD and this dataset contains 11 features that can be used to predict possible heart disease.

People with cardiovascular disease or at high cardiovascular risk (due to one or more risk factors such as hypertension, diabetes, hyperlipidemia, or established disease) need early diagnosis and management — where a machine learning model can be very helpful.

## Dataset attributes

# Heart Failure Prediction

Cardiovascular diseases (CVD) are the leading cause of death worldwide, accounting for about 17.9 million deaths per year (approximately 31% of all global deaths). Four out of five CVD deaths are due to heart attacks and strokes, and one third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common outcome of CVD and this dataset contains 11 features that can be used to predict possible heart disease.

People with cardiovascular disease or at high cardiovascular risk (due to one or more risk factors such as hypertension, diabetes, hyperlipidemia, or established disease) need early diagnosis and management — where a machine learning model can be very helpful.

## Dataset attributes

- Age: patient age [years]
- Sex: patient sex
  - M: Male
  - F: Female
- ChestPainType: chest pain type
  - TA: Typical Angina
  - ATA: Atypical Angina
  - NAP: Non-Anginal Pain
  - ASY: Asymptomatic
- RestingBP: resting blood pressure [mm Hg]
- Cholesterol: serum cholesterol [mg/dl]
- FastingBS: fasting blood sugar
  - 1: if FastingBS > 120 mg/dl
  - 0: otherwise
- RestingECG: resting electrocardiogram results
  - Normal: Normal
  - ST: ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
  - LVH: probable or definite left ventricular hypertrophy according to Estes' criteria
- MaxHR: maximum heart rate achieved [numeric value between 60 and 202]
- ExerciseAngina: exercise-induced angina
  - Y: Yes
  - N: No
- Oldpeak: ST depression induced by exercise relative to rest [numeric value]
- ST_Slope: slope of the peak exercise ST segment
  - Up: upsloping
  - Flat: flat
  - Down: downsloping
- HeartDisease: output class
  - 1: heart disease
  - 0: Normal

*The term Angina Pectoris comes from the Latin terms Angina = pain and Pectoris = chest. It is a syndrome characterized by retrosternal pain, sometimes radiating to the ulnar side of the left arm and shoulders. [wiki reference](https://www.my-personaltrainer.it/cardiopatia-ischemica/angina.html)*

## Dataset source

This dataset was created by combining several previously available heart datasets that had not been combined before. In this combined dataset, 5 heart datasets were merged on 11 common features, making it the largest heart disease dataset available for research purposes. The five datasets used are:

- Cleveland: 303 observations
- Hungary: 294 observations
- Switzerland: 123 observations
- Long Beach VA: 200 observations
- Stalog (Heart) dataset: 270 observations

- Total (before duplicates removed): 1190 observations
- Duplicates removed: 272 observations

Final dataset: **918 observations**

## Dataset analysis

The notebook [analysis](analysis.ipynb) contains the dataset study and includes:

- Exploratory data analysis
- Missing data analysis
- Measures of central tendency and dispersion
- Correlation analysis between variables
- Outlier analysis
- Data normalization and binary classification using a Machine Learning algorithm (Random Forest)

## Time series analysis

The notebook [analysis_time_series](analysis_time_series.ipynb) contains a simple time series study comparing predictions from a standard regression model and an autoregressive model.

## Citation

fedesoriano. (September 2021). Heart Failure Prediction Dataset. Retrieved [Date Retrieved] from <https://www.kaggle.com/fedesoriano/heart-failure-prediction>.
This project is also available on [GitHub](https://github.com/AngeloLongano/heart_failure_prediction.git)
