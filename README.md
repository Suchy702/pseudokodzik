# pseudokodzik
Język programowania, jak najbardziej zbliżony do pseudokodu, stworzony w celach naukowo-dydaktycznych.

## Użytkowanie:

#### Komentarze
```
# To jest komentarz
```

#### Deklarowanie zmiennych
```
logiczna = Prawda
calkowito_liczbowa = 8
zmienno_przecinkowa = 8.7
tesktowa = "abc"
```

#### Instrukcje wejścia/wyjścia
```
wypisz "To jest zmienna: " zmienna " ."
wczytaj a
wczytaj a b c
```

#### Instukcje warunkowe
```
gdy x < 10:
  wypisz "x pasuje"
gdy tylko x < 5:
  wypisz "x jest na granicy"
inaczej:
  wypisz "x nie pasuje"
```

#### Petla dopoki
```
dopoki x < 10:
  wypisz x
  x = x + 1
```

#### Petla iteracyjna
```
dla i = 1, 2 ... 10:
  wypisz i

start = 3
przejscie = 4
stop = 67

dla i = start, start+przejcie, ... stop: # wlacznie
  wypisz i
```

#### Tablice
```
tab = [1, 2, 3]
tab = [8] # [0, 0, 0, 0, 0, 0, 0, 0]
tab[1] = 1
wypisz tab[1]

n = 0
wczytaj n
tab = [n]
tab[4] = 4
```

#### Petle iteratorowe
postac: 
dla zmienna z tablica:
```
tab = ["a", "b", "c"]
dla literka z tab:
  wypisz literka
```

#### Instrukcja przerwij i kontynuuj
```
x = 5
dopoki Prawda:
  gdy x == 69:
    kontynuuj
  gdy x == 100:
    przerwij
  wypisz x
  x = x+1
```

#### Funkcje
```
funkcja czy_parzysta(n):
  gdy n % 2 == 0:
    zwroc Prawda
  zwroc Falsz
```

Słowa kluczowe:
[dla, z, gdy, tylko, inaczej, wypisz, wczytaj, przerwij, kontynuuj, funkcja, zwroc]
