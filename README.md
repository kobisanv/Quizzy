
# Quizzy

Quizzy is a Flutter-based mobile application that enables teachers and students to engage in real-time quiz competitions. Teachers can create quizzes and host games using a unique code, while students join the games, compete in real time, and view scores and leaderboards. The app leverages Firebase for user authentication, real-time database updates, and data storage.

## Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Usage](#usage)
- [License](#license)

## Features

- **User Authentication:**  
  Secure login for both teachers and students using Firebase Authentication.

- **Quiz Creation & Hosting:**  
  Teachers can create quizzes with multiple questions and answer options, and then host these quizzes by generating a unique game code.

- **Real-Time Gameplay:**  
  Students can join live quiz sessions by entering the unique game code. The game operates in real time, displaying questions, collecting answers, and updating scores.

- **Replay Mode & Leaderboards:**  
  After a live session, students can replay quizzes in a timed mode. Scores are recorded and displayed on real-time leaderboards for both live and replay sessions.

## Technology Stack

- **Flutter (Dart):**  
  For building a cross-platform mobile application.

- **Firebase:**  
  - **Authentication:** Secure user login and registration.  
  - **Firestore:** Real-time database for quiz data, scores, and leaderboards.  
  - *(Optional)* **Firebase Storage:** For storing any media assets if needed.
  
## Usage

- **Teacher Workflow:**
  - Log in as a teacher.
  - Create a new quiz by entering questions and multiple-choice answers.
  - Host the quiz to generate a unique game code.
  - Share the game code with students for them to join the session.
  - Monitor real-time scores and leaderboards as students participate.

- **Student Workflow:**
  - Log in as a student.
  - Enter the unique game code provided by the teacher to join a live quiz session.
  - Answer questions as they appear in real time.
  - View scores and live leaderboard updates during the game.
  - Optionally, retake quizzes in replay mode for practice and improved scores.

## License

This project is licensed under the [MIT License](LICENSE).
