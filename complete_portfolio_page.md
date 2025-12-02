# 🚀 BCALM — Conversion Intelligence Layer for an AI EdTech Product

*A complete product case study demonstrating PM, AI-PM, prototyping & analytics execution.*

---

## 📌 Summary

BCALM (Behavior-Calibrated Lead Machine) is a full-stack product prototype I built to solve a common growth problem in education businesses:  
**how to convert cold website traffic into qualified, high-intent leads—while building an AI-ready data foundation for future personalization.**

I designed and shipped an end-to-end system integrating:

- **Smart scheduling (Calendly widget + custom fields)**
- **Lead qualification (AI Gap Assessment)**
- **Micro-event analytics (custom tracker + Supabase)**
- **Automated data pipelines (Google Apps Script + cron)**
- **Admin dashboard (call pipeline, funnel metrics)**

This case study walks through the **problem, solution, architecture, screenshots**, and what it proves about my PM capabilities.

---

# 1️⃣ Problem

### ❌ Traffic was coming in, but conversions were not.

The website generated interest—but there was:

- No structured way to capture high-intent leads  
- No data on where users dropped off  
- No qualification layer to understand skill gaps  
- No visibility into booked calls or call quality  
- No AI-readiness for personalized nudges or scoring  

Essentially, **no intelligence layer around the funnel.**

---

# 2️⃣ Hypothesis

> **If we design an integrated system that captures intent, behavior, and context at every step, we can boost conversions and enable AI-powered personalization later.**

This led to the concept of **BCALM**—a single system handling:

**Interaction → Intention → Intelligence → Insights**

---

# 3️⃣ Solution Overview

BCALM is built as a **5-component system**:

---

## **1. Smart Scheduling Widget**

- Instant “Book a Slot” popup using Calendly inline widget  
- Custom qualification fields: *Name, Email, College, Goals*  
- Embedded metadata: *CTA clicked, landing path, UTM parameters*  
- Auto-sync to backend every 10 minutes  
- Deduplication: only new events are added  

---

## **2. Full-Funnel Event Tracking**

Built using custom JavaScript + Supabase:

Events tracked:
- CTA Clicks (Schedule Call, WhatsApp, Assessment Start, Apply Now)
- Scroll depth
- Assessment steps & answers
- Form interactions
- Landing page behavior with metadata

Each event includes:
- `sessionId`
- `eventName`
- `timestamp`
- `pageURL`
- `referrer`
- `UTM source/medium/campaign`

This created an **end-to-end behavior dataset**.

---

## **3. AI Career Gap Assessment**

An interactive assessment built using plain HTML/JS:

- Evaluates **Product Thinking, AI Intuition, Problem Framing**  
- Auto-calculated scores  
- Detailed response logging  
- Assessment → Personalized CTA → Schedule a call  
- Data stored for lead-scoring models  

This became the **qualification engine**.

---

## **4. Admin Dashboard for Call Pipeline**

Built with Supabase + lightweight JS front-end.

It displays:

- Daily traffic  
- Events per session  
- Assessment completion data  
- Upcoming calls  
- Call-completion toggle (ops workflow)

This dashboard acts as the **single truth source** for marketing + operations.

---

## **5. Automated Data Sync**

Using Google Apps Script:

- Syncs Calendly → Google Sheets  
- Runs every 10 minutes via trigger  
- Deduplicates events  
- Ensures latest status of booked calls  

This automated the **entire operations flow**.

---

# 4️⃣ Architecture Diagram

<img width="379" height="387" alt="image" src="https://github.com/user-attachments/assets/e6c6263d-9d74-4894-8761-62f6cd1ae38a" />


---

# 5️⃣ Screens & UX Overview (Textual)

### 🖼️ **Landing Page**
- Hero section  
- Value props  
- CTA opens Calendly widget popup  

### 📅 **Calendly Booking Flow**
- Inline popup  
- Custom fields  
- Instant confirmation  

### 📝 **Assessment**
- Progress steps  
- Interactive questions  
- Score breakdown  
- CTA to book call  

### 📊 **Dashboard**
- Table + charts  
- Status columns  
- Call log  
- Event explorer  

---

# 6️⃣ Why This Project Matters

### 📌 Demonstrates complete PM thinking
- Problem discovery  
- Funnel mapping  
- System design  
- Analytics instrumentation  
- Prioritization  

### 📌 Shows AI PM readiness
- Captured structured, labeled data  
- Built qualification dimensions  
- Designed foundation for future ML scoring  
- Established data schema for personalization  

### 📌 Shows ability to execute
- Designed UX  
- Coded actual prototype  
- Automated backend pipelines  
- Built dashboard  
- Launched fully working version  

### 📌 Not just “screens”—a complete working system  
Very few PM portfolios contain this level of **end-to-end execution**.

---

# 7️⃣ What I Did (My Role)

- Product strategy & problem definition  
- UX wireframes & IA  
- Javascript prototyping (widget, tracker, assessment)  
- Supabase data modeling  
- Google Apps Script automation  
- Dashboard development  
- User path modeling  
- Growth & conversion analysis  

---

# 8️⃣ Key Metrics Designed For

- CTR to booking widget  
- Booking completion  
- Assessment start → finish  
- Session → CTA mapping  
- Lead quality score  
- Daily conversion funnel  

These weren’t just tracked—they **shaped the design decisions**.

---

# 9️⃣ Results (Prototype Outcomes)

- Complete working system implemented in days  
- Structured database usable for future ML models  
- Visible improvement in call pipeline clarity  
- Full traceability from landing → assessment → booking  
- Reusable analytics & scheduling framework  

---

# 🔟 What I’d Build Next (Roadmap)

### **Short-term**
- Predictive lead scoring (classification model)  
- NLP-based analysis of assessment answers  
- Calendar availability optimizer  

### **Long-term**
- AI Copilot for personalized nudges  
- Adaptive landing page based on user behavior  
- Automated call-prioritization engine  

---

# 📣 Final Takeaways

> **BCALM proves that I can operate as both a Product Manager and an AI-First Builder: I identify core problems, design user-centric flows, instrument data, integrate AI thinking, and ship working systems—fast.**



