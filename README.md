# labspy06

### Latihan
Untuk latihan kali ini merubah dari fungsi ke lambda<br>
Ada 4 fungsi yang harus dirubah ke lambda<br>
![latihan](Pic/latihan.png)<br>
Berikut adalah source code nya
```python
import math


def a(x):
    return x ** 2


def b(x, y):
    return math.sqrt(x ** 2 + y ** 2)


def c(*args):
    return sum(args) / len(args)


def d(s):
    return "".join(set(s))


# Dirubah menggunakan Lambda

aa = lambda x: x ** 2
bb = lambda x, y: math.sqrt(x ** 2 + y ** 2)
cc = lambda *args: sum(args) / len(args)
dd = lambda s: "".join(set(s))

# output
print("Latihan a")
print("=========")
print("Fungsi")
print(a(4))
print("Lambda")
print(aa(4))
print()
print("Latihan b")
print("=========")
print("Fungsi")
print(b(4, 7))
print("Lambda")
print(bb(4, 7))
print()
print("Latihan c")
print("=========")
print("Fungsi")
print(c(10))
print("Lambda")
print(cc(10))
print()
print("Latihan d")
print("=========")
print("Fungsi")
print(d("abcde"))
print("Lambda")
print(dd("abcde"))
```
Disini saya sudah rubah ke lambda<br>
Kalau di Tugas Latihan tidak ada outputnya, tp disini saya akan berikan contoh untuk output dari source code tersebut<br>
Berikut outputnya<br>
![outputlatihan](Pic/outputlatihan.png)<br>

## Tugas Praktikum 6

