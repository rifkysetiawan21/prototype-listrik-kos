# C3 · QR di remote AC

Prototype untuk memperlihatkan biaya AC per jam tepat saat pengguna memegang remote, sebelum AC dinyalakan.

## Alur
1. **Remote AC:** atur suhu dengan tombol + dan −, lalu ketuk **Pindai QR**.
2. **Informasi:** biaya per jam dan per 8 jam sesuai suhu. Pilihan **Saran ahli 24–26°C**, **Coba kipas dulu**, atau **Lanjut nyalakan AC**.
3. **Setelah pemakaian:** simulasi lama AC menyala (geser 1 sampai 12 jam), biaya hari itu, dan proyeksi bila dipakai tiap hari.

## Asumsi
- Biaya dasar AC 1 PK pada 25°C: ≈ Rp 1.150 per jam.
- Tiap 1°C lebih dingin menambah sekitar 6% biaya. Angka ini perkiraan dan perlu diganti dengan sumber yang kelompok gunakan.
- Kipas 50 W ≈ Rp 72 per jam.
- QR pada prototype hanya ilustrasi dan belum memindai apa pun.

## Menjalankan
Buka `index.html` di browser.
