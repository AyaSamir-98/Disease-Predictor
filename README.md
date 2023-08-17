# Disease Predictor using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

This project is a simple Disease Predictor built using Python and Machine Learning algorithms. It allows users to input a few symptoms, and the program predicts the disease based on the entered symptoms using three different Machine Learning algorithms: Decision Tree, Random Forest, and Naive Bayes.

## Requirements

- Python 3.x
- Required libraries: tkinter, numpy, pandas, sklearn

## How to Use

1. Clone this repository to your local machine.
2. Install the required libraries using `pip install numpy pandas scikit-learn`.
3. Run the `main.py` script using `python main.py`.
4. A GUI window will open, where you can enter the patient's name and select up to five symptoms from the dropdown menus.
5. Click on the respective algorithm buttons (Decision Tree, Random Forest, Naive Bayes) to predict the disease based on the symptoms.
6. The predicted disease will be displayed in the text boxes below each algorithm button.

## Project Structure

- `main.py`: The main script that contains the GUI interface and handles the prediction using different algorithms.
- `Training.csv`: The dataset containing training data with symptoms and corresponding disease labels.
- `Testing.csv`: The dataset containing test data with symptoms and corresponding disease labels.

## Algorithms Used

- **Decision Tree**: This algorithm uses a decision tree to make predictions based on the provided symptoms.
- **Random Forest**: This algorithm creates an ensemble of decision trees and combines their predictions.
- **Naive Bayes**: This algorithm uses the Naive Bayes probability theorem to make predictions based on symptoms.

## Author

Aya Samir

## License

This project is licensed under the MIT License.

Feel free to contribute or improve the project further.

*Note: This project is for educational purposes and should not be used as a replacement for professional medical diagnosis.*
