# 🚗 Car Price Predictor

![Car Price Predictor Interface](https://github.com/user-attachments/assets/19f599c9-56ec-4f39-9bdd-09ba54e6431e)

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Model Information](#model-information)
- [Project Structure](#project-structure)
- [Future Improvements](#future-improvements)
- [Acknowledgements](#acknowledgements)

## 🌟 Overview

The Car Price Predictor is a web application that uses machine learning to predict the price of used cars based on various features and specifications. This project integrates a Linear Regression model with a Flask backend and an intuitive HTML/CSS/JavaScript frontend to provide users with accurate price estimates.

## ✨ Features

- **User-friendly Interface**: Clean and responsive design for inputting car details
- **Real-time Prediction**: Instant price estimation based on input parameters
- **Data Validation**: Input validation to ensure accurate predictions
- **Interactive Elements**: Dynamic form controls for better user experience
- **Responsive Design**: Accessible on both desktop and mobile devices

## 🛠️ Tech Stack

### Machine Learning
- Python for data preprocessing and model building
- Scikit-learn for implementing the Linear Regression model
- Pandas and NumPy for data manipulation

### Backend
- Flask web framework for API development
- Pickle for model serialization and deployment

### Frontend
- HTML5 for structure
- CSS3 for styling and responsive design
- JavaScript for interactive elements and form handling

## 📥 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/car-price-predictor.git

# Navigate to project directory
cd car-price-predictor

# Create and activate virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

## 🚀 Usage

1. Access the application through your web browser at `http://127.0.0.1:5000/`
2. Enter the required car details:
   - Manufacturer and model
   - Year of manufacture
   - Mileage
   - Fuel type
   - Engine specifications
   - Other relevant features
3. Click "Predict Price" to get an estimated value
4. The predicted price will be displayed on the screen

## 📊 Model Information

### Linear Regression Model
- **Algorithm**: Multiple Linear Regression
- **Features Used**: Car specifications including brand, model, year, mileage, engine capacity, etc.
- **Performance Metrics**:
  - R-squared: [Your R² score]
  - Mean Absolute Error (MAE): [Your MAE]
  - Root Mean Squared Error (RMSE): [Your RMSE]

### Data Preprocessing
- Handling missing values
- Feature encoding for categorical variables
- Feature scaling for numerical variables
- Outlier detection and treatment

## 📁 Project Structure

```
car-price-predictor/
│
├── app.py                  # Flask application
├── model.pkl               # Serialized machine learning model
├── requirements.txt        # Python dependencies
│
├── static/
│   ├── css/
│   │   └── style.css       # CSS styling
│   ├── js/
│   │   └── script.js       # JavaScript functions
│   └── images/             # Project images
│
├── templates/
│   └── index.html          # Main HTML template
│
├── notebooks/
│   └── model_training.ipynb # Jupyter notebook for model development
│
└── data/
    └── car_data.csv        # Dataset used for training
```

## 🔮 Future Improvements

- Implement more advanced machine learning models (Random Forest, XGBoost)
- Add feature importance visualization
- Include price comparison with market trends
- Develop user accounts to save previous predictions
- Add image upload capability for car recognition

## 🙏 Acknowledgements

This project was developed as my first full-stack machine learning application, with guidance and inspiration from the [CampusX](https://github.com/campusx-official) tutorials. Special thanks to the open-source community for providing valuable resources and libraries.

---

## 📬 Contact

For any questions or feedback, please reach out at [your-email@example.com](mailto:your-email@example.com) or connect with me on [LinkedIn](https://www.linkedin.com/in/yourprofile/).

