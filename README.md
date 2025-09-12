# CodexBMY

CodexBMY ialah sebuah **bahasa pengaturcaraan berasaskan Bahasa Melayu** yang direka untuk pembelajaran, eksperimen, dan pembangunan sistem.  
Ia bertujuan menjadi ekosistem penuh seperti Python tetapi menggunakan sintaks serta kata kunci dalam Bahasa Melayu.

## ✨ Ciri-ciri Utama
- Sintaks mudah difahami, menggunakan perkataan Melayu (contoh: `cetak`, `ubah`, `jika`, `selagi`).
- REPL (Read-Eval-Print Loop) interaktif.
- Menyokong **pengendalian fungsi, kawalan aliran, dan ekspresi aritmetik**.
- Modul asas (stdlib) seperti:
  - Matematik
  - String
  - Fail
  - Sistem
  - Rangkaian
  - Rawak
  - Waktu
- Boleh membaca fail `.bmy` dan menjalankannya terus melalui shell.

## 📂 Struktur Projek
codexbmy/
├── README.md
├── LICENSE
├── Makefile
├── include/ # Fail header (.h)
├── src/ # Kod sumber utama (.c)
├── examples/ # Contoh program CodexBMY
├── tests/ # Unit tests
├── bm_stdlib/ # Standard Library CodexBMY
├── bm_headers/ # Header untuk compiler VM
├── compiler/ # Fail compiler dalam BMY
├── docs/ # Dokumentasi projek
└── build/ # Output binary & log

## 🚀 Cara Membina
1. Pastikan ada **GCC/Clang** di sistem.
2. Klon repositori:
   ```bash
   git clone https://github.com/xalifelabs/codexbmy.git
   cd codexbmy

3. Bina projek: make

4. Jalankan REPL: ./build/codexbmy


5. 📖 Contoh Kod bmy:

ubah x = 10;
selagi (x > 0) {
    cetak("Nilai sekarang: ", x);
    ubah x = x - 1;
}

🎯 Matlamat Projek

Menjadi bahasa pengaturcaraan pertama berasaskan Bahasa Melayu dengan ekosistem lengkap.

Digunakan untuk pendidikan, penyelidikan, dan eksperimen membina sistem bahasa sendiri.

Membuka peluang integrasi AI secara asli ke dalam bahasa pengaturcaraan.

🤝 Sumbangan

Sumbangan dialu-alukan!

Fork repo, buat perubahan, dan hantar pull request.

Laporan pepijat boleh dibuat melalui Issues.

✍️ Pencipta: Muhammad Alif
📅 Projek Bermula: 2025

