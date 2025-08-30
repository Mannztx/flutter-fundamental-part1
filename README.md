# mobile

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# Project Pertama Flutter (Pertemuan 2)

NIM : 362458302101
Nama : Firman Ardiansyah
Kelas : 2D TRPL

## Dokumentasi Praktikum 1: Membuat Project Flutter Baru
- Buka Command Prompt
- Pastikan flutter sudah berhasil terinstall dengan mengetikkan "flutter"
- Buat project baru dengan mengetikkan "flutter create nama_project"
- Tunggu proses pembuatan project selesai
- Jika sudah selesai akan muncul pesan "Your flutter project is ready"
- Buka terminal VScode dan ketik command "flutter run"
- [Hasil Praktikum 1](images/praktikum-1.png)


## Dokumentasi Praktikum 2: Menghubungkan Perangkat Android
- Download & Install Android Studio terlebih dahulu
- Jalankan Android Studio & Install Android SDK
- Pada bagian SDK tools, centang "Android Studio Command-line Tools"
- Klik apply dan proses install component akan berjalan
- Jika sudah selesai, buka powershell dan ketik "flutter doctor"
- Kemudian open folder project yang sudah dibuat tadi Install plugins flutter dan dart
- Pergi ke setting - tools - devices mirroring - centang opsi paling atas
- Kemudian di hp android, aktifkan mode pengembang dan usb debungging
- Hubungkan Android dengan Laptop menggunakan USB, dan nanti pada android studio akan otomatis terdeteksi
- Karena saya menngunakan usb debugging, jadi untuk menampilkan view android saya menggunakan vysor.
- [Hasil Praktikum 2](images/connect%20android.png)


## Dokumentasi Praktikum 3: Membuat Repository GitHub
- Login akun Github terlebih dahulu
- Buat repository baru dengan nama "flutter-fundamental-part1"
- Buka terminal cmd ketik "git" untuk mengecek apakah git sudah terinstall/belum
- Jika belum download & install git terlebih dahulu
- Jika sudah pergi ke source control vscode
- Klik tanda + (stage changes) pada .gitignore / bisa menggunakan "git add ."
- Beri pesan comit "tambah gitignore" lalu klik commit / bisa menggunakan git add commit -m nama_comit
- Jika muncul notifikasi "add username and email for git", buka terminal vscode
- Kemudian ketikkan command 'git config --global user.name "Mannztx"' (contoh)
- Kemudian ketikkan command 'git config --global user.email "ardiansyahfirman136@gmail.com"' (contoh)
- Lalu ketik "git remote add origin https://github.com/Mannztx/flutter-fundamental-part1"
- Ubah nama branch default jadi main dengan mengetikkan "git branch -M main"
- Setelai itu kirim/push committ lokal ke github dengan menggunakan "git push -u origin main"
- Kemudian akan diminta memilih opsi login (token/with browser)
- [Kemudian jika seperti gambar ini berarti .gitignore berhasil di push ke github](images/praktikum-3.1.png)
- Lakukan perintah "git add ." untuk menambahkan semua file yang ada di change ke stage change
- Kemudian ketikkan "git commit -m "project hello_world""
- Setelah itu lakukan push ke github "git push"
- [Jika berhasil tampilan repo github akan seperti ini](images/praktikum-3.2.png)


## Dokumentasi Praktikum 4: Menerapkan Widget Dasar
- Buat folder dengan nama "basic_widgets" di dalam folder lib
- Buat file baru dengan nama "text_widget.dart", dan ketikkan code programnya, pada bagian nama sesuaikan
- Buat file baru dengan nama "image_widget.dart", dan ketikkan code programnya, sesuaikan lokasi penyimpanan gambarnya
- Kode program untuk kedua file tersebut berasal dari "https://flutter-codelabs.netlify.app/05-first-app-widget-dasar-flutter/#8"
- Kemudian import kedua file tersebut ke dalam file main.dart
- scroll kebawah pada baris 109/const ganti teks menjadi const MyTextWidget()/MyImageWidget(),
- Pergi ke file pubspec.yaml, hapus "#" baris assets dan dibawahnya tambahkan file gambar/logo
- Buka terminal ketik command "flutter run"
- [Hasil Praktikum 3: Text Widget](images/praktikum-4.1.png)
- [Hasil Praktikum 3: Image Widget](images/praktikum-4.2.png)