# Thai Wah PMS Hub

หน้าแนะนำระบบประเมินผลงาน (PMS) และการประเมินทดลองงาน สำหรับฝังใน SharePoint ผ่าน Embed Web Part

## ขึ้น GitHub Pages
1. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ (index.html, robots.txt, images/) ไปที่ Repository
2. Settings > Pages > Branch: main, โฟลเดอร์ / (root) > Save
3. รอ 1-2 นาที จะได้ลิงก์ https://<บัญชี>.github.io/<ชื่อ repo>/

## ใส่ลิงก์ PDF และ Workday
แก้ส่วน `window.PMS_LINKS` ด้านบนของ index.html แล้ว Commit
ช่องที่เว้นว่าง ปุ่มนั้นจะถูกซ่อนอัตโนมัติ

## ฝังใน SharePoint
1. Site Settings > HTML Field Security > เพิ่มโดเมน <บัญชี>.github.io
2. เพิ่ม Embed Web Part (Section แบบ Full-width) แล้ววางลิงก์จาก GitHub Pages
3. ใส่ People Web Part รายชื่อ HRBP ไว้ใต้กรอบ Embed
