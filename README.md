# **AI-Powered Medical Diagnosis System (P2)**

## **Overview**
The **AI-Powered Medical Diagnosis System (P2)** is a machine learning-based web application designed to predict multiple diseases using patient input data. The system leverages pre-trained models to provide diagnostic predictions for various medical conditions, assisting healthcare professionals in early detection and decision-making.

## **Features**
- **Multi-Disease Prediction**: Supports diagnosis for Diabetes, Heart Disease, Parkinson's, Lung Cancer, and Thyroid disorders.
- **User-Friendly Interface**: Built with Streamlit for easy access and interaction.
- **Machine Learning Models**: Uses pre-trained models for accurate predictions.
- **Secure and Private**: No data storage, ensuring user privacy.
- **Optimized for Performance**: Models are optimized for fast and efficient predictions.

## **Technologies Used**
- **Python**
- **Machine Learning (Scikit-Learn, Pandas, NumPy)**
- **Streamlit** (for Web UI)
- **Pickle** (for model serialization)

## **Project Structure**
```
Medical_Diagnosis_Model/
│── app.py                # Main Streamlit application file
│── Diabetes.ipynb        # Jupyter Notebook for Diabetes model
│── Heart_Disease.ipynb   # Jupyter Notebook for Heart Disease model
│── Parkinsons.ipynb      # Jupyter Notebook for Parkinson’s model
│── Thyroid.ipynb         # Jupyter Notebook for Thyroid model
│── models/               # Contains trained ML models
│── requirements.txt      # Dependencies list
│── README.md             # Project Documentation
```

## **Installation & Setup**
1. **Clone the Repository**
   ```bash
   git clone https://github.com/VishalMA2004/Medical_Diagnosis_Model.git
   cd Medical_Diagnosis_Model
   ```
2. **Create a Virtual Environment (Optional but Recommended)**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```
3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Application**
   ```bash
   streamlit run app.py
   ```

## **Usage**
1. **Select a disease** from the dropdown menu.
2. **Enter the required patient details**.
3. Click **Predict** to get the diagnosis.
4. The system will display whether the patient is at risk or not.

## **Trained Models**
The following trained ML models are used in this project:
- **Diabetes Prediction** (Logistic Regression, Random Forest)
- **Heart Disease Prediction** (SVM, Decision Tree, Random Forest)
- **Parkinson’s Disease Prediction** (XGBoost, SVM)
- **Lung Cancer Prediction** (Random Forest, Logistic Regression)
- **Thyroid Disease Prediction** (Random Forest, Decision Tree)

## **Contributing**
We welcome contributions to improve the project! Feel free to:
- Report bugs
- Suggest enhancements
- Submit pull requests

## **License**
This project is licensed under the **MIT License**.

## **Contact**
For queries, feel free to reach out:
- **GitHub**: [VishalMA2004](https://github.com/VishalMA2004)
- **Email**: [vishalmanickasundaram@gmail.com] (vishalmanickasundaram@gmail.com)

---
**Star ⭐ this repository if you found it useful!**
