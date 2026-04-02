# 🎬 ยอดไลฟ์สด ปี 2569

เว็บแอปบันทึกและวิเคราะห์ยอดขายไลฟ์สด รองรับ TikTok, Shopee และแพลตฟอร์มอื่นๆ

## ✨ ฟีเจอร์

- 📝 **บันทึกยอด** — กรอกยอดรายวัน แยกตามกะ (เช้า/ดึก) และผู้ไลฟ์
- 📊 **แดชบอร์ด** — สรุปยอดรวม กราฟรายวัน/เดือน สัดส่วนแพลตฟอร์ม
- 👤 **รายคน** — ดูสถิติแยกรายบุคคล เปรียบเทียบทีม
- 🏆 **วิเคราะห์เชิงลึก** — จัดอันดับเดี่ยว/คู่ เปรียบเทียบ Solo vs Pair
- 📋 **ประวัติ** — ดูและแก้ไขทุกรายการ
- ⚙️ **จัดการทีม** — เพิ่ม/ลบ/เปลี่ยนสถานะพนักงาน

## 🚀 วิธี Deploy บน GitHub Pages

### ขั้นตอนที่ 1 — สร้าง Repository

1. ไปที่ [github.com](https://github.com) แล้ว Login
2. กด **+ New repository**
3. ตั้งชื่อ repo เช่น `live2569` หรือ `live-tracker`
4. เลือก **Public**
5. กด **Create repository**

### ขั้นตอนที่ 2 — อัปโหลดไฟล์

**วิธีง่าย (ไม่ต้องใช้ Git):**
1. เปิด repo ที่เพิ่งสร้าง
2. กด **Add file** → **Upload files**
3. ลาก `index.html` ใส่
4. กด **Commit changes**

**วิธีใช้ Git:**
```bash
git init
git add index.html
git commit -m "🎬 ยอดไลฟ์สด 2569"
git branch -M main
git remote add origin https://github.com/USERNAME/live2569.git
git push -u origin main
```

### ขั้นตอนที่ 3 — เปิด GitHub Pages

1. ไปที่ **Settings** (ใน repo)
2. เลื่อนลงหา **Pages** ในเมนูซ้าย
3. ใต้ **Source** เลือก **Deploy from a branch**
4. Branch เลือก **main** / folder เลือก **/ (root)**
5. กด **Save**
6. รอสักครู่ แล้วเว็บจะพร้อมใช้ที่: `https://USERNAME.github.io/live2569/`

## 💾 ข้อมูล

ข้อมูลทั้งหมดเก็บใน **localStorage** ของเบราว์เซอร์นั้นๆ  
(ข้อมูลไม่ได้ sync ระหว่างอุปกรณ์ต่างกัน)

## 📱 รองรับ

- ✅ Desktop / Laptop
- ✅ มือถือ (Mobile Responsive)
- ✅ ทุก Browser สมัยใหม่
