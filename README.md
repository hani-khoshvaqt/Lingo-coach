# Lingo Coach

Lingo Coach is a language-practice chat app. The learner writes in English, Kurdish (Sorani) or Persian, and a tutor replies, corrects mistakes and gives a short learning tip.
i built it because i have taught languages and speak English and Kurdish fluently. Kurdish especially has very few learning tools, so i wanted to make one.

# Features

- Three languages: English, Kurdish (Sorani) and Persian
- Three levels: beginner, intermediate and advanced
- Mistake correction with a short explanation
- A learning tip after each message
- Clean chat interface built with HTML, CSS and JavaScript

## Current status

The interface is finished. Replies are still simulated: the app returns a structured response (reply, correction, tip) from a function called `fakeReply`. The next step is to replace it with real replies from an AI model.

## How to returns

Open `index.html` in your browser. No installation is needed.

## Roadmap

- Add a flask backend and connect it to the Claude API
- Save common mistakes in a database (SQLite)
- Generate practice exercieses from the learner's past mistakes
- Deploy the app online

## Tech stack

HTML, CSS, JavaScript(backend coming soon: Python, flask, Clauden API)
