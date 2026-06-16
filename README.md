# Data Retention System 💾

ระบบจัดการและสำรวจข้อมูลองค์กร เพื่อการจัดเก็บข้อมูลตามนโยบาย (Data Retention Policy) และกฎหมายคุ้มครองข้อมูลส่วนบุคคล (PDPA)

## 🚀 Tech Stack

### Frontend
- **HTML5 & CSS3**: โครงสร้างหลักของระบบ
- **Tailwind CSS**: ใช้สำหรับการทำ Styling และ Responsive Design (Mobile-First)
- **JavaScript (Vanilla ES6+)**: ควบคุม Logic การทำงาน, Dynamic DOM Manipulation และการจัดการ State
- **Chart.js**: แสดงผลสถิติและ ROI ในรูปแบบกราฟ Dashboard
- **Google Fonts (Prompt)**: ฟอนต์ภาษาไทยเพื่อความสวยงามและอ่านง่าย

### Backend & Database
- **Google Apps Script (GAS)**: ทำหน้าที่เป็น API Gateway รับ-ส่งข้อมูล (JSON) ระหว่างหน้าเว็บและฐานข้อมูล
- **Google Sheets**: ใช้เป็นฐานข้อมูล (Database) ในการจัดเก็บข้อมูลตารางสำรวจ

### API & Communication
- **Fetch API**: สื่อสารข้อมูลผ่าน HTTP POST (บันทึก/อัปเดต) และ GET (ดึงข้อมูลกลับมาแก้ไข)
- **JSON**: รูปแบบข้อมูลหลักในการรับ-ส่งระหว่าง Frontend และ Backend

---

## 🛠 Features
- **Dashboard**: แสดง ROI และนโยบายการจัดเก็บข้อมูลตามกฎหมาย
- **Master-Detail Form**: กรอกข้อมูลระบบครั้งเดียว และเพิ่มรายการตารางได้หลายรายการ (Dynamic Rows) พร้อม UI แบบแถวเดียว (Single-line)
- **Bulk CSV Upload**: รองรับการนำเข้าข้อมูลตารางจำนวนมากผ่านไฟล์ CSV พร้อมมี Template ให้ดาวน์โหลด
- **Wide UI Container**: ปรับปรุงหน้าจอแบบ Wide Screen (max-w-7xl) เพื่อรองรับการจัดการข้อมูลขนาดใหญ่
- **Unique Submit Code**: ระบบสร้างรหัสอ้างอิงอัตโนมัติสำหรับการบันทึกแต่ละครั้ง
- **Save & Recall**: สามารถนำรหัส Submit Code มาดึงข้อมูลเดิมกลับมาแก้ไขได้
- **Auto-Mapping**: คำนวณอายุการจัดเก็บและวิธีจัดการตามประเภทกฎหมายอัตโนมัติ
