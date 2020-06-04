# Airbnb seattle data case study

## Table of contents
* [Motivation](#motivation)
* [In this notebook I explored these three questions](#in-this-notebook-i-explored-these-three-questions)
* [Results](#results)
* [Medium Post of the analysis](#medium-post-of-the-analysis)
* [Required Packages](#required-packages)
* [Acknowledgements](#acknowledgements)

## Motivation:

As not all people have the money to travel anytime they want, we tend to search for the cheapest prices.


## In this notebook I explored these three questions:

1. What's the cheapest month to travel to Seattle?
2. The realtionship between the prices and the number of available listings?
3. Do cheaper listings have lower ratings or not necessarily?

## Results:

- January is the cheapest month to visit Seattle.
- There are no enough evidence that the prices and the number of available listings are correlated.
- It's not necessarily that cheaper listings have lower ratings.

## Medium Post of the analysis:

Medium post can be found [here](https://medium.com/@asmaHelmy/visiting-seattle-on-a-budget-here-are-a-few-tips-e2362e7ac7fa)

## Repos' Files:
.
├── Airbnb_seattle_data.ipynb
├── README.md
└── seattle_airbnb_data
    ├── calendar.csv
    └── listings.csv


- seattle_airbnb_data: folder includes the data; 2 csv files (Listings, Calendar).
	- calendar.csv: includes listing id and the price and availability for that day
	- listings.csv: includes full descriptions and average review score
- Airbnb_seattle_data.ipynb: Notebook of analysis
- README.md: this file.

## Required Packages:

- python3
- pandas
- matplotlib
- datetime

## Acknowledgements:

- This project was done as a part of Udacity's Data Scientist Nanodegree.
- Data used in this analysis is from Kaggle [Link](https://www.kaggle.com/airbnb/seattle/data)
