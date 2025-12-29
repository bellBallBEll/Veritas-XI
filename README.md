# Veritas XI: AI-Powered Football Analytics

## Overview

Veritas XI is a football analytics web application designed to provide insightful, rule-based conclusions on individual player performance. By scraping statistical data, this platform aims to offer unique analytical perspectives beyond traditional statistics, helping users understand player roles and contributions in a deeper context.

This project is developed as an IB Personal Project to showcase skills in data science and web development.

## Features (Planned)

* **Player Data Scraping:** Automated extraction of detailed player statistics from public football data sources (e.g., FBref.com).
* **Intelligent Player Analysis:** A logical, rule-based AI engine that applies defined rules and statistical thresholds to generate unique textual conclusions about player strengths, weaknesses, and archetypes.
* **Interactive Web Interface:** A user-friendly web application where users can search for players, view their statistics, and read AI-generated insights.
* **Data Visualization:** Interactive charts and graphs to visually represent player performance.
* **Player Clustering (Stretch Goal):** Using unsupervised learning to group players into statistically similar archetypes.

## Technologies Used

* **Python 3.13:** Core programming language.
* **Web Scraping:** `requests`, `BeautifulSoup4`
* **Data Analysis:** `pandas`, `numpy`
* **AI/Machine Learning:** `scikit-learn` (for clustering stretch goal)
* **Web Framework:** `Flask` or `FastAPI` (for backend API)
* **Frontend:** HTML, CSS, JavaScript
* **Data Visualization:** `Plotly.js` (for visualization stretch goal)
* **Git:** Version control system.
* **Google Chrome or Microsoft Edge browser**

## Getting Started

Follow these steps to set up and run Veritas XI on your local machine for development and testing purposes.

### Prerequisites

* Python 3.8+ installed on your system.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/VeritasXI.git](https://github.com/YourUsername/VeritasXI.git)
    cd VeritasXI
    ```
    (Remember to replace `YourUsername` with your actual GitHub username)

2.  **Create and activate a virtual environment:**
    * **macOS/Linux:**
        ```bash
        python3 -m venv venv
        source venv/bin/activate
        ```
    * **Windows (Command Prompt):**
        ```bash
        python -m venv venv
        venv\Scripts\activate.bat
        ```
    * **Windows (PowerShell):**
        ```bash
        python -m venv venv
        .\venv\Scripts\Activate.ps1
        ```

3.  **Install the required Python packages:**
    ```bash
    pip install -r requirements.txt
    ```
    (Note: The `requirements.txt` file will be generated later once you start installing packages like `requests`, `beautifulsoup4`, etc., using `pip freeze > requirements.txt` after you've installed them.)
