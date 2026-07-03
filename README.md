# BECE Quiz Game

A browser-based **multiple-choice quiz** for BECE-style practice — HTML + vanilla JavaScript, no build step required.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

## Features

- Static quiz flow — open and play immediately
- Multiple-choice buttons with instant feedback logic
- Separate JS modules for messages and wrong-answer handling
- Planned: timers and inline command extensions

## Pages

| File | Purpose |
|------|---------|
| `startup.html` | Entry / splash |
| `loginpage.html` | Player name entry |
| `mycode.html` | Main quiz UI |
| `testvariables.html` | Dev / test harness |

## Quick start

Open `startup.html` in any modern browser — no server or npm install needed.

```bash
# optional local server
python3 -m http.server 8080
# then visit http://localhost:8080/startup.html
```

## Scripts

- `message.js` — question flow + UI messages
- `wrong.js` — incorrect answer handling

---

[malimba](https://github.com/malimba)
