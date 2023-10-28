# Transjakarta-anaylisis
# Latar Belakang
Transjakarta, sistem Bus Rapid Transit (BRT) utama di Jakarta, melayani populasi kota yang padat dengan lalu lintas yang terkenal macet. 
Meskipun bertujuan mengurangi kemacetan dan meningkatkan aksesibilitas transportasi, salah satu tantangan utamanya adalah menangani kepadatan penumpang, terutama selama jam sibuk.
Kepadatan yang berlebihan bisa menurunkan kualitas perjalanan, meningkatkan waktu tempuh, dan mengurangi kepuasan penumpang, yang pada akhirnya berdampak pada penggunaan layanan.
# Pernyataan Masalah
Dalam konteks urban yang semakin berkembang, Transjakarta dihadapkan pada kebutuhan untuk mengelola kepadatan penumpang yang semakin meningkat. Pertanyaan penelitian yang penting termasuk:
- Bagaimana pola kepadatan penumpang berubah sepanjang hari atau antar rute?
- Apakah ada koridor atau jenis layanan (mis. reguler vs non-reguler) yang secara konsisten mengalami kepadatan tinggi?
# DataSet
1. transID: ID transaksi unik untuk setiap transaksi.
2. payCardID: Identifikasi utama pelanggan. Kartu yang digunakan pelanggan sebagai tiket masuk dan keluar.
3. payCardBank: Nama penerbit bank kartu pelanggan.
4. payCardName: Nama pelanggan yang terdapat dalam kartu.
5. payCardSex: Jenis kelamin pelanggan yang terdapat dalam kartu.
6. payCardBirthDate: Tahun kelahiran pelanggan.
7. corridorID: ID Koridor/Rute sebagai kunci untuk pengelompokan rute.
8. corridorName: Nama Koridor/Rute yang berisi Titik Awal dan Titik Akhir untuk setiap rute.
9. direction: 0 untuk Pergi, 1 untuk Kembali. Arah rute.
10. tapInStops: ID Titik Masuk (pintu masuk) untuk mengidentifikasi nama-nama halte.
11. tapInStopsName: Nama Titik Masuk (pintu masuk) tempat pelanggan mengetuk kartu.
12. tapInStopsLat: Garis lintang Titik Masuk (pintu masuk).
13. tapInStopsLon: Garis bujur Titik Masuk (pintu masuk).
14. stopStartSeq: Urutan dari halte-halte, halte pertama, halte kedua, dan seterusnya. Terkait dengan arah.
15. tapInTime: Waktu ketika pelanggan mengetuk kartu masuk. Tanggal dan waktu.
16. tapOutStops: ID Titik Keluar (pintu keluar) untuk mengidentifikasi nama-nama halte.
17. tapOutStopsName: Nama Titik Keluar (pintu keluar) tempat pelanggan mengetuk kartu.
18. tapOutStopsLat: Garis lintang Titik Keluar (pintu keluar).
19. tapOutStopsLon: Garis bujur Titik Keluar (pintu keluar).
20. stopEndSeq: Urutan dari halte-halte, halte pertama, halte kedua, dan seterusnya. Terkait dengan arah.
21. tapOutTime: Waktu ketika pelanggan mengetuk kartu keluar. Tanggal dan waktu.
22. payAmount: Jumlah yang dibayarkan oleh pelanggan. Beberapa gratis, beberapa tidak.
# Tableau
ini tampilan visual menggunakan tableau https://public.tableau.com/app/profile/sankya.sandhya.p/viz/CapstoneTransjakarta/Story1
