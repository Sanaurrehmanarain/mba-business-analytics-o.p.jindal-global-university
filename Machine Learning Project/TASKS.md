# Project Tasks & Problem Statements

This repository solves the following seven business challenges:

**1. E-Commerce Exploratory Data Analysis (ShopStream)**
* Cleaned raw transactional data and handled missing/cancelled orders.
* Visualized monthly revenue trends, geographic sales distribution, and order quantities.
* Provided inventory planning insights based on seasonality and package sizing.

**2. Telecom Customer Churn Prediction (ConnectPlus)**
* Built and evaluated Random Forest, Logistic Regression, and Naive Bayes classifiers.
* Compared models using Accuracy, F1-Score, and AUC-ROC.
* Delivered business recommendations based on model interpretability and recall.

**3. Real Estate Price Prediction & Regularization (HomeLens)**
* Applied standard Linear Regression alongside Ridge, Lasso, and ElasticNet models on high-dimensional data.
* Analyzed the bias-variance trade-off and demonstrated how L1/L2 penalties prevent overfitting on sparse features.

**4. Retail Customer Segmentation (ShopSmart)**
* Applied K-Means clustering to Age, Annual Income, and Spending Score.
* Utilized the Elbow Method and Silhouette Score to determine the optimal number of clusters (K=6).
* Developed targeted marketing strategies for the highest and lowest-spending cohorts.

**5. Energy Efficiency Prediction (GreenBuild)**
* Built Artificial Neural Network (ANN) regression models using TensorFlow/Keras to predict HVAC cooling loads.
* Tuned hyperparameters (layers, neurons, dropout) and implemented Early Stopping.
* Translated the "black box" model mechanics into accessible explanations for building engineers.

**6. Media Sentiment Analysis (ReviewSense)**
* Fine-tuned a HuggingFace Transformer (DistilBERT) for binary sentiment classification.
* Benchmarked deep learning performance and inference time against a traditional TF-IDF + Naive Bayes baseline.
* Evaluated the linguistic advantages of bidirectional attention versus bag-of-words.

**7. Automated Clothing Recognition (StyleAI)**
* Built three Convolutional Neural Network (CNN) architectures to classify Fashion-MNIST images.
* Incorporated Batch Normalization and Data Augmentation layers.
* Analyzed inter-class confusion matrices and proposed solutions for real-world deployment challenges (latency, image variability).