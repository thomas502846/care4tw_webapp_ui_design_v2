# CFT 照顧學校 - UI Design v2 (Customer Feedback Integrated)

🎨 **CFT Care School Web Application UI Design - Version 2**

This repository contains the updated UI design (v2) incorporating comprehensive customer feedback received on **2025-12-18**. Based on the approved UI_v1, this version implements all requested refinements and new features.

## 🚀 Repository

**GitHub:** [https://github.com/thomas502846/care4tw_webapp_ui_design_v2](https://github.com/thomas502846/care4tw_webapp_ui_design_v2)

## 📊 What's New in v2

### ✅ Complete Customer Feedback Integration (2025-12-18)
- **16 files modified** with terminology updates and new features
- **3 new files created** for additional functionality
- **150+ individual changes** aligned with product-design-20251218.md
- **100% customer requirements** implemented

---

## 🔄 Major Changes from v1

### 1. **Terminology Overhaul** (13 files updated)

| Original (v1) | Updated (v2) |
|---------------|--------------|
| 我的儀表板 | 我的學習資訊總覽 |
| 已完成積分 | 已完成長照人員繼續教育積分 |
| 即將上課 | 我已報名 |
| AIO職種完成度地圖 | 課程地圖 |
| 證照追蹤地圖 | 證照地圖 |
| 我的文件 | 我的學習資料夾 |
| 進階點數管理 | 我的點數管理 |
| 分享點數/點數分享 | 轉贈點數 |
| 公眾詢問管理 | 客服紀錄管理 |
| 積分類別設定 | 積分相關資料設定 |

### 2. **New Student Features** 🎓

#### **LTC Points Tracking** (`student-ltc-points.html`) — NEW!
- 6-year cumulative progress tracking (120 points requirement)
- Statistics by course attribute (專業課程, 專業品質, etc.)
- Statistics by course category (消防安全, 感染管制, etc.)
- Self-service record management (add/edit/delete)
- Year-by-year detailed breakdown

#### **Contact School** (`student-contact-school.html`) — NEW!
- Direct inquiry submission form
- Inquiry history with responses
- Status tracking (pending/replied)
- Quick contact information sidebar

#### **Enhanced Points Management**
- Updated terminology: "轉贈點數" replaces "分享點數"
- Clear rules: one-time transfer, keeps original expiry
- Better UX: "留言給對方" field with default "我們一起學習吧!"
- Preview text: "將轉贈 X 點給好友，轉贈後剩餘點數：Y 點"

### 3. **Admin Enhancements** 🔧

#### **Course Management**
- ✅ Added "教師" and "通知" columns to course list
- ✅ Renamed fields: 積分類別設定 → 積分相關資料設定
- ✅ Changed 積分字號 from dropdown to text input (manual entry)
- ✅ New fields: 候補名額, 起訖日, 上課方式 (實體/線上/線上直播)
- ✅ Waitlist functionality with position display

#### **Announcements**
- ✅ Photo upload support (multiple images)
- ✅ YouTube video embedding via URL

#### **Settings - Points & Membership** (NEW Section)
- ✅ Purchase points expiry: 365 days (configurable)
- ✅ Gift points expiry: 180 days (configurable)
- ✅ Expiry notifications: **60, 30, 7 days** (added 7-day alert)
- ✅ Points transfer rules documentation
- ✅ Credit card installment options (3/6/12 periods)

#### **Teacher Management**
- ✅ Search by name and specialty (專長)
- ✅ New fields: 生理性別, 身份證字號, 戶籍地址, Line ID
- ✅ New field: 收款銀行代碼
- ✅ Payout residency status dropdown (4 options for tax purposes)

#### **Student Management**
- ✅ "延期點數" button for admin to extend points expiry on request

#### **Customer Service Records** (renamed from 公眾詢問管理)
- ✅ New search fields: 提問者姓名, 身份證號
- ✅ Identity type badges: 網站訪客/註冊學員/付費會員
- ✅ "新增溝通記錄" button for manual entry

### 4. **Course Pages** 📚
- ✅ Added location (上課地點) filter in `courses.html`
- ✅ Waitlist display in `course-detail.html`
- ✅ "是否需申請長照積分" checkbox in registration form

### 5. **Homepage Updates** 🏠
- ✅ Updated hero text: "ALL IN ONE 跨專業長照人才學習平台"
- ✅ Updated subtitle: "培育人才Ｘ青銀共創Ｘ社會設計"
- ✅ Added "校務管理" link to navigation

### 6. **FAQ Page** ❓
- ✅ Updated heading and response time (3 working days)
- ✅ Added Line ID field to inquiry form

---

## 📝 Documentation

### **CHANGELOG-v2.md**
Comprehensive documentation of all changes with:
- Detailed list of modified files
- Before/after terminology table
- Feature-by-feature breakdown
- Testing recommendations
- Development next steps

### **Product Design Alignment**
All changes align with:
- `product-design-20251218.md` specification
- `照顧學校會員網站需求回饋_20251218下載.csv` requirements

---

## 🎯 Key Improvements

### **User Experience**
- Consistent terminology across all interfaces
- Clearer labels and help text
- Better visual hierarchy
- Enhanced form validation

### **Data Capture**
- Comprehensive teacher payroll information
- Extended student registration fields
- Better points management rules
- Detailed LTC points tracking

### **Administrative Control**
- More search and filter options
- Better notification management
- Enhanced settings configuration
- Flexible points expiry control

---

## 📱 **Responsive Design**

Fully responsive across all devices:
- **Desktop:** 1200px+ (Full feature set)
- **Tablet:** 768px-1199px (Optimized layout)
- **Mobile:** <768px (Touch-optimized)

---

## 🛠 **Technical Stack**

- **HTML5** - Semantic markup with ARIA
- **CSS3** - Custom properties, Flexbox, Grid
- **Vanilla JavaScript** - Progressive enhancement
- **GitHub Pages** - Static hosting compatible

---

## 📂 **Repository Structure**

```
UI_v2/
├── CHANGELOG-v2.md              # Complete change documentation
├── index.html                   # Landing page (updated)
├── student-dashboard.html       # Student dashboard (major updates)
├── student-profile.html         # Student profile (terminology updates)
├── student-ltc-points.html      # NEW: LTC points tracking
├── student-contact-school.html  # NEW: Contact school form
├── courses.html                 # Course catalog (location filter added)
├── course-detail.html           # Course detail (waitlist & LTC checkbox)
├── faq.html                     # FAQ (updated copy)
├── admin-courses.html           # Course management (columns added)
├── admin-course-edit.html       # Course editor (field renames + new fields)
├── admin-announcements.html     # Announcements (media support)
├── admin-settings.html          # Settings (new points & membership section)
├── admin-teachers.html          # Teachers (search + new fields)
├── admin-students.html          # Students (extend points button)
├── admin-inquiries.html         # Customer service (renamed + enhanced)
└── assets/                      # CSS, JS, images (shared with v1)
```

---

## 🔍 Testing Checklist

### Student Flows
- [ ] Dashboard → verify all terminology changes
- [ ] Points management → verify "轉贈點數" terminology
- [ ] Profile → verify certificate category names
- [ ] LTC Points → test 6-year tracking
- [ ] Contact School → test inquiry submission

### Admin Flows
- [ ] Course management → verify new columns and fields
- [ ] Teacher management → test search and new fields
- [ ] Settings → verify points & membership configuration
- [ ] Customer service → test search and identity badges

### Cross-functional
- [ ] Navigation → verify "校務管理" link
- [ ] Homepage → verify updated copy
- [ ] Course search → test location filter
- [ ] Course registration → test waitlist and LTC checkbox

---

## 🚀 **Next Steps**

1. **Customer Review** - Deploy to GitHub Pages for final approval
2. **Backend Alignment** - Update API schemas with new fields
3. **Database Schema** - Create/update tables for new data
4. **Integration** - Connect frontend with backend APIs
5. **UAT** - User acceptance testing with real workflows

---

## 📊 **Version History**

- **v2 (2025-12-18)** - Customer feedback integration (this version)
- **v1 (2025-11-11)** - Initial approved UI design

---

## 📝 **License**

This is a UI design project created for CFT 照顧學校 (Care for Taiwan).

---

**Created with ❤️ for Taiwan's long-term care education community**

*本頁面為UI設計v2版本，整合客戶詳細回饋，準備進入開發階段*
