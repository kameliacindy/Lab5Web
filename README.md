# Praktikum 5 : Javascript

## Pengenalan Javascript

 - Dalam HTML, kode Javascript disisipkan di antara tag `<script>` dan `</script>`.
 - Script dapat diletakkan pada tag `<head>` atau  `<body>` , atau dapat juga diletakkan pada keduanya. 
 - Javascript juga dapat diletakkan pada file external.
 
**Perhatikan contoh berikut ini.**

Persiapan membuat dokumen HTML seperti di bawah ini.

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/html_js.PNG)

Pada contoh di atas terdapat fungsi-fungsi yang **menampilkan output** seperti:

 - Fungsi  `document.write()`  menampilkan output ke dokumen HTML;
 - Fungsi  `console.log()`  menampilkan output ke console javascript.

**Dan hasilnya seperti di bawah ini.**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_html_js.PNG)

## Pemakaian Alert Pada Javascript

- Ada 4 cara untuk menampilkan output pada Javascript, salah satunya adalah dengan menggunakan fungsi `alert()`.
- **Fungsi `alert()`** merupakan sebuah fungsi yang akan menampikan jendela dialog.
- **Jendela dialog** merupakan jendela yang digunakan untuk berinteraksi dengan pengguna.
- Dialog `alert()` biasanya digunakan untuk menampilkan sebauh pesan peringatan atau informasi.
- Fungsi `alert()` berada dalam objek `window`.
 
**Contohnya seperti berikut.**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/alert.PNG)

**Hasilnya:**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_alert.PNG)

Dialog  `alert()`  memiliki satu perameter yang harus diberikan, yaitu: teks yang akan ditampilkan pada dialog.

Pada contoh di atas, kita memberikan teks  **"ini merupakan pesan untuk anda"**.

## Pemakaian Method dalam Objek

- **Objek** adalah sebuah variabel yang menyimpan nilai (properti) dan fungsi _(method)_.
- **_Method_** adalah perilaku dari objek (fungsi).
- Cara membuat method di dalam objek adalah dengan cara mengisi nilai (value) dengan sebuah fungsi.
- Cara mengakses method dari objek yaitu menggunakan tanda titik atau dot (`.`), lalu diikuti dengan nama method.

**Perhatikan contoh di bawah ini.**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/skrip_js.PNG)

Untuk method harus menggunakan tanda kurung. Ini menyatakan kalau kita ingin mengeksekusi fungsi.

**Hasilnya:**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_skrip.PNG)

## Pemakaian Prompt

- Pemakaian prompt juga merupakan salah satu macam jendela dialog pada Javascript.
- **Dialog `prompt()`** berfungsi untuk mengambil sebuah inputan dari pengguna.
- **Dialog `prompt()`** akan mengembalikan sebuah nilai string dari apa yang diinputkan oleh pengguna.

**Contoh:**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/prompt.PNG)

**Hasilnya:**

Kita disuruh menginput nama pada kolom field, seperti ini.

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_prompt1.PNG)

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_prompt2.PNG)

**Lalu, akan muncul teks seperti ini:**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_prompt3.PNG)

Dialog  `prompt()`  memiliki beberapa parameter yang harus diberikan:

1.  Teks yang akan ditampilkan pada form;
2.  Nilai default untuk field input.

Pada contoh di atas, kita memberikan nilai default-nya berupa string dengan tanda petik dan teks  `"masukkan nama anda"`.

Perbedaan dialaog `alert()` dan dialaog `prompt()` adalah waktu yang tepat dalam penggunaan `alert()` dan `prompt()`:

 - Saat kita hanya ingin **menampilkan informasi** saja, maka gunakan `alert()`.
 - Dan apabila kita ingin **mengambil data** teks dari pengguna, maka gunakan `prompt()`.

## Pemakaian Fungsi dan Cara Memanggilnya

 - Fungsi di dalam Javascript adalah sebuah objek. Karena memiliki properti dan juga _method_.
 - Ada 4 cara yang bisa kita lakukan untuk membuat fungsi di Javascript:

1.  Menggunakan cara biasa;
2.  Menggunakan ekspresi;
3.  Menggunakan tanda panah (`=>`);
4.  dan menggunakan  _Constructor_.

**Contohnya:**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/fungsi.PNG)

Contoh di atas merupakan cara membuat fungsi dengan menggunakan cara biasa.

#### Cara Memanggil Fungsi

 1. Memanggil fungsi dengan **menuliskan nama fungsinya**. Contohnya seperti kode di atas, berarti memanggil fungsi dengan nama fungsi `pesan()`.
 2. Memanggil fungsi **melalui atribut _event_ pada HTML**. Seperti contoh kode di atas, memanggil fungsi dengan *event* **`onload`** yang merupakan *event* ketika element atau halaman di buka.
 
Jadi, pada contoh di atas memanggil fungsi dengan cara nomer 2 (dua).

## Operasi Dasar Aritmatika pada Javascript

 - **Operator** adalah simbol yang digunakan untuk melakukan operasi pada suatu nilai dan variabel.
 - **Operator Aritmatika** merupakan operator yang biasa digunakan pada operasi perhitungan matematis.

#### Operator aritmatika terdiri dari:

 1. Penjumlahan, simbolnya **( + )** 
 2. Pengurangan, simbolnya **( - )**
 3. Perkalian, simbolnya **( * )**
 4. Pemangkatan, simbolnya **( ** )**
 5. Pembagian, simbolnya **( / )**
 6. Modulus, simbolnya **( % )**

**Contoh:**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/aritmatika.PNG)

Pada contoh kode di atas, menggunakan fungsi, dan untuk melakukan perhitungan aritmatika, kita menggunakan **variabel**. Variabel pada kode di atas adalah **val1 dan val2**.
Untuk **val1 = 9** dan **val2 = 4**.

Kemudian pada bagian tag `<body>`  terdapat *event* pada Javascript, yaitu **`onclick`** yang merupakan *event* jika sebuah element html di klik.

**Dan hasilnya:**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_aritmatika1.PNG)

Nah, pada gambar di atas dinamakan event **`onclick`** dengan value **"aritmethic**, apabila kita meng-klik `value` tersebut, maka akan muncul hasil seperti di bawah ini:

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_aritmatika2.PNG)

Coba perhatikan pada operator modulus **( % )**

**Operator modulus** adalah operator untuk menghitung sisa bagi.
Pada contoh di atas **9** dibagi **4** adalah **2**, maka sisanya adalah **1**.

## Seleksi Kondisi (*if - else*)

 - ***if - else*** merupakan salah satu bentuk percabangan pada Javascript.
 - **Percabangan  _if - else_**  merupakan percabangan yang memiliki  **dua blok pilihan**. Pilihan pertama untuk kondisi  **benar**, dan pilihan kedua untuk kondisi  **salah**  (_else_).

**Perhatikan contoh di bawah ini.**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/if_else.PNG)

Pada kode di atas menjunjukkan bahwa, pada kondisi ***if***, yang menginput nilai lebih dari sama dengan 60, maka akan lulus,  sedangkan pada kondisi ***else***, di bawah nilai 60 maka hasilnya tidak lulus.

**Dan ini contoh apabila kita menginput nilai 80**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_ifelse1.PNG)

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_ifelse2.PNG)

**Hasilnya akan lulus.**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_ifelse_lulus.PNG)

**Sedangkan apabila kita menginput nilai di bawah 60, maka:**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_ifelse_no_lulus1.PNG)

**hasilnya menunjukkan tidak lulus.**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_ifelse_no_lulus2.PNG)

## Penggunaan Operator switch

 - Salah satu bentuk peracabangan selain if - else yaitu **percabangan *swtich/case***.
 - **Percabangan _switch/case_** adalah bentuk lain dari percabangan _if/else/if_.
 - Pada percabangan switch kita dapat membuat blok kode (`case`) sebanyak yang diinginkan di dalam blok switch.
 - Setiap  `case`  harus diakhiri dengan  **`break`**. Khusus untuk  **`default`**, tidak perlu diakhiri dengan  `break`  karena dia terletak di bagian akhir.
 - Pemberian  `break`  **bertujuan** agar program berhenti mengecek  `case`  berikutnya saat sebuah  `case`  terpenuhi.

**Contohnya:**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/switch1.PNG)

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/switch2.PNG)

Pada kode program di atas, kita akan menginput nilai 1-5.

Dan ini kita menggunakan event `onclick`.

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_switch_1.PNG)

Kemudian apabila di klik, maka akan muncul tampilan seperti ini, misalnya kita akan menginput nilai 4.

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_switch_2.PNG)

**Maka, hasilnya akan seperti ini.**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_switch_3.PNG)

## Pembuatan Form Input

Pada pembuatan form input Javascript, hampir sama dengan pembuatan form pada HTML.

**Contohnya seperti berikut.**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/form_input.PNG)

Hasilnya, kita disuruh menginput pada form yang tersedia, seperti di bawah ini.

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_form_input.PNG)

## Pembuatan Form Button Pada objek document

 - **Objek `document`** adalah model dari dokumen HTML. Objek ini berisi kumpulan fungsi dan atribut berupa objek dari elemen HTML.
 - Di dalam objek `document`, terdapat fungsi-fungsi dan atribut yang bisa kita gunakan untuk memanipulasi dokumen HTML.

**Perhatikan contoh kode program berikut ini.**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/form_button.PNG)

Pada kode di atas, terdapat fungsi **`document.bgColor`** yang digunakan untuk memberikan warna pada background page, sedangkan fungsi **`document.fgColor`** digunakan untuk memberikan warna untuk tulisan pada page.

Selain itu, kode di atas merupakan kode untuk membuat sebuah form, dengan input `type = "button"`, dimana form tersebut menggunakan event Javascript, yaitu `onclick` yang apabila kita meng-klik `<value>` nya, maka akan berubah sesuai dengan  atribut yang diberikan pada fungsinya.

**Dan ini hasilnya *default*nya:**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_form_button.PNG)

Dan seperti ini tampilan apabila kita meng-klik tombol button **"Latar Belakang Hijau**.

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_form_button_hijau.PNG)

Tampilan **Latar Belakang Putih**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_form_button_putih.PNG)

Tampilan **"Teks Kuning"**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_form_button_kuning.PNG)

Tampilan **"Teks Biru**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_form_button_biru.PNG)


## HTML DOM

 - **DOM** merupakan singkatan dari  _Document Object Model_. Artinya, dokumen (HTML) yang dimodelkan dalam sebuah objek.
 - Objek dari dokumen ini menyediakan sekumpulan fungsi dan atribut/data yang bisa kita manfaatkan dalam membuat program Javascript. Inilah yang disebut **API**  _(Application Programming Interface)_.

**Perhatikan contoh berikut ini.**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/daftar_menu.PNG)

Pada contoh di atas merupakan sebuah program untuk membuat daftar menu makanan dengan menggunakan *checkbox*, yang apabila kita men-ceklist pada daftar menu tersebut, maka akan muncul total harga yang harus di bayar.

**Dan pada  kode di atas, terdapat beberapa fungsi:**

 1. fungsi `document.getElementById()` yang merupakan fungsi untuk memilih elemen berdasarkan atribut `id` 
 2. fungsi `parseInt` merupakan fungsi untuk mengubah String menjadi Integer atau mengubah kebilangan bulat. Artinya jika bilangan didalamnya mengandung desimal maka akan dikonversikan ke bilangan bulat.

**Dan hasilnya seperti ini.**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_daftar_menu1.PNG)

Misalnya kita men-ceklist menu makanan **"Ayam Goreng** dan **"Tempe Goreng** dengan masing-masing harga yang sudah ditentukan, maka akan muncul total harga yang harus dibayar, yaitu **Rp. 5.500**

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_daftar_menu2.PNG)


# Tugas Praktikum 5

Buat script untuk melakukan validasi pada isian form.

#### Jawaban:

#### Persiapan membuat dokumen HTML terlebih dahulu dan dilanjut  menambahkan kode seperti di bawah ini.

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/validasi.PNG)

#### Penjelasan kode

Di sini kita memerintahkan untuk menjalankan function `validasi()` saat form di submit. `onSubmit=”validasi()”`

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/val_1.PNG)

dimana function `validasi()` sudah kita buat untuk mengecek inputan.

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/val_2.PNG)

kita menangkap nilai value dari form input. dan memasukkannya ke dalam variabel.

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/val_3.PNG)

dan kemudian mengecek masing-masing variabel.

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/val_4.PNG)

Jika nama, email dan alamat di isi. atau tidak kosong. maka akan di kembalikan nilai TRUE pada form agar dapat di teruskan. jika tidak maka tampilkan pesan alert yang menampilkan “Anda harus mengisi data dengan lengkap !”.

#### Kemudian tambahkan CSS.

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/css_validasi.PNG)

#### Dan hasilnya seperti berikut ini.

![enter image description here](https://github.com/kameliacindy/Lab5Web/blob/main/img/ss_validasi.PNG)


Terimakasih, semoga bermanfaat...

Nama	: Kamelia Cindy Astuti

NIM	: 311910104

Kelas	: TI. 19. A. 1
