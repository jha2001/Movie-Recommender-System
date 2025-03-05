# Movie-Recommender-System

# Overview #

The purpose of a recommendation system basically is to search for content that would be interesting to an individual. Moreover, it involves a number of factors to create personalised lists of useful and interesting content specific to each user/individual. Recommendation systems are AI based algorithms that skim through all possible options and create a customized list of items that are interesting and relevant to an individual. These results are based on their profile, search/browsing history, what other people with similar traits/demographics are watching, and how likely are you to watch those movies. This is achieved through predictive modeling and heuristics with the data available.


# Types Of Recommender System: #

  ### 1. Content Based:

      This method recommends movies based on a user’s previous choices and the characteristics of the movies.
      
   **How It Works:**

      * It analyzes movie features such as genre, director, actors, and description.
      * It compares these features to movies a user has already watched and liked.
      * It suggests movies that are similar to those preferences.


  ### 2. Collaborative Based:

      This method recommends movies based on what similar users have watched and liked.
      
   **Types:**

    1.User-Based Collaborative Filtering:
    
      * Finds users with similar tastes and recommends movies that those similar users liked.
      * Example: If User A and User B both liked Avengers, and User B also liked Iron Man, then Iron Man will be recommended to User A.
    
   2. Item-Based Collaborative Filtering:

      * Finds similar movies based on user ratings.
      * Example: If many users who liked The Dark Knight also liked Joker, then Joker is recommended to someone who liked The Dark Knight.

### 3. Hybrid Based:
    
    This combines content-based filtering and collaborative filtering to improve recommendation accuracy.

**How It Works:**

   * Uses content-based filtering to find similar movies.
   * Uses collaborative filtering to recommend movies liked by similar users.
   * Merges both results to suggest the best options.
        
  
