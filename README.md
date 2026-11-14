# DONKEY BOSS PRO `v3.4.2` — Official Public OTA Releases

> **🟧 Shopee Affiliate (Orange) × ⬛ TikTok + Kalodata Pro (Black) + 🎬 Shared Google Flow Studio**  
> แยก 2 ระบบใหญ่ขาดจากกัน 100% ไม่พ่วงคลิปข้ามแอป: **🟧 ฝั่ง Shopee สีส้ม** และ **⬛ ฝั่ง TikTok × Kalodata Pro สีดำ** โดยใช้หน้า **🎬 Google Flow Studio** ร่วมกัน พร้อมไฟนับถอยหลัง 30 วินาทีขนาดใหญ่สะดุดตา

- **Latest Version:** `v3.4.2`
- **UI Engine:** `Direct3D11 WebView2 Hardware-Accelerated GPU Compositor (60–144+ FPS)`
- **Author:** *by cgame*
- **Installer Download:** [Download DONKEY_BOSS_Setup_v3.4.2.exe](https://github.com/gamemering/donkey-boss-releases/releases/latest)

---

## ⚡ ไฮไลต์อัปเดตใหม่ใน `v3.4.2`

1. **🖼️ ดึงรูปปกสินค้าจาก Kalodata CDN (`img.kalocdn.com`) สำเร็จ 100% + ซ่อมแซมคิวเก่าอัตโนมัติ (`v3.4.2`)**:
   - รองรับการสกัดรูปปกจากทั้ง XHR, CSS `background-image` และการสังเคราะห์ URL มาตรฐาน `tiktok.product/{id}/cover.png` พร้อมส่ง Header `Referer: https://www.kalodata.com/` และ `no-referrer` บน WebUI แก้อาการ `Missing thumbnail URL` และ `HTTP 403` ได้ทั้งโหมดทดลองดูตัวอย่างและแพ็กเกจสมาชิก
   - ป้องกันการทำงานวนซ้ำไม่รู้จบ (Infinite Scout Loop): เมื่อดึงสินค้าตัวอย่างครบโควตาหรือติดหน้าล็อกอิน/สมาชิก ระบบจะสลับเข้าสถานะพักชั่วคราว (`AUTH NEEDED` / `NO NEW ITEMS`) พร้อมข้อความแจ้งเตือนภาษาไทยชัดเจนทันที
2. **🟧 ฝั่ง Shopee (ธีมสีส้ม) & ⬛ ฝั่ง TikTok × Kalodata (ธีมสีดำ) แยกอิสระ 100%**:
   - ตัดการส่งคลิปต่อเข้า TikTok หลังโพสต์ Shopee เสร็จ — งานฝั่งไหนโพสต์ลงเฉพาะแอปนั้นอย่างสะอาดชัดเจน
   - มีโหมด **Autopilot เต็มรูปแบบแยกทั้ง 2 ฝั่ง** พร้อมไฟนับถอยหลังเตรียมพร้อม 30 วินาทีขนาดใหญ่สะดุดตา (`⏭️ ข้ามเวลารอทันที`)
3. **📊 Kalodata Thailand Product Explorer ครบทุกตัวกรอง Pro (`kalodata.com/explore` & `/product`)**:
   - กรองช่วงเวลา (เมื่อวาน / 7 / 14 / 30 วัน), หมวดหมู่ TikTok Shop TH + หมุนเวียนอัตโนมัติ, รายได้ GMV (฿), ยอดขาย, อัตราเติบโต GMV (%), ช่วงราคา, เฉพาะสินค้ามีค่าคอม Affiliate, ค่าคอมขั้นต่ำ (%), สัดส่วนยอดขายจากคลิปสั้น (%), จำนวนครีเอเตอร์ และอายุสินค้า
   - ส่งต่อภาพปก + ชื่อสินค้าเข้า Google Flow แล้วปักตะกร้าเหลือง TikTok ตรงจากข้อมูล Kalodata ทันที (ไม่มี OCR ซ้ำซ้อน)
4. **🎬 Shared Google Flow Studio & Dual-Layer SHA-256 Online OTA**: กดปุ่ม **🔄 อัปเดต** ในโปรแกรมเพื่อรับเวอร์ชันใหม่ได้ในคลิกเดียว
