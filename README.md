# daily_update.py
import datetime
import random

print("Daily GitHub activity - Day 27")

today = datetime.date.today()

# Create a random matrix (3x3) and calculate row sums
matrix = [[random.randint(1, 50) for _ in range(3)] for _ in range(3)]
row_sums = [sum(row) for row in matrix]

print(f"Today's date: {today}")
print("Generated 3x3 matrix:")
for row in matrix:
    print(row)

print("Row sums:", row_sums)
print("Highest row sum:", max(row_sums))
