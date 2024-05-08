# Tutorial-10
---
#### Nama: Naufal Ichsan
#### NPM: 2206082013
#### Kelas: Adpro A
---
### Refleksi
![ss 1](assets/images/ss1.png)
Dari hasil pengamatan, dapat dilihat bahwa fungsi async akan dijalankan di luar fungsi utama yang menjalankannya. Oleh karena itu, "hey hey" bisa saja dieksekusi lebih dulu sebelum "howdy!" dan "done!" karena "hey hey" berada di luar fungsi async yang akan melanjutkan program dan menjalankan ```println!("hey hey");``` saat fungsi async masih menunggu hasil dari future.
