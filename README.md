BFS dan DFS adalah algortima yang digunakan untuk pencarian jalur. Contoh nya pada program ini, terdapat 12 jalur yaitu ABCDEFGHIJKL. Semua titik tersebut tidak terhubung langsung dengan titik-titik yg lainnya.
  
  Breadth first search (BFS) adalah algoritma yang melakukan pencarian secara melebar yang mengunjungi node secara preorder yaitu mengunjungi suatu node kemudian mengunjungi semua node yang bertetangga dengan node tersebut terlebih dahulu. Selanjutnya, node yang belum dikunjungi dan bertetangga dengan node-node yang tadi dikunjungi , demikian seterusnya.
  Algoritma ini memerlukan sebuah antrian q untuk menyimpan node yang telah dikunjungi. Node-node ini diperlukan sebagai acuan untuk mengunjungi node-node yang bertetanggaan dengannya. Tiap node yang telah dikunjungi masuk ke dalam antrian hanya satu kali. 
  Contoh : Kasus jalur terpendek yaitu dari C ke L dengan melalui jalur C, H, L.

  Sedangkan  Depth First Search (DFS) adalah salah satu algoritma penelusuran struktur graf / pohon berdasarkan kedalaman. Node ditelusuri dari root kemudian ke salah satu node anaknya ( misalnya prioritas penelusuran berdasarkan anak pertama [Node sebelah kiri] ), maka penelusuran dilakukan terus melalui node anak pertama dari node anak pertama level sebelumnya hingga mencapai level terdalam. 
  Setelah sampai di level terdalam, penelusuran akan kembali ke 1 level sebelumnya untuk menelusuri node anak kedua pada pohon biner [node sebelah kanan] lalu kembali ke langkah sebelumnya dengan menelusuri node anak pertama lagi sampai level terdalam dan seterusnya.
  
![dfsbfs](https://user-images.githubusercontent.com/44889084/111903268-0171b280-8a74-11eb-8cb7-244b46628dc5.png)
Noted:
Untuk menganalisis program ini disarankan untuk membuat sebuah akar pohon, yang mana akar pohon tersebut akan sangat membantu pada saat melihat rute terdekat.
Ketika memasukan jalur tidak sesuai dengan yang ada pada source code tersebut maka akan berakhir dengan 'mohon maaf node yang kalian pilih tidak ada'. Contohnya jika anda memasukan awal : L, Masukan akhir : M. Karena jalur tujuan M tidak disediakan.
