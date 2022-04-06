# W skrócie o grze:
- wzorowana na Shakes & Fidget oraz D&D 
- gracze mogą walczyć ze sobą, chodzić na misje i rozbudowywać swoje postacie 
- mocno rozbudowany system handlu, stąd baza w PostgreSQL


# Pomysły:
- wiele map:
  - mają różne boty
  - różne questy
  - różne itemki w sklepiku  
  - questy wyczerpują - postać musi iść do karczmy
  - sposób zarobku pieniędzy typu warta
  - karczma, żeby się zregenerować

# Front
- Tworzenie postaci
- Logowanie & rejestracja
- Menu główne
- Okienko:
  - Tawerny - tablica ogłoszeń (lista questów)
  - Arena - lista graczy (ewentualnie 3 proponowanych na podobnym poziomie)
  - sala chwały (?) - ranking na podstawie PCh
  - Market (?) - lista itemów wystawiona po podanej cenie przez innych graczy
  - Weapon shop - randomowo wygenerowana lista broni na poziomie gracza
  - Magic shop - randomowo wygenerowana lista potków, akcesoriów na poziomie gracza
  - Armor shop - randomowo wygenerowana lista zbroi na poziomie gracza
  - Nasza postać - wszystkie atrybuty + skille + przedmioty naszego gracza
  - Walka na arenie
  - NIE TERAZ
  - Stable - lista wierzchowców
  - Blacksmith (?) - wymiana posiadanych surowców na możliwe itemy
  - Targ najemników
  - Cechy miejskie (?) - lista specjalistów, którzy za pieniądze dają skilla
  - Gildia <- twoja lub jej brak (?) - podlista graczy
 
## Walka w misji:
- 1 vs 1 mob

## NIE TERAZ
- 1 vs wiele mobów
- 1 + boty vs 1 mob
- 1 + boty vs wiele mobów
- 2 vs 1 mob 
- 2 vs wiele mobów
- 2 + boty vs 1 mob (?)
- 2 + boty vs wiele mobów (?)

# Backend
- Zrobić klasy postaci i podstawowych obiektów
- Ogarnąć server
- Połączenie z bazą

# Harmonogram gra
- 2 (18.03) - klasy, widoki, harmonogram
- 3 (01.04) - pierwsze postępy
  + backend (podpięcie do bazy, inicjalizacja serwera, pierwsze testy)
  + front (wyświetlanie okienek, przechodzenie między nimi, podstawowe interakcje)
- 4 (15.04) - drugie postępy
  + podpięcie backendu z frontendem (żeby front pobierał dane z serwera, a nie z mockowanych danych)
- 5 (29.04) - trzecie postępy
  + zaimplementowanie zaawansowanych mechanik (walka na arenie, system gildyjny, questy)
- 6 (13.05) - dalsze poprawki gameplay'u
- 7 (27.05) - oddawanie, podsumowanie

# Harmonogram baza danych
