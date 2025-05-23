# ⏰ GitHub Activity Logger 🔄

Keep your GitHub green, show off your automation skills, and look like a CI/CD boss — all with this sleek daily GitHub Action.

<p align="center">
  <img src="https://img.shields.io/github/actions/workflow/status/yourusername/yourrepo/keep-alive.yml?label=Daily%20Update&style=for-the-badge" alt="workflow" />
  <img src="https://img.shields.io/github/last-commit/yourusername/yourrepo?style=for-the-badge" alt="last commit"/>
</p>

---

## 💡 What Is This?

This repo runs a scheduled GitHub Action every day that:

✅ Updates a timestamp file  
✅ Logs the action with the current date  
✅ Commits automatically to trigger your green contribution graph

All without you lifting a finger 🧠.

---

## ⚙️ How It Works

The GitHub Actions workflow:

1. Runs daily at midnight UTC (`0 0 * * *`)
2. Writes the current UTC time to `timestamp.txt`
3. Appends a log entry to `log.txt`
4. Commits and pushes the change

### 📁 Files

| File | Purpose |
|------|---------|
| `timestamp.txt` | Shows the last run date |
| `log.txt`       | Logs all update times |

---

## 🚀 Use Cases

- 👨‍💻 Show off GitHub Actions & automation skills  
- 🌱 Keep your GitHub profile active  
- 🧪 Use as a starter template for CI/CD or cron job demos  
- 🔄 Learn scheduled workflows hands-on  

---

## 🛠️ Built With

- **GitHub Actions**
- **Cron Jobs**
- **Bash Scripting**

---

## 📌 Live Demo

Check out the auto-updated files:

- [`timestamp.txt`](./timestamp.txt)
- [`log.txt`](./log.txt)

Updated daily by GitHub itself ⚡

---

## 🧑‍💻 How to Use (Optional)

Want to try it yourself?

1. **Fork this repo**
2. Make sure your repo is **public**
3. Add a secret called `GH_TOKEN` with your personal access token
4. Watch it go 🤖

---

## 📄 License

MIT — use it, modify it, make it your own.

---

> 👨‍🚀 Made by [Daniel Tadesse](https://github.com/danitadesse/danitadesse) — just a dev who automates everything and loves making things smarter, not harder.
