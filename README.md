# PROGRAM-KALKULATOR-NILAI-MAHASISWA-1
Program ini digunakan untuk menghitung nilai akhir mahasiswa berdasarkan nilai:
Tugas (30%)
UTS (30%)
UAS (40%)

Setelah nilai akhir dihitung, program juga akan menentukan nilai huruf
(A, B, C, D, atau E) sesuai dengan rentang nilai berikut:

A : 85 – 100
B : 70 – 84
C : 55 – 69
D : 40 – 54
E : < 40

📂 Struktur Program
--------------------------------------------------
1. Fungsi `hitung_nilai_akhir(tugas, uts, uas)`
   → Menghitung dan mengembalikan nilai akhir mahasiswa.

2. Fungsi `konversi_nilai(nilai_akhir)`
   → Mengembalikan huruf nilai berdasarkan nilai akhir.

3. Fungsi `main()`
   → Meminta input dari pengguna, memanggil dua fungsi di atas,
     dan menampilkan hasil akhir ke layar.

📊 Contoh Output
--------------------------------------------------
Masukkan nilai Tugas : 85
Masukkan nilai UTS   : 70
Masukkan nilai UAS   : 90

===== Hasil nilai Mahasiswa =====
Nilai Tugas : 85
Nilai UTS   : 70
Nilai UAS   : 90
---------------------------------
Nilai Akhir : 81.5
Grade       : B
Keterangan  : LULUS

▶️ Cara Menjalankan Program
--------------------------------------------------
1. Pastikan Python sudah terpasang di komputer Anda (versi 3.7 ke atas).
2. Simpan file program dengan nama: `kalkulator_nilai.py`
3. Jalankan program melalui terminal atau command prompt:

       python kalkulator_nilai.py
   
5. Masukkan nilai tugas, UTS, dan UAS sesuai instruksi di layar.

