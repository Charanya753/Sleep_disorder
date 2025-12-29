
# 💤AI-Powered Sleep Disorder Prediction System
## Problem Statement
 
**Title:** AI-Based Sleep Disorder Prediction System

Sleep disorders such as Insomnia and Sleep Apnea affect a large portion of the population and can lead to serious health issues including fatigue, stress, cardiovascular problems, and reduced quality of life. However, many individuals remain undiagnosed due to lack of awareness, delayed medical consultation, or limited access to healthcare facilities.

Traditional diagnosis methods often require clinical tests and expert analysis, which may not be easily accessible to everyone. Hence, there is a need for an intelligent system that can analyze lifestyle and physiological factors to predict potential sleep disorders at an early stage.

The challenge is to design an AI-based solution that uses patient-related data to accurately predict sleep disorders and assist users in understanding their sleep health.
## Project Overview

This project focuses on developing an AI-powered Sleep Disorder Prediction application that analyzes user data such as sleep duration, physical activity, stress levels, heart rate, and sleep quality to predict possible sleep disorders.

Using machine learning techniques, the system classifies whether a person is likely to have:

No Sleep Disorder

Insomnia

Sleep Apnea

The application is built with an interactive Streamlit-based interface, allowing users to input their details easily and receive instant predictions, making early awareness and monitoring more accessible.## Dataset

The dataset consists of student-related information such as performance scores, learning preferences, and progress details.
You can find the dataset in the sleep_disorder.csv file.
## Tools & Technologies

Pandas: For student data manipulation and analysis.

NumPy: For numerical computations.

Scikit-Learn: For machine learning model development.

Matplotlib: For visualizing student performance trends.

Streamlit: For building an interactive web-based user interface.

## Methodology:

1. Data Preprocessing

Cleaned missing and inconsistent values

Encoded categorical variables

Normalized numerical features for better model performance

2. Model Building

Trained a machine learning classification model to predict sleep disorders

Features such as sleep duration, stress level, and physical activity were used as inputs

3. Evaluation

Model performance evaluated using accuracy and classification metrics

Predictions validated against known labels in the dataset

4. Deployment

Integrated the trained model into a Streamlit web app

Users can enter their health details using sliders and dropdowns to get real-time predictions

Python: For implementing backend logic and ML workflows.

