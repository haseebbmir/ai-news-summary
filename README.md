# ai-news-summary
An automated AI-powered news digest built with n8n.
# 📰 Daily AI News Summarizer
An automated AI-powered news digest built with n8n.

# 🚀 What It Does

Every day at 9 AM the workflow:

Fetches latest AI news from RSS feeds
Selects the top 5 articles
Uses Google Gemini to summarize them
Formats a Telegram-ready digest
Sends the summary via Telegram Bot
Stores the daily summary in a database
🏗 Architecture
**
RSS Feed → n8n → Gemini AI → Telegram Bot → Database Storage**
