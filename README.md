# CODTECH-Task-1
# Movie Rating Analysis Using Basic Python

ratings = [4.5, 4.8, 4.2, 4.7]

print("Movie Rating Analysis")
print("----------------------")

# Display ratings
for i in range(len(ratings)):
    print("Movie", i + 1, "Rating:", ratings[i])

# Calculate average rating
total = 0

for rating in ratings:
    total = total + rating

average = total / len(ratings)

print("----------------------")
print("Average Rating:", average)

# Find highest rating
highest = max(ratings)

print("Highest Rating:", highest)

Description:
          Movie Rating Analysis

Objective:
The objective of Movie Rating Analysis is to analyze movie data and ratings to identify patterns that influence audience preferences and movie success. It helps understand how factors such as genre, cast, director, budget, and release year affect ratings.

Overview:
This project involves collecting and analyzing movie datasets containing ratings, reviews, and movie attributes. Through data cleaning, visualization, and statistical analysis, meaningful insights are extracted to evaluate movie performance and audience trends.

Technologies Used:
* Python


Key Features:

* Data preprocessing and cleaning
* Rating distribution analysis
* Genre-wise and year-wise rating comparison
* Visualization of trends using charts and graphs
* Correlation analysis between movie attributes and ratings
* Insights generation for decision-making
