# Jawaban Pertanyaan Pemahaman - Tugas 3 Komputasi Awan

(Silakan sesuaikan dengan kalimat Anda sendiri, lalu masukkan ke PDF bukti bersama 6 tangkapan layar.)

**1. Apa perbedaan fungsi Google Drive sebagai SaaS dengan GitHub Pages sebagai layanan untuk mempublikasikan website?**
Google Drive adalah SaaS, yaitu aplikasi siap pakai untuk menyimpan, mengelola, dan membagikan berkas. Pengguna tinggal memakainya tanpa mengurus server. GitHub Pages berfungsi sebagai layanan hosting yang menyajikan berkas HTML, CSS, dan gambar sebagai website yang dapat dibuka lewat URL publik. Jadi Google Drive berfokus pada penyimpanan dan berbagi berkas, sedangkan GitHub Pages berfokus pada menayangkan website ke internet.

**2. Apa yang dimaksud dengan deployment dan URL publik pada tugas ini?**
Deployment adalah proses memindahkan berkas website dari laptop ke server cloud agar website dapat dijalankan dan diakses orang lain. Pada tugas ini deployment dilakukan dengan mengunggah berkas ke repositori GitHub lalu mengaktifkan GitHub Pages. URL publik adalah alamat internet hasil deployment tersebut, sehingga siapa pun dapat membuka website tanpa meminta izin akses.

**3. Setelah website dipublikasikan, di manakah berkas website tersimpan dan dijalankan?**
Berkas website tersimpan di repositori GitHub dan disajikan oleh server milik GitHub Pages. Server inilah yang mengirimkan halaman HTML, CSS, dan gambar ke peramban setiap kali ada pengunjung. Berkas tidak dijalankan dari laptop saya, melainkan dari infrastruktur cloud milik GitHub.

**4. Mengapa website tetap dapat diakses ketika laptop mahasiswa dimatikan?**
Karena website berjalan di server GitHub yang menyala terus, bukan di laptop. Laptop hanya dipakai untuk menyiapkan dan mengunggah berkas. Setelah berkas tersimpan di cloud, pengunjung berhubungan langsung dengan server GitHub, sehingga kondisi laptop tidak memengaruhi ketersediaan website.

**5. Apa yang terjadi ketika perubahan versi 2 diunggah dan dipublikasikan ulang?**
Perubahan yang diunggah dicatat sebagai commit baru pada repositori. GitHub Pages kemudian membangun dan menayangkan ulang website dari commit terbaru tersebut. URL tetap sama, tetapi isinya sudah berubah menjadi versi 2 setelah proses selesai dan halaman dimuat ulang. Ini menunjukkan bahwa pembaruan di cloud dapat dilakukan tanpa mengganti alamat website.

**6. Risiko privasi apa yang dapat muncul pada repositori dan website publik, serta bagaimana cara menguranginya?**
Repositori dan website publik dapat dibaca siapa saja, sehingga data pribadi seperti nomor telepon, alamat, kata sandi, atau API key bisa terbaca bahkan tersimpan di riwayat commit. Risiko ini dikurangi dengan hanya mengunggah data yang aman dipublikasikan, tidak menaruh kata sandi atau kunci rahasia di dalam berkas, memeriksa ulang isi berkas sebelum commit, dan memakai foto serta informasi pribadi secukupnya.
