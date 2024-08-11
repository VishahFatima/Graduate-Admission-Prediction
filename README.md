# Graduate Admissions Prediction with Deep Learning

This project aims to predict the chances of admission into graduate programs based on a student's profile using a Multilayer Perceptron (MLP) model built with TensorFlow and Keras. The purpose is to assist students in making data-driven decisions when shortlisting universities.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Visualization](#visualization)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project uses a dataset containing profiles of students applying for graduate programs. The model predicts the "Chance of Admit" based on features like GRE Score, TOEFL Score, Undergraduate GPA, and others. The predicted output helps students evaluate their profiles and make informed decisions about their university applications.

## Dataset
The dataset used in this project is the [Graduate Admissions Dataset](https://www.kaggle.com/datasets/mohansacharya/graduate-admissions). It contains the following features:
- GRE Score
- TOEFL Score
- University Rating
- Statement of Purpose (SOP)
- Letter of Recommendation (LOR)
- Undergraduate GPA (CGPA)
- Research Experience (Yes/No)
- Chance of Admit (Target)

## Model Architecture
The MLP model is a deep neural network with the following layers:
- Input Layer: Accepts the normalized features.
- Hidden Layers: Three dense layers with ReLU activation functions.
- Output Layer: A single neuron with a linear activation function to predict the "Chance of Admit."

## Requirements
- Python 3.x
- TensorFlow
- Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/graduate-admissions-prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd graduate-admissions-prediction
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. **Preprocess the Data:**
   The dataset is loaded, and features are normalized. The data is then split into training and testing sets.

2. **Train the Model:**
   The MLP model is trained on the dataset. The model is compiled with the Adam optimizer and mean squared error loss function.

3. **Evaluate the Model:**
   The model's performance is evaluated on the test set. Predictions are made for new profiles as well.

4. **Visualization:**
   - **Predicted vs Actual Chance of Admit:** A scatter plot to compare predicted values with actual values.
   - **Training vs Validation Loss:** A line plot showing the loss over epochs.

## Results
The model demonstrates the ability to predict the "Chance of Admit" with reasonable accuracy. The key results are visualized in two plots:
- **Predicted vs Actual Chance of Admit**: Indicates the model’s performance.
- **Training vs Validation Loss**: Shows how the model's learning evolves over epochs.

## Visualization
- **Predicted vs Actual Chance of Admit**

- **Training vs Validation Loss**

## Conclusion
This project showcases the potential of deep learning in educational data analysis. By predicting the chances of admission, the model provides valuable insights for students, helping them make informed decisions about their graduate studies.

## Contributing
Contributions are welcome! If you would like to contribute to this project, please open an issue or submit a pull request.
