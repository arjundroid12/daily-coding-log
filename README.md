# 📓 Daily Coding Log

> A new coding challenge, tip, and reflection prompt — auto-committed every day by GitHub Actions.

![Daily Commit](https://github.com/arjundroid12/daily-coding-log/actions/workflows/daily.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Day](https://img.shields.io/badge/day-85-blue)

## 📅 Today — Monday, September 21, 2026 (Day 85)

### 🧠 Challenge: Fibonacci (Efficient)
**Medium** · Dynamic Programming

Return the nth Fibonacci number. F(0) = 0, F(1) = 1, F(n) = F(n-1) + F(n-2). Handle n up to 50 efficiently.

👉 [Full challenge + solution](./logs/2026-09-21.md)

### 💡 Tip: Use `??` (nullish coalescing) instead of `||` for default values
`||` treats `0`, `''`, `false`, `NaN` as falsy — usually not what you want for defaults.

---

## 🗂️ Archive

All daily logs are saved in [`./logs/`](./logs/) as `YYYY-MM-DD.md` files.

- [2026-09-21](./logs/2026-09-21.md)
- [2026-09-20](./logs/2026-09-20.md)
- [2026-09-19](./logs/2026-09-19.md)
- [2026-09-17](./logs/2026-09-17.md)
- [2026-09-16](./logs/2026-09-16.md)
- [2026-09-15](./logs/2026-09-15.md)
- [2026-09-14](./logs/2026-09-14.md)
- [2026-09-12](./logs/2026-09-12.md)
- [2026-09-11](./logs/2026-09-11.md)
- [2026-09-10](./logs/2026-09-10.md)
- [2026-09-09](./logs/2026-09-09.md)
- [2026-09-08](./logs/2026-09-08.md)
- [2026-09-07](./logs/2026-09-07.md)
- [2026-09-06](./logs/2026-09-06.md)

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
