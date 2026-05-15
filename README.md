# 🍷 Wine Quality Prediction System — Machine Learning Model  

 


## 📘 Project Description  
The **Wine Quality Prediction System** is a Machine Learning-based project that predicts the **quality of wine** based on its **physicochemical properties** such as **Fixed Acidity, Volatile Acidity, Citric Acid, Residual Sugar, Chlorides, Free Sulfur Dioxide, Total Sulfur Dioxide, Density, pH, Sulphates, and Alcohol**.  

Using a **Random Forest Classifier**, the model achieved an impressive **accuracy of 93%**, making it highly effective for quality assessment and classification tasks.  

A detailed **Exploratory Data Analysis (EDA)** was performed to visualize correlations and determine which factors most influence wine quality.  
This project demonstrates how **machine learning** can assist in **food and beverage quality control**, supporting consistency and product improvement in the wine industry.  

---

## 🔍 About the Project  
This project highlights the real-world use of **supervised learning classification algorithms** in **food and beverage analytics**.  
By examining multiple chemical attributes, the model provides **accurate wine quality predictions**, helping producers maintain optimal quality standards and improve product formulation.  

---

## 🧠 Model Architecture  
The project uses a **Random Forest Classifier**, a robust ensemble learning algorithm that combines multiple decision trees to achieve high performance and reduce overfitting.  

* **Algorithm:** Random Forest Classifier  
* **Problem Type:** Multi-class Classification  
* **Evaluation Metrics:** Accuracy, Confusion Matrix, Feature Importance  

---

## 🧾 Dataset Description  
The dataset consists of physicochemical properties (inputs) and a quality score (output), allowing the model to learn patterns that distinguish high-quality wines.  

| Feature Name               | Description |
| :-------------------------- | :------------------------------------------------------------ |
| `fixed acidity`             | Amount of tartaric acid present in the wine |
| `volatile acidity`          | Amount of acetic acid that affects taste |
| `citric acid`               | Contributes to wine freshness and flavor |
| `residual sugar`            | Remaining sugar after fermentation |
| `chlorides`                 | Salt content in the wine |
| `free sulfur dioxide`       | Prevents microbial growth |
| `total sulfur dioxide`      | Sum of free and bound sulfur dioxide |
| `density`                   | Affected by sugar and alcohol concentration |
| `pH`                        | Indicates acidity level |
| `sulphates`                 | Adds to wine preservation and flavor |
| `alcohol`                   | Alcohol percentage in wine |
| `quality`                   | Output variable (rating between 0–10) |

---

## ⚙️ Tech Stack & Libraries  

**Language:**  
* Python 🐍  

**Libraries:**  
* **NumPy** – Numerical computations  
* **Pandas** – Data manipulation and cleaning  
* **Scikit-learn** – Model building and evaluation  
* **Matplotlib / Seaborn** – Data visualization and EDA  

---

## 🚀 Features  
* Predicts **wine quality** based on 11 key physicochemical factors  
* Performs detailed **EDA** to explore correlations and feature importance  
* Utilizes **Random Forest Classifier** for high accuracy and reliability  
* Achieves **93% model accuracy** on test data  
* Applicable for **industrial quality testing and research analysis**  

---

## 📊 Results  
The **Random Forest Classifier** achieved a **93% accuracy**, proving to be an efficient model for wine quality classification based on chemical composition.  

---

## 📁 Repository Structure  

```
📦 ML_Project_Wine_Quality_Prediction
│
├── Wine_Quality_Prediction.ipynb                                        # Complete Jupyter Notebook implementation
├── winequality-red.csv                                                  # Dataset used for training and testing
└── README.md                                                            # Project documentation

```

---

## 🧪 How to Run  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/ms00000ms0000/ML-Project-Wine-Quality-Prediction.git
   cd ML-Project-Wine-Quality-Prediction
   ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the notebook:**

   ```bash
   jupyter notebook wine_quality_prediction.ipynb
   ```

4. **Execute all cells to train, test, and evaluate the model.**

---

## 📈 Future Improvements

* Add hyperparameter tuning using GridSearchCV for optimal performance

* Integrate a Streamlit-based user interface for real-time predictions

* Experiment with Neural Networks or Gradient Boosting for comparison

---

## 👨‍💻 Developer

Developed by: Mayank Srivastava
