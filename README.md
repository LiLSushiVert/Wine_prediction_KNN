**Wine Quality Classification with KNN**
This project focuses on analyzing and predicting the quality of red wine using machine learning, specifically the K-Nearest Neighbors (KNN) classifier

- Dataset: winequality-red_s2.csv
- Source: Contains physicochemical tests (e.g. pH, alcohol, chlorides) of red wine samples and their quality scores (rated from 0 to 10).

**Project Highlights**
- Exploratory Data Analysis (EDA):
  Visualized relationships using scatter plots and correlation heatmaps.
  Investigated memory usage and dataset dimensions.
  
 **Data Preprocessing:**
  Applied MinMaxScaler for normalization.
  Performed train-test splitting with train_test_split.

  **Modeling:**
  Built a K-Nearest Neighbors classifier.
  Evaluated performance using Accuracy, MSE, MAE, and R².
  Conducted additional validation on a held-out test set.
  
 **Tech Stack**
  Python (Pandas, NumPy, Matplotlib, Seaborn)
  Scikit-learn
  Google Colab
  
  **Model Results**
- Accuracy on test data: **0.5125**
- Validation accuracy:  **0.515625**
- Evaluation metrics: MSE, MAE, R² included for deeper performance understanding.
- Mean Squared Error (MSE): **0.7109375**
- Mean Absolute Error (MAE): **0.5578125**
- R-squared (R2): **-0.09329418699385394**
- Predicted wine quality (normalized scale): **5.00**

![image](https://github.com/user-attachments/assets/ea9a874e-9f3e-46d5-b73b-58f9c5cb2d4e)

Correlation Matrix of Wine Quality
![image](https://github.com/user-attachments/assets/50e54230-6b16-40c6-a48b-fc5e952f1593)
