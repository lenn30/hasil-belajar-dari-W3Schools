# Pengantar HTML 
### Apa itu HTML??  
HTML (Hyper Text Markup Language) adalah bahasa markup standar untuk membuat dan mengatur struktur halaman web. HTML terdiri dari elemen-elemen yang memberi tahu browser cara menampilkan konten, seperti judul, paragraf, dan tautan.

### Elemen HTML 
Elemen HTML didefinisikan oleh tag awal, beberapa konten, dan tag akhir:
< tagname > Konten ada di sini... < /tagname >
Elemen HTML adalah segalanya dari tag awal hingga tag akhir 
- `<!DOCTYPE html>` menandakan bahwa dokumen menggunakan HTML5.  
- `<html>` adalah elemen utama yang membungkus seluruh halaman HTML.  
- `<head>` berisi informasi meta, seperti judul halaman.  
- `<title>` menentukan judul yang muncul di tab browser.  
- `<body>` berisi semua konten yang terlihat, seperti teks, gambar, dan tautan.  
- `<h1>` digunakan untuk judul besar.  
- `<p>` digunakan untuk paragraf.

  # Editor HTML
  ### Cara Membuat Halaman HTML Sederhana
1. Buka Editor Teks
     * Windows: Buka Notepad melalui menu Start atau ketik "Notepad" di pencarian.
     * Mac: Buka TextEdit melalui Finder > Aplikasi > TextEdit, lalu ubah ke mode "Teks Biasa" di Preferensi.
2. Tulis Kode HTML
   * Salin atau ketik kode

3. Simpan File
   * Pilih File > Simpan sebagai
   * Simpan dengan nama index.htm
   * Pilih UTF-8 sebagai pengkodean
4. Coba di Editor Online
   * Gunakan editor online seperti W3Schools untuk mengedit dan melihat hasil langsung.

  # Contoh Dasar HTML 
  ### Deklarasi <!DOCTYPE>
Deklarasi tersebut <!DOCTYPE>mewakili jenis dokumen, dan membantu browser menampilkan halaman web dengan benar
Itu hanya boleh muncul satu kali, di bagian atas halaman (sebelum tag HTML apa pun)
Deklarasi <!DOCTYPE>tidak peka huruf besar/kecil
Deklarasi <!DOCTYPE>untuk HTML5 adalah: <!DOCTYPE html> 

### Judul HTML 
Judul HTML didefinisikan dengan tag <h1> <h6>

### Paragraf HTML 
Paragraf HTML didefinisikan dengan <p>tag

### Tautan HTML 
Tautan HTML didefinisikan dengan <a>tag
Tujuan tautan ditetapkan dalam hrefatribut
Atribut digunakan untuk memberikan informasi tambahan tentang elemen HTML.

### Gambar HTML 
Gambar HTML didefinisikan dengan <img>tag.
File sumber ( src), teks alternatif ( alt), width, dan height disediakan. 


### Cara melihat Sumber HTML 
1. Melihat Kode Sumber
   * Tekan CTRL + U di halaman web.
   * Atau klik kanan di halaman, lalu pilih "Lihat Sumber Halaman".
   * Tab baru akan terbuka dengan kode HTML halaman tersebut.
2. Memeriksa Elemen HTML
   * Klik kanan pada elemen atau area kosong.
   * Pilih "Periksa" (Inspect) untuk melihat HTML dan CSS yang digunakan.
   * Anda juga bisa mengedit HTML atau CSS langsung di panel yang terbuka.


  ## Elemen HTML 
  Elemen HTML didefinisikan oleh tag pembuka, konten, dan tag penutup. Contohnya: `<h1>Judul Pertama Saya</h1>` dan `<p>Paragraf pertama saya.</p>`.
  Elemen-elemen ini dapat bersarang, artinya satu elemen dapat berisi elemen lain. Misalnya, dalam struktur berikut:
```html
<!DOCTYPE html>
<html>
<body>
<h1>Judul Pertama Saya</h1>
<p>Paragraf pertama saya.</p>
</body>
</html>
```


* `<html>` adalah elemen akar yang mencakup seluruh dokumen, `<body>` berisi konten yang ditampilkan, `<h1>` mendefinisikan judul, dan `<p>` mendefinisikan paragraf.
* Beberapa elemen HTML tidak memiliki konten atau tag penutup dan disebut elemen kosong, seperti `<br>` yang digunakan untuk membuat baris baru.
* Meskipun HTML tidak peka huruf besar-kecil, disarankan untuk menggunakan tag huruf kecil. Misalnya, `<p>` dan `<P>` dianggap sama, tetapi penggunaan huruf kecil lebih direkomendasikan.

## Atribut HTML 
Atribut HTML adalah informasi tambahan yang ditambahkan ke elemen HTML untuk memberikan karakteristik atau perilaku tertentu. Berikut adalah beberapa poin penting mengenai atribut HTML:
  * Penyertaan Atribut: Semua elemen HTML dapat memiliki atribut yang ditulis dalam tag pembuka elemen tersebut. Atribut biasanya terdiri dari pasangan nama dan nilai, seperti name="value".
  * Contoh Atribut Umum:
    * href: Digunakan dalam tag <a> untuk menentukan URL tujuan dari sebuah tautan.
    * src: Digunakan dalam tag <img> untuk menentukan sumber gambar yang akan ditampilkan.
    * alt: Digunakan dalam tag <img> untuk memberikan teks alternatif jika gambar tidak dapat ditampilkan.
    * style: Digunakan untuk menambahkan gaya CSS langsung pada elemen.
    * lang: Digunakan dalam tag <html> untuk mendeklarasikan bahasa dari halaman web.
    * title: Memberikan informasi tambahan yang biasanya ditampilkan sebagai tooltip saat kursor diarahkan ke elemen tersebut.
* Penulisan Atribut:
    * Huruf Kecil: Meskipun HTML tidak peka huruf besar-kecil, disarankan untuk menulis nama atribut dalam huruf kecil.
    * Tanda Kutip: Nilai atribut sebaiknya ditulis dengan tanda kutip, terutama jika mengandung spasi atau karakter khusus.
 
## Heading HTML 
* Tag heading HTML, digunakan untuk menentukan judul atau subjudul pada halaman web. h1 menandakan heading paling penting, sedangkan h6 menandakan heading dengan kepentingan paling rendah.
* Secara default, browser menambahkan spasi (margin) sebelum dan sesudah heading. Penggunaan heading yang tepat membantu mesin pencari mengindeks struktur dan konten halaman web Anda, serta memudahkan pengguna dalam menavigasi isi halaman. Disarankan untuk menggunakan h1 untuk judul utama, diikuti oleh h2 untuk subjudul, dan seterusnya. Hindari menggunakan heading hanya untuk membuat teks besar atau tebal; gunakan heading sesuai fungsinya untuk menandai struktur dokumen. 
* Secara default, browser menambahkan spasi (margin) sebelum dan sesudah heading. Penggunaan heading yang tepat membantu mesin pencari mengindeks struktur dan konten halaman web Anda, serta memudahkan pengguna dalam menavigasi isi halaman. Disarankan untuk menggunakan h1 untuk judul utama, diikuti oleh h2 untuk subjudul, dan seterusnya. Hindari menggunakan heading hanya untuk membuat teks besar atau tebal; gunakan heading sesuai fungsinya untuk menandai struktur dokumen. 

## Paragraf HTML 
* Dalam HTML, elemen p digunakan untuk mendefinisikan sebuah paragraf. Setiap paragraf dimulai pada baris baru, dan browser secara otomatis menambahkan spasi sebelum dan sesudahnya.
* Perlu diperhatikan bahwa HTML mengabaikan spasi ekstra dan baris baru dalam kode sumber. Misalnya, menambahkan banyak spasi atau baris baru dalam kode HTML tidak akan mempengaruhi tampilan paragraf di browser. 
* Untuk menambahkan garis horizontal yang memisahkan konten, Anda dapat menggunakan elemen hr. Elemen ini tidak memerlukan tag penutup.
* Untuk menampilkan teks dengan format yang persis seperti di kode sumber, termasuk spasi dan baris baru, gunakan elemen pre. Teks di dalam elemen pre akan ditampilkan dengan font lebar tetap dan mempertahankan format aslinya.

## Gaya HTML 
* Atribut style dalam HTML digunakan untuk menambahkan gaya langsung pada elemen, seperti warna, font, ukuran, dan lainnya. 
* Beberapa properti CSS yang sering digunakan dalam atribut style meliputi:
    * background-color: Menentukan warna latar belakang elemen.  <body style="background-color:powderblue;">
    * color: Menentukan warna teks.   <h1 style="color:blue;">Ini adalah heading</h1>
    * font-family: Menentukan jenis font yang digunakan.   <p style="font-family:verdana;">Ini adalah paragraf dengan font Verdana.</p>
    * font-size: Menentukan ukuran teks.   <h1 style="font-size:300%;">Ini adalah heading besar</h1>
    * text-align: Menentukan perataan teks secara horizontal.   <p style="text-align:center;">Teks ini diratakan ke tengah.</p>

## Format Teks HTML 
Dalam HTML, terdapat beberapa elemen yang digunakan untuk memformat teks agar memiliki makna atau penekanan khusus. Berikut adalah elemen-elemen tersebut beserta fungsinya: 
* b : Menampilkan teks dengan huruf tebal tanpa memberikan arti penting tambahan.
* strong : Menandai teks yang penting, biasanya ditampilkan dengan huruf tebal.
* i : Menampilkan teks dengan huruf miring tanpa penekanan khusus, sering digunakan untuk istilah teknis atau kata dalam bahasa asing.
* em : Menandai teks yang harus diberi penekanan, biasanya ditampilkan dengan huruf miring.
* mark : Menyoroti atau menandai teks yang dianggap penting atau relevan.
* small : Menampilkan teks dengan ukuran lebih kecil.
* del : Menandai teks yang dihapus atau tidak lagi relevan, biasanya ditampilkan dengan garis tengah.
* ins : Menandai teks yang baru ditambahkan atau dimasukkan, biasanya ditampilkan dengan garis bawah.
* sub : Menampilkan teks sebagai subskrip, yaitu teks yang ditulis lebih rendah dari teks normal, sering digunakan dalam rumus kimia.
* sup : Menampilkan teks sebagai superskrip, yaitu teks yang ditulis lebih tinggi dari teks normal, sering digunakan untuk penomoran pangkat atau catatan kaki.


## Elemen Kutipan dan Sitasi HTML 
Dalam HTML, terdapat beberapa elemen yang digunakan untuk menandai kutipan dan informasi terkait:
* blockquote>: Digunakan untuk mendefinisikan bagian yang dikutip dari sumber lain. Browser biasanya menampilkan elemen ini dengan indentasi.
* q>: Digunakan untuk mendefinisikan kutipan singkat dalam baris. Browser biasanya menambahkan tanda kutip di sekitar teks.
* abbr>: Digunakan untuk mendefinisikan singkatan atau akronim. Atribut title dapat digunakan untuk memberikan deskripsi lengkap saat pengguna mengarahkan kursor ke singkatan tersebut.
* address>: Digunakan untuk mendefinisikan informasi kontak penulis atau pemilik dokumen atau artikel. Teks dalam elemen ini biasanya ditampilkan dalam huruf miring, dan browser akan menambahkan baris baru sebelum dan sesudah elemen ini.
* cite>: Digunakan untuk mendefinisikan judul karya kreatif (misalnya, buku, puisi, lagu, film, lukisan, patung, dll.). Teks dalam elemen ini biasanya ditampilkan dalam huruf miring.
* bdo>: Singkatan dari "Bi-Directional Override", digunakan untuk menimpa arah teks saat ini.

Penggunaan elemen-elemen ini membantu memberikan struktur dan makna tambahan pada konten HTML, yang dapat meningkatkan aksesibilitas dan pemahaman bagi pengguna dan mesin pencari. 

## Komentar HTML 
* Dalam HTML, komentar digunakan untuk menambahkan catatan atau keterangan dalam kode sumber yang tidak akan ditampilkan oleh browser. Komentar membantu mendokumentasikan kode dan memudahkan pemeliharaan di masa mendatang.
* Sintaks : <!-- Tulis komentar Anda di sini -->
* Penggunaan komentar sangat berguna untuk mendokumentasikan kode, memberikan penjelasan, atau menonaktifkan sementara bagian kode saat debugging.

## Warna HTML 
Dalam HTML, warna dapat ditentukan menggunakan beberapa metode:
* Nama Warna: Menggunakan nama-nama warna standar yang telah ditentukan.
* Nilai Heksadesimal (HEX): Menggunakan kode heksadesimal untuk mewakili warna.
* Nilai RGB: Menentukan warna berdasarkan komposisi warna merah (Red), hijau (Green), dan biru (Blue).
* Nilai RGBA: Sama seperti RGB, namun dengan tambahan komponen alpha untuk menentukan tingkat transparansi.
* Nilai HSL: Menentukan warna berdasarkan Hue (corak warna), Saturation (kejenuhan), dan Lightness (kecerahan).
* Nilai HSLA: Sama seperti HSL, namun dengan tambahan komponen alpha untuk transparansi.

## CSS HTML 
CSS (Cascading Style Sheets) adalah bahasa yang digunakan untuk mendesain tampilan elemen-elemen HTML di berbagai media. Dengan CSS, Anda dapat mengontrol layout dari beberapa halaman web sekaligus, sehingga menghemat banyak pekerjaan. 
Ada tiga cara untuk menambahkan CSS ke dalam elemen HTML: 
*  Inline CSS: Menggunakan atribut style langsung pada elemen HTML untuk menerapkan gaya khusus pada elemen tersebut.
*  Internal CSS: Mendefinisikan gaya dalam elemen style> yang ditempatkan di bagian head> dari halaman HTML.
*  External CSS: Menggunakan file CSS eksternal yang terpisah, yang dihubungkan ke halaman HTML melalui elemen link> di bagian head>.
Metode yang paling umum adalah menggunakan file CSS eksternal, karena memungkinkan pengendalian tampilan dari beberapa halaman web sekaligus.

## Tautan HTML 
Dalam HTML, tautan atau hyperlink memungkinkan pengguna untuk berpindah dari satu halaman ke halaman lain atau ke bagian tertentu dalam halaman yang sama. Tautan didefinisikan menggunakan elemen <a>, dengan atribut href yang menunjukkan tujuan tautan.
### Atribut Target 
Atribut target menentukan di mana dokumen yang ditautkan akan dibuka. Nilai umum untuk atribut ini meliputi:
* _self: Membuka tautan di jendela atau tab yang sama (nilai default).
* _blank: Membuka tautan di jendela atau tab baru.
* _parent: Membuka tautan di frame induk.
* _top: Membuka tautan di seluruh jendela browser, menghapus semua frame.
### URL Absolut vs. Relatif
* URL Absolut: Menunjukkan alamat web lengkap, termasuk protokol dan nama domain.
* URL Relatif: Menunjukkan alamat yang relatif terhadap lokasi halaman saat ini.
### Menggunakan Gambar sebagai Tautan:
Gambar dapat digunakan sebagai tautan dengan menempatkan elemen img> di dalam elemen a>.
### Tautan ke Alamat Email:
Untuk membuat tautan yang membuka program email pengguna dengan alamat tujuan yang sudah terisi, gunakan skema mailto: dalam atribut href.
### Tombol sebagai Tautan:
Untuk menggunakan tombol sebagai tautan, Anda dapat menambahkan kode JavaScript pada atribut onclick yang mengarahkan pengguna ke URL tertentu.
### Atribut title:
Atribut title memberikan informasi tambahan tentang tautan, yang biasanya ditampilkan sebagai tooltip saat pengguna mengarahkan kursor ke tautan tersebut.

## Gambar HTML 
Dalam HTML, gambar ditampilkan menggunakan elemen img>, yang merupakan elemen kosong tanpa tag penutup. Elemen ini memiliki beberapa atribut penting yang mengatur sumber dan tampilan gambar.
### Atribut Utama dalam Elemen 
* src (source): Menentukan URL atau path dari gambar yang akan ditampilkan.
* alt (alternate text): Menyediakan teks alternatif yang ditampilkan jika gambar tidak dapat dimuat. Teks ini juga membantu aksesibilitas bagi pengguna dengan keterbatasan penglihatan.
* width dan height: Menentukan lebar dan tinggi gambar dalam piksel.

## Ikon HTML 
* Favicon adalah gambar kecil yang ditampilkan di sebelah judul halaman pada tab browser. Untuk menambahkan favicon ke situs web Anda, simpan gambar favicon di direktori root server Anda atau dalam folder seperti "images". Nama umum untuk favicon adalah "favicon.ico". Kemudian, tambahkan elemen link> di dalam bagian <head> pada file HTML Anda, setelah elemen title>.
* Setelah menyimpan dan memuat ulang file HTML tersebut di browser, favicon Anda akan muncul di sebelah kiri judul halaman pada tab browser. 

## Judul Halaman HTML 
Setiap halaman web harus memiliki judul yang menggambarkan isi halaman tersebut. Judul halaman ditentukan menggunakan elemen title> yang ditempatkan di dalam bagian head> dari dokumen HTML.

### Pentingnya Judul Halaman 
* SEO (Search Engine Optimization): Judul halaman digunakan oleh mesin pencari untuk menentukan urutan halaman dalam hasil pencarian. Judul yang jelas dan deskriptif dapat meningkatkan peringkat halaman Anda.
* Pengalaman Pengguna: Judul yang informatif membantu pengguna memahami konten halaman sebelum mereka membukanya.
### Tips Membuat Judul yang Baik
* Deskriptif dan Relevan: Pastikan judul mencerminkan isi halaman secara akurat.
* Panjang yang Tepat: Mesin pencari biasanya menampilkan sekitar 50-60 karakter pertama dari judul. Usahakan judul tidak terlalu panjang agar tidak terpotong.
* Hindari Pengulangan Kata Kunci: Gunakan kata kunci seperlunya dan hindari pengulangan yang tidak perlu.

## Tabel HTML 
Dalam HTML, tabel digunakan untuk menyajikan data dalam format baris dan kolom. Tabel dibuat menggunakan elemen-elemen berikut:
* table>: Elemen utama yang mendefinisikan tabel.
* tr> (table row): Mendefinisikan baris dalam tabel.
* th> (table header): Mendefinisikan sel header dalam tabel, biasanya tampil dengan teks tebal dan terpusat.
* td> (table data): Mendefinisikan sel data dalam tabel.
### Atribut Penting pada Tabel
* border: Menentukan lebar batas (border) tabel.
* cellpadding: Menentukan jarak antara konten sel dan batas sel.
* cellspacing: Menentukan jarak antara sel-sel dalam tabel.
### Penggabungan Sel 
* colspan: Menggabungkan beberapa kolom menjadi satu sel.
* rowspan: Menggabungkan beberapa baris menjadi satu sel.

## List HTML 
### Daftar Tidak Berurutan (Unordered List)
* Menggunakan tag <ul> untuk mendefinisikan daftar.
* Setiap item dalam daftar ditandai dengan tag li>.
* Item ditampilkan dengan tanda titik (bullet) secara default.
### Daftar Berurutan (Ordered List) 
* Menggunakan tag <ol> untuk mendefinisikan daftar.
* Setiap item dalam daftar ditandai dengan tag li>.
* Item ditampilkan dengan nomor urut secara default.
### Daftar Deskripsi (Description List)
* Menggunakan tag dl> untuk mendefinisikan daftar.
* Setiap istilah atau nama ditandai dengan tag dt>.
* Deskripsi untuk setiap istilah ditandai dengan tag dd>.

## Blok HTML 
Dalam HTML, elemen dibagi menjadi dua kategori utama berdasarkan perilaku tampilannya: elemen blok dan elemen inline. 
### Elemen blok 
* Selalu dimulai pada baris baru.
* Mengambil lebar penuh yang tersedia (memanjang dari kiri ke kanan).
* Contoh umum: p> (paragraf) dan div> (pembagi).
### Elemen Inline:
* Tidak memulai baris baru; berada dalam baris yang sama dengan konten sebelumnya dan sesudahnya.
* Hanya mengambil lebar yang diperlukan oleh kontennya.
* Contoh umum: span> dan a> (tautan).
### Elemen div> dan span>
* div>: Elemen blok yang sering digunakan sebagai wadah untuk elemen HTML lainnya.
* span>: Elemen inline yang digunakan untuk menandai bagian dari teks atau dokumen.


## Div HTML 
Elemen div> dalam HTML berfungsi sebagai wadah (container) untuk elemen-elemen HTML lainnya, memungkinkan pengelompokan konten untuk tujuan pemformatan dan pengaturan tata letak.
### Karakter Utama 
* Elemen Blok: Secara default, div> adalah elemen blok, yang berarti ia menempati lebar penuh yang tersedia dan dimulai pada baris baru.
* Tidak Memiliki Gaya Bawaan: Elemen div> tidak memiliki tampilan atau gaya bawaan, sehingga sering digunakan bersama CSS untuk menambahkan gaya atau tata letak tertentu.
### Penggunaan Umum 
* Pengelompokan Konten: Mengelompokkan beberapa elemen menjadi satu bagian untuk mempermudah pengaturan dan penataan.
* Penerapan Gaya dan Skrip: Menerapkan gaya CSS atau fungsi JavaScript pada sekelompok elemen sekaligus.
### Penataan Elemen div> Secara Berdampingan 
* Float: Menggunakan properti float untuk mengatur elemen agar mengapung di sebelah kiri atau kanan.
* Inline-Block: Mengubah tampilan elemen menjadi inline-block sehingga elemen tetap sebagai blok tetapi dapat berada dalam satu baris.
* Flexbox: Menggunakan model tata letak fleksibel untuk mengatur elemen dalam baris atau kolom yang fleksibel.
* Grid: Menggunakan model tata letak grid untuk mengatur elemen dalam baris dan kolom yang terstruktur.

## Atribut Kelas HTML 
Atribut class dalam HTML digunakan untuk menetapkan satu atau lebih nama kelas pada elemen, yang memungkinkan pengelompokan elemen untuk tujuan styling dengan CSS atau manipulasi dengan JavaScript. 
### Penggunaan Atribut 
* CSS Styling: Dengan menetapkan kelas pada elemen, Anda dapat menerapkan gaya CSS yang konsisten pada semua elemen dengan kelas yang sama.
* JavaScript Manipulation: JavaScript dapat menggunakan nama kelas untuk mengakses dan memanipulasi elemen-elemen tertentu dalam dokumen.
### Sintaks Penulisan Kelas dalam CSS 
Untuk mendefinisikan sebuah kelas dalam CSS, gunakan tanda titik (.) diikuti oleh nama kelas, kemudian tentukan properti dan nilainya dalam kurung kurawal. 
### Catatan Penting 
* Case Sensitivity: Nama kelas bersifat case-sensitive, sehingga class="contoh" dan class="Contoh" dianggap berbeda.
* Penggunaan pada Elemen Berbeda: Berbagai elemen HTML dapat memiliki nama kelas yang sama, memungkinkan penerapan gaya yang seragam pada elemen-elemen tersebut.
* Multiple Classes: Sebuah elemen dapat memiliki lebih dari satu kelas dengan cara menuliskannya secara berurutan dan dipisahkan oleh spasi dalam atribut class.

## Atribut Id HTML 
Atribut id dalam HTML digunakan untuk memberikan identifikasi unik pada elemen tertentu dalam sebuah dokumen. Nilai dari atribut id harus unik di seluruh dokumen HTML, sehingga tidak boleh ada dua elemen dengan id yang sama. 
### Fungsi Utama 
* Penghubung ke CSS: Atribut id memungkinkan penerapan gaya spesifik pada elemen tertentu melalui CSS.
* Interaksi dengan JavaScript: JavaScript dapat menggunakan id untuk mengakses dan memanipulasi elemen tertentu dalam dokumen.
* Pembuatan Bookmark HTML: Atribut id dapat digunakan untuk membuat penanda (bookmark) dalam halaman, memungkinkan tautan langsung ke bagian tertentu dari halaman tersebut.

## Iframe HTML 
Elemen iframe> dalam HTML digunakan untuk menampilkan sebuah halaman web di dalam halaman web lainnya.
### Sintaks Dasar 
* src: Menentukan URL dari halaman yang akan ditampilkan di dalam iframe.
* title: Memberikan deskripsi tentang konten iframe, penting untuk aksesibilitas.
### Atribut Penting 
* height dan width: Menentukan tinggi dan lebar iframe.
* style: Dapat digunakan untuk mengatur gaya CSS, seperti menghapus atau menyesuaikan border.

## Hava Script HTML 
Elemen script> dalam HTML digunakan untuk menyisipkan atau merujuk pada skrip sisi-klien, seperti JavaScript, yang memungkinkan halaman web menjadi lebih dinamis dan interaktif. 
* Atribut src: Digunakan untuk menautkan file JavaScript eksternal.
* Penempatan Skrip: Skrip dapat ditempatkan di bagian <head> atau <body> halaman HTML.
* Atribut type: Secara default, dianggap sebagai text/javascript, sehingga biasanya tidak perlu ditentukan.
* Elemen <noscript>: Digunakan untuk menyediakan konten alternatif bagi pengguna yang menonaktifkan JavaScript atau menggunakan browser yang tidak mendukungnya.
### Penggunaan Utama 
* Penyisipan Skrip Internal: Menulis kode JavaScript langsung di dalam elemen script>.
* Penyisipan Skrip Eksternal: Merujuk pada file JavaScript eksternal menggunakan atribut src.
### Contoh 
* Skrip Internal:
  script>
    document.getElementById("demo").innerHTML = "Hello JavaScript!";
  /script>
* Skrip Eksternal:
  script src="myscript.js">/script>

## File Path HTML 
Dalam HTML, jalur berkas (file path) digunakan untuk menentukan lokasi berkas dalam struktur folder situs web. Jalur ini penting saat menautkan berkas eksternal seperti halaman web, gambar, lembar gaya, atau skrip JavaScript. 
### Jenis Jalur Berkas 
+ Jalur Absolut: Menunjukkan URL lengkap ke sebuah berkas. Contoh: img src="https://www.example.com/images/picture.jpg" alt="Gambar">
+ Jalur Relatif: Menunjukkan lokasi berkas relatif terhadap halaman saat ini. Ada beberapa tipe jalur relatif:
 * Jalur Relatif ke Folder Saat Ini: Berkas berada di folder yang sama dengan halaman saat ini. Contoh: img src="picture.jpg" alt="Gambar">
 * Jalur Relatif ke Subfolder: Berkas berada di subfolder dari folder saat ini. Contoh: img src="images/picture.jpg" alt="Gambar">
 * Jalur Relatif ke Root Folder: Berkas berada di folder root situs web. Contoh: img src="/images/picture.jpg" alt="Gambar">
 * Jalur Relatif ke Folder Induk: Berkas berada satu tingkat di atas folder saat ini. Contoh: img src="../picture.jpg" alt="Gambar">

## HTML Head Element 
Elemen head> dalam HTML berfungsi sebagai wadah untuk metadata dan informasi yang tidak ditampilkan langsung pada halaman web, tetapi penting bagi browser dan mesin pencari. Penting untuk pengembangan web yang efektif, memastikan halaman Anda diindeks dengan benar dan memberikan pengalaman pengguna yang optimal.
### Elemen elemen umum 
* title>: Menentukan judul halaman yang muncul pada tab browser.
* meta>: Menyediakan metadata seperti deskripsi, kata kunci, dan pengaturan karakter.
* link>: Menghubungkan ke sumber eksternal seperti stylesheet atau ikon.
* style>: Menyisipkan CSS internal untuk menentukan gaya halaman.
* script>: Menyisipkan atau merujuk ke skrip JavaScript untuk interaktivitas.

## layout HTML 
Elemen-elemen semantik HTML membantu mendefinisikan struktur dan tata letak halaman web. 
### Elemen utama yang digunakan dalam pengaturan tata letak
* header>: Mendefinisikan bagian header untuk dokumen atau bagian tertentu.
* nav>: Mendefinisikan sekumpulan tautan navigasi.
* section>: Mendefinisikan bagian dalam dokumen.
* article>: Mendefinisikan konten yang independen dan mandiri.
* aside>: Mendefinisikan konten sampingan, seperti sidebar.
* footer>: Mendefinisikan bagian footer untuk dokumen atau bagian tertentu.
* details>: Mendefinisikan detail tambahan yang dapat dibuka dan ditutup oleh pengguna.
* summary>: Mendefinisikan judul untuk elemen details>

### Teknik yang bisa digunakan 
* Kerangka Kerja CSS: Menggunakan kerangka kerja seperti W3.CSS atau Bootstrap untuk mempercepat pembuatan tata letak.
* Properti Float CSS: Menggunakan properti float untuk mengatur elemen dalam kolom. Namun, teknik ini memiliki keterbatasan dalam fleksibilitas.
* Flexbox CSS: Memastikan elemen berperilaku prediktif saat tata letak harus menyesuaikan berbagai ukuran layar dan perangkat tampilan.
* Grid CSS: Menawarkan sistem tata letak berbasis grid dengan baris dan kolom, memudahkan desain halaman web tanpa harus menggunakan float dan positioning.

## Desain Web Responsif HTML
Desain Web Responsif adalah pendekatan dalam pengembangan web yang memastikan tampilan dan fungsi situs web menyesuaikan secara optimal dengan berbagai ukuran layar dan perangkat. Tujuannya adalah memberikan pengalaman pengguna yang konsisten dan nyaman, baik pada perangkat desktop, tablet, maupun ponsel pintar. 
### Komponen Utama 
* Viewport: Viewport adalah area tampilan konten pada perangkat pengguna. Mengatur viewport memungkinkan kontrol lebih baik terhadap skala dan tata letak halaman. Tag <meta> digunakan untuk mengatur viewport.
* ersentase dan Satuan Relatif: Menggunakan lebar dalam persentase atau satuan relatif seperti vw (viewport width) memungkinkan elemen menyesuaikan ukurannya sesuai dengan lebar layar. Misalnya, teks dengan ukuran font 10vw akan menyesuaikan ukurannya berdasarkan 10% dari lebar viewport.
* Persentase dan Satuan Relatif: Menggunakan lebar dalam persentase atau satuan relatif seperti vw (viewport width) memungkinkan elemen menyesuaikan ukurannya sesuai dengan lebar layar. Misalnya, teks dengan ukuran font 10vw akan menyesuaikan ukurannya berdasarkan 10% dari lebar viewport.
* Media Queries: Media queries memungkinkan penerapan gaya CSS yang berbeda berdasarkan karakteristik perangkat, seperti lebar layar.
* Framework CSS Responsif: Framework seperti W3.CSS dan Bootstrap menyediakan komponen dan grid sistem yang responsif, memudahkan pengembang dalam membuat tata letak yang fleksibel dan konsisten.
    * W3.CSS: Framework modern yang mendukung desain responsif secara default dan tidak bergantung pada pustaka JavaScript eksternal.
    * Bootstrap: Framework populer yang menawarkan sistem grid responsif dan komponen siap pakai untuk mempercepat pengembangan desain responsif.

 ## Elemen Kode Komputer HTML 
 Dalam HTML, terdapat beberapa elemen yang dirancang khusus untuk menampilkan kode komputer atau teks yang terkait dengan input dan output komputer. 
 ### Elemen utama 
 * code>: Digunakan untuk menampilkan potongan kode pemrograman atau perintah. Elemen ini menggunakan font monospace secara default, sehingga cocok untuk menampilkan kode.
 * pre>: Menyajikan teks dengan mempertahankan spasi dan format asli, termasuk baris baru. Elemen ini sering digunakan bersama <code> untuk menampilkan blok kode dengan format yang terjaga.
 * kbd>: Merepresentasikan input dari pengguna melalui keyboard, menunjukkan teks yang harus diketik oleh pengguna.
 * samp>: Menampilkan output atau respon dari komputer atau program.var>: Digunakan untuk merepresentasikan variabel dalam konteks pemrograman atau ekspresi matematika.
 * var>: Digunakan untuk merepresentasikan variabel dalam konteks pemrograman atau ekspresi matematika.

## Sematik HTML 
Elemen-elemen semantik dalam HTML5 memberikan makna yang jelas pada struktur halaman web, memudahkan mesin pencari dan pembaca layar untuk memahami konten. 
### Elemen sematik utama 
* header>: Bagian atas halaman yang biasanya berisi judul, logo, atau navigasi utama.
* nav>: Sekumpulan tautan navigasi.
* section>: Bagian dalam dokumen yang mengelompokkan konten dengan tema tertentu.
* article>: Konten independen yang bisa berdiri sendiri, seperti posting blog atau artikel berita.
* aside>: Konten sampingan, seperti sidebar atau informasi tambahan.
* footer>: Bagian bawah halaman yang biasanya berisi informasi hak cipta, tautan kebijakan privasi, atau informasi kontak.
* figure> dan <figcaption>: Digunakan untuk menyertakan gambar atau ilustrasi beserta keterangan atau caption
 
## Panduan gaya HTML 
Dalam HTML5, sintaks penulisan kode telah disederhanakan untuk memudahkan pengembang dalam membuat halaman web yang lebih efisien dan terstruktur. 
### Aturan dasar dalam sintaks HTML 
* Deklarasi DOCTYPE: Setiap dokumen HTML5 harus dimulai dengan deklarasi DOCTYPE sederhana untuk memastikan kompatibilitas dengan browser
* Penulisan Tag: Tag HTML tidak peka huruf besar-kecil, namun disarankan untuk menggunakan huruf kecil demi konsistensi dan keterbacaan.
* Penutupan Tag: Semua elemen harus ditutup dengan benar. Elemen kosong, seperti <img> atau br>, tidak memerlukan penutupan sendiri.
* Atribut: Atribut harus ditulis dalam huruf kecil, memiliki nilai, dan nilai tersebut harus diapit oleh tanda kutip ganda.
* Indentasi dan Spasi: Gunakan indentasi konsisten untuk meningkatkan keterbacaan kode.
* Komentar: Gunakan komentar untuk menjelaskan bagian kode tertentu, yang membantu dalam pemeliharaan dan kolaborasi.

## Entitas HTML 
Dalam HTML, beberapa karakter memiliki makna khusus dan tidak dapat digunakan langsung dalam teks karena dapat menyebabkan konflik atau interpretasi yang salah oleh browser. Untuk menampilkan karakter-karakter tersebut, digunakan HTML Entities, yaitu kode khusus yang mewakili karakter tertentu. Nama entitas bersifat case-sensitive, artinya penulisan huruf besar dan kecil harus tepat sesuai definisi.
#### Penulisan HTML Entitas 
* Nama Entitas (Entity Name): Menggunakan nama yang mudah diingat, diawali dengan tanda ampersand (&) dan diakhiri dengan titik koma (;).
* Nomor Entitas (Entity Number): Menggunakan kode numerik dari karakter tersebut, diawali dengan &# dan diakhiri dengan titik koma (;).
### Keuntungan dan kerugiaan 
* Nama Entitas:
Keuntungan: Lebih mudah diingat dan dibaca.
Kerugian: Tidak semua browser mendukung semua nama entitas.
* Nomor Entitas:
Keuntungan: Dukungan yang lebih luas di berbagai browser.
Kerugian: Kurang intuitif dan lebih sulit diingat.
### Spasi tak terputus
Entitas &nbsp ; digunakan untuk menambahkan spasi yang tidak akan terputus atau terpecah oleh pergantian baris. Ini berguna untuk menjaga dua kata atau elemen tetap bersama dalam satu baris.

## Simbol HTML 
Dalam HTML, simbol atau karakter khusus yang tidak tersedia langsung pada keyboard dapat ditambahkan menggunakan HTML Entities. Ini memungkinkan Anda untuk menampilkan berbagai simbol matematika, teknis, atau mata uang dalam halaman web.

## Emoji HTML 
Emojis adalah karakter dari set karakter UTF-8 yang dapat digunakan dalam HTML untuk menambahkan ekspresi visual pada konten web.
### Menampilkan emoji 
* Untuk menampilkan emoji dalam HTML, pastikan halaman Anda menggunakan set karakter UTF-8 dengan menambahkan tag meta berikut di bagian <head
* Setelah itu, Anda dapat menambahkan emoji langsung ke dalam konten HTML menggunakan entitas numerik.

## Set Karakter HTML 
Untuk memastikan halaman HTML ditampilkan dengan benar, penting untuk menentukan set karakter (charset) yang digunakan. Set karakter menginformasikan browser bagaimana cara menampilkan teks dan simbol pada halaman web.
### Mengapa set karakter penting??
Setiap karakter, termasuk huruf, angka, dan simbol, direpresentasikan oleh kode numerik tertentu. Set karakter menentukan bagaimana kode-kode ini diterjemahkan menjadi karakter yang dapat dibaca oleh manusia. Jika set karakter tidak ditentukan atau ditentukan dengan tidak tepat, browser mungkin menampilkan karakter yang salah atau simbol aneh.
### Set Karakter dalam HTML4: ISO-8859-1
Pada HTML versi 4, set karakter default yang digunakan adalah ISO-8859-1, juga dikenal sebagai Latin-1. Set karakter ini mencakup karakter untuk bahasa-bahasa Eropa Barat. Untuk menentukan set karakter ini dalam HTML4. 
### Set Karakter dalam HTML5: UTF-8
Dengan diperkenalkannya HTML5, penggunaan set karakter UTF-8 sangat dianjurkan. UTF-8 adalah bagian dari standar Unicode yang mencakup hampir semua karakter dan simbol di dunia, sehingga sangat cocok untuk lingkungan multibahasa. Untuk menentukan UTF-8 sebagai set karakter dalam HTML5.

## Kode URL HTML 
URL Encoding adalah proses mengonversi karakter ke dalam format yang dapat ditransmisikan melalui Internet. Hal ini diperlukan karena URL hanya dapat menggunakan karakter dari set karakter ASCII. Karakter non-ASCII, seperti karakter dengan aksen atau simbol khusus, harus diubah agar dapat dimasukkan dalam URL.
### Mengapa URL Encoding Diperlukan?
URL hanya dapat mengandung karakter tertentu, termasuk huruf (A-Z, a-z), angka (0-9), dan beberapa karakter khusus seperti tanda hubung (-), garis bawah (_), titik (.), dan tilde (~). Karakter lain, termasuk spasi, karakter non-ASCII, dan karakter khusus lainnya, tidak diizinkan dalam URL dan harus dienkode agar sesuai dengan format URL yang valid.
### Cara Kerja URL Encoding
URL encoding menggantikan karakter yang tidak diizinkan dengan tanda persen (%) diikuti oleh dua digit heksadesimal yang mewakili nilai ASCII atau Unicode dari karakter tersebut. Misalnya, spasi ( ) digantikan dengan %20 atau tanda plus (+), dan karakter "€" (Euro) digantikan dengan %E2%82%AC.
## Perbedaan HTML dan XHTML 
XHTML (Extensible HyperText Markup Language) adalah versi HTML yang lebih ketat dan berbasis XML. Ini dirancang untuk membuat HTML lebih fleksibel dan dapat bekerja dengan format data lain seperti XML.
### Perbedaan utama 
* Deklarasi DOCTYPE: XHTML memerlukan deklarasi <!DOCTYPE> yang wajib.
* Atribut xmlns pada <html>: Atribut ini harus ada untuk menentukan namespace XML.
* Elemen Wajib: Tag <html>, <head>, <title>, dan <body> harus ada dalam dokumen XHTML.
* Penulisan Elemen: Semua elemen harus ditulis dalam huruf kecil dan ditutup dengan benar.
* Penulisan Atribut: Nama atribut harus dalam huruf kecil, nilainya harus diberi tanda kutip, dan minimisasi atribut tidak diperbolehkan.



