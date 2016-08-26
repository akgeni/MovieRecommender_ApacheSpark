# MovieRecommender_ApacheSpark
MovieRecommender Using ALS Algorithm(Collaborative Filtering)

###Lets start with some concepts:

Collaborative Filtering : If a user A has the same opinion as of User B on some issue, then A is likely to have B's opinion on different
issuses.
Definitely it is better than recomending randomly.

### Data Description:
It is subset of MovieLens dataset http://grouplens.org/datasets/movielens/

Number of Movies : 27278

Number of Ratings : 20000263


### How to Run?
To run You need DataBricks community Account.(Free 6GB Cluster) :)
import this notebook, And run-all. 
It will recommend you some movies. But Hey don't you want movie recommendation for yourself. :)
#### Giving Inputs to the recommender.
You need to fill in your ratings:
my_user_id = 0

my_rated_movies = [

  (my_user_id, 318, 3),
  
  (...)
  
]

