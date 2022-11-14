# pseudokodzik
Język programowania, jak najbardziej zbliżony do pseudokodu, stworzony w celach naukowo-dydaktycznych.

## Użytkowanie:

#### Komentarze
```python
# To jest komentarz
```

#### Deklarowanie zmiennych
```python
logiczna = Prawda
calkowito_liczbowa = 8
zmienno_przecinkowa = 8.7
tesktowa = "abc"
```

#### Instrukcje wejścia/wyjścia
```python
wypisz "To jest zmienna: " zmienna " ."
wczytaj a
wczytaj a b c
```

#### Instukcje warunkowe
```python
gdy x < 10:
  wypisz "x pasuje"
gdy tylko x < 5:
  wypisz "x jest na granicy"
inaczej:
  wypisz "x nie pasuje"
```

#### Petla dopoki
```python
dopoki x < 10:
  wypisz x
  x = x + 1
```

#### Petla iteracyjna
```python
dla i = 1, 2 ... 10:
  wypisz i

start = 3
przejscie = 4
stop = 67

dla i = start, start+przejcie, ... stop: # wlacznie
  wypisz i
```

#### Tablice
```python
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
```python
tab = ["a", "b", "c"]
dla literka z tab:
  wypisz literka
```

#### Instrukcja przerwij i kontynuuj
```python
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
```python
funkcja czy_parzysta(n):
  gdy n % 2 == 0:
    zwroc Prawda
  zwroc Falsz
```

Słowa kluczowe:
[dla, z, gdy, tylko, inaczej, wypisz, wczytaj, przerwij, kontynuuj, funkcja, zwroc]
