# 🚗 AI Vision Gate

> **Smart Village Access Control System — Powered by AI**  
> ระบบควบคุมทางเข้า-ออกหมู่บ้านอัจฉริยะ ขับเคลื่อนด้วย AI

---

## 🌟 About This Project / เกี่ยวกับโปรเจคนี้

**EN:**  
At 44 years old, after losing my job, I decided to start building something meaningful.  
This is one of my very first projects as I begin learning app development — built from scratch, self-taught, step by step.  
It may not be perfect, but it is built with heart and with the sincere hope that it will genuinely help communities across Thailand.

**TH:**  
ตอนอายุ 44 ปี หลังจากตกงาน ผมตัดสินใจลุกขึ้นมาสร้างบางอย่างที่มีคุณค่า  
นี่คือหนึ่งในโปรเจคแรกๆ ในช่วงที่ผมเริ่มหัดทำแอป — สร้างขึ้นจากศูนย์ เรียนรู้ด้วยตัวเองทีละขั้นตอน  
อาจยังไม่สมบูรณ์แบบ แต่สร้างด้วยใจ และด้วยความหวังว่ามันจะเป็นประโยชน์กับทุกคนครับ 🙏

---

## 🎯 What It Does / ระบบทำอะไรได้

| Feature | EN | TH |
|---------|----|----|
| 📷 | AI reads license plates automatically | AI อ่านทะเบียนรถอัตโนมัติ |
| 🪪 | Scans visitor national ID cards | สแกนบัตรประชาชนผู้มาติดต่อ |
| 🔔 | Notifies residents via mobile app | แจ้งเตือนลูกบ้านผ่านแอป |
| 🚧 | Controls barrier gate via ESP32 WiFi | ควบคุมไม้กั้นผ่าน ESP32 WiFi |
| ✅ | Resident approves/rejects entry & exit | ลูกบ้านอนุญาต/ปฏิเสธ เข้า-ออก |
| 📋 | Logs all visits to Google Sheets | บันทึกทุกการเข้า-ออกใน Google Sheets |

---

## 🛠️ Tech Stack

```
📱 Mobile Camera (Android)  →  Gemini Vision AI
🧠 Google Gemini API        →  License Plate + ID Card OCR
⚡ ESP32 + Relay Module     →  Barrier Gate Control
📊 Google Sheets            →  Database & Logging
🔥 Firebase                 →  Push Notifications (Phase 2)
🌐 GitHub Pages             →  Free Hosting (HTTPS)
```

---

## 🚀 How to Use / วิธีใช้งาน

**1. Open the Web App / เปิดแอป**
```
https://inno-home.github.io/ai-vision-gate/
```

**2. Configure Settings / ตั้งค่าระบบ**
- Gemini API Key → get from [aistudio.google.com](https://aistudio.google.com)
- ESP32 IP Address → check Serial Monitor after flashing
- Apps Script URL → deploy from Google Sheets

**3. Point camera at vehicle / ชี้กล้องไปที่รถ**
- Tap 📸 to scan plate / กดสแกนทะเบียน
- Tap 🪪 to scan ID card / กดสแกนบัตร ปชช.
- System handles the rest! / ระบบจัดการให้อัตโนมัติ

---

## 📦 Hardware Required / อุปกรณ์ที่ต้องใช้

| Item | Price (THB) |
|------|-------------|
| ESP32 Development Board | ~150 ฿ |
| Relay Module 5V | ~50 ฿ |
| Magnetic Switch | ~100 ฿ |
| Old Android Phone (Camera) | Free / มีอยู่แล้ว |
| Phone Mount + Weatherproof Box | ~300 ฿ |
| **Total / รวม** | **~600-750 ฿** |

---

## 📁 Project Structure / โครงสร้างไฟล์

```
ai-vision-gate/
├── index.html                  # Web App (Camera + AI + UI)
├── ESP32_Gate_Controller.ino   # ESP32 Arduino Code
├── Apps_Script_Gate.gs         # Google Apps Script Backend
└── README.md                   # This file
```

---

## 🗺️ Roadmap

- [x] **Phase 1** — Web App MVP (Current / ปัจจุบัน)
- [ ] **Phase 2** — Flutter Mobile App (iOS + Android)
- [ ] **Phase 3** — Multi-village Enterprise System

---

## 👨‍💻 Developer / ผู้พัฒนา

**TaBon (Thapanat Baisaeng)**  
- 🏭 Background: Factory Manager, Industrial Automation
- 📍 Location: Khon Kaen, Thailand
- 🚀 Organization: [InnoHome](https://github.com/inno-home)
- 📧 Contact: thapanat.bon@gmail.com

> *"Started learning app development at 44, after job loss.*  
> *This is one of my first projects — still learning, still growing.*  
> *Built with hope — for every village, every family, every guard.*  
> *เริ่มหัดทำแอปตอนอายุ 44 หลังจากตกงาน*  
> *นี่คือโปรเจคในช่วงแรกของผม — ยังเรียนรู้อยู่ ยังเติบโตอยู่*  
> *สร้างด้วยความหวัง — เพื่อทุกหมู่บ้าน ทุกครอบครัว ทุกคน"* 🙏

---

## 🙏 Acknowledgements / ขอบคุณ

**EN:**  
This project would not have been possible without the incredible support of:

- **[Anthropic](https://anthropic.com)** — for creating Claude AI, my coding companion and teacher throughout this entire journey. Every line of code, every idea, every problem solved — Claude was there helping me every step of the way.
- **[GitHub](https://github.com)** — for providing free hosting and tools that make it possible for anyone, anywhere, to share their work with the world.

**TH:**  
โปรเจคนี้จะเกิดขึ้นไม่ได้เลย หากปราศจากความช่วยเหลืออันยอดเยี่ยมจาก:

- **[Anthropic](https://anthropic.com)** — ขอบคุณที่สร้าง Claude AI ซึ่งเป็นทั้งผู้ช่วยและครูของผมตลอดเส้นทางนี้ ทุกบรรทัดโค้ด ทุกไอเดีย ทุกปัญหาที่แก้ได้ — Claude อยู่เคียงข้างผมทุกขั้นตอนครับ
- **[GitHub](https://github.com)** — ขอบคุณที่ให้บริการ Hosting ฟรี และเครื่องมือที่เปิดโอกาสให้ทุกคน ไม่ว่าจะอยู่ที่ไหน สามารถแบ่งปันผลงานของตัวเองกับโลกได้ครับ

---

## 📄 License

MIT License — Free to use, modify, and share / ใช้ได้ฟรี แก้ไขและแบ่งปันได้

---

⭐ **If this helps you, please give it a star!**  
⭐ **ถ้าเป็นประโยชน์ กด Star ให้ด้วยนะครับ ขอบคุณครับ 🙏**
