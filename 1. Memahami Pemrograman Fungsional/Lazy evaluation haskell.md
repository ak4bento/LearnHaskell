# Materi lazy evaluation
Lazy evaluation adalah salah satu konsep penting dalam pemrograman fungsional, dan bahasa Haskell adalah salah satu bahasa yang mengelolanya dengan baik. Lazy evaluation, atau evaluasi malas, adalah teknik di mana ekspresi atau nilai dihitung hanya saat dibutuhkan, bukan pada saat ekspresi tersebut dievaluasi secara eksplisit. Ini memungkinkan untuk menghindari perhitungan yang tidak perlu dan meningkatkan efisiensi dalam program.
Dalam Haskell, lazy evaluation dicapai melalui penggunaan struktur data yang disebut "thunks" (dikenal juga sebagai "promises"). Thunks adalah representasi tertunda dari ekspresi yang akan dievaluasi hanya ketika nilainya benar-benar dibutuhkan. Berikut adalah cara Haskell mengelola evaluasi malas ini:

1. Call-by-Need (Demand-driven): Haskell menggunakan pendekatan "call-by-need", yang berarti ekspresi akan dievaluasi hanya jika hasilnya dibutuhkan dalam perhitungan selanjutnya. Ini memungkinkan untuk menunda evaluasi sebanyak mungkin.
2. Memoization: Haskell secara otomatis menyimpan hasil evaluasi yang telah dilakukan sehingga jika ekspresi yang sama harus dievaluasi lagi, nilainya akan diambil dari penyimpanan daripada dievaluasi ulang. Ini menghindari pengulangan perhitungan yang mahal.
3. Infinite Data Structures: Dalam Haskell, Anda dapat dengan mudah membuat struktur data tak terbatas seperti daftar tak terbatas. Nilai dari daftar tersebut akan dievaluasi secara bertahap sesuai dengan kebutuhan, dan Anda tidak perlu khawatir tentang eksekusi yang tak terbatas.
4. Strictness Annotations: Meskipun Haskell secara umum menerapkan lazy evaluation, Anda dapat menggunakan anotasi ketat (strictness annotations) untuk memaksa evaluasi segera pada beberapa ekspresi jika diperlukan.
5. Control over Laziness: Haskell juga memberikan kontrol yang baik atas laziness melalui bahasa pemrograman itu sendiri, seperti dengan menggunakan fungsi seq atau $! untuk mempengaruhi kapan evaluasi seharusnya terjadi.

Jika teman-teman butuh referensi mengenai ini kalian bisa lihat di wikipedia tentang [Evaluation strategy](https://en.wikipedia.org/wiki/Evaluation_strategy#Call_by_need) atau [Lazy Evaluation](https://wiki.haskell.org/Lazy_evaluation)

Ini adalah beberapa cara Haskell mengelola evaluasi malas. Konsep ini sangat bermanfaat dalam pemrograman fungsional, karena memungkinkan kita untuk mengekspresikan komputasi dengan lebih dekat kepada pemikiran matematis dan meminimalkan perhitungan yang tidak perlu.
