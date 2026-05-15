# 🌻 พรรคความหวังใหม่ — New Aspiration Party Platform

ระบบดิจิทัลครบวงจรสำหรับพรรคการเมือง พัฒนาด้วย HTML5, CSS3, Vanilla JS  
พร้อม Design System สีเขียว `#0B7A33` และเหลือง `#FFF04F` ตามอัตลักษณ์พรรค

---

## 📁 โครงสร้างโปรเจกต์

```
new-aspiration-party-platform/
├── website/
│   ├── index.html       # 🌐 เว็บไซต์หลัก (Public Website)
│   ├── admin.html       # 🛠️ Admin Dashboard (ระบบหลังบ้าน)
│   └── app.html         # 📱 Mobile PWA App
├── entities/            # 📦 Database Entity Schemas (JSON)
│   ├── PartySettings.json
│   ├── Member.json
│   ├── Donation.json
│   ├── News.json
│   ├── Policy.json
│   ├── Event.json
│   ├── EventRegistration.json
│   ├── Volunteer.json
│   ├── Banner.json
│   ├── MembershipPlan.json
│   ├── ContactMessage.json
│   └── MediaFile.json
└── README.md
```

---

## 🌐 Public Website (`index.html`)

เว็บไซต์สาธารณะสำหรับประชาชนทั่วไป

**Features:**
- ✅ Hero Section พร้อมภาพดอกทานตะวัน AI Generated
- ✅ นโยบายพรรค 6 ด้าน
- ✅ ข่าวสารและกิจกรรม
- ✅ ระบบสมัครสมาชิก (รายปี ฿200 / ตลอดชีพ ฿2,000)
- ✅ ระบบบริจาคสนับสนุน (PromptPay + โอนธนาคาร)
- ✅ สมัครอาสาสมัคร
- ✅ แบบฟอร์มติดต่อ
- ✅ **Mobile-first Responsive** — Hamburger Menu + Bottom Navigation
- ✅ Fade-up animations on scroll

---

## 🛠️ Admin Dashboard (`admin.html`)

ระบบจัดการหลังบ้านสำหรับเจ้าหน้าที่พรรค

**Login:**
- Email: `admin@newaspirationparty.or.th`
- Password: `Admin@2026`

**หน้าที่มี:**
| หน้า | ฟีเจอร์ |
|------|---------|
| Dashboard | Stats Cards, Bar Chart, Donut Chart, Activity Log |
| สมาชิก | ตาราง, อนุมัติ/ปฏิเสธ, เพิ่มสมาชิก, Export |
| การบริจาค | ตรวจสอบสลิป, อนุมัติ, ออกใบเสร็จ |
| ข่าวสาร | CRUD ข่าว, เผยแพร่/แบบร่าง |
| นโยบาย | จัดการนโยบายพรรค |
| กิจกรรม | สร้างและจัดการกิจกรรม |
| Media Manager | อัปโหลดและจัดการสื่อ |
| ตั้งค่าพรรค | ข้อมูลพรรค, Social Media, บัญชีธนาคาร |
| ข้อความติดต่อ | ตอบกลับประชาชน |
| Activity Log | ประวัติการทำงานของ Admin |

---

## 📱 Mobile PWA App (`app.html`)

แอปพลิเคชันมือถือสำหรับสมาชิกพรรค

**Features:**
- ✅ Splash Screen พร้อม Animation
- ✅ Bottom Navigation 5 ปุ่ม
- ✅ บัตรสมาชิก Digital (Gradient Card + QR Code)
- ✅ ระบบบริจาค PromptPay
- ✅ ข่าวสาร + กรอง Category
- ✅ กิจกรรม + ลงทะเบียน
- ✅ **Dark Mode** toggle
- ✅ Quick Actions Grid
- ✅ สถิติพรรค Scrollable Strip

---

## 🗄️ Database Entities

| Entity | คำอธิบาย |
|--------|----------|
| `PartySettings` | ข้อมูลหลักพรรค, สี, Social, บัญชีธนาคาร |
| `Member` | ข้อมูลสมาชิกทั้งหมด |
| `Donation` | รายการบริจาคและสถานะ |
| `News` | ข่าวสารและบทความ (TH/EN) |
| `Policy` | นโยบายพรรค (TH/EN) |
| `Event` | กิจกรรมและงานอีเวนต์ |
| `EventRegistration` | การลงทะเบียนกิจกรรม + QR Check-in |
| `Volunteer` | อาสาสมัครพรรค |
| `Banner` | แบนเนอร์โฆษณาและสื่อ |
| `MembershipPlan` | แผนสมาชิก (รายปี/ตลอดชีพ) |
| `ContactMessage` | ข้อความติดต่อจากประชาชน |
| `MediaFile` | ไฟล์และสื่อต่างๆ |

---

## 🎨 Design System

| Token | Value |
|-------|-------|
| Primary Color | `#0B7A33` (เขียวพรรค) |
| Secondary Color | `#FFF04F` (เหลืองทานตะวัน) |
| Accent | `#F5C400` |
| Dark | `#1A1A1A` |
| Font TH | Kanit, Sarabun |
| Font EN | Poppins |

---

## 🚀 Responsive Breakpoints

| Breakpoint | Layout |
|-----------|--------|
| Desktop (1024px+) | Full layout, multi-column |
| Tablet (768–1024px) | 2-column grids |
| Mobile (≤768px) | Single column, Hamburger menu, Bottom Nav |
| Small (≤375px) | Compact, 1-column everything |

---

## 📝 License

© 2569 พรรคความหวังใหม่ (New Aspiration Party)  
สงวนลิขสิทธิ์ทุกประการ
