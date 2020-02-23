# Coursera Capstone Project
This repository is a demonstration of Coursera Capstone Project Course for IBM Data Science Professional Certificate

## About the project:
This includes the projects in the last course of IBM Data Science Professional Certificate. The course guidelines are to make a simple application using K-means clustering with Foursquare location API.

## Introduction/Business problem:
Every week, we spend two days or one day at least as a weekend. Sometimes, we feel confused about where to spend this weekend, or where should I go. Planning a good weekend will help people feel happier and better. We will create an application that will recommend the users with some places where they can have fun and enjoy their times. The target audience, mostly everyone above the age of 18 years they can use the app to find places to visit in their weekends.

## Data:
The data will be acquired from Foursquare.com depending on the customer location. We will show the users a map with every place they can visit and have a good time around their place.
The foursquare data will consist of many categories and we will only extract the venues, their names, location, category and category id.
We will determine the user location and get all cities and places around the user, for this purpose, there is a readymade dataset of Canada neighborhoods as an example.
The data includes the names of neighborhoods and their postal codes.

## Methodology:
We will obtain the data based on neighborhoods of the user current location from Foursquare, we filter data based on category to select only places suitable for having good times at weekends and holidays.
After extracting the suitable data, we will cluster them using K-means to provide them in groups for the user, so the user can choose something suitable for him/her. Such as clubs/ theaters/ gaming cafes and so on. 

## Results:
The application gets the information based on the user current location successfully and provides a great tool for the user to plan his/her weekends locally.

## Discussion:
The App may fail to get the required information if the city neighborhoods are too limited or have not been added on Foursquare database yet.

## Conclusion:
Finally, this app is considered the initial core for a greater project that can be customized as per the user range, age, and desired places that he/she likes to spend time based on their hobbies for example.

