# 🕌 Masjid Hub

> **Sistem manajemen operasional masjid sumber terbuka (open-source) untuk masjid, mushalla, dan pusat komunitas Islam.**

**Masjid Hub** adalah modul dalam ekosistem **Ummah Civic Super App** yang membantu pengurus masjid mengelola profil masjid, struktur DKM, jadwal ibadah, kajian, pengumuman, inventaris, dokumen, halaman publik, dan laporan operasional secara rapi, amanah, transparan, serta mudah diwariskan.

> Masjid bukan hanya tempat shalat.
>
> Masjid adalah pusat ibadah, pendidikan, sosial, dakwah, dan peradaban.
>
> **Masjid Hub membantu fungsi besar tersebut ditopang oleh sistem yang tertata dengan baik.**

---

## 🌙 Mengapa Masjid Hub?

Banyak masjid dan mushalla masih mengandalkan:

* 💬 Grup WhatsApp
* 📊 File Excel pribadi
* 📒 Buku kas manual
* 📁 Dokumen yang tercecer
* 🕰️ Jadwal yang hanya diingat oleh satu orang
* 📦 Inventaris tanpa pencatatan
* 🧾 Laporan yang tidak memiliki standar

Masalahnya tidak selalu karena niat yang buruk.

Sering kali masalahnya adalah:

> **Amanah belum didukung oleh sistem yang baik.**

Masjid Hub membantu masjid menjadi lebih:

* ✅ Terorganisasi
* ✅ Transparan
* ✅ Akuntabel
* ✅ Mudah dikelola
* ✅ Mudah diserahterimakan kepada pengurus berikutnya
* ✅ Dapat di-host sendiri tanpa ketergantungan vendor

---

## 🚧 Status Proyek

```txt
Status       : Draft / Perencanaan Awal
Versi        : v0.1
Lisensi      : MIT
Induk Proyek : Ummah Civic Super App
Target       : Indonesia terlebih dahulu, siap untuk global
Deployment   : Prioritas self-hosted
```

---

## ✨ Fitur Utama

### 🧩 Fitur MVP

* 🕌 Profil masjid/mushalla
* 👥 Struktur DKM/takmir
* 🕋 Jadwal ibadah
* 🕌 Jadwal shalat Jumat
* 🎙️ Penugasan imam, khatib, muadzin, dan bilal
* 📚 Manajemen kajian dan kegiatan
* 📢 Pengumuman
* 🌐 Halaman publik masjid
* 📦 Inventaris dasar
* 📁 Arsip dokumen dasar
* 🧾 Laporan operasional bulanan
* 📤 Ekspor CSV/JSON
* 🔐 Log audit
* 🐳 Deployment Docker Compose

### 🔮 Fitur Masa Depan

* 👨‍👩‍👧‍👦 Registrasi jamaah
* 🛠️ Tiket pemeliharaan fasilitas
* 🧍 Kehadiran peserta kegiatan
* 🖥️ Mode papan informasi digital
* 📱 Dukungan PWA dan mode offline
* 💰 Integrasi dengan Amanah Ledger
* 📖 Integrasi dengan TPA/Tahfidz Hub
* 🤝 Integrasi dengan Relawan Hub
* 🧾 Integrasi dengan Mustahik Registry
* 🚀 Integrasi dengan Ummah Mission Hub
* 🌍 Dukungan multi-bahasa
* 🔌 API publik

---

## 🏗️ Arsitektur

```txt
Browser / Klien PWA
        |
        v
Aplikasi Web / Lapisan Antarmuka
        |
        v
Lapisan API
        |
        v
Layanan Domain Masjid Hub
        |
        v
Layanan Inti Ummah
(Auth, Tenant, RBAC, Data Anggota, Berkas, Audit Log)
        |
        v
PostgreSQL + Penyimpanan Kompatibel S3
```

### 🧱 Prinsip Arsitektur

* 🔐 Aman secara bawaan
* 🏢 Siap multi-tenant
* 📜 Ramah audit
* 🧩 Desain domain modular
* 🐳 Prioritas self-hosted
* 🌍 Siap digunakan secara global, dimulai dari Indonesia
* 🔌 Berorientasi integrasi

---

## 🔗 Integrasi

Masjid Hub dirancang untuk terintegrasi dengan modul lain dalam **Ummah Civic Stack**:

| Modul                | Integrasi                                              |
| -------------------- | ------------------------------------------------------ |
| `ummah-core`         | Autentikasi, organisasi, RBAC, data anggota, audit log |
| `amanah-ledger`      | Dana, transaksi, laporan keuangan, transparansi        |
| `tpa-tahfidz-hub`    | Program TPA dan tahfidz di bawah masjid                |
| `dakwah-content-hub` | Materi kajian, arsip khutbah, data pemateri            |
| `ummah-mission-hub`  | Program sosial dan misi dakwah lapangan                |
| `mustahik-registry`  | Data penerima manfaat program sosial                   |
| `relawan-hub`        | Penugasan relawan                                      |
| `org-hub`            | Tata kelola, rapat, dan keputusan organisasi           |
| `ziswaf-kit`         | Alur kerja zakat, infak, sedekah, dan wakaf            |

---

## 🗺️ Ringkasan Roadmap

| Tahun | Fokus                                           |
| ----: | ----------------------------------------------- |
|     1 | MVP dan proyek percontohan                      |
|     2 | Stabilisasi dan pembangunan lapisan kepercayaan |
|     3 | Kematangan operasional                          |
|     4 | Integrasi lintas domain                         |
|     5 | Jaringan dan standarisasi                       |
|     6 | Ketahanan mobile/PWA                            |
|     7 | Tata kelola tingkat lanjut                      |
|     8 | Adaptasi regional dan global                    |
|     9 | Kecerdasan operasional tanpa fungsi fatwa       |
|    10 | Kematangan infrastruktur sipil                  |

---

## 🤝 Kontribusi

Kontribusi sangat terbuka.

Area kontribusi yang cocok untuk pemula:

* 📚 Dokumentasi
* 🇮🇩 Teks antarmuka Bahasa Indonesia
* 🧹 Triase dan pengelolaan issue
* ♿ Tinjauan aksesibilitas
* ✅ Validasi formulir
* 🌱 Data contoh (seed data)
* 🧪 Pengujian
* 🐳 Konfigurasi Docker
* 🎨 Komponen UI
* 🔌 API
* 🗄️ Basis data
* 🌐 Template halaman publik

---

## 🔐 Keamanan

Jika Anda menemukan celah keamanan, mohon laporkan secara bertanggung jawab.

Area keamanan dengan prioritas tinggi:

* 🏢 Isolasi data organisasi
* 👁️ Pengaturan visibilitas publik dan privat
* 📁 Kontrol akses berkas
* 👤 Hak akses dan peran pengguna
* 📜 Audit log
* 📤 Hak ekspor data

---

## 🧭 Filosofi

Masjid Hub dibangun berdasarkan satu keyakinan sederhana:

> **Amanah bukan hanya nilai moral.**
>
> Amanah juga membutuhkan sistem yang baik, pencatatan yang jelas, alur kerja yang transparan, dan tata kelola yang bertanggung jawab.

Masjid dengan niat baik tetapi pencatatan yang buruk pada akhirnya akan menguras energi orang-orang terbaiknya.

Masjid dengan niat baik dan sistem yang baik dapat melayani umat lintas generasi.

---

## 🌍 Visi Proyek

Masjid Hub bertujuan menjadi fondasi open-source yang terpercaya untuk operasional masjid di seluruh dunia, dimulai dari Indonesia.

Tujuan jangka panjangnya bukan sekadar adopsi perangkat lunak.

Tujuan jangka panjangnya adalah membangun institusi Muslim yang:

* 🕌 Lebih terorganisasi
* 🧾 Lebih akuntabel
* 🔍 Lebih transparan
* 🌱 Lebih berkelanjutan
* 🤝 Lebih bermanfaat bagi umat

---

## 📜 Lisensi

Proyek ini dirilis di bawah lisensi **MIT**.

---

## 🤲 Catatan Penutup

> Institusi yang baik tidak dibangun hanya oleh orang-orang baik.
>
> Institusi yang baik dibangun oleh orang-orang baik yang didukung sistem yang baik, pencatatan yang jelas, dan akuntabilitas yang tulus.

**Masjid Hub hadir untuk membantu masjid menjadi lebih kuat, lebih tertib, lebih terorganisasi, dan lebih mudah dilanjutkan oleh generasi berikutnya.**
