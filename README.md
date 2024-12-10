# Klempoken Analysis

Klempoken Analysis is a project aimed at plotting, analyzing, and predicting sales trend for Klempoken MSMEs. This repository provides tools for data preprocessing, analysis, visualization, and forecasting to help Klempoken MSMEs make informed decisions.

## Features

- **Data cleanning**: handles missing values, type casting, and parsing.
- **Visualization**: Generate meaningful plots for better insight.
- **Forecasting Model**: Implement a time series forecasting technique ([<u>Prophet</u>](https://facebook.github.io/prophet/) by Meta)

## Requirements

This program built using python or rather jupyter notebook (version 3.11.7), with several libraries and tools, such as:

- **Pandas** for data manipulation.
- **Matplotlib** and **Seaborn** for data visualization.
- **Prophet** for time series forecasting.

## Setup

1. Clone the repository

```bash
git clone https://github.com/bryanfks-dev/Klempoken-Analysis
cd klempoken-analysis
```

2. Set up a virtual environment (Optional)

```bash
python3 -m venv venv
```

3. Activate the virtual environment (Optional)

```bash
# On MacOS / Linux:
source venv/bin/activate

# On Windows:
.\venv\Scripts\activate
```

4. Install the required depedencies

```bash
pip install -r requirements.txt
```

## Usage

To run the analysis program:

```bash
jupyter execute plot_analysis.ipynb
```

To run the forecast program:

```bash
jupyter execute forecast.ipynb
```
