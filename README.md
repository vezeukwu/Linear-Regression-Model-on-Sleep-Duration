# Random-Forest-Regression-Model-on-Sleep-Duration

## Introduction

Sleep is essential for both physical and mental health, supporting immune functions, muscle recovery, and overall vitality. Quality sleep repairs cells, enhances memory, concentration, and problem-solving skills, improving daily performance and decision-making.
Adequate sleep helps regulate emotions, reducing stress, anxiety, and the risk of mood disorders like depression. In this project, I intend to analyze sleep data from a Sleep app to uncover insights into lifestyle factors affecting sleep quality and its duration.

## Situation
SleepInc. is a start up company that tracks customers sleep pattern from their new tracking app called Sleep Scope app. The company is interested in finding out if there exist a relationship between human life style behaviors such as exercise, occupation etc and sleep quality. My responsibility is to analyze the lifestyle survey data with python to discover relationships between exercise, gender, occupation, and sleep quality. And to Identify patterns leading to insights on sleep quality. I then proceeded to train the Random Forest Regression model to predict sleep duration.

### Data Dictionary
The dataset contains data of sleep and lifestyle metrics for 374 individuals. This dataset contains average values for each person calculated over the past six months. The dataset includes 13 columns covering sleep duration, quality, disorders, exercise, stress, diet, demographics, and other factors related to sleep health.

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

## Exploratory Data Analysis
The Dataset was inspected for duplicate values, missing values, outliers, standardization error and were cleaned.

The relationship between features were examined with interesting fetures noted.

Age and Quality of Sleep: Sleep quality fluctuates with age, showing variability across different age groups. Adults (36-55) have the highest count of poor sleep quality, have the highest physical activity level, while older adults (>55) are the least active.

![Screenshot 2025-03-27 210618](https://github.com/user-attachments/assets/24dc0b19-cf8b-4245-aab2-89e71ab088df)

There is a noticeable fluctuation in sleep duration across different ages. Some age groups (e.g., early 30s) have lower sleep durations compared to others, Sleep duration appears to be relatively low in the late 20s and in the early 30s, sleep duration peaks but then drops around mid-30s. From late 30s to early 40s, sleep duration remains stable with slight variations. Around ages 50 and above, there seems to be an increase in sleep duration meanwhile, Sleep duration appears to stabilize in midlife (40s).

![Screenshot 2025-03-28 060949](https://github.com/user-attachments/assets/3f541154-97c4-45c4-b41c-300e8b3d78c2)

Different professions experience fluctuations in sleep quality, with some occupations having lower or higher averages. Doctors and Nurses Experience Moderate Sleep Quality, Teachers Show Significant Fluctuations with a noticeable dip and rise in sleep quality, Engineers and Accountants Show an Upward Trend while Sales Representatives May Experience Poorer Sleep. 

 ![Screenshot 2025-03-28 093606](https://github.com/user-attachments/assets/344b4ffb-862d-4777-818a-d4c3d1eb2894)
