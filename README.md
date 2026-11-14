# DONKEY BOSS PRO `v3.4.5` — Official Public OTA Releases

> **🟧 Shopee Affiliate (Orange) × ⬛ TikTok + Kalodata Pro (Black) + 🎬 Shared Google Flow Studio**  
> แยก 2 ระบบใหญ่ขาดจากกัน 100% ไม่พ่วงคลิปข้ามแอป: **🟧 ฝั่ง Shopee สีส้ม** และ **⬛ ฝั่ง TikTok × Kalodata Pro สีดำ** โดยใช้หน้า **🎬 Google Flow Studio** ร่วมกัน พร้อมไฟนับถอยหลัง 30 วินาทีขนาดใหญ่สะดุดตา

- **Latest Version:** `v3.4.5`
- **UI Engine:** `Direct3D11 WebView2 Hardware-Accelerated GPU Compositor (60–144+ FPS)`
- **Author:** *by cgame*
- **Installer Download:** [Download DONKEY_BOSS_Setup_v3.4.5.exe](https://github.com/gamemering/donkey-boss-releases/releases/latest)

---

## ⚡ ไฮไลต์อัปเดตใหม่ใน `v3.4.5`

1. **💬 ตัวเลือกใช้ห้องแชท Gemini เดิมต่อเนื่อง vs เปิดแชทใหม่สำหรับสินค้าถัดไป (`v3.4.5`)**:
   - เพิ่มช่องติ๊ก **`💬 ใช้ห้องแชท Gemini เดิมต่อเนื่องสำหรับสินค้าถัดไป`** แยกอิสระทั้งฝั่ง **🟧 Shopee Autopilot**, **⬛ TikTok × Kalodata Autopilot**, และ **🎬 Google Flow Studio (Part A)** (ค่าเริ่มต้นเปิดใช้งาน `ON`) ช่วยส่งสินค้าชิ้นถัดไปต่อในห้องแชทเดิมได้ทันทีโดยไม่สร้างห้องแชทใหม่รกแถบประวัติ พร้อมล้างไฟล์แนบค้างในกล่องพิมพ์และสั่ง Gemini แยกบริบทสินค้าใหม่ทุกเทิร์น
2. **🧹 แยกสวิตช์ลบโปรเจกต์ใน Google Flow ระหว่าง 🟧 Shopee และ ⬛ TikTok ขาดจากกัน 100% (`v3.4.5`)**:
   - แก้ไข `GoogleFlowAutomator` และ `AutopilotWorker` ให้อ่านค่าการลบโปรเจกต์ตามแพลตฟอร์มของงานนั้นๆ เท่านั้น (`cleanup_flow_project_enabled` สำหรับคิว Shopee และ `tiktok_autopilot_cleanup_flow_enabled` สำหรับคิว TikTok) การติ๊กลบในแท็บ Shopee จะไม่ไปลบโปรเจกต์ของคิว TikTok อีกต่อไป
3. **🧼 สกัดรูปสินค้าคลีน 3 มิติ & ระบบจำแนกสเกลสินค้าขนาดใหญ่สมจริง (`v3.4.4`)**:
   - ตัดแยกตัวสินค้าจริงจากป้ายโปรโมชั่นบนฉากสตูดิโอสีขาวคลีน (`800×800`) และบังคับให้สินค้าเฟอร์นิเจอร์/เครื่องใช้ไฟฟ้าขนาดใหญ่ยืนรีวิวข้างสินค้าจริงในห้อง ไม่ถือกล่องกระดาษ
4. **🛒 ปักตะกร้าเหลืองตรงด้วยลิงก์สินค้าไทย (`?region=TH&locale=th-TH`) + แยก 2 ระบบ 🟧 Shopee & ⬛ TikTok × Kalodata (`v3.4.3`)**:
   - คัดกรองเฉพาะสินค้า Open Affiliate จริง ปิดแผ่น `ตัวเลือกเพิ่มเติม` แม่นยำก่อนกด `โพสต์` และอัปเดตผ่านปุ่ม **🔄 อัปเดต (Online OTA)** พร้อมตรวจ SHA-256 ได้ในคลิกเดียว
