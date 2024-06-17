# "Good Commit" vs "Your Commit": How to Write a Perfect Git Commit Message

Tentu! Berikut adalah ringkasan yang lebih sederhana dan mudah dipahami dari artikel tersebut:

### Mengapa Menulis Pesan Komit yang Baik Itu Penting?

Pesan komit yang baik sangat penting karena:

1. **Memberikan Konteks:** Membantu kita dan rekan kerja memahami apa yang telah diubah dan mengapa perubahan itu dilakukan.
2. **Mudah Dibaca di Masa Depan:** Memudahkan kita untuk melihat kembali perubahan yang telah dibuat tanpa bingung.

### Kesalahan Umum yang Harus Dihindari

1. **Jangan Gunakan Pesan Tidak Relevan:** Hindari pesan seperti "WIP", "Mau makan siang", atau "Happy Weekend Team". Pesan ini tidak memberikan informasi yang berguna.
2. **Jangan Komit Perubahan Terpisah untuk File Terkait:** Misalnya, jika Anda mengubah header dan footer, jangan komit perubahan ini secara terpisah. Gabungkan perubahan yang terkait dalam satu komit.

### Cara Menghindari Kesalahan

1. **Gabungkan Perubahan Terkait:**

   ```bash
   git add header.js footer.js
   git commit -m "Perbaiki tata letak Header dan Footer"
   ```

2. **Gunakan Cabang Pribadi untuk Komit Sementara:** Gunakan cabang pribadi untuk komit yang belum final, seperti saat Anda perlu menyimpan pekerjaan sebelum makan siang.

   ```bash
   git checkout -b private/my-temp-branch
   ```

### 7 Aturan Menulis Pesan Komit yang Baik

1. **Batas 50 Karakter untuk Judul:** Buat judul pesan komit singkat dan jelas, maksimal 50 karakter.
2. **Kapitalisasi Huruf Pertama Judul:** Misalnya, "Perbaiki bug pada halaman login".
3. **Tidak Ada Titik di Akhir Judul:** Jangan tambahkan titik di akhir judul.
4. **Pisahkan Judul dan Isi dengan Baris Kosong:** Contoh:

   ```bash
   Perbaiki tampilan halaman login

   Perbaiki masalah penyelarasan teks di halaman login.
   ```

5. **Bungkus Isi Pesan di 72 Karakter:** Bungkus teks isi pesan komit setiap 72 karakter untuk memastikan keterbacaan di berbagai alat.
6. **Gunakan Bentuk Imperatif:** Gunakan kata kerja perintah, misalnya "Perbaiki bug" bukan "Memperbaiki bug".
7. **Jelaskan "Apa" dan "Mengapa", Tidak "Bagaimana":** Fokus pada apa yang diubah dan mengapa, bukan bagaimana perubahan tersebut dilakukan.

### Contoh Studi Kasus

Jika Anda bekerja pada fitur keranjang belanja di toko online, berikut adalah cara Anda bisa menulis pesan komit:

1. **Enhance CSS presentation of cart section**
2. **Introduce JavaScript functionality to cart**
3. **Refine CSS to resolve text alignment issue**
4. **Fix counter bug related to cart behavior**
5. **Incorporate loading animation for checkout button**

Untuk menggabungkan semua perubahan ini menjadi satu komit yang jelas, Anda bisa menggunakan teknik "squash" untuk menggabungkan komit dari cabang pribadi Anda.

### Tips Akhir

- **Jelas dan Bermakna:** Selalu tulis pesan komit yang jelas dan berarti.
- **Gunakan Cabang Pribadi untuk Eksperimen:** Simpan komit sementara di cabang pribadi sebelum digabungkan ke cabang utama.

### Sumber Belajar

- [Dokumentasi Git](https://git-scm.com/doc)
- [GitHub Learning Lab](https://lab.github.com/)
- [Tutorial Git Atlassian](https://www.atlassian.com/git/tutorials)
- [Learn Git Branching](https://learngitbranching.js.org/)

<p>Dengan mengikuti panduan ini, pesan komit Anda akan lebih informatif dan membantu baik Anda maupun tim Anda di masa depan.</p>

### Original url

https://medium.com/gitconnected/good-commit-vs-your-commit-how-to-write-a-perfect-git-commit-message-6e96ab6357fa
