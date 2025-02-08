# Admin Dashboard

Admin Dashboard เป็นหน้าเว็บสำหรับการจัดการระบบ (Admin Dashboard) ที่ออกแบบมาให้มีความสวยงามและตอบสนองต่ออุปกรณ์หลากหลาย โดยใช้เทคโนโลยีหลัก ๆ ดังนี้:

- **HTML5** สำหรับโครงสร้างหน้าเว็บ
- **Tailwind CSS** สำหรับจัดการสไตล์และการออกแบบที่ตอบสนอง (responsive design)
- **Font Awesome** สำหรับไอคอนที่สวยงามและใช้งานง่าย
- **JavaScript** สำหรับการจัดการข้อมูลแบบไดนามิก เช่น การแสดงตารางรายการคำสั่งซื้อ (Recent Orders)

## ตัวอย่างหน้าจอ
![Admin Dashboard Screenshot](https://img2.pic.in.th/pic/screencapture.png)

## คุณสมบัติหลัก

- **Responsive Layout:** 
  - หน้าเว็บออกแบบให้รองรับการแสดงผลบนอุปกรณ์ทั้งเดสก์ท็อปและมือถือ
  - มี sidebar ที่สามารถเปิด/ปิดได้บนอุปกรณ์มือถือ

- **UI/UX ที่ทันสมัย:**
  - ใช้ hover effects และ transitions ที่ช่วยให้การใช้งานดูมีชีวิตชีวามากขึ้น
  - มีการแสดงผลการเปลี่ยนแปลงเมื่อโต้ตอบกับผู้ใช้

- **Data Presentation:**
  - มีส่วนแสดงผล "Dashboard Overview" พร้อม card สรุปยอดผู้ใช้งาน, รายได้ และคำสั่งซื้อ
  - ตาราง "Recent Orders" ที่แสดงรายการคำสั่งซื้อ พร้อมการเปลี่ยนสีของสถานะ (Completed, Pending, Canceled) โดยอาศัย JavaScript ในการ populate ข้อมูล

- **Accessibility และ Semantic Markup:**
  - ใช้แท็ก HTML5 ที่เหมาะสม เช่น `<header>`, `<nav>`, `<main>`, และ `<section>`
  - มีการเพิ่ม `aria-label` และ `aria-labelledby` เพื่อช่วยให้ผู้ใช้ที่ใช้ screen reader เข้าถึงเนื้อหาได้ง่ายขึ้น

## เทคโนโลยีที่ใช้

- HTML5
- Tailwind CSS
- Font Awesome
- JavaScript

## วิธีเริ่มต้นใช้งาน

### Prerequisites
- เว็บบราวเซอร์ที่ทันสมัย (เช่น Chrome, Firefox, Edge ฯลฯ)

### การติดตั้งและรันโปรเจ็กต์

1. **Clone repository:**
   ```bash
   git clone https://github.com/yourusername/admin-dashboard.git
   ```
