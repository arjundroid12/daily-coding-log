# 📓 Daily Coding Log

> A new coding challenge, tip, and reflection prompt — auto-committed every day by GitHub Actions.

![Daily Commit](https://github.com/arjundroid12/daily-coding-log/actions/workflows/daily.yml/badge.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Day](https://img.shields.io/badge/day-34-blue)

## 📅 Today — Saturday, August 1, 2026 (Day 34)

### 🧠 Challenge: FizzBuzz
**Easy** · Loops / Conditionals

Print numbers 1 to 100. For multiples of 3, print 'Fizz' instead of the number. For multiples of 5, print 'Buzz'. For multiples of both 3 and 5, print 'FizzBuzz'.

👉 [Full challenge + solution](./logs/2026-08-01.md)

### 💡 Tip: Use `??=` and `||=` for conditional assignment
ES2021 added compound assignment for nullish and logical OR:

---

## 🗂️ Archive

All daily logs are saved in [`./logs/`](./logs/) as `YYYY-MM-DD.md` files.

- [2026-08-01](./logs/2026-08-01.md)
- [2026-07-31](./logs/2026-07-31.md)
- [2026-07-30](./logs/2026-07-30.md)
- [2026-07-29](./logs/2026-07-29.md)
- [2026-07-28](./logs/2026-07-28.md)
- [2026-07-27](./logs/2026-07-27.md)
- [2026-07-26](./logs/2026-07-26.md)
- [2026-07-25](./logs/2026-07-25.md)
- [2026-07-24](./logs/2026-07-24.md)
- [2026-07-23](./logs/2026-07-23.md)
- [2026-07-22](./logs/2026-07-22.md)
- [2026-07-21](./logs/2026-07-21.md)
- [2026-07-20](./logs/2026-07-20.md)
- [2026-07-19](./logs/2026-07-19.md)

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
