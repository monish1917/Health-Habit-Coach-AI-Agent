# Health-Habit-Coach-AI-Agent
AI-powered Health Habit Coach built using n8n, Google Gemini AI, and Google Sheets.

# 🩺 Health Habit Coach AI Agent

An AI-powered Health Habit Coach built using **n8n**, **Google Gemini AI**, and **Google Sheets**. This project helps users build healthy habits by generating personalized wellness recommendations, tracking daily habits, and providing automated weekly health analysis.

---

## 📌 Project Overview

The Health Habit Coach AI Agent is an intelligent automation workflow that collects user health information, analyzes daily habits, and generates personalized health recommendations using Google Gemini AI. The entire workflow is automated using n8n and stores data securely in Google Sheets.

---

## ✨ Features

- 📝 Collects user health information through an n8n Form
- 🤖 Generates personalized wellness recommendations using Google Gemini AI
- 📊 Stores user data in Google Sheets
- 💧 Tracks daily habits such as:
  - Water intake
  - Sleep hours
  - Exercise
  - Mood
- ⏰ Sends automated daily motivational reminders
- 📈 Generates weekly AI-powered health analysis
- 📄 Stores weekly reports automatically

---

## 🛠 Technologies Used

- n8n
- Google Gemini AI
- Google Sheets
- Google Forms (n8n Form Trigger)
- JavaScript (Workflow Expressions)

---

## 🔄 Workflow Architecture

### Workflow 1 – Health Habit Coach
User Form
⬇
Google Gemini AI
⬇
Google Sheets

### Workflow 2 – Daily Health Reminder
Schedule Trigger
⬇
Google Gemini AI
⬇
Daily Motivation

### Workflow 3 – Daily Habit Tracker
Habit Form
⬇
Google Sheets

### Workflow 4 – Weekly Health Analysis
Schedule Trigger
⬇
Read Google Sheets
⬇
Google Gemini AI
⬇
Weekly Report
⬇
Google Sheets

---

## 📂 Repository Structure

```
Health-Habit-Coach-AI-Agent
│
├── 01 - Health Habit Coach.json
├── 02 - Daily Health Reminder.json
├── 03 - Daily Habit Tracker.json
├── 04 - Weekly Health Analysis.json
├── screenshots/
└── README.md
```

---

## 📸 Screenshots

### Health Habit Coach
(health-habit-coach-workflow.png)

### Daily Health Reminder
(daily-health-reminder.png)

### Daily Habit Tracker
(daily-health-reminder.png)

### Weekly Health Analysis
(weekly-health-analysis.png)

---

## 🚀 How to Run

1. Install n8n.
2. Import all four workflow JSON files.
3. Connect your Google Gemini API credentials.
4. Connect Google Sheets credentials.
5. Publish the workflows.
6. Open the Production Form URL.
7. Submit the form and view the generated health recommendations.

---

## 🎯 Future Improvements

- Email notifications
- Telegram integration
- WhatsApp reminders
- Dashboard for health analytics
- Database integration (MySQL/PostgreSQL)
- User authentication

---

## 📚 Learning Outcomes

This project demonstrates:

- AI Agent Development
- Workflow Automation
- Prompt Engineering
- Google Gemini Integration
- Google Sheets Automation
- Low-Code Development with n8n

This project is created for educational and portfolio purposes.
