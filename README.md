# Quiz Game

This project is a **Java and Firebase**-based quiz application where users can sign up or log in to participate in quizzes. Users can answer questions within a set time limit, view their correct/incorrect answers visually, and track their scores.

## Features

- **Sign-Up and Login**: Users can register, log in, and reset their passwords.
- **Answering Questions**: Each question has a set time limit for users to answer.
- **Correct/Incorrect Feedback**: After each question, users see if their answers were correct (in green) or incorrect (in red).
- **Score Tracking**: Users can view their past performance on a score table.

## Technologies Used

- **Java**: The primary language, handling all application functionalities.
- **Firebase**: Manages user data and quiz questions.
- **Android Studio**: The development environment used.

## Project Steps

1. **Start Screen**: When the app starts, the "Quiz Game" text and a progress bar appear on the screen.

2. **Login Page**:
   - If you have an account, you can proceed by entering your email and password.
   - If you don’t have an account, click "Don’t have an account? Become a member" to sign up.
   - If you forgot your password, click "Forgot your password?" to reset it.

3. **Sign-Up**:
   - Enter your email and password to create a new account.

4. **Password Reset**:
   - Enter your registered email and click the "Continue" button to receive a password reset email.
   - If the email is not registered, an error message will appear on the screen.

5. **Starting the Quiz**:
   - Once logged in, you can start the quiz by selecting the "Start Quiz" option on the home page.
   - To log out, click the "Exit" button.

6. **Answering Questions**:
   - When you click "Start Quiz," you’ll receive 10 questions, each with a 25-second timer. After 25 seconds, answers can no longer be selected.
   - If you select an answer, correct answers will be shown in green, while incorrect answers will appear in red.

7. **Tracking Correct/Incorrect Answers**:
   - If your answer is correct, the correct answer count will increase. Similarly, incorrect answers will be tracked and displayed.
