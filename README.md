# 🕌 Masjid Hub

> **Open-source mosque operations management system for masjid, mushalla, and Islamic community centers.**

**Masjid Hub** adalah modul dalam ekosistem **Ummah Civic Super App** untuk membantu pengurus masjid mengelola profil masjid, struktur DKM, jadwal ibadah, kajian, pengumuman, inventaris, dokumen, halaman publik, dan laporan operasional secara rapi, amanah, transparan, dan mudah diwariskan.

> Masjid bukan hanya tempat shalat.
> Masjid adalah pusat ibadah, pendidikan, sosial, dakwah, dan peradaban.
> **Masjid Hub membantu fungsi besar itu ditopang oleh sistem yang rapi.**

---

## 🌙 Why Masjid Hub?

Banyak masjid dan mushalla masih mengandalkan:

* 💬 Grup WhatsApp
* 📊 Excel pribadi
* 📒 Buku kas manual
* 📁 Dokumen tercecer
* 🕰️ Jadwal yang diingat satu orang
* 📦 Inventaris tanpa catatan
* 🧾 Laporan yang tidak standar

Masalahnya bukan selalu niat buruk.
Sering kali masalahnya adalah:

> **Amanah belum ditopang oleh sistem.**

Masjid Hub membantu masjid menjadi lebih:

* ✅ Organized
* ✅ Transparent
* ✅ Accountable
* ✅ Easy to manage
* ✅ Easy to hand over to future committees
* ✅ Self-hosted and vendor-independent

---

## 🚧 Project Status

```txt
Status       : Draft / Early Planning
Version      : v0.1
License      : MIT
Parent       : Ummah Civic Super App
Target       : Indonesia-first, global-ready
Deployment   : Self-hosted first
```

---

## ✨ Core Features

### 🧩 MVP Features

* 🕌 Mosque/mushalla profile
* 👥 DKM/takmir structure
* 🕋 Worship schedule
* 🕌 Friday prayer schedule
* 🎙️ Imam, khatib, muadzin, bilal assignments
* 📚 Kajian/event management
* 📢 Announcements
* 🌐 Public mosque page
* 📦 Basic inventory
* 📁 Basic document archive
* 🧾 Monthly operational report
* 📤 CSV/JSON export
* 🔐 Audit log
* 🐳 Docker Compose deployment

### 🔮 Future Features

* 👨‍👩‍👧‍👦 Jamaah registry
* 🛠️ Facility maintenance tickets
* 🧍 Event attendance
* 🖥️ Display board mode
* 📱 PWA/offline-friendly mode
* 💰 Integration with Amanah Ledger
* 📖 Integration with TPA/Tahfidz Hub
* 🤝 Integration with Relawan Hub
* 🧾 Integration with Mustahik Registry
* 🚀 Integration with Ummah Mission Hub
* 🌍 Multi-language support
* 🔌 Public API

---


## 🏗️ Architecture

```txt
Browser / PWA Client
        |
        v
Web App / UI Layer
        |
        v
API Layer
        |
        v
Masjid Hub Domain Services
        |
        v
Ummah Core Services
(Auth, Tenant, RBAC, People, Files, Audit Logs)
        |
        v
PostgreSQL + S3-Compatible Storage
```

### 🧱 Architecture Principles

* 🔐 Secure by default
* 🏢 Multi-tenant ready
* 📜 Audit-friendly
* 🧩 Modular domain design
* 🐳 Self-hosted first
* 🌍 Global-ready, Indonesia-first
* 🔌 Integration-oriented

---

## 🔗 Integrations

Masjid Hub is designed to integrate with other **Ummah Civic Stack** modules:

| Module               | Integration                                          |
| -------------------- | ---------------------------------------------------- |
| `ummah-core`         | Auth, organization, RBAC, people, audit logs         |
| `amanah-ledger`      | Funds, transactions, financial reports, transparency |
| `tpa-tahfidz-hub`    | TPA programs under mosque                            |
| `dakwah-content-hub` | Kajian materials, khutbah archive, speakers          |
| `ummah-mission-hub`  | Social/dakwah field missions                         |
| `mustahik-registry`  | Beneficiary data for social programs                 |
| `relawan-hub`        | Volunteer assignments                                |
| `org-hub`            | Governance, meetings, decisions                      |
| `ziswaf-kit`         | Zakat, infaq, sedekah, and wakaf workflows           |

---

## 🗺️ Roadmap Summary

| Year | Focus                         |
| ---: | ----------------------------- |
|    1 | MVP and pilot                 |
|    2 | Stabilization and trust layer |
|    3 | Operational maturity          |
|    4 | Cross-domain integration      |
|    5 | Network and standardization   |
|    6 | Mobile/PWA resilience         |
|    7 | Advanced governance           |
|    8 | Regional/global adaptation    |
|    9 | Intelligence without fatwa    |
|   10 | Civic infrastructure maturity |

---

## 🤝 Contributing

Contributions are welcome.

Good first contribution areas:

* 📚 Documentation
* 🇮🇩 Indonesian UI copy
* 🧹 Issue triage
* ♿ Accessibility review
* ✅ Form validation
* 🌱 Seed data
* 🧪 Test cases
* 🐳 Docker setup
* 🎨 UI components
* 🔌 API
* 🗄️ Database
* 🌐 Public page templates

---

## 🔐 Security

If you find a security issue, please report it responsibly.

High-priority security areas:

* 🏢 Organization data isolation
* 👁️ Public/private visibility
* 📁 File access control
* 👤 Role permissions
* 📜 Audit logs
* 📤 Export permissions

---

## 🧭 Philosophy

Masjid Hub is built on one simple belief:

> **Amanah is not only a moral virtue.**
> Amanah also needs good systems, clear records, transparent workflows, and responsible governance.

A masjid with good intentions but poor records will eventually exhaust its best people.

A masjid with good intentions and good systems can serve the ummah across generations.

---

## 🌍 Project Vision

Masjid Hub aims to become a trustworthy open-source foundation for mosque operations worldwide, starting from Indonesia.

The long-term goal is not merely software adoption.

The long-term goal is stronger Muslim institutions:

* 🕌 More organized
* 🧾 More accountable
* 🔍 More transparent
* 🌱 More sustainable
* 🤝 More beneficial for the ummah

---

## 📜 License

This project is released under the **MIT License**.

---

## 🤲 Closing Note

> Good institutions are not built only by good people.
> They are built by good people, good systems, clear records, and sincere accountability.

**Masjid Hub exists to help masjid become stronger, cleaner, more organized, and easier to continue across generations.**
