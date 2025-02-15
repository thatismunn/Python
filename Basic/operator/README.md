# operator

operator digunakan untuk melakukan operasi pada kedua variabel atau value

python memiliki beberapa jenis operator yaitu

- [operator aritmatika](operator_aritmatika.py)
- [operator penugasan](operator_penugasan.py)
- [operator komparasi](operator_perbandingan.py)
- operator logika
- operator identitas
- operasi member


## operasi aritmatika
operasi aritmatika adalah operasi yang digunakan untuk melakukan operasi matematika diantara kedua value atau kedua variabel

sebagai contoh operasi pertambahan
```python
angka = 2
angka_kedua = 3

print(angka + angka_kedua)
```
operasi tersebut menambahkan kedua variabel yang memiliki value yaitu 2 dan 3

berikut table dari operasi aritmatika

| operator | nama operator | contoh penggunaan |
|----------|---------------|-------------------|
| +        | penambahan    | a + b             |
| -        | pengurangan   | a - b             |
| *        | perkalian     | a * b             |
| /        | pembagian     | a / b             |
| **       | perpangkatan  | a ** b            |
| %        | modulus       | a % b             |
| //       | floor         | a // b            |

## operasi penugasan
operasi penugasan adalah operasi yang digunakan untuk menetapkan suatu bilangan ke dalam variabel

sebagai contoh operasi penugasan
```python
nilai = 5
nilai += 3

print("nilai adalah", nilai)
```
operasi tersebut menambahkan sekaligus menetapkan ke dalam variabel nilai

berikut tabel dari operasi penugasan

|   Operator    |   Example     |  Sama Dengan  |
|---------------|---------------|---------------|
|     =         |   x = 5       |   x = 5       |
|     +=        |   x += 3      |   x = x + 3   |
|     -=        |   x -= 3      |   x = x - 3   |
|     *=        |   x *= 3      |   x = x * 3   |
|     /=        |   x /= 3      |   x = x / 3   |
|     %=        |   x %= 3      |   x = x % 3   |
|     //=       |   x //= 3     |   x = x // 3  |
|     **=       |   x **= 3     |   x = x ** 3  |
|     &=        |   x &= 3      |   x = x & 3   |
|     &#124;=        |   x &#124;= 3      |   x = x &#124; 3   |
|     ^=        |   x ^= 3      |   x = x ^ 3   |
|     <<=       |   x <<= 3     |   x = x << 3  |
|     >>=       |   x >>= 3     |   x = x >> 3  |


## operasi perbandingan

operasi perbandingan adalah operasi yang digunakan untuk membandingkan suatu nilai dengan nilai yang lain

sebagai contoh operasi perbandingan
```python
print(2 < 3)  # True
```

operasi tersebut membadingkan apakah nilai pertama lebih kecil daripada nilai kedua

berikut tabel dari operasi perbandingan
|   Operator    |                Artinya                |
|---------------|---------------------------------------|
|      ==       |              Sama Dengan              |
|      !=       |           Tidak Sama Dengan           |
|      >        |           Lebih besar dari            |
|      <        |           Lebih Kecil dari            |
|      >=       |    Lebih Besar dari atau sama dengan  |
|      <=       |    Lebih Kecil dari atau sama dengan  |