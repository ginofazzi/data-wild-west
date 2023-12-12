# Data Wild West - Project Structure

This repository contains all the necessary code and resources to reproduce the Data Wild West group project. 

Below is an overview of the key components and their organization:

### Code
Located in the **"code"** folder:

    - Project_Notebook.ipynb: The main Jupyter Notebook where all the analyses are performed.
    - libraries/utils.py: This file, located in the libraries subfolder, 
    contains all the functions utilized in Project_Notebook.ipynb.

### Data
Located in the **"data"** folder:

    - This directory contains both the raw and processed data utilized in the project.
    **NOTE: The final processed dataset is located at /data/processed/final_reviews.csv** 

### Additional Folders
    - "images": Contains images used in the report.
    - "translations": This folder includes any translation files related to the project.
    - "visualizations": Here, you will find visual representations and output generated during the project.
    - "annotations": Contains annotations results, samples and the guideline.

Each folder is structured to provide a clear and organized workflow, ensuring easy navigation and replication of the project's results.

### How to run our notebook and recreate the same results ?

Make sure you are in the right directory where you have all the necessary files, so you can run the following commands below.

We use Python 3.10.11.

    1) pip install -r requirements.txt
    2) "Run All" button if you are using VS Code