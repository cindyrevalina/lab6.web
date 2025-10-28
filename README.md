# **Laporan Praktikum 6 - Pemrograman Web (Bootstrap & JavaScript)**

## **Nama:** Cindy Revalina Simanullang 


## Nim : 312410417


## Kelas:TI.24 A3


## Mata Kuliah: Pemrograman Web 1


---

## **Deskripsi Proyek**
Repositori **lab5.web** ini berisi latihan pembuatan halaman web dengan menerapkan **Bootstrap** dan **JavaScript**.  
Tujuannya adalah untuk mempelajari cara membuat **layout responsif**, **form interaktif**, dan **halaman portfolio** menggunakan komponen-komponen modern dari Bootstrap.

Struktur folder proyek sebagai berikut:

---

## **Penjelasan Setiap File**

### 🟩 **1. index.html**
File ini merupakan hasil **refactor layout dari Praktikum 4** menggunakan **Bootstrap Grid System**.

**Tujuan:**  
Mengubah layout sederhana menjadi responsif menggunakan komponen Bootstrap.

**Fitur yang digunakan:**
- `<nav>` Bootstrap untuk navigasi atas.  
- Grid System (`.row`, `.col-md-8`, `.col-md-4`) untuk membagi halaman menjadi konten utama dan sidebar.  
- Komponen `.card` untuk menggantikan `.box` dan `.widget-box`.  
- Tidak menggunakan CSS manual seperti `float` dan `clear`.  

**Hasil tampilan:**  
Terdapat header navigasi, konten utama di sebelah kiri, dan sidebar di sebelah kanan dalam satu layout responsif.  

📸 *Contoh tampilan:*  
![Tampilan index]<img width="1077" height="760" alt="image" src="https://github.com/user-attachments/assets/78c03a4b-8583-4296-a998-d574ca55fe30" />


---

### 🟦 **2. form.html**
File ini merupakan hasil **refactor form dari Praktikum 5** menggunakan Bootstrap.

**Tujuan:**  
Merapikan tampilan form agar terlihat profesional dan responsif dengan class Bootstrap.

**Komponen yang digunakan:**
- `.form-label` untuk label input.  
- `.form-control` untuk input teks, email, dan textarea.  
- `.btn` untuk tombol kirim dengan variasi warna dari Bootstrap.  
- `.card` untuk membungkus form agar tampil elegan dan terstruktur.  

**Hasil tampilan:**  
Form terlihat rapi, mudah diisi, dan otomatis menyesuaikan ukuran layar.  

📸 *Contoh tampilan:*  
![Tampilan form]<img width="770" height="763" alt="image" src="https://github.com/user-attachments/assets/59ee723a-3e7f-496d-b5e4-f202faf99c12" />


---

### 🟨 **3. portfolio.html**
File ini adalah halaman **Portfolio Pribadi** yang dibuat dengan Bootstrap.

**Tujuan:**  
Membuat halaman portfolio yang menampilkan profil diri dan proyek-proyek yang pernah dibuat.

**Struktur halaman:**
- **Navbar:** di bagian atas dengan judul “Portfolio Saya”.  
- **Section Tentang Saya:** menggunakan `.row` dengan dua kolom:
  - Kolom kiri: berisi foto profil menggunakan `.img-fluid`.
  - Kolom kanan: berisi nama dan deskripsi diri.
- **Section Portfolio:** berisi 3 kolom (`.col-md-4`), masing-masing berisi **.card** yang menampilkan gambar proyek dan deskripsi singkat.
- **Footer:** teks hak cipta di bagian bawah halaman.

**Hasil tampilan:**  
Halaman tampil modern dengan layout simetris dan foto profil yang responsif.

📸 *Contoh tampilan:*  
![Tampilan Portfolio]<img width="1128" height="628" alt="image" src="https://github.com/user-attachments/assets/8464d5b9-8b42-4732-a73e-a3b909e62271" />


---

## **4. Teknologi yang Digunakan**
- **HTML5**  
- **CSS3 (melalui Bootstrap 5)**  
- **JavaScript dasar (untuk interaksi di form)**  
- **Bootstrap Components:** Navbar, Card, Grid System, Form, Button  

---

## **5. Kesimpulan**
Dari praktikum ini, saya belajar:
- Cara menggunakan **Bootstrap Grid System** untuk membuat layout web tanpa float atau clear.  
- Cara membuat form dengan class Bootstrap agar tampil profesional.  
- Cara membangun halaman **portfolio responsif** dengan desain modern.  
- Bootstrap sangat membantu dalam membuat tampilan web yang rapi dan cepat tanpa menulis CSS manual.

---


