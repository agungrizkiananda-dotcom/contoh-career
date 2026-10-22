# Template Halaman Karier — PT Contoh Maju Jaya

Template statis (HTML + CSS) untuk halaman "Karier" perusahaan, lengkap dengan form lamaran kerja. **"PT Contoh Maju Jaya" adalah nama perusahaan fiktif** — dibuat untuk tujuan latihan/contoh tata letak, bukan situs resmi entitas nyata mana pun.

## Isi Folder

```
contoh-careers/
├── index.html      # Halaman beranda + daftar posisi
├── careers.html     # Form lamaran kerja (data pribadi, pendidikan, kontak)
├── style.css         # Styling bersama untuk kedua halaman
└── README.md         # Berkas ini
```

## Cara Menjalankan

Situs ini statis, tidak perlu server khusus.

1. Ekstrak folder ini.
2. Buka `index.html` langsung di browser, **atau**
3. Jalankan server lokal sederhana dari dalam folder, misalnya:
   ```bash
   python3 -m http.server 8000
   ```
   lalu buka `http://localhost:8000` di browser.

## Catatan Penting

- **Form tidak terhubung ke server/database apa pun.** Tombol "Kirim" di `careers.html` hanya contoh tata letak (`onsubmit="return false;"`) dan tidak mengirim atau menyimpan data ke mana pun.
- Semua nama perusahaan, logo, dan posisi lowongan di dalamnya adalah placeholder — silakan ganti sesuai kebutuhan Anda sendiri.
- Jika Anda ingin memakai template ini untuk bisnis/perusahaan Anda yang sah, ganti:
  - Nama perusahaan dan logo di `index.html` & `careers.html`
  - Daftar posisi di bagian `.positions` (index) dan `<select id="posisi">` (careers)
  - Tambahkan backend (form handler, database, atau layanan pihak ketiga) yang aman untuk benar-benar memproses data pelamar, beserta kebijakan privasi yang jelas.

## Lisensi

Bebas dipakai dan dimodifikasi untuk keperluan pribadi/latihan.
