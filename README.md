# Building Linear Regression Models from Scratch 🏗️📏🧠

This repository contains a Jupyter Notebook that dives deep into the implementation of Simple and Multiple Linear Regression models from scratch using the powerful NumPy library. It also provides a clear comparison of the performance of these custom-built models to the corresponding highly optimized models available in the popular scikit-learn library.

Access the notebook [here](https://github.com/amansagar88/Custom-Linear-Regression-model/blob/main/linear-regression-model.ipynb)

## Project Overview ✨💡

The core objective of this project is to gain a thorough understanding of the fundamental principles and inner workings of linear regression by constructing the models entirely from the ground up. The notebook systematically demonstrates the mathematical concepts underpinning both simple and multiple linear regression and provides clear, well-commented Python code implementations. The implemented models are then rigorously tested and evaluated by applying them to a real-world dataset to assess their predictive capabilities and performance.

## Models Implemented 📊🐍

*   **Simple Linear Regression:**
    *   Implemented from scratch using the fundamental formula \(y = mx + b\), where 'm' represents the slope and 'b' is the y-intercept.
    *   Includes essential methods for training the model (`fit`), making predictions on new data (`predict`), calculating the R-squared score (`score`) to evaluate the goodness of fit, and computing the Mean Squared Error (MSE) (`mean_squared_error`) as a measure of prediction error.
    *   Demonstrated with a simple, intuitive example predicting pizza price based on its size. 🍕💰

*   **Multiple Linear Regression:**
    *   Implemented from scratch using the elegant matrix operations and the normal equation, which provides a closed-form solution for the coefficients.
    *   Includes essential methods for training the model (`fit`) with multiple features, making predictions (`predict`) on new data points, calculating the R-squared score (`score`) for multi-variate data, and computing the Mean Squared Error (MSE) (`mean_squared_error`).
    *   Demonstrated with a simple example predicting house prices based on features like size and number of bedrooms. 🏠🛏️

## Dataset 💾🏡

*   **USA Housing Dataset:**
    *   A publicly available dataset used to test the performance and generalization ability of the custom-built linear regression models and to provide a realistic comparison against scikit-learn's implementations.
    *   Contains various features related to houses, such as square footage, number of bedrooms and bathrooms, year built, and their corresponding sale prices.

## Comparison with Scikit-learn 🆚🔬

The notebook conducts a direct comparison of the performance metrics (R-squared and RMSE) obtained from the custom-built models and the robust `LinearRegression` model from the scikit-learn library using the USA Housing Dataset. The results clearly show that the custom implementations yield remarkably similar performance metrics to the established library, effectively validating the correctness and accuracy of the scratch implementations.

## Visualizations 📈📊📉

The notebook includes insightful visualizations created using Matplotlib and Seaborn to help understand the data and model performance:

*   Scatter plots illustrating the relationship between key features and the target variable (house price).
*   A line plot showing the regression line for the simple linear regression model, visualizing the learned linear relationship.
*   A scatter plot comparing the actual house prices against the prices predicted by the multiple linear regression model, along with a diagonal line representing perfect prediction.

## 🧑‍💻 Author

**Aman Sagar**  
Data Science Enthusiast | Passionate about ML Algorithms
