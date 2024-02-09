## Calendar Generator

### Overview
This C++ program generates a calendar for a given year. It calculates the day code for the given year using Zeller's Congruence algorithm and determines if it's a leap year. The calendar is then generated for the entire year, displaying each month along with the corresponding days of the week.

### How to Use
1. Compile the program using a C++ compiler.
2. Run the compiled executable.
3. Enter a year when prompted.
4. View the generated calendar for the entered year.

### Program Functionality
1. **Input Year**: The program prompts the user to enter a year (e.g., 1999).
2. **Day Code Calculation**: Calculates the day code for the given year, representing the day of the week for January 1st (0 for Sunday, 1 for Monday, ..., 6 for Saturday).
3. **Leap Year Determination**: Checks if the given year is a leap year or not. If it is, updates the number of days in February to 29; otherwise, sets the days to 28.
4. **Calendar Generation**: Generates and prints the calendar for the entire year. Iterates over each month, printing the month name, days of the week, and days of the month, properly formatted within the days of the week.

### Example Output
```
Please enter a year (example: 1999) : 2024

              January

Sun Mon Tue Wed Thu Fri Sat
              1   2   3   4  
  5   6   7   8   9  10  11  
 12  13  14  15  16  17  18  
 19  20  21  22  23  24  25  
 26  27  28  29  30  31

             February

Sun Mon Tue Wed Thu Fri Sat
                            1  
  2   3   4   5   6   7   8  
  9  10  11  12  13  14  15  
 16  17  18  19  20  21  22  
 23  24  25  26  27  28  29  
```
