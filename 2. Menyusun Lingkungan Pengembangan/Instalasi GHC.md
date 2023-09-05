# Materi Instalasi GHC dan GHCi

Daftar Isi
• Pendahuluan
• Memasang GHC pada Mac OS
• Memasang GHC pada Linux
• Memasang GHC pada Windows
• Kesimpulan

## Pengantar

Menginstal GHC untuk Pengembangan Haskell di Mac OS, Linux, dan Windows dengan mudah menggunakan alat yang tepat. Dengan menggunakan GHCup, Anda dapat dengan mudah menginstal versi GHC tertentu dan membuat lingkungan pengembang Haskell yang segar. Baik Anda menggunakan Mac OS, Linux, atau Windows, GHCup menyediakan layanan lengkap. Jadi, mari kita mulai dan pasang GHCup di komputer Anda!

## Menginstal GHC di Mac OS.

Menginstal GHC di Mac OS dapat dilakukan dengan mudah dengan mengikuti beberapa langkah. Pertama, pastikan Anda telah menginstal llvm, disarankan melalui brew. Selanjutnya, pastikan bahwa toolchain terpapar pada PATH Anda. Setelah persyaratan ini terpenuhi, Anda dapat melanjutkan dengan instalasi. Gunakan perintah yang disediakan untuk mengunduh binary ghcup dan jalankan untuk interaktif menginstal Haskell Toolchain. Penting untuk dicatat bahwa perintah ini harus dieksekusi sebagai pengguna non-root/non-admin. Dengan langkah-langkah ini, Anda akan memiliki GHC terinstal di Mac OS Anda dalam waktu singkat. Selamat mengembangkan Haskell!

## Menginstal GHC di Linux

Untuk menginstal GHC di Linux, Anda dapat mengikuti langkah-langkah berikut:

1. Pastikan Anda telah menginstal paket distro yang diperlukan. Hal ini termasuk paket seperti curl, gcc, gmp, gmake, ncurses, perl5, libffi, dan libiconv. Jangan khawatir jika Anda tidak tahu apa itu, cukup menginstalnya.

2. Setelah Anda memiliki paket yang diperlukan, Anda dapat menggunakan alat praktis yang disebut ghcup untuk menginstal Haskell Toolchain. Ghcup seperti jin ajaib yang tahu segalanya tentang Haskell. Jalankan perintah berikut di terminal Anda: `curl --proto '=https' --tlsv1.2 -sSf https://get-ghcup.haskell.org | sh`.

3. Duduk dan bersantailah ketika ghcup melakukan tugasnya. Ini akan mengunduh biner yang diperlukan dan mengatur GHC di sistem Anda. Ingatlah untuk mengatur PATH Anda di file ~/.bashrc (atau sejenisnya) untuk menyertakan biner ghcup.

4. Itu saja! Sekarang Anda telah menginstal GHC di sistem Linux Anda. Saatnya untuk menaklukkan dunia pemrograman Haskell! Yah, mungkin mulailah dengan "Halo, Dunia" dulu. Langkah-langkah kecil, Anda tahu?

Sekarang Anda siap menulis kode Haskell yang indah di mesin Linux Anda. Selamat coding!

## Menginstal GHC di Windows

Menginstal GHC di Windows bisa sangat mudah. Pertama, Anda perlu mengunduh file biner ghcup dan meletakkannya di direktori yang sesuai. Kemudian, Anda harus menginstal MSYS2 dan menambahkan variabel lingkungan yang diperlukan ke sistem Anda. Akhirnya, jangan lupa untuk memperbarui PATH Anda untuk mencakup direktori GHC dan ghcup. Secara keseluruhan, proses instalasi memastikan bahwa Anda memiliki lingkungan pengembangan Haskell yang solid pada mesin Windows Anda. Happy coding!

## Kesimpulan.

Menginstal GHC untuk Pengembangan Haskell di Mac OS, Linux, dan Windows sangat mudah! Ikuti langkah-langkah sederhana ini untuk memulai. Untuk pengguna Mac OS, menginstal GHC semudah mengklik tombol. Pengguna Linux dapat dengan cepat menginstal GHC dengan menggunakan package manager pilihan mereka. Dan untuk pengguna Windows, jalankan skrip PowerShell untuk memulai GHC. Tidak lebih sederhana dari itu! Selamat coding Haskell!
