## Our project repository: 
https://github.com/lavenderliao/Final-Proejct

## What Our project is about

This project allows users to get the rating for the movie, 
the sentiment analysis results on the movie reviews, 
the similarity result on the first and second reviews,
and the most common words used in the reviews on IMDB,
when entering an IMDB ID for a movie.

## How the code works
The backend code contains functions that use movie ID as input to get the rating and comments of the movie from the IMDB website. After getting the comments, three functions are used to generate most common word list, sentiment analysis result, and similarity result. Based on the results, one function is used to judge if a movie could be recommended (if the rating is over 7 and the compound value in sentiment analysis result is over 0.8).  

The frontend code contains a function that get the input(movie ID) from the user, deploy the backend code to generate the result, and present the result using the html template.

## Sample Result

For the movie Bullet train (Movie ID: 12593682), a sample result would look like this:  

![微信图片_20221206235152](https://user-images.githubusercontent.com/112440325/206091540-106357b3-4cfd-4854-a611-cf22f10ac557.png)
