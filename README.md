# ANN Classification using PyTorch

## 📌 Project Overview

This project implements an **Artificial Neural Network (ANN)** for classifying different varieties of dates using the **Date Fruit Dataset**.

The model is built using **PyTorch** and uses feature scaling, label encoding, train-test splitting, and a feed-forward neural network for classification.

## 🎯 Objective

The main objective of this project is to classify a date fruit into one of **7 different classes** based on its given features.

The seven classes are:

* BERHI
* DEGLET
* DOKOL
* IRAQI
* ROTANA
* SAFAVI
* SOGAY

## 📊 Dataset

The dataset contains:

* **898 samples**
* **34 input features**
* **1 target column (`Class`)**
* **7 different date fruit classes**

The target column is `Class`.

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* PyTorch
* Matplotlib
* Jupyter Notebook

## 🔄 Project Workflow

The project follows these steps:

```text
Dataset
   ↓
Data Exploration
   ↓
Feature & Target Separation
   ↓
Label Encoding
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
PyTorch Tensors
   ↓
DataLoader
   ↓
ANN Model
   ↓
Model Training
   ↓
Model Testing
   ↓
Accuracy Evaluation
   ↓
Actual vs Predicted
   ↓
Confusion Matrix
```

## 🧠 ANN Architecture

The neural network contains:

```text
Input Layer
   ↓
64 Neurons
   ↓
ReLU
   ↓
64 Neurons
   ↓
ReLU
   ↓
7 Output Neurons
```

The input layer contains **34 features**, and the output layer contains **7 neurons**, one for each date fruit class.

## ⚙️ Model Configuration

* **Loss Function:** CrossEntropyLoss
* **Optimizer:** Adam
* **Epochs:** 100
* **Activation Function:** ReLU
* **Output Classes:** 7

## 📈 Training

The model is trained for 100 epochs.

During training, the loss is calculated for each batch and the model parameters are updated using the Adam optimizer.

The training loss decreases as the model learns from the training data.

## 🧪 Testing

After training, the model is evaluated using the test dataset, which contains **20% of the original dataset**.

The predicted class is obtained by selecting the output neuron with the highest score.

## 📊 Result

The model achieved approximately:

**Test Accuracy: 94.44%**

This indicates that the ANN was able to correctly classify most of the unseen test samples.

## 📉 Evaluation

The project also includes:

* Training Loss Graph
* Actual vs Predicted Results
* Confusion Matrix
* Test Accuracy

These evaluation methods help understand how well the model performs on unseen data.

## 📁 Project Structure

```text
ANN-Classification/
│
├── ANN_Classification.ipynb
├── DateFruit_Dataset.csv
└── README.md
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone <your-repository-link>
```

### 2. Install the required libraries

```bash
pip install pandas numpy scikit-learn matplotlib torch
```

### 3. Open the notebook

Open:

```text
ANN_Classification.ipynb
```

using Jupyter Notebook or JupyterLab.

### 4. Run the cells

Run the cells in order to:

* Load the dataset
* Preprocess the data
* Train the ANN
* Test the model
* Evaluate the results

## 📌 Conclusion

This project demonstrates how an **Artificial Neural Network can be used for multi-class classification**.

Using the Date Fruit Dataset, the PyTorch ANN achieved approximately **94.44% test accuracy**, showing good classification performance across the seven date fruit varieties.

## 👨‍💻 Author

**Sayan Bairi**

B.Tech in Computer Science and Engineering (AIML)

Institute of Engineering and Management
