# Pair-of-Duplicate-Question
## Project Overview
This project consists of two Jupyter notebooks: `Duplicates.ipynb` and `Model.ipynb`. These notebooks aim to process and analyze a dataset for identifying duplicate questions and build a machine learning model for classification.

### `Duplicates.ipynb`
#### Purpose
This notebook processes a dataset containing pairs of questions to identify potential duplicates. The dataset includes columns such as `id`, `qid1`, `qid2`, `question1`, `question2`, and `is_duplicate`.

#### Key Features
- Loads the dataset `train.csv` using `pandas`.
- Inspects the data by displaying the first few rows.
- Focuses on exploring duplicates in the dataset.

#### Usage
1. Place the `train.csv` file in the same directory as the notebook.
2. Run the notebook cells sequentially to load and analyze the dataset.

### `Model.ipynb`
#### Purpose
This notebook builds on the processed data from the first notebook to develop a machine learning model.

#### Key Features
- Loads the processed dataset `new_df.csv`.
- Checks the shape of the dataset (49,606 rows and 18 columns).
- Prepares the data for machine learning tasks.

#### Usage
1. Ensure the `new_df.csv` file is available in the specified directory.
2. Run the notebook cells to load the data and proceed with the model-building process.

## Setup Instructions

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - `pandas`
  - `numpy`

### Installation
1. Clone this repository.
2. Install the required Python libraries:
   ```bash
   pip install pandas numpy
   ```
3. Open the notebooks in Jupyter:
   ```bash
   jupyter notebook
   ```

## File Descriptions
- **`Duplicates.ipynb`**: Prepares and analyzes the dataset for duplicate detection.
- **`Model.ipynb`**: Develops a machine learning model using the processed data.
- **`train.csv`**: Raw dataset for duplicate analysis (required for `Duplicates.ipynb`).
- **`new_df.csv`**: Processed dataset for modeling (required for `Model.ipynb`).

## Acknowledgements
- This project utilizes publicly available datasets for educational and analytical purposes.
- Developed using Python and popular data analysis libraries.

