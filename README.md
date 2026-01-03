# Anime News Telegram Bot

A Python-based Telegram bot that automatically fetches the latest anime news from **Anime News Network (ANN)** and posts them to a Telegram channel with images, summaries, and clean formatting.

The bot avoids duplicate posts, respects Telegram rate limits, and supports timezone-aware daily filtering.

---

## ✨ Features

- Fetches latest anime news from Anime News Network
- Posts news with **image + summary** to Telegram
- Prevents duplicate posts using local JSON storage
- Timezone-aware (default: Asia/Kolkata)
- Automatic HTML escaping for Telegram safety
- Retry mechanism for network stability
- Fallback to text-only message if image fails
- Lightweight & cron-job friendly

---

## ⚙️ Requirements

- Python 3.9+
- Telegram Bot Token
- Telegram Channel / Group Chat ID

---

## 📦 Installation

```bash
pip install -r requirements.txt
