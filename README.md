# labpy02
buka phycharm buka new project lalu tulis di bawah ini
Bilangan1 = int(input("Masukan Bilangan 1:"))
Bilangan2 = int(input("Masukan Bilangan 2:"))
Bilangan3 = int(input("Masukan Bilangan 3:"))

if  int(Bilangan1) and Bilangan1 > Bilangan3:
    print("Nilai Terbesar Adalah :", Bilangan1)
    Terbesar = Bilangan1
    NomBil = "Bilangan 1"
elif (Bilangan2 > Bilangan3) and (Bilangan2 > Bilangan1):
    print("Nilai Terbesar Adalah :", Bilangan2)
    Terbesar = Bilangan2
    NomBil = "Bilangan 2"
else:
    Terbesar = Bilangan3
    NomBil = "Bilangan 3"

    print("Bilangan yang terbesar adalah", Bilangan1, "dengan nilai", Terbesar)
    
    ![1](https://user-images.githubusercontent.com/56498070/68081960-e4b9e800-fe48-11e9-8816-3aeb79b5eeba.PNG)
![2](https://user-images.githubusercontent.com/56498070/68081961-e5527e80-fe48-11e9-9033-5754d286f2ef.PNG)
