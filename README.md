# FinalProjectIF4021_118140094
## Filter Suap-Suap

Nama    : Hendry Kurniawan  
NIM     : 118140094
Github  : hendrykurr
Matkul  : Sistem Informasi Multimedia
Kode    : IF4021
Pengampu: Martin Clinton Tosima Manullang, S.T., M.T.

### Deskripsi
Filter ini adalah aplikasi real-time yang menambahkan efek gambar katak ke wajah pengguna dengan menggunakan teknologi MediaPipe dan OpenCV. Menggunakan deteksi wajah, gambar katak disesuaikan dengan posisi dan pembukaan mulut pengguna, menciptakan efek interaktif. Dengan transparansi gambar dan ukuran yang menyesuaikan ekspresi wajah, aplikasi ini menawarkan pengalaman filter wajah yang halus dan personal. Proyek ini cocok untuk hiburan, media sosial, dan eksperimen kreatif, serta dapat dengan mudah dikembangkan untuk efek wajah lainnya.

### Instalasi dan penggunaan
#### **1. Persyaratan Sistem**

Pastikan Anda memiliki perangkat dengan sistem operasi Windows, macOS, atau Linux, serta kamera untuk menangkap gambar real-time.
Pastika juga Anda memiliki Anaconda atau Miniconda untuk mengelola environment dan pustaka Python. Jika belum memilikinya, Anda bisa mendownload Miniconda pada link berikut : https://docs.conda.io/en/latest/miniconda.html.

#### **2. Download Project**

Sebelum lanjut ke tahap berikutnya, Anda perlu mendownload seluruh file project ini, dan tempatkan pada satu folder terpisah.

#### **3. Membuat Environment untuk Program**

Setelah Miniconda terinstal, Anda dapat membuat lingkungan (environment) Python yang terisolasi untuk menjalankan program ini.

1. Buka Command Prompt atau Terminal
Di Windows, buka Anaconda Prompt atau Command Prompt.
Di macOS/Linux, buka Terminal.

2. Buat Environment Baru dengan Miniconda
Di terminal atau command prompt, arahkan direktori yang aktif ke folder tempata Anda menyimpan file yang Anda downliad dari repository ini.
Kemudian jalankan perintah berikut untuk membuat environment baru:

**conda create --name filter_suapsuap python=3.12.4**

**filter_suapsuap** adalah nama environment yang Anda buat, Anda dapat mengganti namanya jika diinginkan. **python=3.12.4** memastikan Anda menggunakan versi Python 3.12.4.

Setelah selesai, aktifkan environment baru ini dengan perintah:

**conda activate filter_suapsuap**

#### **4. Install Pustaka yang Dibutuhkan**

Setelah environment Python 3.12.4 aktif, Anda perlu menginstal pustaka yang dibutuhkan.
Pada terminal atau command prompt, jalankan perintah berikut untuk menginstal pustaka yang diperlukan:

**pip install mediapipe opencv-python numpy**

Pustaka yang diinstal:

- mediapipe: Untuk mendeteksi wajah dan landmark wajah.
- opencv-python: Untuk menangani pengolahan gambar dan video.
- numpy: Untuk manipulasi array dan gambar.

Jika ada masalah saat menginstal beberapa pustaka, Anda bisa mencoba menginstalnya menggunakan conda:

**conda install mediapipe opencv**

#### **5. Menjalankan Program Menggunakan Jupyter Notebook**

Setelah menginstal semua pustaka yang diperlukan, jalankan Jupyter Notebook dengan perintah:

**jupyter notebook**

Perintah ini akan membuka Jupyter Notebook pada browswer Anda.

Jupyter Notebook akan otomatis membuka folder tempat Anda menyimpan file project ini.
Buka file **main.ipynb** lalu tekan  **Shift + Enter** pada setiap sel untuk menjalankan program secara berurutan.

#### **6. Menggunakan Program**

Filter Wajah: Saat program berjalan, Anda akan melihat gambar katak yang muncul di area mulut Anda dalam jendela kamera.

Keluar dari Program: Untuk keluar dari program, tekan tombol ESC pada keyboard. Program akan berhenti dan menutup jendela kamera.

#### **7. Troubleshooting**

Jika kamera tidak terdeteksi, pastikan perangkat kamera Anda terhubung dengan baik dan aktif.

Jika program tidak berjalan, pastikan semua pustaka telah terinstal dengan benar.

Jika mediapipe tidak dapat diinstal atau tidak berjalan dengan benar, coba turunkan versi Python ke 3.10 atau 3.11, karena mediapipe kadang-kadang memerlukan versi Python yang lebih stabil dan lebih lama.
