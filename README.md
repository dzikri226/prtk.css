# prtk.css
# M. Dzikri Hidayat
# Ti 22 a1
# 312210136
# langkah pratikum css
pertama buka VS Code maka tampilannya awal akan seperti ini. ![image](https://github.com/dzikri226/prtk.css/assets/122372727/2a5bb43b-8a34-4d5e-b0c2-96ce69cd4963)


Selanjutnya membuat dokumen HTML, pada bagaian title uabah menjadi CSS Dasar agar tampilan judul halaman akan berubah menjadi CSS Dasar. ![image](https://github.com/dzikri226/prtk.css/assets/122372727/88a467a3-af36-4a93-b4bf-6d98044a8e0a)


Lalu buat Kode didalam tag body seperti berikut. ![image](https://github.com/dzikri226/prtk.css/assets/122372727/3da277c9-f09c-4f65-8dda-551d384654ae)


Selanjutnya buka pada browser untuk melihat hasilnya. ![image](https://github.com/dzikri226/prtk.css/assets/122372727/291993b9-5ddf-4283-b5f1-2b27a2b1700c)


Kemudian mendeklarasikan CSS Internal, tambahkan deklarasi CSS internal pada bagian head lalu tambahkan style untuk membuat CSS internal. ![image](https://github.com/dzikri226/prtk.css/assets/122372727/4b6fcdf5-98e4-4525-8e7e-6327ddab2890)


Lalu save perubahan tadi terus kembali ke browser dan refresh untuk melihat hasilnya. ![image](https://github.com/dzikri226/prtk.css/assets/122372727/9ffdaf03-2598-4810-9a7f-fa8d4614f218)


Selanjutnya menambahkan Inline CSS, untuk melakukannya tambahkan deklarasi inline CSS pada tag <p> seperti ini. ![image](https://github.com/dzikri226/prtk.css/assets/122372727/94b7dd59-c7a5-4816-933c-c17ce2a550ae)


lalu save perubahan lagi terus kembali ke browser refresh dan lihat hasilnya. ![image](https://github.com/dzikri226/prtk.css/assets/122372727/22e58398-7781-4b27-a96e-a0a9242df19b)


Selanjutnya membuat CSS Eksternal, buat file baru terlebih dahulu dengan nama style_eksternal.css lalu buat deklarasi CSS seperti berikut. ![image](https://github.com/dzikri226/prtk.css/assets/122372727/30c5f038-6c0d-4bae-bc56-82e5428ab4d9)


Tambahkan tag <link> pada bagian head untuk menghubungkan style_eksternal.css yang sudah dibuat tadi. ![image](https://github.com/dzikri226/prtk.css/assets/122372727/08fc4d21-5de4-4181-95a4-05b2c7f89749)


Lalu save kembali ke browser refresh maka hasilnya seperti ini. ![image](https://github.com/dzikri226/prtk.css/assets/122372727/47262c73-43cc-436a-934a-930087f5334d)


Selanjutnya menambahkan CSS Selector menggunakan ID dan class selector pada file style_eksternal.css ![image](https://github.com/dzikri226/prtk.css/assets/122372727/32ce6b2e-a4e3-451b-90a3-22b825821dfb)


Lalu save lagi dan kembali ke browser dan refresh. ![image](https://github.com/dzikri226/prtk.css/assets/122372727/06005587-861d-4e63-8415-6b22e4044325)


Pertanyaan dan Tugas
1.Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
Yang saya lakukan disini menambahkan hayperlink pada dokumen HTML saya lalu menambahkan juga kode pada style CSS maka hasilnya seprti ini
![image](https://github.com/dzikri226/prtk.css/assets/122372727/96eeb5de-b665-4ac1-86a9-7ed0ffb5c492)


2.Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!

Pada pendeklarasian CSS elemen h1 maka yang akan berubah adalah seluruh tag h1 pada halam web berdeda dengan #intro h1 atau tag yang ada id maka itu saja yang akan berubah pada tampilan web.

3.Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!

Jika ada ketiga deklarasi css secara internal, css eksternal, dan inline css maka yang akan di tampilkan pada browser adalah deklarasi css inline karena memiliki prioritas tertinggi dalam aturan css cascade ![image](https://github.com/dzikri226/prtk.css/assets/122372727/00ed0505-745f-4287-9d97-c792e8bdc1b7)

4.Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! <p id="paragraf-1" class="text-paragraf">

Ketika dalam satu tag html terdapat id dan class didalamnya maka yang akan di tampilkan oleh browser adalah deklarasi css dengan id karena id menjadi prioritas tertinggi dalam aturan css cascade sedangkan class menjadi peioritas kedua setelah id
Ketika dalam satu tag html terdapat id dan class didalamnya maka yang akan di tampilkan oleh browser adalah deklarasi css dengan id karena id menjadi prioritas tertinggi dalam aturan css cascade sedangkan class menjadi peioritas kedua setelah id
contoh penulisan pada tag p di halaman HTML : ![image](https://github.com/dzikri226/prtk.css/assets/122372727/e8346590-8ab7-4f8a-b452-869b4f9f1def)

contoh penulisan CSS iinternal atau eksternal ![image](https://github.com/dzikri226/prtk.css/assets/122372727/0b297317-04fd-4fc8-aa80-87606d0d77bc)
