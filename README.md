# 2025-Y2-S1-MLB-B4G2-02--AIML---Data-Preprocessing-and-EDA-Pipeline

1. Overview of the Project

This project focuses on building a data preprocessing and machine learning pipeline for real-estate price prediction.
The dataset (MagicBricks.csv) contains property-related information (such as area, location, number of rooms, price, etc.).

The main goals of this project are:

  - Cleaning and preprocessing the dataset.

  - Handling categorical and numerical features.

  - Applying feature scaling and encoding.

  - Selecting important features using statistical methods.

  - Preparing the data for further predictive modeling.

  - This pipeline ensures a structured workflow that can be reused for similar datasets.

2. Dataset Details

  - Dataset name: MagicBricks.csv

  - Source: Uploaded manually in the notebook (via Google Colab file upload).

  - Shape: Printed in the notebook (df.shape) → gives number of rows and columns.

Exploration done:

.head() → first five records.

.info() → data types and null values.

.describe() → summary statistics of numerical columns.


3. Group Member Roles

Here’s a suggested breakdown of responsibilities :

   - IT24100603 - Handling Missing Data
   - IT24100658 - Target Encoding
   - IT24100654 - Outlier Removing
   - IT24100678 - Min Max Scaling
   - IT24100653 - Add New Feature
   - IT24100637 - Variance threshold

4. How to Run the Code
   - Requirements : Python 3.x
                  : Google Colab
   - Libraries: pip install pandas numpy seaborn matplotlib scikit-learn category_encoders
   - Steps to Execute
         Open the notebook in Google Colab or Jupyter.
         Upload the dataset MagicBricks.csv when prompted.
             from google.colab import files
             uploaded = files.upload()
             Run all cells in order (Runtime > Run all).
   - The notebook will:
       Load the dataset.
       Display shape, info, and description.
       Perform feature encoding and scaling.
       Apply feature selection.
       Use the final preprocessed dataset for training models.
