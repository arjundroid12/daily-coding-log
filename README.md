# 📓 Daily Coding Log

> A new coding challenge, tip, and reflection prompt — auto-committed every day by GitHub Actions.

![Daily Commit](https://github.com/arjundroid12/daily-coding-log/actions/workflows/daily.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Day](https://img.shields.io/badge/day-131-blue)

## 📅 Today — Friday, November 6, 2026 (Day 131)

### 🧠 Challenge: Remove Duplicates from Array
**Easy** · Arrays / Sets

Return a new array with duplicates removed, preserving the order of first occurrence.

👉 [Full challenge + solution](./logs/2026-11-06.md)

### 💡 Tip: `Array.prototype.at()` for negative indexing
Forget `arr[arr.length - 1]` — use `.at(-1)`.

---

## 🗂️ Archive

All daily logs are saved in [`./logs/`](./logs/) as `YYYY-MM-DD.md` files.

- [2026-11-06](./logs/2026-11-06.md)
- [2026-11-05](./logs/2026-11-05.md)
- [2026-11-04](./logs/2026-11-04.md)
- [2026-11-03](./logs/2026-11-03.md)
- [2026-11-02](./logs/2026-11-02.md)
- [2026-11-01](./logs/2026-11-01.md)
- [2026-10-31](./logs/2026-10-31.md)
- [2026-10-30](./logs/2026-10-30.md)
- [2026-10-29](./logs/2026-10-29.md)
- [2026-10-28](./logs/2026-10-28.md)
- [2026-10-27](./logs/2026-10-27.md)
- [2026-10-26](./logs/2026-10-26.md)
- [2026-10-24](./logs/2026-10-24.md)
- [2026-10-23](./logs/2026-10-23.md)

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
