# Titanic Survival Prediction using Neural Networks 🚢  

This project builds a machine learning model using TensorFlow and Keras to predict Titanic passenger survival based on various features.  

## 📌 Project Overview  
- Load and preprocess the Titanic dataset  
- Perform feature selection and transformation  
- Build and train a neural network for binary classification  
- Evaluate model performance  

## 📂 Dataset  
We use the Titanic dataset from **Seaborn**, which includes information about passengers such as age, class, gender, and survival status.  

## ⚙️ Preprocessing Steps  
- Handle missing values (drop rows with missing age and embarkation data)  
- Convert categorical variables into dummy variables  
- Select relevant features for training  
- Split data into training and testing sets  
- Standardize features using `StandardScaler`  

## 🏗️ Model Architecture  
The model consists of:  
- **Input Layer**: Dense layer with 10 neurons and ReLU activation  
- **Output Layer**: Dense layer with 1 neuron and Sigmoid activation  

We use the **Adam optimizer** and **binary cross-entropy loss** for training.  

## 🚀 Training the Model  
- Trained for **100 epochs** with a batch size of **32**  
- Used **verbose=1** to monitor progress  

## 📊 Model Evaluation  
The model is evaluated using accuracy and loss on the test dataset.  

## 📌 Requirements  
Install the necessary libraries before running the notebook:  
```bash
pip install tensorflow pandas seaborn scikit-learn
