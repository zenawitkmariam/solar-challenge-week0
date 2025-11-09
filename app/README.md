
---

# Solar Irradiance Visualization Dashboard

This repository contains a **Streamlit** app that visualizes solar irradiance data, including metrics like **Global Horizontal Irradiance (GHI)**, **Direct Normal Irradiance (DNI)**, and **Diffuse Horizontal Irradiance (DHI)** for different countries. The app includes interactive visualizations to explore solar energy potential.

## Table of Contents

* [Overview](#overview)
* [Features](#features)
* [Project Structure](#project-structure)
* [Installation](#installation)
* [How to Run the App Locally](#how-to-run-the-app-locally)
* [Deployment](#deployment)
* [Contributing](#contributing)

## Overview

This **Streamlit** app allows users to:

* Compare solar irradiance metrics (GHI, DNI, and DHI) for multiple countries.
* Visualize summary statistics such as mean, median, and standard deviation.
* Interact with various visualizations like **bar charts** and **box plots** to explore the data.

The app aims to help analyze solar energy potential across different countries, offering insights into how solar energy might vary regionally.

## Features

* **Interactive Filters**: Users can filter data by country and solar irradiance metrics (GHI, DNI, DHI).
* **Summary Statistics**: The app shows statistics like mean, median, and standard deviation of GHI, DNI, and DHI for each country.
* **Visualizations**:

  * **Bar Chart**: Visualizes average GHI by country.
  * **Boxplot**: Shows the distribution of GHI, DNI, and DHI for each country.
* **Dynamic Plotting**: Users can interact with different metrics and countries to view customized plots.

## Project Structure

```
solar-challenge-week0/
├── app/
│   ├── __init__.py        # Initialization file for app module
│   ├── main.py            # Main Streamlit app script
│   ├── utils.py           # Utility functions for data processing and visualizations
├── scripts/
│   ├── __init__.py        # Initialization file for scripts module (optional)
│   └── README.md          # Project documentation (this file)
└── requirements.txt       # List of Python dependencies
```

* **app/main.py**: The main entry point for the Streamlit app, which controls the layout and visualizations.
* **app/utils.py**: Contains utility functions for generating plots and summarizing data.
* **scripts/README.md**: A secondary readme for any additional script documentation (optional).

## Installation

To set up this project locally, follow these steps:

### 1. Clone the repository:

```bash
git clone https://github.com/your-username/solar-challenge-week0.git
cd solar-challenge-week0
```

### 2. Create a virtual environment:

```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies:

```bash
pip install -r requirements.txt
```

### 4. Install Streamlit (if not already installed):

```bash
pip install streamlit
```

## How to Run the App Locally

1. Navigate to the project directory where `main.py` is located:

   ```bash
   cd solar-challenge-week0/app
   ```

2. Run the Streamlit app:

   ```bash
   streamlit run main.py
   ```

3. The app will launch in your browser at `http://localhost:8501`, and you can start interacting with the visualizations.

## Deployment

### Deploy to Streamlit Cloud:

1. Push the project to **GitHub**:

   ```bash
   git push origin main
   ```

2. Go to [Streamlit Community Cloud](https://share.streamlit.io/), log in, and create a new app.

3. Link your **GitHub repository** and select the file path to `main.py` for deployment.

4. After deployment, you’ll get a public URL where you can share your app with others.

### Example Deployment URL:

```
https://share.streamlit.io/your-username/solar-challenge-week0/app/main.py
```

## Contributing

Contributions are welcome! If you find a bug or want to add a new feature, feel free to open an issue or a pull request. Please follow the steps below to contribute:

1. Fork the repository.
2. Clone your fork to your local machine.
3. Create a new branch (`git checkout -b feature-branch`).
4. Make your changes and commit them (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a pull request.

---

### Notes:

* **Requirements File**: If you haven't already created a `requirements.txt` file for your project, run this command to generate it:

  ```bash
  pip freeze > requirements.txt
  ```
  

---

