# Kupass 🔐

Kupass (Aku - User - Pass) adalah *tool* simpel berbasis web buat bikin username, password, atau pasangan kredensial (Pairs) secara *offline*. Semuanya digenerate langsung di *browser* kamu pakai *Cryptographically Secure RNG* (CSPRNG), jadi aman dan nggak butuh koneksi internet.

**Link Repo:** [https://github.com/xwzsmcvnra/kupass](https://github.com/xwzsmcvnra/kupass)

## Fitur
- **Randomize:** Bikin kredensial baru pakai aturan yang kamu tentuin sendiri (huruf besar/kecil, angka, simbol, dll).
- **Existing:** Gabungin username dan password yang udah kamu generate sebelumnya jadi satu paket rapi.
- **Export & Backup:** Simpan hasilnya ke format CSV, TXT, PDF, atau Backup JSON (buat di-*update* nanti).
- **Mode Update:** Upload file backup JSON buat generate ulang password tanpa ngubah format aslinya.

## Soal Privasi & Data
Kami percaya privasi itu penting, jadi Kupass dibuat sejujur mungkin:
- **Nggak ada data yang dikirim ke server.** Semua proses terjadi di HP/laptop kamu.
- Kupass *menggunakan* `localStorage` untuk mengingat preferensi kamu (seperti tema, panjang password, dll) biar nggak perlu setting ulang tiap buka.
- `sessionStorage` dipakai sementara saat kamu masuk ke "Mode Update".
- **Password atau kredensial hasil generate nggak akan pernah disimpan permanen.** Kalau kamu reload halaman atau nutup tab, hasilnya bakal hilang. Makanya, selalu pakai tombol **Backup** sebelum keluar!
- Kalau lagi pakai komputer bersama, biasakan klik ikon **Power** (tombol hapus) buat bersihin *history* input dan hasil generate dari *browser*.

## Cara Pakai Singkat
1. Buka file `indexnew.html` di browser (Chrome/Edge/Firefox/Safari).
2. Pilih tab yang mau kamu kerjain (Username, Password, atau Pairs).
3. Atur panjang dan aturan karakternya.
4. Klik **Generate**.
5. Klik ikon **Backup** di pojok kanan atas kalau mau nyimpen hasilnya.

---
*Dibuat simpel buat kamu yang butuh kredensial cepat tapi tetap peduli keamanan.*
