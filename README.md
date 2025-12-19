# DataAI Pro - Business Website

> เว็บไซต์บริษัทจำหน่ายข้อมูลสำหรับ AI พร้อม CSS Styling

## 📁 โครงสร้างโปรเจค

```
my-business-web/
├── index.html        # หน้าแรก
├── about.html        # เกี่ยวกับเรา
├── services.html     # บริการ
├── contact.html      # ติดต่อเรา
├── css/
│   └── styles.css    # CSS Stylesheet
├── images/
│   ├── logo.png
│   └── team-*.jpg
└── README.md
```

## 🎨 CSS Features (Assignment #2)

### Selectors

- **Element Selectors**: `h1`, `p`, `a`, `table`
- **Class Selectors**: `.container`, `.hero`, `.card`
- **ID Selectors**: `#header`, `#footer`
- **Pseudo-classes**: `:hover`, `:focus`, `:first-child`, `:nth-child()`
- **Pseudo-elements**: `::first-line`, `::after`

### Units & Colors

- **rem/em** สำหรับ Typography
- **%** สำหรับ Responsive widths
- **vh** สำหรับ Hero section
- **HSL/RGBA** สำหรับ Shadows และ Colors

### Typography

- Custom font-family: Segoe UI, Tahoma
- Line-height และ Letter-spacing
- Font-weight variations

### Box Model

- Padding และ Margin ทั้งหมด
- Border-radius สำหรับมุมโค้ง
- Box-shadow สำหรับเงา

### Positioning

- **Sticky**: Header ติดบนสุด
- **Relative/Absolute**: สำหรับ overlays

### Layout Systems

- **Flexbox**: Navigation menu, Services cards
- **CSS Grid**: Team members section

## 📄 หน้าเว็บ

| หน้า            | คำอธิบาย                       |
| --------------- | ------------------------------ |
| `index.html`    | Hero section, 3 บริการหลัก     |
| `about.html`    | เรื่องราวบริษัท, ทีมงาน (Grid) |
| `services.html` | รายละเอียดบริการ, ตารางราคา    |
| `contact.html`  | Contact form, Google Maps      |

## ✅ Checklist

- [x] Semantic HTML (header, nav, section, article, figure, footer)
- [x] CSS Reset & Defaults
- [x] Typography styling
- [x] Component styles (buttons, cards, forms)
- [x] Flexbox layout
- [x] CSS Grid layout
- [x] Hover effects และ Transitions
- [x] Responsive design

## 🚀 วิธีใช้งาน

```bash
# Clone repository
git clone https://github.com/67160003-Chutiphon/my-business-webV2.git

# เปิดในเบราว์เซอร์
open index.html
```

## 👨‍💻 ผู้พัฒนา

นายชุติพนธ์ จิตต์รุ่งเรืองสุข

## 📝 License

MIT License
