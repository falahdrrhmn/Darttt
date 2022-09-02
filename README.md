<div align = "center">
  <h1> DART NOTESS </h1>
</div>

<div align = "center">
  <h2> BASIC DART </h2>
</div>

## SYNTAX BASIC

bisa gini
```dart
main() { 
   print("Hello World!"); 
}
```
atau gini
```dart
void main() { 
   print("Hello World!"); 
}

```

jalanin di terminal
```ssh
dart Test.dart
```

### Command

```dart
//single line command

/*
multi
line 
command
*/
```

### Data Type

- Numbers
- Strings
- Booleans
- Lists
- Maps

Contoh

#### STRING

kumpulan huruf, contoh

```dart
String contohString = "falah\n"; //bisa make /n hanjaayy
print("Nama saya adalah " + contohString);
```

#### INTEGER

angka tanpa desimal, contoh

```dart
  int contohInt = 10;
  print(contohInt + 10); //output 20 (10+10)
```

#### NUM

Bisa jadi tipe data integer atau double, kelemahan gabisa bikin angka desimal jadi sempurna, misal 0.1 + 0.2 harusnya jadi 0.3 tapi hasilnya bakal 0.30000000000000004 

```dart
num contonNum1 = 10;
  print(contonNum1);
  num contonNum2 = 10.2;
  print(contonNum2 + 10.3); //kok hasilnya 20.5? gatau lah
  num contonNum3 = 10.3;
  print(contonNum2 + contonNum3); //sama aja 20.5... ndak taulah
  num jumlahCoba = contonNum2 + contonNum3;
  print(jumlahCoba); // sama aja 20.5
```

#### DOUBLE

desimal intinya 

```dart
double contohDouble = 10.2;
print(contohDouble);
```

#### DYNAMIC

tipe data yang isinya bisa berubah. dynamic bisa berupa integer, string, double, num, object, dan lain sebagainya.

```dart
  dynamic contohDynamic1 = 10;
  dynamic contohDynamic2 = 10.19;
  dynamic contohDynamic3 = "kampret";

  print(contohDynamic1);
  print(contohDynamic2);
  print(contohDynamic3);
```

#### LIST

tumpukan data sama aja kayak array. isi data dari List bisa dideskripsikan secara statis, contohnya List<double>, List<String>, List<int> , dan terserah lagi. Jika kalian tidak mendeklarasikan tipe data dari isi List, maka hasilnya akan menjadi List<dynamic>. List, memiliki kunci (key) untuk mengambil data secara spesifik, mirip sama index lah

```dart
List ujang = ["patek", "tomcat", "apalah"];
print(ujang); // output : [patek, tomcat, apalah]
print(ujang[0]); // output : patek
```

#### MAP

kurang lebih mirip sama json. pasangan key dan value. Setiap key dan valu  e dapat dideklarasikan tipe datanya. seperti Map<String, dynamic> 
Dapat diartikan bahwa key memiliki tipe data String, dan value-nya memilki tipe data dynamic.

```dart
Map<String, dynamic> contohMap = {
    "url": "https://gepcode.com",
    "domain": "gepcode.com",
    "penulis": "Gilang Pratama",
    "totalAdmin": 1,
    "supportSeo": 100,
  };
```

<br>
<br>

<div align="center">
    Follow me!<br>
    <a href="https://bit.ly/3Qcg3s4">LinkedIn</a>
    ·
    <a href="https://bit.ly/3oRMMaA">Instagram</a>
    ·
    <a href="https://bit.ly/3zqrTrP">Youtube</a>
</div>



