🧬 Breast Cancer Prediction using Machine Learning

A data-driven machine learning project that predicts whether a tumor is malignant (cancerous) or benign (non-cancerous) using classification techniques.

📌 Overview

This project focuses on building a predictive model using supervised machine learning to assist in early detection of breast cancer. By analyzing medical diagnostic features, the model classifies tumors with high accuracy, supporting data-driven decision-making in healthcare.

🎯 Objectives
Perform data cleaning and preprocessing
Conduct exploratory data analysis (EDA)
Identify and remove highly correlated features
Train a classification model (Logistic Regression)
Evaluate model performance using standard metrics
📊 Dataset

The dataset contains features computed from digitized images of breast mass cell nuclei, including:

Radius
Texture
Perimeter
Area
Smoothness
Compactness
Symmetry
Fractal dimension
Target Variable:
M → Malignant (1)
B → Benign (0)
⚙️ Workflow
1. Data Preprocessing
Removed irrelevant columns (id, Unnamed: 32)
Converted categorical diagnosis labels to numerical values
Checked and visualized missing values
2. Exploratory Data Analysis (EDA)
Distribution plots for numerical features
Correlation heatmap for feature relationships
Identification of multicollinearity
3. Feature Selection
Removed highly correlated features (threshold > 0.92)
Reduced redundancy to improve model performance
4. Model Building
Split data into training and testing sets (70/30)
Applied StandardScaler for normalization
Trained a Logistic Regression model
5. Evaluation Metrics
Accuracy Score
Confusion Matrix
Classification Report
🧠 Model Used
Logistic Regression
Simple and interpretable classification algorithm
Performs well on linearly separable data
📈 Results
High training and testing accuracy achieved
Model effectively distinguishes between malignant and benign cases
Confusion matrix shows strong classification performance
🛠️ Tech Stack
Python
Libraries:
Pandas
NumPy
Seaborn
Matplotlib
Missingno
Scikit-learn
📂 Project Structure
breast-cancer-prediction/
│── breast cancer.ipynb
│── data.csv
│── README.md
🚀 How to Run
# Clone the repository
git clone https://github.com/Nikh56/BREAST-CANCER.git

# Navigate to the folder
cd breast-cancer-prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
🧪 Future Improvements
Implement advanced models (Random Forest, SVM, XGBoost)
Hyperparameter tuning
Deploy as a web application
Add real-time prediction interface
⚠️ Disclaimer

This project is for educational purposes only and should not be used as a substitute for professional medical diagnosis.

🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

📄 License

This project is licensed under the MIT License.

👨‍💻 Author

NIKHIL KUMAR
GitHub: https://github.com/Nikh56
