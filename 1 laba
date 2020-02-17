import math

m=int(input("введите значение m="))
n: int=int(input("Введите значение n="))
try:
    z1 = -1 * (math.sqrt((3 * m + 2) ** 2 - 24 * m)) / (3 * math.sqrt(m) - 2 / math.sqrt(m))
except ZeroDivisionError:
    print('Извините, текущие значения m=', m, "и n=", n, "не подходят")
    z1 = None
try:
    z2= -1 * math.sqrt(m)
except ZeroDivisionError:
    print("Извините, текущие значения m=", m, "и n=", n, "не подходят")
    z2 = None
print ("z1 =", z1, "z2 =", z2)
