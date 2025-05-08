  Task 1 – Decision Tree Classification using the Iris Dataset

Internship Project - Machine Learning (CodTech)

Hello!  This repository contains my implementation of **Task 1** from the Machine Learning Internship Program by **CodTech**. The task is to build, train, visualize, and evaluate a **Decision Tree Classifier** using the well-known **Iris dataset**.

This is the first of four tasks in the internship and focuses on classification using supervised learning.

🎯 Objective

To build a machine learning model that:
- Classifies different species of Iris flowers
- Uses four features: sepal length, sepal width, petal length, petal width
- Trains a **Decision Tree Classifier** using the `scikit-learn` library
- Evaluates its performance on unseen data
- Visualizes the decision tree structure for easy interpretability

🗂️ Dataset Description

The dataset used is the **Iris dataset**, which is a classic in machine learning and pattern recognition.

- **Features (Independent variables):**
  - sepal_length (cm)
  - sepal_width (cm)
  - petal_length (cm)
  - petal_width (cm)

- **Target (Dependent variable):**
  - species (Setosa, Versicolor, Virginica)

In my version, the dataset is a `.csv` file uploaded and loaded via Google Colab.

 📈 Step-by-Step Workflow

 🔹 Step 1: Data Upload and Exploration
- Uploaded the dataset to Colab using `files.upload()`
- Loaded the CSV into a pandas DataFrame
- Explored the data using `.head()`, `.info()`, and `.value_counts()`

 🔹 Step 2: Data Preprocessing
- Encoded the target column `species` into numeric format using `LabelEncoder`
- Split the dataset into features (X) and target (y)

 🔹 Step 3: Train-Test Split
- Used `train_test_split()` from `sklearn` to divide data into 80% training and 20% testing sets

 🔹 Step 4: Model Training
- Created and trained a `DecisionTreeClassifier`
- Fit the model on training data

 🔹 Step 5: Prediction and Evaluation
- Predicted species for test data using `.predict()`
- Evaluated model using `accuracy_score` and `classification_report`

 🔹 Step 6: Visualization
- Used `plot_tree()` to visualize the trained decision tree
- Displayed feature names and class labels for clarity

---

 📊 Results

- Achieved high accuracy on the test data
- The decision tree structure shows clear and logical splits based on petal and sepal dimensions
- The model is interpretable, easy to explain, and performs well on small datasets like Iris

---

 🛠️ Tools & Libraries Used

- Python 3
- Google Colab
- pandas
- scikit-learn
- matplotlib
- LabelEncoder

---
Output:

![Image](https://github.com/user-attachments/assets/78af157d-c145-4b51-afb0-4785bb8332bf)
