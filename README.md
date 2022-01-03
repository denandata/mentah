# Pertemuan 14
## Eksepsi
## Irvan Ardiyansyah

>Implementasikan penggunaan eksepsi pada lab-lab sebelumnya untuk mengatasi error yang ditimbulkan.

## Penjelasan 

**Eksepsi** ( exception ) : Merupakan suatu kesalahan (error) yang terjadi saat proses eksekusi program sedang berjalan, Kesalahan ini akan menyebabkan program berakhir dengan tidak normal.

**Blok Try and Except :**
* Setiap kode program yang memungkinkan terjadinya eksepsi, maka
perlu untuk di tempatkan di dalam blok **try** .
* Ketika ada kesalahan, maka kode di blok **except** akan dieksekusi.
* Jika program tidak memiliki kesalahan, maka blok except
akan diabaikan.

Disini saya menggunakan eksepsi di bagian input data. Berikut adalah kode tambahannya:

- Latihan1

![image](https://user-images.githubusercontent.com/84762007/147787222-6120aa08-d014-4742-9369-b274b30bf2b3.png)

Syntaxnya :

```bash
while True:
        try:
            Angka = int(input("Masukan Angka\t: "))
            if nim == "":
                print("Masukan Nilai N: 5")
            else:
                break
        except:
            print("Harap Masukan Angka")
        else:
            break
```

- Latihan2

![image](https://user-images.githubusercontent.com/84762007/147787270-2f0ac361-572f-4c58-b310-be3d10794b65.png)

Syntax nya :

```     
while True:
        try:
            Laba = int(input("Masukan Laba\t: "))
            if nilai == "":
                print("Masukan Bilangan : ")
            else:
                break
        except:
            print("Harap Masukan Angka")
        else:
            break
```
- Program1

![image](https://user-images.githubusercontent.com/84762007/147787467-b0d449a0-c4f3-48bd-83e7-88cd34fd1f95.png)

Syntaxnya :

```python
  >>> print("Laba bulan ke-",x, " : ",c))
    File "<stdin>", line 1
      print("Laba bulan ke-",x, " : ",c'))
                                          ^
  SyntaxError: invalid syntax
 `TypeError` : operasi Laba pada tipe data yang tidak sesuai, tidak dapat melakukan operasi penjumlahan antara _integer_ dengan _string_
