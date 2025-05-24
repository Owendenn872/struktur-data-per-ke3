# 1. Menentukan Nilai Terbesar dari Tiga Bilangan
def nilai_terbesar(a, b, c):
    if a >= b and a >= c:
        return a
    elif b >= a and b >= c:
        return b
    else:
        return c

# 2. Menentukan Bilangan Genap atau Ganjil
def genap_atau_ganjil(n):
    return "Genap" if n % 2 == 0 else "Ganjil"

# 3. Menghitung Rata-rata Tiga Bilangan
def rata_rata(a, b, c):
    return (a + b + c) / 3

# Contoh penggunaan
a, b, c = 10, 20, 15
print("Nilai terbesar:", nilai_terbesar(a, b, c))
print("Bilangan", a, "adalah", genap_atau_ganjil(a))
print("Rata-rata:", rata_rata(a, b, c))
