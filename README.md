# 📓 Daily Coding Log

> A new coding challenge, tip, and reflection prompt — auto-committed every day by GitHub Actions.

![Daily Commit](https://github.com/arjundroid12/daily-coding-log/actions/workflows/daily.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Day](https://img.shields.io/badge/day-66-blue)

## 📅 Today — Wednesday, September 2, 2026 (Day 66)

### 🧠 Challenge: Factorial
**Easy** · Recursion

Compute n! (n factorial) — the product of all positive integers up to n. Note: 0! = 1.

👉 [Full challenge + solution](./logs/2026-09-02.md)

### 💡 Tip: `Promise.allSettled()` waits for all, never rejects
Unlike `Promise.all()` which rejects on the first failure, `Promise.allSettled()` waits for all and reports status:

---

## 🗂️ Archive

All daily logs are saved in [`./logs/`](./logs/) as `YYYY-MM-DD.md` files.

- [2026-09-02](./logs/2026-09-02.md)
- [2026-09-01](./logs/2026-09-01.md)
- [2026-08-31](./logs/2026-08-31.md)
- [2026-08-30](./logs/2026-08-30.md)
- [2026-08-29](./logs/2026-08-29.md)
- [2026-08-28](./logs/2026-08-28.md)
- [2026-08-27](./logs/2026-08-27.md)
- [2026-08-26](./logs/2026-08-26.md)
- [2026-08-25](./logs/2026-08-25.md)
- [2026-08-24](./logs/2026-08-24.md)
- [2026-08-23](./logs/2026-08-23.md)
- [2026-08-22](./logs/2026-08-22.md)
- [2026-08-21](./logs/2026-08-21.md)
- [2026-08-20](./logs/2026-08-20.md)

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
