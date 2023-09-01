# Materi Memahami Pemrograman Fungsional 

Berikut adalah daftar 30 konsep dalam pemrograman fungsional dengan istilah teknis yang lebih mendalam: 

1. First-Class Functions: Fungsi yang dapat diperlakukan sebagai nilai dan dapat dioperasikan seperti objek lainnya.
2. Immutability: Karakteristik data yang tidak berubah setelah dibuat, mencegah perubahan nilai setelah inisialisasi.
3. Referential Transparency: Properti ekspresi di mana setiap pemanggilan fungsi dengan argumen yang sama selalu menghasilkan nilai yang sama.
4. Pure Functions: Fungsi yang hanya bergantung pada argumen input dan tidak memiliki efek samping yang dapat mempengaruhi lingkungan luar.
5. Function Composition: Penggabungan beberapa fungsi menjadi satu untuk membentuk alur kerja yang lebih besar.
6. Recursion: Pendekatan pengulangan di mana fungsi memanggil dirinya sendiri untuk menyelesaikan masalah.
7. Higher-Order Functions: Fungsi yang menerima atau mengembalikan fungsi lain sebagai argumen atau nilai.
8. Closure: Lingkungan eksekusi fungsi yang menyimpan referensi ke variabel luar yang didefinisikan dalam konteks yang lebih tinggi.
9. Partial Application and Currying: Proses menerapkan sebagian argumen ke fungsi, menghasilkan fungsi yang memiliki tanda tangan yang lebih sedikit.
10. Monad: Struktur data yang mengelola alur komputasi dengan memisahkan nilai dari konteks dan mengendalikan efek samping.
11. Lazy Evaluation: Pendekatan evaluasi di mana ekspresi dievaluasi hanya ketika hasilnya diperlukan.
12. Pattern Matching: Teknik membandingkan struktur data dengan pola yang ditentukan untuk pengambilan keputusan.
13. Map, Filter, and Reduce: Operasi dasar untuk memanipulasi dan mengolah koleksi data. 
14. Transduction: Proses menerapkan serangkaian transformasi pada aliran data dalam satu iterasi. 
15. Monoid and Semigroup: Struktur aljabar yang mendefinisikan operasi penggabungan dengan properti tertentu. 
16. Immutable Data Structures: Struktur data yang tidak dapat diubah setelah dibuat. 
17. Tail Call Optimization: Optimasi yang menghindari penumpukan tumpukan dalam rekursi akhir. 
18. Stream and Generator: Abstraksi untuk menghasilkan aliran data. 
19. Lens: Abstraksi untuk mengakses dan memodifikasi bagian tertentu dari struktur data. 
20. Anonymous Functions (Lambda): Fungsi tanpa nama yang sering digunakan untuk operasi sederhana. 
21. Monad Transformer: Struktur yang menggabungkan beberapa monad untuk mengelola efek samping dan pemrosesan kompleks. 
22. Functional Data Flow: Pendekatan menggabungkan fungsi-fungsi untuk mengatur aliran data dalam program. 
23. Functional Optics: Abstraksi untuk memanipulasi dan mengakses data melalui berbagai tipe optik. 
24. Parallel and Concurrent Programming: Penggunaan konsep fungsional dalam mengelola komputasi paralel dan konkuren. 
25. Effector: Struktur yang mengelola efek samping di dalam pemrograman fungsional. 
26. Monadic Transformations: Konversi dari satu tipe monad ke tipe monad lainnya. 
27. Algebraic Data Types: Jenis data yang didefinisikan oleh kumpulan konstruktor aljabar. 
28. Typeclasses: Abstraksi yang memungkinkan operasi yang didefinisikan di berbagai tipe data. 
29. Concurrency Abstractions: Konsep yang mengelola eksekusi konkuren dalam lingkungan fungsional. 
30. Function Chaining: Penggabungan beberapa operasi pada objek dengan mengembalikan objek itu sendiri setelah setiap operasi.
31. Type Inference: Proses di mana tipe data variabel dapat ditentukan oleh kompiler berdasarkan nilai yang diberikan.
32. Curried Functions: Fungsi-fungsi yang secara otomatis mengembalikan fungsi lain sebagai hasil jika argumen tidak cukup.
33. Algebraic Laws: Hukum matematika yang diterapkan pada operasi pada tipe data aljabar.
34. Thunk: Ekspresi yang dievaluasi hanya saat nilai itu diperlukan.
35. Effect System: Sistem tipe yang mengidentifikasi dan mengelola efek samping dalam program.
36. Property-Based Testing: Pendekatan pengujian di mana properti yang diharapkan dari kode didefinisikan, dan uji dihasilkan berdasarkan properti tersebut.
37. Higher-Kinded Types: Tipe-tipe yang menerima tipe lain sebagai argumen dan menghasilkan tipe lain sebagai hasil.
38. Imperative vs. Functional Composition: Membandingkan cara komposisi dalam paradigma imperatif dan fungsional.
39. Continuation: Objek yang merepresentasikan kembali dari sebuah komputasi.
40. State Monad: Monad yang mengelola status dalam aplikasi fungsional.
41. Reader Monad: Monad yang memfasilitasi berbagi nilai yang dapat dibaca di seluruh komputasi.
42. Free Monad: Struktur yang memungkinkan konstruksi monad dengan menggabungkan langkah-langkah dasar.
43. Strict vs. Non-Strict Evaluation: Membandingkan pendekatan evaluasi ketat dan tidak ketat.
44. Total dan Partial Functions: Fungsi total yang didefinisikan untuk setiap input, dan fungsi parsial yang mungkin tidak didefinisikan untuk beberapa input.
45. Type Constructor: Fungsi yang mengambil tipe dan mengembalikan tipe lain.
46. Type Erasure: Proses menghilangkan informasi tipe selama kompilasi.
47. Tail Recursion: Jenis rekursi di mana pemanggilan rekursif berada dalam posisi terakhir fungsi.
48. Laziness and Thunks: Evaluasi yang ditunda hingga diperlukan dengan penggunaan thunks.
49. Monad Laws: Hukum matematika yang menggambarkan properti monad dalam pemrograman fungsional.
50. Parallelism Strategies: Teknik mengelola komputasi paralel untuk meningkatkan kinerja.

Konsep diatas adalah penejelasan singkat tentang konsep-konsep di fungsional programming, teman-teman bisa bisa pelajari di repository di bawah ini.

https://github.com/wisn/jargon-pemrograman-fungsional
atau
https://github.com/hemanth/functional-programming-jargon

Untuk proses implementasi nya temam-teman bisa coba setelah mempelajari dasar-dasar haskell.

Semua konsep ini memainkan peran penting dalam pemrograman fungsional dan dapat diterapkan dalam pengembangan perangkat lunak untuk menciptakan solusi yang lebih deklaratif, terstruktur, dan dapat dipahami. 

