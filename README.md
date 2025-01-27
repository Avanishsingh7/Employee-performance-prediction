# Employee Performance Prediction using Machine Learning

## Project Description

This project focuses on predicting employee performance within an organization using various machine learning techniques. We aim to analyze and predict performance based on several factors such as individual characteristics, schooling, socioeconomic status, and psychological factors. The prediction is made using a classification model where employees are categorized into three levels of performance: low, medium, and high.

Machine learning algorithms employed include:
- Support Vector Machines (SVM)
- Random Forest
- Naive Bayes
- Neural Networks
- Logistic Regression

The model uses 10-fold cross-validation to ensure the correctness of predictions, with SVM proving to be the most accurate model in this case. The results are presented through a Flask web application, where users can input various employee data points and receive a performance prediction.

## Features

- **User Input Form**: A form is provided for users to input various attributes related to employee performance. The form includes fields such as team, targeted productivity, SMV, incentive, and more.
- **Prediction Display**: Based on the input, the model predicts the employee's performance and displays the result as a percentage.
- **Interactive Web Interface**: Built using Flask and Bootstrap, the web app is simple and user-friendly, making it easy to collect inputs and display predictions.

## How It Works

1. **User Inputs**: Users enter details about an employee's performance factors (e.g., incentive, idle time, number of workers, etc.) into the provided form on the web interface.
2. **Model Prediction**: Upon submission, the form data is processed, and the model predicts the performance level of the employee.
3. **Result Display**: The prediction is displayed as a percentage, indicating the likelihood of the employee achieving the desired performance level.

## Technologies Used

- **Flask**: For building the web application.
- **Scikit-learn**: For machine learning models and metrics.
- **XGBoost, LightGBM**: For advanced boosting models.
- **NumPy, Pandas**: For data manipulation and processing.
- **Seaborn, Matplotlib**: For data visualization (not directly used in the web app but can be used for analysis).
- **Bootstrap**: For styling the web interface.

## How to Run the Web App

1. Clone this repository to your local machine.
2. Install the required libraries using `pip install` (you can find the list of required libraries in the code files).
3. Place the machine learning model `model.pkl` in the root directory of the project.
4. Run the Flask app using the following command:
    ```bash
    python app.py
    ```
5. Open your browser and go to `http://127.0.0.1:5000/` to use the app.

## Model Training

- **Data**: The model is trained on a dataset containing multiple employee-related features.
- **Training**: Various regression and classification models were tested, and the best-performing model (SVM) is used in the app.

## License

This project is licensed under the MIT License.

---

Feel free to contribute, open issues, or suggest improvements.
