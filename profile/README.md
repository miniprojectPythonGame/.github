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

## NIE TERAZ
- 1 vs wiele mobów
- 1 + boty vs 1 mob
- 1 + boty vs wiele mobów
- 2 vs 1 mob 
- 2 vs wiele mobów
- 2 + boty vs 1 mob (?)
- 2 + boty vs wiele mobów (?)

# Harmonogram gra
- 2 (18.03) - klasy, widoki, harmonogram
- 3 (01.04) - pierwsze postępy
  + backend (podpięcie do bazy, inicjalizacja serwera, pierwsze testy)
  + front (wyświetlanie okienek, przechodzenie między nimi, podstawowe interakcje)
- 4 (29.04) - drugie postępy
  + podpięcie backendu z frontendem (żeby front pobierał dane z serwera, a nie z mockowanych danych)
- 5 (13.05) - trzecie postępy
  + zaimplementowanie zaawansowanych mechanik (walka na arenie, system gildyjny, questy)
- 6 (27.05) - dalsze poprawki gameplay'u
- 7 (10.06) - oddawanie, podsumowanie


## Registration
![alt text](https://github.com/miniprojectPythonGame/.github/blob/main/frontend/images/register.png?raw=true)

## Login
![alt text](https://github.com/miniprojectPythonGame/.github/blob/main/frontend/images/login.png?raw=true)

## Hero select
![alt text](https://github.com/miniprojectPythonGame/.github/blob/main/frontend/images/hero_select.png?raw=true)

## Map view
![alt text](https://github.com/miniprojectPythonGame/.github/blob/main/frontend/images/map_view.png?raw=true)


# Wnioski Backend - Piotr Witek ~Viciooo
- TDD to moim zdaniem jedyne sensowne podejście przy większych projektach, braki automatycznych testów sprawiły, że trzeba było robić manualne co sprawiało ogromny ból 
- większy projekt bez testów to tykająca bomba. Chciałbyś zmienić ten głupi camelCase na_coś_takiego? Pojawia się regresja o której przekonujesz się po 2 dniach dzięki losowemu printowi
- ręczne mapowanie bazy danych jest straszliwie żmudne i mało eleganckie - użyj Django. Może i setup zajmie z 6h jak nigdy tego nie robiłeś ale warto, w gratisie dostajesz jeszcze admina do łatwiejszego wprowadzania rzeczy przez UI.
- pisanie komentarzy nie boli - po 2 miesiącach czasami ciężko zgadnąć o co Ci chodziło o 3:27 PM jak dodałeś ten źle dodany feature
- typingi ❤️. Oprócz tego, że śliczne to jeszcze mówią nieraz więcej niż nazwa.
- pisząc backend dobrze myśleć o frontendzie. Myślę, że to nawet u nas się udało, chociaż można lepiej.
- ogólnie to fajny ten projekt, bardzo pomógł w dostaniu stażu jako Python Dev :))
