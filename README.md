## **Table of Contents**
- [**Table of Contents**](#table-of-contents)
- [**Project Overview**](#project-overview)
  - [**Objective**](#objective)
  - [**The analysis involves:**](#the-analysis-involves)
- [**Results**](#results)
  - [**Hyperparameter Tuning Attempts:**](#hyperparameter-tuning-attempts)
  - [**Key Findings**](#key-findings)
- [**Summary**](#summary)
- [**Technologies / Dependencies Needed and Used**](#technologies--dependencies-needed-and-used)
- [**How to Run the Application**](#how-to-run-the-application)
- [**Sample Visualizations**](#sample-visualizations)
- [**Data Source**](#data-source)
- [**Sources**](#sources)
- [**License**](#license)
- [**Project By**](#project-by)
- [**Contact**](#contact)
- [**Other Links**](#other-links)

## **Project Overview**
### **Objective**
The primary objective of this project is to develop and optimize a deep learning model capable of accurately predicting successful funding applications. By leveraging advanced machine learning techniques, we aim to identify key features that contribute to the success of funding requests, thereby enabling stakeholders to make informed decisions.

### **The analysis involves:**
* **Preprocessing**: Splitting the dataset into training and testing sets, followed by feature scaling using StandardScaler to normalize the input data. This step is crucial for improving the performance of the neural network model.
* **Model Training**: Implementing a deep learning model using a neural network architecture. The model consists of multiple layers, which are trained to recognize patterns in the data that correlate with successful funding applications.
* **Evaluation**: Assessing the model's performance through metrics such as accuracy, precision, recall, and the confusion matrix. This evaluation helps to understand how well the model predicts successful outcomes.
* **Recommendation**: Based on the evaluation results, determining the model's suitability for real-world applications. This includes considering its predictive accuracy and the potential impact on funding decisions.

## **Results**
- **Final Model Accuracy**: 78.45%
- **Final Model Loss**: 0.4429

### **Hyperparameter Tuning Attempts:**
- **Baseline Model:** 
  - Accuracy = 72.68%
  - Loss = 0.5538
- **Optimized Model (Additional Hidden Layers & Neurons):** 
  - Accuracy = 78.45%
  - Loss = 0.4429


### **Key Findings**
- The deep-learning model outperformed basic ML approaches but struggled with overfitting.
- Further improvements could include additional data augmentation or more feature engineering.
- Adding the NAME feature with a value over 5, increased the accuracy by 5%. From 73% to 78%


## **Summary**
This project demonstrated the effectiveness of deep learning for predicting funding application success. While the model achieved a reasonable accuracy, **further optimization is necessary** to generalize better. **Key next steps** could include experimenting with different architectures, tuning hyperparameters, and exploring additional datasets.

## **Technologies / Dependencies Needed and Used**
- **TensorFlow/Keras**: Used for building and training the deep-learning model.
- **Scikit-learn**: Used for preprocessing data (e.g., `StandardScaler` for normalization).
- **Matplotlib / Seaborn**: Used for visualizing model performance.
- **Pandas & NumPy**: For data manipulation and transformations.

## **How to Run the Application**
1. **Install Dependencies**: See [**Sources**](#sources) for additional information.
2. **Run the Jupyter Notebook**: Open and run all cells from **top to bottom** in the following notebook:  
   - [**Deep Learning Challenge**](https://colab.research.google.com/drive/1kUOWUprjhsx66qhrq6K8jQIbUsd8Fp_n)


## **Sample Visualizations**
[Sample 1 Optimizations ](Images/Sample_optimizations.png)

[Sample 2 Seaborn Chart](Images/seaborn_graph_amt.png)

[Sample 3 Google Colab](Images/Google_colab.png)

[Sample 4 myHDF5 viewer](Images/myHDF5_sample.png)

## **Data Source**
The dataset was sourced from the IRS. [Tax Exempt Organization Search Bulk Data Downloads](https://www.irs.gov/)
## **Sources**
* Office hours / instructional time / T.A.'s
* [sklearn.preprocessing.StandardScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)
* [Tensorflow](https://www.tensorflow.org/guide/keras)
* [Scikit-learn](https://scikit-learn.org/stable/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Pandas](https://pandas.pydata.org/)
* [Numpy](https://numpy.org/doc/stable/)
* Xpert Learning Assist
* Tutor sessions (Carlos Gattorno)
* Google
* ChatGPT


## **License**
This project is licensed under the [GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007](./LICENSE) - see the LICENSE file for details here.

## **Project By**
**Matthew Matti**

## **Contact**
For any questions or feedback, feel free to reach out to me at [mattimatt@hotmail.com](mailto:mattimatt@hotmail.com).

![License](https://img.shields.io/badge/license-GPL%203-blue)

## **Other Links**
[Neural Network Model Report](/Neural_network_model_report.md)

[Baseline Neuron Layers](/Baseline_neurons_layers.txt)
