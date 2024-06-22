# Star Classification using Random Forest

This project demonstrates the process of building a machine learning model to classify stars based on their spectral types using the Random Forest algorithm. The dataset consists of various features that describe stars, and the target variable is the spectral type of the stars. This project involves data loading, preprocessing, model building, hyperparameter tuning, and evaluation.

## Project Structure

The project is structured as follows:

1. **Data Loading**: Load the dataset and display basic information about it.
2. **Data Visualization**: Visualize the distribution of the target variable 'SpType-ELS'.
3. **Data Preprocessing**: Preprocess the data by handling missing values, encoding categorical variables, and preparing the dataset for model building.
4. **Model Building and Hyperparameter Tuning**: Build a Random Forest classifier and tune its hyperparameters using GridSearchCV.
5. **Model Evaluation**: Evaluate the model using accuracy, classification report, and confusion matrix.

## Files

- `dataGaia_AB_train.csv`: The main dataset containing the features and target variable.
- `head_description.csv`: A file containing the description of the dataset headers.
- `Star_Classification.ipynb`: The Jupyter Notebook containing the code for this project.

## Getting Started

### Prerequisites

Make sure you have the following libraries installed:

- pandas
- matplotlib
- scikit-learn

You can install these libraries using pip:

```sh
pip install pandas matplotlib scikit-learn
```

### Running the Project

1. Clone this repository:

```sh
git clone https://github.com/your-username/star-classification.git
cd star-classification
```

2. Ensure the `dataGaia_AB_train.csv` and `head_description.csv` files are in the same directory as the Jupyter Notebook.

3. Open the Jupyter Notebook:

```sh
jupyter notebook Star_Classification.ipynb
```

4. Run all the cells in the notebook to see the results.

## Data

The dataset consists of various features describing stars. The target variable is the spectral type of the stars. The dataset contains missing values, which are handled using median imputation during preprocessing. The spectral type is encoded using Label Encoding.

## Model

The model used in this project is a Random Forest classifier. The hyperparameters of the model are tuned using GridSearchCV to find the best combination of parameters. The model is evaluated using accuracy, classification report, and confusion matrix.

## Results

The best hyperparameters found using GridSearchCV are printed, along with the model's accuracy on the test set. The classification report and confusion matrix provide detailed insights into the model's performance.

## Conclusion

This project demonstrates a complete workflow for building a machine learning model to classify stars based on their spectral types. It covers data preprocessing, model building, hyperparameter tuning, and model evaluation.

## Acknowledgements

- The dataset used in this project is provided in the `dataGaia_AB_train.csv` file.
- The description of the dataset headers is provided in the `head_description.csv` file.

Feel free to explore the notebook and experiment with different models and hyperparameters to improve the classification performance.

---

**Note:** Ensure you have the necessary data access permissions and Power BI installed to view the report.

---

For more information and updates, visit our [GitHub repository](https://github.com/PrinceRajyaguru/Data-Science-AI-ML).

---

**Contact Information:**
- **Email:** princerajyaguru1111@gmail.com
- **GitHub:** [Prince Rajyaguru](https://github.com/PrinceRajyaguru)
