# bruteforce
import os 


os.system("color 0A")

print("...........  ............. ............. ....               .... .............")
print("...........  ............. .............  ....             ....  .............")
print("....              ....     ....            ....           ....   ....         ")
print("....              ....     ....             ....         ....    ....         ")
print("...........       ....     .............     ....       ....     .............")
print("...........       ....     .............      ....     ....      .............")
print("        ...       ....     ....                ....   ....       ....         ")
print("        ...       ....     ....                 .... ....        ....         ")
print("...........       ....     .............         .......         .............")
print("...........       ....     .............          .....          .............")




print("1. supprimer les fichiers temporaire")
print("")
print("")
print("2. voir les information systeme")
print("")
number = input("entrez le numero de la command choisis: ")

if number=="1":
	os.system("del /S /F /Q %temp%")
	print("operation effectuer avec succes")
elif number=="2":
	os.system("systeminfo")
	print("operation effectuer avec succes")
elif number!="1" and number!="2":
	print("vous avez entrez le mauvais numero....reessayer avec 1 ou 2")

