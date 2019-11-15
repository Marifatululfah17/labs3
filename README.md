program1

print("Program menampilkan bilangan terbesar dari n bilangan")

a = 1
max = 0
while a !=0:
    if a > max:
        max = a
    a = int(input("Masukan bilangan:"))
    if a == 0:
        break
print("Nilai terbesar adalah:",max)

![image](https://user-images.githubusercontent.com/56728542/68946036-cfa55900-0766-11ea-982b-495bdc7b5ae1.png)

latihan 1

n = int(input("Masukan nilai N:"))

from random import random
a = random()

jumlah = n
for i in range(jumlah):
    print("date ke:", i,(a))

print("selesai")


![image](https://user-images.githubusercontent.com/56728542/68948243-51e44c00-076c-11ea-8d08-4296e658f533.png)


latihan 2

x=100000000
sum=0
y=0
laba = [int(0), int(0), int(x) * .1, int (x) * .1, int(x) * .5, int(x) * .5, int(x)* .5, int(x) * .2]
print("Modal awal seorang pengusaha:", x)
for i in laba :
    sum = sum+i
    y+=1
    print("Laba bulan ke-",y,"sebesar:", i)
print("Total laba adalah:",sum)

![image](https://user-images.githubusercontent.com/56728542/68948301-74766500-076c-11ea-9d63-fc600d5ffa21.png)
