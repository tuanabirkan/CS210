# CS210
Data Analysis Project
Music Data Analysis Project

Overview

This project involves the analysis of a music dataset, presumably from a music streaming service or a collection of music tracks. The analysis includes creating visualizations to understand music genre distributions, artist track counts, and playlist activities over time. Additionally, the project entails feature engineering tasks to enhance the data for further analysis or machine learning applications.

Features

The project includes the following features:

Top 10 Genres Distribution: A pie chart that shows the distribution of the top 10 music genres.
Top 20 Artists: A bar chart that displays the top 20 artists based on the number of tracks.
Playlist Activity Over Time: A line chart that represents the number of tracks added to a playlist each month.
Feature Engineering

Two key engineered features are:

Yearly Song Addition Count: The count of songs added to the dataset or playlist each year.
Yearly Genre Diversity Score: A metric that measures the diversity of music genres each year.
Code Description

The Python code provided performs the following tasks:

Extracts the year from a addedDate datetime column and calculates the number of songs added per year.
Calculates the diversity of genres in the dataset on a yearly basis.
Combines these engineered features into a single DataFrame for further analysis.
Calculates the age of a person based on a given birth year relative to the year songs were added.
Maps ages to life stages for demographic analysis.
