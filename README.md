# Academy Awards: rewarding WHITENESS and MALENESS since 1928

Final College Thesis by Gerard Vinyes Sanchez.

## Prerequisites
To run this project MongoDBCompass and Python in Jupyter Notebook need to be installed.

## Introduction
The code in this project uses Machine Learning to predict the winners of the Academy Awards. The repository contains a folder called *data* containing the 11 datasets needed for the execution, the Python code that performs the data loading and cleaning plus the Academy Awards predictions and the written thesis.

## Data files
The files in the data folder are:
- the_oscar_awards.csv: dataset with the Academy Awards nominees.
- golden_globes_awards.csv: dataset with the Golden Globes nominees.
- bafta_awards.csv: dataset with the Bafta's nominees.
- vis_effects_awards.csv: dataset with the Visual Effects Society nominees.
- sag_awards.csv: dataset with the Society Actors Guild nominees.
- awards.csv: dataset with the number of Academy Awards, Golden Globes and Baftas wins and nominees of every film nominated in the Academy Awards.
- country_continent.csv: dataset with the country and continent of the films nominated for International Feature Film
- international_directors.csv: dataset with the directors of the films nominated for International Feature Film
- ratings.csv: dataset with the IMDB ratings of the films nominated for Best Picture
- race_gender_df: dataset with the race and gender of the nominees from 13 out of the 23 categories in the Academy Awards.
- ID_map_df.csv: dataset with the CinemaGoer ID of every film nominated in the Academy Awards.

## Execution
The Python file doesn't contain a main, it needs to be run through Jupyter Notebook.

## Goal
The goal of this project is to predict the winners of the Academy Awards based on other awards that are awarded before this as well as the characteristics of the nominees. Right now it works for the 2023 nominations but it is designed to be easily modified to work for other future ceremonies just by adding the new nominations and changing a few parameters.
