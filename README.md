# Prototype Listrik Kos

Tiga prototype interaktif untuk proyek kesadaran konsumsi listrik mahasiswa kos (SDG 12), mata kuliah Pengalaman Pengguna, Telkom University Surabaya. Dibuat dari sketsa konsep hasil metode 10 plus 10 (Tubes 07a).

| Prototype | Folder | Fokus |
|---|---|---|
| C1 Estimator biaya | [`c1-estimator-biaya`](c1-estimator-biaya/) | Perkiraan tagihan bulanan per perangkat |
| C3 QR remote AC | [`c3-qr-remote-ac`](c3-qr-remote-ac/) | Biaya AC per jam saat memilih suhu |
| C6 Jalur aman | [`c6-jalur-aman`](c6-jalur-aman/) | Beban perangkat vs batas daya kamar |

## Melihat prototype

Buka halaman GitHub Pages repo ini (lihat bagian hosting di bawah), atau buka file `index.html` di tiap folder langsung di browser. Tidak perlu instalasi apa pun.

## Hosting dengan GitHub Pages

1. Buka repo di GitHub, lalu **Settings** > **Pages**.
2. Pada **Build and deployment**, pilih **Deploy from a branch**.
3. Pilih branch `main` dan folder `/ (root)`, lalu **Save**.
4. Tunggu 1 sampai 2 menit. Alamatnya: `https://USERNAME.github.io/NAMA-REPO/`

## Asumsi yang dipakai

- Tarif listrik Rp 1.444,70 per kWh (golongan R-1), dihitung 30 hari per bulan.
- Batas aman daya = VA × 0,8.
- Tiap 1°C lebih dingin menambah sekitar 6% biaya AC (perkiraan, perlu diverifikasi).

Semua angka adalah perkiraan untuk keperluan prototype, bukan tagihan resmi.
