# Analyse and Predict Daily Steps

![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)

This project focuses on analyzing and predicting my personal daily step count using data analysis and machine learning techniques.

---

## Overview

I collected data of my daily steps over a period of 20 days. The goal of this project is to:

- Explore trends and behavior in my physical activity
- Build a predictive model to forecast the number of steps for the next 10 days
- Visualize actual vs. predicted data

---

## Project Highlights

- Cleaned and processed real-life daily step data
- Visualized step trends over time using line plots
- Built a regression model to make 10-day forecasts
- Compared actual vs predicted step values in a clear visual format

---

## Tools & Technologies

- **Python**
- **Pandas** – for data manipulation
- **Matplotlib / Seaborn** – for data visualization
- **Scikit-learn** – for building the predictive model
- **Jupyter Notebook** – interactive data exploration

---

## Example Visualization

You can generate a line chart that compares actual and predicted steps using the following code:

```python
import matplotlib.pyplot as plt

# Example data (replace with your actual values)
actual_steps = [6534, 7230, 6890, 7020, 7210, 7350, 6900, 7100, 7400, 7500]
predicted_steps = [6600, 7150, 7000, 7050, 7300, 7400, 6950, 7200, 7350, 7450]
days = list(range(1, 11))

plt.figure(figsize=(10, 5))
plt.plot(days, actual_steps, label='Actual Steps', marker='o')
plt.plot(days, predicted_steps, label='Predicted Steps', marker='x')
plt.title('Actual vs Predicted Steps (Next 10 Days)')
plt.xlabel('Day')
plt.ylabel('Steps')
plt.legend()
plt.grid(True)
plt.tight_layout()
plt.show()

![Step Forecast](images/step_forecast.png)

How to Use
Clone this repository.

Open the notebook file (Analyse_and_Predict_Steps.ipynb).

Ensure the dataset file is available and in the correct path.

Run the notebook cell by cell to explore and predict.

Modify the dataset or model to experiment with your own data.

Results
The model predicts step count trends with reasonable accuracy.

Line plots provide intuitive understanding of activity patterns.

Offers a good starting point for applying data science to personal health data.

License
This project is licensed under the MIT License.

Author
Created by Abd_Lekbir kassab 
