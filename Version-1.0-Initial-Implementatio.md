### Version 1.0 - Initial Implementation

Date: Initial Release



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

&#x09;Deadlines: task|subject|due\_date|completed



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

Menu-based navigation with 4 options:



Add Habit

Add Deadline to task

Display All

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



### Version 2.15 - Updated interface and fixed features and added feature

Date: 25/03/2026





### Version 2.11

Date: 11/03/2026



###### &#x20; Additional Menu Option (5 options instead of 4)

* ###### Added option 4: "Complete/Remove Task" - allows users to mark deadlines as complete or delete them entirely
* ###### Original had only 4 options (Add Habit, Add Deadline, Display All, Exit)

### Version 2.12

Date: 14/03/2026



###### &#x20;Enhanced Habit Streak Tracking

* ###### Date tracking: Now stores the date when a habit was last logged
* ###### Streak logic: Intelligently manages streaks based on consecutive days:
* ###### If logged on consecutive days (delta = 1 day): streak increases
* ###### If missed 2+ days: streak resets to 1
* ###### Original just incremented streak without any date validation

### Version 2.13

Date: 17/03/2026



###### &#x20;Improved Display Format

* ###### Added "Last Logged" column to habits display showing when each habit was last updated
* ###### Better visual formatting with centered headers and consistent separators
* ###### Shows N/A for habits without a logged date

### Version 2.14

Date: 19/03/2026



###### &#x20;Task Management Capabilities

###### Users can now:

* ###### Mark deadlines as "complete" without deleting them
* ###### Delete deadlines entirely from the system
* ###### Original only allowed adding and viewing deadlines

### Version 2.15

Date: Date: 25/03/2026



###### &#x20;Better Data Structure

* ###### Habits now store both streak and date (e.g., "habit": {"streak": 5, "date": "2026-03-26"})
* ###### Original habits only stored streak
* ###### File format updated from habit|streak to habit|streak|date

