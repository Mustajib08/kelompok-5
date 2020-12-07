# kelompok-5
tugas dari pak deny
import os

print("+===================================================+")
print("|\tSelamat Datang Di Aplikasi Sistem Pakar\t    |")
print("|\t\tDeteksi Tifus & Covid-19\t    |")
print("+===================================================+")
nama = input("Nama :\t ")
pilihan = input("Hello,"+nama+"\n Apakah Anda Ingin Melakukan Diagnosa ? (Y/N)")

os.system("cls")

while pilihan == "Y":
  print("\n Apakah Anda Mersakan Gejala Berikut Ini :")
  print("1.Demam / Suhu Badan Tinggi ")
  print("2.Nafsu Makan Berkurang ")
  print("3.Diare ")
  print("4.Kelelahan & Lemas ")
  diag1 = input(" Jawab Y/N : ")

