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