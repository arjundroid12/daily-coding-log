# 📓 Daily Coding Log

> A new coding challenge, tip, and reflection prompt — auto-committed every day by GitHub Actions.

![Daily Commit](https://github.com/arjundroid12/daily-coding-log/actions/workflows/daily.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Day](https://img.shields.io/badge/day-29-blue)

## 📅 Today — Monday, July 27, 2026 (Day 29)

### 🧠 Challenge: Fibonacci (Efficient)
**Medium** · Dynamic Programming

Return the nth Fibonacci number. F(0) = 0, F(1) = 1, F(n) = F(n-1) + F(n-2). Handle n up to 50 efficiently.

👉 [Full challenge + solution](./logs/2026-07-27.md)

### 💡 Tip: Use `Object.hasOwn(obj, key)` instead of `obj.hasOwnProperty(key)`
Modern JS (ES2022) provides `Object.hasOwn(obj, key)` as a safer alternative to `obj.hasOwnProperty(key)`.

---

## 🗂️ Archive

All daily logs are saved in [`./logs/`](./logs/) as `YYYY-MM-DD.md` files.

- [2026-07-27](./logs/2026-07-27.md)
- [2026-07-26](./logs/2026-07-26.md)
- [2026-07-25](./logs/2026-07-25.md)
- [2026-07-24](./logs/2026-07-24.md)
- [2026-07-23](./logs/2026-07-23.md)
- [2026-07-22](./logs/2026-07-22.md)
- [2026-07-21](./logs/2026-07-21.md)
- [2026-07-20](./logs/2026-07-20.md)
- [2026-07-19](./logs/2026-07-19.md)
- [2026-07-18](./logs/2026-07-18.md)
- [2026-07-17](./logs/2026-07-17.md)
- [2026-07-16](./logs/2026-07-16.md)
- [2026-07-15](./logs/2026-07-15.md)
- [2026-07-14](./logs/2026-07-14.md)

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
