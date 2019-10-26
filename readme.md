# Latihan operator dengan phyton
Operator adalah simbol khusus pada Python yang merupakan perhitungan aritmatika atau logika. Nilai yang dioperasikan operator disebut operand. operator aritmatika terdiri dari :
1 Penjumlahan + 
2 Pengurangan - 
3 Perkalian * 
4 Pembagian / 
5 Sisa bagi % 
6 Pemangkatan **

## Contoh Coding
```
a=input("masukkan nilai a:")
b=input("masukkan nilai b:")
print("variable a=" ,a)
print("variable b=" ,b)
print("hasil penggabungan {0}&{1}=%s" .format(a,b) %(a+b))
a=int(a)
b=int(b)
print("hasil penjumlahan {0}+{1}=%s" .format(a,b) %(a+b))
print("hasil pembagian {0}/{1}=%s" .format(a,b) %(a/b))
```
note:
%d adalah fungsi untuk bilangan bulat desimal 
%s adalah fungsi untuk Konversi string melalui str () sebelum memformat.
{0}&{1}=%s variable a dahulu baru variable b. {0} adalah variable a, {1} adalah variable b.
a=input("masukkan nilai a:")   menginput variable a
b=input("masukkan nilai b:")   menginput variable b
print("variable a=" ,a)        menginput variable a yang sudah diisi
print("variable b=" ,b)        menginput variable b yang sudah diisi
print("hasil penggabungan {0}&{1}=%s" .format(a,b) %(a+b))       hasil penggabungan varible a dan b
a=int(a)                       variable a yang sudah diinput
b=int(b)                       variable b yang sudah diinput
print("hasil penjumlahan {0}+{1}=%s" .format(a,b) %(a+b))        hasil penjumlahan variable a dan b
print("hasil pembagian {0}/{1}=%s" .format(a,b) %(a/b))          hasil pemabagian variable a dan b
