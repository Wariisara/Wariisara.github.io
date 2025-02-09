# Security Requirement

---

## V5.4 Memory , String and Unmanaged Code ⌨️

---

### 5.4.2 Verify that format strings do not take potentially hostile input, and are  constant.

### ChatGPT  
- ความปลอดภัยของข้อมูล และ การป้องกันช่องโหว่ในโปรแกรม โดยเฉพาะช่องโหว่ที่เกี่ยวกับ Format String Vulnerability เช่น ใช้ %s, %x, %d  โดยไม่ควบคุมหรือกรองอินพุตที่ป้อนเข้ามา ส่งผลให้สามารถเข้าถึงหรือแก้ไขหน่วยความจำที่ไม่ควรเข้าถึงได้้

### Gemini  
- การรักษาความปลอดภัยในการเขียนโปรแกรม โดยเฉพาะอย่างยิ่งเมื่อใช้ฟังก์ชันที่เกี่ยวข้องกับการจัดรูปแบบข้อความ หรือ Format String ซึ่งช่องโหว่ของ  Format String เกิดขึ้นเมื่อโปรแกรมรับข้อมูลจากผู้ใช้ เช่น input มาใช้เป็นส่วนหนึ่งของ Format String โดยตรง ทำให้ผู้ใช้สามารถแทรกคำสั่งหรือข้อมูลที่เป็นอันตรายเข้าไปใน Format String ได้

---

### My Summary
- เป็นการตรวจสอบความปลอดภัยของข้อมูล ที่มีช่องโหว่ที่เป็นการจัดรูปแบบข้อความ หรือ  Format String ซึ่งช่องโหว่นั้นเกิดขึ้นจากการรับ input จากผู้ใช้มา ซึ่งอาจทำให้เกิดการทำงานที่ผิดพลาดได้ ถ้าไม่ได้ทำการ Format String ไว้

---
- [go to page >](https://wariisara.github.io/security-requirement) 6530250468 - Warisara Yamma
- [go to page >]() 6530250603 - Suphattra Prasomsap