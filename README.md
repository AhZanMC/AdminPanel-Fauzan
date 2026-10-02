# 🚀 Admin Panel Fauzan

**Admin Panel Fauzan** adalah template dashboard admin modular, modern, dan *lightweight* yang dibangun menggunakan **Vanilla HTML**, **Tailwind CSS v4**, dan **Vite**. Template ini dirancang dengan struktur *clean code* dan fleksibel untuk digunakan pada proyek pribadi, sistem internal, dan apapun :v

---

## 🌟 Fitur Utama

- 🎨 **Light Mode Standard** — Desain bersih, kontras tinggi, dan optimal untuk presentasi atau sidang akademik.
- 👾 **Custom Pixel Art Branding** — Dukungan Aseprite pixel art logo yang tajam (`image-rendering: pixelated`).
- 📱 **Collapsible & Responsive Sidebar** — Sidebar yang fleksibel untuk mode desktop dan *drawer* otomatis di perangkat mobile.
- ⚡ **Interactive Components**:
  - **CRUD Modal**: Popup interaktif untuk tambah, edit, dan hapus data.
  - **Live Table Search**: Pencarian data secara *real-time* di tabel tanpa *dependency* luar.
  - **Toast Notification**: System feedback yang responsif dan teranimasi.
- 🔐 **Authentication Pages**: Halaman `login.html` dan `register.html` lengkap dengan *Show/Hide Password*, validasi konfirmasi password, serta simulasi *logout confirmation*.
- 📦 **Modular JS Structure** — Pembagian logika JavaScript terpisah berdasarkan fungsi (Auth, Modal, Sidebar, Search, Toast).

---

## 🛠️ Tech Stack

- **Build Tool:** [Vite](https://vitejs.dev/)
- **CSS Framework:** [Tailwind CSS v4](https://tailwindcss.com/)
- **Language:** HTML5 & Vanilla JavaScript (ES Modules)
- **Icons:** Inline SVG (Heroicons / Lucide)
- **Design & Assets:** Aseprite (Pixel Art Logo)

---

## 📁 Struktur Proyek

```text
├── assets/
│   ├── css/
│   │   ├── output.css        # CSS hasil kompilasi Tailwind
│   │   └── style.css         # Custom styling & Tailwind directives (@theme)
│   ├── images/               # Aset gambar & logo pixel art
│   └── js/
│       ├── Auth/
│       │   ├── login.js      # Logika form login
│       │   ├── logout.js     # Logika logout & konfirmasi
│       │   └── register.js   # Logika pendaftaran & validasi password
│       ├── crudModal.js      # Logika modal CRUD & hapus baris
│       ├── sidebarToggle.js  # Logika toggle sidebar desktop/mobile
│       ├── tableSearch.js    # Logika live search tabel
│       └── toastNotif.js     # Logika notifikasi toast
├── node_modules/
├── .gitignore
├── index.html                # Main Dashboard Page
├── login.html                # Halaman Login
├── register.html             # Halaman Registrasi
├── package.json
├── package-lock.json
└── vite.config.js
```

---

## 📥 Panduan Instalasi Node.js & NPM (Setup dari Nol)

Jika kamu belum memiliki **Node.js** dan **NPM** di komputer kamu, ikuti langkah berikut:

### 1. Download & Install Node.js
1. Buka situs resmi [Node.js](https://nodejs.org/).
2. Download versi **LTS (Long Term Support)** yang direkomendasikan untuk stabilitas terbaik.
3. Jalankan file installer (`.msi` atau `.pkg`) yang sudah didownload.
4. Klik **Next** terus sampai selesai (pastikan opsi *"Add to PATH"* tercentang secara default).
5. Untuk memastikan Node.js & NPM sudah terinstall dengan benar, buka **Terminal** / **Command Prompt (CMD)** lalu ketik:
   ```bash
   node -v
   npm -v
6. Jika berhasil, terminal akan menampilkan nomor versi, contohnya:
```text
   v22.12.0
   10.9.0
```
7. kalo udah ketik di terminal `npm run dev` untuk menjalankan Tailwind CSS
8. Kalo mau liat preview web ini gunakan extension Live Server
9. DONE