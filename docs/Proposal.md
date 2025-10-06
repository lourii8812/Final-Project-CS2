# Title: WEATHER DATABASE INQUIRY

# Problem statement:

Weather affects our daily activities, but raw weather data can be hard to understand. This project aims to create a Python program that reads and analyzes weather information from a JSON file. It will help users easily view important details like temperature, rainfall. Humidity and weather conditions, allowing them to observe patterns and make better decisions based on the week’s weather.

# Objectives:

The goal of creating a JSON file that analyzes weather is to keep the data simple and organized yet detailed. Details like humidity, temperature and rainfall are expected to be found in the program. The project aims to be user-friendly, it helps users interpret data accurately and the details are easy to understand. Moreover, it could help users connect weather factors that could help them make plans for their vacation, errands or outings based on  the data.

# Features:
 
- Weather Checker: Getting the weather condition/s based on the date.
- Dates of Weather: Find out which dates had this specific weather condition.
- Temperature Check: Find out which dates were cold(low temperature) or hot(high temperature)
- Direction Checker: Checking the wind direction of a specific day
- Humidity Identifier: Checking if the humidity of a specified day is High or Low

# Logic plan:
Input  Logic plan:
I  1.   Read JSON file:
- load weather data from the JSON file:
-Get user input:
- ask the user for a specific date or range of dates
  3.   Confirm input:
- check if the input is in the correct format

# Processing
  1.   Gather relevant data:
- compile the JSON data to gather key weather information which is the temperature, rainfall, humidity, wind speed, wind direction, pressure, and condition for the specified date(s)
  2.   Analyze data:
- analyze user(s) questions:
•get weather condition for a specific date
•find dates with a specific weather condition
•identify the coldest or hottest dates
•check wind direction for a specific day
•determine the humidity level (high or low) for a specific date

# Output
  1.   Display weather details:
- show the user weather information for the specified date(s), even including:
•temperature
•rainfall
•humidity
•wind speed 
•wind direction
•pressure
•weather conditions
  2.   Display analysis results:
- give the results of the users questions, such as:
•dates with a specfic condition
•coldest or hottest dates
•wind direction for a specific date
• humidity level of a specific date

# Error Handling
  1.   Handle file errors
  2.   Handle invalid input
  3.   Handle data errors

# User interaction
  1.   User-friendly out


Input:
Date/s

Output:
Temperature
Rainfall
Humidity
Wind speed
Wind direction
Pressure
Condition

Logic Plan:

Start Program

Load JSON file "weather.json"

Display Main Menu:

    1. Check weather details for a specific date
    2. Find all dates with a specific weather condition
    3. Identify hottest and coldest days
    4. Check wind direction for a specific date
    5. Determine humidity level (High or Low)
    6. Show weekly weather summary
    7. Exit program

Repeat until user chooses Exit:
    Ask for user choice
```
If choice == 1:
    - Ask user to input a specific date
    - Display all weather details for that date
    - Show temperature, rainfall, humidity, wind speed, wind direction, pressure, and condition

Else if choice == 2:
    - Ask user to input a specific weather condition (e.g., "Rainy", "Sunny")
    - Search through all dates with that condition
    - Display list of dates that match the weather condition

Else if choice == 3:
    - Analyze temperature data from all dates
    - Find and display the hottest day(s) and coldest day(s)
    - Show their respective temperature values and conditions

Else if choice == 4:
    - Ask user to input a specific date
    - Retrieve wind direction for that date
    - Display wind direction and speed

Else if choice == 5:
    - Ask user to input a specific date
    - Retrieve humidity data for that date
    - Determine whether humidity is “High” or “Low”
    - Display humidity percentage and status

Else if choice == 6:
    - Display summary report for all days in the dataset
    - Include average temperature, average humidity, total rainfall, and most common weather condition
    - Help users observe general weather patterns for the week

Else if choice == 7:
    - Display “Exiting program...”
    - End the loop

Else:
    - Display “Invalid option, please try again.”
```
End Program
# Github link:
https://github.com/lourii8812/Final-Project-CS2
