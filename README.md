# DL Methods for Early CVD Prediction

## Abstract
Cardiovascular disease (CVD) is a leading cause of death globally, making early prediction critical for timely interventions. This project develops deep learning models to predict CVD risk using health data, including age, blood pressure, cholesterol levels, and lifestyle factors. We implemented five models: Artificial Neural Network (ANN), Gated Recurrent Unit (GRU), Long Short-Term Memory (LSTM), MultiLayer Perceptron (MLP), and an ensemble hybrid model. Extensive preprocessing, including normalization and feature selection, was conducted. The models were evaluated based on accuracy, precision, recall, F1-score, and AUC, with the ensemble model achieving the best performance.

**Keywords:** CVD, Deep Learning, ANN, LSTM, GRU, MLP, Ensemble

## Dataset

The **Heart Failure Prediction Dataset**, compiled by Fedesoriano, is a comprehensive amalgamation of previously disparate datasets to create a unified resource for cardiovascular research. The dataset encompasses five distinct sources:

| **Dataset**     | **Observations** |
|-----------------|------------------|
| Cleveland       | 303              |
| Hungarian       | 294              |
| Switzerland     | 123              |
| Long Beach VA   | 200              |
| Stalog (Heart)  | 270              |

In total, these datasets contribute 1190 observations. After removing duplicated entries (272 observations), the resultant dataset comprises 918 unique observations. This is the largest heart disease dataset available for research and is publicly accessible via the UCI Machine Learning Repository.

### Attribute Information

The dataset contains 12 attributes that are crucial for heart disease prediction:

| **Attribute**       | **Description**                                          | **Values**                        |
|---------------------|----------------------------------------------------------|-----------------------------------|
| Age                 | Age of the patient (years)                               | Numeric value                    |
| Sex                 | Sex of the patient                                       | M: Male, F: Female                |
| ChestPainType       | Type of chest pain                                       | TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic |
| RestingBP           | Resting blood pressure (mm Hg)                           | Numeric value                    |
| Cholesterol         | Serum cholesterol (mm/dl)                                | Numeric value                    |
| FastingBS           | Fasting blood sugar                                      | 1: if FastingBS > 120 mg/dl, 0: otherwise |
| RestingECG          | Resting electrocardiogram results                        | Normal, ST: ST-T wave abnormality, LVH: left ventricular hypertrophy |
| MaxHR               | Maximum heart rate achieved (between 60 and 202)         | Numeric value                    |
| ExerciseAngina      | Exercise-induced angina                                  | Y: Yes, N: No                    |
| Oldpeak             | ST depression induced by exercise relative to rest       | Numeric value                    |
| ST Slope            | The slope of the peak exercise ST segment                | Up: upsloping, Flat: flat, Down: downsloping |
| HeartDisease        | Output class                                             | 1: heart disease, 0: Normal       |

## Models Evaluated
- **Artificial Neural Network (ANN)**
- **Gated Recurrent Unit (GRU)**
- **Long Short-Term Memory (LSTM)**
- **MultiLayer Perceptron (MLP)**
- **Ensemble Hybrid Model**

## Results
The table below highlights the performance of each model:

| Metric       | ANN    | GRU    | LSTM   | MLP    | RNN    | Final Ensemble |
|--------------|--------|--------|--------|--------|--------|----------------|
| **Accuracy** | 94.01% | 92.16% | 92.48% | 92.37% | 94.12% | **94.55%**     |
| **Precision**| 93.81% | 92.75% | 94.34% | 92.94% | 94.51% | **95.26%**     |
| **Recall**   | 95.47% | 93.11% | 91.93% | 93.31% | 94.88% | **94.88%**     |
| **F1 Score** | 94.63% | 92.93% | 93.12% | 93.12% | 94.70% | **95.07%**     |
| **ROC AUC**  | 93.83% | 92.04% | 92.55% | 92.26% | 94.03% | **94.51%**     |

## Conclusion
This project demonstrates the effectiveness of deep learning models in predicting cardiovascular disease, with the ensemble hybrid model achieving the best performance. Deep learning techniques, particularly those capable of capturing temporal dependencies, can significantly enhance early detection of CVD, providing a valuable tool for healthcare professionals.

## Repository Link
Explore the code and the detailed implementation in the GitHub repository: [CVD Prediction Using DL](https://github.com/metarex21/CVD-prediction-using-DL)
