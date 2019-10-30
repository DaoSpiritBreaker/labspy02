 Program Sederhana Python Mencari Bilangan Terbesar & Terkecil

Setelah saya posting "Labspy01", sekarang saya ingin memposting cara membuat program sederhana. Yang di butuhkan hanyalah statement IF.

Struktur Algoritma

    1.Mulai
    2.Inisiasi bil1,bil2,bil3 sebagai integer.
    3.Baca bil1.
    4.Baca bil2.
    5.Baca bil3.
    6.Jika bil1 > bil2 dan bil1 > bil3 maka kerjakan langkah 8, selain itu
    7.Jika bil2 > bil1 dan bil2 > bil3 maka kerjakan langkah 9, selain itu kerjakan langkah 10.
    8.Cetak “Bilangan Terbesar Bilangan Pertama”.
    9.Cetak “Bilangan Terbesar Bilangan Kedua”.
    10.Cetak “Bilangan Terbesar Bilangan Ketiga”.
    11.Selesai

Step pada source code

print ('masukkan 3 bilangan yang diinginkan!')

a=int(input('bilangan1 = '))

b=int(input('bilangan2 = '))

c=int(input('bilangan3 = '))

if a>b and a>c:

    if b>c:

        print (a, 'terbesar dan', c, 'terkecil')

    else:

        print (a, 'terbesar dan', b, 'terkecil')

elif b>a and b>c:

    if a>c:

        print (b, 'terbesar dan', c, 'terkecil')

    else:

        print (b, 'terbesar dan', a, 'terkecil')

else:

    if a>b:

        print (c, 'terbesar dan', b, 'terkecil')

    else:

        print (c, 'terbesar dan', a, 'terkecil')

print ('')

print ('ingin coba lagi? (ya/tidak)')

x=input()

if x=='ya':

    return pengulangan()

if x=='tidak':

    print('terimakasih telah menggunakan program ini.')


pengulangan()

Gambaran Flowchart

![67663464-2bff2f00-f998-11e9-9af4-8b55e2346a7d](https://user-images.githubusercontent.com/53388439/67880894-1d6c6f80-fb72-11e9-903b-84c27520121a.jpg)

Screenshoot Code 1
![67663571-68328f80-f998-11e9-99fb-f4d0947e5e51](https://user-images.githubusercontent.com/53388439/67882059-31b16c00-fb74-11e9-8352-68afd917af1f.png)

Screenshoot Code 2
![67663620-813b4080-f998-11e9-959a-c5a594578d0e](https://user-images.githubusercontent.com/53388439/67882163-632a3780-fb74-11e9-93d5-1e50ffd8ae2f.png)

Screenshoot Hasil
![Screenshot (56)](https://user-images.githubusercontent.com/53388439/67883246-53abee00-fb76-11e9-8b97-2c5c2f482359.png)
