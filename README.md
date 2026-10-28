Digital Clock: Displays live, updating local date and time (DD-MM-YYYY HH:MM:SS) in the console.
Alarm Clock: Accepts a target time (HH:MM:SS), validates the input format using datetime.strptime, continuously checks current time against the target, and triggers a visual alert and system beep (\a) upon match.
Stopwatch: Tracks continuous elapsed time in HH:MM:SS format using divmod math and real-time in-place terminal updates (\r).
Countdown Timer: Parses an input duration in HH:MM:SS, validates hours/minutes/seconds constraints, converts the total into seconds, and counts down to zero before triggering an alert.
Menu & Error Handling: Uses a standard while True main menu with robust input validation and KeyboardInterrupt (Ctrl+C) handling to gracefully stop active modes without crashing the application.
