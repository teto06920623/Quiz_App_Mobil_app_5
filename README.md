# 🧠 Flutter Quiz App

A dynamic and interactive Quiz Application built with **Flutter**. This project demonstrates the implementation of core mobile development concepts including UI design, state management, and data modeling.

## 📸 Screenshots

| Splash Screen | Quiz Screen | Score Dialog |
|

  <tr>
    <td style="border: none;"><img width="500" alt="(quiz app)" src="https://github.com/user-attachments/assets/ed1822c0-acb7-426c-a364-85e7c95744d3" /></td>
  </tr>
  <tr style="border: none;> <img width="300" alt="image" src="https://github.com/user-attachments/assets/49c36afc-0a3a-474e-a402-c8dcf15d1dca" />
 </tr>
  <tr style="border: none;> <img width="300" alt="image" src="https://github.com/user-attachments/assets/0030d2ee-33b4-4325-bf45-0d8bc4542c7d" />
 </tr>
  <tr style="border: none;> <img width="300" alt="image" src="https://github.com/user-attachments/assets/13e35d4e-b920-4534-80b6-7e02821b45a3" />
 </tr>
</table>
  <tr style="border: none;> <img width="300" alt="image" src="https://github.com/user-attachments/assets/ede33db3-785d-4dfb-91d0-3bbefc0f8f94" />
 </tr>
</table>
  <tr style="border: none;> <img width="300" alt="image" src="https://github.com/user-attachments/assets/05f4b18f-f1f6-41c2-9e97-c07a88f525b0" />
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
