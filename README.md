# sm64-Bahasa-Indonesia

Membuat tampilan game **Super Mario 64** berbahasa Indonesia

ini akan menimpa file asli dari *sm64ex coop* sehingga dapat mengubah bahasanya. Lakukan hal ini untuk membuat gamenya berbahasa indonesia.
__________________________________________________


## Langkah-Langkah

Sebelum melakukan proses *Compile* atau kompilasi pada proses sebelumnya, untuk membuat tampilan game menjadi berbahasa Indonesia. kamu bisa melakukan hal ini.

Klon repositori
```
git clone https://github.com/Loople/sm64-BIndonesia.git
```

Membuka folder dari *termux*
```
cd sm64-BIndonesia
```
  

Menyalin file ke folder *`sm64ex coop`*
```
cp -r  sm64ex-coop ~
```

masuk ke *`sm64ex-coop`*
```
cd ../sm64ex-coop
```
__________________________________________________

**Kompilasi**

Setelah sebelumnya selesai sekarang waktunya mengkompilasi gamenya. Kamu dapa menggunakan dua perintah, namun kau harus memilih salah satu

Pertama:
```
make
```

atau yang ke dua:
```
make -j$(nproc)
```
__________________________________________________

Jika kamu telah melakukan kompilasi sebelumnya dan meninggalkan hasilnya begitusaja ataupun
kedua perintah itu tidak berhasil.

Kamu perlu melakukan ini.
```
make clean
```

ini akan membuat hasil kompilasi sebelumnya terhapus.
__________________________________________________
