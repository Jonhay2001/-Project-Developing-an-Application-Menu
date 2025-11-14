# -Project-Developing-an-Application-Menu
A five week Python Project
# <jonhay2001> Spreadsheet Automation Menu

from datetime import datetime

print("1234567 Spreadsheet Automation Menu")   # Replace 1234567 with your actual student ID
print("------------------------------------")
print("1. Input Data")
print("2. View Current Data")
print("3. Generate Report")

# The next line retrieves the inputted option and stores into the variable called choice.
choice = input("Enter an option number: ")

print("\nYou selected option:", choice)
print("The time and date is", str(datetime.now()))
