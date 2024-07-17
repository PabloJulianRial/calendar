# Post Course – Java Project: Meeting Scheduler

## Overview

This project is designed to help you schedule a meeting with a co-worker, taking into account both of your busy schedules and availability bounds. Given your calendar and your co-worker's calendar, along with your respective daily bounds and the desired meeting duration, the program will output all possible time slots for the meeting.

## Features

- **Input Handling**: The program accepts user input for personal and co-worker calendars, as well as daily availability bounds.
- **Time Slot Calculation**: It computes and displays all possible time slots that fit the specified meeting duration.
- **Military Time**: Times are handled and returned in military time format (e.g., 8:30, 9:01, 23:56).

## Sample Input

Here is an example of what the input to the program might look like:

```java
calendar1 = [['9:00', '10:30'], ['12:00', '13:00'], ['16:00', '18:00']]
dailyBounds1 = ['9:00', '20:00']
calendar2 = [['10:00', '11:30'], ['12:30', '14:30'], ['14:30', '15:00'], ['16:00', '17:00']]
dailyBounds2 = ['10:00', '18:30']
meetingDuration = 30
```

## Sample Output

Based on the sample input, the program will output:

```java
[['11:30', '12:00'], ['15:00', '16:00'], ['18:00', '18:30']]
```

## How to Use

1. **Clone the Repository**:

   ```sh
   git clone https://github.com/yourusername/meeting-scheduler.git
   cd meeting-scheduler
   ```

2. **Compile the Program**:

   ```sh
   javac MeetingScheduler.java
   ```

3. **Run the Program**:

   ```sh
   java MeetingScheduler
   ```

4. **Follow the Prompts**:

   - Enter your calendar entries.
   - Enter your daily bounds.
   - Enter your co-worker's calendar entries.
   - Enter your co-worker's daily bounds.
   - Specify the desired meeting duration.

5. **View Possible Meeting Slots**:
   - The program will display all possible meeting slots that fit the criteria.

## Project Structure

- **MeetingScheduler.java**: Main class that handles user input and coordinates the scheduling logic.
- **README.md**: This file, providing an overview and usage instructions for the project.

## Testing

The project includes multiple test cases to demonstrate the working solution. Make sure to input various scenarios to see the flexibility and robustness of the scheduling logic.
