# TravelTide Customer Segmentation
In this project I worked with generated data from a travel-website. The goal was to cluster the customers in different groups to give specific recommodations for customer retention.


## 01SQL_Query
Filter the data with this query for the different tables (sessions, user, flights, hotels) for active customers and download the csv file to raw/data.

## 02EDA
Looking and analyzing the data, add columns to the different tables, handle errors in the data and saving them in preprocessed_data.

## 03Feature Engineering
Creating a users table with new combined columns from the four tables for the segmentation and saving it in user_features_data.

## 04EDA_and_preprocessing
Making sure the data is ready for Segmentation. And looking more intensly at the data for the clustering in the next step. 
Saving the data inuser_features_data.

## 05Group_and_Clustering
First, with rules: some customers can be clustered manually by simple rules (e.g. high-spenders or no-bookers). The rest is clustered with kmeans.
The single groups are exported again as csv files in groups_data.

## 06Group_Analysis
Visualizing differences between the groups and exporting the complete df with all users, features and groups.
