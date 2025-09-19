# CodexBMY

CodexBMY ialah sebuah bahasa pengaturcaraan berasaskan **Bahasa Melayu** yang direka untuk pembelajaran, eksperimen, dan pembangunan sistem.
Ia bertujuan menjadi ekosistem penuh seperti Python tetapi menggunakan sintaks serta kata kunci dalam Bahasa Melayu.

---

## ✨ Ciri-ciri Utama
- Sintaks mudah difahami, menggunakan perkataan Melayu (contoh: `cetak`, `ubah`, `jika`, `selagi`).
- REPL (Read-Eval-Print Loop) interaktif.
- Menyokong pengendalian fungsi, kawalan aliran, dan ekspresi aritmetik.
- Modul asas (stdlib) seperti:
  - Matematik
  - String
  - Fail
  - Sistem
  - Rangkaian
  - Rawak
  - Waktu
- Boleh membaca fail `.bmy` dan menjalankannya terus melalui shell.

---

## 📂 Struktur Projek
```

codexbmy/
├── README.md
├── LICENSE
├── Makefile
├── include/       # Fail header (.h)
├── src/           # Kod sumber utama (.c)
├── examples/      # Contoh program CodexBMY
├── tests/         # Unit tests
├── bm\_stdlib/     # Standard Library CodexBMY
├── bm\_headers/    # Header untuk compiler & VM
├── compiler/      # Fail compiler (lexer, parser, AST, interpreter)
├── docs/          # Dokumentasi projek
└── build/         # Output binary & log

````

---

## 🚀 Cara Membina
Pastikan GCC atau Clang dipasang dalam sistem.

```bash
git clone https://github.com/xalifelabs/codexbmy.git
cd codexbmy
make
./build/codexbmy
````

---

## 📖 Contoh Kod `.bmy`

```bmy
ubah x = 10;
selagi (x > 0) {
    cetak("Nilai sekarang: ", x);
    ubah x = x - 1;
}
```

Output:

```
Nilai sekarang: 10
Nilai sekarang: 9
...
Nilai sekarang: 1
```

---

## 🎯 Matlamat Projek

* Menjadi bahasa pengaturcaraan pertama berasaskan Bahasa Melayu dengan ekosistem lengkap.
* Digunakan untuk pendidikan, penyelidikan, dan eksperimen membina sistem bahasa sendiri.
* Membuka peluang integrasi AI secara asli ke dalam bahasa pengaturcaraan.

---

## 🤝 Sumbangan

Sumbangan dialu-alukan!

1. Fork repo
2. Buat perubahan
3. Hantar pull request

Laporan pepijat boleh dibuat melalui tab **Issues**.

---

✍️ **Pencipta**: Muhammad Alif
📅 **Projek Bermula**: 2025
