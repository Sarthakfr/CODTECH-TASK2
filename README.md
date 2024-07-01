NAME : SARTHAK SINGH NEGI 
Organisation Name : CODTECH IT SOLUTIONS 
ID : CT12PD161 
DOMAIN : PYTHON PROGRAMMING 
DURATION : 14th MAY to 1st JULY 
MENTOR : SRAVANI GOUNI

![image](https://github.com/Sarthakfr/CODTECH-TASK2/assets/174301153/e3b99244-8601-4f6a-9a6f-5ff9bb0de1bc)

Project Overview: Student Grade Tracker 

1. Introduction:
Objective: Develop a graphical user interface (GUI) application using Python's tkinter library to track student grades.
Functionality: Users can input student names and grades, add them to a list, calculate the average grade, and clear the list when needed.

2. Features:
Input Fields: Entry fields for entering student name and grade.
Buttons:
Add Grade: Adds the entered student name and grade to a list and displays it in a Listbox.
Clear List: Clears the Listbox and resets the student list.
Calculate Average: Computes and displays the average grade of all students in the list.
Listbox: Displays added students and their grades for easy viewing and management.
Error Handling: Alerts users with error messages (e.g., empty fields, non-numeric grades) using messagebox.

3. Implementation Details:
Class Structure: Utilizes a single class StudentGradeTrackerGUI encapsulating all GUI elements and logic.
Initialization: Sets up the tkinter window (root) with labels, entry fields, buttons, listbox, and result display.
Methods:
add_grade: Validates and adds student data to the list and updates GUI components.
clear_entries: Clears entry fields (entry_name, entry_grade).
clear_list: Clears the Listbox and resets the student list.
calculate_average: Computes and displays the average grade of all students.
Main Program: Initializes the tkinter application, creates an instance of StudentGradeTrackerGUI, and starts the GUI main loop (root.mainloop()).

4. Usage:
Launch the application by running the Python script.
Enter a student's name and grade, then click "Add Grade" to add them to the list.
Use "Clear List" to remove all students from the list and "Calculate Average" to compute the average grade.

5. Potential Enhancements:
Validation: Implement additional validation for grade inputs (e.g., range checking).
File Handling: Add functionality to save and load student data from files.
Sorting: Allow sorting of students by name or grade.
Visual Improvements: Enhance the GUI layout, styling, and usability.

6. Conclusion:
The Student Grade Tracker GUI provides a simple yet effective tool for managing student grades interactively. It demonstrates fundamental GUI programming skills using Python's tkinter library and can be extended with more features based on user requirements and feedback.
