# 🔥 Algerian Forest Fire Prediction

A Machine Learning web application built with **Flask** that predicts the **Fire Weather Index (FWI)** using meteorological and environmental parameters from the Algerian Forest Fires dataset.

## 🚀 Features

* Predicts Fire Weather Index using a trained Ridge Regression model
* Interactive web interface built with Flask
* Responsive input form for user data
* Real-time predictions
* Deployed on AWS Elastic Beanstalk

## 🛠️ Tech Stack

* Python
* Flask
* Scikit-Learn
* NumPy
* Pandas
* HTML/CSS
* AWS Elastic Beanstalk

## 📊 Input Features

The model uses the following features:

| Feature     | Description                  |
| ----------- | ---------------------------- |
| Temperature | Temperature in °C            |
| RH          | Relative Humidity            |
| Ws          | Wind Speed                   |
| Rain        | Rainfall                     |
| FFMC        | Fine Fuel Moisture Code      |
| DMC         | Duff Moisture Code           |
| ISI         | Initial Spread Index         |
| Classes     | Fire/Not Fire Classification |
| Region      | Geographic Region            |

## 📂 Project Structure

```text
.
├── application.py
├── requirements.txt
├── models
│   ├── ridge.pkl
│   └── scaler.pkl
├── templates
│   ├── index.html
│   └── home.html
├── static
│   └── style.css
└── README.md
```

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/algerian-forest-fire-prediction.git

cd algerian-forest-fire-prediction
```

### Create Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run Locally

```bash
python application.py
```

Visit:

```text
http://127.0.0.1:5000
```

## 🌐 Deployment

This project is deployed using AWS Elastic Beanstalk.

Deploy updates using:

```bash
eb deploy
```

## 📈 Machine Learning Model

* Algorithm: Ridge Regression
* Feature Scaling: StandardScaler
* Framework: Scikit-Learn

## 👨‍💻 Author

**Sumit Avasthi**

* GitHub: https://github.com/Sumit-Avasthi

## 📜 License

This project is licensed under the MIT License.
