<<<<<<< HEAD
# From Playlists to Predictions: Understanding Churn in Sparkify

## Table of Contents
- [Introduction](#introduction)
- [Project Motivation](#project-motivation)
- [File Descriptions](#file-descriptions)
- [File Descriptions](#installation)
- [Result](#result)
- [Instructions](#instructions)
- [Acknowledgments](#acknowledgments)

---

## Introduction <a name="introduction"></a>
Sparkify is a fictional music streaming service, akin to Spotify or Pandora. The provided dataset contains logs of user interactions with the service, whether they're playing songs, logging out, giving a thumbs up/down, etc. These logs also have demographic info for users.

This project's primary goal is to predict user churn. We define churning as when a user confirms the cancellation of the service. Predicting this ahead of time can be highly valuable for the business, as they can start targeting these users with special offers or prioritize user experience improvements based on the feedback.

## Project Motivation<a name="motivation"></a>
Churn rate is a critical metric for any growing business. If the churn rate is high, it indicates that users aren't finding value in the service, leading to decreased revenues and increased costs. By predicting churn, we can take proactive actions to retain users, improving the business's bottom line.

## File Descriptions <a name="files"></a>
- Sparkify_Udc_Project.ipynb: Jupyter notebook containing all the analyses, visualizations, and the model.
- Sparkify_Udc_Project.html: An HTML export of the notebook, useful for viewing the notebook in web browsers.
- README.md: This file, describing the contents of this repository.

## Installation:
The project library will included in requirement.txt file. You need to execute:
pip install -r requirements.txt

Library used : 
- Pandas
- NumPy
- Matplotlib
- Seaborn
- PySpark (including pyspark.ml)

## Results<a name="results"></a>
The project includes exploratory data analysis (EDA) to understand the patterns in user behavior, especially between churned and active users. Some key insights include:

Churned users tend to have fewer interactions with the platform.
The length of listening tends to be shorter for churned users.
Post EDA, several features were engineered for the modeling phase, such as:
Total songs played.
Average songs played per session.
Number of thumbs up/down.
Total length of listening.

The model built using these features resulted in an F1 Score on Test Data: 0.9131, indicating a high precision and recall balance. The top features influencing churn, based on feature importance, are:
Total Session Time
Total Time Registered
Songs Added to Playlist
Number of Friends Added
Average Session Duration

## Acknowledgments<a name="Acknowledgments"></a>
I would like to thank Udacity[https://www.udacity.com/] for this amazing project and the dataset. You can find the Licensing for the data and other descriptive information at the Udacity link available here[https://www.udacity.com/]. Otherwise, feel free to use the code here as you would like!


=======
# Final_Capstone_Udc
Final_Capstone_Udc
>>>>>>> 4942d199e7b60762116856c219ee88b823780405
