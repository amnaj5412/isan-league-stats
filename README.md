# สถิติฟุตบอลไทยลีก

หน้าเว็บสถิติ ไทยลีก 3 โซนอีสาน และ ไทยลีก 2 (ไฟล์เดียว: `index.html`)

## วิธีขึ้น GitHub Pages

1. สร้าง repository ใหม่บน GitHub (เช่น `thai-league-stats`) แบบ Public
2. กด **Add file → Upload files** แล้วลากไฟล์ `index.html`, `README.md`, `.nojekyll` ขึ้นไป แล้วกด Commit
3. ไปที่ **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / `(root)` → Save
4. รอ 1–2 นาที เว็บจะอยู่ที่ `https://<ชื่อผู้ใช้>.github.io/thai-league-stats/`

## ข้อมูล

- เมื่อเปิดบน GitHub Pages หน้าเว็บจะพยายามดึงข้อมูลล่าสุดจาก API ของไทยลีกโดยตรง
- ถ้าดึงไม่ได้ จะใช้ข้อมูลชุดที่ฝังไว้ในไฟล์ (snapshot) แทน

ข้อมูลจาก thaileague.co.th · เว็บไซต์ส่วนตัว ไม่ใช่เว็บไซต์ทางการของไทยลีก
