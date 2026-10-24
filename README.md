# 📓 Daily Coding Log

> A new coding challenge, tip, and reflection prompt — auto-committed every day by GitHub Actions.

![Daily Commit](https://github.com/arjundroid12/daily-coding-log/actions/workflows/daily.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Day](https://img.shields.io/badge/day-118-blue)

## 📅 Today — Saturday, October 24, 2026 (Day 118)

### 🧠 Challenge: Merge Two Sorted Arrays
**Medium** · Arrays / Two Pointers

Given two sorted arrays `a` and `b`, merge them into a single sorted array.

👉 [Full challenge + solution](./logs/2026-10-24.md)

### 💡 Tip: Use `structuredClone()` for deep copies
Stop writing `JSON.parse(JSON.stringify(obj))` — it loses Dates, Maps, Sets, undefined, functions, and chokes on circular refs.

---

## 🗂️ Archive

All daily logs are saved in [`./logs/`](./logs/) as `YYYY-MM-DD.md` files.

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
- [2026-10-11](./logs/2026-10-11.md)

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
