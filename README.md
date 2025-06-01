# 🤖 AI-Personalized Lead Generator Agent

An automated, intelligent lead generation system built with [n8n](https://n8n.io). This project collects from a website survey on GoHighLevel, enriches them through Instagram scraping using Apify, and crafts personalized outreach messages with Claude AI—all without manual intervention.

---

## 🧠 What It Does

- Collects business profile data from GoHighLevel (CourseCreator 360)
- Uses Claude AI to generate tailored Instagram search terms based on lead criteria
- Scrapes Instagram profiles using Apify
- Scores leads with AI based on multiple weighted factors
- Generates personalized outreach messages for high-potential leads

---

## 🔧 Tech Stack

- **n8n** – Workflow automation
- **Telegram** – Lead input via chat interface
- **Apify** – Instagram scraping
- **Claude AI** – Lead scoring & personalized messaging
- **Google Sheets** – Optional output storage or reporting

---

## 📦 Features

- ✅ Interactive Telegram survey with conversation memory
- ✅ Custom search term generation using AI
- ✅ Fully automated Instagram scraping with filters
- ✅ AI-powered lead scoring based on:
  - Bio Keywords (30%)
  - Follower Count (20%)
  - Hashtag Relevance (25%)
  - General Keyword Matching (25%)
- ✅ Personalized message generation for top leads
- ✅ Google Sheets or webhook export for CRM integration

---

## 🚀 Getting Started

1. Clone this repo:
   ```bash
   git clone https://github.com/didiberman/ai-personalized-lead-generator.git
