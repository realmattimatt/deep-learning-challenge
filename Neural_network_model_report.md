# **Alphabet Soup Charity Optimization Report**

## **Overview**: The goal was to build and optimize a deep learning model to predict successful funding applications.

### **Results**
  #### **Data Processing**
  - Target Variable(s):
    - The Target was the column (**IS_SUCCESSFUL**)
  - Feature Variables:
    - The Feature variables were (**APPLICATION_TYPE,AFFILIATION	CLASSIFICATION,	USE_CASE,	ORGANIZATION,	STATUS,	INCOME_AMT,	SPECIAL_CONSIDERATIONS,	ASK_AMT**)
    - The following variables were removed from the input data because they are neither targets nor features (**EIN, NAME, and the original ASK_AMT**), **ASK_AMT** due to extreme outliers there for was transformed and renamed to "**ASK_AMT_LOG** and used in the Features"

  #### **Compiling, Training, and Evaluating the Model**
  - How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - Were you able to achieve the target model performance?
  - What steps did you take in your attempts to increase model performance?

### **Visualizations** 

  ### **Summary**: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.