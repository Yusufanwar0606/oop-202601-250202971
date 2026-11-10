# Catatan Minggu 03 : Inheritance

## Yang saya kerjakan
pada praktikum ini , saya membuat hierarki class aset dengan memanfaatkan inheritance. saya menambahkan class Ruang, Laptop, dan AlatLab yang mewarisi class Aset , kemudian membuat konstruktor yang memanggil super agar validasi pada class induk tetap digunakan .

## Keputusan desain
keputusan saya adalah menempatkan atribut yang dimiliki semua aset pada class Aset agar tidak terjadi duplikasi kode. sementara itu atribut yang dimiliki jenis aset tertentu seperti kapasitas pada ruang, spesifikasi dan nomor inventaris pada laptop ,serta laboratorium dan tingkat risiko pada AlatLab, ditempatkan di masing-masing subclass.

## Kendala
kendala yang saya temui adalah saat mengubah/menambahkan code ,terjadinya error karena ada yang salah atau lupa menambahkan kodenya 

## Penggunaan AI
- Alat yang dipakai: claude
- Bagian yang dibantu AI: Penjelasan konsep inheritance, penggunaan super(), dan pengecekan struktur class.
- Prompt utama: 
    - 
    -
- Yang saya ubah atau tolak dari saran AI, dan alasannya:
- Satu hal yang saya pahami lebih baik sekarang:
