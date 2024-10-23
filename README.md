# Mess Wastage Predictor - Machine Learning and Web Development

## Overview

The **Mess Wastage Predictor** is a project developed to tackle the issue of food wastage in college messes by designing a predictive model to estimate food consumption. By optimizing meal preparation, this system aims to minimize food wastage while ensuring adequate food availability for students.

Given the challenge of collecting real-world data during the initial phase, this project will use **synthetic data** based on assumptions about student attendance, meal preferences, weekdays versus weekends, and special events. Once developed, the model should also be able to adapt to dynamic factors such as holidays, menu changes, and unexpected events.

By applying machine learning techniques to predict food demand for different meals, this project seeks to minimize excess preparation, reduce waste, and potentially save costs in mess operations.

## Problem Statement

- **Objective**: Develop a predictive model that estimates food consumption in college messes and optimizes meal preparation.
- **Initial Challenge**: Lack of real-world data requires teams to generate approximated data based on assumptions.
- **Goal**: Use synthetic data to train machine learning models that predict food demand and optimize mess operations.
  
## Assumptions and Data Generation

The initial dataset is based on the following factors:

- **Student Attendance**: Estimated attendance for each meal.
- **Meal Preferences**: Popularity of different food items.
- **Day of the Week**: Weekdays versus weekends.
- **Special Events**: Holidays, festivals, or other events that might affect meal consumption.

## Model Requirements

The developed model should:

1. **Predict Food Demand**: Estimate the number of servings needed for different meals.
2. **Reduce Food Wastage**: Minimize over-preparation of food to cut down waste.
3. **Adapt to Dynamic Changes**: Handle variables such as holidays, unexpected events, and menu variations.
4. **Learn from Real Data**: Once real-world data is available, the model should be refined for more accurate predictions.

## Technology Stack

- **Programming Language**: Python
- **Data Generation**: Python libraries for synthetic data creation (e.g., `numpy`, `pandas`)
- **Machine Learning**: Scikit-learn, TensorFlow/PyTorch
- **Visualization**: Matplotlib, Seaborn
- **Version Control**: Git and GitHub

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/adityabagla7/Mess-wastage-predictor.git
