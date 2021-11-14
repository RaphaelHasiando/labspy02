# labspy02
# Buat program sederhana dengan input tiga buah bilangan, dari ketiga bilangan tersebut tampilkan bilangan terbesarnya. Gunakan statement 'if'

Pertama, buatlah tiga variable untuk tiga bilangan dan juga int(input("")) ke dalam tiga variable tersebut untuk memasukkan nilai ke dalam program.
###
    bilangan_1 = int(input("Bilangan 1 = "))
    bilangan_2 = int(input("Bilangan 2 = "))
    bilangan_3 = int(input("Bilangan 3 = "))

Lalu, gunakan if statement dari ketiga bilangan untuk menentukan nilai yang tertinggi. Contoh:

Kondisi 1 : jika bilangan 1 lebih besar daripada bilangan 2 dan 3, maka kita buat...
###
    if bilangan_1 > bilangan_2 and bilangan_1 > bilangan_3:
      print(f"Bilangan 1 ({bilangan_1}) adalah bilangan terbesar")

Kondisi 2 : bilangan 2 lebih besar daripada 1 dan 3, maka kita buat...
### 
    elif bilangan_2 > bilangan_3:
      print(f"Bilangan 2 ({bilangan_2}) adalah bilangan terbesar")

Kondisi 3 : bilangan 3 lebih besar daripada 1 dan 2, maka kita buat...
###
    else:
      print(f"Bilangan 3 ({bilangan_3}) adalah bilangan terbesar")

Ketika tiga bilangan itu mendapatkan nilai yang sama, Kondisi 3 selalu hasilnya tapi nilai yang sama dengan 2 bilangan tersebut. Maka kita pisahkan menjadi dua bagian. Bagian yang nilainya tidak sama dan nilainya sama dengan.

Nilai yang sama :
### 
    if bilangan_1 == bilangan_2 == bilangan_3:

Nilai yang tidak sama :
###
    if bilangan_1 != bilangan_2 or bilangan_1 != bilangan_3:
      print(Tiga bilangan tersebut adalah sama)

Untuk Tiga kondisi sebelumnya terletak di Kondisi 'Nilai yang tidak sama' jika hasilnya berbeda. Gambarnya akan seperti ini

#### 
     if bilangan_1 != bilangan_2 or bilangan_1 != bilangan_3:
       if bilangan_1 > bilangan_2 and bilangan_1 > bilangan_3:
         print(f"Bilangan 1 ({bilangan_1}) adalah bilangan terbesar")
       elif bilangan_2 > bilangan_3:
         print(f"Bilangan 2 ({bilangan_2}) adalah bilangan terbesar")
       else:
         print(f"Bilangan 3 ({bilangan_3}) adalah bilangan terbesar")

     if bilangan_1 == bilangan_2 == bilangan_3:
       print("Tiga bilangan tersebut adalah sama")


