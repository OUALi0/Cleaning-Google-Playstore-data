# Project Title

Data Analysis of Google Play Store Apps

## Introduction

This project involves the analysis of Google Play Store apps. The goal is to extract insights and trends related to app categories, ratings, sizes, and other attributes. The analysis includes data cleaning, processing, and visualization to answer various questions about the apps.

## Dataset

The dataset used in this project is a CSV file containing information about Google Play Store apps. It includes features such as app name, category, rating, reviews, size, installs, and more.

## Requirements

- Python 3.7 or above
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/project.git
   cd project
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Load the provided notebook file `project.ipynb`.

3. Run the cells sequentially to perform the analysis.

## Steps

The notebook is organized into the following sections:

1. **Loading the Dataset**: Load the dataset into a Pandas DataFrame.
2. **Data Cleaning**: Handle missing values and correct data types.
3. **Exploratory Data Analysis (EDA)**: Generate various plots to visualize the data.
   - Distribution of app categories
   - Ratings vs. Reviews
   - Size vs. Installs
4. **Feature Engineering**: Create new features if needed.
5. **Answering Specific Questions**: Perform targeted analyses to answer specific questions.
   - Most common app category
   - Top 10 apps by number of reviews
   - Free vs. paid apps distribution
   - Most popular game app by reviews
   - Total data transferred for the most popular lifestyle app

## Results

- **Most Common Category**: Identified the most common app category in the dataset.
- **Top 10 Apps by Reviews**: Listed the top 10 apps based on the number of reviews.
- **Free vs. Paid Apps**: Analyzed the distribution of free and paid apps.
- **Popular Game App**: Found the most popular game app by number of reviews.
- **Data Transferred**: Calculated the total data transferred for the most popular lifestyle app in Tebibytes (Tb).

## Authors

- [@Oualid El-Ouardi](https://github.com/OUALi0)
