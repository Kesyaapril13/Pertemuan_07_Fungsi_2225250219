Pertemuan 07 — Fungsi Python

Nama: Kesya Nur Aprilliani
NIM: 2225250219
Kelas: 3E

1. Tujuan
Praktik ini bertujuan memahami penggunaan fungsi, parameter, return value, dan scope variabel dalam Python. Program dibuat secara modular agar setiap operasi matematika memiliki fungsi tersendiri, mudah diuji, dan dapat digunakan kembali.

2. Struktur Folder
pertemuan-07-fungsi-NIM/
├── README.md
├── .gitignore
├── latihan/
│   ├── 01_salam.py
│   ├── 02_luas_persegi_panjang.py
│   ├── 03_jumlah_n.py
│   ├── 04_statistik_sederhana.py
│   └── 05_scope.py
└── praktik/
    └── utilitas_matematika.py

3. Cara Menjalankan:

1. Buka folder proyek melalui VS Code.
2. Buka Terminal.
3. Jalankan perintah berikut dari folder utama proyek:
python praktik/utilitas_matematika.py
Jika sistem menggunakan perintah "python3", jalankan:
python3 praktik/utilitas_matematika.py
4. Pilih operasi sesuai menu.
5. Masukkan data yang diminta dan periksa hasilnya.

4. Struktur Fungsi
- "luas_persegi_panjang(p, l)": menghitung luas persegi panjang dan mengembalikan hasil dengan "return".
- "luas_segitiga(a, t)": menghitung luas segitiga dan mengembalikan hasil.
- "jumlah_n(n)": menghitung jumlah bilangan dari 1 sampai n menggunakan perulangan.
- "faktorial(n)": menghitung faktorial menggunakan perulangan.
- "tampilkan_menu()": menampilkan pilihan operasi kepada pengguna.

Program utama menggunakan seleksi "if-elif-else" untuk menjalankan fungsi sesuai pilihan pengguna. Validasi dilakukan agar nilai n pada fungsi jumlah dan faktorial merupakan bilangan bulat nonnegatif.

5. Hasil Pengujian
No.| Pengujian| Hasil yang Diharapkan| Status
1| Luas persegi panjang (8, 5)| 40| Sesuai
2| Luas segitiga (10, 6)| 30.0| Sesuai
3| Jumlah 1 sampai 10| 55| Sesuai
4| Faktorial 5| 120| Sesuai
5| Faktorial 0| 1| Sesuai

Catatan: status pengujian perlu dikonfirmasi setelah setiap test case dijalankan di VS Code.

6. Refleksi
Melalui praktik ini, saya memahami bahwa fungsi dapat memisahkan program menjadi bagian-bagian yang mempunyai tugas jelas. Parameter digunakan untuk menerima data, sedangkan "return" mengembalikan hasil perhitungan agar dapat digunakan oleh program utama. Scope membantu membedakan variabel lokal dan global. Pengujian dengan beberapa test case juga membantu memastikan hasil program sesuai dengan yang diharapkan.