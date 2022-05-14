# Recommender System using Collaborative Filtering

1. Install surprise package
2. Read the jokes dataset, check the shape and sample of the dataset
3. Read the ratings dataset, check the shape and sample of the dataset
4. Convert ratings data into surprise data frame format
5. Define the similarity parameters and the algorithm for finding similar users
6. Check the results using the crossvalidation
7. Get the train and test data from surprise data frame and fit the model on train data
8. Get the predictions on test data
9. Write a function to get top 10 predictions for each user
10. Using the top predictions matrix map the jokes to understand the recommendations

# Attributes Description
#### Jokes Dataset
1.ItemID - ID of each Item

2.Joke - Description of each Joke

#### Ratings Dataset
1.UserID - ID of each User

2.ItemID - ID of each Item

3.Rating - Rating for each joke ranging from [-10,10]

### Surprise is a python package used to make recommender systems
http://surpriselib.com/
<br>https://github.com/NicolasHug/Surprise
<br>http://surprise.readthedocs.io/en/stable/index.html



#### Read the jokes dataset, check the shape and sample of the dataset

##### Jokes Dataset
http://eigentaste.berkeley.edu/dataset/
<br>140 Jokes
<br>59132 Users
<br>Reading jokes files
<br>Note - Data is tab seperated
