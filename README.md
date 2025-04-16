📁 Project Name:
Explainable House Price Prediction using Neural Networks

🧠 Overview
This project builds a deep learning model to predict house prices using tabular real estate data. It combines a neural network with explainability tools (SHAP) to highlight how individual features influence predictions — enabling transparency and trust in AI systems.

🔍 Objectives
Predict house sale prices using features like square footage, age, etc.

Train a custom neural network for regression.

Visualize model predictions vs. true prices.

Use SHAP to explain model decisions feature-by-feature.

🛠️ Technologies & Tools
Python, NumPy, Pandas, Matplotlib, Seaborn

TensorFlow / Keras – for model training

SHAP – for model interpretability

Jupyter Notebook – for workflow and documentation

🧩 Dataset
Used a real estate dataset with the following features:

sqft_living, sqft_above, sqft_basement

age, lot_size

Target variable: House Price

Note: Dataset assumed cleaned and preloaded. You can plug in your own dataset in the format.

🔗 Notebook
👉 Explainable_house_predictions.ipynb

🚀 How It Works
Preprocess tabular data (no one-hot — all numerical)

Train a Keras-based regression neural network

Visualize model performance with scatter and residual plots

Apply SHAP to:

See global feature importance

Inspect local explanations (per-instance)

📊 Results
RMSE, MAE, and R² computed on test set

SHAP shows sqft_living and age as top contributors

SHAP visualizes why some homes are over/under-predicted

💡 Key Learnings
Neural networks can compete with XGBoost on tabular data with proper tuning.

SHAP is an excellent framework to explain DL models post-hoc.

Dense embeddings or log-transforming features could boost performance further.

📌 Future Improvements
Hyperparameter tuning with Keras Tuner

Embedding-based handling for categorical data (zip codes, etc.)

Web app interface using Streamlit or Gradio

Try TabNet for improved explainability and sparsity

📣 Author
Built with ❤️ by Ishan Bhattacharya
Drop a ⭐ if this repo helped you!