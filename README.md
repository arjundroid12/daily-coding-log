# 📓 Daily Coding Log

> A new coding challenge, tip, and reflection prompt — auto-committed every day by GitHub Actions.

![Daily Commit](https://github.com/arjundroid12/daily-coding-log/actions/workflows/daily.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Day](https://img.shields.io/badge/day-76-blue)

## 📅 Today — Saturday, September 12, 2026 (Day 76)

### 🧠 Challenge: Sum of Digits
**Easy** · Math / Loops

Given a non-negative integer, return the sum of its digits.

👉 [Full challenge + solution](./logs/2026-09-12.md)

### 💡 Tip: Use `Set` for fast membership checks
`Set.has()` is O(1), `Array.includes()` is O(n).

---

## 🗂️ Archive

All daily logs are saved in [`./logs/`](./logs/) as `YYYY-MM-DD.md` files.

- [2026-09-12](./logs/2026-09-12.md)
- [2026-09-11](./logs/2026-09-11.md)
- [2026-09-10](./logs/2026-09-10.md)
- [2026-09-09](./logs/2026-09-09.md)
- [2026-09-08](./logs/2026-09-08.md)
- [2026-09-07](./logs/2026-09-07.md)
- [2026-09-06](./logs/2026-09-06.md)
- [2026-09-05](./logs/2026-09-05.md)
- [2026-09-04](./logs/2026-09-04.md)
- [2026-09-03](./logs/2026-09-03.md)
- [2026-09-02](./logs/2026-09-02.md)
- [2026-09-01](./logs/2026-09-01.md)
- [2026-08-31](./logs/2026-08-31.md)
- [2026-08-30](./logs/2026-08-30.md)

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
