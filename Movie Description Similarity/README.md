# Movie Description Similarity

## Description
This project uses the Spacy library to find the most similar movie to a given description. It reads a list of movie descriptions from a text file, converts the data to a list, and calculates the similarity between the given description and each movie description. The movie with the highest similarity is returned.

## Importance
This project can be useful in movie recommendation systems or for individuals looking for similar movies based on a description they provide.

## Table of Contents
* Installation
* Usage


## Installation
* Clone the repository: git clone `https://github.com/your_username/your_project.git`
* Install the required libraries by running `pip install spacy pandas`
* Download the Spacy model by running `python -m spacy download en_core_web_md`
* Place your movie descriptions in a text file separated by tabs, with one description per line.

## Usage
* Initialize the spacy model.
* Read in the movie descriptions from the text file.
* Call the `next_movie` function with a description.
* The function will return the most similar movie to the description.


