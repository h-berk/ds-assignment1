## Serverless REST Assignment - Distributed Systems.

__Name:__ Hasan Berk / 20093361

This repository contains the implementation of a serverless REST API for the AWS platform. A CDK stack creates the infrastructure. The domain context of the API is movie reviews.

### API endpoints.
POST /movies/reviews - add a movie review.
GET /movies/{movieId}/reviews - Get all the reviews for a movie with the specified id.
GET /movies/{movieId}/reviews?minRating=n - Get all the reviews for the movie with the specified ID with a rating greater than the minRating.
GET /movies/{movieId}/reviews/{reviewerName} - Get the review for the movie with the specified movie ID and written by the named reviewer.
PUT /movies/{movieId}/reviews/{reviewerName} - Update the text of a review. (movie ID and reviewer username uniquely identify a review item).

[Include screenshots from the AWS console (API Gateway service) that clearly show the deployed API ( have legible font size). ]
![image](https://github.com/h-berk/ds-assignment1/assets/74901973/ed7afd6e-0565-4e4b-98b1-130bbd816287)

Video Demo: https://www.youtube.com/watch?v=3PYwDhzA-yk
