# Data Wild West - Project Structure

## Introduction
This repository hosts all the necessary resources for the ``"Navigating the Gym Landscape: Analyzing Customer Reviews in Danish Facilities"`` project by the Data Wild West group.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
  - [Code](#code)
  - [Data](#data)
  - [Additional Folders](#additional-folders)
- [Installation](#installation)
- [Usage](#usage)

## Project Structure

### Code
Located in the **"code"** folder:
- `Project_Notebook.ipynb`: Main Jupyter Notebook where all the analyses are performed.
- `libraries/utils.py`:  This file, located in the libraries subfolder, contains all the functions used in `Project_Notebook.ipynb`.

### Data
Located in the **"data"** folder:
- This directory contains both the raw and processed data utilized in the project.

*Note:* The final processed dataset is at `/data/processed/final_reviews.csv`.

### Additional Folders
- `images`: Images used in reports.
- `translations`: Translation files related to the project.
- `visualizations`: Visual representations generated during the project.
- `annotations`: Annotations results, samples and the guideline.
- `report`: The project report.

## Installation
Ensure Python 3.10.11 is installed and then run:
- `pip install -r requirements.txt`

## Usage
To run the notebook and recreate results:
1. Navigate to the project directory.
2. Run `Project_Notebook.ipynb` using the "Run All" feature in VS Code or another IDE.