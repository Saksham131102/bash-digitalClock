# bash-digitalClock ⏰
A lightweight shell script that displays a real-time digital clock in the terminal. The clock updates every second and shows the current time in HH:MM:SS format.

# Features 🌟
- Real-time updates: Displays the current time updated every second.
- Clean and minimal design: Uses ANSI escape codes for colored output.
- Lightweight: Requires only Bash and basic system utilities.

# How It Works 🛠️
- The script continuously clears the terminal screen.
- It fetches the current time using the date command in HH:MM:SS format.
- The time is displayed with a green color using ANSI escape codes.
- The script pauses for 1 second before repeating.

# Usage
1. Clone the repository:
  ```bash
  git clone <repository-url>
  cd <repository-directory>
  ```

2. Make the script executable:
  ```bash
  chmod +x script.sh
  ```

3.	Run the script:
  ```bash
  ./script.sh
  ```
  or
  ```bash
  bash script.sh
  ```

# Why Use This? 🤔
- A fun and simple example of how to use shell scripting for real-time tasks.
- Great for beginners learning Bash scripting and terminal output formatting.
- Customizable for more advanced clock features like dates, time zones, etc.
