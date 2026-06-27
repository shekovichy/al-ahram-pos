# VOODO ERP — نظام نقاط البيع وإدارة المخزون

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-green?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)
![PWA](https://img.shields.io/badge/PWA-ready-purple?style=for-the-badge)
![Firebase](https://img.shields.io/badge/Firebase-realtime-orange?style=for-the-badge)

**A full-featured, multi-branch ERP & Point of Sale system — built as a single HTML file.**  
No installation. No server. Works offline. Deploy in 60 seconds.

[🚀 Live Demo](https://voodo-erp.vercel.app) · [🐛 Report Bug](https://github.com/shekovichy/al-ahram-pos/issues)

</div>

---

## ✨ Why VOODO ERP?

Most ERP systems require expensive servers, complex setup, and weeks of training. VOODO ERP is a **single HTML file** that runs anywhere — tablet, laptop, or phone — with zero installation. Yet it packs features that rival enterprise systems costing tens of thousands of dollars.

> 🔗 **Live Demo:** https://voodo-erp.vercel.app  
> 🔑 **Login:** `admin` / `admin1234`

---

## 🚀 Features

### 🛒 Point of Sale
- Fast cashier interface optimized for retail
- Barcode scanning support
- Multiple payment methods (cash, card, mixed)
- Invoice suspend & resume (park sales)
- Manager discount with PIN authorization
- Returns & refunds system
- WhatsApp invoice sharing

### 📦 Inventory Management
- Multi-branch stock control (up to 5 branches + warehouse)
- Real-time stock transfers between branches
- Low stock alerts & configurable thresholds
- Product families & categories
- Barcode & price tag printing

### 📊 Analytics & Reports
- Executive dashboard with KPIs
- ATV (Average Transaction Value) & UPT (Units Per Transaction)
- ABC product analysis (A/B/C classification)
- Comparative branch analytics
- Salesperson performance reports
- Profit & margin tracking per product/branch
- Excel & PDF export for all reports

### 👥 CRM & Customers
- Customer profiles with full purchase history
- Offers & promotions management

### 🏪 Multi-Branch
- Up to 5 branches + main warehouse
- Per-branch dashboards and report filtering
- Inter-branch stock transfer management
- Real-time sync via Firebase Firestore

### 🛍️ Purchasing
- Supplier management
- Purchase orders (PO) creation & tracking
- Goods receipt with automatic inventory update

### 💰 Finance
- Expense tracking (branch-level & administrative)
- Revenue, cost & profit reports
- Basic accounting ledger

### 👨‍💼 HR & Payroll
- Employee management
- Salary & attendance tracking
- Salesperson targets & commission calculation
- Full audit log of all system changes

### ⚙️ Technical Highlights
- **PWA** — installable on any device, fully works offline
- **Dark mode** — system-aware toggle
- **Firebase real-time** — live sync across all devices
- **Google Drive backup** — automatic daily backups
- **Complete audit trail** — every change is logged with user & timestamp
- **Export everything** — Excel & PDF for every report

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Vanilla JavaScript (ES2022+) |
| UI Framework | Bootstrap 5 + Custom CSS |
| Real-time Database | Firebase Firestore |
| Offline Storage | localStorage + IndexedDB |
| PWA | Web App Manifest + Service Worker |
| Deployment | Vercel |
| Cloud Backup | Google Drive API (OAuth 2.0) |
| Architecture | Single-file app (~9,000 lines) |

---

## ⚡ Deploy in 60 Seconds

### Option 1: Vercel (Recommended — One Click)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/shekovichy/al-ahram-pos)

### Option 2: Local
```bash
git clone https://github.com/shekovichy/al-ahram-pos.git
cd al-ahram-pos
# Open index.html in any browser — done!
```

### Option 3: Any Static Host
Upload `index.html`, `manifest.json`, and `sw.js` to Netlify, GitHub Pages, S3, or any CDN.

---

## 🔧 First-Time Setup

1. Open the app → first-run wizard sets admin password
2. Go to **Settings → Branches** — set your branch names
3. Go to **Settings → Firebase** — add your Firebase config for real-time sync
4. Go to **Settings → Backup** — add Google Drive Client ID for cloud backup

---

## 🌍 Language

- **Arabic (RTL)** — primary UI language
- Designed specifically for Arabic-speaking retail businesses in the Middle East

---

## 📈 Roadmap

- [ ] Full double-entry accounting (قيود يومية)
- [ ] Advanced user permissions (per-field access control)
- [ ] REST API for third-party integrations
- [ ] E-commerce / online store module
- [ ] Native iOS & Android app
- [ ] Manufacturing module (MRP/BOM)
- [ ] Google verification for Drive OAuth

---

## 🤝 Contributing

Pull requests are welcome!

```bash
# 1. Fork the repo
# 2. Create your branch
git checkout -b feature/my-feature
# 3. Commit
git commit -m 'Add my feature'
# 4. Push & open a PR
git push origin feature/my-feature
```

---

## 📄 License

MIT License — free for personal and commercial use.

---

## 💬 Support

- **Live App:** https://voodo-erp.vercel.app
- **Issues:** [GitHub Issues](https://github.com/shekovichy/al-ahram-pos/issues)
- **Email:** shekovichy@gmail.com

---

<div align="center">

Built with ❤️ for Arabic retail businesses

**⭐ Star this repo if you find it useful!**

</div>
