# Food Rating Prediction using Machine Learning

### Kaggle competition link : [Recipe for Rating: Predict Food Ratings using ML](https://www.kaggle.com/competitions/recipe-for-rating-predict-food-ratings-using-ml)

The challenge revolves around predicting the rating of food recipe.
Participants received a comprehensive dataset comprising recipe names, reviews, and various relevant features.

Submissions were evaluated on **accuracy score**.

## Dataset Description
In this challenge, the goal was to build models that can guess the ratings for each recipe using given information.

### Dataset Overview

Each entry captures a unique culinary story with details such as recipe names, user reviews, and various key features. The task was to explore this rich data and develop predictive models that can forecast the ratings for every recipe.

### Data Files
The dataset is composed of the following files:

* train.csv: The training set, which includes the target variable 'rating' and accompanying feature attributes.

* test.csv: The test set, containing similar feature attributes but without the target variable 'rating' , as it is the variable to be predicted.

* sample_submission.csv: A sample submission file provided in the correct format for competition submissions.

### Columns Description

- **RecipeNumber**: Placement of the recipe on the top 100 recipes list
- **RecipeCode**: Unique ID of the recipe used by the site
- **RecipeName**: Name of the recipe the comment was posted on
- **CommentID**: Unique ID of the comment
- **UserID**: Unique ID of the user who left the comment
- **UserName**: Name of the user
- **UserReputation**: Internal score of the site, roughly quantifying the past behavior of the user
- **CreationTimestamp**: Time at which the comment was posted as a Unix timestamp
- **ReplyCount**: Number of replies to the comment
- **ThumbsUpCount**: Number of up-votes the comment has received
- **ThumbsDownCount**: Number of down-votes the comment has received
- **Rating**: The score on a 1 to 5 scale that the user gave to the recipe. A score of 0 means that no score was given (Target Variable)
- **BestScore**: Score of the comment, likely used by the site to help determine the order comments appear in
- **Recipe_Review**: Text content of the comment

Among the **950** participants, I got **38th** position on the leaderboard with a score of **0.79058**. The **best score** in the competition was **0.80444**.
