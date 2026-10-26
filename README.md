# 📓 Daily Coding Log

> A new coding challenge, tip, and reflection prompt — auto-committed every day by GitHub Actions.

![Daily Commit](https://github.com/arjundroid12/daily-coding-log/actions/workflows/daily.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Day](https://img.shields.io/badge/day-120-blue)

## 📅 Today — Monday, October 26, 2026 (Day 120)

### 🧠 Challenge: Throttle Function
**Medium** · Closures / Async

Implement a `throttle(func, limit)` function that ensures `func` is called at most once per `limit` ms.

👉 [Full challenge + solution](./logs/2026-10-26.md)

### 💡 Tip: Use `Array.from()` with a mapper for clean transforms
`Array.from()` accepts a map function as its second argument — cleaner than `.map()` after `.fill()`.

---

## 🗂️ Archive

All daily logs are saved in [`./logs/`](./logs/) as `YYYY-MM-DD.md` files.

- [2026-10-26](./logs/2026-10-26.md)
- [2026-10-24](./logs/2026-10-24.md)
- [2026-10-23](./logs/2026-10-23.md)
- [2026-10-22](./logs/2026-10-22.md)
- [2026-10-21](./logs/2026-10-21.md)
- [2026-10-20](./logs/2026-10-20.md)
- [2026-10-19](./logs/2026-10-19.md)
- [2026-10-18](./logs/2026-10-18.md)
- [2026-10-17](./logs/2026-10-17.md)
- [2026-10-16](./logs/2026-10-16.md)
- [2026-10-15](./logs/2026-10-15.md)
- [2026-10-14](./logs/2026-10-14.md)
- [2026-10-13](./logs/2026-10-13.md)
- [2026-10-12](./logs/2026-10-12.md)

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
