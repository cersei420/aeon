---
name: crypto-research
description: Research crypto coins and Twitter sentiment
category: research
schedule: "0 9 * * *"
tags: [crypto, venice, telegram]
---

Daily crypto research task:

1. Search for trending crypto coins on Twitter/X
2. Analyze sentiment (bullish/bearish)
3. Check for major news or announcements
4. Generate summary report

Use Venice API for all AI calls:
- API Key: ${VENICE_API_KEY}
- Base URL: https://api.venice.ai/v1
- Model: kimi-k2-6

Output format:
- Coin name
- Sentiment score (-10 to +10)
- Key news (if any)
- Recommendation (watch/buy/avoid)

Send final report via Telegram to ${TELEGRAM_CHAT_ID}
