# YoungDevInterns_Artificial Intelligence_Tasks

Welcome to my AI Internship repository with **YoungDevInterns**. This project tracks my progress through foundational and advanced AI/ML concepts, from UI design to complex model evaluation.

---

## 🟢 Basic Tasks (Level 1)

### Task 1: Responsive UI Design (Figma)
* **Goal:** Create a webpage interface that adapts to Desktop, Tablet, and Mobile.
* **Key Features:** Used **Auto-Layout** for flexible containers and **Constraints** for element positioning.
* **Outcome:** A prototype that maintains visual hierarchy across all device types.

### Task 2: Data Preprocessing Pipeline
* **Goal:** Transform raw, "messy" data into a model-ready format.
* **Techniques:** * Imputation of missing values.
    * Feature scaling using `StandardScaler`.
    * Categorical encoding (Label/One-Hot).
* **Outcome:** Cleaned datasets with an 80/20 train-test split.

### Task 3: K-Fold Cross-Validation
* **Goal:** Robustly evaluate model performance.
* **Implementation:** Applied 5-Fold CV on a Random Forest Classifier.
* **Metrics:** Tracked Accuracy, Precision, Recall, and F1-Score to ensure generalization.

---

## 🟡 Intermediate Tasks (Level 2)

### Task 4: Advanced Neural Network Architecture
* **Goal:** Build a multi-layer Perceptron (MLP) for complex pattern recognition.
* **Key Features:** Implementation of **Hidden Layers**, **Dropout** (for overfitting prevention), and **Activation Functions** like ReLU and Softmax.
* **Outcome:** Improved classification accuracy on non-linear datasets.

### Task 5: Feature Engineering & Selection
* **Goal:** Improve model accuracy by selecting the most impactful data features.
* **Techniques:** Used **Correlation Matrices** and **Principal Component Analysis (PCA)** to reduce dimensionality while retaining variance.
* **Outcome:** Reduced model training time and increased predictive power.

### Task 6: Hyperparameter Tuning (GridSearch)
* **Goal:** Find the "perfect" settings for a Machine Learning model.
* **Implementation:** Used `GridSearchCV` to automatically test hundreds of combinations of parameters (like `n_estimators` and `max_depth`).
* **Outcome:** Optimized model performance beyond default settings.
ask 1: Advanced Model Optimization
Goal: Optimize a complex model using automated hyperparameter tuning.

Model: Random Forest / Gradient Boosting.

Methodology: Implemented RandomizedSearchCV to navigate a high-dimensional parameter space (including n_estimators, max_depth, and min_samples_split).

Outcome: Achieved a significant uplift in model performance by identifying the optimal balance between bias and variance, ensuring the model generalizes well to unseen data.

Task 2: Deep Learning Implementation (CNN)
Goal: Design and train a Convolutional Neural Network (CNN) for image classification.

Architecture: Built a multi-layer CNN using the Keras Functional API/Sequential model.

Optimization Techniques:

Batch Normalization: Applied to stabilize the learning process and reduce training time.

Dropout: Integrated (0.2–0.5 rate) to prevent overfitting by deactivating random neurons during training.

Dataset: Trained on the CIFAR-10 dataset (32x32 color images).

Result: Attained high validation accuracy, demonstrating the network's ability to extract spatial hierarchies from raw pixel data.

Task 3: Model Deployment as a Web Service
Goal: Deploy the trained model to a live web API.

Framework: FastAPI — chosen for its high performance and native support for asynchronous requests.

Server: Uvicorn serving as the ASGI implementation.

Deployment Strategy: * The model was serialized as a .keras file.

Exposed via a public URL using Localtunnel to simulate a cloud-hosting environment (AWS/GCP).

Features a /predict endpoint that accepts image uploads, performs real-time preprocessing, and returns class predictions in JSON format.
---

## 🛠️ Tech Stack
* **Programming:** Python 3.10+
* **Libraries:** Scikit-Learn, NumPy, Pandas, Matplotlib, Seaborn
* **Tools:** Google Colab, Figma, GitHub

---

## 👤 Connect & Submit
* **LinkedIn:** [Insert Your Profile Link]
* **Facebook:** [Insert Your Profile Link]
* **Internship Provider:** [YoungDevInterns](https://www.linkedin.com/company/youngdevinterns/)

---
*Submitted as part of the YoungDevInterns AI Internship Program.*
