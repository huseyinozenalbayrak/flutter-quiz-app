# 🧠 Flutter Quiz App

A simple and interactive quiz application built with **Flutter** to learn core concepts like widgets, state management, and navigation — the fun way! 🚀

This app lets users answer a series of Flutter-related questions, shows results dynamically, and demonstrates the use of **Stateful** and **Stateless** widgets.

---

## 📱 Screenshots

| Start Screen                                                                                  | Question Screen                                                                                  | Result Screen                                                                                  |
| --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------- |
| ![Start](Simulator%20Screenshot%20-%20iPhone%2015%20Pro%20-%202025-10-19%20at%2013.00.57.png) | ![Question](Simulator%20Screenshot%20-%20iPhone%2015%20Pro%20-%202025-10-19%20at%2013.01.06.png) | ![Result](Simulator%20Screenshot%20-%20iPhone%2015%20Pro%20-%202025-10-19%20at%2013.01.18.png) |

Additional flow and summary screen example:  
![Summary](Screenshot%202025-10-19%20at%2013.02.19.png)

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
