# 🍎 Food Product Classification

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-1.40.1-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

##  Description

This project aims to **predict whether a food product is healthy or unhealthy** using data from the **OpenFoodFacts dataset**.

The project follows a complete **machine learning workflow**, including:

* **Data preprocessing** (cleaning, feature selection, normalization)
* **Training a supervised classification model** using `RandomForestClassifier`
* **Model performance evaluation**
* **Interactive Streamlit application** allowing users to test new food products and visualize predictions in real time

---

##  Project Objectives

This project aims to:

* Help consumers make **more informed food choices**
* Contribute to scientific understanding of the **long-term impacts of food consumption** on health, environment, and society
* Assist food producers in **identifying and improving the quality of their products**
* Empower individuals, researchers, startups, and organizations to **address global food system challenges**
* Support policymakers in developing **effective public health strategies**

---

##  Repository Structure

* `Classification_Des_Produits_Alimentaires_Final.ipynb`
  Main notebook containing all stages of the project: data preprocessing, model training, and evaluation.

* `streamlit_app.py`
  Streamlit web application used to interact with the trained model and test predictions.

* `requirements.txt`
  Contains all required Python dependencies for running the project.

* `images/`
  Project illustrations and visual assets.

* `model/`
  Trained machine learning model and related files.

---

##  Requirements

To run this project, install the following dependencies:

```
joblib==1.3.2
numpy==1.24.4
pandas==2.0.3
Pillow==11.1.0
scikit_learn==1.0.2
streamlit==1.40.1
```

Install them using:

```bash
pip install -r requirements.txt
```

---

##  Run the Application

To launch the Streamlit application:

```bash
streamlit run streamlit_app.py
```

The application will open in your browser, allowing you to **test predictions for new food products**.

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Joblib

---

##  Dataset

The dataset used in this project comes from **OpenFoodFacts**, an open database containing nutritional information about food products worldwide.

🔗 https://world.openfoodfacts.org
