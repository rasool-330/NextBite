# 🍔 NextBite — Food Order Prediction System

NextBite is a **Machine Learning-based food recommendation system** that predicts the **Top 3 food items** a customer is likely to order based on historical food-order data.

The project combines **Python, Scikit-learn, Pandas, NumPy, and Streamlit** to build an interactive food prediction application.

---

## 📌 Problem Statement

Food vendors and food delivery platforms generate large amounts of historical order data. However, identifying customer preferences and predicting the next likely food choice can be challenging.

NextBite addresses this problem by using Machine Learning to analyze historical order patterns and predict the **Top 3 most likely food items**.

### Key challenges addressed

- Predicting likely food choices
- Ranking food items based on learned patterns
- Providing quick predictions
- Handling user input through an interactive interface
- Reusing a trained ML model for real-time inference

---

## 💡 Solution

NextBite uses a trained Machine Learning model to analyze historical food-order data and generate ranked predictions.

The application:

1. Loads historical food-order data
2. Cleans and preprocesses the dataset
3. Performs feature engineering
4. Encodes categorical features
5. Scales numerical features
6. Trains a Machine Learning model
7. Saves the trained model and preprocessing objects
8. Loads the saved model into the Streamlit application
9. Accepts user input
10. Predicts the Top 3 food items

---

## 🧠 System Workflow

```text
                 ┌──────────────────────┐
                 │ Historical Food Data │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Data Preprocessing   │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Feature Engineering  │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Encoding & Scaling   │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Model Training       │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Trained ML Model     │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Streamlit Application│
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ User Input           │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Prediction           │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │ Top 3 Food Items     │
                 └──────────────────────┘
```

---

## 🛠️ Technologies Used

| Technology | Usage |
|---|---|
| **Python** | Core programming language |
| **Pandas** | Data loading, cleaning and manipulation |
| **NumPy** | Numerical operations |
| **Scikit-learn** | Machine Learning and preprocessing |
| **Streamlit** | Interactive web application |
| **Jupyter Notebook** | Data analysis and model development |
| **Pickle** | Saving and loading trained ML components |

---

## ✨ Key Features

### 🍕 Top-3 Food Prediction

The system predicts and ranks the three most likely food items instead of returning only a single result.

### 🧠 Machine Learning Based

Historical food-order data is used to train the prediction model and identify patterns in customer orders.

### ⚡ Real-Time Inference

The trained model is loaded directly into the application so predictions can be generated without retraining the model for every request.

### 📊 Interactive Interface

The Streamlit application provides a simple interface through which users can provide inputs and receive predictions.

### 🔄 Reusable ML Pipeline

The trained model, label encoders, and scaler are stored separately and reused during prediction.

---

## 📈 Performance Highlights

The current project was developed with a focus on efficient prediction and concurrent usage.

- **500+ historical records**
- **40+ concurrent users**
- **Prediction latency below 250 ms**
- Approximately **30% improvement in decision turnaround time**

> Performance may vary depending on the hardware, dataset size, and execution environment.

---

## 🧪 Machine Learning Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Feature Engineering
     ↓
Categorical Encoding
     ↓
Feature Scaling
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Model Serialization
     ↓
Streamlit Application
     ↓
User Input
     ↓
Top-3 Prediction
```

---

## 📂 Project Structure

```text
NextBite/
│
├── .devcontainer/
│
├── Food-Order-Prediction(NextBite).ipynb
│   └── Data analysis, preprocessing,
│       model development and experimentation
│
├── app.py
│   └── Streamlit application
│
├── food_orders_clean.csv
│   └── Cleaned food-order dataset
│
├── final_model.pkl
│   └── Trained Machine Learning model
│
├── label_encoders.pkl
│   └── Saved categorical encoders
│
├── scaler.pkl
│   └── Saved feature scaler
│
├── requirements.txt
│   └── Python dependencies
│
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/rasool-330/NextBite.git
```

### 2. Navigate to the Project

```bash
cd NextBite
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Streamlit application using:

```bash
streamlit run app.py
```

After running the command, Streamlit will provide a local URL in the terminal.

---

## 📓 Machine Learning Notebook

The complete Machine Learning workflow is available in:

```text
Food-Order-Prediction(NextBite).ipynb
```

The notebook contains the data analysis, preprocessing, feature preparation, model development, and experimentation performed for the project.

---

## 📊 Dataset

The project uses historical food-order data for training and prediction.

The cleaned dataset included in the repository is:

```text
food_orders_clean.csv
```

---

## 🔮 Future Enhancements

- Real-time data ingestion
- Automated model retraining
- Personalized recommendations
- Larger and more diverse datasets
- Advanced recommendation algorithms
- User authentication
- Recommendation history
- Restaurant analytics dashboard
- REST API for prediction services
- Cloud-based scalable deployment

---

## 🎯 Learning Outcomes

This project provided practical experience in:

- Machine Learning
- Data preprocessing
- Feature engineering
- Categorical encoding
- Feature scaling
- Model training
- Model serialization
- Real-time ML inference
- Streamlit application development
- Git and GitHub
- Machine Learning deployment concepts

---

## 👨‍💻 Author

### Patan Rasool

Computer Science Engineering Student

**GitHub:**  
https://github.com/rasool-330

**Project Repository:**  
https://github.com/rasool-330/NextBite
## 🚀 Live Demo

👉 [Try NextBite Live](https://nextbite-330.streamlit.app/)
---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

---

## 📜 Disclaimer

This project was developed for **learning, experimentation, and practical Machine Learning implementation**. Prediction results depend on the quality, size, and characteristics of the historical dataset.

---

**Built with Python, Machine Learning & Streamlit.**
