Calendar Generator
This C++ program generates a calendar for a given year.

How to Use
Compile the program using a C++ compiler.
Run the compiled executable.
Enter a year when prompted.
View the generated calendar for the entered year.

This C++ program generates a calendar for a given year. Here's an overview of how it works:

Input Year: The program prompts the user to enter a year (e.g., 1999).
Day Code Calculation: It calculates the day code for the given year using Zeller's Congruence algorithm. This day code represents the day of the week for January 1st of the given year (0 for Sunday, 1 for Monday, ..., 6 for Saturday).
Leap Year Determination: It checks if the given year is a leap year or not. If it is, it updates the number of days in February to 29; otherwise, it sets the days to 28.
Calendar Generation: The program then generates and prints the calendar for the entire year. It iterates over each month, printing the month name and the days of the week (Sun, Mon, Tue, ..., Sat), and then prints the days of the month, properly formatted within the days of the week.
Output: Finally, the generated calendar for the given year is displayed.
