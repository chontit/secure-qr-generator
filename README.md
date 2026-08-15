<div align="center">

# 🔒 Secure QR Generator

**เครื่องมือสร้างและสแกน QR Code ระดับโปร — ปรับแต่งอิสระ ทำงานในเบราว์เซอร์ 100% ไม่ส่งข้อมูลออกเซิร์ฟเวอร์**

[![version](https://img.shields.io/badge/version-1.0.0-0ea5e9.svg)](https://github.com/chontit/secure-qr-generator/releases)
[![license](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![made with](https://img.shields.io/badge/HTML5-single%20file-e34f26.svg)](index.html)

### 🌐 เปิดใช้งานได้ที่: **https://chontit.github.io/secure-qr-generator/**

</div>

---

## ✨ ฟีเจอร์หลัก

### สร้าง QR Code
- **หลายรูปแบบข้อมูล** — URL / ข้อความ, vCard (นามบัตร), Wi-Fi, Email, และพิกัดแผนที่ (เลือกจุดบนแผนที่ได้)
- **ปรับแต่งดีไซน์อิสระ** — รูปร่างจุด/กรอบตา/จุดตา, สี QR และพื้นหลัง, พื้นหลังโปร่งใส, ระยะขอบ
- **ใส่โลโก้ตรงกลาง** — อัปโหลดรูป ปรับขนาด/ช่องว่าง และแปลงเป็นขาวดำได้
- **ดาวน์โหลด** — PNG (512 – 8192 px) และ SVG (เวกเตอร์)
- **รองรับภาษาไทย/Unicode** — เข้ารหัสแบบ UTF-8 อ่านออกทั้ง iOS และ Android

### สแกน QR Code 🆕
- **เลือกได้ทั้งกล้องและไฟล์รูป** — คลิกเมนูสแกนแล้วเลือกวิธีเอง ระบบจะเริ่มทำงานหลังเลือกเท่านั้น
- **อ่านโค้ดสไตล์ตกแต่งได้** — มี image preprocessing (grayscale + blur/threshold) อ่านโค้ดจุดวงกลม/สีต่าง ๆ ที่เครื่องอ่านทั่วไปอ่านไม่ออก
- **รองรับกล้องหลังอัตโนมัติ** บนมือถือ พร้อมสลับกล้องได้

### อื่น ๆ
- 🌙 โหมดสว่าง/มืด
- 🕒 ประวัติการสร้าง (เก็บในเครื่อง)
- 📱 รองรับทั้งมือถือและคอมพิวเตอร์ — บน iOS ดาวน์โหลดผ่าน Share Sheet (บันทึกลงรูปภาพ/ไฟล์)

---

## 🚀 วิธีใช้งาน

**แบบออนไลน์ (แนะนำ):** เปิด https://chontit.github.io/secure-qr-generator/ ได้เลย

**แบบเปิดไฟล์ในเครื่อง:** ดาวน์โหลด `index.html` แล้วดับเบิลคลิกเปิดในเบราว์เซอร์

> ⚠️ **หมายเหตุเรื่องกล้อง:** ฟีเจอร์เปิดกล้องสแกนต้องรันบน **HTTPS หรือ localhost** เท่านั้น (ข้อกำหนดความปลอดภัยของเบราว์เซอร์) — เปิดผ่าน GitHub Pages ใช้ได้เต็มระบบ ส่วนการเปิดไฟล์ตรง ๆ แบบ `file://` จะสแกนได้เฉพาะ "เลือกไฟล์รูป"

---

## 🛠️ เทคโนโลยี

โปรเจกต์นี้เป็น **ไฟล์ HTML เดียวจบ** ไม่ต้อง build ไม่ต้องติดตั้งอะไร ใช้ไลบรารีผ่าน CDN:

| ไลบรารี | หน้าที่ |
|---|---|
| [qr-code-styling](https://github.com/kozakdenys/qr-code-styling) | สร้าง QR แบบปรับแต่งได้ |
| [html5-qrcode](https://github.com/mebjas/html5-qrcode) | สแกนผ่านกล้อง |
| [jsQR](https://github.com/cozmo/jsQR) | ถอดรหัส QR จากไฟล์รูป |
| [Leaflet](https://leafletjs.com/) | แผนที่สำหรับพิกัด Geo |

---

## 📁 โครงสร้างไฟล์

```
secure-qr-generator/
├── index.html      # ตัวแอปทั้งหมด (single-file)
├── README.md       # ไฟล์นี้
├── CHANGELOG.md    # ประวัติเวอร์ชัน
└── LICENSE         # สัญญาอนุญาต MIT
```

---

## 📌 เวอร์ชัน

**v1.0.0** — ดูรายละเอียดที่ [CHANGELOG.md](CHANGELOG.md) หรือหน้า [Releases](https://github.com/chontit/secure-qr-generator/releases)

## 📄 License

เผยแพร่ภายใต้สัญญาอนุญาต [MIT](LICENSE) — นำไปใช้/แก้ไข/แจกจ่ายได้อิสระ

---

<div align="center">
สร้างโดย <a href="https://github.com/chontit">@chontit</a> · 🔒 ข้อมูลของคุณไม่ถูกส่งออกจากเบราว์เซอร์
</div>
