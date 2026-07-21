# Machine Learning Model Implementations

A collection of **32 machine learning algorithm implementations** in Python using Jupyter Notebooks, organized by category. Each notebook covers data loading, preprocessing, model training, and evaluation.

---

## 📂 Repository Structure

```
.
├── data_pre_processing/
├── Regression/
├── Classification/
├── Clustering/
├── Association_Rule_Learning/
├── Dimensionality Reduction/
├── Deep Learning/
├── Natural Language Processing/
├── Reinforcement Learning/
├── XGBoost/
└── LLM-Fine-Tuning/
```

---

## 🔧 Data Preprocessing

[`data_pre_processing/data_preprocessing_tools.ipynb`](data_pre_processing/data_preprocessing_tools.ipynb)

Covers the foundational preprocessing steps applied across all models:
- Handling missing data
- Encoding categorical variables
- Feature scaling (Standardisation & Normalisation)
- Splitting datasets into training and test sets

---

## 📈 Regression

Supervised learning models for predicting continuous outcomes.

| Algorithm | Notebook |
|-----------|----------|
| Simple Linear Regression | [`simple_linear_regression/simple_linear_regression.ipynb`](Regression/simple_linear_regression/simple_linear_regression.ipynb) |
| Multiple Linear Regression | [`multiple_linear_regression/multiple_linear_regression.ipynb`](Regression/multiple_linear_regression/multiple_linear_regression.ipynb) |
| Polynomial Regression | [`polynomial_regression/polynomial_linear_regression.ipynb`](Regression/polynomial_regression/polynomial_linear_regression.ipynb) |
| Support Vector Regression (SVR) | [`Support_vector_regression/support_vector_regression.ipynb`](Regression/Support_vector_regression/support_vector_regression.ipynb) |
| Decision Tree Regression | [`Decision_Tree_Regression/decision_tree_regression.ipynb`](Regression/Decision_Tree_Regression/decision_tree_regression.ipynb) |
| Random Forest Regression | [`Random_Forest_Regression/random_forest_regression.ipynb`](Regression/Random_Forest_Regression/random_forest_regression.ipynb) |
| Evaluating Regression Models | [`evaluating_regression_models/evaluating_regression_models.ipynb`](Regression/evaluating_regression_models/evaluating_regression_models.ipynb) |

---

## 🏷️ Classification

Supervised learning models for predicting discrete class labels.

| Algorithm | Notebook |
|-----------|----------|
| Logistic Regression | [`Logistic_Regression/logistic_regression.ipynb`](Classification/Logistic_Regression/logistic_regression.ipynb) |
| K-Nearest Neighbors (KNN) | [`K-Nearest_Neighbor/k_nearest_neighbor.ipynb`](Classification/K-Nearest_Neighbor/k_nearest_neighbor.ipynb) |
| Support Vector Machine (Linear) | [`Support_Vector_Machine/support_vector_machine.ipynb`](Classification/Support_Vector_Machine/support_vector_machine.ipynb) |
| Kernel SVM (Non-linear) | [`Kernel_Support_Vector_Machine_non_linear/kernal_svm_non_linear.ipynb`](Classification/Kernel_Support_Vector_Machine_non_linear/kernal_svm_non_linear.ipynb) |
| Naive Bayes | [`Naive_Bayes_Classifiers/naive_bayes.ipynb`](Classification/Naive_Bayes_Classifiers/naive_bayes.ipynb) |
| Decision Tree Classification | [`Decision_Tree_classification/decision_tree_classification.ipynb`](Classification/Decision_Tree_classification/decision_tree_classification.ipynb) |
| Random Forest Classification | [`Random_Forest_Classifier/random_forest_classifier.ipynb`](Classification/Random_Forest_Classifier/random_forest_classifier.ipynb) |
| Evaluating Classification Models | [`evaluating_classifications_models/evaluating_classification_models.ipynb`](Classification/evaluating_classifications_models/evaluating_classification_models.ipynb) |

---

## 🔵 Clustering

Unsupervised learning models for grouping similar data points.

| Algorithm | Notebook |
|-----------|----------|
| K-Means Clustering | [`K_means_Clustering/k_means_clustering.ipynb`](Clustering/K_means_Clustering/k_means_clustering.ipynb) |
| Hierarchical Clustering | [`Hierarchical_Clustering/hierarchical_clustering.ipynb`](Clustering/Hierarchical_Clustering/hierarchical_clustering.ipynb) |

---

## 🛒 Association Rule Learning

Unsupervised methods for discovering interesting relationships between variables in large datasets.

| Algorithm | Notebook |
|-----------|----------|
| Apriori | [`Apriori/apriori.ipynb`](Association_Rule_Learning/Apriori/apriori.ipynb) |
| ECLAT | [`ECLAT_Algorithm/ECLAT_algorithm.ipynb`](Association_Rule_Learning/ECLAT_Algorithm/ECLAT_algorithm.ipynb) |

---

## 📉 Dimensionality Reduction

Techniques for reducing the number of features while retaining important information.

| Algorithm | Notebook |
|-----------|----------|
| Principal Component Analysis (PCA) | [`Principal Component Analysis/principal_component_analysis.ipynb`](<Dimensionality Reduction/Principal Component Analysis/principal_component_analysis.ipynb>) |
| Linear Discriminant Analysis (LDA) | [`Linear Discriminant Analysis/linear_discriminant_analysis.ipynb`](<Dimensionality Reduction/Linear Discriminant Analysis/linear_discriminant_analysis.ipynb>) |
| Kernel PCA | [`KERNEL PCA/kernal_principal_component_analysis.ipynb`](<Dimensionality Reduction/KERNEL PCA/kernal_principal_component_analysis.ipynb>) |

---

## 🧠 Deep Learning

Neural network architectures for complex pattern recognition.

| Architecture | Notebook |
|--------------|----------|
| Artificial Neural Network (ANN) | [`Artificial Neural Network/artificial_neural_network.ipynb`](<Deep Learning/Artificial Neural Network/artificial_neural_network.ipynb>) |
| Convolutional Neural Network (CNN) | [`Convolution Neural Network/convolution_neural_network.ipynb`](<Deep Learning/Convolution Neural Network/convolution_neural_network.ipynb>) |

- **ANN** — applied to bank customer churn prediction (tabular data)
- **CNN** — applied to image classification (cats vs. dogs)

---

## 💬 Natural Language Processing

Text analysis using the Bag of Words model for sentiment classification.

| Topic | Notebook |
|-------|----------|
| Bag of Words & Text Classification | [`natural_language_processing.ipynb`](<Natural Language Processing/natural_language_processing.ipynb>) |

Dataset: Restaurant reviews (`Restaurant_Reviews.tsv`)

---

## 🎰 Reinforcement Learning

Algorithms for sequential decision-making and exploration-exploitation trade-offs.

| Algorithm | Notebook |
|-----------|----------|
| Upper Confidence Bound (UCB) | [`Upper Confidence Bound/upper_confidence_bound.ipynb`](<Reinforcement Learning/Upper Confidence Bound/upper_confidence_bound.ipynb>) |
| Thompson Sampling | [`Thompson Sampling/thompson_sampling.ipynb`](<Reinforcement Learning/Thompson Sampling/thompson_sampling.ipynb>) |

Both algorithms are applied to ad click-through-rate (CTR) optimisation.

---

## ⚡ XGBoost

Extreme Gradient Boosting — a high-performance ensemble method.

| Algorithm | Notebook |
|-----------|----------|
| XGBoost | [`XGBoost/XGBoost.ipynb`](XGBoost/XGBoost.ipynb) |

---

## 🤖 LLM Fine-Tuning

Fine-tuning large language models on domain-specific data.

| Model | Notebook |
|-------|----------|
| TinyLlama (Medical Records) | [`tinyLlama_finetuning_medical_records.ipynb`][https://github.com/yashas224/machine-learning-model-implementations](https://nbsanity.com/static/a75d70df33038e902e17ff4d9fdcd335/tinyLlama_finetuning_medical_records.html)  |

---

## 📊 Summary

| Category | Algorithms | Type |
|----------|-----------|------|
| Data Preprocessing | 1 | Utility |
| Regression | 7 | Supervised |
| Classification | 8 | Supervised |
| Clustering | 2 | Unsupervised |
| Association Rule Learning | 2 | Unsupervised |
| Dimensionality Reduction | 3 | Unsupervised |
| Deep Learning | 2 | Neural Networks |
| Natural Language Processing | 1 | NLP |
| Reinforcement Learning | 2 | Reinforcement Learning |
| XGBoost | 1 | Gradient Boosting |
| LLM Fine-Tuning | 1 | Transfer Learning |
| **Total** | **30** | |

---

## 🛠️ Tech Stack

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Key Libraries:** NumPy, Pandas, Matplotlib, Scikit-learn, TensorFlow/Keras, XGBoost, NLTK, Transformers
