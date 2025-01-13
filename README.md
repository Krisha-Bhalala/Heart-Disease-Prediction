# Heart Disease Prediction

This project implements a machine learning model to predict the presence of heart disease based on various health-related features. The model uses Logistic Regression to classify whether a person is at risk of heart disease or not.

## Dataset

The dataset used for training the model is the **heart_disease_data.csv** file. It contains health-related features such as age, sex, cholesterol levels, resting blood pressure, and more. The target variable is `target`, where:
- `1` indicates the person has heart disease
- `0` indicates the person does not have heart disease

### Data Features:
- **Age**: Age of the person
- **Sex**: Gender (0 = female, 1 = male)
- **Chest pain type**: Type of chest pain experienced
- **Resting blood pressure**: Blood pressure when resting
- **Serum cholesterol**: Cholesterol levels in mg/dl
- **Fasting blood sugar**: Whether the person has fasting blood sugar greater than 120 mg/dl
- **Resting electrocardiographic results**: Results of the electrocardiogram
- **Maximum heart rate achieved**: Highest heart rate achieved
- **Exercise induced angina**: Whether the person has induced angina during exercise
- **ST depression induced by exercise**: The depression of ST segment during exercise
- **Slope of peak exercise ST segment**: The slope of the ST segment during peak exercise
- **Number of major vessels colored by fluoroscopy**: Number of vessels colored
- **Thalassemia**: A blood disorder
- **Target**: Presence of heart disease (1 = disease, 0 = no disease)

## Files in the Repository

- **Heart_Disease_Detection.ipynb**: Jupyter notebook containing the machine learning model, data exploration, and prediction process.
- **heart_disease_data.csv**: Dataset containing health-related information.

## How to Run the Code

1. **Clone this repository** to your local machine using the following command:
    ```bash
    git clone https://github.com/Krisha-Bhalala/Heart-Disease-Prediction.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd Heart-Disease-Prediction
    ```

3. **Install the required dependencies**. If you have `requirements.txt`, you can use:
    ```bash
    pip install -r requirements.txt
    ```

    Alternatively, you can manually install the required libraries:
    ```bash
    pip install numpy pandas scikit-learn
    ```

4. **Run the Jupyter Notebook**:
    - Start Jupyter Notebook by running the following command:
    ```bash
    jupyter notebook
    ```

    - Open the `Heart_Disease_Detection.ipynb` notebook and execute the cells.

5. **Make Predictions**:
    - The notebook contains a section where you can input health data and get a prediction of whether the person is at risk for heart disease.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The dataset is based on the Cleveland Heart Disease dataset from the UCI Machine Learning Repository.
- This project is part of my learning in machine learning and data science.
