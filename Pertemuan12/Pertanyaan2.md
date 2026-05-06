1. Mengapa digunakan keyword break pada fungsi remove?
Karena setelah node ditemukan dan dihapus, perulangan harus langsung dihentikan agar tidak melanjutkan pencarian yang tidak perlu dan mencegah error akibat pointer yang sudah berubah.
2. Kegunaan kode berikut :Baris pertama menghapus node target dengan menghubungkan node sebelumnya langsung ke node sesudah target. Baris kedua mengecek apakah node yang dihapus adalah node terakhir — jika iya, maka tail diperbarui ke node temp.
