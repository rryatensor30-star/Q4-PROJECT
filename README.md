# Q4-PROJECT
###### This program is a simple command-line planner that combines a habit tracker and a deadline manager, allowing users to log habits, track streaks, and manage tasks with due dates. It saves all data in a text file, updates habit streaks automatically, and displays task progress with statuses like pending, completed, or overdue.

#### Core Features Implemented

#### 1\. Data Structure

Created nested dictionary data with two main sections:



hobbies: Stores habit information including streaks and history

deadlines: Stores task deadlines with subject, due date, and completion status

Implemented file-based persistence using habit\_deadline\_data.txt



#### 2\. File I/O Operations



Load Functionality: Reads from text file with sections \[HABITS] and \[DEADLINES]

Save Functionality: Writes data back to file with proper formatting

File format specifications:

&#x09;Habits: habit|streak

&#x09;Deadlines: task|subject|due\_date|stauts



#### 3\. Core Functions

Functions:

input\_date() - Prompts user for date input

save\_data() - Saves current data to file

habit\_check() - Validates and returns habit input

deadline\_track() - Handles deadline input and storage

display() - Shows all habits and deadlines

options() - Displays menu options

main() - Main program loop

#### 4\. User Interface

Menu-based navigation with 5 options:


Add Habit

Add Deadline to task

Display All

Complete/remove a task

Exit

Table-formatted displays for both habits and deadlines



#### 5\. Deadline Tracking Features

Automatic calculation of days left until deadline



Status indicators:



"DONE" - Completed tasks

"OVERDUE" - Past due dates

“PENDING" - Upcoming deadlines



#### 6\. Habit Tracking Features

Streak counter increments each time habit is added

Basic validation for empty inputs

Persistent data storage placed in txt files
