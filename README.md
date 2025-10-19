# 🧠 Flutter Quiz App

A simple and interactive quiz application built with **Flutter** to learn core concepts like widgets, state management, and navigation — the fun way! 🚀

This app lets users answer a series of Flutter-related questions, shows results dynamically, and demonstrates the use of **Stateful** and **Stateless** widgets.

---

## 📱 Screenshots

| Start Screen                                                                                                      | Question Screen                                                                                                     | Result Screen                                                                                                        |
| ----------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| ![Start](https://github.com/huseyinozenalbayrak/flutter-quiz-app/blob/main/screenshots/start_screen.png?raw=true) | ![Question](https://github.com/huseyinozenalbayrak/flutter-quiz-app/blob/main/screenshots/quiz_screen.png?raw=true) | ![Result](https://github.com/huseyinozenalbayrak/flutter-quiz-app/blob/main/screenshots/results_screen.png?raw=true) |

---

## 🧩 Features

- Multiple-choice quiz with dynamic question flow
- Live score tracking and result summary
- Clean UI with gradient backgrounds
- Fully responsive and runs on iOS, Android, and Web
- Demonstrates key Flutter concepts like:
  - `StatefulWidget` vs `StatelessWidget`
  - `setState()` and state updates
  - Widget tree and layout composition
  - Navigation between screens

---

## 🛠️ Project Structure

```
lib/
 ├── data/
 │   └── questions.dart
 ├── models/
 │   └── quiz_question.dart
 ├── questions_summary/
 │   ├── question_identifier.dart
 │   ├── questions_summary.dart
 │   └── summary_item.dart
 ├── answer_button.dart
 ├── main.dart
 ├── questions_screen.dart
 ├── quiz.dart
 ├── results_screen.dart
 ├── screenshots
 │   ├── quiz_screen.png
 │   ├── results_screen.png
 │   └── start_screen.png
 └── start_screen.dart
```

---

## 🚀 How to Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/quiz_app.git
   cd quiz_app
   ```

2. **Install dependencies**

   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

---

## 💡 Concepts Used

- Flutter UI building with **Widgets**
- Managing state with **StatefulWidget**
- Navigation between screens using **setState()**
- Dart collections & lists for dynamic question data
- Custom widget creation for better UI structure

---

## 📜 License

This project is open-source and free to use for educational purposes.
