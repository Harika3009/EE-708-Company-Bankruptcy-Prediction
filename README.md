🏦 Company Bankruptcy Prediction

This repository contains code, models, and evaluation tools for a machine learning project that predicts company bankruptcy using financial indicators. The project combines traditional and deep learning approaches for robust classification performance.

📁 Contents

Code.ipynb: Main notebook for data preprocessing, model training, and predictions.

Evaluation.ipynb: Contains metrics, visualizations, and model comparisons.

Company-Bankruptcy-Prediction.pdf: Project report summarizing objective, methodology, results, and key insights.

GaussianNB_model (1).pkl: Trained Gaussian Naive Bayes model.

dnn_model.h5: Trained Deep Neural Network model.

scaler.pkl: Scikit-learn standard scaler used for data normalization.

🧠 Models Used

Gaussian Naive Bayes (GNB): Efficient baseline classifier.

Deep Neural Network (DNN): For capturing complex feature interactions.

Hybrid Voting Strategy: Combined predictions from both models using soft voting.

📊 Performance Highlights

Accuracy: 97.23%

F1-score: Improved from baseline to 0.51 using hybrid voting and class balancing.

⚙️ Libraries

Scikit-learn

TensorFlow / Keras

NumPy, Pandas, Matplotlib
