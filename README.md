# 🧠 NagarNetra Backend — AI Civic Issue Detection & Management API

The **NagarNetra Backend** powers the AI intelligence, civic issue detection, duplicate handling, analytics, and admin operations for the NagarNetra platform.  
It is built using **FastAPI**, integrates **Google Gemini AI**, **computer vision models**, and **Firebase Firestore** for real-time data storage.

---

## 🚀 Key Responsibilities

- AI-based civic issue detection from images
- Gemini-powered short descriptions & explanations
- Duplicate issue detection using geolocation
- Severity & urgency classification
- Citizen voting system
- Admin issue management APIs
- Heatmap analytics
- Municipal PDF report generation

---

## 🛠️ Tech Stack

- **Framework:** FastAPI (Python)
- **AI Models:**  
  - GroundingDINO / YOLO (image detection)  
  - Google Gemini (text intelligence)
- **Database:** Firebase Firestore
- **PDF Reports:** ReportLab
- **Auth & Storage:** Firebase Admin SDK

---
# ⚙️ Backend Setup & API Endpoints — NagarNetra

This document explains how to **set up the NagarNetra backend locally** and lists **all available API endpoints**.

---

## 🧩 Backend Setup (Local)

### 1️⃣ Create Conda Environment

-- bash
--conda create -n nagarnetra-ai python=3.10 -y
--conda activate nagarnetra-ai

### 2️⃣ Install Dependencies
--pip install -r requirements.txt
--pip install fastapi uvicorn firebase-admin python-dotenv reportlab google-genai

### 3️⃣ Run Backend Server
--uvicorn main:app --reload
--If uvicorn is not found:
--pip install uvicorn

### 4️⃣ Verify Backend
--Service	URL
--API Root	http://127.0.0.1:8000
--Swagger Docs	http://127.0.0.1:8000/docs

