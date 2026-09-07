# AI-news-mail-automation
AI-powered n8n automation that collects AI &amp; tech news, summarizes articles using Google Gemini, structures key insights, and delivers personalized news updates via email.
# 🤖 AI News Email Automation

AI News Email Automation is an AI-powered workflow designed to automatically collect, summarize, structure, and deliver the latest AI and technology news through email. The project uses workflow automation and Generative AI to reduce the time and effort required to manually read and track multiple news articles.

The workflow is built using **n8n**, which acts as the automation engine connecting different services and handling the complete process from collecting article information to sending the final email.

## 🔄 How It Works

The automation follows a simple pipeline:

**News Articles → Google Sheets → n8n → Gemini AI → Structured Summary → Email**

News article links and relevant information are stored in **Google Sheets**. When new information is added, n8n triggers the workflow and processes the article content. The content is then sent to **Google Gemini AI**, which analyzes the article and generates a concise, structured summary.

The AI extracts important information such as the **headline, category, summary, key points, important people or companies, significant numbers, why the news matters, and a one-line takeaway**. This makes the information easier to understand and consume.

After the AI processing is complete, n8n formats the generated content and automatically sends it through email as a personalized news update.

## ✨ Key Features

* Automated AI and technology news processing
* Google Sheets integration for managing article sources
* AI-powered article summarization
* Structured extraction of important information
* Concise and readable news summaries
* Automated email delivery
* End-to-end workflow automation using n8n
* Easily extendable for additional news sources and platforms

## 🛠️ Technologies Used

* **n8n** – Workflow automation
* **Google Sheets** – Article and data management
* **Google Gemini AI** – News analysis and summarization
* **Email** – Automated news delivery

## 🎯 Project Goal

The main goal of this project is to create a practical AI automation system that helps users stay informed about the rapidly changing AI and technology landscape. Instead of manually opening and reading multiple articles, users can receive important information in a concise and structured email.

This project can also be extended to support **daily AI newsletters, personalized news categories, duplicate detection, news ranking, LinkedIn/X publishing, and automated news discovery**.
