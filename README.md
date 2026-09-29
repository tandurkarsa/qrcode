# 🔳 QR Generator — Direct Link, Tanpa Redirect

QR code generator yang **menyimpan URL asli langsung ke dalam QR**, bukan shortlink atau halaman redirect. 100% berjalan di browser — tidak ada server, tidak ada tracking, tidak ada perantara.

![Preview](preview.png)

## ✨ Fitur

- 🔗 **Direct URL** — URL asli langsung di-encode, bukan shortlink
- ⚡ **Real-time preview** — QR berubah seketika saat URL diketik
- ✅ **Validasi URL** — deteksi otomatis URL valid/tidak
- 🎨 **Kustomisasi warna** — atur warna QR & background
- 📏 **Ukuran fleksibel** — 256px, 512px, 1024px, 2048px
- 🛡️ **Error correction level** — L / M / Q / H
- 📐 **Margin / quiet zone** yang bisa diatur
- ⬇️ **Download PNG & SVG** — SVG untuk cetak, PNG untuk digital
- 📋 **Copy URL** — sekaligus menampilkan string yang di-encode
- 🔒 **100% client-side** — tidak ada request ke server, tidak ada data yang dikirim

## 🚀 Demo

Coba langsung: **[https://tandurkarsa.github.io/qrcode/](https://tandurkarsa.github.io/qrcode/)**

## 🧠 Kenapa Direct, Bukan Redirect?

Sebagian besar QR generator online menggunakan **QR dinamis** yang isinya shortlink milik mereka. Saat di-scan, server mereka yang mengalihkan ke URL asli. Akibatnya:

- ❌ URL mati kalau langganan berhenti
- ❌ Ada limit scan
- ❌ Ada tracking & analitik
- ❌ Bergantung pada pihak ketiga

QR Generator ini kebal dari semua itu. Sekali generate, QR berlaku **selamanya** — tidak peduli apakah situs ini masih online atau tidak.

## 🛠️ Cara Pakai

### Online
1. Buka link demo di atas
2. Ketik URL tujuan
3. Klik **PNG** atau **SVG** untuk download

### Lokal
```bash
git clone https://tandurkarsa.github.io/qrcode/.git
cd [nama-repo]
# Buka index.html di browser
