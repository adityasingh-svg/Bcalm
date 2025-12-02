# BCALM — End-to-End Conversion & Intelligence Layer for an Ed-Tech Landing Page

BCALM is a full-stack product prototype built to demonstrate how a modern education startup can convert cold traffic into qualified leads using a tightly integrated system of **scheduling**, **lead qualification**, **analytics**, and **AI tooling**.

---
<img width="1437" height="811" alt="image" src="https://github.com/user-attachments/assets/c359f124-a58e-46d4-b718-8d75b3d6eb33" />


## 🚀 Goal
To design, prototype, and implement a *production-ready* web experience capable of:
- Converting users through booking calls
- Capturing high-intent data
- Running skill assessments
- Tracking micro-interactions across the funnel
- Enabling quantitative decision-making for growth

---

## 🧩 Key Capabilities

### **1. Smart Scheduling System (Calendly + Custom Widget)**
- Instant “Book a Slot” popup widget embedded inside CTA.
- Custom onboarding fields: Name, Email, College, Goals.
- Auto-synced events to Google Sheets via Apps Script.
- Deduplication logic to sync only new appointments.
- Metadata logging for CTA origin, referrer, and campaign source.

---

### **2. Event Analytics Layer (Built from Scratch)**
- Micro-event tracking (CTA clicks, scroll depth, form interactions).
- Custom `trackEvent()` router with metadata for each event.
- Supabase backend to store user session paths and key events.
- Google Tag Manager pipeline for scalable instrumentation.
- Serverless cron to periodically sync scheduled-call events.

---

### **3. User Assessment Module**
- A short “AI Career Gap Assessment” built using JS.
- Automated scoring logic to identify gaps across:
  - Product Thinking  
  - AI Intuition  
  - Problem Framing  
  - Industry Knowledge  
- Auto-save all question-level responses to Supabase.
- Display dynamic result screen to drive call booking.

---

### **4. Admin Dashboard**
- Built with Supabase + simple React table.
- Shows:
  - Daily traffic trends
  - CTA interactions
  - Funnel conversion rate
  - Upcoming calls
  - Call completion status (manual + automated update flow)

---

### **5. Growth & Marketing Readiness**
- UTM-aware event tracking.
- WhatsApp click-out tracking.
- Funnel visualization model shared with business stakeholders.

---

## 🛠️ Tech Stack
- **Frontend**: HTML/CSS/JS (Replit)
- **Analytics**: Custom JS tracking, GTM, Supabase
- **Data Sync**: Google Apps Script + Scheduled Triggers
- **Scheduling**: Calendly widget + custom event fields
- **Backend**: Supabase (auth + DB)
- **Dashboards**: Supabase admin UI + custom JS dashboard

---

## 📈 Outcomes
- A working prototype demonstrating end-to-end conversion funnel.
- A measurable system for campaigns, call quality, and student intent.
- A reusable product analytics framework that can be installed in any landing page.
- A strong demonstration of PM-level **systems thinking**, **data thinking**, and **AI-productization**.

---

## 🔗 Status
Code is deployed on Replit (private for now).  
Documentation & screens in `/docs`.

