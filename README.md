# 🧠 n8n + Quadratic | Supply Chain Automation & Analysis

This project is part of the "AI Tools for Data Analysis", where I built a real-time **data automation pipeline** and **business insights dashboard** using **n8n** and **Quadratic** (an AI-powered spreadsheet).

---

## 🚀 Project Overview

**Goal:**  
To solve a supply chain problem by automating data migration from email to database and analyzing it to extract key performance indicators (KPIs) and actionable business insights.

---

## 🔧 Tools & Tech Used

- **n8n:** Workflow automation platform (trigger, Gmail integration, data transformation)
- **Quadratic:** AI-powered spreadsheet used for analysis and visualization
- **Supabase (PostgreSQL):** Cloud database to store and manage the ingested data
- **Gmail API:** Trigger to watch for incoming emails with CSV attachments

---

## ⚙️ Workflow Architecture

1. 📬 **Data Ingestion:**  
   - Trigger: New email with CSV attachment in Gmail  
   - Parse CSV, clean data

2. 🛢️ **Data Storage:**  
   - Insert the clean data into a PostgreSQL table in Supabase

3. 📊 **Data Analysis:**  
   - Import into Quadratic
   - Analyze KPIs like stockouts, delivery delays, demand patterns, etc.
   - Use AI formulas and validations to extract insights

---

## 📈 Key Business Insights

- Identified frequent **stockout issues** and their locations
- Flagged **delayed deliveries**
- Monitored warehouse efficiency based on historical trends
- Enabled proactive **inventory planning**

---

## 🔗 Project Assets

- 🔄 **Quadratic File** → [View Analysis](https://app.quadratichq.com/file/fc27c668-e39e-4d07-b1d6-ea9fc77df80c?sheet=cbb55ee0-c2c7-413c-b9f6-d857f07b67b6)
- 🛠️ **Supabase DB View** → [View Tables](https://supabase.com/dashboard/project/htbpijwgyujgdhjvrifr/database/tables)

---

## 📚 What I Learned

- How to use **n8n** for end-to-end data automation
- Connecting multiple tools to create a seamless pipeline
- Leveraging **AI-powered analysis** to make informed business decisions
- Hands-on experience in the **Supply Chain domain**






