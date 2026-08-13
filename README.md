# 📓 Daily Coding Log

> A new coding challenge, tip, and reflection prompt — auto-committed every day by GitHub Actions.

![Daily Commit](https://github.com/arjundroid12/daily-coding-log/actions/workflows/daily.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Day](https://img.shields.io/badge/day-46-blue)

## 📅 Today — Thursday, August 13, 2026 (Day 46)

### 🧠 Challenge: Binary Search
**Medium** · Search Algorithms

Given a sorted array and a target value, return the index of the target (or -1 if not found). Must be O(log n) time.

👉 [Full challenge + solution](./logs/2026-08-13.md)

### 💡 Tip: Use `Object.hasOwn(obj, key)` instead of `obj.hasOwnProperty(key)`
Modern JS (ES2022) provides `Object.hasOwn(obj, key)` as a safer alternative to `obj.hasOwnProperty(key)`.

---

## 🗂️ Archive

All daily logs are saved in [`./logs/`](./logs/) as `YYYY-MM-DD.md` files.

- [2026-08-13](./logs/2026-08-13.md)
- [2026-08-12](./logs/2026-08-12.md)
- [2026-08-11](./logs/2026-08-11.md)
- [2026-08-10](./logs/2026-08-10.md)
- [2026-08-09](./logs/2026-08-09.md)
- [2026-08-07](./logs/2026-08-07.md)
- [2026-08-06](./logs/2026-08-06.md)
- [2026-08-05](./logs/2026-08-05.md)
- [2026-08-04](./logs/2026-08-04.md)
- [2026-08-03](./logs/2026-08-03.md)
- [2026-08-02](./logs/2026-08-02.md)
- [2026-08-01](./logs/2026-08-01.md)
- [2026-07-31](./logs/2026-07-31.md)
- [2026-07-30](./logs/2026-07-30.md)

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
