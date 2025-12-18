# UI_v2 Changelog — Customer Feedback Integration (2025-12-18)

This document tracks changes from UI_v1 to UI_v2 based on customer feedback received through 2025-12-18.

## Completed Updates

### 1. Student Dashboard (`student-dashboard.html`) ✅
- **Page title:** "我的儀表板" → "我的學習資訊總覽"
- **Meta description:** Updated to reflect new terminology
- **KPI section changes:**
  - Removed: "🚨 點數偏低，建議補充"
  - Removed: "已超過基本要求"
  - Changed: "已完成積分" → "已完成長照人員繼續教育積分"
  - Removed: "長照專業認證"
  - Removed: "繼續加油！"
- **Section renames:**
  - "即將上課" → "我已報名"
  - "AIO職種完成度地圖" → "課程地圖"
  - "證照追蹤地圖" → "證照地圖"
  - "進階點數管理" → "我的點數管理"
  - "我的文件" → "我的學習資料夾"
- **Points sharing/gift terminology updates:**
  - "分享點數" / "點數分享與轉贈" → "轉贈點數"
  - "附言" → "留言給對方" (default text: "我們一起學習吧!")
  - "確認分享" → "確認轉贈點數"
  - "產生分享連結" → "複製轉贈連結"
  - Preview text: "將轉贈 X 點給好友，轉贈後剩餘點數：Y 點"
  - Help text: "點數只能贈送給已註冊的學員帳號"
- **JavaScript updates:** Preview function updated to use new terminology

### 2. Student Profile (`student-profile.html`) ✅
- **Meta description:** "管理您的..." → "管理我的..."
- **Section renames:**
  - "AIO職種設定與學習路徑" → "AIO職種與學習路徑簡介"
  - "主要AIO職種 *" → "選擇我的AIO職種"
  - "目標證照管理與設定" → "學習目標設定與管理"
- **Removed section:** Entire "次要興趣領域" block removed
- **Certificate category renames:**
  - Tabs: "AIO認證" → "AIO證照", "政府認證" → "政府證照", "專業認證" → "民間證照"
  - Headers updated accordingly
  - Certificate names: "專業認證" → "民間證照"

### 3. FAQ Page (`faq.html`) ✅
- **Heading:** "還有其他問題嗎？" → "以上找不到您要的答案？歡迎直接留下您的基本資料及疑問，我們將盡快回覆您"
- **SLA copy:** "1-2 個工作日" → "3個工作日" (2 occurrences)
- **New field:** Added Line ID input field to inquiry form

### 4. Admin Inquiries (`admin-inquiries.html`) ✅
- **Page title:** "公眾詢問管理" → "客服紀錄管理"
- **Meta description:** "管理來自官網詢問表單的問題與回覆" → "網站訪客、註冊學員、付費會員提問與客服回覆紀錄管理"
- **New search fields:** Added "提問者姓名" and "身份證號" search inputs
- **New button:** "➕ 新增溝通記錄" button added
- **New display field:** Added identity type badge (網站訪客/註冊學員/付費會員) to inquiry items

---

## Completed Updates (Continued)

### 5. Course Pages (`courses.html`, `course-detail.html`) ✅
**Changes completed:**
- ✅ Added location (上課地點) to search filters in `courses.html`
- ✅ Added waitlist (候補名額) display in course registration card
- ✅ Added "是否需申請長照積分" checkbox in registration form for points courses

### 6. Admin Courses (`admin-courses.html`, `admin-course-edit.html`) ✅
**Changes completed:**
- ✅ Added "教師" and "通知" columns to course list table
- ✅ Updated course row to show teacher name and notification status badge
- ✅ Renamed all course edit fields as specified
- ✅ Changed "積分字號" from dropdown to text input for manual entry
- ✅ Added "起訖日" field for points validity date range
- ✅ Added "上課方式" dropdown (實體/線上/線上直播)
- ✅ Added "候補名額" field with help text

### 7. Admin Announcements (`admin-announcements.html`) ✅
**Changes completed:**
- ✅ Added announcement photo upload field (multiple images)
- ✅ Added announcement video link field for YouTube embedding

### 8. Admin Settings (`admin-settings.html`) ✅
**Changes completed:**
- ✅ Added new "點數與會員設定" section
- ✅ Purchase points expiry: 365 days (configurable)
- ✅ Gift points expiry: 180 days (configurable)
- ✅ Expiry notifications: 60, 30, **7** days (all three checkboxes)
- ✅ Added points transfer rules explanation (one-time, keeps original expiry)
- ✅ Added installment payment options (3/6/12 periods)

### 9. Admin Teachers (`admin-teachers.html`) ✅
**Changes completed:**
- ✅ Added search section with name and specialty (專長) filters
- ✅ Added new fields to teacher form:
  - 生理性別 (dropdown)
  - 身份證字號
  - 戶籍地址
  - Line ID
  - 收款銀行代碼
  - 領款人基本資料 (dropdown with 4 residency options)

### 10. Admin Students (`admin-students.html`) ✅
**Changes completed:**
- ✅ Added "延期點數" button in student action buttons

### 11. Homepage (`index.html`) ✅
**Changes completed:**
- ✅ Updated hero section copy: "ALL IN ONE 跨專業長照人才學習平台" + "培育人才Ｘ青銀共創Ｘ社會設計"
- ✅ Added "校務管理" link to navigation menu

### 12. New Screens ✅
**New files created:**
- ✅ `student-ltc-points.html` — Complete LTC points tracking interface with 6-year summary, year tabs, attribute/category statistics, and course details table
- ✅ `student-contact-school.html` — Contact form for students to submit inquiries and view inquiry history with responses

---

## Key Terminology Reference

| Original (UI_v1) | Updated (UI_v2) |
|------------------|-----------------|
| 我的儀表板 | 我的學習資訊總覽 |
| 已完成積分 | 已完成長照人員繼續教育積分 |
| 即將上課 | 我已報名 |
| AIO職種完成度地圖 | 課程地圖 |
| 證照追蹤地圖 | 證照地圖 |
| 我的文件 | 我的學習資料夾 |
| 進階點數管理 | 我的點數管理 |
| 分享點數 / 點數分享與轉贈 | 轉贈點數 |
| 附言 | 留言給對方 |
| 確認分享 | 確認轉贈點數 |
| 產生分享連結 | 複製轉贈連結 |
| 公眾詢問管理 | 客服紀錄管理 |
| AIO職種設定與學習路徑 | AIO職種與學習路徑簡介 |
| 主要AIO職種 | 選擇我的AIO職種 |
| 目標證照管理與設定 | 學習目標設定與管理 |
| AIO認證 | AIO證照 |
| 政府認證 | 政府證照 |
| 專業認證 | 民間證照 |
| 積分類別設定 | 積分相關資料設定 |
| 積分類別 | 積分屬性 |
| 積分等級 | 積分類別 |
| 認證機構 | 積分字號 |

---

## Progress Summary

- **Completed:** 12/12 major sections ✅
- **Status:** 100% complete
- **All customer feedback from 2025-12-18 has been integrated**

---

## Summary of All Changes

### Files Modified: 11
1. `student-dashboard.html` — Major terminology overhaul, points sharing renamed
2. `student-profile.html` — Record center updates, certificate categories renamed
3. `courses.html` — Added location filter
4. `course-detail.html` — Added LTC points checkbox and waitlist display
5. `faq.html` — Updated copy, SLA, added Line ID
6. `admin-inquiries.html` — Renamed to customer service records, added search fields
7. `admin-courses.html` — Added columns, field renames
8. `admin-course-edit.html` — Field renames, new fields added
9. `admin-announcements.html` — Media upload fields
10. `admin-settings.html` — New points & membership configuration section
11. `admin-teachers.html` — Search functionality, extensive new fields
12. `admin-students.html` — Extend points button
13. `index.html` — Updated hero copy, added 校務管理 link

### Files Created: 3
1. `student-ltc-points.html` — Complete LTC points tracking system
2. `student-contact-school.html` — Student inquiry system
3. `CHANGELOG-v2.md` — This file

### Key Improvements
- **Comprehensive terminology alignment** across all student-facing pages
- **Enhanced data capture** for teachers (payroll information)
- **Robust points management** with clear expiry rules and extension capability
- **New student self-service** features (LTC points tracking, contact school)
- **Improved admin workflows** with search, filters, and new data fields
- **Clear product alignment** with 2025-12-18 customer feedback

---

## Testing Recommendations

1. **Student flows:** Dashboard → Profile → Points → Contact School → LTC Points
2. **Course flows:** Browse → Filter by location → Register → Waitlist → LTC points checkbox
3. **Admin flows:** Course management → Teacher management → Student management → Settings
4. **Terminology:** Verify all renamed terms display correctly across all pages
5. **New features:** Test waitlist, extend points, LTC tracking, contact school forms

---

## Next Steps for Development

1. Review UI_v2 with customer for final approval
2. Backend API alignment with new data fields
3. Database schema updates for new fields
4. Integration testing with real data
5. User acceptance testing (UAT)

