<html>
  <body>
    Pemprograman WEB

<p align = "justify">
  <b>*Pengertian HTML* </b>
(Hyper Text Markup Languange) adalah Bahasa Markup yang mendeskripsikan tag-tag HTML dalam sebuah website . 
Bahasa Markup digunakan untuk menampilkan sebuah informasi dalam bentuk website yang ditujukan kepada golongan umum atau circle.
Tag-Tag dasar didalam nya mempunyai banyak arti untuk dapat diterjemahkan dalam sebuah informasi dalam bentuk website tersebut. 
Setiap tag memiliki pendeskripsian konten yang berbeda. Untuk membaca dokumen HTML dan menampilkan sebagai halaman web bisa
menggunakan web broser yaitu Mozila Firefox, Google Chrome, Safari dan lain sebagai nya yang sejenis. </p>

<b> 1. HTML ENCODING/CHARSET</b>
<p align = "justify"> HTML Charset ini berguna untuk menampilkan halaman HTML secara benar,guna dari tag ini agar web browser harus mengetahui pengaturan yang akan digunakan. </p>
<b> 2. HTML HEADING </b>
<p align = "justify"> HTML Heading adalah tag dasar html yang berfungsi untuk membuat heading pada tampilan web. Berguna untuk membedakan antara isi halaman web dan header dari halaman itu sendiri. </p>
<b> 3. HTML PARAGRAPH </b>
<p align = "justify"> HTML Paragraph adalah untuk membuat isi pada halaman web. </p>
<b> 4. HTML LINE BREAK </b>
<p align = "justify"> HTML Line Break berfungsi seperti enter pada keyboard untuk membuat baris baru dalam element html. </p>
<b> 5. HTML FONT </b>
<p align = "justify"> HTML Font Berfungsi untuk mengatur warna bentuk dan ukuran tulisan pada halaman HTML .</p>
<b> 6. HTML FORMATING </b>
<p align = "justify"> HTML Formatting adalah tag dasar html untuk membuat format penulisan dalam element html. Misalnya menebalkan tulisan, membuat huruf menjadi miring dan lain-lain. dan ada beberapa jenis nya yaitu Bold Text, Important Text, Italic Text, Emphasized Text,Marked Text,Small Text, Deleted Text, Inserted Text, Subscripts, dan Superscripts. </p>
<b> 7. HTML IMAGES </b>
<p align = "justify"> HTML IMAGES berguna untuk memasukkan gambar pada halaman web. Dengan cara memanggil gambar yang tersimpan.</p>
<b> 8. HTML LINK </b>
<p align = "justify"> HTML LINKS adalah tag dasar untuk membuat link/url didalam halaman web sehingga dapat menghubungkan antara halaman web yang satu dengan yang lain.</p>
<b> 9. HTML LIST </b>
<p align = "justify"> HTML LIST berguna untuk membuat Numbering List maupun Bullet List pada element HTML.</p>
Terdiri atas 2 Unordered List yaitu : 
<ol>
<li>Bullet List</li>
<li>Ordered List</li>
</ol>
<b> 10. HTML TABLE </b>
<p align = "justify"> HTML Table adalah tag dasar HTML untuk membuat table di dalam halaman web html.</p>
Terdiri dari 3 HTML Table Yaitu :
<ol>
<li>Table Heading </li>
<li>Column Spanning </li>
<li>Row Spanning </li>
</ol>
<b> 11. HTML COMMENT </b>
<p align = "justify"> Tag ini berguna untuk membuat comment dalam html.</p>
<b> 12. HTML FORM </b>
<p align = "justify"> Tag HTML Form berguna untuk mengambil data yang di iputkan oleh user.</p>
Adapun Tipe input yang ada dalam html :
<ol type = 'a'>
<li>Text Input</li>
<li>RadioButton Input</li>
<li>Submit Button</li>
<li>Password</li>
<li>Checkbox</li>
<li>Button</li>
<li>Textarea Element</li> 
<li>Combobox</li>
<li>Method Attribute (Post dan Get)</li>
</ol>
<b>Dasar-Dasar CSS </b>
<p align = "justify">
  <b>A.Pengertian CSS </b>
  <br> CSS adalah kepanjangan dari Cascading Style Sheets, yang berfungsi untuk mengintrol tampilan dari sebuah halaman website. Dengan mengunakan CSS cukup satu kode untuk semua mark up yang sama pada tag HTML.</br>
  
  <b>B.Struktur Dasar CSS </b>
  <p align = "justify">
  Sintak dari CSS berbeda dengan HTML apabila HTML menggunakan tag dan atribute, maka CSS menggunakan selector, dimna selector memiliki declarations. Declarations memiliki properties value. Sintak-sintak CSS ini ada yang ada diselipkan di dalam dokumen HTML ada juga yang berupa file tersendiri yang dapat di akses oleh HTML. Secara garis besar anatomi dari aturan CSS adalah sebgai berikut :</p>

  ![image1](https://github.com/user-attachments/assets/ff39b4bb-c5f3-46ef-8cd8-7a94a254d803)
 

 <b> C.Penempatan CSS </b>
   <b> 1.EXTERNAL STYLE SHEET </b>
   <p align = "justify">
    External Style Sheet adalah penempatan css pada satu file css, file css tersebut dibuat dengan ekstensi css yang kemudian dipanggil menggunakan element link pada HTML.</p>
     <b> 2.INTERNALL STYLE SHEET </b>
      <p align = "justify">
     Insternal Style Sheet adalah pendeklarasian style css yang ada didalam file HTML. Untuk mendeklarasi css ini kita menggunakan tag <stlye>.Biasanya digunakan jika file HTML itu meliki style tersendiri dan berbeda dengan style css halaman HTML yang lain.</p>
     <b> 2.INTERNAL STYLE SHEET </b>
      <p align = "justify">
     Insternal Style Sheet adalah pendeklarasian style css yang ada didalam file HTML. Untuk mendeklarasi css ini kita menggunakan tag <stlye>.Biasanya digunakan jika file HTML itu meliki style tersendiri dan berbeda dengan style css halaman HTML yang lain.</p>
     <b> 3.INLINE STYLE </b>
      <p align = "justify">
     Inline Style adalah pendeklarasian langsung pada tag-tag HTML.Untuk mendeklarasian css ini kita menggunakan attribut stlye pada tag HTML. Biasanya digunakan jika kita ingin membuat style seniri untuk satu tag di dalam HTML.</p>
     <b> 4.MULTIPLE STYLE SHEET </b>
      <p align = "justify">
     Multiple style sheet adalah kondisi dimana satu halaman HTML memiliki 2 stlye css. Misalnya pada contoh syntax dibawah, kita menggunakan external style sheet dan internal style sheet. Di dalam external style sheet kita menggunakan property yang sama namun dengan vakue yang berbeda dengan style internal. Makan yang valuse yang akan dibaca adalah value internal style sheet karena merupakan value terakhir. Kondisinya akan berbeda jika penempatan element <link> verada dibawah tag style, maka yang dibaca value dari style external. </p>

 <b> D. CSS SYNTAX </b>
   <b> 1.SELECTOR </b>
   <p align = "justify">
   CSS selctor digunakan untuk menumakan atau memilih nama element, id, class, attribute dan lain-lain di dalam halaman HTML.</p>
    <b> a.ELEMENT/ TAG </b>
    <p align = "justify">
    Elemen Selector memilih element atau tah sesuai nama tag yang ada di dalam halaman HTML.</p>
    <b> b.ID </b>
    <p align = "justify">
ID Selector menggunakan atribut ID pada tag HTML untuk pemanggilnya. Biasanya digunakan untuk tag/ element yang meimilki style tersendiri . Untuk penulisan nya menggunakan tagar (#) kemudian nama id nya . Pengaplikasian pada html tag. element menggunakan atrribut id = "nama_selector_id"</p>
<b> c.CLASS </b>
    <p align = "justify">
Class selector memilih element dengan atrribut class yang spesifik. Untuk memilih element atau tag yang spesifik, dengan menulis nama element kemudian di ikuti dengan tanda titik(.) dan di lanjtkan dengan anam class yang di deklarasikan . ada 2 Bentuk Umum dan Bentuk Classs Spesifik euntuk element / tag</p>
<b> d. GROUPING </b>
    <p align = "justify">
Grouping Selector adalah penggabungan beberapa tag/element, yang memilki property dan value yang sama sehingga meringkas penulisan syantax, untuk melakukan grouping hal yang perlu di perhatikan adalah tanda ":" pada selector sebagai pemisah tag-tag/element.ada 2 dan Sebelum dan sesudah Gruping </p>

![image](https://github.com/user-attachments/assets/f9550730-e0f0-4ec2-b695-598a7b5fe940)

  <b> 2. COMMENT </b>   
 <p align = "justify">
Comment digunakan untuk mendeskripsikan syntax yang ada pada css. dan akan di abaikan oleh browser. Pengaplikasian nya menggunakan /*....*/ berlaku untuk 1 baris maupun lebih. </p>
 <b> E. PROPERTIES </b>  <br> 
 <b> 1. COLOR </b>  
 <p align = "justify">
Terdapat 3 cara melakukan pewarnaan style dalam css, yaitu Valid Color Name, RGB Value. dan Hexadecimal Value. </p>
 <b> 2. BACKGROUND </b>  
 <p align = "justify">
   CSS Background digunakan untuk mengatur style background suatu tag/element. Terdiri dari beberapa properties diantaranya. </p>
<ul>
<li>background-color</li>
<li>background-image</li>
<li>background-repeat</li>
<li>background-attachment</li>
<li>background-position </li>
</ul>
   <b> 3. BORDER </b>  
 <p align = "justify">
   Border Style property digunakan untuk membuat tampilan border pada tag html. </p>
   Hasil :

![image](https://github.com/user-attachments/assets/5f718832-c2e1-47b9-a590-d75786a418e6)


 <br>

<b> 4. MARGIN </b>
<p align = "justify">
   Margin digunakan untuk mengatur jarak antar elemen pada html .Untuk valuenya dapat menggunakan auto,px,pt,cm,%, inherit,dll. </p>
 <ul>
<li>Auto untuk mengatur ukuran secara otomatis</li>
<li>Px,pt,cm untuk mengatur ukuran sesuai dengan kemauan dari kita sendiri </li>
<li>Persen (%) Mengatur jarak menggunakan persen misalnya 50% </li>
<li>Inherit mengatur jarak sesuai dengan element kepala.</li>
</ul>  
  <b> 5. PADDING </b>
<p align = "justify">
   Padding digunakan untuk mengatur space element content dan element border pada html, maksudnya adalah mengatur jarak suatu elemeny yang terdapat di dalam elemen kepala. Untuk valuenya dapat menggunakan auto, px,pt, cm. % inherit,dll </p>
<ul>
<li>Auto untuk mengatur ukuran secara otomatis</li>
<li>Px,pt,cm untuk mengatur ukuran sesuai dengan kemauan dari kita sendiri </li>
<li>Persen (%) Mengatur jarak menggunakan persen misalnya 50% </li>
<li>Inherit mengatur jarak sesuai dengan element kepala.</li>
</ul>  
<b> 6. HEIGHT/WIDTH </b>
<p align = "justify">
Height untuk mengatur tinggi suatu style, sedangkan wifth digunakan untuk mengatur lebar suatu style, biasa digunakan pada tag layout <div> untuk mengatur ukuran.</p>
<b> 7. HEIGHT/WIDTH </b>
<p align = "justify">
Pada CSS Text kita dapat mengatur style mulai dari warna text, alignment, case text, indent text, jarak kata, arah teks, jarak antar line, jaral antar huruf dan underline atau tidak.</p>
<b> 8. FONTS </b>
<p align = "justify">
CSS font properties mendefinisikan font family, ketebalan, ukuran, and the style dari senuah text pada element html. </p>
<b> 9. ROUNDED CORNER </b>
<p align = "justify">
Property CSS3 yang dapat membuat tampilan di setiap sudut. Menjadi rounded atau tak bersudut. </p>
  
Bisa cek Tag-Tag nya di repositori ya yang mau belajar...🤞

Dee-Glit1015

  </body>
</html>
