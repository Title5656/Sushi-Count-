# Sushi Count — Sushiro Plate Counter

เว็บแอปนับจำนวนจานซูชิโร่และประมาณยอดค่าอาหาร ใช้งานบนมือถือได้ทันที ไม่ต้องสมัครสมาชิก ไม่ต้องใช้ฐานข้อมูล และไม่มีโฆษณา

> โปรเจกต์ส่วนตัว ไม่ใช่แอปอย่างเป็นทางการของ Sushiro โปรดตรวจสอบราคาจริงและยอดในบิลของร้านเสมอ

## คุณสมบัติ

- เพิ่ม/ลดจำนวนจานตามสี แดง เงิน ทอง ดำ
- ปรับราคาจานได้ตามเมนูและโปรโมชัน
- แสดงจำนวนจาน ยอดรวม และเปรียบเทียบกับงบอาหารที่ตั้งไว้
- เพิ่มเมนูอื่น ย้อนกลับรายการ และเริ่มมื้อใหม่
- คัดลอกหรือแชร์สรุปค่าอาหาร
- เก็บข้อมูลเฉพาะใน `localStorage` ของเบราว์เซอร์บนอุปกรณ์ที่ใช้งาน

## วิธีเปิดใช้งาน

เปิดไฟล์ `index.html` ในเบราว์เซอร์ได้โดยตรง หรือใช้ GitHub Pages

### Deploy ฟรีด้วย GitHub Pages

1. สร้าง GitHub repository ใหม่ชื่อ `sushiro-plate-counter` และเลือก **Public** (จำเป็นสำหรับ GitHub Free)
2. อัปโหลด `index.html`, `.nojekyll` และ `README.md` ไปยัง branch `main` ที่ root
3. เปิด **Settings → Pages → Build and deployment → Source: Deploy from a branch**
4. เลือก **Branch: main**, **Folder: /(root)** และกด **Save**
5. เมื่อ GitHub Pages เปิดใช้งานแล้ว เข้าไปที่ `https://<USERNAME>.github.io/sushiro-plate-counter/`

**ไม่ต้องติดตั้ง Node.js, npm, framework, GitHub Actions workflow, backend, database หรือ domain แบบเสียเงิน**

## นโยบายค่าใช้จ่าย: $0

- ใช้เฉพาะ public repo และ GitHub Pages ของ GitHub Free
- ไม่มีบริการ third-party, paid API, ซื้อ domain, ไฟล์ใน cloud ที่คิดตามการใช้งาน หรือเครื่องมือ build ที่มีค่าใช้จ่าย
- ไม่มีการใช้ GitHub Actions แบบกำหนด workflow เอง หรือ runner ขนาดใหญ่
- ไม่เปิดใช้บริการที่คิดค่าใช้จ่ายเพิ่ม หาก GitHub เปลี่ยนนโยบายราคา ให้หยุดใช้งานก่อนยอมรับค่าใช้จ่ายใด ๆ
- GitHub Pages มีขีดจำกัดทรัพยากรและเงื่อนไขการใช้งานของ GitHub เช่น bandwidth soft limit; หากใช้งานหนักเกินอาจถูกจำกัดบริการแทนการให้บริการได้ไม่จำกัด
- หากต้องการป้องกันค่าใช้จ่ายจากฟีเจอร์อื่นในบัญชี GitHub ด้วย ให้ตรวจสอบ **Settings → Billing & Licensing → Budgets and alerts** และตั้งเพดานใช้จ่าย $0 พร้อมการหยุดใช้งานเมื่อถึงวงเงินสำหรับผลิตภัณฑ์ที่รองรับ

เอกสาร GitHub: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## สิทธิส่วนบุคคล

แอปไม่มี server และไม่ส่งข้อมูลการนับจานให้ผู้พัฒนา การกดแชร์/คัดลอกเป็นการกระทำโดยผู้ใช้เอง การล้างข้อมูลเว็บไซต์ในเบราว์เซอร์จะทำให้รายการที่บันทึกไว้หายไป
