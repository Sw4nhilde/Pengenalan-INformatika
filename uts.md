## 1.1 Latar Belakang

Di masa modern ini kita sebagai manusia sudah semakin terbiasa dengan gaya hidup praktis dan cepat, gaya hidup ini tercermin dari berbagai pilihan yang kita lakukan. Seperti belanja melalui E-commerce, memesan makanan melalui aplikasi online, bahkan tersedia juga aplikasi ojek online (Ex: GoJek, Grab, Maxim, Uber, dll) yang di aplikasi tersebut ada fitur yang memungkinkan kita untuk
melakukan kegiatan pembelian, transaksi, dan penjualan dari rumah. Tanpa harus bertatap muka (Ex: belanja bulanan, pembayaran E-commerce, pembelian/penjualan makanan, dll).

Salah satu contoh dari gaya hidup modern yang praktis dan cepat ini adalah cara kita mencuci pakaian, yang awalnya bermula dengan enggunakan tangan kita, lalu diciptakannya mesin cuci yang sangatb memudahkan kita dalam proses mencuci baju. Sampai pada akhirnya terciptalah bisnis Laundry, dimana bisnis Laundry ini menawarkan jasa pencucian dan penyetrikaan baju. Jadi kita tidak usah pusing
mencuci dan menyetrika baju kita sendiri, karena sekarang dengan menggunakan bisnis Laundry ini kita cukup membayar biaya yang diperlukan untuk jasa mereka dan bisa tenang tentang urusan mencuci baju dan menyetrikanya.

Dengan melihat perkembangan dan kemajuan dari bisnis Laundry ini di negara kita indonesia, ada celah kesempatan yang bisa diambil. Yaitu, walaupun sudah banyak bisnis Laundry ini yang berdiri dan dan mendapati sukses/perhatian di kalangan orang Indonesia, masih belum ada aplikasi yang bisa memudahkan kita untuk memesan jasa Laundry tanpa harus bertatap muka. Ini menjadi alasan utama kenapa saya mencoba untuk membuat dan mengembangkan aplikasi yang dapat memudahkan kita dalam memesan jasa Laundry.

## 1.2. Deksripsi Teknologi Informasi

Aplikasi ini saya buat dan kembangkan dengan harapan dapat membantu/memudahkan masyarakat dalam memesan jasa Laundry, tidak semua orang mau dan mampu mencuci serta menyetrika bajunya sendiri dengan alasan tersendiri (ex: Tidak punya mesin cuci dan setrika, fisik tidak mumpuni, mencari air bersih susah, dll). 

Dengan aplikasi ini saya berharap bisa membantu masyarakat baik dari pihak pelanggan dan pihak pengusaha, pihak pelanggan akan lebih terbantu ketika ingin mencuci bajunya dan pihak pengusaha bisa lebih mengembangkan usahanya karena bisa medai jangkauannya bertambah. Di aplikasi ini pelanggan bisa menentukan tempat laundry mana yang mereka inginkan dan memesan keperluan mereka dengan bebas mulai dari berapa 
berat total pakaian yang ingin mereka laundry, seberapa cepat mereka menginginkannya kembali, mau diapakan pakaiannya mereka (ex: Cuci & Sterika, cuci kering, dll).

## 1.3. Branding

Merk : yuuLAUNDRY

Tagline : Cuci supaya hepi no ribet-ribet

Campaign : Membuat aplikasi yang memudahkan dan membantu mendorong jasa laundry

Target User : 
  - Usia 13+
  - Seseorang yang jauh dari lokasi laundry
  - Seseorang yang memiliki halangan fisik ketika mencuci bajunya
  - Seseorang yang ingin meluaskan usaha/bisnisnya
  - Seseorang yang ingin sibuk/tidak punya waktu dan tidak bisa mencuci bajunya
  - Seseorang yang alat mencuci bajunya sedang rusak
  - Seseorang yang sedang malas mencuci bajunya
    
User experience theme :
  - Mudah
  - Sederhana
  - Enak dilihat
  - Mudah untuk lansia
  
## 2. User Story

Sebagai   | Saya ingin bisa        | Sehingga                                                  | Prioritas
----------|------------------------|---------------------------------------------------------|-------------
Pelanggan | Memesan jasa laundry   | Mencuci pakaian saya dengan praktis dan tidak capek     | ⭐⭐⭐⭐⭐
Pelanggan | Mengatur pesanan saya  | Pakaian saya dicuci sesuai dengan kemauan saya          | ⭐⭐⭐⭐⭐
Pelanggan | Memilih tempat laundry | Agar pakaian saya dicuci di tempat yang sudah dipercaya | ⭐⭐⭐⭐
Pengusaha | Memepromosikan usaha   | Meraup keuntungan lebih banyak                          | ⭐⭐⭐
Pengusaha | Membuat toko di app    | Memulai kegiatan promosi dan menambah jangakuan         | ⭐⭐⭐⭐⭐
Driver    | Mendaftar jadi mitra   | Bisa dipanggil oleh pelanggan yang memesan              | ⭐⭐⭐⭐⭐
Driver    | Akses aplikasi peta    | Mengetahui lokasi pelanggan dan laundry yang dipilih    | ⭐⭐⭐⭐



## 3. Struktur Data

---
title: Cuci & Setrika reguler 6kg
---
erDiagram
    PELANGGAN ||--o{ Cuci & Setrika reguler : places
    ORDER ||--|{ Baju 6kg : contains
    PELANGGAN }|..|{ alamat pelanggan : uses



erDiagram
    DRIVER ||--o{ PESANAN PELANGGAN : places
    DRIVER {
        string pelanggan
        string pesanan
        string alamat pelanggam
    }
    PESANAN PELANGGAN ||--|{ PENGUSAHA : contains
    PESANAN PELANGGAN {
        int 6kg
        string alamat laundry
    }
    PENGUSAHA {
        string Cuci & Setrika reguler
        int 6kg
        float harga untuk cuci setrika 6kg
    }

## 4. Arsitektur Sistem

flowchart TD
    DATABASE <--> BACKEND <--> APLIKASI IOS & ANDROID

## 5. Teknologi, Library, dan Framework

React Native

## 6. Desain User Experience dan User Interface

Bisa load image 
![Contoh](https://fastly.picsum.photos/id/318/536/354.jpg?hmac=Ixy-wle80nudIR_cmnF1iY2y6rMUH7_9sk-BP1fTpM8)

## 7. Demonstrasi Video

Link youtube nya

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini
