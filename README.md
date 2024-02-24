# Apple Quality Prediction

This Python application predicts the quality of apples based on various attributes such as size, weight, sweetness, crunchiness, juiciness, ripeness, and acidity. The prediction model is trained using a dataset containing information about these attributes of a set of fruits, providing insights into their characteristics.

## Getting Started

To use this application, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have Python installed on your machine.
3. Install the required dependencies by running `pip install -r requirements.txt`.
4. Run the `apple_quality_prediction.py` script to launch the GUI application.

## Usage

Once the application is running, you can enter the attributes of the apple in the input fields provided. The attributes should be numeric values between -10 and 10. After entering the attributes, click the "Predict" button to see the predicted quality of the apple.

If any of the input fields contain invalid values or are left blank, an error message will be displayed, indicating which input fields need correction.

You can also click the "Clear" button to clear the input fields and any output messages.

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

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
