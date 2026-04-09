Nama : Hazel Iqbal Izdihar Khotomi 
NIM : 25141011P

Slide 1: Review Pewarisan – Mengingat kembali konsep inheritance menggunakan keyword extends, penggunaan super() untuk konstruktor, dan @override untuk mengganti fungsi parent.

Slide 2: Pengantar Polimorfisme – Polimorfisme berarti "banyak bentuk", di mana objek dari subclass dapat dianggap sebagai objek dari superclass. Dart mendukung Runtime polymorphism melalui method overriding.

Slide 3: Polimorfisme dengan Inheritance – Referensi tipe parent dapat menampung objek child. Contohnya, variabel bertipe Bentuk bisa berisi objek Lingkaran atau Persegi.

Link Gist : https://gist.github.com/hazelkhotomi/eb0d43f1026ec43d979b8b113bb653a9
contoh code Dartpad : https://dartpad.dev/?id=eb0d43f1026ec43d979b8b113bb653a9

Slide 4: Manfaat Polimorfisme – Memberikan fleksibilitas kode, kemudahan dalam menambah tipe baru (extensibility), penggunaan kembali kode, dan kemudahan pemeliharaan.

Slide 5: Operator is dan as – is digunakan untuk mengecek tipe objek, sedangkan as digunakan untuk melakukan casting (mengubah tipe referensi secara paksa) agar bisa mengakses fitur spesifik milik subclass.

Link Gist : https://gist.github.com/hazelkhotomi/9abc3720927b0b95b9dd33e93e017619
contoh code Dartpad : https://dartpad.dev/?id=9abc3720927b0b95b9dd33e93e017619

Slide 6: Polimorfisme dengan List – Implementasi praktis dengan menyimpan berbagai objek subclass ke dalam satu List bertipe superclass, lalu menjalankan loop untuk memanggil method yang sama.

Slide 7 & 8: Abstraksi & Abstract Class – Abstraksi menyembunyikan detail dan fokus pada "apa" yang dilakukan. abstract class tidak bisa dibuat objeknya secara langsung dan dapat memiliki abstract method (tanpa isi).

Link Gist : https://gist.github.com/hazelkhotomi/cdc36491ef3bfc7371f53b6e81da31da
Link Dartpad : https://dartpad.dev/?id=cdc36491ef3bfc7371f53b6e81da31da

Slide 9: Abstract Method – Method yang wajib di-override oleh subclass karena tidak memiliki implementasi di kelas induknya.

Slide 10: Interface di Dart – Di Dart 3.0, semua kelas adalah implicit interface. Keyword implements digunakan untuk mewajibkan kelas mengikuti kontrak (semua method harus diimplementasi ulang).

Slide 11: Perbedaan extends vs implements – extends adalah hubungan "is-a" (mewarisi implementasi), sedangkan implements adalah hubungan "can-do" (hanya mewarisi kontrak/nama method).

Slide 12: Static Members – Properti atau method yang menempel pada kelas itu sendiri, bukan pada objek. Diakses langsung melalui nama kelas tanpa perlu instansiasi.

Slide 13 & 14: Studi Kasus – Implementasi nyata pada sistem pembayaran dan sistem perhitungan geometri (luas dan keliling) menggunakan abstract class dan implements.

Link Gist : https://gist.github.com/hazelkhotomi/1cf60a0539ede3777151e6b4318a9185 Link Dartpad : https://dartpad.dev/?id=1cf60a0539ede3777151e6b4318a9185

Latihan:
1. Buat abstract/interface class bekerja() Pekerja dengan method abstract/non abstract
2. Buat 3 class yang mengimplementasi: Programmer , Dokter ,
3. Buat list List<Pekerja> dan demonstrasikan polimorfisme
4. buat class "Tablet" (Mewarisi komputer,Kamera dan Telepon)
5. Buat Guru class MathUtils dengan static methods untuk factorial, cek bilangan prima, Membulatkan double ke desimal tertentu, Menghasilkan bilangan acak integer dan double dalam range [min, max], Menghitung rata-rata dari list angka, dan Menghitung median dari list angka

Link gist : https://gist.github.com/hazelkhotomi/d73bef7b71f270006abd09d95ac077c5
link dartpad : https://dartpad.dev/?id=d73bef7b71f270006abd09d95ac077c5

Challenge:
•
Buat sistem dengan: Abstract class: MediaPlayer
•
Interface: Playable , Pausable
•
Class implementasi: AudioPlayer , VideoPlayer

Link gist : https://gist.github.com/hazelkhotomi/5e7ee284f1271407d179b73a4e51f1e1
link dartpad : https://dartpad.dev/?id=5e7ee284f1271407d179b73a4e51f1e1
