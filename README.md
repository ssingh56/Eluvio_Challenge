# Eluvio_Challenge
Scene Segmentation Using MovieScenes Dataset

Name: Sankalp Singh
Email: ssingh56@syr.edu

Challenge Overview
- In this challenge, our task is to predict the scene segmentation for each movie given features for each shot
- One scene contains a series of consecutive shots. To define the problem, we first carry out shot detection for movies and group shots afterward to form scenes, where the scene boundary detection could be regarded as a binary classification problem on shot boundaries
- Dataset includes 64 .pkl files corresponding to 64 movies
- Dataset features:
             - place
             - cast
             - action
             - audio
             - shot_end_frame
             - scene_transition_boundary_ground_truth (target feature)
             - scene_transition_boundary_prediction
             - imdb_id
- We have followed the CRISP-DM methodology to tackle the scene segmentation problem
CRISP-DM consists of following steps:
              - Business & Data Understanding
              - Data Preprocessing, Wrangling and Exploratory Data Analysis
              - Modeling
              - Evaluation
              - Deployment
- Due to lack of computing resources, we have trained our machine learning models on 10 movies instead of all the 64 movies
