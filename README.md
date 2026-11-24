# 📡 rss-bangla

[![RSS](https://img.shields.io/badge/type-rss%20reader-blue)](https://github.com/tunnabri-ops/rss-bangla)
[![Language](https://img.shields.io/badge/UI-Bangla-orange)](https://github.com/tunnabri-ops/rss-bangla)

**Bangla RSS news reader — five feeds in one mobile-first page.**

> বাংলা সংস্করণ নিচে আছে। / Bangla version below.

## ✨ Features

- **5 feeds** in `feeds.json`:
  - Prothom Alo — `https://www.prothomalo.com/feed/`
  - BBC Bangla — `https://www.bbc.com/bengali/index.xml`
  - banglanews24.com — `https://www.banglanews24.com/rss/rss.xml`
  - BBC News — `https://feeds.bbci.co.uk/news/rss.xml`
  - Hacker News — `https://hnrss.org/frontpage`
- **Keeps working offline** — `index.html` keeps the static feed list visible when the feed fetch fails (for example, when opened as a file)

## 🚀 How to use

1. Open `index.html` in a browser and pick a feed.
2. To add or remove feeds, edit `feeds.json` — each entry needs a `name` and a feed `url`.

## ⚠️ Honest limits

- An Add-Feed form in the UI is still to come — for now, edit `feeds.json`.
- A direct-fetch fallback for when the feed proxy fails is still to come.

## 🇧🇩 বাংলা

**RSS বাংলা — বাংলার খবর এক জায়গায়, মোবাইল-বান্ধব পাতায়।**

- `index.html` খুলে ফিড বেছে পড়ুন
- নতুন ফিড যোগ করতে `feeds.json` সম্পাদনা করুন

## 📄 License

MIT — use it however you like; credit is appreciated.
