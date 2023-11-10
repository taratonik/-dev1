import random

karakterler="+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
uzunluk=int(input("uzunluk:"))

sifre=""

#kod
for i in range(uzunluk):
    sifre=sifre+random.choice(karakterler)

print(sifre)
