# Catatan Minggu 04: Polymorphism
## Yang saya kerjakan
Pada minggu ini saya menambahkan konsep polymorphism ke dalam sistem yang sedang saya kerjakan. Saya mengimplementasikan method hitungDenda() pada beberapa jenis aset seperti ruang, laptop, dan alat laboratorium yang masing-masing memiliki perhitungan denda yang berbeda. Selain itu, saya juga membuat fitur pencarian aset menggunakan method overloading agar pencarian bisa dilakukan dengan beberapa cara.

## Keputusan desain
Saya memutuskan menggunakan method overriding untuk hitungDenda() karena setiap jenis aset memiliki kebutuhan perhitungan yang berbeda. Dengan cara ini saya tidak perlu membuat banyak method dengan fungsi yang mirip. Saya juga menggunakan overloading pada fitur pencarian supaya pengguna bisa mencari aset menggunakan parameter yang sesuai kebutuhan.

## Kendala
Kendala yang saya alami adalah muncul beberapa error setelah menambahkan method overriding pada beberapa class. Saya juga sempat bingung menentukan bagian mana saja yang perlu diubah agar implementasi polymorphism dapat berjalan dengan benar. Untuk mengatasinya, saya memeriksa kembali hubungan antar class dan menelusuri error satu per satu sampai program dapat berjalan sesuai yang diharapkan.

## Penggunaan AI
Alat yang dipakai: Claude
Bagian yang dibantu AI: Analisis error pada implementasi polymorphism dan pengecekan method overriding.
Prompt utama:
- Jelaskan error yang muncul pada kode berikut.
- Bagian mana saja yang perlu diubah agar method overriding berjalan dengan benar?
- Apa penyebab method yang di-override tidak terpanggil?

Yang saya ubah atau tolak dari saran AI, dan alasannya:
    Tidak semua perubahan yang disarankan langsung diterapkan karena beberapa bagian tidak sesuai dengan struktur project yang sudah dibuat.
    
Satu hal yang saya pahami lebih baik sekarang:
Saya lebih memahami bagaimana proses pemanggilan method yang berbeda dapat terjadi meskipun menggunakan referensi parent class.