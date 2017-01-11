# imdb_movie_finder
This will help you find the right movie for Netflix or Apple 

### Data Base
I got the data base on [Kaggle] (https://www.kaggle.com/deepmatrix/imdb-5000-movie-dataset); the direct link to the data base is [IMDB 5000 Movie Data Set] (https://www.kaggle.com/deepmatrix/imdb-5000-movie-dataset)


### Data Structure
  * Data Frame: 5043 observations of 28 variables
  
   [1] "color"                     "director_name"             "num_critic_for_reviews"   
 [4] "duration"                  "director_facebook_likes"   "actor_3_facebook_likes"   
 [7] "actor_2_name"              "actor_1_facebook_likes"    "gross"                    
[10] "genres"                    "actor_1_name"              "movie_title"              
[13] "num_voted_users"           "cast_total_facebook_likes" "actor_3_name"             
[16] "facenumber_in_poster"      "plot_keywords"             "movie_imdb_link"          
[19] "num_user_for_reviews"      "language"                  "country"                  
[22] "content_rating"            "budget"                    "title_year"               
[25] "actor_2_facebook_likes"    "imdb_score"                "aspect_ratio"             
[28] "movie_facebook_likes"

##### Reading the file

I used read.csv("", stringsAsFactors = FALSE)

##### Column Names and Class

  [1,] "color"                     "character"
 [2,] "director_name"             "character"
 [3,] "num_critic_for_reviews"    "integer"  
 [4,] "duration"                  "integer"  
 [5,] "director_facebook_likes"   "integer"  
 [6,] "actor_3_facebook_likes"    "integer"  
 [7,] "actor_2_name"              "character"
 [8,] "actor_1_facebook_likes"    "integer"  
 [9,] "gross"                     "integer"  
[10,] "genres"                    "character"
[11,] "actor_1_name"              "character"
[12,] "movie_title"               "character"
[13,] "num_voted_users"           "integer"  
[14,] "cast_total_facebook_likes" "integer"  
[15,] "actor_3_name"              "character"
[16,] "facenumber_in_poster"      "integer"  
[17,] "plot_keywords"             "character"
[18,] "movie_imdb_link"           "character"
[19,] "num_user_for_reviews"      "integer"  
[20,] "language"                  "character"
[21,] "country"                   "character"
[22,] "content_rating"            "character"
[23,] "budget"                    "numeric"  
[24,] "title_year"                "integer"  
[25,] "actor_2_facebook_likes"    "integer"  
[26,] "imdb_score"                "numeric"  
[27,] "aspect_ratio"              "numeric"  
[28,] "movie_facebook_likes"      "integer"  
