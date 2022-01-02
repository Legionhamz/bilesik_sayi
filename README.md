# bilesik_sayi
#======= Bileşik Sayı =======#

x = ""

sayi=int(input("bir sayı giriniz :"))

##########  sayı sıfırdan farklıysa devam eder değilse hata verir.

while not(sayi==0):
    
    ############## aşağıda sayıyı 2'ye bölerek kalanı x'e ekler
    
    x=str(sayi%2)+x

    ####aşağıda sayıyı kalansız bir şekilde bölerek sayi'ya atama yapıyor

    sayi=sayi//2

print(x)
#§==============================0

#####   VEYA

# x = int(input("bir sayi gir: "))     # burada ki binnary ikilik sayiya çevirme işlemini görür

# print(bin(x)[2:])