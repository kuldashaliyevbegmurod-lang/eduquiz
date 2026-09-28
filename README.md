# EduQuiz

EduQuiz is a small Uzbek-language online quiz platform built with plain HTML, CSS, and JavaScript.

## Run locally

Open `index.html` in a browser, or start a local server from this folder:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Features

- Student sign-in screen and sign-out
- Randomized English, mathematics, and history quizzes
- Two-minute quiz timer, answer validation, and automatic scoring
- Locally saved custom questions and leaderboard results
- Responsive layout for desktop and mobile

## Demo limitations

This is a browser-only demo. Login does not verify accounts, and questions and scores are stored in the current browser's local storage. It is not suitable for real credentials or shared, tamper-resistant results; those require a backend and database.
