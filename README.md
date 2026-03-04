# 🤖 AI Agent: OKR Management System (n8n + Gemini + Airtable)

## 📖 Overview
This project features an intelligent **AI Agent** built in **n8n** that uses **Google Gemini 1.5 Pro** to manage OKRs (Objectives and Key Results) stored in **Airtable**. It allows users to interact with their data via natural language to search, create, and update records.

## ⚡ Key Features
* **Natural Language Processing**: Powered by Gemini 1.5 Pro to interpret user intent.
* **Airtable Integration**: Full CRUD (Create, Read, Update, Delete) capabilities for OKR tracking.
* **Memory Management**: Uses a "Simple Memory" node to maintain context during chat sessions.
* **Automated Video Editing**: Documentation processed via Clipchamp as seen in the timeline assets.

---

## 🛠️ Visual Workflow & Logic
Since the internal JSON is proprietary, the logic is documented below via system captures:

### 🎬 Step 1: Video Production & Timeline Logic
Documentation of the Clipchamp timeline, featuring grouped elements and optimized 8% audio levels.
![Video Timeline Assets](<Step 1 Video Elements Group Audio and MP4 Timeline.png>)

### 🤖 Step 2: n8n & Airtable Architecture
The core workflow engine connecting Google Gemini 1.5 Pro to the Airtable relational database for seamless data management.
![n8n Airtable Workflow](<Step 2 N8N Ai agents Airtable Workflow.png>)

### 💬 Step 3: Conversational Agent Interaction
Real-time demonstration of the AI Agent interpreting natural language to manage OKR records.
![Chat Interactions](<Step 3 N8N Workflow Chat Interactions.png>)## 🛠️ Visual Workflow & Logic

---

## 🧰 Tech Stack
* **Orchestration**: n8n
* **LLM**: Google Gemini 1.5 Pro
* **Database**: Airtable
* **Video Production**: Clipchamp
