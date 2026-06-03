# Masjid Hub

**Open-source mosque operations management system for masjid, mushalla, and Islamic community centers.**

Masjid Hub adalah modul dalam ekosistem **Ummah Civic Super App** untuk membantu pengurus masjid mengelola profil masjid, struktur DKM, jadwal ibadah, kajian, pengumuman, inventaris, dokumen, halaman publik, dan laporan operasional secara rapi, amanah, transparan, dan mudah diwariskan.

> Masjid bukan hanya tempat shalat. Masjid adalah pusat ibadah, pendidikan, sosial, dakwah, dan peradaban. Masjid Hub membantu fungsi besar itu ditopang oleh sistem yang rapi.

---

## Why Masjid Hub?

Banyak masjid dan mushalla masih mengandalkan:

- grup WhatsApp;
- Excel pribadi;
- buku kas manual;
- dokumen tercecer;
- jadwal yang diingat satu orang;
- inventaris tanpa catatan;
- laporan yang tidak standar.

Masalahnya bukan selalu niat buruk. Sering kali masalahnya adalah **amanah belum ditopang oleh sistem**.

Masjid Hub membantu masjid menjadi lebih:

- organized;
- transparent;
- accountable;
- easy to manage;
- easy to hand over to future committees;
- self-hosted and vendor-independent.

---

## Project Status

```txt
Status       : Draft / Early Planning
Version      : v0.1 roadmap
License      : AGPL-3.0-or-later recommended for app
Parent       : Ummah Civic Super App
Target       : Indonesia-first, global-ready
Deployment   : Self-hosted first
```

---

## Core Features

### MVP Features

- Mosque/mushalla profile.
- DKM/takmir structure.
- Worship schedule.
- Friday prayer schedule.
- Imam, khatib, muadzin, bilal assignments.
- Kajian/event management.
- Announcements.
- Public mosque page.
- Basic inventory.
- Basic document archive.
- Monthly operational report.
- CSV/JSON export.
- Audit log.
- Docker Compose deployment.

### Future Features

- Jamaah registry.
- Facility maintenance tickets.
- Event attendance.
- Display board mode.
- PWA/offline-friendly mode.
- Integration with Amanah Ledger.
- Integration with TPA/Tahfidz Hub.
- Integration with Relawan Hub.
- Integration with Mustahik Registry.
- Integration with Ummah Mission Hub.
- Multi-language support.
- Public API.

---

## What This Project Is Not

Masjid Hub is not:

- a fatwa engine;
- an AI ustadz;
- a political campaign tool;
- a surveillance tool for jamaah;
- a government system replacement;
- a legal verification tool for land/waqf;
- a full accounting system;
- a closed commercial SaaS.

---

## Architecture

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

---

## Integrations

Masjid Hub is designed to integrate with other Ummah Civic Stack modules:

| Module | Integration |
|---|---|
| `ummah-core` | Auth, organization, RBAC, people, audit logs |
| `amanah-ledger` | Funds, transactions, financial reports, transparency |
| `tpa-tahfidz-Hub` | TPA programs under mosque |
| `dakwah-content-Hub` | Kajian materials, khutbah archive, speakers |
| `ummah-mission-Hub` | Social/dakwah field missions |
| `mustahik-registry` | Beneficiary data for social programs |
| `relawan-Hub` | Volunteer assignments |
| `org-Hub` | Governance, meetings, decisions |
| `ziswaf-kit` | Zakat/infaq/sedekah/wakaf workflows |

---

## Roadmap Summary

| Year | Focus |
|---:|---|
| 1 | MVP and pilot |
| 2 | Stabilization and trust layer |
| 3 | Operational maturity |
| 4 | Cross-domain integration |
| 5 | Network and standardization |
| 6 | Mobile/PWA resilience |
| 7 | Advanced governance |
| 8 | Regional/global adaptation |
| 9 | Intelligence without fatwa |
| 10 | Civic infrastructure maturity |

See `docs/ROADMAP.md` for full roadmap.

---

## Contributing

Contributions are welcome.

Good first contribution areas:

- documentation;
- Indonesian UI copy;
- issue triage;
- accessibility review;
- form validation;
- seed data;
- test cases;
- Docker setup;
- UI components;
- public page templates.

Before contributing, please read:

- `CONTRIBUTING.md`
- `CODE_OF_CONDUCT.md`
- `SECURITY.md`

---

## Security

If you find a security issue, do not open a public issue. Please follow the process in `SECURITY.md`.

High-priority security areas:

- organization data isolation;
- public/private visibility;
- file access control;
- role permissions;
- audit logs;
- export permissions.

---

## Philosophy

Masjid Hub is built on one simple belief:

> Amanah is not only a moral virtue. Amanah also needs good systems, clear records, transparent workflows, and responsible governance.

A masjid with good intentions but poor records will eventually exhaust its best people. A masjid with good intentions and good systems can serve the ummah across generations.

---

## Project Vision

Masjid Hub aims to become a trustworthy open-source foundation for mosque operations worldwide, starting from Indonesia.

The long-term goal is not merely software adoption. The long-term goal is stronger Muslim institutions: more organized, more accountable, more transparent, and more sustainable.
