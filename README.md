# DL Methods for Early CVD Prediction

## Abstract
Cardiovascular disease (CVD) remains a leading cause of mortality worldwide, emphasizing the critical need for early prediction and intervention. This project explores the development and evaluation of deep learning models to predict the risk of cardiovascular disease using a comprehensive dataset. The dataset includes various health parameters such as age, gender, blood pressure, cholesterol levels, and lifestyle habits. Extensive data preprocessing was performed, including handling missing values, normalization, and feature selection. 

We implemented and compared the performance of five deep learning models: Artificial Neural Network (ANN), Gated Recurrent Unit (GRU), Long Short-Term Memory (LSTM), MultiLayer Perceptron (MLP), and a hybrid model by ensemble methods. The models were evaluated based on metrics such as accuracy, precision, recall, F1-score, and the area under the curve (AUC). 

Our results indicate that the hybrid ensemble model outperforms the others, achieving an accuracy of 94.55% in predicting CVD. The study demonstrates that deep learning models, particularly those capable of capturing temporal dependencies, can be highly effective in early CVD prediction. This approach offers a non-invasive, efficient, and accurate tool for assessing cardiovascular risk, potentially enabling timely medical interventions and reducing the global burden of cardiovascular diseases.

**Keywords:** Cardiovascular Disease (CVD), Deep Learning, ANN, LSTM, GRU, MLP, Ensemble methods

## Models Evaluated
- **Artificial Neural Network (ANN)**
- **Gated Recurrent Unit (GRU)**
- **Long Short-Term Memory (LSTM)**
- **MultiLayer Perceptron (MLP)**
- **Ensemble Hybrid Model**

## Results
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
