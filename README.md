# 🧠 Flutter Quiz App

A dynamic and interactive Quiz Application built with **Flutter**. This project demonstrates the implementation of core mobile development concepts including UI design, state management, and data modeling.

## 📸 Screenshots

| Splash Screen | Quiz Screen | Score Dialog |
|

  <tr>
    <td style="border: none;"><img width="500" alt="(quiz app)" src="https://github.com/user-attachments/assets/ed1822c0-acb7-426c-a364-85e7c95744d3" /></td>
  </tr>
</table>
|

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
