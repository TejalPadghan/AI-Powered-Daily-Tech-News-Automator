# AI-Powered-Daily-Tech-News-Automator 

OVERVIEW:
AutoTech Digest is a fully automated system that fetches, filters, summarizes, and delivers the latest technology news to your inbox using n8n workflow automation and Google Gemini LLM. This project showcases how smart automation and AI can save time, ensure news relevance, and deliver actionable tech insights every day—without manual effort.

FEATURES:
Automated Multi-Source Collection: Aggregates tech news from multiple RSS feeds.
Intelligent Filtering & Deduplication: Randomizes order, filters duplicates, and keeps only the latest articles.
AI Summarization: Uses Gemini LLM to generate succinct, context-aware, markdown-formatted digests.
Email Delivery: Sends polished daily digests to your email automatically.
No-Code & Extensible: Built with n8n for easy customization and expansion (add new sources, delivery channels, analytics).

HOW IT WORKS:
Scheduled Run: Triggered automatically each day.
RSS Fetch: Collects articles from curated technology news feeds.
Merge & Shuffle: Combines all articles and shuffles them for freshness.
Limit & Filter: Keeps only the most recent, non-duplicate articles.
AI Summarization: Gemini LLM summarizes and rates news relevance.
Markdown Formatting: Converts summaries to clean, readable email content.
Automated Email: Sends the digest to the configured recipient(s).

EXAMPLE OUTPUT
text:
## AI Tech Digest - October 2025
- **OpenAI’s ChatGPT Usage:**
  High relevance. Safety teams now identify users with potential distress, emphasizing the need for ethical AI management.
- **Philosophy of AI:**  
  Wired explores whether AI should be seen as guidance or just a tool, urging critical, unbiased perspective.
- … etc.
