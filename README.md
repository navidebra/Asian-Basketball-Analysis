This Notebook covers the process of analyzing, and visualizations of FIBA international events data using Python 3.9.

This structure can only be used for FIBA international events, collected from the official website available publicly.
The teams game by game data needs to be collected and aggregated in one excel file for the program to be used.
The visualization covers only Attempts share of total Attempts including Free Throws to depict teams play style in each tournament for comparison

# Libraries Used
The following python libraries were used in this project.
- matplotlib == 3.5.1
- Pandas == 1.4.1


# Project Motivation
For this project I was interested in using FIBA Asia and World Cup Official data feed to better understand:

1. How Asian Teams are currently playing?
2. Why Teams Need to Abandon Mid-Range Attempts?
3. How Team’s Were Playing Before?
4. How to Know When to Stop?


# File Description
Basketball Data Analysis.ipynb: Notebook Containing the data analysis.

Data/Average.xlsx: All Tournaments Aggregated Average Attempts and Points by different scoring category data.

Data/*/: Containts Folder for each of the following tournament names: 2019  FIBA, Asian Qualifiers, 2019  FIBA, World Cup, 2022  FIBA, Asia Cup, 2023  FIBA, Asian Qualifiers

Data/*/: each Tournament Folder contains two of the following files:

Data/*/Games.xlsx: given tournament game by game teams data

Data/*/Teams Average.xlsx : given tournament average teams data

Data/Logos: Containts Folder for each of the above mentioned tournaments

Data/Logos/*: each Tournament Folder contains images of participated countries' flags


# Results Summary

In this analysis I take a look at how Asian teams used to play and are playing basketball currently according to FIBA last 4 tournaments.

1- I examined how teams are playing currently and how they performed in the previous World Cup and Asian Qualifiers, which showed that **more attempts closer to the rim**, **shoot more 3s**, and **fewer mid-range shots**.

2- When you look at how different methods of scoring were related to success the same priority pattern emerges. Although, different strategies and players require different focus on each category, one thing remains clear:

**The Era of Mid-Range is Over**

Go to my blog to read the full article:
https://medium.com/@navidebra/where-asia-stands-in-modern-basketball-8955281b79e3

- ## Data Source: https://fiba.basketball
- ## Acknowledgements:

  Dataset credit

  FIBA has partnered with genius sports to provide live feed data from basketball games all over the world, data is publicly accessible on official FIBA    website.


