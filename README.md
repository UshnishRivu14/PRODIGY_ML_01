---

# **House Price Prediction Using Linear Regression**

This project demonstrates the use of a linear regression model to predict the prices of houses based on specific features such as square footage, number of bedrooms, and bathrooms. The goal is to provide an accurate estimation of house prices, which can be beneficial for real estate analysis and decision-making.

## **Project Overview**

Predicting house prices is a fundamental problem in the real estate industry. This project leverages a linear regression model to estimate house prices using key features from a dataset of house sales. The project walks through data preprocessing, model training, evaluation, and making predictions with new data.

## **Dataset**

The dataset used in this project is available on Kaggle: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data). It includes the following relevant features:
- **GrLivArea**: Above ground living area (in square feet).
- **BedroomAbvGr**: Number of bedrooms above ground.
- **FullBath**: Number of full bathrooms.
- **SalePrice**: The sale price of the house (target variable).

## **Project Structure**

The project is organized as follows:

- **data/**: Contains the dataset used in the project.
- **notebooks/**: Jupyter notebooks with the code implementation and analysis.
- **images/**: Visualizations generated during the analysis.
- **README.md**: Project overview and instructions.

## **Getting Started**

### **Prerequisites**

To run the code, you need to have the following packages installed:
- Python 3.x
- pandas
- scikit-learn
- matplotlib

### **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd house-price-prediction
   ```
3. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

### **Usage**

1. Open the Jupyter notebook `house_price_prediction.ipynb`.
2. Run the cells step by step to execute the linear regression model.
3. Visualizations and metrics will be generated to help you understand the model's performance.

### **Key Steps in the Analysis**

1. **Data Preprocessing:**
   - Selecting relevant features: `GrLivArea`, `BedroomAbvGr`, and `FullBath`.
   - Splitting the data into training and testing sets.

2. **Model Training:**
   - Training a linear regression model using the training data.

3. **Model Evaluation:**
   - Evaluating the model using Mean Squared Error (MSE) and R-squared score.
   - Visualizing the comparison between actual and predicted prices.

4. **Prediction:**
   - Predicting house prices for new data inputs.

## **Results**

The linear regression model provided a reasonable estimation of house prices based on the selected features. The performance was evaluated using the Mean Squared Error (MSE) and R-squared score, which indicated how well the model fits the data.

## **Contributing**

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## **Contact**

If you have any questions or feedback, feel free to reach out:

- **Email**: ushnishsarkar14@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/ushnish-sarkar-b21208217/

---
