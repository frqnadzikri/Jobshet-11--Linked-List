1. Mengapa baris pertama menghasilkan "Linked List Kosong"?
Karena sll.print() dipanggil sebelum data apapun ditambahkan, sehingga head == null dan kondisi isEmpty() bernilai true.
2. Kegunaan variable temp pada setiap method?
Sebagai pointer sementara untuk menelusuri (traverse) node-node dalam linked list tanpa mengubah posisi head atau tail.
3. Modifikasi 