# Traffic Congestion Prediction Using Machine Learning

## Project Overview
This project uses machine learning to predict traffic congestion levels from a smart city traffic and mobility dataset.

## Objective
- Analyze traffic congestion patterns.
- Predict congestion levels using historical traffic data.
- Evaluate model performance.
- Visualize congestion categories and prediction results.

## Dataset Description
**Dataset:** Smart City Traffic and Mobility Dataset  
**File:** `smart_city_traffic_mobility.csv`  
**Records:** 204,000  
**Features:** 47 columns, including traffic information, road characteristics, weather conditions, vehicle counts, and congestion indicators.

The dataset is loaded from a ZIP file in Google Colab. Include the original dataset in this repository only if its licence permits redistribution.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Machine Learning Algorithm
Random Forest Classifier.

## Methodology
1. Load and inspect the dataset.
2. Check missing values and congestion categories.
3. Prepare numerical and categorical features.
4. Split the dataset into training and testing sets.
5. Train the Random Forest model.
6. Evaluate accuracy and classification metrics.
7. Generate a confusion matrix and congestion distribution graph.
8. Save prediction results as a CSV file.

## Project Files
- `Traffic_Congestion_Prediction.ipynb` — Python source code and execution outputs.
- `traffic_congestion_predictions.csv` — Actual and predicted congestion levels.
- `confusion_matrix.png` — Model evaluation visualization.
- `congestion_distribution.png` — Congestion distribution visualization.
- `Traffic_Congestion_Project_Report.pdf` — One-page project report, if included.

## Results
The model is evaluated using accuracy, precision, recall, and F1-score. Refer to the executed notebook for the actual measured results.

## Conclusion
This project demonstrates the use of machine learning to classify traffic congestion levels using smart city traffic data. Future improvements may include testing on new data and using real-time traffic information.

## How to Run
1. Open the notebook in Google Colab.
2. Upload the dataset ZIP file.
3. Run each code cell in order.
4. Review the evaluation metrics, graphs, and predictions.
