# C6 · Jalur aman

Prototype untuk membantu penghuni kos menyalakan beberapa perangkat tanpa melewati batas daya kamar.

## Alur
1. **Kapasitas kamar:** pilih 900, 1300, atau 2200 VA. Ketuk kotak kuning untuk panduan cara mengecek VA.
2. **Pilih alat elektronik:** centang kipas, rice cooker, setrika, atau AC. Meteran berubah antara *Aman*, *Hampir batas*, dan *Melebihi batas*.
3. **Saran urutan:** total beban, batas perkiraan, dan saran perangkat mana yang ditunda.

## Aturan
- Batas perkiraan = VA × 0,8 (contoh: 1.300 × 0,8 = 1.040 W).
- Aman: di bawah 80% batas. Hampir batas: 80% sampai 100%. Melebihi batas: di atas 100%.
- Saran menunda dimulai dari perangkat berdaya terbesar sampai total beban di bawah batas.

## Menjalankan
Buka `index.html` di browser.
