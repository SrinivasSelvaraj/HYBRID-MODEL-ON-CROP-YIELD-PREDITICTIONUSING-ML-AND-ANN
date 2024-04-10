
---

# Crop Yield Prediction Using Machine Learning

Crop yield prediction is a crucial task in agriculture, aiming to estimate the total quantity of crop output based on various environmental and agricultural parameters. This project aims to construct a hybrid model using machine learning to estimate agricultural output based on characteristics such as rainfall, temperature, and pesticide use.

## Dataset
The dataset used in this project contains information about crop yields and relevant environmental and agricultural parameters for various locations worldwide.

## Project Steps
1. **Data Preprocessing and Exploration**: The dataset is preprocessed and explored to understand the correlations between variables. Various data visualization techniques are used to find patterns in the data.

2. **Model Development**: Several machine learning algorithms are used to develop the prediction model, including linear regression, decision tree regression, random forest regression, support vector regression, and XGBoost regression. The models are evaluated using the R2 score to assess accuracy and reliability.

3. **Hybrid Model Creation**: The best-performing models are combined into a single hybrid model using a voting regressor. The R2 score of the hybrid model indicates a high level of accuracy.

4. **Web Application Development**: The hybrid model is implemented in an interactive web application using the Gradio library. This application allows users to input environmental and farming data for a specific location and obtain a forecast of crop production for that region.

## Usage
To run the web application:
1. Install the required libraries: `pip install gradio`.
2. Run the application: `python app.py`.
3. Access the application in your web browser at `http://localhost:7860`.

## Conclusion
The hybrid model developed in this project provides a reliable method for predicting crop yields based on environmental and agricultural parameters. This information can assist farmers in making informed decisions about crop management and contribute to food security planning.

---
