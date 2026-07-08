![Skills_Network](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-PY0221EN-Coursera/images/image.png)

<h1 align="center">Machine Learning with Python</h1>

This repository contains a structured collection of Jupyter Notebooks developed while working through the IBM **Machine Learning with Python** learning path. The notebooks demonstrate the full applied machine learning workflow: preparing data, splitting datasets into training and testing subsets, building supervised and unsupervised models, evaluating performance, tuning hyperparameters, and interpreting results through statistical metrics and visual tools.

The repository includes two main project notebooks in the root folder: **Australian rainfall prediction** and **Titanic survival prediction**. The remaining notebooks are organised inside the **Jupyter Notebooks** folder as supporting laboratories covering regression, classification, clustering, dimensionality reduction, model evaluation, pipelines, and ensemble learning.

<h1 align="center"><i>Notebooks Overview</i></h1>

* [**Final Project – Australian Rainfall Prediction**](FinalProject_AUSWeather.ipynb)

This is the main final project of the repository. It builds a classification model to predict whether it will rain tomorrow using Australian weather observations. The notebook applies data cleaning, feature selection, leakage analysis, train-test splitting, preprocessing pipelines, model training, prediction, and classification evaluation. It uses methods such as `LogisticRegression`, `RandomForestClassifier`, `Pipeline`, `StandardScaler`, `GridSearchCV`, confusion matrices, and classification reports to compare predictive performance.

* [**Practice Project – Titanic Survival Prediction**](Practice%20Project.ipynb)

This project applies machine learning to the Titanic survival dataset. It uses passenger attributes to predict survival outcomes and introduces the practical end-to-end classification workflow: selecting relevant features, dropping leakage-prone or irrelevant variables, splitting data into training and testing sets, building models, evaluating classification metrics, and comparing the final model against earlier approaches. It includes Logistic Regression, K-Nearest Neighbours, Random Forest, PCA, pipelines, GridSearchCV, confusion matrices, and classification reports.

* [**Simple Linear Regression**](Jupyter%20Notebooks/Simple-Linear-Regression.ipynb)

This notebook introduces Simple Linear Regression using a fuel consumption dataset. It focuses on modelling the relationship between one predictor and one continuous target variable, such as estimating emissions from engine size. It covers exploratory visualisation, train-test splitting, model fitting, coefficient interpretation, prediction, and regression evaluation through metrics such as Mean Squared Error and R-squared.

* [**Multiple Linear Regression**](Jupyter%20Notebooks/Mulitple-Linear-Regression.ipynb)

This notebook extends linear regression to several input variables. It demonstrates how multiple vehicle characteristics can be used together to predict a continuous outcome. The notebook applies feature selection, standardisation, train-test splitting, multiple regression fitting, coefficient interpretation, and prediction visualisation.

* [**Regularisation in Linear Regression**](Jupyter%20Notebooks/Regularization_in_LinearRegression.ipynb)

This notebook compares Ordinary Linear Regression, Ridge Regression, and Lasso Regression. It shows how regularisation can reduce overfitting, stabilise models affected by outliers, and control excessively large coefficients. The notebook is especially useful for understanding why penalty terms are added to regression models when the data contains noise, multicollinearity, or high-dimensional feature spaces.

* [**Regression Trees – Taxi Tip Prediction**](Jupyter%20Notebooks/Regression_Trees_Taxi_Tip.ipynb)

This notebook introduces Decision Tree Regression for predicting taxi tips. Instead of fitting a straight-line equation, a regression tree divides the feature space into branches and predicts numerical values from terminal leaves. It is useful for modelling non-linear relationships and interactions between features.

* [**Evaluating Random Forest Performance**](Jupyter%20Notebooks/Evaluating_random_forest.ipynb)

This notebook uses Random Forest Regression on the California Housing dataset. It demonstrates train-test splitting, exploratory inspection, model training, prediction, evaluation with MSE and R-squared, feature importance analysis, and the interpretation of ensemble models. It also introduces the idea that several trees can be combined to produce stronger and more stable predictions.

* [**Random Forests and XGBoost**](Jupyter%20Notebooks/Random_%20Forests%20_XGBoost.ipynb)

This notebook compares Random Forest and XGBoost models for regression performance. It evaluates both models using predictive metrics and timing comparisons, showing how ensemble methods can be compared not only by accuracy but also by computational efficiency.

* [**Logistic Regression**](Jupyter%20Notebooks/Logistic_Regression.ipynb)

This notebook introduces Logistic Regression for binary classification using a customer churn scenario. It covers preprocessing, feature scaling, train-test splitting, model fitting, probability prediction, class prediction, and performance evaluation with metrics such as accuracy, Jaccard score, F1-score, log loss, and confusion matrix analysis.

* [**K-Nearest Neighbours Classification**](Jupyter%20Notebooks/KNN_Classification.ipynb)

This notebook uses K-Nearest Neighbours for classification. It demonstrates how predictions can be made by comparing a new observation with nearby observations in the feature space. It covers feature normalisation, train-test splitting, fitting a KNN classifier, selecting the number of neighbours, and evaluating predictive accuracy.

* [**Decision Trees**](Jupyter%20Notebooks/Decision_trees.ipynb)

This notebook introduces Decision Tree Classification. It explains how a tree-based classifier splits data into decision rules, trains on labelled observations, predicts class labels, evaluates accuracy, and visualises the final tree. Decision trees are useful when interpretability and rule-based prediction are important.

* [**Credit Card Fraud Detection with Decision Trees and SVM**](Jupyter%20Notebooks/decision_tree_svm_ccFraud.ipynb)

This notebook applies classification models to credit card fraud detection. It compares Decision Trees and Support Vector Machines in an imbalanced, high-risk classification scenario. It introduces the importance of scaling, train-test splitting, fraud detection metrics, and ROC-AUC evaluation when the minority class is especially important.

* [**Evaluating Classification Models**](Jupyter%20Notebooks/Evaluating%20Classification%20Models.ipynb)

This notebook focuses on classification evaluation using models such as KNN and SVM. It uses the Breast Cancer dataset, standardisation, controlled noise, prediction, confusion matrices, classification reports, and accuracy comparisons to show how different classifiers behave under realistic data conditions.

* [**Multi-class Classification**](Jupyter%20Notebooks/Multi-class_Classification.ipynb)

This notebook extends classification beyond two classes. It demonstrates preprocessing, feature scaling, one-hot encoding, train-test splitting, Logistic Regression for multiple classes, prediction, accuracy evaluation, and interpretation of multi-class outputs.

* [**Machine Learning Pipelines and GridSearchCV**](Jupyter%20Notebooks/ML_Pipelines_and_GridSearchCV.ipynb)

This notebook introduces scikit-learn pipelines and hyperparameter tuning. It combines preprocessing steps such as `StandardScaler` and `PCA` with a `KNeighborsClassifier`, then uses `GridSearchCV` to test multiple parameter combinations. It also demonstrates prediction, confusion matrix generation, and systematic model selection.

* [**K-Means Customer Segmentation**](Jupyter%20Notebooks/K-Means-Customer-Seg.ipynb)

This notebook introduces K-Means clustering for customer segmentation. It applies unsupervised learning to group customers according to similarities in their attributes. The notebook covers scaling, fitting clusters, assigning cluster labels, and interpreting customer groups without using a target variable.

* [**Evaluating K-Means Clustering**](Jupyter%20Notebooks/Evaluating_k-means_clustering.ipynb)

This notebook focuses on evaluating K-Means clustering. It uses synthetic blob data to explore cluster stability, number of clusters, inertia, silhouette score, and visual inspection. It demonstrates why clustering must be evaluated differently from supervised models because no true target label is always available.

* [**Comparing DBSCAN and HDBSCAN**](Jupyter%20Notebooks/Comparing_DBScan_HDBScan.ipynb)

This notebook compares density-based clustering methods. It applies DBSCAN and HDBSCAN to geographical and cultural facility data, showing how density-based methods can discover irregular clusters and identify noise points. It is especially useful for spatial clustering and datasets where clusters are not spherical.

* [**Principal Component Analysis**](Jupyter%20Notebooks/PCA.ipynb)

This notebook introduces PCA as a dimensionality reduction technique. It explains how high-dimensional data can be projected onto fewer components while preserving as much variance as possible. PCA is used for visualisation, compression, noise reduction, and preparing data for models that benefit from fewer correlated features.

* [**Comparing t-SNE and UMAP Dimension Reduction Models**](Jupyter%20Notebooks/tSNE_UMAP.ipynb)

This notebook compares t-SNE and UMAP for non-linear dimensionality reduction. It uses synthetic clustered data and visual projections to show how complex high-dimensional patterns can be represented in two dimensions. These techniques are especially useful for visualising clusters, embeddings, and complex feature spaces.

<h1 align="center"><i>Technical Methodologies and Mathematical Foundations</i></h1>

## 1. Supervised and Unsupervised Learning

The repository covers both supervised and unsupervised machine learning.

In **supervised learning**, the model learns from input-output pairs:

$$
(X, y)
$$

where \(X\) represents the feature matrix and \(y\) represents the target variable. If \(y\) is numerical, the task is regression. If \(y\) is categorical, the task is classification.

In **unsupervised learning**, there is no target variable. The model studies the structure of the feature matrix \(X\) alone. Clustering and dimensionality reduction are examples of unsupervised learning methods.

These notebooks therefore cover three major machine learning objectives:

* predicting continuous values through regression;
* predicting class labels through classification;
* discovering hidden structure through clustering and dimensionality reduction.

## 2. Feature Matrix and Target Vector

Most notebooks represent data as a feature matrix:

$$
X =
\begin{bmatrix}
x_{11} & x_{12} & \dots & x_{1p} \\
x_{21} & x_{22} & \dots & x_{2p} \\
\vdots & \vdots & \ddots & \vdots \\
x_{n1} & x_{n2} & \dots & x_{np}
\end{bmatrix}
$$

where \(n\) is the number of observations and \(p\) is the number of features.

For supervised learning, the target variable is represented as:

$$
y =
\begin{bmatrix}
y_1 \\
y_2 \\
\vdots \\
y_n
\end{bmatrix}
$$

In the Australian weather project, the target is whether it will rain tomorrow. In the Titanic project, the target is whether a passenger survived. In regression notebooks, the target may be a continuous value such as fuel consumption, CO2 emissions, house price, or taxi tip amount.

## 3. Data Preprocessing and Feature Engineering

Before fitting a machine learning model, the notebooks apply preprocessing steps such as cleaning missing values, selecting useful variables, converting categorical variables into numerical format, removing leakage-prone features, and scaling numerical values.

Feature engineering transforms raw data into model-ready inputs. In the weather project, this includes selecting meteorological features and considering temporal or location-related variables. In the Titanic project, it includes selecting passenger characteristics and removing variables that either do not help prediction or may create leakage.

A common preprocessing transformation is standardisation:

$$
z = \frac{x - \mu}{\sigma}
$$

where \(x\) is the original value, \(\mu\) is the mean, and \(\sigma\) is the standard deviation. Standardisation is especially important for algorithms based on distance, margins, or regularisation, such as KNN, SVM, Logistic Regression, PCA, t-SNE, UMAP, and Ridge or Lasso Regression.

## 4. Data Leakage

Data leakage occurs when a model is trained with information that would not be available at the time of prediction. This can make model performance appear unrealistically high.

For example, if the goal is to predict tomorrow's rain, any feature that directly or indirectly contains tomorrow's weather outcome would leak future information into the model. Similarly, in a survival prediction problem, a variable recorded after the event would not be valid for prediction.

The mathematical danger of leakage is that the model learns from information correlated with the target for artificial reasons. As a result, the estimated test score no longer represents real generalisation performance.

## 5. Train-Test Split

The notebooks use train-test splitting to estimate how well a model performs on unseen data. The dataset is divided into:

* a **training set**, used to fit the model;
* a **testing set**, used to evaluate the model after training.

This can be expressed as:

$$
D = D_{train} \cup D_{test}
$$

where the two subsets should not overlap:

$$
D_{train} \cap D_{test} = \varnothing
$$

Train-test splitting is used in regression, classification, and ensemble modelling notebooks. It is essential for measuring generalisation rather than memorisation.

## 6. Simple Linear Regression

Simple Linear Regression models the relationship between one input feature and one continuous target variable:

$$
\hat{y} = \beta_0 + \beta_1x
$$

where \(\hat{y}\) is the predicted value, \(\beta_0\) is the intercept, and \(\beta_1\) is the coefficient of the input feature.

The model chooses coefficients that minimise the residual sum of squares:

$$
RSS = \sum_{i=1}^{n}(y_i - \hat{y}_i)^2
$$

This method is used when the goal is to predict a numerical value from one main explanatory variable, such as estimating CO2 emissions from engine size.

## 7. Multiple Linear Regression

Multiple Linear Regression extends linear regression to several features:

$$
\hat{y} = \beta_0 + \beta_1x_1 + \beta_2x_2 + \dots + \beta_px_p
$$

In matrix form:

$$
\hat{y} = X\beta
$$

This approach is used when the target depends on several variables at once. For example, vehicle emissions or fuel consumption may depend on engine size, number of cylinders, fuel consumption metrics, and other technical measurements.

Multiple Linear Regression is useful when relationships are approximately linear and interpretability of coefficients is important.

## 8. Regularised Regression: Ridge and Lasso

Regularisation modifies linear regression by adding a penalty term to control model complexity.

**Ridge Regression** adds an L2 penalty:

$$
J(\beta) = \sum_{i=1}^{n}(y_i - \hat{y}_i)^2 + \alpha \sum_{j=1}^{p}\beta_j^2
$$

Ridge shrinks coefficients towards zero but usually does not remove them completely. It is useful when features are correlated or when the model is sensitive to noise.

**Lasso Regression** adds an L1 penalty:

$$
J(\beta) = \sum_{i=1}^{n}(y_i - \hat{y}_i)^2 + \alpha \sum_{j=1}^{p}|\beta_j|
$$

Lasso can shrink some coefficients exactly to zero, making it useful for feature selection.

Both methods are used when ordinary regression overfits, when the model has many predictors, or when coefficients become unstable.

## 9. Regression Trees

Regression Trees predict continuous values by recursively splitting the feature space. At each split, the algorithm chooses the feature and threshold that reduce prediction error.

A regression tree partitions the data into regions:

$$
R_1, R_2, \dots, R_m
$$

and predicts each region using the average target value within that leaf:

$$
\hat{y}_{R_m} = \frac{1}{|R_m|}\sum_{i \in R_m} y_i
$$

Regression trees are used when relationships are non-linear, interactions between variables are important, or the data does not fit a straight-line pattern.

## 10. Random Forest Regression and Classification

Random Forest combines many decision trees to produce a stronger ensemble model.

For regression, the final prediction is the average of all tree predictions:

$$
\hat{y} = \frac{1}{B}\sum_{b=1}^{B} T_b(x)
$$

where \(B\) is the number of trees and \(T_b(x)\) is the prediction from the \(b\)-th tree.

For classification, the model usually predicts by majority vote:

$$
\hat{y} = \text{mode}(T_1(x), T_2(x), \dots, T_B(x))
$$

Random Forests are useful for tabular data, non-linear relationships, mixed feature types, and situations where stronger predictive performance is needed than a single tree can provide.

## 11. XGBoost

XGBoost is a gradient boosting algorithm that builds trees sequentially. Each new tree attempts to correct the errors of the previous trees.

The model can be written as an additive ensemble:

$$
\hat{y}_i = \sum_{k=1}^{K} f_k(x_i)
$$

where each \(f_k\) is a tree. The algorithm minimises an objective function that combines loss and regularisation:

$$
Obj = \sum_i l(y_i, \hat{y}_i) + \sum_k \Omega(f_k)
$$

XGBoost is commonly used for high-performing structured-data prediction tasks, especially when accuracy is a priority and model complexity can be managed through tuning.

## 12. Logistic Regression

Despite its name, Logistic Regression is a classification algorithm. It estimates the probability that an observation belongs to a class.

For binary classification, the logistic function is:

$$
P(y=1|x) = \frac{1}{1 + e^{-z}}
$$

where:

$$
z = \beta_0 + \beta_1x_1 + \dots + \beta_px_p
$$

The output is a probability between 0 and 1. A threshold, often 0.5, converts this probability into a class label.

Logistic Regression is used in scenarios such as customer churn prediction, rainfall prediction, survival prediction, and other binary classification problems where probability interpretation is useful.

## 13. K-Nearest Neighbours

K-Nearest Neighbours predicts the label of a new observation by looking at the \(k\) closest observations in the training set.

Distance is often measured using Euclidean distance:

$$
d(x, x') = \sqrt{\sum_{j=1}^{p}(x_j - x'_j)^2}
$$

For classification, the predicted class is usually the majority class among the neighbours:

$$
\hat{y} = \text{mode}(y_1, y_2, \dots, y_k)
$$ 

KNN is useful when similar observations are expected to have similar outcomes. Because it depends on distances, scaling is especially important.

## 14. Decision Tree Classification

Decision Tree Classification predicts categorical outcomes by splitting the data into branches. A common splitting criterion is entropy:

$$
H(S) = -\sum_{c} p_c \log_2(p_c)
$$

where \(p_c\) is the proportion of observations belonging to class \(c\).

The tree selects splits that maximise information gain:

$$
IG = H(parent) - \sum_{j} \frac{|S_j|}{|S|}H(S_j)
$$

Decision trees are useful when interpretability matters because their predictions can be explained through visible rules.

## 15. Support Vector Machines

Support Vector Machines classify data by finding a decision boundary that maximises the margin between classes.

For a linear SVM, the decision boundary is:

$$
w^Tx + b = 0
$$

The margin is maximised by minimising:

$$
\frac{1}{2}||w||^2
$$

subject to correct classification constraints. SVMs are useful for classification problems where classes can be separated by a clear margin, and kernel methods allow them to model non-linear boundaries.

In the credit card fraud notebook, SVM is used in a high-risk classification scenario where separating rare fraudulent cases from normal transactions is important.

## 16. Multi-class Classification

Multi-class classification predicts more than two possible labels. Logistic Regression can be extended to multiple classes through strategies such as one-vs-rest or multinomial classification.

In a one-vs-rest approach, one classifier is trained for each class:

$$
P(y = c | x)
$$

and the predicted class is the one with the highest probability:

$$
\hat{y} = \arg\max_c P(y=c|x)
$$

This is used when the target variable contains several categories rather than only two.

## 17. Confusion Matrix

A confusion matrix compares actual labels with predicted labels. For binary classification, it contains:

| | Predicted Positive | Predicted Negative |
|---|---:|---:|
| Actual Positive | True Positive | False Negative |
| Actual Negative | False Positive | True Negative |

It is especially useful because accuracy alone can hide important mistakes. For example, in fraud detection or rainfall prediction, false negatives may be more serious than false positives.

The confusion matrix is used in the final project, Titanic project, pipelines notebook, and classification evaluation notebooks.

## 18. Classification Metrics

Several notebooks use classification reports and related metrics.

**Accuracy** measures the proportion of correct predictions:

$$
Accuracy = \frac{TP + TN}{TP + TN + FP + FN}
$$

**Precision** measures how many predicted positives were actually positive:

$$
Precision = \frac{TP}{TP + FP}
$$

**Recall** measures how many actual positives were correctly detected:

$$
Recall = \frac{TP}{TP + FN}
$$

**F1-score** is the harmonic mean of precision and recall:

$$
F1 = 2 \cdot \frac{Precision \cdot Recall}{Precision + Recall}
$$

**Log Loss** evaluates predicted probabilities:

$$
LogLoss = -\frac{1}{n}\sum_{i=1}^{n}[y_i \log(p_i) + (1-y_i)\log(1-p_i)]
$$

These metrics are used when evaluating classifiers such as Logistic Regression, KNN, Decision Trees, Random Forests, and SVMs.

## 19. Regression Metrics

Regression notebooks evaluate numerical predictions with metrics such as Mean Squared Error and R-squared.

Mean Squared Error is:

$$
MSE = \frac{1}{n}\sum_{i=1}^{n}(y_i - \hat{y}_i)^2
$$

Root Mean Squared Error is:

$$
RMSE = \sqrt{MSE}
$$

R-squared is:

$$
R^2 = 1 - \frac{\sum_{i=1}^{n}(y_i - \hat{y}_i)^2}{\sum_{i=1}^{n}(y_i - \bar{y})^2}
$$

MSE and RMSE measure prediction error, while R-squared measures the proportion of target variance explained by the model.

## 20. Machine Learning Pipelines

A scikit-learn pipeline chains preprocessing and modelling steps into one reproducible workflow. A typical pipeline may look like:

```python
Input Data → StandardScaler → PCA → KNeighborsClassifier → Prediction
```

Pipelines reduce mistakes because the same transformations are applied consistently during training and testing. They are especially important when combining scaling, dimensionality reduction, and model fitting.

## 21. GridSearchCV and Hyperparameter Tuning

Grid Search tests several combinations of hyperparameters and selects the best model configuration. If the candidate parameter values are:

$$
\theta \in \{\theta_1, \theta_2, \dots, \theta_m\}
$$

GridSearchCV evaluates each option using cross-validation and selects the one with the strongest validation score.

This is used in the pipeline notebooks and project notebooks to tune models such as KNN, Logistic Regression, or Random Forest.

## 22. Cross-Validation

Cross-validation divides the training data into \(k\) folds. The model trains on \(k-1\) folds and validates on the remaining fold, repeating the process \(k\) times.

The final validation estimate is:

$$
CV = \frac{1}{k}\sum_{i=1}^{k} score_i
$$

Cross-validation is useful when a single train-test split may give an unstable estimate of model performance.

## 23. K-Means Clustering

K-Means is an unsupervised algorithm that groups observations into \(k\) clusters. It minimises the within-cluster sum of squared distances:

$$
J = \sum_{i=1}^{n}\sum_{k=1}^{K} r_{ik}||x_i - \mu_k||^2
$$

where \(\mu_k\) is the centroid of cluster \(k\), and \(r_{ik}\) indicates whether observation \(i\) belongs to cluster \(k\).

K-Means is used for customer segmentation and synthetic cluster evaluation. It works best when clusters are relatively compact and spherical.

## 24. Silhouette Score and Clustering Evaluation

The silhouette score measures how well an observation fits within its assigned cluster compared with other clusters.

For each observation:

$$
s = \frac{b-a}{\max(a,b)}
$$

where \(a\) is the average distance to points in the same cluster and \(b\) is the average distance to points in the nearest different cluster.

A score close to 1 suggests good clustering, a score near 0 suggests overlapping clusters, and a negative score suggests possible misclassification.

## 25. DBSCAN and HDBSCAN

DBSCAN identifies clusters as dense regions separated by sparse regions. It uses two main parameters:

* \(\epsilon\), the neighbourhood radius;
* `min_samples`, the minimum number of points needed to form a dense region.

A point is a core point if it has enough neighbours within radius \(\epsilon\).

HDBSCAN extends this idea by building a hierarchy of density-based clusters and selecting stable clusters. It is useful when clusters have different densities and when the number of clusters is not known in advance.

These methods are especially useful for spatial data, geographical patterns, anomaly detection, and irregular cluster shapes.

## 26. Principal Component Analysis

PCA reduces dimensionality by projecting data onto directions of maximum variance.

Given a covariance matrix:

$$
\Sigma = \frac{1}{n}X^TX
$$

PCA finds eigenvectors and eigenvalues:

$$
\Sigma v = \lambda v
$$

The eigenvectors define principal components, and the eigenvalues indicate how much variance each component explains.

PCA is useful for visualisation, compression, noise reduction, removing correlated structure, and improving downstream modelling pipelines.

## 27. t-SNE and UMAP

t-SNE and UMAP are non-linear dimensionality reduction methods used mainly for visualisation.

t-SNE preserves local neighbourhood similarity by converting distances into probability distributions and minimising the difference between high-dimensional and low-dimensional similarities.

UMAP builds a graph representation of the data and optimises a low-dimensional embedding that preserves local and some global structure.

Both techniques are useful for visualising clusters, embeddings, high-dimensional datasets, and complex feature spaces where PCA may not reveal non-linear structure.

## 28. Feature Importance

Tree-based models such as Random Forests can estimate feature importance by measuring how much each feature contributes to reducing prediction error or impurity across the ensemble.

Feature importance is useful for interpreting which variables most influence a model's predictions. However, it must be interpreted carefully because correlated features can share importance between them.

## 29. Overfitting and Underfitting

Overfitting occurs when a model learns the training data too closely, including noise. Underfitting occurs when a model is too simple to capture the true pattern.

A model that overfits has low training error but high testing error. A model that underfits performs poorly on both training and testing data.

The notebooks address this through train-test splitting, cross-validation, regularisation, ensemble methods, and hyperparameter tuning.

<h1 align="center"><i>Skills Demonstrated</i></h1>

* Loading, inspecting, and preparing tabular datasets with pandas and NumPy.
* Performing train-test splitting for regression and classification tasks.
* Identifying and avoiding data leakage in predictive modelling.
* Scaling numerical features with `StandardScaler`.
* Building Simple Linear Regression and Multiple Linear Regression models.
* Applying Ridge and Lasso regularisation to control overfitting.
* Training Regression Trees, Random Forests, and XGBoost models.
* Building binary and multi-class classifiers with Logistic Regression.
* Training KNN, Decision Tree, Random Forest, and SVM classifiers.
* Creating reusable machine learning pipelines with scikit-learn.
* Performing hyperparameter tuning with GridSearchCV.
* Evaluating regression models with MSE, RMSE, and R-squared.
* Evaluating classification models with confusion matrices, accuracy, precision, recall, F1-score, log loss, and ROC-AUC.
* Applying K-Means, DBSCAN, and HDBSCAN clustering.
* Evaluating clustering performance with inertia and silhouette score.
* Applying PCA, t-SNE, and UMAP for dimensionality reduction and visualisation.
* Interpreting feature importance in ensemble models.
* Comparing model performance across multiple algorithms and scenarios.

<h1 align="center"><i>Technologies Used</i></h1>

<table align="center">
<tr>
<td>
<i>

* Python
* Jupyter Notebook / JupyterLab
* pandas
* NumPy
* Matplotlib
* Seaborn
* scikit-learn
* SciPy
* XGBoost
* HDBSCAN
* UMAP
* Plotly

</i>
</td>
</tr>
</table>

<h1 align="center"><i>Overall Summary</i></h1>

Together, these notebooks provide a practical and mathematically grounded introduction to Machine Learning with Python. They begin with foundational regression models and progress towards classification, clustering, ensemble learning, dimensionality reduction, pipelines, hyperparameter tuning, and model evaluation.

The two main projects apply these ideas to realistic classification scenarios: predicting rainfall in Australia and predicting Titanic passenger survival. The supporting notebooks then expand the portfolio by showing how different algorithms behave across structured datasets, imbalanced classification problems, customer segmentation tasks, fraud detection, housing prediction, taxi tip prediction, and high-dimensional visualisation.

Overall, this repository demonstrates the full applied machine learning workflow: preparing data, selecting features, training models, evaluating performance, interpreting results, and choosing the right algorithm for the right type of problem.

# Author
# ***[Matteo Meloni](https://www.linkedin.com/in/matteo-meloni-40a357154/)***
