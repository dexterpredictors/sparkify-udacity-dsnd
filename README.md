# sparkify udacity capstone project
Predicting user churn for a song streaming company

In this project, we analyze the data from a song application to predict the churn from users. The dataset (128 MB) we use here is a subset of the whole data. We use the power of apache spark to perform data manipulations and build our models for this problem.

Churn is defined as Submit Downgrade or Cancellation Confirmation events. If a user has at some instance performed the above two activities, he is considered a churned user.

We calculate the following metrics on which we build our models.

  1. average number of songs per session
  2. Total number of thumbs down
  3. Total number of thumbs up
  4. Total number of errors encountered
  5. Number of Add to Playlist events
  6. Number of Add Friends events
  7. Total number of songs played
  
Gradient Boosted Tree Classifier performs the best on the dataset provided which provides a F1 score of 0.9067.

The code can be found at [Sparkify.ipynb](https://github.com/savinay/sparkify---udacity-dsnd/blob/master/Sparkify.ipynb)

The blog post about the details of the findings can be found at [Medium Post](https://medium.com/@savinaynarendra/sparkify-project-predicting-user-churn-8d9ee4185274)

