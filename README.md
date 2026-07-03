# 📓 Daily Coding Log

> A new coding challenge, tip, and reflection prompt — auto-committed every day by GitHub Actions.

![Daily Commit](https://github.com/arjundroid12/daily-coding-log/actions/workflows/daily.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Day](https://img.shields.io/badge/day-5-blue)

## 📅 Today — Friday, July 3, 2026 (Day 5)

### 🧠 Challenge: Debounce Function
**Medium** · Closures / Async

Implement a `debounce(func, wait)` function that delays invoking `func` until `wait` ms have elapsed since the last call.

👉 [Full challenge + solution](./logs/2026-07-03.md)

### 💡 Tip: Top-level `await` works in ES modules
In `.mjs` files (or with `"type": "module"` in package.json), you can use `await` at the top level — no wrapping IIFE needed:

---

## 🗂️ Archive

All daily logs are saved in [`./logs/`](./logs/) as `YYYY-MM-DD.md` files.

- [2026-07-03](./logs/2026-07-03.md)
- [2026-07-02](./logs/2026-07-02.md)
- [2026-07-01](./logs/2026-07-01.md)
- [2026-06-30](./logs/2026-06-30.md)

---

## ⚙️ How It Works

1. **GitHub Action** (`.github/workflows/daily.yml`) runs on a schedule (multiple times daily, commits at random times between 9 AM - 10 PM IST)
2. **`scripts/generate-daily.mjs`** picks a random challenge and tip, generates today's markdown log, and updates this README
3. The Action commits and pushes the changes — green square unlocked for today ✅

## 📚 Challenge Pool

Challenges live in [`./challenges/`](./challenges/) as JSON files. Want to add more? Open a PR!

| File | Topic | Count |
|------|-------|-------|
| [`challenges/algorithms.json`](./challenges/algorithms.json) | Arrays / Hash Maps | 20 |

## 💡 Tips Pool

Tips live in [`./data/tips.json`](./data/tips.json).

## 🤝 Contributing

Found a bug in a solution? Have a better approach? Want to add a challenge?
PRs are welcome — that's how we all learn!

## 📄 License

MIT © Arjun Vashishtha
