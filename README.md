# TLX Translations Project

## Tentang Project Ini

Project ini bertujuan untuk menerjemahkan kontes-kontes lokal yang ada di TLX ke Bahasa Inggris.

Semua penerjemahan akan dilakukan pada *repository* ini. \
Semua orang dipersilakan untuk menambah terjemahan. Apabila Anda ingin berkontribusi, harap mengikuti Cara Kerja yang ada di bawah.

## Cara Kerja

1. Bikin [issue](https://github.com/prabowo02/tlx-translations/issues) untuk problemset yang ingin diterjemahkan. Judul issue adalah "Penerjemahan [nama-problemset]". Sebagai contoh: "Penerjemahan BNPCHS 2019 - Final". Deskripsi dari issue adalah judul-judul soal yang ada.

2. Penerjemah akan menerjemahkan soal-soal dalam bentuk **HTML**. Apabila format deskripsi Bahasa Indonesianya berbentuk pdf, maka terjemahan bahasa Inggrisnya tetap berbentuk **HTML**. Bisa saja terdapat lebih dari satu penerjemah untuk sebuah problemset, dan penerjemah tidak harus sama dengan yang orang yang membuka issue penerjemahan. Contoh HTML bisa dilihat dalam folder `contoh`.

3. Nama file terjemahan sebisa mungkin relevan (sebagai contoh: `bnpchs-2019-final-3-plus-1.html`) dan disimpan di dalam folder `translations`. Apabila sudah selesai diterjemahkan, buka [pull request](https://github.com/prabowo02/tlx-translations/pulls) dengan judul "Terjemahan [nama-problemset]: [judul-soal]". Sebagai contoh: "Terjemahan BNPCHS 2019 - Final: 3 Plus 1".

4. Setelah di-review, Pull Request akan dimerge oleh pemilik repository. Setelah semua problemset direview, maka ditunggu agar penerjemahannya dimasukkan ke TLX.

### Catatan

Beberapa catatan yang perlu diperhatikan:

- Setiap baris sebaiknya berisi paling banyak satu kalimat. Hal ini dilakukan untuk mempermudah review.
- Apabila Anda ingin menggunakan inline equation, gunakan `$$$`.
- Apabila ingin menambahkan gambar, gunakan tag html `<img src="render/nama_gambar.png" />` dan tambahkan `nama_gambar.png` ke dalam pull request yang sama.
- Tambahkan komentar judul soal bahasa Inggrisnya di paling atas `<!-- Title: English Title -->`.
- Nama kontributor akan ditulis pada repo ini di bagian Credits.

## Credits

- BNPCHS 2019 Final: [Edbert Geraldy Cangdinata](https://github.com/Berted), [Juan Carlo Vieri](https://github.com/juancarlovieri), [Maximillianus Utomo Quok](https://github.com/tzaph), [Steven Novaryo](https://github.com/stevennovaryo), [Vio Albert Ferdinand](https://github.com/VioAlbert).
- BNPCHS 2018 Penyisihan: Edbert Geraldy Cangdinata, Juan Carlo Vieri, Vio Albert Ferdinand
- BNPCHS 2018 Final: Steven Novaryo, Edbert Geraldy Cangdinata, Vio Albert Ferdinand
