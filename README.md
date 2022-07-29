# Recommender-Systems

![movies](https://github.com/AbeerMahjoub/Recommender-Systems/blob/main/pic.jpg?raw=true)

**This repo contains some exercises on different recommender system type included in *Hands-On	Recommendation	Systems	with	Python* book:**


- ## Simple Recommender:

  relies on recommending movies based on some metric, in our case we used the weighted average rating, and we considered only movies with enough number of raters.
  
- ## Knowledge-based Recommender:
  
  asking the user about his/her preferences like (genre, duration, timline, etc) then apply a simple recommender on movies that satisfy these conditions.
  
- ## Content-based Recommender:
  - ### Description:
      
      extracting information from description, so the recommender will be ble to recommend movies with similar plots.
      
  - ### Metadata:
    
      combining more information about movies, like the director, top actors, keywords and genres, improves the recommender functionality.
      
- # Collaborative Filter:

   a technique that can filter out items that a user might like on the basis of reactions by similar users.

   - ## BaseLine Model:

      simply rate every movie 3 stars for every user.

   - ## Standard Mean Model:

     outputs the mean rating for the movies by all users who have rated it, assigning each user an equal weight.

   - ## Weighted Mean Model:

     giving more weight for users whose ratings are more similar to the user in question than others whose ratings are not.

   - ## Demographics-based Model:

     see if users	of	the	same	demographic	tend to	have	similar	tastes.	

   - ## KNN:

     use the ratings of k nearest neighbours to filter out items instead of all data.



## Data: [Kaggle](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset).
