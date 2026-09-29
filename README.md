![Preview](preview.png)

# QR Code Generator — Direct Link

Generator QR code sederhana yang menyimpan **URL asli secara langsung** ke dalam QR. Tidak ada shortlink, tidak ada redirect, tidak ada tracking.

🔗 **Live demo:** https://tandurkarsa.github.io/qrcode/

---

## ✨ Fitur

- **QR Statis Murni** — URL asli dibakar ke dalam QR, bukan shortlink
- **Tanpa Redirect** — Scanner langsung membuka domain tujuan
- **Tanpa Backend** — 100% berjalan di browser (client-side)
- **Tanpa Tracking** — Tidak ada data yang dikirim ke server mana pun
- **Real-time Preview** — QR berubah seiring kamu mengetik URL
- **Validasi URL** — Deteksi otomatis URL tidak valid
- **Auto HTTPS** — Ketik `example.com` tanpa `https://` juga bisa
- **Download PNG & SVG** — SVG untuk cetak, PNG untuk digital
- **Ukuran Kustom** — 256 / 512 / 1024 / 2048 px
- **Error Correction** — Level L, M, Q, H
- **Warna Kustom** — Atur warna QR dan background
- **Quiet Zone** — Atur margin sesuai kebutuhan

---

## 🚀 Cara Pakai

1. Buka https://tandurkarsa.github.io/qrcode/
2. Ketik URL tujuan (contoh: `https://tandurkarsa.github.io/qrcode/`)
3. QR langsung muncul di panel kanan
4. Cek bagian **"Isi QR (encoded)"** untuk memastikan URL yang tertanam sudah benar
5. Klik **PNG** atau **SVG** untuk mengunduh

### Menjalankan Secara Lokal

Karena murni client-side, kamu cukup:

```bash
git clone https://github.com/tandurkarsa/qrcode.git
cd qrcode
