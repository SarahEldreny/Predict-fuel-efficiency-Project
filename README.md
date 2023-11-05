# Predict Fuel Efficiency Project

This project aims to predict the fuel efficiency of vehicles using linear regression. The dataset used for training and testing the model is obtained from the UCI Machine Learning Repository and can be accessed through the following link: [Auto MPG Dataset](http://archive.ics.uci.edu/ml/machine-learning-databases/auto-mpg/auto-mpg.data).

## Dataset

The dataset contains information about various cars, including attributes such as displacement, horsepower, weight, and model year. The target variable is the vehicle's fuel efficiency, measured in miles per gallon (mpg). Each data instance is represented as a row in the dataset, where each column corresponds to a specific attribute.

The dataset is in a text file format, where each line represents a data instance. The columns are separated by spaces or tabs. Missing values are denoted by a question mark "?".

## Project Structure

The project has the following file structure:

- `predict_fuel_efficiency.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
- `README.md`: Documentation file providing an overview of the project.

## Getting Started

To get started with this project, follow the steps below:

1. Clone this repository to your local machine or download the project files.
2. Open the Jupyter Notebook `predict_fuel_efficiency.ipynb` using Jupyter Notebook or any compatible environment.
3. Ensure that you have the necessary dependencies installed, including Python, NumPy, Pandas, and scikit-learn.
4. Run the code cells in the Notebook sequentially to preprocess the data, train the linear regression model, and evaluate its performance.
5. Feel free to modify the code or experiment with different features and model parameters to improve the predictions.

## Dependencies

- Python 3.x
- NumPy
- Pandas
- scikit-learn

You can install the required dependencies using pip:

```
pip install numpy pandas scikit-learn
```

## License

The dataset used in this project is available in the public domain and is provided by the UCI Machine Learning Repository. Please refer to the repository's license terms and conditions for more information.

The project code is released under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgments

- UCI Machine Learning Repository for providing the Auto MPG dataset.

## Further Help

If you encounter any issues or have questions regarding the project, please feel free to [open an issue](https://github.com/SarahEldreny/predict-fuel-efficiency-project/issues).
