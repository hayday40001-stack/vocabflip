# VocabFlip Plus

เปิดใช้งาน:
1. อย่าเปิด index.html แบบ file:// หากต้องการโหลด data/vocab.json
2. เปิดโฟลเดอร์นี้ด้วย local server เช่น:
   python -m http.server 8000
3. เปิด http://localhost:8000

สิ่งที่เพิ่ม:
- 8 หมวดหมู่
- คำอ่านภาษาไทย
- Emoji/ภาพช่วยจำ
- เสียงอ่านผ่าน Web Speech API
- ค้นหา + กรอง CEFR
- UI สีสันใหม่
- ระบบ Spaced Repetition และ localStorage
- แยกฐานศัพท์เป็น data/vocab.json

หมายเหตุ:
ไฟล์ vocab.json ที่ให้มาเป็น starter dataset ที่คัดตัวอย่างไว้ 160 คำ เพื่อให้โปรเจกต์พร้อมรันและขยายได้ทันที
โครงสร้างรองรับ 8,000+ คำโดยเพิ่ม object ใน data/vocab.json ได้โดยไม่ต้องแก้หน้าเว็บ
