# COMP90051 Project2 Group9
# Authorship classification of academic papers

## Collective Team Details (Member's Name/Student ID)
- Cenxi Si 1052447
- Keyi Zhang 1217718
- Zihan Xu


## Description
In this project, we are going to predict the prolific authors of a given document. There are two provided datasets in json format for training and testing. Five features are included in training data: author IDs, year of the paper published, publication venue, paper title and abstract. Authors field, ranging from 0 to 21245, represents a collection of authors. The first 100 authors, identified as the prolific authors, is the prediction target. Year and venue are mapped to a unique integer. Title and abstract are sequences of words, each word is mapped to an index in the range of 1 to 4999. This project aims to determine who of a group of 100 well-known authors contributed to each of the 800 papers in the test set. The right response might be none, one, or many of these writers.


## Files
- Final Approach: final_approach.ipynb
- Alternative Approaches: Alternative_Approaches Folder
- Final Prediction: NN_results.csv
- Data sets: data Folder
- Meet minutes: 3 meeting minutes are in the Meeting Minutes Folder
