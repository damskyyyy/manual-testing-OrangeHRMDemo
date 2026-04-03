# 📘 Manual Testing Portfolio | Portofolio Pengujian Manual

**Application**: OrangeHRM Open Source Demo  
**URL**: https://opensource-demo.orangehrmlive.com/web/index.php/auth/login  
**Credentials**: `Admin` / `admin123`  
**Last Updated**: 2026-04-03  

---

## 📂 Repository Structure | Struktur Repositori
| Folder | Purpose | Tujuan |
|--------|---------|--------|
| `test-plans/` | Test strategy & scope documents | Dokumen strategi & lingkup uji |
| `test-cases/` | Detailed test cases (positive & negative) | Kasus uji rinci (positif & negatif) |
| `bug-reports/` | Bug tracking templates | Template pelacakan bug |
| `test-summary/` | Execution reports & coverage | Laporan eksekusi & cakupan |
| `assets/screenshots/` | Screenshots & evidence | Screenshot & bukti |

---

## 🧪 Test Case Overview | Ringkasan Kasus Uji
### 🎯 Current Focus | Fokus Saat Ini
- TC001: Login System Validation
- TC002: New Employee Registration
- TC003: Leave Application Processing
- TC004: User Profile Update
- TC005: Recruitment Vacancy Management

### ⚙️ Technical Validation | Validasi Teknis
- TC006: Directory Search Negative
- TC007: Social Media Integration Failure
- TC008: Attendance Tracking Errors
- TC009: Performance Metrics
- TC010: Recruitment Negative
- TC011: PIM Run Report
- TC012: MyInfo Update Details

---

## 📊 Test Execution Summary | Ringkasan Eksekusi
| Metric | Count | |
|--------|-------|---|
| 🟢 Successful | [Number] | |
| 🔴 Failed | [Number] | |
| ⚠️ Pending | [Number] | |
| 📈 Coverage | [Percentage] | |

---

## 📄 Sample Test Case | Contoh Kasus Uji
### 🇮🇩 Version Indonesia - TC007
**Judul**: Kegagalan Membuat Post di Buzz
1. **Deskripsi**: Validasi fitur penulisan post di platform media sosial
2. **Langkah-langkah**:
   1. Login sebagai user biasa
   2. Klik tombol "Buzz"
   3. Isi konten dengan format tidak valid (mis. HTML tags)
3. **Hasil yang Diharapkan**: Sistem menampilkan pesan error, post tidak tersimpan

### 🇺🇸 English Version - TC007
**Title**: Buzz Post Creation Failure
1. **Description**: Validate social media post creation feature
2. **Steps**:
   1. Login as regular user
   2. Click "Buzz" button
   3. Enter invalid content format (e.g., HTML tags)
3. **Expected Result**: Error message displayed, post not saved

---

## 🛠️ File Structure Navigation | Navigasi Struktur File
```
orangehrm-test-portfolio/
├── test-plans/
│   └── orangehrm-test-plan.md
├── test-cases/
│   └── orangehrm/
│       ├── TC001-login.md
│       ├── TC002-add-employee.md
│       ├── ...
│       └── TC012-myinfo-update-details.md
├── bug-reports/
│   └── (coming soon)
├── test-summary/
│   └── orangehrm-test-summary.md
└── assets/
    └── screenshots/
```

---

## 🎨 Documentation Features | Fitur Dokumentasi
- **Icons**: Visual navigation using emojis
- **Dynamic**: Placeholders for auto-generated metrics
- **Links**: Direct links to each test case file
- **Status Indicators**: Real-time test status tracking

---

> *Dibuat dengan kemampuan dokumentasi teknikal yang matplotlib*  
> *Crafted with technical documentation skills*