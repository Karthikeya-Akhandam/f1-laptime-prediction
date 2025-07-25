# f1-laptime-prediction
Advanced machine learning project leveraging real Formula 1 telemetry and session data to predict lap times with high accuracy. Utilizes FastF1 for data retrieval and features exploratory analysis, feature engineering, model training, and visualization.

# Advanced F1 Lap Time Prediction

This repository uses real Formula One telemetry and session data to build and analyze machine learning models for advanced lap time prediction. Powered by FastF1, pandas, and scikit-learn.

## Features
- Automated data retrieval from recent F1 events
- Telemetry & lap analysis (speed, throttle, gear, tire, etc.)
- ML feature engineering, model training & evaluation
- Insightful visualizations for F1 performance understanding

## Getting Started

1. Clone repository
2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Download or cache F1 session data (see `src/data/get_data.py`)
4. Start with exploratory analysis in `notebooks/EDA.ipynb`

## Directory Structure

See the main folders above for scripts and notebooks separation. All source code under `src/`, with Jupyter notebooks under `notebooks/`.

---

## 4. Next Steps: Initial GitHub Commit

After creating the above directories and placeholders:

- `git init`
- `git add .`
- `git commit -m "Initial project structure for F1 advanced lap time prediction"`

This setup will position your project for robust machine learning development and version control. Further steps will focus on scraping and fetching real F1 session data, engineering predictive features, and building your first regression models.
