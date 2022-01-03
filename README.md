# Pertemuan 13
## Penanganan_Eksepsi
## Latihan

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

```bash
while True:
        try:
            nim = int(input("Masukan NIM\t: "))
            if nim == "":
                print("NIM tidak boleh kosong")
            else:
                break
        except:
            print("Harap Masukan Angka")
        else:
            break
        
while True:
        try:
            nilai = int(input("Masukan Nilai\t: "))
            if nilai == "":
                print("Nilai tidak boleh kosong")
            else:
                break
        except:
            print("Harap Masukan Angka")
        else:
            break
```

# Output

![Gambar 1](img/output.png)
