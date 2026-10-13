# 🌤️ สภาพอากาศ

แอปดูอากาศ ฝุ่น PM2.5 อุณหภูมิ และแผนที่ลมแบบเรียลไทม์ พร้อมระบบแจ้งเตือนผ่าน LINE เฉพาะตอนผิดปกติ

## ไฟล์ใน repo นี้
| ไฟล์ | หน้าที่ |
|---|---|
| `index.html` | ตัวแอป (เปิดผ่าน GitHub Pages) |
| `richmenu.png` | รูปเมนูใน LINE OA (สคริปต์ดึงไปใช้ตอนรัน `setupRichMenu`) |
| `apps-script/weather-alert.gs` | สำเนาโค้ดระบบแจ้งเตือน **ต้องคัดลอกไปวางใน Google Apps Script เอง** |
| `SETUP.md` | วิธีติดตั้งทีละขั้น |

## ข้อมูลจาก
Open-Meteo, Windy, Air4Thai (กรมควบคุมมลพิษ), WAQI, NASA FIRMS, USGS, GloFAS, กรมอุตุนิยมวิทยา

> ค่าที่เป็นความลับ (LINE token, key ต่างๆ) เก็บใน Script properties ของ Apps Script เท่านั้น ห้ามใส่ในไฟล์ใน repo นี้
