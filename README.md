# Predicting and Analyzing Air Quality Patterns

## Project Overview
This project uses the "Air Quality" dataset to predict pollution levels based on hourly sensor readings. A machine learning pipeline was built that includes data cleaning, feature engineering, and the training of a Random Forest Classifier. The final model successfully classifies pollution levels (Low, Medium, High, Very High) with an accuracy of over 99%.

---

## How to Run This Project

### Prerequisites
- Python 3.8 or higher
- `pip` for package management

### Setup Instructions

1.  **Clone the Repository**
    ```bash
    git clone <your-repository-url>
    cd <your-repository-folder>
    ```

2.  **Create and Activate a Virtual Environment** (Recommended)
    ```bash
    # For Windows
    python -m venv venv
    venv\Scripts\activate

    # For macOS/Linux
    python -m venv venv
    source venv/bin/activate
    ```

3.  **Install Dependencies**
    This project uses a few Python libraries. Install them using the `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the Analysis**
    The entire analysis is contained within the `air_quality_analysis.ipynb` colab Notebook. Google colab  to run it.
    ```bash
    Google Colab
    ```
    Once Colab opens in your browser, open the notebook and run the cells sequentially.

---

## Files in This Repository
- `air_quality_analysis.ipynb`: The main Colab Notebook containing all code for the analysis and modeling.
- `AirQuality.csv`: The raw dataset used for this project.
- `requirements.txt`: A list of required Python packages for easy installation.
- `REPORT.pdf`: One-Page Write-up
- - `README.md`: This file.
