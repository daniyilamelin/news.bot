News Parser Telegram Bot

Description

Telegram bot for collecting and delivering latest news from selected sources.
Users can browse news by categories and receive them in a clean and readable format directly in Telegram.

The project includes:

- News scraping from RSS feeds and websites
- AI-based summarization of articles
- Interactive Telegram interface

Features

- Parsing news from RSS feeds and web pages
- Image extraction and URL validation
- AI-generated short summaries of news
- Category-based news browsing
- Interactive Telegram keyboards
- Modular project structure

Project Structure

- "news_scraper.py" — collects and parses news from sources
- "ai_generate.py" — generates summaries using AI
- "handlers.py" — Telegram bot command handlers
- "config.py" — configuration and environment variables
- "run.py" — main entry point of the bot

Tech Stack

- Python 3.8+
- python-telegram-bot
- requests
- BeautifulSoup4
- Flask (for keep_alive)
- dotenv (.env configuration)

Installation & Setup

1. Clone the repository:
   git clone https://github.com/YOUR_USERNAME/tg_bot.git

2. Navigate to the project:
   cd tg_bot

3. Install dependencies:
   pip install -r requirements.txt

4. Create ".env" file:
   TELEGRAM_TOKEN=your_telegram_bot_token
   API_KEY=your_ai_api_key

5. Run the bot:
   python run.py

How It Works

- The bot fetches news from configured sources (RSS/web scraping)
- Content is processed and cleaned
- AI module generates short summaries
- Users interact via Telegram commands and inline keyboards
- Flask keep_alive ensures the bot stays online (if deployed)

Notes

This project demonstrates:

- Web scraping techniques
- Working with APIs
- Telegram bot development
- Modular Python architecture
- Basic AI integration for text processing
