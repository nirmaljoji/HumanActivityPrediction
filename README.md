# Human Activity Recognition using Accelerometer and Gyroscope Data

## Overview
This project focuses on utilizing accelerometer and gyroscope data collected from a special device worn by test subjects to recognize human activities. The dataset contains two main components: acceleration and gyroscope values recorded at a frequency of 40Hz, and activity labels recorded at a frequency of 10Hz. The objective is to build predictive models that can accurately identify the activity being performed based on the sensor readings.

## Project Structure
1. **Data Exploration:** Explore the dataset to understand its structure, patterns, and characteristics. This phase involves statistical analysis, visualization, and feature engineering to gain insights into the data.
2. **Prediction using MLP:** Implement a Multilayer Perceptron (MLP) model, a type of artificial neural network, to predict human activities based on the sensor data. The dataset will be preprocessed, split into training and testing sets, and used to train and evaluate the MLP model.
3. **Prediction using CNN:** Utilize a Convolutional Neural Network (CNN) to predict human activities. CNNs are particularly effective for sequential and image data, making them suitable for analyzing sensor data. Similar preprocessing steps as in MLP prediction will be applied, and the CNN model will be designed, trained, and evaluated.


## How to Run
1. Clone the repository to your local machine.
2. Navigate to the `notebooks` directory.
3. Execute the Jupyter notebooks in the following order:
   - `1_Data_Exploration.ipynb`
   - `2_Prediction_MLP.ipynb`
   - `3_Prediction_CNN.ipynb`
4. Follow the instructions within each notebook to explore data, train models, and evaluate predictions.

## Results
- Data exploration insights, including visualizations and key findings.
- Performance metrics of the MLP and CNN models, such as accuracy, precision, recall, and F1-score, will be reported.

## Conclusion
This project demonstrates the application of machine learning techniques, specifically MLP and CNN models, for human activity recognition using accelerometer and gyroscope data. By accurately identifying activities from sensor readings, the project has potential applications in various domains, including health monitoring, fitness tracking, and activity recognition systems.
