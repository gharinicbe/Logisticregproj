Predictive Logistic Model for Heart Disease
This project aims to build a predictive logistic model to determine the likelihood of a patient prone to heart disease based on collected data. The dataset used in this project contains the following variables:

age: age of the patient
sex: gender of the patient (0 = female, 1 = male)
cp: type of chest pain (0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic)
trestbps: resting blood pressure (in mm Hg)
chol: serum cholesterol (in mg/dl)
fbs: fasting blood sugar > 120 mg/dl (0 = false, 1 = true)
restecg: resting electrocardiographic results (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy)
thalach: maximum heart rate achieved
exang: exercise induced angina (0 = no, 1 = yes)
oldpeak: ST depression induced by exercise relative to rest
slope: the slope of the peak exercise ST segment (0 = upsloping, 1 = flat, 2 = downsloping)
ca: number of major vessels (0-3) colored by fluoroscopy
thal: thalassemia (0 = normal, 1 = fixed defect, 2 = reversable defect)
target: presence of heart disease (0 = no, 1 = yes)
Installation
This project requires Python 3.7 or higher and the following Python libraries:

NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
You can install these libraries using pip, by running the following command:

Copy code
pip install numpy pandas matplotlib seaborn scikit-learn
Usage
To use this project, follow these steps:

Clone this repository to your local machine.

Navigate to the cloned directory in your terminal.

Run the heart_disease_prediction.py script using the following command:

Copy code
python heart_disease_prediction.py
The script will generate a logistic regression model to predict the likelihood of heart disease based on the collected data.

The script will also generate a decision tree and a random forest model, and compare their performance to the logistic regression model.

Results
The results of this project show that the logistic regression model achieved an Train /Test accuracy of 86.79%/86.81% in predicting the likelihood of heart disease, while the decision tree and random forest models achieved an Train /Test accuracy of 100%/78.02% and 100%/81.32, respectively, which is overfitting. These results indicate that the logistic regression model is the most accurate model for predicting the likelihood of heart disease based on the collected data.

Conclusion
In conclusion, this project demonstrates the effectiveness of logistic regression as a predictive model for heart disease, and compares its performance to that of overfitting models like decision tree and random forest. By implementing this model, healthcare providers can identify patients who are at a higher risk of developing heart disease and provide timely interventions to improve their health outcomes.










