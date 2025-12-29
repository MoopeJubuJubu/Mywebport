# วิธีอัปภาพไปยัง repo (ง่าย) — ภาษาไทย

ต้องการให้รูปของคุณแสดงในไฟล์ `index.html` ข้างต้น ให้ทำตามขั้นตอนนี้:

1) อัปภาพผ่านหน้าเว็บ GitHub
- ไปที่: https://github.com/MoopeJubuJubu/Mywebport
- คลิกปุ่ม `Add file` -> `Upload files` -> เลือกไฟล์ภาพของคุณ (แนะนำชื่อไฟล์: `me.jpg` หรือ `profile.jpg`)
- ใส่ข้อความ commit (เช่น `Add profile photo`) แล้วกด `Commit changes` (เลือกสาขา `main` ถ้ามี)

2) ตรวจสอบไฟล์และเส้นทาง
- ให้แน่ใจว่าภาพถูกวางไว้ที่ `images/me.jpg` (ถ้าไฟล์ชื่ออื่น ให้เปลี่ยน `index.html` หรือเปลี่ยนชื่อไฟล์ให้ตรง)

3) เปิด GitHub Pages (ถ้าต้องการเว็บ URL สาธารณะ)
- ไปที่ Settings -> Pages ของ repository
- เลือก Branch: `main` และ Folder: `/ (root)` หรือ `/docs` ขึ้นกับที่เก็บไฟล์ แล้วกด `Save`
- รอไม่กี่นาที จะได้ URL ประมาณ: `https://MoopeJubuJubu.github.io/Mywebport/`
- รูปจะเข้าถึงได้ที่: `https://MoopeJubuJubu.github.io/Mywebport/images/me.jpg`

4) ใช้ CDN (ไม่ต้องเปิด Pages)
- คุณสามารถใช้ลิงก์ตรงของ jsDelivr เพื่อแสดงรูปได้โดยตรง:
  `https://cdn.jsdelivr.net/gh/MoopeJubuJubu/Mywebport@main/images/me.jpg`

เคล็ดลับ:
- ย่อภาพก่อนอัปให้ขนาดไม่เกิน ~1 MB เพื่อให้เว็บโหลดเร็ว
- ตั้งชื่อไฟล์เป็นตัวพิมพ์เล็กและไม่มีช่องว่าง เช่น `me.jpg` หรือ `profile-photo.jpg`

ถ้าคุณต้องการ ผมสามารถ:
- สร้างไฟล์เหล่านี้ให้เรียบร้อยใน repo (ผมกำลังทำให้) หรือ
- ถ้าต้องการให้อัปภาพของคุณให้แทน placeholder ให้แนบไฟล์ภาพที่นี่ หรือตั้งชื่อไฟล์และผมจะอัปให้ถ้าคุณให้เนื้อหา (base64) หรือไฟล์แนบ
