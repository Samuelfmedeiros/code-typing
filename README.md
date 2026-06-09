# ⌨️ Code Typing Challenge

A typing speed game for developers. Practice typing real code snippets in multiple languages — JavaScript, Python, React, TypeScript, Go, Rust, Ruby, SQL, and more.

![screenshot](https://img.shields.io/badge/React-18-61DAFB?logo=react)
![license](https://img.shields.io/badge/license-MIT-green)

## 🎯 Features

- **Real code snippets** — Type actual functions, classes, and algorithms (not random words)
- **Multiple languages** — Python, JavaScript, React JSX, TypeScript, Go, Rust, Ruby, SQL
- **Live metrics** — WPM (words per minute), accuracy, time, and progress in real-time
- **Character-level highlighting** — See exactly which keys you missed (green = correct, red = wrong, blue = current position)
- **Session results** — After each snippet, view detailed per-snippet stats and overall ratings
- **No backend** — Runs entirely in the browser via React 18 + Babel standalone from CDN
- **Dark theme** — GitHub-dark inspired design, easy on the eyes

## 🚀 How to use

Simply open `index.html` in your browser:

```bash
# Clone or download
git clone https://github.com/Samuelfmedeiros/code-typing.git
cd code-typing

# Open in browser
open index.html    # macOS
xdg-open index.html # Linux
start index.html   # Windows
```

Or serve with any static server:

```bash
npx serve .
```

No build step required. No npm install. No backend.

## 🎮 How it works

1. A code snippet is displayed on screen
2. Start typing in the textarea below
3. Characters turn **green** when correct, **red** when wrong
4. A blue highlight marks your current position
5. When you finish the snippet, your stats are recorded
6. Click **Next Snippet** to continue, or **View Results** to see your session summary

## 📊 Rating system

| WPM      | Accuracy | Title           |
|----------|----------|-----------------|
| 70+      | 98%+     | 🏆 Legend       |
| 50+      | 95%+     | 🔥 Pro          |
| 35+      | 90%+     | 💪 Solid        |
| 20+      | 80%+     | 👍 Getting there |
| < 20     | < 80%    | 🌱 Keep practicing |

## 🛠️ Tech

- [React 18](https://reactjs.org/) — UI
- [Babel Standalone](https://babeljs.io/docs/en/babel-standalone) — JSX transpilation in the browser
- Plain CSS — no frameworks
- Zero dependencies at build time

## 📄 License

MIT
