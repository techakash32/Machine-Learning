# 🤖 Machine Learning Practice

> A personal repository where I learn and practice core **Machine Learning** concepts — from data preprocessing and feature engineering to building pipelines — using Python and scikit-learn.

---

## 🗂️ Repository Structure

```
machine-learning/
notebooks/
│   ├── 1_standard_deviation.ipynb
│   ├── 2_standard_deviation.ipynb
│   ├── 3_minmax_scaler.ipynb
│   ├── 4_minmax_scaler.ipynb
│   ├── 5_label_encoding.ipynb
│   ├── 6_ALL_encoding.ipynb
│   ├── 7_practic_encoding.ipynb
│   ├── 8_Transformer.ipynb
│   ├── 9_Function_transformer.ipynb
│   ├── 10_pipelines_creating.ipynb
│   └── 11_comple_case_analysis.ipynb
│
|
|
└── README.md
```

---

## 📓 Notebooks Overview

| # | Notebook | Topic | Key Concepts |
|---|----------|-------|--------------|
| 1 | `1_standard_deviation.ipynb` | Statistics Basics | Mean, variance, std deviation, normal distribution |
| 2 | `2_standard_deviation.ipynb` | Standard Deviation Practice | Z-score, spread of data, StandardScaler intro |
| 3 | `3_minmax_scaler.ipynb` | Min-Max Scaling | Normalizing features to [0, 1] range |
| 4 | `4_minmax_scaler.ipynb` | Min-Max Scaler Practice | Applied scaling on real datasets |
| 5 | `5_label_encoding.ipynb` | Label Encoding | Converting categorical text to numbers |
| 6 | `6_ALL_encoding.ipynb` | All Encoding Techniques | LabelEncoder, OrdinalEncoder, OneHotEncoder |
| 7 | `7_practic_encoding.ipynb` | Encoding Practice | End-to-end encoding on mixed datasets |
| 8 | `8_Transformer.ipynb` | Column Transformer | Applying different transforms to different columns |
| 9 | `9_Function_transformer.ipynb` | Function Transformer | Custom transformations using `FunctionTransformer` |
| 10 | `10_pipelines_creating.ipynb` | ML Pipelines | Building end-to-end `Pipeline` with preprocessing + model |
| 11 | `11_comple_case_analysis.ipynb` | Complete Case Analysis | Handling missing data by dropping incomplete rows |

---

## 🧠 Topics Covered

### 📐 Feature Scaling
- **Standard Deviation & Z-score Normalization** — center data around mean with unit variance
- **Min-Max Scaling** — rescale features to a fixed range [0, 1]
- When to use `StandardScaler` vs `MinMaxScaler`

### 🏷️ Encoding Categorical Data
- **Label Encoding** — assign integer labels to categories
- **Ordinal Encoding** — encode ordered categories
- **One-Hot Encoding** — binary columns for each category
- Choosing the right encoder for nominal vs ordinal data

### 🔧 Transformers
- **ColumnTransformer** — apply different preprocessing to numeric and categorical columns simultaneously
- **FunctionTransformer** — wrap any custom Python function as a scikit-learn transformer

### 🔁 Pipelines
- Chaining preprocessing steps and a model into a single `Pipeline` object
- Avoiding data leakage by fitting only on training data
- Making predictions with a single `.predict()` call

### 🗃️ Missing Data
- **Complete Case Analysis (CCA)** — understanding when and why to drop rows with nulls
- Impact of missing data on model performance

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Core language |
| scikit-learn | Scalers, encoders, transformers, pipelines |
| Pandas | Data manipulation |
| NumPy | Numerical computing |
| Matplotlib / Seaborn | Visualizations |
| Jupyter Notebook | Interactive learning environment |

---

## ⚙️ Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/machine-learning.git
cd machine-learning
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter
```bash
jupyter notebook
```

---

## 📦 requirements.txt

```
scikit-learn
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## 💡 Key Learnings

- Scaling features is **critical** before distance-based or gradient-based models
- **Label Encoding** should not be used for nominal categories with tree-free models — use One-Hot instead
- `ColumnTransformer` keeps your preprocessing **clean and reproducible**
- `Pipeline` prevents **data leakage** and makes deployment-ready code
- **Complete Case Analysis** is simple but can introduce bias if data is not missing completely at random (MCAR)

---

## 🔮 What's Next

- [ ] Linear & Logistic Regression from scratch
- [ ] Decision Trees and Random Forests
- [ ] Cross-validation and Hyperparameter Tuning
- [ ] Model Evaluation Metrics (Precision, Recall, F1, ROC-AUC)
- [ ] Feature Selection techniques
- [ ] Handling imbalanced datasets (SMOTE, class weights)

---

## 📄 License

This repository is for **personal learning and practice**.  
Feel free to fork it and use it for your own ML journey!

---

## 🙋‍♂️ Author

**AKASH**  
Learning Machine Learning one notebook at a time. 🚀  
[GitHub](https://github.com/your-username) · [LinkedIn](https://linkedin.com/in/your-profile)
