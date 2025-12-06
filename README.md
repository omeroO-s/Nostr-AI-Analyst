# 🟣 Nostr AI Analyst (n8n + Gemini 2.0)

![Nostr AI Analyst Cover](NOSTR_AI_ANALYST.png)

## 📖 Description
Keeping up with the fast-paced Nostr feed (e.g., `#damus` tag) is impossible manually. This automated agent acts as a 24/7 intelligence analyst.

It watches relays, aggregates threads, uses **Google Gemini 2.0** to extract themes/sentiment, and sends an Executive Summary to Telegram.

## ⚡️ Features
- **Relay Scraping:** Uses `n8n-nodes-nostrobots` to fetch notes.
- **AI Analysis:** Summarizes "Overall Themes" and "Key Highlights".
- **Multi-Channel:** Reports via Telegram (Instant) and Gmail (HTML).

## 📄 Sample Output (Telegram)
Here is how the AI report looks on your phone:

\`\`\`text
📊 NOSTR INTELLIGENCE REPORT
📅 Date: 2025-12-06

🔹 Overall Theme:
Discussion is focused on censorship resistance and the new "Zaps" feature update.

🔹 Key Highlights:
- User @alice mentioned issues with relay connectivity in EU.
- High engagement on threads discussing "Nostr vs X".

🔹 Sentiment:
Positive (80%) - Community is excited about the new client release.
\`\`\`

## 📥 Get the Workflow
This is a complex setup involving multiple nodes and AI prompts.
You can download the **Ready-to-Import JSON file** + **Setup Guide** here:

👉 https://ghostnodes.gumroad.com/l/zxxbul?_gl=1*n6vpp2*_ga*MzU4ODAwODU4LjE3NjM2NDAyODc.*_ga_6LJN6D94N6*czE3NjUwMjIxNzAkbzkkZzEkdDE3NjUwMjQ1NjkkajUzJGwwJGgw