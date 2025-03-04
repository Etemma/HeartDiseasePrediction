# HeartDiseasePrediction
Predicting heart disease using machine learning

steps
1. Problem definition
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentation

## 1. Problem Definition
In a statement,
> Given clinical parameters of a patient, can we predict if the have heart disease?
## 2. Data - Creating data dictionary
Original data from cleaeland database on UCI machine learning repository. Available on: https://archive.ics.uci.edu/dataset/45/heart+disease

Also available on Kaggle: https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data?select=heart_disease_uci.csv
## 3. Evaluation
> If we can reach 95% accuracy at predicting whether or not a patient has heart disease during proof of concept, we'll pursue the project.
## 4. Features 
**Create data dictionary**
* id (Unique id for each patient)
  
* 
age (Age of the patient in years
* 
origin (place of stud
* sex (male[1]/female[0])
* cp - chest pain type
  * 0 - typical angina (chest pain related to decreased blood supply to the heart)
  * 1 - atypical angina (Chest Pain not related to heart)
  * 2- non-anginal (typically esophagael spasms [non heart related])
  * 3 - asymptomatic (Not showing signs of disease)
* trestbpd resting blood pressure ( resting blood pressure in mmHg on admission to the hospital))
* chol (serum cholesterol in mg/dl)
* fbs (if fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
* restecg (resting electrocardiographic results) -- Values: [normal, stt abnormality, lv hypertrophy]
* thalach: max heart rate achieved
* exang: exercise-induced angina (True/False)
* oldpeak: ST depression induced by exercise relative to rest
* slope: Slope of peak exercise ST segment
* ca: number of majr vessels (0-3) colored by fluroscopy
* thal: [normal; fixed defect; reversible defect]
* target (1 or 0) 0dicted attribute
