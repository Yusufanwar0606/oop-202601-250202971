# Catatan Minggu 05: Abstraction
## Yang saya kerjakan
Pada minggu ini saya mempelajari dan menerapkan konsep abstraction pada sistem. Saya mengubah class Aset menjadi abstract class sehingga hanya bisa digunakan sebagai dasar untuk class turunannya. Selain itu, saya juga membuat interface untuk fitur peminjaman serta menambahkan beberapa strategi perhitungan denda yang dapat digunakan sesuai kebutuhan.

## Keputusan desain
Saya memilih menjadikan Aset sebagai abstract class karena objek aset tidak perlu dibuat secara langsung. Penggunaan interface juga membantu memisahkan aturan peminjaman dari implementasi masing-masing aset. Dengan struktur ini, kode menjadi lebih rapi dan lebih mudah dikembangkan jika nantinya ada jenis aset baru.

## Kendala
Saat menerapkan abstraction, saya cukup bingung ketika harus mengubah class yang sebelumnya biasa menjadi abstract class. Perubahan tersebut membuat beberapa bagian program ikut terkena dampaknya sehingga muncul error yang perlu diperbaiki satu per satu. Meskipun tujuannya agar struktur kode lebih rapi, saya masih perlu membiasakan diri dengan pola seperti ini karena sebelumnya belum sering menggunakannya.

## Penggunaan AI
Alat yang dipakai: Claude
Bagian yang dibantu AI: Analisis error setelah mengubah Aset menjadi abstract class serta penyesuaian implementasi interface.
Prompt utama:
- Jelaskan error setelah mengubah class menjadi abstract class.
- Bagian mana saja yang perlu disesuaikan ketika menggunakan abstract class dan interface?
- Apa perbedaan abstract class dan interface dalam kasus ini?
Yang saya ubah atau tolak dari saran AI, dan alasannya:
- Beberapa contoh implementasi tidak digunakan secara langsung karena saya perlu menyesuaikannya dengan class dan method yang sudah ada pada project.

Satu hal yang saya pahami lebih baik sekarang:
Saya menjadi lebih paham bahwa abstraction memang membutuhkan penyesuaian di beberapa bagian program, tetapi hasilnya membuat struktur kode menjadi lebih rapi dan mudah dikembangkan.