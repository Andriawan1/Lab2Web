**<b>Langkah-langkah dalam pemberian warna ataupun desain dengan menggunakan CSS</b>**

**1. Membuat Dokumen HTML**
    

- Buatlah dokumen HTML dengan menggunakan koodingan dasar pada HTML, Contohnya sebagai berikut:
![e1](https://user-images.githubusercontent.com/81581236/113515920-93fc7080-95a1-11eb-9b53-fbb2830fd0b2.PNG)

- Lalu jalankan VSCODE dengan mengklik menu terminal yang berada pada kiri atas pada VS CODE, dan pilih Run Active File. Otomatis langsung terhubung ke Web Browser. contohnya pada gambar:
 ![ee](https://user-images.githubusercontent.com/81581236/113516135-da9e9a80-95a2-11eb-8bfc-93930fec67b5.PNG)
![e2](https://user-images.githubusercontent.com/81581236/113516140-e38f6c00-95a2-11eb-896b-984abdf293f4.PNG)

**2. Mendeklarasikan CSS Internal**
    
 

-  Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian Head dokumen.

![e3](https://user-images.githubusercontent.com/81581236/113516356-03735f80-95a4-11eb-9963-ebe7bc72996c.PNG)

Selanjutnya Simpan Perubahan pada coodingan anda dengan mengklik CTRL+S, dan lakukan refresh pada browser yang tadi untuk melihat hasil perubahannya.

![e4](https://user-images.githubusercontent.com/81581236/113516495-c196e900-95a4-11eb-9d7a-115d9e7431db.PNG)

**3. Menambahkan Inline CSS**

- Kemudian tambahakan deklarasi Inline CSS pada tag <p> seperti berikut.
![e5](https://user-images.githubusercontent.com/81581236/113516577-3407c900-95a5-11eb-8144-3efcdcd708b7.PNG)
- Simpan hasil  perubahan dengan CTRL+S, dan refresh kembali web Browser untuk melihat perubahannya.

![e6](https://user-images.githubusercontent.com/81581236/113516625-792bfb00-95a5-11eb-9d7c-2b004dca68a6.PNG)

**4. Membuat CSS Eksternal.**
- Buatlah File baru dengan nama style_eksternal.css dan kemudian buatlah deklarasi CSS berikut:

![e7](https://user-images.githubusercontent.com/81581236/113516664-b8f2e280-95a5-11eb-9854-f047e8490294.PNG)
- Kemudian tambahkan <link untuk merujuk File CSS yang telah dibuat pada bagian Head

![e8](https://user-images.githubusercontent.com/81581236/113516706-edff3500-95a5-11eb-9938-53a012708df6.PNG)
- selanjutnya refresh kembali browser untuk melihat perubahannya.

![e9](https://user-images.githubusercontent.com/81581236/113516741-23a41e00-95a6-11eb-8e67-e68ac5cfdfc5.PNG)

**5. Menambahkan CSS Selector**
- Selanjutnya menambahkan CSS Selector menggunakan Id dan Class Selector pada file style_eksternal.css, lalu tambahan Code berikut:

![e10](https://user-images.githubusercontent.com/81581236/113516826-a3ca8380-95a6-11eb-9f4f-07b8fc77846b.PNG)

- Kemudian simpan kembali dan refresh browser untuk melihat hasil perubannya.

![e14](https://user-images.githubusercontent.com/81581236/113576201-4fc4ab00-9649-11eb-91a1-9c7bfa7c3607.PNG)


6. Melaukan Validasi dokumen CSS dengan mengakses https://jigsaw.w3.org/css-validator/
![e12](https://user-images.githubusercontent.com/81581236/113517206-bf368e00-95a8-11eb-92e4-b6e921587c35.PNG)
![e13](https://user-images.githubusercontent.com/81581236/113517214-c52c6f00-95a8-11eb-85b8-2a60929d8b67.PNG)


Tugas !

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )
   
Penyelesaian:

2. Perbedaan pendeklarasian  CSS elemen h1 {...} dengan #intro h1{...}

   - h1 {...} adalah pendeklarasian elemen yang hanya merubah elemen pada "h1" yang sudah di tandai sedangkan.
   - #intro h1 {...} adalah pendeklarasian yang mengacu kepada pemberian atribut pada "h1" dengan menambahakan ID"intro".

3. Deklarasi yang akan ditampilkan adalah deklarasi Inline yang akan di tampilkan pada Web Browser
4. Apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi yang akan di tampilkan pada Web Browser adalah Class ID. Karena Class ID secara individu mewakili semua atribut yang ada. 
- untuk contohnya dapat kita lihat, pada gambar berikut:
![e15](https://user-images.githubusercontent.com/81581236/113592289-27e04200-965f-11eb-8702-fa4ea9cf0f42.PNG)
![e16](https://user-images.githubusercontent.com/81581236/113593270-6de9d580-9660-11eb-8423-00f92d630096.PNG)
untuk tampilan di Web Browsernya seperti gambar :
![e17](https://user-images.githubusercontent.com/81581236/113593352-89ed7700-9660-11eb-8c68-4574399820a9.PNG)

