# 🧠 Smart Routine Scheduler

A command-line based Smart Scheduler that helps you organize your daily tasks based on their **priority**, **duration**, and **deadline**. It uses **SQLite** to store tasks and schedules them within defined work hours.

## 🚀 Features

- 📅 Add tasks with duration, priority (High/Medium/Low), and optional deadlines.
- 🧠 Automatically schedule tasks within work hours (default: 9 AM – 5 PM).
- 📋 View the optimized schedule for the day.
- 🔔 Get real-time reminders for scheduled tasks.
- 💾 Uses SQLite for lightweight persistent storage.

## 📦 Tech Stack

- Python 3.x
- SQLite3
- `plyer` for notifications (optional, simulated with `print()` for CLI)
- Multithreading for background reminders

## 🛠️ Setup Instructions

1. Clone or download this repository.
2. Install dependencies:

```bash
pip install plyer
```

3. Run the scheduler:

```bash
python smart_schedule_.ipynb
```

> ⚠️ Recommended: Convert the `.ipynb` to `.py` if running outside of Jupyter.

## 📂 How It Works

1. **Add Task**: Enter task name, duration in hours, priority, and optional deadline.
2. **View Schedule**: Displays your daily routine based on task priority and availability.
3. **Exit**: Stops the CLI app.

## 💡 Example

```
Smart Routine Scheduler
1. Add Task
2. View Schedule
3. Exit
Enter choice (1-3): 1
Enter task name: Team Meeting
Enter duration in hours: 1.5
Enter priority (high, medium, low): high
Do you want to set a deadline? (yes/no): yes
Enter deadline (YYYY-MM-DD HH:MM): 2025-07-18 11:00
```
