🌸 Iris Flower Classification using Neural Network

📌 Project Overview

This project implements a Neural Network model to classify iris flowers into different species based on their features.

Unlike traditional machine learning, this model uses a Deep Learning approach to achieve high accuracy.

🌼 Dataset Information

The project uses the well-known Iris dataset, which includes:

150 samples

3 classes:

Setosa

Versicolor

Virginica

4 input features:

Sepal Length

Sepal Width

Petal Length

Petal Width

🛠 Technologies Used

Python

pandas

NumPy

Scikit-learn

TensorFlow / Keras

📂 Project Workflow

1️⃣ Import Libraries

Imported required libraries for data handling, preprocessing, and deep learning.

2️⃣ Load Dataset

Loaded the Iris dataset and converted it into a DataFrame for easy understanding and manipulation.

3️⃣ Data Preparation

Separated input features (X) and target variable (y)

Prepared data for model training

4️⃣ Encoding Target Values

Used Label Encoding to convert categorical labels into numerical form

This is required for training the neural network model

5️⃣ Train-Test Split

Split dataset into training and testing sets

Ensured proper evaluation of the model

6️⃣ Building the Neural Network Model

Created a Sequential model using Keras

Added multiple layers:

Input + hidden layer with ReLU activation

Additional hidden layer

Output layer with Softmax activation

👉 Softmax is used because this is a multi-class classification problem

7️⃣ Model Compilation

Loss Function: sparse_categorical_crossentropy

Optimizer: adam

Evaluation Metric: accuracy

8️⃣ Model Training

Trained the neural network on training data

Learned patterns between input features and output classes

9️⃣ Model Evaluation

Accuracy Score:

1.0 (100% accuracy)

Model performs very well on the dataset

🔟 Predictions

The trained model is used to predict the class of new iris flower data

📊 Results

The Neural Network achieved 100% accuracy, showing excellent classification performance.

📁 Files in Repository

iris_nn_classification.ipynb → Full implementation

README.md → Project documentation


👩‍💻 Author

Nidhi Kumawat

⭐ Acknowledgement

Dataset provided by Scikit-learn library.

🚀 Future Improvements

Try deeper neural networks

Add visualization of training performance

Deploy model using a web application
