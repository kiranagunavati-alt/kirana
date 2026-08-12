# 🌸 Kirana's Space - Profile & Portofolio Tugas Sekolah

Website profil pribadi & kumpulan tugas sekolah yang dibuat dengan **HTML5, Tailwind CSS, Lucide Icons, dan JavaScript Vanilla**. Memiliki tema warna **Pastel Pink & Rose Cream** yang lembut, modern, dan estetik.

Website ini berformat **Single File HTML (`index.html`)**, sehingga sangat mudah dipublish ke hosting mana pun tanpa perlu install Node.js atau proses build yang rumit!

---

## 📌 Fitur Utama

1. **🎨 Tampilan Estetik Pastel Pink**: Menggabungkan efek glassmorphism, warna pastel soft (`#f472b6`, `#fda4af`), serta font *Plus Jakarta Sans* & *Playfair Display*.
2. **📱 Responsif & User Friendly**: Tampilan menyesuaikan secara otomatis di Layar HP, Tablet, dan Laptop/PC dengan menu drawer mobile.
3. **🧭 Navigasi Menu SPA**:
   - **Dashboard**: Hero greeting, statistik tugas, sorotan tugas terbaru, dan hub sosial media.
   - **Profil**: Biodata lengkap pelajar, hobi, progres skill (HTML/CSS, Esai, Canva), dan link kontak.
   - **Tugas**: Filter tugas per mata pelajaran,live search judul tugas, serta badge status.
   - **Informatika**: Showcase khusus tugas IT, koding HTML/CSS, infografis keamanan siber, dan flowchart.
   - **Bahasa Indonesia**: Showcase karya literasi, esai argumentatif, resensi buku Laskar Pelangi, dan puisi senja pastel.
4. **🌐 Integrasi Link Sosial Media**: Tombol dan kartu direct ke Instagram, TikTok, GitHub, LinkedIn, YouTube, Email, dan WhatsApp.
5. **🔍 Live Search & Interactive Modal**: Pengunjung bisa mencari judul tugas serta membuka jendela popup detail informasi tugas.

---

## 🛠️ Cara Mengubah Data Diri & Menambah Tugas Baru

Karena websitenya menggunakan **1 file HTML**, Anda bisa membukanya menggunakan text editor seperti VS Code, Notepad++, atau Notepad:

### 1. Mengubah Link Sosial Media
Cari bagian `href="https://instagram.com"` pada file `index.html` dan ganti dengan username akun Anda:
```html
<a href="https://instagram.com/username_kamu" target="_blank">@instagram_kamu</a>
<a href="https://tiktok.com/@username_kamu" target="_blank">@tiktok_kamu</a>
<a href="https://wa.me/6281234567890" target="_blank">WhatsApp Kamu</a>
```

### 2. Menambah Card Tugas Baru di Section Tugas
Cari `<div id="task-grid-container">` dan tambahkan elemen card berikut:
```html
<div class="task-card glass-card rounded-2xl p-6 flex flex-col justify-between hover:shadow-lg transition-all border-t-4 border-t-pastel-400" data-subject="Informatika" data-title="Judul Tugas Baru Kamu">
    <div class="space-y-3">
        <div class="flex items-center justify-between">
            <span class="px-2.5 py-1 rounded-full text-[10px] font-bold bg-pastel-100 text-pastel-600">Informatika</span>
            <span class="text-[11px] text-slate-400">20 Jul 2026</span>
        </div>
        <h3 class="text-base font-bold text-slate-800 leading-snug">Judul Tugas Baru Kamu</h3>
        <p class="text-xs text-slate-500 line-clamp-3 leading-relaxed">
            Ringkasan atau penjelasan singkat mengenai tugas sekolah ini.
        </p>
    </div>
    <div class="pt-4 mt-4 border-t border-pink-50 flex items-center justify-between">
        <span class="text-[10px] font-bold text-emerald-600 bg-emerald-50 px-2 py-0.5 rounded">Selesai</span>
        <button onclick="openModal('Judul Tugas Baru', 'Informatika', '20 Jul 2026', 'Deskripsi lengkap tugas...', 'Format File', 'Selesai')" class="text-xs font-bold text-pastel-600 hover:text-pastel-700 flex items-center gap-1">Pratinjau <i data-lucide="eye" class="w-3.5 h-3.5"></i></button>
    </div>
</div>
```

---

## 🚀 Panduan Publish ke Hosting (Gratis)

### Pilihan 1: GitHub Pages (Gratis & Paling Populer)
1. Buat akun di [GitHub](https://github.com) jika belum punya.
2. Buat Repository baru dengan nama `portofolio-tugas` (centang *Public*).
3. Upload file `index.html` ini ke repository tersebut.
4. Buka menu **Settings** > **Pages** > Pada bagian **Branch**, pilih `main` dan klik **Save**.
5. Website Anda akan aktif di URL: `https://username_kamu.github.io/portofolio-tugas/`.

### Pilihan 2: Netlify Drop (Sangat Cepat & Tanpa Koding)
1. Buka [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag & Drop folder yang berisi file `index.html` ini ke area yang disediakan.
3. Website Anda langsung aktif dan memberikan link domain gratis (dapat di-custom).

### Pilihan 3: Shared Hosting / cPanel (Hosting Berbayar)
1. Login ke cPanel hosting Anda.
2. Buka **File Manager** > masuk ke folder `public_html`.
3. Upload file `index.html`.
4. Website akan langsung aktif di domain Anda sendiri.

---

### ✨ Dibuat Spesial untuk Kirana
*Semoga portofolio tugas sekolah ini bermanfaat dan membantu nilai sekolah kamu makin gemilang!*
