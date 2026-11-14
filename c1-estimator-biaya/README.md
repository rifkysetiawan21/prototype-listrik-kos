# C1 · Estimator biaya listrik

Prototype untuk menghitung perkiraan tagihan listrik bulanan dari perangkat yang dipakai di kamar kos.

## Alur
1. **Pilih perangkat:** AC, rice cooker, setrika, kipas, dan perangkat lain (laptop, kulkas mini, dispenser, lampu LED).
2. **Atur durasi:** geser lama pakai per hari, biaya per perangkat langsung berubah.
3. **Hasil:** total perkiraan per bulan dan porsi tiap perangkat.
4. **Perbandingan penggunaan AC:** bandingkan 6, 8, dan 10 jam per hari beserta selisih total tagihan.

## Rumus
`biaya per bulan = daya (kW) × jam per hari × 30 × Rp 1.444,70`

## Catatan
- Setrika 30 menit per hari menghasilkan sekitar Rp 21.700, sedikit berbeda dari angka di sketsa awal (Rp 15 rb).
- Nilai awal: AC 8 jam, setrika 30 menit, rice cooker 1 jam.

## Menjalankan
Buka `index.html` di browser. Sumber font (Google Fonts) bersifat opsional; tanpa internet tampilan memakai font bawaan sistem.
