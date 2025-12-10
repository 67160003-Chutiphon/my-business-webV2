# DataAI Pro - บริษัทจำหน่ายข้อมูลสำหรับ AI

## คำอธิบายโปรเจค

เว็บไซต์สำหรับบริษัท DataAI Pro ที่ให้บริการข้อมูลคุณภาพสูงสำหรับการพัฒนาและฝึกฝน AI Models รวมถึงข้อมูลภาษาไทย ข้อมูลภาพและวิดีโอ และข้อมูลเสียง

## โครงสร้างไฟล์

```
my-business-web/
├── index.html          # หน้าแรก
├── about.html          # หน้าเกี่ยวกับบริษัท
├── services.html       # หน้าบริการ
├── contact.html        # หน้าติดต่อ
├── images/             # โฟลเดอร์เก็บรูปภาพ
│   ├── logo.png
│   ├── team-member-1.jpg
│   ├── team-member-2.jpg
│   └── team-member-3.jpg
└── README.md           # เอกสารนี้
```

## รูปหน้าจอ

### หน้าแรก (index.html)

- มี Header พร้อม logo และชื่อบริษัท
- Navigation menu เชื่อมโยงไปยังทุกหน้า
- Hero section ต้อนรับผู้เข้าชม
- แสดง 3 บริการหลักของบริษัท
- Footer พร้อมข้อมูลติดต่อ

### หน้าเกี่ยวกับ (about.html)

- เรื่องราวของบริษัท
- ทีมงาน 3 คน (ใช้ figure element)
- วิสัยทัศน์และพันธกิจ
- ลิงก์กลับหน้าแรก

### หน้าบริการ (services.html)

- รายละเอียดบริการทั้ง 4 ประเภท
- แต่ละบริการอยู่ใน section แยกกัน
- ตารางเปรียบเทียบแพ็กเกจ (Basic, Professional, Enterprise)

### หน้าติดต่อ (contact.html)

- Contact form พร้อม validation
- ที่อยู่บริษัท (ใช้ address element)
- แผนที่ Google Maps embed

## ลิงก์เข้าหน้าต่างๆ

- [หน้าแรก](index.html)
- [เกี่ยวกับเรา](about.html)
- [บริการ](services.html)
- [ติดต่อเรา](contact.html)

## Features

- ✅ ใช้ Semantic HTML (header, nav, section, article, figure, footer)
- ✅ มี meta tags และ DOCTYPE ครบถ้วน
- ✅ Form มี validation (required, email, tel pattern)
- ✅ รูปภาพทุกรูปมี alt text
- ✅ Navigation menu ทำงานถูกต้องทุกหน้า
- ✅ Code มี comments

## วิธีการใช้งาน

1. Clone repository นี้
2. เปิดไฟล์ index.html ด้วย web browser
3. สำรวจหน้าต่างๆ ผ่าน navigation menu

## หมายเหตุ

- โปรเจคนี้เป็น HTML พื้นฐาน ยังไม่มี CSS styling
- รูปภาพใน folder images/ ต้องเตรียมเอง
- Google Maps URL ในหน้า contact.html เป็นตัวอย่าง ควรเปลี่ยนเป็นที่อยู่จริง

## ผู้พัฒนา

นิสิต นายชุติพนธ์ จิตต์รุ่งเรืองสุข

## License

MIT License
