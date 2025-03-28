# Linear-Regression-Model-on-Sleep-Duration

## Introduction

Sleep is essential for both physical and mental health, supporting immune functions, muscle recovery, and overall vitality. Quality sleep repairs cells, enhances memory, concentration, and problem-solving skills, improving daily performance and decision-making.
Adequate sleep helps regulate emotions, reducing stress, anxiety, and the risk of mood disorders like depression. In this project, I intend to analyze sleep data from a Sleep app to uncover insights into lifestyle factors affecting sleep quality and its duration.

## Situation
SleepInc. is a start up company that tracks customers sleep pattern from their new tracking app called Sleep Scope app. The company is interested in finding out if there exist a relationship between human life style behaviors such as exercise, occupation etc and sleep quality. My responsibility is to analyze the lifestyle survey data with python to discover relationships between exercise, gender, occupation, and sleep quality. And to Identify patterns leading to insights on sleep quality. I then proceeded to train the Random Forest Regression model to predict sleep duration.

### Data Dictionary
The dataset contains data of sleep and lifestyle metrics for 374 individuals. This dataset contains average values for each person calculated over the past six months. The data is saved as sleep_health_data.csv.

The dataset includes 13 columns covering sleep duration, quality, disorders, exercise, stress, diet, demographics, and other factors related to sleep health.

Column Description

Person ID An identifier for each individual.
Gender The gender of the person (Male/Female).
Age The age of the person in years.
Occupation The occupation or profession of the person.
Sleep Duration (hours) The average number of hours the person sleeps per day.
Quality of Sleep (scale: 1-10) A subjective rating of the quality of sleep, ranging from 1 to 10.
Physical Activity Level (minutes/day) The average number of minutes the person engages in physical activity daily.
Stress Level (scale: 1-10) A subjective rating of the stress level experienced by the person, ranging from 1 to 10.
BMI Category The BMI category of the person (e.g., Underweight, Normal, Overweight).
Blood Pressure (systolic/diastolic) The average blood pressure measurement of the person, indicated as systolic pressure over diastolic pressure.
Heart Rate (bpm) The average resting heart rate of the person in beats per minute.
Daily Steps The average number of steps the person takes per day.
Sleep Disorder The presence or absence of a sleep disorder in the person (None, Insomnia, Sleep Apnea).
