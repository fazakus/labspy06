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
print(a(4))
print(aa(4))
print()
print("Latihan b")
print("=========")
print(b(4, 7))
print(bb(4, 7))
print()
print("Latihan c")
print("=========")
print(c(10))
print(cc(10))
print()
print("Latihan d")
print("=========")
print(d("abcde"))
print(dd("abcde"))
```
Disini saya sudah rubah ke lambda<br>
Berikut outputnya<br>
![outputlatihan](Pic/outputlatihan.png)<br>

## Tugas Praktikum 6

