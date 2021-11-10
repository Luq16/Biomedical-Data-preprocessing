# Biomedical-Data-preprocessing
## Objective
The goal of this analysis is to show how to preprocess a biomedical data. Before perfoming machine learning on dataset it usually needs to be processed in a way that it will be suitable for downtream analysis.
## About data
The dataset ia a real medical dataset downloaded from Machine Learning repository (https://archive.ics.uci.edu/ml/datasets/Heart+Disease).

- age: age in years

- sex: sex (1 = male; 0 = female)

- chest_pain: chest pain type -- Value 1: typical angina -- Value 2: atypical angina -- Value 3: non-anginal pain -- Value 4: asymptomatic

- trestbps: resting blood pressure (in mm Hg on admission to the hospital)

- chol: serum cholestoral in mg/dl

- fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

- restecg: resting electrocardiographic results -- Value 0: normal -- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) -- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

- thalach: maximum heart rate achieved

- exang: exercise induced angina (1 = yes; 0 = no)

- oldpeak = ST depression induced by exercise relative to rest

- slope: the slope of the peak exercise ST segment -- Value 1: upsloping -- Value 2: flat -- Value 3: downsloping

- ca: number of major vessels (0-3) colored by flourosopy

- thal: 3 = normal; 6 = fixed defect; 7 = reversable defect

- num: diagnosis of heart disease (angiographic disease status) -- Value 0: < 50% diameter narrowing -- Value 1: > 50% diameter narrowing (in any major vessel: attributes 59 through 68 are vessels) 

## Preprocessing steps

* Deal with missing values
* Normalization
* Discretization
* Exporatory data analysis to understand data