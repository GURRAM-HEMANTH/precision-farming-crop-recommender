# 🌾 Precision Farming: A Machine Learning-Based Crop Recommender

A machine learning-powered agricultural application designed to help farmers make better crop selection and yield prediction decisions using agricultural data.

## 📌 Project Overview

Precision Farming is a web-based application that uses machine learning algorithms to recommend suitable crops and predict agricultural production.

The system aims to support farmers by considering agricultural parameters, soil conditions, crop information and weather data.

## 🎯 Objectives

- Recommend suitable crops based on agricultural parameters.
- Predict crop yield using machine learning.
- Provide weather forecast information based on location.
- Allow users to upload and preview agricultural datasets.
- Support better agricultural decision-making.

## 🚀 Key Features

- **Crop Recommendation:** Recommends suitable crops using a trained machine learning model.
- **Crop Yield Prediction:** Estimates crop production using agricultural inputs.
- **Weather Information:** Provides weather forecast information based on the user's location.
- **Dataset Upload:** Allows users to upload and preview CSV datasets.
- **Machine Learning Integration:** Uses trained classification and regression models.

## 🧠 Machine Learning Algorithms

The project report discusses the following algorithms:

1. Random Forest
2. Support Vector Machine (SVM)
3. Artificial Neural Network (ANN)
4. Multivariate Linear Regression (MLR)
5. K-Nearest Neighbors (KNN)

The implementation uses saved Random Forest models for crop recommendation and yield prediction.

## 🛠️ Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Backend | Flask |
| Frontend | HTML, CSS, JavaScript |
| Machine Learning | Scikit-learn |
| Data Processing | NumPy, Pandas |
| Data Visualization | Matplotlib |
| Model Storage | Pickle |
| Dataset | CSV |

## 📂 Project Structure

```text
precision-farming-crop-recommender/
│
├── config/
├── model/
├── static/
├── templates/
│
├── app.py
├── weather.py
├── crop.pkl
├── yield.pkl
├── requirements.txt
├── upload.csv
├── test.csv
├── Accuracy.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/GURRAM-HEMANTH/precision-farming-crop-recommender.git
```

### 2. Navigate to the project directory

```bash
cd precision-farming-crop-recommender
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure the application

Check the configuration file:

```text
config/config.cfg
```

Set any required configuration values locally. Do not publish API keys or secret credentials.

### 6. Run the application

```bash
python app.py
```

### 7. Open in your browser

```text
http://127.0.0.1:5000/
```

## 📊 Dataset Information

The project report describes an agricultural dataset containing approximately 94,375 records.

The dataset includes:

- State Name
- Season
- Crop
- Area
- Production
- Soil Types

## 🔮 Future Enhancements

- Integration of real-time weather APIs.
- Improved crop yield prediction models.
- Fertilizer recommendation system.
- Integration of additional soil and climatic parameters.
- Mobile-friendly interface.
- Regional language support for farmers.

## 👨‍💻 Author

**Hemanth Gurram**

GitHub: https://github.com/GURRAM-HEMANTH

---

⭐ If you find this project interesting, consider starring the repository!
