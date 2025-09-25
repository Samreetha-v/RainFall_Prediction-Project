🌦️ Rainfall Prediction Using Random Forest

📌 Overview

This project uses machine learning to predict the possibility of rainfall based on weather conditions such as temperature, humidity, pressure, and wind speed. By applying the Random Forest algorithm, the system provides accurate and timely predictions that can be useful for agriculture, disaster prevention, and resource management.

🎯 What This Project Does

Analyzes and visualizes weather data.

Preprocesses data to handle missing values and categorical features.

Trains a Random Forest model to predict rainfall.

Offers a simple and interactive Gradio interface for live predictions.

🧠 Why This Matters

Rainfall prediction plays a key role in agriculture, flood prevention, and water management. With accurate predictions, stakeholders can make better decisions and reduce risks caused by natural disasters.

📊 Dataset

The project uses the Australian Weather Dataset (Kaggle), which contains daily observations such as:

🌡️ MinTemp & MaxTemp

🌧️ Rainfall (mm)

🌞 Sunshine hours

💨 Wind direction & speed

💧 Humidity levels

🌫️ Cloud cover

⏱️ Atmospheric pressure

⚙️ Tech Stack

Language: Python

Libraries: pandas, numpy, scikit-learn, seaborn, matplotlib, imblearn

Model: Random Forest Classifier

Interface: Gradio

Environment: Google Colab / Jupyter Notebook

🧪 Workflow

Preprocessing – Clean data, handle missing values, encode categories.

EDA – Visualize patterns and correlations.

Model Training – Train Random Forest on selected attributes.

Evaluation – Measure accuracy, confusion matrix, and F1-score.

Deployment – Use Gradio for real-time predictions.

💻 How to Run
# Clone repository
git clone https://github.com/yourusername/rainfall-prediction.git
cd rainfall-prediction

# Install dependencies
pip install -r requirements.txt

# Run script
python rainfall_prediction.py

# Or run via notebook
jupyter notebook rainfall_prediction.ipynb

# Launch Gradio interface
python app.py

📈 Results

✅ Accurately predicts rainfall probability for the next day.

✅ Achieved high accuracy using Random Forest.

✅ Easy-to-use web interface for non-technical users.

📸 Sample Output

Input: MinTemp, MaxTemp, Humidity, Pressure, etc.

Output:

🌧️ “THERE IS A CHANCE OF RAINFALL”

☀️ “LESS POSSIBLE”

📜 Future Scope

Add advanced models (XGBoost, ANN).

Deploy as a web API for integration.

Connect with real-time weather APIs for live forecasting.

👩‍💻 Author

Samreetha V
B.E. Computer Science and Engineering
