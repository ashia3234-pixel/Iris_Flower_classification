# 🌸 Iris Flower Classification using Streamlit

A Machine Learning web application that predicts the species of an Iris flower based on its sepal and petal measurements. Built using **Python**, **Scikit-learn**, and **Streamlit**, with a **Random Forest Classifier** trained on the Iris dataset.

---

## ⚡ Live App

🔗 [Click here to open the app](https://irisflowerclassification-h36fv6bzntu8aqxuqbeyaz.streamlit.app/)

---

## 📌 Project Overview

This project demonstrates the complete machine learning workflow:

- Load and explore the Iris dataset
- Train a Random Forest Classifier
- Evaluate model performance
- Save the trained model using Joblib and Pickle
- Deploy the model as an interactive Streamlit web application

---

## 🚀 Features

- 🌸 Predict Iris flower species (Setosa, Versicolor, Virginica)
- 🎛️ Interactive sliders for feature input
- 🤖 Random Forest Machine Learning model
- 📊 Prediction confidence scores
- 💾 Model saved using Joblib and Pickle
- ⚡ Fast and interactive Streamlit interface

---

## 🛠️ Technologies Used

- Python
- Streamlit
- NumPy
- Pandas
- Scikit-learn
- Joblib
- Matplotlib
- Pillow

---

## 📂 Project Structure

```
Iris_Flower_classification/
│
├── app.py
├── train_model.py
├── requirements.txt
├── runtime.txt
├── .python-version
├── .gitignore
│
└── models/
    ├── iris_model.joblib
    ├── iris_model.pickle
    ├── model_info.json
    └── feature_ranges.json
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/ashia3234-pixel/Iris_Flower_classification.git
```

Move into the project folder:

```bash
cd Iris_Flower_classification
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Train the model:

```bash
python train_model.py
```

Run the Streamlit application:

```bash
streamlit run app.py
```

---

## 📊 Machine Learning Model

- **Algorithm:** Random Forest Classifier
- **Dataset:** Iris Dataset (built into Scikit-learn)
- **Input Features:**
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
- **Predicted Classes:**
  - Setosa
  - Versicolor
  - Virginica

---

## 👩‍💻 Author

**Ashiba .C**
Computer Science Student

---

## 📄 License

This project is created for educational purposes.
