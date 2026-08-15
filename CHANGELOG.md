# Changelog

รูปแบบอ้างอิงตาม [Keep a Changelog](https://keepachangelog.com/) และใช้ [Semantic Versioning](https://semver.org/lang/th/)

## [1.0.0] - 2026-08-15

🎉 เวอร์ชันเปิดตัวแรก (First stable release)

### เพิ่มใหม่ (Added)
- **สร้าง QR Code** 5 รูปแบบ: URL/ข้อความ, vCard, Wi-Fi, Email, พิกัดแผนที่ (Geo)
- **ปรับแต่งดีไซน์**: รูปร่างจุด/กรอบตา/จุดตา, สี, พื้นหลังโปร่งใส, ระยะขอบ
- **ใส่โลโก้** ตรงกลาง ปรับขนาด/ช่องว่าง และแปลงขาวดำ
- **ดาวน์โหลด** PNG (512–8192 px) และ SVG
- **สแกน QR Code** เลือกได้ทั้งกล้องและไฟล์รูป — ทำงานหลังผู้ใช้เลือกวิธีเท่านั้น
- **Image preprocessing** (grayscale + blur/threshold) อ่าน QR สไตล์ตกแต่ง เช่น จุดวงกลม/สีต่าง ๆ ได้
- **กล้องหลังอัตโนมัติ** บนมือถือ + สลับกล้องได้
- **โหมดสว่าง/มืด**, ประวัติการสร้าง, รองรับภาษาไทย/Unicode (UTF-8)
- **Favicon + apple-touch-icon** ครบชุด และ PWA manifest

### รายละเอียดเชิงเทคนิค
- รองรับดาวน์โหลดบน **iOS ผ่าน Share Sheet** (แก้ปัญหา iOS Safari ไม่รองรับ blob download)
- เปิดกล้องด้วย `facingMode` พร้อม fallback หลายชั้น (แก้ปัญหา `cameraIdOrConfig is required`)
- เป็นไฟล์ HTML เดียวจบ ไม่ต้อง build

[1.0.0]: https://github.com/chontit/secure-qr-generator/releases/tag/v1.0.0
