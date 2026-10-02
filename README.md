# Mutmainnah_Lab

Simulator papan UNO yang berjalan di browser. Rakit rangkaian di breadboard, tulis kode Arduino (C++), jalankan, lalu susun rancangan proyek: daftar komponen, tabel sambungan, dan pemeriksaan rangkaian.

## Fitur
- Papan UNO dan breadboard 400 titik dengan tampilan realistis
- Komponen: LED, resistor, tombol, potensiometer, LDR, buzzer, servo, LCD 16×2 I2C, sensor ultrasonik HC-SR04
- Simulasi tegangan dan arus (LED bisa terbakar tanpa resistor, hubung singkat memutus daya)
- Editor kode, Serial Monitor, dan Serial Plotter
- 10 contoh proyek siap jalan
- Proyek tersimpan otomatis di browser

## Publikasi di GitHub Pages
1. Buat repository baru di GitHub, misalnya `mutmainnah-lab`.
2. Unggah `index.html` (dan `README.md`) ke cabang `main`.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Source: Deploy from a branch**, lalu **Branch: main** dan folder **/ (root)**. Klik **Save**.
5. Tunggu 1–2 menit. Situs akan tersedia di `https://<nama-pengguna>.github.io/mutmainnah-lab/`.

Semua kode ada dalam satu file `index.html`; tidak perlu proses build. Font dimuat dari Google Fonts, dan jika tidak tersedia, halaman otomatis memakai font sistem.
