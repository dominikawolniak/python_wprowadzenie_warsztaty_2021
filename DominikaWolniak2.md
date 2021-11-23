#Zadanie 1
slowo =input("Wpisz tekst:")
print(slowo)
for ttt in slowo:
  print(ttt)

#Zadanie 2
from random import randint

los = randint(1,10)
odp = -1
i = 0
print("Zgadnij liczbę z przedziału 1 do 10")

while odp != los:
    i += 1
    odp = int(input("Podaj liczbę: "))
    if odp == los: 
        print("Brawo! Zgadłeś za", i, "razem")
    else: 
        print("Nie! Szukana liczba jest inna!")
print("Koniec programu.")

#Zadanie 3

kontynenty = {
    'Europa': 46,
    "Ameryka Północna" : 22,
    "Ameryka Południowa" : 13,
    "Azja": 50,
    "Afryka": 57,
    "Australia i Oceania": 14
}

x = input("Podaj nazwę kontynetu: ")
