# 📓 Daily Coding Log

> A new coding challenge, tip, and reflection prompt — auto-committed every day by GitHub Actions.

![Daily Commit](https://github.com/arjundroid12/daily-coding-log/actions/workflows/daily.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Day](https://img.shields.io/badge/day-21-blue)

## 📅 Today — Sunday, July 19, 2026 (Day 21)

### 🧠 Challenge: Two Sum
**Easy** · Arrays / Hash Maps

Given an array of integers `nums` and an integer `target`, return the indices of the two numbers such that they add up to `target`.

👉 [Full challenge + solution](./logs/2026-07-19.md)

### 💡 Tip: Use `??` (nullish coalescing) instead of `||` for default values
`||` treats `0`, `''`, `false`, `NaN` as falsy — usually not what you want for defaults.

---

## 🗂️ Archive

All daily logs are saved in [`./logs/`](./logs/) as `YYYY-MM-DD.md` files.

- [2026-07-19](./logs/2026-07-19.md)
- [2026-07-18](./logs/2026-07-18.md)
- [2026-07-17](./logs/2026-07-17.md)
- [2026-07-16](./logs/2026-07-16.md)
- [2026-07-15](./logs/2026-07-15.md)
- [2026-07-14](./logs/2026-07-14.md)
- [2026-07-13](./logs/2026-07-13.md)
- [2026-07-12](./logs/2026-07-12.md)
- [2026-07-11](./logs/2026-07-11.md)
- [2026-07-10](./logs/2026-07-10.md)
- [2026-07-09](./logs/2026-07-09.md)
- [2026-07-08](./logs/2026-07-08.md)
- [2026-07-07](./logs/2026-07-07.md)
- [2026-07-06](./logs/2026-07-06.md)

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
