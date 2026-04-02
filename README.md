# 🏥 Multilingual AI Medical Assistant & Medication Reminder System

> Devoteam Internship Project · Jul–Aug 2025

---

## Overview

An AI-powered healthcare automation system built during my internship at **Devoteam**. It combines a **multilingual medical assistant** (capable of answering health-related questions in multiple languages) with an **intelligent medication reminder engine** that sends scheduled reminders to patients via messaging platforms.

Built entirely on **n8n** automation workflows with LLM-powered pipelines.

---

## Features

- **Multilingual Medical Q&A** — patients can ask medical questions in their native language; the assistant responds in the same language using an LLM backend
- **Medication Reminder Engine** — automated scheduling system that sends personalized medication reminders at the right times
- **Conversation Memory** — maintains context across a patient's session for coherent follow-up questions
- **n8n Workflow Architecture** — no-code/low-code automation backbone, easy to extend and maintain

---

## Tech Stack

| Tool | Role |
|---|---|
| n8n | Workflow automation engine |
| LLM API | Medical Q&A + language understanding |
| Telegram / Messaging API | Patient-facing interface |
| Custom Logic Nodes | Scheduling, language detection, reminder triggers |

---

## Architecture

```
Patient Message
    ↓
Language Detection
    ↓
LLM Medical Assistant (multilingual)
    ↓
Response → Patient
    
[Parallel]
Medication Schedule → Trigger at set times → Reminder → Patient
```

---

## Context

Built as part of a **2-month AI/ML internship at Devoteam** (Jul–Aug 2025), focused on practical LLM deployment, prompt engineering, and n8n workflow architecture.

> Note: Workflow JSON files and full implementation details are internal to Devoteam. This repo documents the architecture and approach.

---

## Author

**Aymane Idrissi Khamlichi** — [github.com/ikaymane](https://github.com/ikaymane)
