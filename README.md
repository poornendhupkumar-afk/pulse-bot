# 🚀 Pulse Bot

Pulse Bot is a Python-based automation project that generates and delivers useful daily information directly to your inbox.

The project combines API integration, web scraping, email automation, and GitHub Actions to create a fully automated daily information system.

---

## ✨ Features

* 🌤️ Live weather updates using APIs
* 💡 Random fact generator
* 💬 Daily motivational quotes
* 📧 Automated email delivery using Gmail SMTP
* ⚠️ Weather alert system using OpenWeatherMap API
* 📰 Daily News Digest from multiple news sources
* 🔄 Scheduled execution using GitHub Actions
* 🔐 Secure credential management using GitHub Secrets

---

## 🛠️ Tech Stack

* Python
* GitHub Actions
* Requests
* BeautifulSoup4
* SMTP Email Automation
* OpenWeatherMap API
* GitHub Secrets

---

## 📁 Project Structure

```text
pulse-bot/
│
├── bot.py
├── weather_alert.py
├── news_digest.py
├── requirements.txt
├── daily_summary.txt
├── README.md
│
└── .github/
    └── workflows/
        └── daily.yml
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/poornendhupkumar-afk/pulse-bot.git
cd pulse-bot
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the bot:

```bash
python bot.py
```

---

## ⚙️ GitHub Secrets Required

Add the following secrets in:

Settings → Secrets and Variables → Actions

```text
EMAIL_ADDRESS
EMAIL_PASSWORD
EMAIL_SENDER
EMAIL_RECEIVER
WEATHER_API_KEY
```

---

## 📧 Automated Tasks

### Daily Summary

Generates a report containing:

* Current weather
* Random fact
* Motivational quote

and emails it automatically.

### Weather Alert

Checks weather conditions using OpenWeatherMap API.

If:

* Temperature exceeds 35°C
* Rain is predicted

an email alert is sent automatically.

### News Digest

Collects top headlines from:

* Hacker News
* BBC News
* AP News

and sends a formatted HTML email containing:

* Headlines
* Publication time
* Source links

---

## 🎯 What I Learned

This project helped me gain hands-on experience with:

* Python automation
* API integration
* Web scraping
* Email automation
* Environment variables
* GitHub Actions workflows
* CI/CD concepts
* Secure secret management

---

## 🔮 Future Improvements

* Personalized news categories
* AI-generated daily summaries
* Telegram and Discord notifications
* Multiple city weather monitoring
* Database storage for reports

---

## 👨‍💻 Author

Poornendhu P Kumar

GitHub:
https://github.com/poornendhupkumar-afk

LinkedIn:
https://www.linkedin.com/in/poornendhu-p-kumar-89aab137b/
