# Apple Quality Prediction

This Python application predicts the quality of apples based on various attributes such as size, weight, sweetness, crunchiness, juiciness, ripeness, and acidity. The prediction model is trained using a Random Forest algorithm and a dataset obtained from [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/apple-quality), which contains information about these attributes of a set of fruits, providing insights into their characteristics.

## Getting Started

To use this application, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine.
   
    ```bash
    git clone https://github.com/your-username/apple-quality-prediction.git
    ```

2. **Install Dependencies**: Ensure you have Python installed on your machine. Install the required dependencies by running:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Application**: Run the `apple_quality_prediction.py` script to launch the GUI application.

    ```bash
    python apple_quality_prediction.py
    ```

## Usage

Once the application is running, follow these steps to predict the quality of an apple:

1. **Enter Apple Attributes**: Enter the attributes of the apple in the input fields provided. The attributes should be numeric values between -10 and 10.

2. **Predict Apple Quality**: Click the "Predict" button to see the predicted quality of the apple.

3. **View Prediction**: The application will display the predicted quality of the apple, along with any additional message if the predicted quality is outside the expected range.

## Example

Here's an example of how to use the application:

1. Enter the following attributes of the apple:
   - Size: 7
   - Weight: 5
   - Sweetness: 8
   - Crunchiness: 6
   - Juiciness: 7
   - Ripeness: 6
   - Acidity: 4

2. Click the "Predict" button.

3. The application will display the predicted quality of the apple, along with any additional message if the predicted quality is outside the expected range.

## Notes

- Ensure that all input values are numeric and fall within the range of -10 to 10.
- The predicted quality is displayed with two decimal places for better accuracy.
- The model uses the Random Forest algorithm for prediction.
- The dataset used for training the model can be found on [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/apple-quality).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
