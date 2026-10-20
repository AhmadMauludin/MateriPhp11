# Aturan Penulisan Sintaks PHP

1. Tag Dasar PHP
Skrip PHP diawali dengan tag `<?php` dan diakhiri dengan `?>`. File yang berisi kode PHP harus disimpan dengan ekstensi `.php`.
```
   <?php
   // Kode PHP ditulis di dalam sini
   echo "Hello, World!";
   ?>
```

2. Karakter Penutup (Semicolon)
Setiap perintah atau instruksi dalam PHP wajib diakhiri dengan tanda titik koma (;).
```
echo "Baris pertama";
echo "Baris kedua";
```

3. Sensitivitas Huruf Besar/Kecil (Case Sensitivity)
 * Tidak Peka (Case-Insensitive): Kata kunci (keywords) bawaan PHP seperti if, else, while, echo, serta nama fungsi dan kelas tidak membedakan huruf besar dan kecil.
```
ECHO "Hello";
echo "Hello";
EcHo "Hello"; // Ketiganya menghasilkan output yang sama
```

 * Peka (Case-Sensitive): Nama variabel sangat membedakan huruf besar dan kecil.
   $color = "merah";
```
echo $color; // Berhasil
echo $COLOR; // Error atau undefined variable
```

4. Penulisan Variabel
Variabel digunakan untuk menyimpan data dan harus mengikuti aturan berikut:
 * Wajib diawali dengan tanda dolar ($).
 * Karakter pertama setelah $ harus berupa huruf atau underscore (_).
 * Tidak boleh diawali dengan angka.
 * Hanya boleh berisi karakter alfanumerik dan underscore (a-z, A-Z, 0-9, dan _).
```
$nama = "John";     // Valid
$_umur = 25;       // Valid
//$1nilai = 100;   // TIDAK VALID (diawali angka)
```
5. Komentar dalam PHP
Komentar digunakan untuk memberi catatan pada kode dan tidak akan dieksekusi oleh server.
```
// Ini adalah komentar satu baris`
```
atau
`# Ini juga komentar satu baris (style Unix/Perl)`
```
/*
  Ini adalah komentar
  beberapa baris (multi-line)
*/
```
6. Penggabungan Teks (Concatenation)
Untuk menggabungkan dua string atau variabel dalam PHP, gunakan operator titik (.).
```
$nama_depan = "Budi";
$nama_belakang = "Santoso";
echo $nama_depan . " " . $nama_belakang; // Output: Budi Santoso`
```

