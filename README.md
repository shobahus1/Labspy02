# Labspy02

**Nama : SHOBAHUS SOLICHIN** <br>
**Kelas : TI.20.A1** <br>
**Nim : 312010076** 

___________________________________________________________________________________

 Pada pertemuan 7 tugas PPT ke-2 ini, saya diberikan beberapa tugas oleh dosen saya yaitu 

![Tugas Praktikum 2](https://user-images.githubusercontent.com/72906579/98377632-a5376480-2077-11eb-914b-7edfddf5d866.png)

untuk mencari sebuah nilai maksimal dari 3 data yang sebelumnya telah diinput, dan setelah mendapat nilai maksimalnya, dirubah menjadi dalam 
sebuah bentuk flowchart.

## TUGAS PRAKTIKUM 2
##### MENGINPUT DATA DAN MENCARI NILAI MAX
________________________________________________________________________________________
Pertama-tama disini saya akan mencoba untuk menginput 3 data dengan menggunakan syntax berikut terlebih dahulu.
```python
a = int(input("Masukkan bilangan 1: "))
b = int(input("Masukkan bilangan 2: "))
c = int(input("Masukkan bilangan 3: "))
```
Masukan syntax tersebut dengan angka yang kalian inginkan. 

![Input](Foto/shoba1.PNG)

Jika sudah mendapat tampilan seperti gambar diatas, maka kalian sudah berhasil menginput ketiga data tersebut. <br>

Langkah selanjutnya adalah mencari tahu nilai terbesar (max) dari ketiga data tersebut. Sebelum memulainya kalian harus memasukan terlebih 
dahulu berapa jumlah data yang akan kalian kerjakan dari ketiga data tersebut dengan syntax <br>
```python
N=int(input("banyaknya data = "))
```
Karena disini saya diberi tugas mencari nilai max dari ketiga data maka saya akan menggunkan semua data diatas.

```python
if N>0:
    i=1
    x=int(input("data ke -"+str(i)+"="))
    max=x;total=x
    for i in range(2,N+1):
        x=int (input("data ke -"+str(i)+"="))
        total+=x
        if max<x:
            max=x

    print("bilangan terbesar =",max)
```
Selanjutnya kalian bisa langsung  memasukan syntax ini untuk melengkapi syntax diatas supaya bisa berjalan dengan baik seperti pada gambar 
dibawah ini.

![Nilai Max](Foto/shoba2.PNG)

Maka jika digabungkan, cara untuk mencari nilai max dari ketiga data yang diinputkan adalah dengan menggunakan syntax
```python
N=int(input("banyaknya data = "))
if N>0:
    i=1
    x=int(input("data ke -"+str(i)+"="))
    max=x;total=x
    for i in range(2,N+1):
        x=int (input("data ke -"+str(i)+"="))
        total+=x
        if max<x:
            max=x

    print("bilangan terbesar =",max)
```
Seperti inilah hasil akhirnya 

![Hasil](Foto/ss7.PNG)

## MERUBAH DATA DIATAS MENJADI DALAM BENTUK FLOWCHART
__________________________________________________________________________________
Setelah kalian mendapatkan semua data diatas langkah selanjutnya adalah mengubahnya menjadi dalam bentuk flowchart seperti ini

![Flowchart](Foto/ss6.PNG)

Untuk bisa mendapatkan hasil flowchart diatas, maka kalian harus mendownload flowgorithm terlebih dahulu. Download lah pada web resminya yaitu :[clickHere](http://www.flowgorithm.org/download/) 

Download lah yang sesuai dengan laptop kalian agar tidak terjadi kendala saat sedang mengoperasikannya.

![Download Flow](Foto/download1.PNG)

Setelah mendapat tampilan seperti dibawah ini kalian bisa mengklik pada bagian garis hitamnya

![Flow Step1](Foto/shoba12.png)

Pada tampilan diatas kalian dapat memilih menu mana yang kalian butuhkan.

Jika kalian sudah mengerjakannya hingga akhir, maka step akhir adalah kalian hanya perlu mengecek apakah flowchart tersebut sudah bekera dengan
baik atau belum dengan cara sebagai berikut

![Flow Step2](Foto/ss5.PNG)

Jika sudah me 'run' berkali kali dan mendapatkan jawaban sama yang sesuai itu berbarti flowchart yang kalian buat sudah benar dan bekerja 
dengan baik.

## TERIMA KASIH