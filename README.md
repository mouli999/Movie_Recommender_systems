# Movie_Recommender_systems
Created a recommender system to show personalized movie recommendations based on ratings given by user and other users similar to them in order to improve user experience 
The data set actually consists of 3 differnet data tables 
1. User data set
2. Movies data set
3. Ratings data set

Steps for building the recommendation system.

1. Read the data files and formatted them to proper workable format and merging the data files to one single dataframe.
2. Did preprocessing and cleaning and modifying the data wherever required.
3. Performed EDA
4. Performed Feature Engineering
5. Visualized the data to get better understanding of underlying distribution of various categories
6. Grouped the data and created pivot table and fill the nan values
7. Did item item approach and by using pearson and cosine correlations developed a recommendation system where it can take movie name from a user and can recommend a 5 similar movies.
8. Similarly done user user similarity approach and developed a system to find simialr users and then the movies
9. Developed a matrix factorization method and calculated all probable ratings of all users and all movies.
