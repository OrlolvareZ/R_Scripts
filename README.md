# R Scripts

This is a collection of Jupyter Notebooks that contain R code done in the Big Data course at college, where I've learned how to:

* Create, join and mutate dataframes
* Read and write to files
* Plot relevant information to gain insights
* Use common machine learning models (as well as the problems where they can be applied):
    * Linear regression
    * Logistic regression
    * Linear discriminant analysis
    * K-nearest neighbors

## movies_analysis

Two notebooks where I read JSON files that contain data about movie ratings, the users that rated them and several information about the rated movie.

* In rate_per_occupation_analysis, the files are read and joined, and then a scatter plot is drawn in
    order to see how the occupation is related to the movie rating. Later, a linear regression model is trained
    to gain further insight into the correlation of these two variables, and to make a prediction given the
    occupation.
* In movie_analysis, an aribitrary criteria must be defined to solve three given formulations, to report the most popular movies and where they are watched, and to compare how much of the movies are seen by the male users in the sample against the female ones. This is an excercise of finding a useful chart and to practice how to build a strong criteria, and then compare it to the classmates' ones.

## hotel_reserv_analysis

In this notebook, a hotel bookings dataset (in CSV format) is read, which contains rows that describe several parameters of multiple bookings and whether they were cancelled or not.

An instance of a KNN model is trained and then evaluated using a confussion matrix. The goal of the model is to predict wether or not a booking was cancelled or not.

## ML_model_collage

An exercise of formulating three statements based on the movie ratings dataset, each of which must be solved using one of the three ML models that the classmates taught in the block (Log. R, LDA and KNN).

## correlation_analysis

A one-day long test where a random prompt is given and it must be solved using the assigned model.

Here, I was asked to use the logistic regression model to make predictions on the acceptance of a movie (whether the user finds it good or bad), based on the users' age and gender. I also used a correlation matrix to aid my conclusion.

## wordcloud_w_remote_kernel

A notebook that uses a jupyter server hosted on a Oracle Linux 7.9 virtual machine, where I used the `wordcloud` library to generate a word cloud based on the output of Hadoop's word count example, given 4 different sources of text.