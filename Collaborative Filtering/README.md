Implement a Movie Recommendation System and run it on the Movie Lens Dataset (Train vs Test). <br /><br />
Measure performance on test set using RMSE (Root Mean Square Error) <br /><br />
First, compute user-user similarity based on the ratings and movies in common <br /><br />
Second, make rating predictions on the test set following the KNN idea: a prediction (user, movie) is the weighted average of other users' rating for the movie, weighted by user-similarity to the given user. <br /><br />
