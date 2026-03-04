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

### 1. The n8n Agent Architecture
The agent is triggered by a chat message and utilizes specific tools to query Airtable.
![n8n Workflow Structure](workflow_main.png)

### 2. Conversational Interface
Users can ask the agent to "List all my OKRs" or "Update progress," and the agent executes the corresponding Airtable tool.
![Gemini Chat Demo](chat_demo.png)

### 3. Documentation Timeline
The video walkthrough was edited to balance background audio at 8% to ensure the technical explanation is clear.
![Video Editing Timeline](timeline_edit.png)

---

## 🧰 Tech Stack
* **Orchestration**: n8n
* **LLM**: Google Gemini 1.5 Pro
* **Database**: Airtable
* **Video Production**: Clipchamp
