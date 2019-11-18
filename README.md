# Tugas-2

x = int()

y = 0

while x >= 0:

    x = int(input("Masukan Bilangan: "))
    
    if x > y:
    
     y = int(x)
     
    if x == 0:
    
     break
     
print("\n Angka Terbesar Adalah ",y)
