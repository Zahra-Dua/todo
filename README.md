Todo App
A beautiful and intuitive Flutter todo application with a modern gradient UI and persistent data storage.
📱 Features
Todo Management

✅ Add new tasks with timestamps
✅ Mark tasks as complete/incomplete
✅ Delete tasks with confirmation
✅ Real-time progress tracking
✅ Task completion percentage display

Counter Feature

➕ Increment counter
➖ Decrement counter
🔄 Reset counter to zero
💾 Automatic counter state saving

UI/UX

🎨 Beautiful gradient background (purple to pink)
📱 Modern mobile-friendly design
🔄 Smooth animations and transitions
💾 Persistent data storage using SharedPreferences

🛠️ Technologies Used

Flutter - Cross-platform mobile development framework
Dart - Programming language
SharedPreferences - Local data persistence

📦 Dependencies
yamldependencies:
  flutter:
    sdk: flutter
  shared_preferences: ^2.2.2
🚀 Getting Started
Prerequisites

Flutter SDK (>=3.0.0)
Dart SDK
Android Studio / VS Code
Android/iOS device or emulator

Installation

Clone the repository
bashgit clone https://github.com/Zahra-Dua/todo.git
cd todo

Install dependencies
bashflutter pub get

Run the app
bashflutter run


📱 App Screens
1. Counter Screen

Display current count with large, clear typography
Three action buttons: Decrease (-), Reset (🔄), Increase (+)
Instructions panel explaining functionality
Auto-save feature for counter state

2. Todo List Screen

Progress indicator showing completion percentage
Add new tasks with the "+" button
Task list with creation timestamps
Complete tasks by tapping the circle checkbox
Delete tasks using the trash icon
Visual feedback for completed tasks (green checkmark)

🎯 Key Features Explained
Data Persistence
The app uses shared_preferences to store:

Counter value
Todo tasks and their completion status
Task creation timestamps

Task Management

Add Task: Tap the "+" button and enter task description
Complete Task: Tap the circle icon next to any task
Delete Task: Tap the red trash icon
Progress Tracking: Automatic calculation of completion percentage

Counter Functionality

Increment: Tap "+" to increase counter
Decrement: Tap "-" to decrease counter
Reset: Tap refresh icon to reset to 0
Persistence: Counter value is automatically saved

🏗️ Project Structure
lib/
├── main.dart              # App entry point
├── models/                # Data models
├── screens/               # UI screens
│   ├── counter_screen.dart
│   └── todo_screen.dart
├── widgets/               # Reusable UI components
└── services/              # SharedPreferences service
🎨 Design Features

Gradient Background: Smooth purple to pink gradient
Rounded Components: Modern card-based design with rounded corners
Typography: Clean, readable fonts with proper hierarchy
Color Scheme: Consistent purple/pink theme throughout
Icons: Intuitive iconography for all actions
Animations: Smooth transitions between states

![WhatsApp Image 2025-08-02 at 15 47 56_bed852ba](https://github.com/user-attachments/assets/6ce3cbf7-89e5-4a37-aa23-7020325a4f28)
![WhatsApp Image 2025-08-02 at 15 47 55_a08f84a2](https://github.com/user-attachments/assets/33fe7b5e-4171-4413-9dea-f56f6bc47b9e)
![WhatsApp Image 2025-08-02 at 15 47 53_73217379](https://github.com/user-attachments/assets/5df2de9b-033b-4caf-936d-ac7c87f7b22d)
![WhatsApp Image 2025-08-02 at 15 47 56_57e5caf3](https://github.com/user-attachments/assets/1492a570-a0a5-4dcc-8527-8861307bb557)

Author
Zahra Dua

GitHub: @Zahra-Dua

