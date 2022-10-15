# TUGAS 6 PEMOGRAMAN MOBILE

### NAMA : MILA YUNITA
### NIM : 2041720027
### KELAS : TI-3C
<br>

## Langkah-Langkah Penyelesaian
1. Mengubah versi gradle. Pada menu File yang ada di pojok kiri atas, memilih opsi Project Structure. Pada jendela Project Structure memilih menu Project. Kemudian mengisikan verisi 7.3.0 unutk Android Gradle Plugin dan versi 7.4 untuk gradle. Mengklik Apply.

<img src="img/langkah/1.png">

2. Mengganti Gradle JDK. Pada menu SDK Location menekan link Gradle Settings yang ada di sebelah kiri bawah. Memilih opsi "Android Studio default JDK" pada kolom Grade JDK. Lalu mengklik OK.
<img src="img/langkah/2.png">

3. Ketika mengklik link "Try Again" yang ada di pojok kanan atas, masih terdapat error saat program dijalankan. Menekan link "Add gradle Maven repository and sync project" yang ada pada terminal.
<img src="img/langkah/3.png">
<br>

4. Membuka file <b>build.gradle (Module: CrudSqlite.app)</b> yang ada di dalam folder Gradle Script. Kemudian mengatur isi method dependencies seperti di bawah ini.
<img src="img/langkah/l4.png">

5. Pada file <b>build.gradle (Project CrudSqlite)</b> yang ada di dalam folder Gradle Script, mengubah versi gradle menjadi 7.2.1 seperti hasil screenshot di bawah ini. Kemudian menekan link "Try Again" yang ada di pojok kanan untuk mencoba mlakukan sinkronisasi gradle kembali.
<img src="img/langkah/5.png">

6. Sudah tidak terdapat error. Hal tersebut menunjukkan bahwa proses sinkronisasi gradle berhasil dilakukan.
<img src="img/langkah/7.png">

<br>

## Hasil Screenshoot tampilan saat dijalankan di handphone
1. Tampilan awal Ketika aplikasi dijalankan
<img src="img/tampilan awal.jpg">

2. Mencoba Fitur Create dengan menekan tombol "Buat Bidoata Baru"
<img src="img/create data.jpg">

3. Tampilan ketika data berhasil ditambahkan.
<img src="img/hasil create data.jpg">

4. Tampilan ketika mengklik salah satu data. Akan muncul fitur lihat data, update data, dan hapus data.
<img src="img/klik data.jpg">

5. Mencoba fitur Lihat Data
<img src="img/lihat data.jpg">

6. Mencoba fitur Update Data "MILA YUNITA" menjadi "MILA Y"
<img src="img/update data.jpg">

7. Hasil ketika data berhasil di-update
<img src="img/hasil update data.jpg">

8. Mencoba fitur Hapus Biodata. Data "MILA Y" berhasil dihapus.
<img src="img/hasil hapus.jpg">