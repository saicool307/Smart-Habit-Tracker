Smart Habit Tracker
A complete habit tracking application built in Java featuring both:

✔ Graphical User Interface (GUI) using Swing
✔ Console (CLI) mode for terminal-based usage

Designed with clean Object-Oriented Programming (OOP), modular package structure, and includes advanced features like reminders, leaderboard, statistics analysis, data persistence, and CSV export.

🚀 Features
✓ Dual Mode Application

Choose how you want to use the app:

GUI Mode – Interactive Swing interface

Console Mode – Fully text-based CLI

✓ User Account System

Sign up & login with username

Persistent storage using serialization

✓ Habit Management

Add new habits

Remove habits

Mark habit as completed

Track streaks, completion history, and overall performance

✓ Smart Analytics

Auto-calculated streaks

Weekly activity graph (Swing line chart)

Completion rate percentage

Longest run detector

Historical analysis

✓ Goals & Targets

Set:

Target completion count

Target streak days
App automatically congratulates when user reaches the goal 🎉

✓ Leaderboard

Ranks all users based on:

Total completions

✓ Reminders Engine

Daily reminder scheduling

Custom times (HH:mm)

Notification pop-ups

✓ CSV Export

Export all habits and stats to a .csv file:

habit, streak, totalCompletions, totalDays, completionRate

✓ Clean OOP Architecture

Well-structured packages:

app
 ├── gui               (Swing UI)
 ├── console           (CLI mode)
 ├── user              (Models: Habit, History, UserProfile)
 ├── HabitTrackerManager
 ├── ProgressAnalyzer
 ├── ReminderEngine
 ├── util
 └── exception

🖥️ Technology Stack
Area	Technology
UI	Java Swing + AWT
Console	Standard Java I/O
Storage	Java Serialization (.ser)
Language	Java 8+
Charting	Custom Swing Graphics
Build Tool	(manual javac / your choice)
📦 Installation & Run
1. Compile
javac -d out (Get-ChildItem -Recurse -Filter *.java | ForEach-Object {$_.FullName})

2. Run main launcher
java -cp out app.Main

3. Select mode
1 → GUI Mode
2 → Console Mode

📷 Screenshots

(You can insert: GUI main screen, stats popup, console menu etc.)

🧩 Future Improvements

Cloud sync

Mobile companion app

SQLite database storage

Theme customization
