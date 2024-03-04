# Airbnb Seattle Dataset Analysis

## Table of Contents
1. [Installation](#installation)
2. [Project Motivation](#project-motivation)
3. [File Descriptions](#file-descriptions)
4. [Results](#results)

## Installation
The following Python packages were used:
- pandas
- matplotlib
- seaborn
- scikit-learn
- numpy

Ensure you are using Python version 3.9.7 for compatibility.

## Project Motivation
For this project, the Seattle Airbnb Dataset was chosen. Since 2008, Airbnb has been facilitating a distinctive and personalized way of travel for both guests and hosts. This dataset, a component of the Airbnb Inside initiative, outlines the listing activity of homestays in Seattle, WA.

This dataset could be utilized by an investor seeking to purchase a condominium and lease it through Airbnb. The investor may be interested in determining the optimal district for acquiring a flat and strategies for achieving a high occupancy rate.

Key business questions are:

- Which neighborhoods in Seattle are the most popular?
- What are the peak and off-peak months in terms of expense and activity for staying in an Airbnb in Seattle?
- What variables hold the most significance in attaining a high occupancy rate?

## File Descriptions
The Seattle dataset encompasses the following Airbnb activities:
- Listings, comprising comprehensive descriptions and average review scores.
- Reviews, featuring unique identifiers for each reviewer along with detailed comments.
- Calendar, incorporating listing IDs, daily prices, and availability information.

The Jupyter Notebook `main.ipynb` contains the code and results.

## Results
In this Udacity project, the dataset was analyzed to address key business questions for potential Airbnb investors in Seattle. The focus included identifying optimal districts and strategies for achieving high occupancy rates. Here are the main findings:

1. **Popular Neighborhoods:**
   - Highest average nightly prices: Magnolia, Downtown, Queen Anne.
   - Highest booking rates: Cascade, Seward Park, Capitol Hill.

2. **Peak and Off-Peak Months:**
   - Summer months, especially July, exhibited peak average prices.
   - Booking activity peaked in January and had a smaller peak in July.

3. **Variables Influencing Occupancy Rate:**
   - A linear regression model highlighted factors influencing the occupancy rate.
   - Notably, entire home/apartment had a significant positive impact, while shared room had the highest negative effect.
   - An intriguing paradox was observed: the number of bedrooms positively influenced occupancy, while the number of beds had a negative impact.
   - Being a super host was identified as advantageous for a positive impact on the occupancy rate.

In summary, while certain factors influenced occupancy rates, the dataset suggested the presence of unexplored variables. Investors should consider a comprehensive approach, considering neighborhood popularity, seasonal pricing dynamics, and the nuanced impact of property features on occupancy rates.
