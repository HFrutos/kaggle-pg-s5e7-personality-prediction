# Predicting Introverts vs. Extroverts (Kaggle Playground S5E7)

A machine learning project to predict personality traits based on behavioral data from a Kaggle Playground competition.

## Project Overview

The primary goal of this project is to explore the provided dataset, engineer relevant features, and build a robust classification model to accurately predict whether an individual is an introvert or an extrovert. This serves as a practical exercise in a complete data science workflow, from data cleaning and exploration to modeling and submission.

## Project Structure

The repository is organized as follows:

├── data/              # Raw and processed data from the competition
├── notebooks/         # Jupyter notebooks for exploration, feature engineering, and modeling
├── src/               # Source code for reusable functions or pipelines
├── .gitignore         # Specifies intentionally untracked files to ignore
├── requirements.txt   # Lists all Python package dependencies
└── README.md          # This overview file

## Getting Started

To get this project running locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/HFrutos/kaggle-pg-s5e7-personality-prediction.git](https://github.com/HFrutos/kaggle-pg-s5e7-personality-prediction.git)
    cd kaggle-pg-s5e7-personality-prediction
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    python3 -m venv .venv
    source .venv/bin/activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Download the data:**
    Ensure you have your `kaggle.json` API token set up. Then run:
    ```bash
    kaggle competitions download -c playground-series-s5e7 -p data/
    unzip data/playground-series-s5e7.zip -d data/
    ```

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.