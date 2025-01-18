# Titanic Survival Analysis: Exploratory Data Analysis (EDA)

This project analyzes the survival rates of passengers aboard the Titanic using Python libraries. By exploring the Titanic dataset, we uncover insights into factors that influenced survival, such as age, gender, and passenger class.

## Key Features

- **Data Exploration**: Understanding the dataset structure, identifying missing values, and examining key statistics.
- **Data Cleaning**: Handling null values and preparing the dataset for analysis.
- **Visualization**: Generating charts to uncover relationships between survival rates and variables like gender, age, and class.

## Tools and Libraries

The project leverages the following libraries:
- `Pandas` for data manipulation.
- `Seaborn` for advanced visualizations.
- `Matplotlib` for basic plotting.
- `NumPy` for numerical operations.

## Dataset

The dataset is sourced from Seaborn's built-in `titanic` dataset. It includes the following key columns:
- **`survived`**: Survival status (0 = No, 1 = Yes).
- **`pclass`**: Ticket class (1 = First, 2 = Second, 3 = Third).
- **`sex`**: Gender of the passenger.
- **`age`**: Age of the passenger.
- **`fare`**: Ticket fare.
- **`embarked`**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Steps to Reproduce

1. Clone this repository:
   ```bash
   git clone <repository_url>
   cd <repository_folder>
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook and run the analysis:
   ```bash
   jupyter notebook Titanic_EDA.ipynb
   ```

## Results and Insights

- **Gender**: Female passengers had a significantly higher survival rate compared to males.
- **Age**: Children had higher survival rates than adults.
- **Class**: First-class passengers were more likely to survive compared to second and third-class passengers.

## Visualizations

The project includes visualizations such as:
- Bar charts showing survival rates by gender.
- Histograms of age distribution for survivors vs. non-survivors.
- Heatmaps for correlation between variables.

## Future Enhancements

- **Feature Engineering**: Create new features to improve insights, such as family size.
- **Machine Learning**: Build predictive models to classify survival using scikit-learn.
- **Advanced Visualization**: Utilize Plotly for interactive charts.

## Contributions

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

Feel free to explore the notebook and share your feedback!
