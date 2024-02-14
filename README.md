# katalon-finalmobile-RizkyAriSaktiaPasi

## Test Case Login
1. memulai aplikasi dengan menggunakan file APK yang terletak di lokasi C:\\Users\\rizky\\Downloads\\Advantage+demo+3.2.apk
2. Mengetuk elemen dengan test object yang sesuai. Pada kasus ini, elemen yang ditargetkan adalah label menu
3. Mengetuk elemen dengan test object yang sesuai. Pada kasus ini, elemen yang ditargetkan adalah login
4. Mengisi teks pada elemen username dengan variabel Username (karena nanti digunakan data binding)
5. Mengisi teks pada elemen password dengan variabel Password (karena nanti digunakan data binding)
6. menyembunyikan keyboard setelah mengisi teks
7. Mengetuk tombol LOGIN
8. Verifikasi kondisi dengan if else (Script kemudian melakukan verifikasi apakah pesan “Incorrect user name or password” muncul)
9. Jika pesan tersebut muncul, maka akan mencetak pesan “username atau password salah, silahkan klik lupa password atau mendaftar”
10. Jika tidak, maka akan mencetak pesan “Berhasil Login” dan mengetuk tombol NO untuk ketampilan berikutnya

## Test Case Checkout
1. memulai aplikasi dengan menggunakan file APK yang terletak di lokasi C:\\Users\\rizky\\Downloads\\Advantage+demo+3.2.apk
2. Mengetuk elemen dengan test object yang sesuai. Pada kasus ini, elemen yang ditargetkan adalah label menu
3. Mengetuk elemen dengan test object yang sesuai. Pada kasus ini, elemen yang ditargetkan adalah login
4. Mengisi teks pada elemen username dengan dika12
5. Mengisi teks pada elemen username dengan Dika12
6. Mengetuk tombol LOGIN
7. Mengetuk tombol NO untuk ketampilan berikutnya
8. Verifikasi kondisi dengan if else (Script kemudian melakukan verifikasi apakah elemen “Keranjang Kosong” muncul)
9. Jika elemen tersebut muncul, maka akan mencetak pesan “keranjang kosong, silahkan tambahkan barang”
10. Jika tidak, maka akan mengeklik tombol cekout, kemudian tombol PAY NOW, dan memastikan elemen “verify sukses cekout” muncul sebelum mencetak pesan “berhasil checkout”

Link video
 
