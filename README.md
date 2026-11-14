# DONKEY BOSS PRO `v3.4.3` — Official Public OTA Releases

> **🟧 Shopee Affiliate (Orange) × ⬛ TikTok + Kalodata Pro (Black) + 🎬 Shared Google Flow Studio**  
> แยก 2 ระบบใหญ่ขาดจากกัน 100% ไม่พ่วงคลิปข้ามแอป: **🟧 ฝั่ง Shopee สีส้ม** และ **⬛ ฝั่ง TikTok × Kalodata Pro สีดำ** โดยใช้หน้า **🎬 Google Flow Studio** ร่วมกัน พร้อมไฟนับถอยหลัง 30 วินาทีขนาดใหญ่สะดุดตา

- **Latest Version:** `v3.4.3`
- **UI Engine:** `Direct3D11 WebView2 Hardware-Accelerated GPU Compositor (60–144+ FPS)`
- **Author:** *by cgame*
- **Installer Download:** [Download DONKEY_BOSS_Setup_v3.4.3.exe](https://github.com/gamemering/donkey-boss-releases/releases/latest)

---

## ⚡ ไฮไลต์อัปเดตใหม่ใน `v3.4.3`

1. **🛒 ปักตะกร้าเหลืองตรงเป๊ะด้วยลิงก์สินค้าไทย (`?region=TH&locale=th-TH`) + คัดกรองเฉพาะสินค้า Open Affiliate จริง (`v3.4.3`)**:
   - ดึงและประกอบลิงก์ปักตะกร้าตรงตามปุ่ม `TikTok Product Link` ของ Kalodata ประเทศไทย และตัดสินค้า `[ตะกร้าบริษัท]` / สินค้าที่ร้านไม่เปิดค่าคอมนายหน้า (`commission_rate: '-'` หรือ `0%`) ออกตั้งแต่วินาทีแรก
   - บังคับเข้าหน้า **ตลาดสินค้า (`Product Marketplace`)** ก่อนวางลิงก์/รหัสสินค้า 19 หลักเสมอ (ไม่ติดค้างอยู่ในหน้าโชว์เคสตัวเอง) และ **ยกเลิกการค้นด้วยชื่อสินค้าแล้วสุ่มหยิบชิ้นแรก** 100% ไม่มีการเผลอปักเคส/อะไหล่ผิดชิ้นอีกต่อไป
2. **🎯 แก้บั๊กกดสวิตช์ 'อนุญาตให้แสดงความคิดเห็น' ย้ำไปมา & กดปุ่ม 'โพสต์' ทะลุแผ่นบังหน้าจอ (`v3.4.3`)**:
   - แยกแยะปุ่ม `Switch` / `CheckBox` ออกจากปุ่มกากบาทปิดหน้าต่าง (`×`) 100% พร้อมระบบกด `Back` ปิดแผ่น `ตัวเลือกเพิ่มเติม` อัตโนมัติทันทีหากปุ่ม `×` ไม่ตอบสนอง แล้วตรวจยืนยันว่าหน้าจอโล่งก่อนกดปุ่ม `โพสต์` จริง
3. **🖼️ ดึงรูปปกสินค้าจาก Kalodata CDN (`img.kalocdn.com`) สำเร็จ 100% + ป้องกันการวนลูปหาสินค้าซ้ำ (`v3.4.2`)**:
   - รองรับการสกัดรูปปกจากทั้ง XHR, CSS `background-image` และการสังเคราะห์ URL มาตรฐาน `tiktok.product/{id}/cover.png` พร้อมส่ง Header `Referer: https://www.kalodata.com/`
4. **🟧 ฝั่ง Shopee (ธีมสีส้ม) & ⬛ ฝั่ง TikTok × Kalodata (ธีมสีดำ) แยกอิสระ 100% + Online OTA คลิกเดียว**:
   - กดปุ่ม **🔄 อัปเดต** ในโปรแกรมเพื่อรับเวอร์ชันใหม่พร้อมตรวจ SHA-256 อัตโนมัติได้ทันที
