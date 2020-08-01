# Time-Tracker-App
Project Name: Time Tracker Program

PROBLEM:
Client needs a solution to calculate hours spent on work and the amount of money he will make at a rate of $5 per hour.

SOLUTION:
Language Used: Python_
Description: This Time Tracking Program is a program that allows a user in this case “Nana” to:
1.Enter the time they started working on an activity and the time they ended work on a particular date or any date entered per the user’s preference.
2. Calculate the hours the user spent working.
3. Calculate the amount of money he makes tackling a project at a rate of $5 per hour.
4. Store time entered and information concerning an activity in a csv file for future references

PROGRAM DEPENDENCIES 

•	Pandas library-pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time serie
•	Datetime module -supplies classes for manipulating dates and times.
•	Csv module-implements classes to read and write tabular data in CSV format. It allows programmers to say, “write this data in the format preferred by Excel,” or “read data from this file which was generated by Excel,” without knowing the precise details of the CSV format used by Excel. Programmers can also describe the CSV formats understood by other applications or define their own special-purpose CSV formats
•	Os module-the OS module in python provides functions for interacting with the operating system. OS, comes under Python’s standard utility modules. This module provides a portable way of using operating system dependent functionality.
•	Sys module -this module provides access to some variables used or maintained by the interpreter and to functions that interact strongly with the interpreter.

IMPLEMENTATION AND DESIGN

HOW IT WORKS 

Installation:

1. To use this program locally, you should have Python 3 installed on your workstation.
2. Click on the green Code tab in the repository and download the zip file or run `git clone https://github.com/AfiDede/Time-tracker-app.git` in the directory you want to download it to.
3. Extract the `.py` file and run in your python shell or run in an editor.

Usage: 

After successful installation you are ready to benefit from this amazing program. The steps below should guide you to effective achieve your desire output of the program
Process:
1. Check if there is a file named `tracking.csv` in the directory and create it if it doesn't exit.
2. Ask the user to input the name of the client whose money he's trying to track.
3. Ask the user if he'd like to input his own preferred date and time or if he'd like to use the current systems date and input the time as the starting time.
4. Based on the users choice the program would take his input then convert it to seconds.
5. Ask the user if he'd like to input his own preferred date and time or if he'd like to use the current systems date and input the time as the ending time.
6. Based on the users choice the program would take his input then convert it to seconds then calculate the difference between the start and end times and use the results to deduce how much they would have to pay based on the $5 rate.

CONCLUSION:This program executes with no errors and meets the client's user requirements.



Contributors:

[Kevin Dodor](https://github.com/doski-codes/)

[Kweyakie Blebo](https://github.com/AfiDede)

[Kwame Owusu Appiah-Kubi](https://github.com/Quibik)
