# Motion Amplifier (PWA)

ขยายการเคลื่อนไหวเล็กๆ จากกล้องมือถือแบบเรียลไทม์ ใช้อัลกอริทึม Riesz pyramid phase-based
(เขียนใหม่เป็น JavaScript จากโปรเจกต์ [elapt1c/motion-amplification](https://github.com/elapt1c/motion-amplification))

## ใช้งาน
เปิดหน้าเว็บ → กด "เปิดกล้อง" → วางมือถือให้นิ่ง → ปรับความแรงและช่วงความถี่

ติดตั้งเป็นแอป: Android (Chrome) เมนู ⋮ > ติดตั้งแอป / iPhone (Safari) แชร์ > เพิ่มที่หน้าจอโฮม

## โฮสต์บน GitHub Pages
Settings > Pages > Source: Deploy from a branch > Branch: main, โฟลเดอร์ / (root)

ทุกพาธในโปรเจกต์เป็นแบบ relative จึงใช้ได้ทั้งที่ `username.github.io/repo-name/` และโดเมนของตัวเอง

## ไฟล์
- `index.html` แอปทั้งหมด (ไฟล์เดียว)
- `manifest.webmanifest`, `sw.js`, `icons/` ส่วนของ PWA

หมายเหตุ: ถ้าแก้ `index.html` ให้เปลี่ยนเลขเวอร์ชัน `CACHE` ใน `sw.js` ด้วย เพื่อให้เครื่องที่ติดตั้งไว้อัปเดต
