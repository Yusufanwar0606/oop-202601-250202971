# Minggu 2: Struktur OOP: Class, Object, Encapsulation

## Yang saya kerjakan
Mengisi class dengan objek dan encapsulation.membuat field private, constructor, getter, dan setter untuk mengelola data aset. Validasinya juga ditambahkan agar data yang dimasukkan tetap sesuai aturan.
## Keputusan 
Saya menggunakan trim() saat validasi untuk mencegah input yang hanya berisi spasi dianggap valid. Namun, saya tidak mengubah format huruf menjadi huruf besar atau kecil karena aturan tugas hanya mewajibkan validasi null dan kosong. Setter untuk kode juga tidak dibuat agar kode tidak dapat diubah setelah objek dibuat.

## Kendala
pada bagian "public Aset(String kode, String nama)" ada masalah dalam codinganya yang dimana perintahnya tidak paham bahasanya dan mengatasinya memperbaiki dengan mengganti codingannya sesuai bahasa yg dipahami oleh javanya

## Penggunaan AI
- Alat yang dipakai: claude
- Bagian yang dibantu AI: kelas aset.java dan beberapa metode getter/setter
- Prompt utama: 
    - tugas week duanya di suruh ngapain dan berikan penjelasannya dari awal sampai akhir dan perbarisnya dijelaskan
- Yang saya ubah atau tolak dari saran AI, dan alasannya: Saya menghapus throw new UnsupportedOperationException karena menyebabkan error sebelum validasi berjalan. Method bisaDipinjam(), getJenis(), dan hitungDenda() tidak saya ubah karena merupakan tugas minggu 3–5. Saya juga tidak membuat setKode() karena kode tidak boleh diubah setelah objek dibuat. Error pada wajibIsi() saya perbaiki dengan menambahkan method tersebut.
- Satu hal yang saya pahami lebih baik sekarang:
