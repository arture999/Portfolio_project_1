# Arturo's Portfolio

Welcome to my portfolio project! In this project, I've used Python to perform a comprehensive analysis of Uber Eats data and restaurant locations. Below, you'll find an overview of the project and its components.

## Table of Contents
- [Introduction](#introduction)
- [Folder Description](#Folder-Description)



## Introduction
In this portfolio project, I've applied my Python skills to web scrap Uber Eats data and restaurant locations.
The goal was to gain insights, visualize patterns, and extract valuable information from the available datasets.


## Folder Description
- **`/data`**: This directory contains the dataset files used for the data scrapping.
   - **`/categorias.txt`**: list of the categories that are used by Uber eats.
- **`/scripts`**: contains all the scripts used for scraping in the form of Jupyter Notebooks.
   - **`/Ubereats_states_cities_english.ipynb`**: contains the scripts to get all the states and cities where Uber eats operates in Mexico.
   - **`/Ubereats_categories.ipynb`**: contains the code used to get all the urls of restaurantes in Mexico city(only that city).
   - **`/restaurants_details_mexico-city.ipynb`**: code to iterate each of the urls got it and scrape all the details of the restaurants in Mexico city.
- **`/results`**: Any generated results, reports, or visualizations are stored in this directory.
    - **`/states_cities_english.csv`**: Data obteined from the first script "Ubereats_states_cities_english", contains all the cities and states of Ubear eats Mexico.
    - **`/links_restaurants.csv`**: Data obteined from the second script "Ubereats_categories", contains all the urls for all the restaurants in Mexico City.
    - **`/details_restaurants.csv`**: Data obteined from the last script "restaurants_details_mexico-city", contains all the details of each restaurant in Mexico city.
      


1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Arturo/Python-Portfolio.git
