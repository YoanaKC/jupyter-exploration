# jupyter-exploration
Test
print("My name is Yoana")
print("Calculating what day my Birthday will fall on this year" 
# Define the year, month, and day
year = 2025
month = 10
day = 23

# Days of the week (starting with January 1, 2025, which is Wednesday)
dayOfWeek = ("Wednesday", "Thursday", "Friday", "Saturday", "Sunday", "Monday", "Tuesday")

# Number of days in each month, 2025 is not a leap year
daysInMonth = (31, 28, 31, 30, 31, 30, 31, 31, 30, 31, 30, 31)

# Calculate the day of the year for October 23
dayOfYear = sum(daysInMonth[:month - 1]) + day

# January 1, 2025 is Wednesday
# Calculate the weekday index (0 = Wednesday)
weekdayIndex = (dayOfYear - 1) % 7

# Print the result
print("October 23, 2025 is a " + dayOfWeek[weekdayIndex] + ".")
