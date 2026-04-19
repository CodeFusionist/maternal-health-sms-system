# 🩺 Maternal Health SMS Advisory System

---

## 📷 Preview
(Screenshots coming soon)

---

## 📌 Overview

A low-cost SMS-based maternal health system designed to improve antenatal care adherence in rural Kenya by delivering timely reminders and health advisories to expectant mothers.

This system was developed as part of a Diploma in ICT project and focuses on accessibility, simplicity, and real-world usability in low-resource settings.

---

## ❗ The Problem

In many rural communities:

- Expectant mothers miss antenatal clinic visits due to lack of timely reminders  
- Health information between visits is limited or unavailable  
- Most users rely on basic feature phones, not smartphones  
- Internet access is inconsistent or unavailable  

As a result, preventable complications often go unnoticed due to gaps in communication.

---

## 💡 The Solution

This system uses **SMS (Short Message Service)** to deliver:

- Timely antenatal appointment reminders  
- Stage-based pregnancy health advice  
- Alerts on potential danger signs  
- Basic nutrition and self-care guidance  

The system works entirely on basic mobile phones, requiring **no internet access**, making it highly accessible in rural environments.

---

## ⚙️ Key Features

- 📅 Automated appointment reminders  
- 🤰 Trimester-based health messaging  
- ⚠️ Danger sign alerts  
- 🌍 Multilingual support (English & Swahili)  
- 🔁 Message retry and logging system  
- ⏱ Scheduled messaging using cron jobs  

---

## 🏗 System Architecture

The system is built using simple, reliable technologies:

- **Backend:** PHP  
- **Database:** MySQL  
- **Scheduling:** Cron Jobs  
- **SMS Gateway:** Africa’s Talking  
- **Logic:** Expected Date of Delivery (EDD)-based message generation  

Messages are automatically scheduled and sent based on each patient’s pregnancy stage.

---

## 🌍 Real-World Impact

- Works on **any mobile phone** (no smartphone required)  
- Low-cost and scalable for rural deployment  
- Designed with local context and constraints in mind  
- Supports improved maternal health awareness and clinic attendance  

---

## 🧠 Key Lessons

- Simplicity is often more effective than complex systems  
- Designing for real-world constraints is critical  
- Trust and community involvement matter as much as technology  
- Low-tech solutions can outperform high-tech systems in the right context  

---

- ## 🔗 Related Articles

These articles expand on the real-world insights and design decisions behind this system:

- [How I Built a Maternity Health SMS System in Rural Kenya and What It Taught Me About AI-Driven Care] (https://medium.com/@muthokatitus/how-i-built-a-maternity-health-sms-system-in-rural-kenya-and-what-it-taught-me-about-ai-driven-care-e843b93d367a)

- [Why Most Health Tech Projects Fail in Rural Africa (And What Actually Works Instead)] (https://medium.com/@muthokatitus/why-most-health-tech-projects-fail-in-rural-africa-and-what-actually-works-instead-028df3de9ebc)

---

## 🚧 Future Improvements

- AI-based personalization of SMS messages  
- Integration with health facility systems  
- Expansion to postpartum care messaging  
- Data analytics dashboard for health workers  
