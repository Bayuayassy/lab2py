# lab2py
## Latihan Pyhton 
Nama    : Bayu Maulana Ayassy

Nim     : 312210166

Kelas   : TI.22.A1

# Install Python
1. donwload pyhton pada web resmi python https://www.python.org/ dengan menyesuaikan OS dari versi masing masing.
![2022-10-24 (2)](https://user-images.githubusercontent.com/115678251/197452117-f044acd8-038e-43d3-82ac-cea3eb802f8f.png)


2. buka hasil donwload kemudian klik install, tunggu sampai proses installasi selesai ( ceklis setiap menu yang di tampilkan selama porses installasi )

![2022-10-24 (3)](https://user-images.githubusercontent.com/115678251/197452938-1262ca1c-9fa8-4260-8c8f-d92914e17f21.png)
![2022-10-24 (4)](https://user-images.githubusercontent.com/115678251/197452991-126897e9-1cae-4829-98ce-1c343338abea.png)


3. cek keterangan instalasi berhasil pada menu cmd dengan cara ketik python --version,  dan instalasi dinyatakan berhasil dijalankan pada menu cmd

![2022-10-24 (5)](https://user-images.githubusercontent.com/115678251/197453352-c6f4b23a-f95d-4555-a3e1-b8ccc1a2d6d4.png)


# Latihan Python 1
1. pada menu windows ketik CMD dan akan muncul CMD 
2. Setalah CMD masukan perintah PYTHON
3. Kemudian lakukan latihan pertama dengan menampilkan kalimat ("Hallo") dan ("Saya belajar Python")


```python
#menampilkan tulisan "Hallo" di layar
print("Hallo")
print("Saya sedang belajar Pyhton")
````

![2022-10-24](https://user-images.githubusercontent.com/115678251/197455611-40bd77ea-2a43-4757-af46-b9d6b2a0fdc6.png)





# Latihan Python 2
buat file baru (Latihan 2)
1. Menjumlahkan dua buah bilangan variabel a dan b
2. kemudian klik run maka akan muncul tampilan seperti berikut

```python
a=8
b=6
print("variable a=",a)
print("variable a=",b)
print("hasil penjumlahan a+b=",a+b)
```
![197394472-b038cbea-3bc0-40ac-96ad-e4aba5ee0284](https://user-images.githubusercontent.com/115678251/197456138-5544833d-ce67-4603-bc50-204e4f623cbf.png)








# Latihan Python 3
buat file baru (Latihan 3)
1. Memasukan nilai Penggabungan, Penjumlahan, dan Pembagian dari nilai a= 6 dan b=8
2. kemudian klik run dan masukan nilai a=6 dan b=8 maka akan tampil sebagai berikut
```python
#Input nilai variabel
a=input("masukan nilai a:")
b=input("masukan nilai b:")

#Cetak nilai variabel
print("Variabel a=",a)
print("Variabel b=",b)

#Cetak hasil kedua variabel dengan String Format :
print("Hasil Penggabungan {1}&{0}=%s".format(a,b) + str(a+b))

#Konversi nilai variabel
a=int(a)
b=int(b)
print("Hasil penjumlahan {1}+{0}=%s".format(a,b) %(a+b))
print("Hasil pembagian {1}/{0}=%s".format(a,b) %(a/b)
```
![2022-10-24 (1)](https://user-images.githubusercontent.com/115678251/197456566-d9a1b194-70f0-4a20-ab49-624fb113e9b9.png)



