# 🧠 Flutter Quiz App

A dynamic and interactive Quiz Application built with **Flutter**. This project demonstrates the implementation of core mobile development concepts including UI design, state management, and data modeling.

## 📸 Screenshots

| Splash Screen | Quiz Screen | Score Dialog |
|
<img width="2557" height="1446" alt="(quiz app)" src="https://github.com/user-attachments/assets/ed1822c0-acb7-426c-a364-85e7c95744d3" />

|
| ![Splash](path/to/splash.png) | ![Quiz](path/to/quiz.png) | ![Result](path/to/result.png) |

## ✨ Features

- **Dynamic Question Loading:** Fetches questions and answers from a structured List of Models.
- **Interactive UI:**
  - Real-time feedback on user selection.
  - Color-coded answers (Green for selected/correct logic).
- **Score Tracking:** Calculates and displays the final score at the end of the quiz.
- **Responsive Layout:** Uses `MediaQuery`, `Expanded`, and `Gap` for adaptive designs.
- **Custom Assets:** Includes custom fonts and images.

## 🛠️ Tech Stack & Dependencies

- **Framework:** [Flutter](https://flutter.dev/)
- **Language:** [Dart](https://dart.dev/)
- **Packages:**
  - [`gap`](https://pub.dev/packages/gap): For simplified UI spacing.

## 📂 Project Structure

```text
lib/
├── models/
│   └── model.dart         # Question data model & List
├── screens/
│   ├── splash_screen.dart # Intro screen with navigation logic
│   ├── page_view.dart     # Main parent widget (Controller Logic)
│   └── quiz_screen.dart   # UI for questions and answers
└── main.dart              # Entry point
