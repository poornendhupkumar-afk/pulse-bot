# 🌤️ Pulse – Daily Summary Bot

An automated Python bot that generates a daily summary containing live weather updates, an inspirational quote, and a random fact. The bot runs automatically using GitHub Actions and sends the summary directly to email.

---

## 🚀 Features

- 🌦️ Live weather updates using wttr.in API
- 💡 Daily motivational quotes
- 🎲 Random interesting facts
- 📄 Generates a daily summary report
- 📧 Sends the summary via email automatically
- ⏰ Scheduled execution using GitHub Actions
- 🔐 Secure credential management using GitHub Secrets
- 🛡️ Error handling for API failures

---

## 📸 Sample Output

```text
---------------------------
PULSE - Daily Summary
June 12, 2026
---------------------------

WEATHER
Thiruvananthapuram: 🌫️ +27°C

RANDOM FACT
In most watch advertisements the time displayed is 10:10.

TODAY'S QUOTE
"Don't blame others. It won't make you a better person."
- Lolly Daskal

---------------------------
```

---

## 🛠️ Tech Stack

- Python 3.11
- Requests
- SMTP Email
- GitHub Actions
- GitHub Secrets
- YAML

---

## 📂 Project Structure

```text
pulse-bot/
│
├── .github/
│   └── workflows/
│       └── daily.yml
│
├── bot.py
├── requirements.txt
├── daily_summary.txt
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/poornendhupkumar-afk/folio.git
cd folio
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

## 🔑 Environment Variables

The project uses GitHub Secrets for secure email authentication.

Required secrets:

```text
EMAIL_ADDRESS
EMAIL_PASSWORD
```

Example:

```text
EMAIL_ADDRESS = your_email@gmail.com
EMAIL_PASSWORD = Google App Password
```

---

## 🤖 GitHub Actions Automation

The bot is configured to:

- Run automatically every day
- Generate a fresh summary
- Send the summary via email
- Upload the summary as a workflow artifact

Workflow file:

```text
.github/workflows/daily.yml
```

---

## 📚 What I Learned

Through this project, I gained hands-on experience with:

- Python scripting
- REST API integration
- Error handling
- File handling
- Email automation
- GitHub Actions
- GitHub Secrets
- Workflow automation

---

## 🔮 Future Improvements

- Add currency exchange rates
- Add news headlines
- Support multiple recipients
- Generate HTML email reports
- Deploy as a cloud service

---

## 👨‍💻 Author

**Poornendhu P Kumar**

- GitHub: https://github.com/poornendhupkumar-afk
- LinkedIn: https://www.linkedin.com/in/poornendhu-p-kumar-89aab137b/

---

⭐ If you found this project interesting, consider giving it a star.
