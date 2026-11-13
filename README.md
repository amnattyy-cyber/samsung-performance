# Samsung Performance Dashboard

[เปิด Dashboard](https://amnattyy-cyber.github.io/samsung-performance/) · [ตรวจสถานะเผยแพร่](https://github.com/amnattyy-cyber/samsung-performance/actions) · [ดาวน์โหลด index.html ล่าสุด](https://raw.githubusercontent.com/amnattyy-cyber/samsung-performance/main/index.html)

## อัปเดตยอดขายและสต็อกรายวัน

1. ใช้ `index.html` ล่าสุดจาก branch `main` เป็นต้นฉบับ เพื่อเก็บหน้ารายงานและรูปในเมนู Campaign ครบถ้วน
2. สร้าง `index.html` ฉบับอัปเดตด้วยยอดจาก **Data Refresh SS**, **TSM Manual** และสต็อก Samsung ล่าสุด ใช้ TSM Manual สำหรับวันที่ Data Refresh SS ยังมาไม่ถึง เมื่อ Refresh ครอบคลุมวันนั้นแล้ว ให้แทนยอด Manual ของวันเดียวกันเพื่อป้องกันยอดซ้ำ
3. เปิด [หน้าอัปโหลดไฟล์](https://github.com/amnattyy-cyber/samsung-performance/upload/main) แล้วอัปโหลด `index.html` ไว้ที่หน้าแรกของ branch `main` กด **Commit changes** ใช้ชื่อ commit เช่น `Update Samsung sales and stock 2026-11-13`
4. เปิด [Actions](https://github.com/amnattyy-cyber/samsung-performance/actions) รอให้ **pages build and deployment** ของ commit ล่าสุดขึ้นสีเขียว แล้วเปิด Dashboard ตรวจวันที่ **Sales as of** และ **Stock as of** ให้ตรงกับแหล่งข้อมูล

GitHub Pages เผยแพร่จาก `main` หลัง commit สำเร็จ ขั้นตอนนี้ใช้ไฟล์ `index.html` ที่ฝังข้อมูลพร้อมแสดงผลแล้ว การอัปโหลด Excel อย่างเดียวจะไม่อัปเดต Dashboard และ repo นี้เป็นสาธารณะ จึงควรอัปโหลดเฉพาะไฟล์ Dashboard ที่พร้อมเผยแพร่
