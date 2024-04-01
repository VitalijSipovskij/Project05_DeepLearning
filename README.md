# Technology Adoption Prediction Deep Learning

## Overview
This project focuses on predicting technology adoption behavior in consumer households. It employs machine learning 
techniques to analyze factors influencing technology adoption, with a particular emphasis on regression and 
classification tasks.

## Dataset
The dataset used in this project, named "Factors Influencing Technology Adoption in Consumer Households," contains 
various features such as age, household income, and frequency of technology usage (e.g., laptops, smartphones, tablets, 
smart home devices). Additionally, it includes target variables related to technology adoption behavior, such as 
likeliness to recommend and likeliness to adopt.

## Project Structure
- **Data Preprocessing**: The dataset is preprocessed to extract relevant features and prepare the target variables for regression and classification tasks. Standard scaling is applied to normalize the feature values.
  
- **Regression Task**: Two machine learning frameworks, TensorFlow/Keras and PyTorch, are utilized to build regression models. These models predict the likeliness to recommend technology products based on selected features. Mean squared error is used as the evaluation metric.

- **Classification Task**: Similarly, TensorFlow/Keras and PyTorch are employed for the classification task, where the goal is to predict whether households are likely to adopt technology products. Binary cross-entropy loss and accuracy are used as evaluation metrics.

## Implementation
- **TensorFlow/Keras Models**: Dense neural network architectures are constructed using TensorFlow/Keras for both regression and classification tasks. The models are trained using gradient descent optimization and evaluated on test data.

- **PyTorch Models**: PyTorch is used to define and train neural network models for regression and classification tasks. Custom model classes are created, and training is performed using manual optimization loops.

## Results
The project evaluates and compares the performance of regression and classification models built using TensorFlow/Keras and PyTorch frameworks. Evaluation metrics such as mean squared error, loss, and accuracy are computed for each model. The results provide insights into the effectiveness of different machine learning frameworks for predicting technology adoption behavior.

## Conclusion
Through this project, we gain valuable insights into the factors influencing technology adoption in consumer households. By leveraging machine learning techniques and frameworks like TensorFlow/Keras and PyTorch, we can develop predictive models that assist in understanding consumer behavior and informing decision-making processes in the technology industry.

## Usage
1. Clone the repository.
2. Open `Project04_ML.ipynb` script file and execute it using integrated development environment (IDE)
like Jupyter Notebook or Colaboratory. And upload Dataset into that platform so that it could initiate properly. !Notice
uploaded dataset into platform will be available only for 24 hours after that you will need to upload it again into that
platform.
