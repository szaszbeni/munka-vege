print("Ezek az eszközök találhatók otthon :")
print("\n Router ár:10000ft","\nSwitch ár:15000ft","\n Wifi router ár:10000ft","\n Számítógép ár:300000ft","\n Laptop ár:150000ft","\n Telefon ár:100000","\n Tablet ár:50000ft")
print(" ")
print("and a kilépéshez")
print(" ")

ossz=[]
termek = []
while True:
    data = input("Irj ide egy eszközt: ")
    if data.count("Router"):
        ossz.append(10000)
    if data.count("Switch"):
        ossz.append(15000)
    if data.count("Wifi router"):
        ossz.append(10000)
    if data.count("Számítógép"):
        ossz.append(300000)
    if data.count("Laptop"):
        ossz.append(150000)
    if data.count("Telefon"):
        ossz.append(100000)
    if data.count("Tablet"):
        ossz.append(50000)
    if str.lower(data) =="and" :
        break
    termek.append(data)
for food in termek:
    print("Otthoni eszközök:",food)
print("Összesen: ",sum(ossz),"ft")

#Egy személyre.
