Berikut adalah penjelasan lengkap dari setiap langkah praktikum HTML Dasar berdasarkan modul **Praktikum 1: Pemrograman Web**:

---

### **1. Persiapan & Pembuatan Struktur Dasar Document**

* **Langkah:** Membuka text editor (misal: Visual Studio Code), membuat folder kerja `praktikum-1-html-dasar`, lalu membuat file bernama `index.html` yang berisi struktur dasar dokumen HTML5 (`<!DOCTYPE html>`, `<html>`, `<head>`, `<title>`, dan `<body>`).
* **Penjelasan:**
* `<!DOCTYPE html>` memberitahu web browser bahwa dokumen menggunakan standar HTML5.


* Tag `<html>` merupakan elemen root (akar) pembungkus seluruh konten web.


* Bagian `<head>` digunakan untuk menyimpan meta-informasi halaman, seperti judul tab browser yang ditentukan melalui tag `<title>`.


* Bagian `<body>` berfungsi sebagai tempat menampung seluruh elemen/konten visual yang akan dilihat oleh pengguna di browser.

---

### **2. Langkah 1: Membuat Paragraf**

* **Langkah:** Menambahkan paragraf menggunakan tag `<p>` di dalam elemen `<body>`.
* **Penjelasan:** Tag `<p>` (*paragraph*) digunakan untuk mengelompokkan teks menjadi sebuah paragraf. Browser secara otomatis memberikan jarak (margin atas dan bawah) antar tag `<p>`, sehingga antartag paragraf tidak saling menempel.

---

### **3. Langkah 2: Menambahkan Judul (Heading)**

* **Langkah:** Menambahkan heading `<h1>` sebelum paragraf pertama dan `<h2>` sebelum paragraf kedua.
* **Penjelasan:** Tag heading (`<h1>` hingga `<h6>`) digunakan untuk membuat judul atau subjudul secara berhierarki. `<h1>` digunakan sebagai judul utama (ukuran teks paling besar dan penting), sedangkan `<h2>` hingga `<h6>` digunakan untuk subjudul dengan tingkatan/hirarki di bawahnya.

---

### **4. Langkah 3: Memformat Teks**

* **Langkah:** Menerapkan tag pemformatan seperti `<b>` (bold), `<i>` (italic), `<strong>`, `<sub>`, `<sup>`, `<mark>`, dll.
* **Penjelasan:** Tag pemformatan memberikan gaya atau makna khusus pada teks. Contohnya:
* `<b>` atau `<strong>` untuk mempertebal teks.
* `<i>` atau `<em>` untuk mencetak miring teks.
* `<sub>` (*subscript*) untuk teks di bawah garis dasar (contoh: $H_2O$).
* `<sup>` (*superscript*) untuk teks di atas garis dasar (contoh: $x^2$).
* `<mark>` untuk memberikan efek penanda/stabilo pada teks.



---

### **5. Langkah 4 & 5: Menyisipkan dan Mengatur Ukuran Gambar**

* **Langkah:** Menyiapkan folder `images/`, menyimpan file gambar `profil.jpg`, menyisipkannya dengan tag `<img>`, serta mengatur atribut `src`, `alt`, `title`, `width`, dan `height`.
* **Penjelasan:**
* Tag `<img>` merupakan *self-closing tag* (tidak berpasangan) untuk menampilkan gambar.
* Atribut `src` menentukan alur/lokasi direktori file gambar.
* Atribut `alt` (*alternative text*) menyediakan deskripsi teks jika gambar gagal diolah/dimuat browser atau dipindai oleh alat pembaca layar (*screen reader*).
* Atribut `title` menampilkan tooltip saat kursor diarahkan ke gambar.
* Atribut `width` dan `height` mengatur dimensi lebar dan tinggi tampilan gambar dalam piksel.



---

### **6. Langkah 6: Menambahkan Hyperlink (Navigasi)**

* **Langkah:** Membuat file tambahan `halaman2.html` dan menambahkan tag `<a>` (anchor) dengan atribut `href` untuk tautan lokal maupun eksternal.
* **Penjelasan:** Tag `<a>` berfungsi menghubungkan antarhalaman web (hyperlink). Atribut `href` berisi alamat URL atau path file tujuan.
* **Link Internal:** Mengarah ke file lokal dalam domain/folder yang sama (misal: `halaman2.html`).
* **Link Eksternal:** Mengarah ke domain luar menggunakan URL lengkap (misal: `[https://www.google.com](https://www.google.com)`).



---

### **7. Langkah 7: Menambahkan List (Daftar)**

* **Langkah:** Membuat daftar menggunakan Unordered List (`<ul>`) dan Ordered List (`<ol>`).
* **Penjelasan:**
* `<ul>` (*Unordered List*) digunakan untuk daftar tanpa urutan angka, secara default ditandai dengan ikon *bullet* (titik).
* `<ol>` (*Ordered List*) digunakan untuk daftar berurutan berbasis nomor, huruf, atau angka romawi.
* Tag `<li>` (*List Item*) diletakkan di dalam `<ul>` atau `<ol>` sebagai penanda tiap butir item daftar.



---

### **8. Langkah 8: Menambahkan Komentar**

* **Langkah:** Menyisipkan sintaks `<!-- Komentar -->` pada kode HTML.
* **Penjelasan:** Komentar digunakan untuk memberikan deskripsi atau catatan pada kode sumber tanpa dieksekusi atau ditampilkan oleh browser. Hal ini mempermudah pembacaan dan pemeliharaan kode (*maintenance*).

---

### **9. Langkah 9: Menggabungkan Semua Elemen (Halaman Profil Mahasiswa)**

* **Langkah:** Menyusun seluruh elemen HTML yang telah dipelajari (struktur dasar, navigasi, gambar, judul, paragraf, daftar keahlian, dan target belajar) menjadi satu halaman lengkap bertema **Profil Mahasiswa**.
* **Penjelasan:** Langkah ini bertujuan menguji pemahaman penggabungan struktur dokumen HTML yang lengkap, logis, serta rapi sehingga membentuk layout halaman web fungsional.