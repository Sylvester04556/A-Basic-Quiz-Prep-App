# 🧠 Quiz App (Login & Signup System)

This is a simple terminal-based Quiz Application built in Python. It features a user-friendly login and signup system to authenticate users before allowing access to the quiz. It also includes password management features such as password confirmation and password reset.

## 🚀 Features

- User Sign Up (with username uniqueness check)
- User Login (with password verification and retry attempts)
- Password Reset (forgot password flow)
- Basic Quiz Interaction with 2 questions
- Exits program gracefully if user declines to proceed

## 🛠 Technologies Used

- Python 3
- Standard libraries (`sys`)

## 🔄 How It Works

1. On startup, the user is prompted to either **Log in** or **Sign up**.
2. If the user signs up:
   - They enter their first name, last name, username, and password.
   - Passwords must match during sign-up.
3. If the user logs in:
   - They must enter correct credentials within a limited number of attempts.
4. If they forget the password:
   - They can reset it.
5. Once logged in, they are prompted to start the quiz.

## ✅ Quiz Format

- Multiple choice questions.
- Input is taken as `a`, `b`, `c`, etc.
- Immediate feedback is provided along with explanations.
