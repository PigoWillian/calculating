# calculating
def Penjumlahan(num1, num2):
    return num1 + num2
def Penguranan(num1, num2):
    return num1 - num2
def Perkalian(num1, num2):
    return num1 * num2
def Pembagian(num1, num2):
    return num1 / num2

while True:
    # print("Pilihan Operasi: \n [1]penjumlahan \n [2]pengurangan \n [3]perkalian \n [4]pembagian \n [5] Stop Operasi")
    pilihan = [
        "penjumlahan",
        "pengurangan",
        "perkalian",
        "pembagian",
        "Stop Operasi"
    ]
    
    choice = int(input ("Masukkan pilihan: [1/2/3/4/5]"))
    if choice < 1 or choice > 5 :
        print("Nomor tersebut tidak tersedia, masukkan ulang nomor")
        continue
    elif choice == 5:
        print("operasi perhitungan telah berhenti")
        break
    no1 = int(input("Input Bil.1: "))
    no2 = int(input("Input Bil.2: "))

    print("Hasil Operasi")
    if choice == 1:
        print(f"Penjumlahan {no1} + {no2} = {Penjumlahan(no1,no2)}")
    elif choice == 2:
        print(f"Penguranan {no1} - {no2} = {Penguranan(no1,no2)}")
    elif choice == 3:
        print(f"Perkalian {no1} * {no2} = {Perkalian(no1,no2)}")
    elif choice == 4:
        print(f"Pembagian {no1} / {no2} = {Pembagian(no1,no2)}")
    

