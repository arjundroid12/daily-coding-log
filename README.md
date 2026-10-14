# 📓 Daily Coding Log

> A new coding challenge, tip, and reflection prompt — auto-committed every day by GitHub Actions.

![Daily Commit](https://github.com/arjundroid12/daily-coding-log/actions/workflows/daily.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Day](https://img.shields.io/badge/day-108-blue)

## 📅 Today — Wednesday, October 14, 2026 (Day 108)

### 🧠 Challenge: Two Sum
**Easy** · Arrays / Hash Maps

Given an array of integers `nums` and an integer `target`, return the indices of the two numbers such that they add up to `target`.

👉 [Full challenge + solution](./logs/2026-10-14.md)

### 💡 Tip: Use `structuredClone()` for deep copies
Stop writing `JSON.parse(JSON.stringify(obj))` — it loses Dates, Maps, Sets, undefined, functions, and chokes on circular refs.

---

## 🗂️ Archive

All daily logs are saved in [`./logs/`](./logs/) as `YYYY-MM-DD.md` files.

- [2026-10-14](./logs/2026-10-14.md)
- [2026-10-13](./logs/2026-10-13.md)
- [2026-10-12](./logs/2026-10-12.md)
- [2026-10-11](./logs/2026-10-11.md)
- [2026-10-10](./logs/2026-10-10.md)
- [2026-10-09](./logs/2026-10-09.md)
- [2026-10-08](./logs/2026-10-08.md)
- [2026-10-07](./logs/2026-10-07.md)
- [2026-10-06](./logs/2026-10-06.md)
- [2026-10-05](./logs/2026-10-05.md)
- [2026-10-04](./logs/2026-10-04.md)
- [2026-10-03](./logs/2026-10-03.md)
- [2026-10-02](./logs/2026-10-02.md)
- [2026-10-01](./logs/2026-10-01.md)

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
