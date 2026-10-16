<div align="center">

# 🚀 Mini Project #2: Web Application with Database

[![Node.js](https://img.shields.io/badge/Node.js-v18+-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-v4.x-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![SQLite](https://img.shields.io/badge/SQLite-v3.x-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![HTML5](https://img.shields.io/badge/HTML5-Modern_UI-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)

เว็บแอปพลิเคชันขนาดเล็กสำหรับจัดการรายการข้อมูล (Item Management System) มีการเชื่อมต่อระหว่าง Frontend และ Backend พร้อมจัดเก็บข้อมูลลงในฐานข้อมูล SQLite

</div>

---

## 🔗 ลิงก์ที่เกี่ยวข้อง (Quick Links)

- 🌐 **หน้าเว็บไคลเอนต์ (Client Application):** [เปิดใช้งาน index.html](./public/index.html)
- 📸 **ภาพ Debug ฝั่ง Server:** [ดูภาพ debug-server.png](./public/debug-server.png)
- 📸 **ภาพ Debug ฝั่ง Client:** [ดูภาพ debug-client.png](./public/debug-client.png)

---

## 📌 ภาพรวมโครงการ (Overview)

โปรเจกต์นี้จัดทำขึ้นเพื่อสาธิตการทำงานร่วมกันระหว่าง **Frontend (HTML/CSS/JS)** และ **Backend (Node.js & Express)** โดยมีระบบ CRUD ช่วยในการจัดการข้อมูลรายการสิ่งของอย่างครบถ้วน และเก็บบันทึกข้อมูลอย่างถาวรไว้ในฐานข้อมูล **SQLite**

### ✨ คุณสมบัติเด่น (Features)
- ➕ **เพิ่มรายการใหม่:** สามารถบันทึกข้อมูลเข้าสู่ฐานข้อมูล SQLite ได้ทันที
- 📜 **ดึงรายการทั้งหมด:** แสดงผลรายการข้อมูลที่จัดเก็บอยู่ในระบบแบบ Real-time
- 🗑️ **ลบรายการ:** จัดการลบข้อมูลตาม ID ที่เลือกได้อย่างแม่นยำ
- 🎨 **Modern UI:** หน้าตาเว็บดีไซน์ทันสมัย สวยงาม และใช้งานง่าย

---

## 📁 โครงสร้างโปรเจกต์ (Project Structure)

```text
mini-project-2/
├── 📂 public/              # HTML, CSS และ JavaScript สำหรับหน้าเว็บไคลเอนต์
│   ├── index.html          # หน้าเว็บหลัก
│   ├── debug-client.png    # ภาพหลักฐานการ Debug ฝั่ง Client
│   └── debug-server.png    # ภาพหลักฐานการ Debug ฝั่ง Server
├── 📂 server/              # Node.js + Express API และฐานข้อมูล SQLite
│   ├── index.js            # Express Web Server
│   ├── database.sqlite     # ไฟล์ฐานข้อมูล
│   └── package.json        # Dependencies
└── README.md               # เอกสารอธิบายโปรเจกต์


⚙️ วิธีติดตั้งและเรียกใช้งาน (Setup & Run)
1. ฝั่ง Server (Backend)
เปิด Terminal แล้วรันคำสั่ง

Bash
cd server
npm install
npm run dev