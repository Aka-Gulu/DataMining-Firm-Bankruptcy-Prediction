# Firm-Bankruptcy-Prediction
### General Description
This repository contains the final project for the "Data Mining" (MGMT 571) course. The project involves developing a predictive model using SAS Enterprise Miner (SAS EM) to forecast if a firm will file for bankruptcy. The project showcases the application of Gradient Boosting and Neural Network models to enhance prediction accuracy.

### Project Description
The project aims to predict firm bankruptcy by leveraging various econometric measures and data mining algorithms. The final model is an ensemble of Gradient Boosting and Neural Network models, designed to improve robustness and accuracy through data stratification and multiple sampling.

### Model Development
The predictive model was developed using the following steps:

1. **Data Preparation**:
   - The data was preprocessed and cleaned to ensure quality inputs for the modeling process.
   - A sample node was used to split the data multiple times, employing stratified sampling to increase robustness.

2. **Model Building**:
   - **Gradient Boosting**: This model was used to capture complex patterns in the data through iterative boosting.
   - **Neural Network**: This model was employed to leverage its ability to model nonlinear relationships.

3. **Ensemble Method**:
   - The final model is an ensemble of Gradient Boosting and Neural Network models. This approach was chosen to leverage the strengths of both models and provide more accurate predictions.

### Dataset
The dataset used in this project contains various financial and economic indicators that are used to predict the likelihood of firm bankruptcy. The data was sourced from a Kaggle competition specifically designed for this project.

### Outcomes
The final ensemble model provides the following outcomes:
- Enhanced prediction accuracy by combining the strengths of Gradient Boosting and Neural Network models.
- Increased robustness through stratified sampling and multiple data splits.
- A comprehensive analysis of the factors influencing firm bankruptcy.

### Usage
To reproduce the results of this project using SAS Enterprise Miner:
1. Download the project files from this repository.
2. Open SAS Enterprise Miner and import the project files.
3. Follow the project workflow to understand the data preprocessing, model building, and ensemble method steps.
4. Run the models to generate predictions and evaluate the results.

### Conclusion
This project demonstrates the effective use of data mining algorithms in predicting firm bankruptcy. By combining Gradient Boosting and Neural Network models and employing robust data sampling techniques, the project achieves high prediction accuracy and provides valuable insights into the factors contributing to firm bankruptcy.

### Diagram
Here is the diagram of the ensemble model used in this project:
![Ensemble Model](assets/Ensemble.png)
