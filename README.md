# BIODATA

NAMA : MUHAMMAD RAFI ALBANI RASYIN

KELAS : TI.24.A.4

NIM : 312410316

MATKUL : BAHASA PEMROGRAMAN 

# TUGAS LATIHAN 

![377445480-73d90a5f-3d61-4756-a812-177fc694c4a7](https://github.com/user-attachments/assets/936ed331-de58-4aee-8f10-d2b811925fff)

PRAKIKUM 3

# LATIHAN 1

![377447897-c55fed7a-d5c7-4d5a-8cd4-f6f93ef8ed8a](https://github.com/user-attachments/assets/6e31f1bf-a59f-4c50-a3ef-8b94864c0463)

Pembahasan Mengenai :

## Penggunaan End

## Penggunaan Separator

## String Format

# PENGGUNAAN END

![377455340-2bf9fa7a-756c-49eb-95ad-c3b2f0d11b36](https://github.com/user-attachments/assets/66214e7c-5433-4d0e-9d88-1c4f98be8a8d)

```python
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('Z')
````

Parameter end dalam fungsi Print() di python digunakan untuk menambahkan string (" ") apapun diakhir dan mengeluarkan pernyataan Print

```python
print()
````

Secara Default, fungsi print() akan mengakhiri dengan baris baru, dan akan secara otomatis menambahkan karakter baris baru di akhir Outputnya

ini hasil program tersebut :

![377488504-e1269cc5-7a35-46e1-9769-510bf9a35d4d](https://github.com/user-attachments/assets/2e50e6fd-6066-4d1c-bdcd-f3a360325d8a)

dan ini hasil tanpa menggunakan fungsi `print()` di tengah pada kode program di atas :

![377491703-a2775246-1374-4d7d-a64c-d67a4592309b](https://github.com/user-attachments/assets/2cd3ff76-d0f8-4944-916b-603ba2803420)

# PENGGUNAAN SEPERATOR

![377494080-2ff0ca65-d1c7-45b0-8ab9-74c2e3bca8f3](https://github.com/user-attachments/assets/9aba3975-982b-4b34-9fdc-6845748d202a)

```python
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
````

Pada python penggunaan Separator dapat menggunakan Fungsi split() atau sep yang seperti dalam kode program diatas

Separator ini menentukan pembatas yang digunakan untuk memisahkan string, separator dapat berupa karakter tunggal atau beberapa karakter.Jika tidak ditentukan, maka python akan menggunakan spasi sebagai pemisah.

Berikut Hasil Kode Program diatas : 

![377501444-10aeb6fc-4f8d-4007-89c3-6c97aa7a7f73](https://github.com/user-attachments/assets/694e0c8b-006f-4a0d-af8b-b26be00da208)

```python
w, x, y, z = 10, 15, 20, 25
````

Variable yang seperti ini menentukan parameter, jadi variable ini tidak bisa memasukan variable huruf melainkan variable angka yang sudah ditentukan w = 10, x = 15, y = 20, z = 25

```python
print(w, x, y, z)
````

fungsi ini hanya mencetak saja yang menggunakan fungsi print(), tetapi di karenakan mencetak parameter, koma tersebut dihilangkan

```python
print(w, x, y, z, sep=',')
````

karna pemisahnya dihilangkan kita memakainya fungsi sep=',' untuk membuat pemisah yaitu (,) koma di kode program ini

dan kode program seterusnyapun begitu menggunakan fungsi `sep` atau `split()` dan kita memasukan pemisahnya didalam string akan memunculkan cetakkan yang sesuai keinginan anda dalam memisahkan sesuatu parameter

#STRING FORMAT

![377522500-1b64d016-ee87-425d-baec-da0ff9932b64](https://github.com/user-attachments/assets/809cadc0-101f-44ab-8869-af9bd4af357c)

```python
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**5)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)

print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10)) 
````

String Format adalah proses memasukkan variable atau string kustom ke dalam teks yang sudah ditentukan, dan dapat digunakan untuk berbagai keperluan, seperti memasukkan judul dalam grafik, menampilkan pesan atau kesalahan, atau meneruskan kesalahan ke suatu fungsi.

```python
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**5)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)
````

Nilai pertama dalam setiap pasangan adalah angka dari 0 hingga 10, kode program ini dihitung dengan menggunakan operasi pangkat atau fungsinya (**) untuk menaikkan 10 ke pangkat yang sesuai dengan angka pertama, yang bisa di bahasa manusiakan variable 0 = 10 pangkat 0, variable 1 10 pangkat 1 dan seterusnya hingga variable 10 yaitu 10 pangkat 10, dan di cetak dengan fungsi print()

```python
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10))
````

Kode inimencetak 11 baris dengan format {0:3} {1:16} yang di gunakan untuk mengatur format string

Pada string pertama, angka `0` di format untuk memeliki lebar 3 karakter atau yang bisa disebut 3 kali spasi dengan perataan kanan.

angka 1 diformat untuk memiliki lebar 16 Karakter atau 16 kali spasi dengan perataan kanan, dan masing-masing mencetak nilai seperti format di atas dengan fungsi `print()`

# CODE PROGRAM

## 3 INPUT BILNGAN

```python
a = int(input("masukan angka pertama: "))
b = int(input("masukan angka kedua: "))
c = int(input("masukan angka ketiga: "))

if a > b and a > c:
    print(f"angka lebih besar adalah {a}")
elif b > a and b > c:
    print(f"angka lebih besar adalah {b}")
else:
    print(f"angka lebih besar adalah {c}")
````

Program ini akan menginputkan 3 bilangan dari yang a sampai dengan c.

```python
if a > b and a > c:
    print(f"angka lebih besar adalah {a}")
````

Karna Jika {a} lebih besar dari {b} dan {a} lebih besar dari {c}, output yang keluar adalah {a}

```python
elif b > a and b > c:
   print(f"angka lebih besar adalah {b}")
````

dan jika {b} lebih besar dari {a} dan {b} lebih besar dari {c} maka output yang keluar adalah {b}

```python
else:
    print(f"angka lebih besar adalah {c}")
````

Jika inputan yang diatas lebih kecil dari {c} maka output {c} yang akan keluar

Ini adala hasil program tersebut :

![377551292-b663a7b1-cbfc-47f9-b02e-2f6e661c1fb3](https://github.com/user-attachments/assets/c4611ae5-5b98-4934-88b0-22a6e8b0bd30)

dengan eksekusi program :

![Screenshot 2024-10-19 134831](https://github.com/user-attachments/assets/e2aa3dae-9e6c-4384-b136-bdfd7a6611ae)

dan flowchart sebagai berikut : 

![377560153-e78cf387-c05a-484a-a6e8-3c1cd627ee54](https://github.com/user-attachments/assets/7eb26e60-940d-49c8-ba9e-773085d6d57e)

# MENENTUKAN BILANGAN TERBESAR DARI N DAN BERIKAN ANGKA 0

```python
while True:   
    N = int(input("masukan angka: "))

    if N == 0:
        print(f"angaka terbesar adalah: {max}")
        break
    if N > max:
        max = N
````

Untuk menentukan bilangan terbesar dari n dalam Python, Anda bisa menggunakan fungsi max()

```python
max = 0
````

Masukkan daftar angka ke fungsi max(), Fungsi max() akan mengembalikan angka terbesar dalam daftar

Fungsi `max()` adalah fungsi bawaan Python yang berguna untuk menemukan nilai terbesar dalam suatu iterable atau dalam serangkaian argumen reguler.

```python
if N == 0:
        print(f"angka yang terbesar adalah: {max}")
        break
````

Fungsi ini jika Kita memasukan inputan integer yaitu 0 akan berlanjut ke fungsi break program dihentikan yang artinya selesai.

```python
if N > max:
        max = N
````

Jika Inputan yang kita masukan lebih besar dari fungsi max() di atas, program akan melanjutkan ke proses max = N yang artinya Angka terbesar akan Mencetak Inputan Bilangan yang kita masukan yang terbesar di cetak

```python
while True:
````

While true: adalah konstruksi perulangan dalam bahasa pemrograman Python yang memungkinkan blok kode diulang tanpa batas. dan karna di kode program diatas ada fungsi While True: Program terus berlanjut terus menerus, dan ketika kita ingin berhenti saya berikan decision N==0 dengan fungsi di bawahnya break seperti di atas yang berarti Inputan Integer yang di masukan angka 0 program akan di hentikan dan memunculkan cetakan yang terbesar

dan ini hasil program tersebut: 

![377864890-3d432805-856a-4582-8b1b-8f8a3a56a1d4](https://github.com/user-attachments/assets/95d20feb-cff5-49e8-8562-1a3b9449c6bf)

dengan screenshot kode program yang saya miliki: 

![Screenshot 2024-10-19 144941](https://github.com/user-attachments/assets/6d725432-8b18-4083-b614-3765c39647be)

dan hasil flowchart dari program tersebut:

![377865621-4fbfeb33-c0a1-4f4b-ba53-481ce76271ab](https://github.com/user-attachments/assets/77b87bae-f869-42d7-b51e-c1cbb1daf42d)

