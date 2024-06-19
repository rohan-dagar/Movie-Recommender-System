# Movie Metadata Analysis and Recommendation System

## Overview

This project focuses on developing a content-based movie recommendation system using the TMDB 5000 Movie and Credits datasets. The system recommends movies based on various attributes such as genres, keywords, cast, and crew.

## Table of Contents
1. [Introduction](#introduction)
2. [Datasets](#datasets)
3. [Preprocessing](#preprocessing)
4. [Recommendation System](#recommendation-system)
5. [Dependencies](#dependencies)
6. [Installation](#installation)


## Introduction

The goal of this project is to create a recommendation engine that suggests movies to users based on the metadata provided in the TMDB datasets. By leveraging content-based filtering techniques, the system recommends movies similar to a given movie.

## Datasets

The project utilizes two datasets:
1. **TMDB 5000 Movies Dataset**: Contains information about movies such as title, genres, budget, revenue, etc.
2. **TMDB 5000 Credits Dataset**: Contains information about the cast and crew of the movies.

Both datasets are merged and used for building the recommendation system.

## Preprocessing

Data preprocessing steps include:
- Merging the Movies and Credits datasets on the movie ID.
- Cleaning and transforming columns such as genres, keywords, cast, and crew.
- Creating helper functions to extract and process relevant data.

## Recommendation System

The recommendation system is built using content-based filtering:
- Extracts features such as genres, keywords, cast, and crew from the dataset.
- Combines these features to compute similarity scores between movies.
- Recommends movies that have the highest similarity scores to a given movie.

## Dependencies

The project requires the following Python libraries:
- pandas
- numpy
- ast

## Installation

To install the required libraries, use the following command:
```bash
pip install pandas numpy
