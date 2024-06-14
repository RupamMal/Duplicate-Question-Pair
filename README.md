# Quora Duplicate Questions Detection

## Overview
This project utilizes Natural Language Processing (NLP) and Machine Learning (ML) algorithms to identify duplicate question pairs in the Quora dataset. The goal is to accurately predict whether pairs of question texts have the same intent.

## Project Structure
- `EDA.ipynb`: Performs exploratory data analysis (EDA) on the Quora dataset. It includes data loading, visualization, and preliminary analysis to understand the data's characteristics.
- `bow (basic-features).ipynb`: Prepares the dataset for modeling by applying feature engineering techniques like bag-of-words (BoW) to represent questions.
- `BOW.ipynb`: Implements machine learning models using the features prepared in the previous notebook. It focuses on setting up and evaluating different models to identify duplicate questions.

## Setup
To run this project, follow these steps:
1. **Clone the Repository**:
   ```
   git clone <repository-url>
   ```
2. **Install Required Libraries**:
   Ensure you have Python installed and proceed to install the required packages:
   ```
   pip install numpy pandas matplotlib seaborn sklearn
   ```
3. **Run the Notebooks**:
   Open the Jupyter Notebooks in an environment that supports IPython (like Jupyter Lab or VSCode) and execute them in order.

## Data
The dataset used in this project is the Quora question pairs dataset, which includes several thousands of question pairs along with a label indicating if they are duplicates.

## Contributing
Contributions to this project are welcome! Please feel free to fork the repository, make improvements, and submit a pull request.

## License
This project is open-sourced under the MIT license.

