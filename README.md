# 🏥 Multilingual Patient Intake Assistant

> **Agents Assemble: The Healthcare AI Endgame Hackathon**  
> Built on [Prompt Opinion](https://promptopinion.ai) · Powered by Google Gemini

---

## 🌍 Overview | Loyiha haqida

**English:**  
A multilingual AI-powered patient intake agent that collects health information through a guided conversational interface. The agent communicates fluently in both **Uzbek** and **English**, making healthcare more accessible for Central Asian patients who may not be comfortable in English-only systems.

**O'zbek:**  
Bu loyiha bemor ma'lumotlarini sun'iy intellekt yordamida to'playdigan ko'p tilli agent hisoblanadi. Agent **o'zbek** va **ingliz** tillarida bemorlar bilan muloqot qilib, tibbiy so'rovnomani avtomatik to'ldiradi va shifokor uchun strukturalashtirilgan hujjat yaratadi.

---

## 🎯 Problem | Muammo

Millions of patients in Central Asia (Uzbekistan, Kazakhstan, Tajikistan) face a language barrier when interacting with digital healthcare systems built exclusively in English. This leads to:

- Incomplete or inaccurate patient intake forms
- Delayed diagnoses
- Reduced trust in digital health tools

---

## ✅ Solution | Yechim

**Multilingual Patient Intake Assistant** bridges this gap by:

1. Greeting patients in their preferred language (Uzbek or English)
2. Asking guided questions about symptoms, history, and medications
3. Automatically filling out the **Patient Health Survey** form
4. Generating a structured document ready for the physician

---

## 🚀 Demo | Namoyish

The agent is deployed on the **Prompt Opinion** platform and can be accessed as a configured Survey/Form Completion Agent.

**Sample conversation (O'zbek):**
```
User:  Assalomu alaykum, boshim og'riyapti va haroratim 38 daraja
Agent: Va alaykum assalom. O'zingizni qanday his qilayotganingizdan afsusdaman.
       Sizga yordam berish uchun, avval ism-familiyangizni bilsam bo'ladimi?
User:  Azamat Yusupov
Agent: Tushunarli, Azamat. Bu muammo bo'yicha avval shifokorga murojaat qildingizmi?
...
Agent: Barcha ma'lumotlarni so'rovnomaga kiritib qo'ydim. Hujjat yaratildi!
```

**Generated Output:**
```markdown
# Patient Health Survey
1. Full name: Azamat Yusupov
2. Age: ...
3. Primary reason for visit: Headache and fever (38°C)
4. Symptoms: Headache, high temperature
5. Pain level (1-10): 4
6. Duration: 3 days
...
```

---

## 🛠️ How It Works | Qanday ishlaydi

```
Patient (Uzbek/English)
        ↓
Prompt Opinion Platform
        ↓
Survey/Form Completion Agent
        ↓
Google Gemini AI (FREE TIER)
        ↓
Structured Patient Health Survey (PDF/Markdown)
        ↓
Doctor receives complete intake document
```

---

## 🧩 Tech Stack | Texnologiyalar

| Component | Technology |
|---|---|
| AI Platform | [Prompt Opinion](https://promptopinion.ai) |
| AI Model | Google Gemini (Free Tier) |
| Protocol | A2A (Agent-to-Agent) |
| Form Standard | Patient Health Survey (Public Form) |
| Languages | Uzbek 🇺🇿 · English 🇬🇧 |

---

## 📋 Features | Imkoniyatlar

- 🌐 **Bilingual** — Uzbek and English support
- 💬 **Conversational** — Natural dialogue, not a cold form
- 📄 **Auto-document** — Generates structured intake report
- 🔒 **Privacy-aware** — No data stored outside the platform
- 🏥 **Healthcare-ready** — Built on FHIR-compatible Prompt Opinion platform
- ⚡ **No-code agent** — Configured entirely within Prompt Opinion

---

## 🏆 Hackathon

- **Event:** [Agents Assemble: The Healthcare AI Endgame](https://agents-assemble.devpost.com)
- **Category:** A2A Agent (Survey/Form Completion)
- **Platform:** Prompt Opinion
- **Deadline:** May 11, 2026

---

## 👤 Author | Muallif

**Azamat** — Computer Science Teacher & AI Developer  
📍 Urgench, Uzbekistan  
🏫 InfoSchoolUz

---

## 📄 License

MIT License — free to use and adapt for educational and healthcare purposes.
