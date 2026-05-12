**Classification of Healthcare Data using Random Forest Algorithm**

**Project Overview**

This project focuses on the classification of healthcare data using the **Random Forest Algorithm**, a supervised Machine Learning technique. The system predicts disease outcomes based on patient-related healthcare information such as symptoms and medical attributes.

The project was developed as part of an internship to understand Machine Learning concepts, including **classification, regression, data preprocessing, model training, and prediction**.

---

**Objectives**

- Understand Machine Learning concepts and workflow  
- Apply classification techniques to healthcare data  
- Perform effective data preprocessing  
- Build a prediction model using the Random Forest algorithm  
- Predict healthcare outcomes based on patient data

---

**Machine Learning Concept Used**

**Random Forest Algorithm**
Random Forest is a **supervised learning algorithm** used for both **classification and regression** tasks. It combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

**Dataset Information**

The dataset contains healthcare-related patient information such as:

- Age  
- Fever  
- Cough  
- Blood Pressure  
- Cholesterol Level  
- Other medical attributes  

**Target Variable**
- **Outcome Variable**
  - Positive  
  - Negative

---

**Methodology**

The project follows the following workflow:

**Dataset → Data Preprocessing → Feature Encoding → Model Training → Prediction → Output**

**Steps Performed:**
1. Data collection from healthcare dataset  
2. Data preprocessing and cleaning  
3. Feature encoding using `get_dummies()`  
4. Splitting dataset into training and testing sets  
5. Training model using Random Forest Classifier  
6. Saving trained model using `pickle`  
7. Predicting healthcare outcomes

---

**Technologies Used**

- **Python**
- **Pandas**
- **Scikit-learn**
- **Streamlit**
- **Pickle**

---

**Project Structure**

```text
ml_project/
│── app.py
│── requirements.txt
│── data/
│   └── dataset.csv
│── results/
│   ├── model.pkl
│   └── columns.pkl
│── src/
│   └── train_model.py
```

---

**How to Run the Project**

**1. Clone Repository**

```bash
git clone YOUR_GITHUB_LINK
```

2. Install Required Libraries

```bash
pip install -r requirements.txt
```

3. Run Streamlit Application

```bash
streamlit run app.py
```

---

**Output**

The system predicts disease outcomes as:

- **Positive**
- **Negative**

It also provides a **prediction probability (%)** to indicate confidence level.

---

## Learning Outcomes

Through this project, the following concepts were learned:

- Machine Learning workflow  
- Classification and Regression  
- Data preprocessing techniques  
- Model training and evaluation  
- Random Forest algorithm implementation

---

## Author

**MD AZAM**  
B.Sc Computer Science   
Central University of Karnataka

---

## 🙏 Acknowledgment

Special thanks to my mentor and faculty members for their guidance and support during the internship.
