

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

Date: 25/03/2026



###### &#x20;Better Data Structure

* ###### Habits now store both streak and date (e.g., "habit": {"streak": 5, "date": "2026-03-26"})
* ###### Original habits only stored streak
* ###### File format updated from habit|streak to habit|streak|date

### Version 2.16

Date: 29/03/2026



###### &#x20;Enhanced deadline display features

* ###### Added days-left calculation for each deadline
* ###### Implemented OVERDUE status for past due dates
* ###### Visual table formatting with borders and headers
* ###### Added purpose/subject field for deadlines

### Version 2.2

Date: 05/4/2026



###### &#x20;Input validation and error handling

* ###### Empty input detection for habits and tasks
* ###### Invalid date format error messages
* ###### Task not found notifications
* ###### Graceful error recovery without crashes
* ###### Case-insensitive input handling for all user entries

###### 

###### 


