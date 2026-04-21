# Predicting Shopping Preferences

## Project Description
This project aims to predict customer shopping preferences (Online, Store, or Hybrid) using various machine learning models, including Support Vector Machine (SVM), Gaussian Naive Bayes, and Logistic Regression. It includes data loading, exploratory data analysis (EDA), preprocessing (feature encoding and scaling), model development, hyperparameter tuning with GridSearchCV, and performance evaluation, including confusion matrix and ROC curves. A Gradio interface is also integrated for interactive predictions using the SVM model.

## How to Run the Code
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/eimoehtet/shopping-preferences-prediction.git
    cd shopping-preferences-prediction
    ```
2.  **Install dependencies:**
    It's recommended to create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```
3.  **Run the Jupyter/Colab Notebook:**
    Open the provided `.ipynb` file in Google Colab or a local Jupyter environment. Execute all cells sequentially.
    
    *Note: If running in Google Colab, ensure you are connected to a GPU runtime if desired, and grant drive access if prompted.*

## Libraries Required
All necessary Python libraries are listed in `requirements.txt`. Install them using:
```bash
pip install -r requirements.txt
```

## Algorithm Implementation Summary
*   **Support Vector Machine (SVM):** Implemented by Ei Moe Htet
*   **Logistic Regression:** Implemented by TO RYSHA
*   **Gaussian Naive Bayes:** Implemented by Min Kywal Htet Oo (Stan)
