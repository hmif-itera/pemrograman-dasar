# Perkenalan Variabel dan Tipe Data

## Variabel
Variabel merupakan istilah yang diadopsi dari dunia matematika, yang memetakan sebuah nama ke suatu nilai.

Dalam pemrograman, variabel digunakan untuk menyimpan nilai yang akan digunakan dalam program. Nilai yang disimpan dalam variabel dapat berupa angka, huruf, karakter, atau bahkan kumpulan nilai lainnya.

Variabel dalam pemrograman memiliki beberapa karakteristik, yaitu:
- Nama variabel
- Tipe data
- Nilai

## Nama Variabel
Nama variabel adalah nama yang diberikan kepada variabel. Nama variabel harus diawali dengan huruf atau garis bawah (_), dan tidak boleh diawali dengan angka. Nama variabel juga tidak boleh menggunakan spasi, simbol, atau karakter khusus lainnya.

Contoh nama variabel yang benar:
- `nama`
- `umur`
- `nilai`
- `nilai_akhir`

Contoh nama variabel yang salah:
- `1nama`
- `nama umur`
- `nilai-akhir`

## Gaya Penulisan Nama Variabel
Ada beberapa gaya penulisan nama variabel yang umum digunakan dalam pemrograman, yaitu:
- `camelCase` : huruf pertama kecil, dan huruf pertama setiap kata berikutnya besar
- `PascalCase` : huruf pertama setiap kata besar
- `snake_case` : menggunakan garis bawah (_) sebagai pemisah antar kata

Contoh:
- `namaLengkap` (camelCase)
- `NamaLengkap` (PascalCase)
- `nama_lengkap` (snake_case)


## Tipe Data
Tipe data adalah jenis nilai yang akan disimpan dalam variabel. Tipe data yang umum digunakan dalam pemrograman adalah:
- `int` : untuk menyimpan bilangan bulat
- `float` : untuk menyimpan bilangan riil
- `double` : untuk menyimpan bilangan riil dengan presisi ganda
- `char` : untuk menyimpan karakter
- `string` : untuk menyimpan kumpulan karakter
- `bool` : untuk menyimpan nilai kebenaran (true atau false)

## Nilai
Nilai adalah data yang disimpan dalam variabel. Nilai yang disimpan dalam variabel harus sesuai dengan tipe data variabel tersebut.

Contoh:
```cpp
int umur = 17;
float berat_badan = 45.5;
char jenis_kelamin = 'L';
string nama = "Budi";
bool status = true;
```

## Aturan Penulisan Variabel
- Nama variabel bersifat case sensitive, artinya huruf besar dan kecil dianggap berbeda.
- Nama variabel tidak boleh menggunakan kata kunci yang sudah ada dalam bahasa pemrograman.
- Nama variabel sebaiknya bersifat deskriptif, sehingga mudah dipahami oleh orang lain yang membaca kode program.

Contoh:
```cpp
int umur;
float beratBadan;
char jenisKelamin;
string namaLengkap;
bool statusMenikah;
```

## Contoh Program
```cpp
#include <iostream>
using namespace std;

int main() {
    int umur = 17;
    float beratBadan = 45.5;
    char jenisKelamin = 'L';
    string namaLengkap = "Budi";
    bool statusMenikah = true;

    cout << "Jenis Kelamin: " << jenisKelamin << endl;
    cout << "Nama Lengkap: " << namaLengkap << endl;
    cout << "Umur: " << umur << endl;
    cout << "Berat Badan: " << beratBadan << endl;
    cout << "Status Menikah: " << statusMenikah << endl;

    return 0;
}
```


## Referensi
- [https://www.petanikode.com/cpp-variabel/](https://www.petanikode.com/cpp-variabel/)
- [https://www.w3schools.com/cpp/cpp_variables.asp](https://www.w3schools.com/cpp/cpp_variables.asp)


