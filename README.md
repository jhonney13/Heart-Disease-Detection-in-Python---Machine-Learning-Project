
# ❤️ Heart Disease Detection Using Machine Learning

This project uses machine learning to predict the presence of heart disease based on a variety of medical attributes. The project includes exploratory data analysis, visualizations, model training, and evaluation.

## 📁 Dataset

The dataset used is `heart.csv`, containing 303 records with the following features:

- `age`: Age of the patient
- `sex`: Sex (1 = male; 0 = female)
- `cp`: Chest pain type (4 values)
- `trestbps`: Resting blood pressure (in mm Hg)
- `chol`: Serum cholesterol in mg/dl
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
- `restecg`: Resting electrocardiographic results
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina
- `oldpeak`: ST depression induced by exercise
- `slope`: The slope of the peak exercise ST segment
- `ca`: Number of major vessels (0–3) colored by fluoroscopy
- `thal`: Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect)
- `target`: Presence of heart disease (1 = yes; 0 = no)



## 🧠 **Models Used**

The following machine learning models are used:

1.  **Decision Tree Classifier**
    
2.  **Gaussian Naive Bayes**
    
3.  **Support Vector Machine (SVM)**

Each model is evaluated using accuracy, confusion matrix, and classification reports.

## 📊 **How Performance is Measured**

Each model's performance is evaluated using:

*   **Accuracy Score**: Measures how many predictions were correct.
    
*   **Confusion Matrix**: Visual representation of true vs predicted values.
    
*   **Classification Report**: Includes:
    
    *   **Precision**
        
    *   **Recall**
        
    *   **F1-Score**

## 🏆 Best Model

The **Decision Tree Classifier** performed best with an accuracy of approximately **98.54%**.

## 🛠️ Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🚀 Run the Notebook

```bash
jupyter notebook Heart_Disease_Detection_in_Python_Machine_Learning_Project.ipynb
```

## 📬 Contact

Made with ❤️ by [Vipul Singh](https://github.com/jhonney13)  
For any queries or collaborations, feel free to reach out!
