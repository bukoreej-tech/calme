# แคลอรี่ของฉัน (PWA)

แอปติดตามแคลอรี่ สารอาหาร และน้ำ ทำงานในเบราว์เซอร์ ติดตั้งลงหน้าจอโฮมได้ ไม่ต้องมีเซิร์ฟเวอร์

## ขึ้น GitHub Pages
1. สร้าง repo ใหม่ (Public) แล้วอัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ (Add file > Upload files)
2. Settings > Pages > Source: Deploy from a branch > Branch: main / (root) > Save
3. รอ 1-2 นาที จะได้ลิงก์ `https://<ชื่อผู้ใช้>.github.io/<ชื่อ repo>/`

## ติดตั้งเป็นแอป
- Android (Chrome): เมนู ⋮ > ติดตั้งแอป / Add to Home screen
- iPhone (Safari): ปุ่มแชร์ > Add to Home Screen

## ข้อควรรู้
- ข้อมูลเก็บใน localStorage ของเครื่องนั้น ไม่ซิงค์ข้ามเครื่อง และหายถ้าล้างข้อมูลเบราว์เซอร์
- ปุ่ม AI ใช้ได้เฉพาะเวอร์ชันบน claude.ai เวอร์ชันนี้จะซ่อน AI ส่วนอื่นใช้ได้ปกติ
- ถ้าแก้ไฟล์แล้วหน้าไม่อัปเดต ให้เปลี่ยน `cal-v1` ใน sw.js เป็น `cal-v2`
