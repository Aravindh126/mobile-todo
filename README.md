# 📋 DoTask

**DoTask** is a simple, efficient, and elegant task management app built with Flutter. Designed to boost your daily productivity, it helps you manage, track, and complete your tasks with ease.

---

## 🚀 Features

- 📝 Add, update, and delete tasks
- ✅ Organize tasks into **All**, **Completed**, and **Pending**
- 🔐 Secure Google Sign-In using Firebase Authentication
- 🌙 Dark Mode and Light Mode support
- 💾 Offline task persistence using Hive (NoSQL)
- 📱 Clean and responsive UI for all screen sizes
- 🧹 Swipe to delete tasks using smooth animations
- 🔄 Real-time task updates

---

## 📦 Getting Started

### 🔧 Prerequisites

- Flutter SDK (>= 3.5.3)
- Android Studio or VS Code
- A Firebase project (for Android support)

### 🛠 Installation

```bash
git clone https://github.com/your-username/dotask.git
cd dotask
flutter pub get
flutter pub run build_runner build
flutter run
```
### 📱 APK Download
 - 👉 Download the APK

### 🧰 Architecture
 - DoTask follows MVVM (Model-View-ViewModel) + Provider pattern:

 - Model: Represents the structure of a task

 - ViewModel: Business logic and task state management

 - View: UI components and user interactions

 - Provider: Reactive state management for scalable updates

### 🎥 App Demo
 - 🎬 Watch Demo Video

### 🧠 Assumptions
 - Users have a stable internet connection for authentication

 - The MVP supports Android (iOS can be added later)

 - Offline support is handled with Hive local database

 - Notifications and calendar integration are out of scope for MVP

### 🎨 UI and Design
 - Material Design principles

 - Custom dark/light themes

 - Clean and accessible layout

Responsive across phone and tablet sizes

### 🧰 Packages Used
 - Package	Purpose
 - provider	State management
 - firebase_auth	Firebase Authentication
 - google_sign_in	Google account login
 - hive	Lightweight local database
 - hive_flutter	Flutter support for Hive
 - flutter_slidable	Swipe-to-delete animations
 - intl	Date and time formatting
 - lottie	Optional animated effects

## 🏁 Final Notes
 - Clean, modular, and well-documented codebase

 - Optimized for scalability and maintainability

 - Built as part of a hackathon organized by Katomaran

 - Easy to extend with features like task priority, reminders, and calendar view

