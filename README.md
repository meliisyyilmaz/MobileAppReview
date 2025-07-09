# MobileAppReview

# Duoling App Review NLP — What Users Want 📱🧠

This project explores sentiment mismatches in Google Play Store reviews — specifically when the *star rating* and the *text sentiment* don't quite agree.

## 📌 Overview
- App: **Duolingo**
- Total reviews collected: 20,000
- Methods:
  - Score-based sentiment
  - Text-based sentiment (VADER)
  - Transformer-based sentiment (CardiffNLP)
  - GPT-4 reasoning on mismatch cases

## 🧠 Key Insights
- Lexicon-based models like VADER struggle with sarcasm, irony, and passive aggression.
- Transformer models like CardiffNLP perform much better but still leave room for gray-area cases.
- GPT-4 was used to provide contextual reasoning on mismatches, offering human-like interpretation.

## 🛠 Technologies
- Python (pandas, seaborn, matplotlib)
- Google Play Scraper
- VADER
- CardiffNLP (huggingface)
- OpenAI GPT-4

## 🤖 Future Ideas
- Auto-tagging misleading positive/negative reviews
- Multi-class review classifier (UX, pricing, bugs, etc.)
- Agent-style chat insights from raw feedback

