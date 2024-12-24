# FinalProjectIF4021_118140094
## Filter Suap-Suap

Hendry Kurniawan  118140094  hendrykurr

### Deskripsi
Filter ini adalah aplikasi real-time yang menambahkan efek gambar katak ke wajah pengguna dengan menggunakan teknologi MediaPipe dan OpenCV. Menggunakan deteksi wajah, gambar katak disesuaikan dengan posisi dan pembukaan mulut pengguna, menciptakan efek interaktif. Dengan transparansi gambar dan ukuran yang menyesuaikan ekspresi wajah, aplikasi ini menawarkan pengalaman filter wajah yang halus dan personal. Proyek ini cocok untuk hiburan, media sosial, dan eksperimen kreatif, serta dapat dengan mudah dikembangkan untuk efek wajah lainnya.

### Instalasi dan penggunaan
#### **1. Persyaratan Sistem**

Pastikan Anda memiliki perangkat dengan sistem operasi Windows, macOS, atau Linux, serta kamera untuk menangkap gambar real-time.

#### **2. Instalasi Paket yang Dibutuhkan**

Program ini menggunakan beberapa pustaka Python yang perlu diinstal terlebih dahulu. Ikuti langkah-langkah berikut untuk menginstalnya:

a. Install Python

Pastikan Anda sudah menginstal Python (versi yang digunakan dalam pengembanga filter ini adalan 3.12.4). Jika belum, Anda bisa mengunduhnya dari situs resmi Python.

b. Install Pustaka yang Dibutuhkan

Buka terminal atau command prompt dan jalankan perintah berikut untuk menginstal pustaka yang diperlukan:

**pip install mediapipe opencv-python numpy**

Pustaka yang diinstal:

mediapipe: Untuk mendeteksi wajah dan landmark wajah.
opencv-python: Untuk menangani pengolahan gambar dan video.
numpy: Untuk manipulasi array dan gambar.

#### **3. Mempersiapkan Gambar Katak**

Siapkan gambar katak yang memiliki saluran alpha (transparansi). Pastikan gambar tersebut berformat PNG.
Gambar katak dapat diunduh pada folder data, dengan nama katak.png
Buat folder data, lalu simpan gambar katak didalamnya

#### **4. Menjalankan Program**

Setelah semua pustaka diinstal dan gambar hewan disiapkan, Anda dapat menjalankan program dengan langkah berikut:

a. Menyiapkan Kode Program

Salin seluruh kode program yang ada pada file main.ipynb ke dalam sebuah file Python, misalnya filter_suap.py.

b. Menjalankan Program

Buka terminal atau command prompt, arahkan ke folder tempat file Python disimpan, dan jalankan perintah berikut:

**python filter_suap.py**

Program akan membuka jendela kamera dan menampilkan efek gambar hewan yang mengikuti pergerakan mulut Anda.

#### **5. Menggunakan Program**

Filter Wajah: Saat program berjalan, Anda akan melihat gambar katak yang muncul di area mulut Anda dalam jendela kamera.

Keluar dari Program: Untuk keluar dari program, tekan tombol ESC pada keyboard. Program akan berhenti dan menutup jendela kamera.

#### **6. Troubleshooting**

Jika kamera tidak terdeteksi, pastikan perangkat kamera Anda terhubung dengan baik dan aktif.

Jika program tidak berjalan, pastikan semua pustaka telah terinstal dengan benar.

Dengan mengikuti instruksi ini, Anda akan dapat menjalankan program filter wajah dengan gambar hewan secara mudah dan menyenangkan!
