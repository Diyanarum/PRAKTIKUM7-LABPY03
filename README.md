# PERTEMUAN 7
### NAMA: DIYAN ARUM M
### KELAS: TI. 20. A. 1
### NIM: 312010133

_________________________________________________________________________________________
## TUGAS PRAKTIKUM 3
Pada pertemuan 7 di PPT3 ini saya diberikan beberapa tugas diantaranya yaitu:

![Tgs Praktikum3](https://user-images.githubusercontent.com/72906579/98434074-f3dc1180-20fe-11eb-8d2d-2c2592899895.png)

_________________________________________________________________________________________
## LATIHAN 1
Untuk saat ini saya akan mencoba untuk mengerjakan Latihan 1 seperti gambar dibawah ini terlebih dahulu.

![Lat1](https://user-images.githubusercontent.com/72906579/98434023-757f6f80-20fe-11eb-84c8-f932fae7a155.png)

untuk mengerjakannya kalian perlu memasuka sytax berikut 

```python
import random
print(40*"=")
print("Bilangan random yang lebih kecil dari 0,5")
print(40*"=")
jum = int( input("Masukan nilai n : "))
i = 0
for i in range(jum):
    i += 1
    angkaDec = random.uniform(0, 0.5)
    print("Data ke", i, " = ", angkaDec)
```
Maka hasil yang didapat dari syntax tersebut adalah

![Foto Lat2](https://user-images.githubusercontent.com/72906579/98340266-b19fcb00-203f-11eb-8660-6c72540b8626.png)
_______________________________________________________________________________________
## LATIHAN 2
Setelahnya saya akan mencoba untuk mengerjakan Latihan selanjutnya yaitu Latihan 2.

![Lat2](https://user-images.githubusercontent.com/72906579/98442065-1557f000-2135-11eb-961c-530168029224.png)


Untuk mengerjakan soal diatas maka kita perlu memasukan atau menginput datanya terlebih dahulu baru setelah itu bisa terlihat data mana yang terbesar denagn syntax.
```python
N=int(input("silahkan masukan jumlah bilangan ="))
if N>0:
    i=1
    x=int(input("masukan bilangan "+str(i)+"="))
    max=x;total=x
    for i in range(2,N+1):
        x=int (input("masukan bilangan "+str(i)+"="))
        total+=x
        if max<x:
            max=x

    print("bilangan terbesar =",max)
```
Setelah itu bisa langsung kalian run untuk dapat memasukan data yang sesuai dengan yang ada di soal seperti dibawah ini

![Jawaban Lat2](https://user-images.githubusercontent.com/72906579/98442806-a761f780-2139-11eb-9f58-65ddeecf8eab.png)
