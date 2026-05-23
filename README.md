\# 🍔 NutriClass Project  

\## Food Classification Using Nutritional Data and Machine Learning



!\[Python](https://img.shields.io/badge/Python-3.13-blue)

!\[Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)

!\[Status](https://img.shields.io/badge/Project-Completed-brightgreen)

!\[License](https://img.shields.io/badge/License-MIT-lightgrey)



\---



\# 📌 Project Overview



NutriClass is an end-to-end Machine Learning project designed to classify food items based on their nutritional values.  

The project uses multiple machine learning algorithms to analyze nutritional features such as calories, protein, fat, carbohydrates, sugar, sodium, cholesterol, glycemic index, and serving size.



The primary objective of this project is to build an accurate food classification system capable of predicting food categories from nutritional information.



This project demonstrates:

\- Data preprocessing

\- Exploratory Data Analysis (EDA)

\- Feature engineering

\- Dimensionality reduction using PCA

\- Model training and evaluation

\- Cross-validation

\- Feature importance analysis

\- Model persistence using Pickle



\---



\# 🚀 Technologies Used



\- Python

\- Jupyter Notebook

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Scikit-learn

\- XGBoost



\---



\# 📂 Project Structure



```bash

NutriClass\_Project/

│

├── data/

│   └── synthetic\_food\_dataset\_imbalanced.csv

│

├── notebooks/

│   └── NutriClass\_Project.ipynb

│

├── outputs/

│   ├── models/

│   │   └── svm\_model.pkl

│   │

│   ├── plots/

│   │   ├── correlation\_heatmap.png

│   │   ├── feature\_importance.png

│   │   ├── model\_accuracy\_comparison.png

│   │   └── pca\_visualization.png

│   │

│   └── reports/

│       └── NutriClass\_Project.pdf

│

└── README.md

```



\---



\# 📊 Dataset Information



The dataset contains nutritional information for different food categories.



\### Features Used



| Feature | Description |

|---|---|

| Calories | Total calorie content |

| Protein | Protein amount |

| Fat | Fat content |

| Carbs | Carbohydrates |

| Sugar | Sugar level |

| Fiber | Fiber content |

| Sodium | Sodium amount |

| Cholesterol | Cholesterol level |

| Glycemic\_Index | Glycemic index value |

| Water\_Content | Water percentage |

| Serving\_Size | Serving size |

| Meal\_Type | Type of meal |

| Preparation\_Method | Cooking method |

| Is\_Vegan | Vegan indicator |

| Is\_Gluten\_Free | Gluten-free indicator |



\### Target Variable



\- `Food\_Name`



\---



\# ⚙️ Machine Learning Workflow



The project follows a complete machine learning pipeline:



\## 1️⃣ Data Preprocessing

\- Missing value handling

\- Duplicate removal

\- Outlier treatment using IQR method

\- Label encoding

\- Feature scaling using StandardScaler



\---



\## 2️⃣ Exploratory Data Analysis (EDA)

\- Statistical summary

\- Distribution analysis

\- Histograms

\- Correlation heatmap

\- Food category distribution



\---



\## 3️⃣ Dimensionality Reduction

\- PCA (Principal Component Analysis)



\---



\## 4️⃣ Machine Learning Models Used



The following models were trained and evaluated:



\- Logistic Regression

\- Decision Tree

\- Random Forest

\- K-Nearest Neighbors (KNN)

\- Support Vector Machine (SVM)

\- XGBoost

\- Gradient Boosting



\---



\# 🏆 Best Performing Model



After comparing all models, \*\*SVM (Support Vector Machine)\*\* achieved the highest performance.



\### Final SVM Accuracy



```text

Accuracy: 99.42%

```



\---



\# 📈 Model Performance Comparison



| Model | Accuracy |

|---|---|

| SVM | 99.42% |

| Gradient Boosting | 99.35% |

| Random Forest | 99.33% |

| XGBoost | 99.30% |

| Logistic Regression | 99.20% |

| KNN | 99.13% |

| Decision Tree | 98.48% |



\---



\# 📷 Visualizations



\## 📌 PCA Visualization



!\[PCA Visualization](outputs/plots/pca\_visualization.png)



\---



\## 📌 Correlation Heatmap



!\[Correlation Heatmap](outputs/plots/correlation\_heatmap.png)



\---



\## 📌 Model Accuracy Comparison



!\[Model Accuracy Comparison](outputs/plots/model\_accuracy\_comparison.png)



\---



\## 📌 Feature Importance



!\[Feature Importance](outputs/plots/feature\_importance.png)



\---



\# 🔍 Cross Validation



Cross-validation was performed using 5-fold validation to ensure model reliability and stability.



\### Average Cross Validation Score



```text

0.9928

```



\---



\# 💾 Saved Model



The final trained SVM model was saved using Pickle.



\### Saved File



```bash

outputs/models/svm\_model.pkl

```



\---



\# ▶️ How to Run the Project



\## Step 1: Clone the Repository



```bash

git clone https://github.com/rajdeepsen97/NutriClass\_Project.git

```



\---



\## Step 2: Navigate to Project Folder



```bash

cd NutriClass\_Project

```



\---



\## Step 3: Install Dependencies



```bash

pip install -r requirements.txt

```



\---



\## Step 4: Launch Jupyter Notebook



```bash

jupyter notebook

```



\---



\## Step 5: Open Notebook



Open:



```bash

notebooks/NutriClass\_Project.ipynb

```



\---



\# 📌 Future Improvements



Possible future enhancements:

\- Deep Learning implementation

\- Real-world food dataset integration

\- Web application deployment using Flask or Streamlit

\- API integration

\- Real-time food recommendation system



\---



\# 👨‍💻 Author



\### Rajdeep Sen



Machine Learning Enthusiast | Data Science Learner



\---



\# 📄 License



This project is licensed under the MIT License.



\---



\# ⭐ Acknowledgements



Special thanks to:

\- Scikit-learn

\- XGBoost

\- Open-source Python community



\---

