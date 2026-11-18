# เว็บไซต์หลักสำหรับ มูดวงดูดวง (MooDuang DuDuang)

## ไฟล์
- `index.html` หน้าเว็บไซต์หลัก
- `terms-of-service.html` ข้อกำหนดการใช้งาน
- Privacy Policy ใช้หน้าเดิม: https://sftraktorfs.github.io/privacy-policy/

## วิธีเผยแพร่ที่แนะนำ
1. สร้าง GitHub repository ใหม่ชื่อ **SFtraktorFS.github.io** (ชื่อบัญชีต้องตรงกับเจ้าของ Pages)
2. อัปโหลด `index.html` และ `terms-of-service.html` ไว้ที่ root ของ repository
3. ไปที่ Settings → Pages
4. เลือก Deploy from a branch → Branch `main` → Folder `/ (root)` → Save
5. รอ GitHub Pages เผยแพร่ แล้วตรวจสอบ:
   - https://sftraktorfs.github.io/
   - https://sftraktorfs.github.io/terms-of-service.html
   - https://sftraktorfs.github.io/privacy-policy/

## ก่อนใช้งานจริง
- แก้ `[กรอกอีเมลสำหรับติดต่อผู้พัฒนา]` ใน `index.html` และ `terms-of-service.html` เป็นอีเมลที่ติดต่อได้จริง
- ตรวจสอบว่าข้อความแนะนำแอปตรงกับฟังก์ชันจริง
- ตรวจสอบ Privacy Policy ว่าตรงกับข้อมูลที่แอปเก็บ ใช้ แชร์ และระยะเวลาเก็บรักษาจริง
- หากมี URL หน้า Google Play แล้ว สามารถเพิ่มปุ่มดาวน์โหลดได้

## ค่าที่นำไปกรอกใน Google OAuth Branding
- Application home page: `https://sftraktorfs.github.io/`
- Application privacy policy link: `https://sftraktorfs.github.io/privacy-policy/`
- Application terms of service link: `https://sftraktorfs.github.io/terms-of-service.html`
- Authorized domain: `sftraktorfs.github.io`

หมายเหตุ: การใส่ URL ในหน้า Branding ไม่ได้ยืนยันโดเมนให้อัตโนมัติ ต้องทำการยืนยันโดเมนตามขั้นตอนที่ Google แสดงใน Authorized domains / Google Search Console ด้วย
