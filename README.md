# Fitness Tracker Application

A machine learning-powered web application that predicts calories burned during exercise based on individual metrics and provides personalized insights.

## Overview

This Fitness Tracker uses machine learning to predict calorie expenditure during physical activities. The application takes user input parameters such as age, BMI, exercise duration, heart rate, body temperature, and gender to estimate calories burned. Additionally, it provides contextual information by comparing user metrics with the dataset population.

## Features

- **Personalized Calorie Prediction**: Uses a Random Forest Regressor model to predict calories burned based on user inputs
- **Interactive UI**: Intuitive sliders and controls for inputting personal metrics
- **Comparative Analysis**: Shows how your metrics compare to others in the dataset
- **Similar Results**: Displays records from the dataset with similar calorie expenditure
- **Real-time Feedback**: Visual progress indicators during processing

## Technology Stack

- **Frontend**: Streamlit for the interactive web interface
- **Backend**: Python with scikit-learn for machine learning
- **Data Processing**: Pandas for data manipulation and preprocessing
- **Visualization**: Matplotlib and Seaborn for data visualization capabilities

## Dataset

The application utilizes two datasets:
- `exercise.csv`: Contains user metrics (Gender, Age, Height, Weight, Duration, Heart Rate, Body Temperature)
- `calories.csv`: Contains calorie expenditure data

## How It Works

1. The application processes and merges the datasets
2. A Random Forest Regressor model is trained on the processed data
3. User inputs are collected through the Streamlit interface
4. The trained model predicts calories burned based on user inputs
5. Comparative statistics and similar records are displayed

## Installation and Setup

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Installation Steps

1. Clone the repository:
```bash
git clone https://github.com/yourusername/fitness-tracker.git
cd fitness-tracker
```

2. Install required dependencies:
```bash
pip install streamlit pandas numpy matplotlib seaborn scikit-learn
```

3. Run the application:
```bash
streamlit run app.py
```

4. Access the application in your web browser at `http://localhost:8501`

## Acknowledgments

- The datasets used in this project are being referenced from Edunet Foundation
- Special thanks to the Edunet Foundation and Techsaksham teams for their guidance and continuous support to make the project a grand success. 
