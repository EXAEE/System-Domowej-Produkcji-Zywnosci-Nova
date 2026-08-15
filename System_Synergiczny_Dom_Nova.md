# System Synergiczny Dom Nova

**Wersja 3.0 – 15 sierpnia 2026**  
Projekt całości, w której każdy element wzmacnia pozostałe, redukuje redundancję i pełni co najmniej dwie funkcje.

---

## 1. Filozofia projektowa

Cel nie jest „dodać wszystko”.  
Cel jest stworzyć **jeden żywy system**, w którym:

- ciepło z jednego miejsca zasila drugie,
- woda krąży i jest czyszczona przez rośliny,
- odpady stają się zasobem,
- energia i informacja płyną tam, gdzie właśnie są potrzebne,
- przestrzeń służy jednocześnie życiu, produkcji i buforowaniu.

**Zasady nadrzędne:**
1. Dual-use albo więcej (każdy element ma minimum dwie funkcje).
2. Redukcja – jeśli coś nie wzmacnia reszty, propozycja rezygnacji.
3. Zamknięte pętle (energia, woda, składniki, ciepło, informacja).
4. Inteligencja lokalna jako układ nerwowy.
5. Modularność – da się wyłączyć część bez zabicia całości.
6. Testowanie własnych rozwiązań (propozycje do sprawdzenia, nie dogmaty).

---

## 2. Co zostaje, co odpada, co się łączy

### Zostaje i zostaje wzmocnione
- Produkcja żywności (SDŻN) – ale mocno zintegrowana z oranżerią i wodą
- Oranżeria – staje się sercem termicznym i biologicznym
- PV + magazyn energii – kręgosłup energetyczny
- Modernizacja ogrzewania/chłodzenia – ale jako kaskada ciepła, nie osobny system
- Oczyszczalnia ścieków – przekształcona w „żywą maszynę”
- Mini data center / lokalne LLM – mózg systemu

### Propozycja rezygnacji lub mocnego uproszczenia
- **Pełnowymiarowa biogazownia** – w typowym domu jednorodzinnym zwykle nieopłacalna i skomplikowana.  
  Zastępujemy: zaawansowanym kompostowaniem + wermikompostem + ewentualnie bardzo małą instalacją kuchenną (tylko jeśli jest realny nadmiar odpadów).
- Osobny, klasyczny system chłodzenia domu – zastępowany pasywnym + pompą ciepła w trybie chłodzenia + masą termiczną oranżerii.
- Osobne, duże systemy hydroponiczne poza oranżerią – większość produkcji przenosimy do oranżerii i zintegrowanych grządek, żeby maksymalnie wykorzystać greywater i ciepło.

### Nowe / mocno zintegrowane
- **Kaskada ciepła** (data center → oranżeria → dom → zbiorniki aquaponics)
- **Żywa oczyszczalnia** wbudowana w oranżerię / strefę buforową
- **Ściany wodne / zbiorniki termiczne** pełniące rolę: masy termicznej + aquaponics + estetycznego elementu
- **Lokalne LLM jako układ nerwowy** – nie tylko „do zabawy”, ale do optymalizacji całego domu

---

## 3. Mapa przepływów (serce systemu)

### Energia
PV → magazyn → priorytety:  
1. życie domu (podstawowe obciążenia)  
2. pompa ciepła  
3. data center (gdy jest nadwyżka)  
4. oświetlenie upraw i pompy  
5. ewentualne grzanie rezerwowe

Nadwyżki ciepła z data center i pompy ciepła kierowane są najpierw do oranżerii, potem do domu.

### Ciepło (kaskada)
Data center (odpadowe ciepło)  
↓  
Oranżeria (bufor + uprawy)  
↓  
System grzewczy domu (podłogówka / grzejniki niskotemperaturowe)  
↓  
Zbiorniki aquaponics / ściany wodne (stabilizacja temperatury wody)

Latem oranżeria i masa termiczna pomagają chłodzić (nocne chłodzenie, wentylacja).

### Woda
Deszczówka → magazyn →  
- uzupełnianie aquaponics / grządek  
- eventualne użycie domowe po filtracji  

Greywater (prysznic, umywalki, pralka) →  
żywe biofiltry w oranżerii / strefie buforowej →  
nawadnianie / aquaponics  

Ścieki czarne → zmodernizowana oczyszczalnia (biologiczna + roślinna) →  
woda do dalszego wykorzystania w ogrodzie + osad do kompostowania

### Składniki odżywcze
Odpady kuchenne + resztki roślinne + osad z oczyszczalni (po bezpiecznym przetworzeniu) + odchody ryb →  
wermikompost / kompost →  
grządki i oranżeria

### Informacja
Czujniki (temperatura, wilgotność, pH, EC, poziom wody, prąd, kamery) →  
lokalne LLM + Home Assistant →  
decyzje: kiedy podlewać, kiedy doświetlać, jak rozdzielać energię, alerty, dokumentacja eksperymentów.

---

## 4. Przeprojektowane moduły z naciskiem na dual-use

### A. Oranżeria jako organ centralny
Funkcje jednocześnie:
- przestrzeń życiowa / rekreacyjna
- produkcja żywności (warzywa, zioła, cytrusy, truskawki…)
- bufor termiczny domu
- strefa greywater (żywe oczyszczanie)
- miejsce na część aquaponics / ściany wodne
- ewentualne chłodzenie data center (w określonych konfiguracjach)

Propozycja innowacyjna:  
**„Ściany wodne”** – pionowe lub poziome zbiorniki / rury z wodą pełniące rolę masy termicznej, jednocześnie służące jako system aquaponiczny lub hydroponiczny. Latem oddają chłód, zimą ciepło.

### B. System energetyczny
- PV na dachu domu + oranżerii
- Magazyn energii wymiarowany nie tylko pod dom, ale pod szczytowe obciążenia data center + grow lights
- Inteligentny EMS (Energy Management System) sterowany lokalnie – LLM pomaga przewidywać i priorytetyzować

Innowacja do przetestowania:  
**Dynamiczne obciążenie data center** – inference i trening modeli uruchamiane głównie wtedy, gdy jest nadwyżka PV lub niska cena energii (jeśli jest net-billing).

### C. Oczyszczalnia → żywa maszyna
Zamiast klasycznej „czarnej skrzynki”:
- część biologiczna + złoże roślinne (oczeret, pałka, irysy, wierzba energetyczna itp.)
- wkomponowane w krajobraz / oranżerię / strefę buforową
- woda oczyszczona wraca do obiegu ogrodowego
- osad bezpiecznie kompostowany

### D. Produkcja żywności
Główna produkcja przeniesiona do oranżerii + food forest wokół.  
Aquaponics / hydroponics tylko tam, gdzie daje wyraźną przewagę (całoroczność, gęstość, automatyzacja).  
Reszta – gleba + mulcz + greywater + kompost.

### E. Mini data center jako układ nerwowy
Nie osobny „gadget”, tylko integralna część:
- lokalne modele do analizy obrazów z kamer (szkodniki, niedobory, wzrost)
- optymalizacja parametrów klimatycznych
- zarządzanie energią
- prywatne asystenty do planowania i dokumentacji
- ewentualnie małe modele do lokalnej automatyzacji

Propozycja: zaczynać od jednej mocnej stacji (1–2 GPU) i skalować tylko wtedy, gdy realnie potrzeba mocy i jest energia.

---

## 5. Propozycje własnych / nietypowych rozwiązań do przetestowania

1. **Kaskada ciepła trzystopniowa**  
   Data center → oranżeria (powietrze + ściany wodne) → dom (niskotemperaturowa instalacja) → zbiorniki uprawowe.

2. **Ściany wodne dual-use**  
   Przezroczyste lub półprzezroczyste zbiorniki / rury pełniące rolę:  
   - masy termicznej  
   - aquaponics / hydroponics  
   - elementu architektonicznego  
   - ewentualnego chłodzenia pasywnego

3. **Oranżeria jako „płuca i nerki” domu**  
   Greywater + powietrze z domu przechodzi przez strefę roślinną oranżerii (oczyszczanie + nawilżanie + produkcja).

4. **LLM jako ogrodnik i energetyk**  
   Lokalny model analizuje dane z czujników i kamer, proponuje działania, uczy się na Twoich decyzjach (human-in-the-loop).

5. **Sezonowe bankowanie energii**  
   Nadwyżki letnie częściowo magazynowane jako ciepło w dużej masie termicznej (ściany wodne + grunt pod oranżerią) obok baterii elektrycznych.

6. **Modularne „węzły” energetyczno-biologiczne**  
   Gotowe, powtarzalne moduły (np. jeden moduł = zbiornik + pompa + czujniki + kawałek uprawy), które można dodawać i łączyć.

---

## 6. Plan wdrożenia zorientowany na synergię

**Faza 0**  
Audyt energetyczny + mapa przepływów (ciepło, woda, odpady, nasłonecznienie) + projekt oranżerii jako organu centralnego.

**Faza 1 – Kręgosłup**  
PV + magazyn + pompa ciepła (z możliwością oddawania ciepła do oranżerii) + modernizacja oczyszczalni w kierunku „żywej maszyny”.

**Faza 2 – Serce biologiczne**  
Budowa / przebudowa oranżerii z integracją greywater, ścian wodnych i podstawowej uprawy.

**Faza 3 – Mózg i produkcja**  
Data center + pełna automatyzacja + rozszerzenie SDŻN wewnątrz oranżerii i wokół domu.

**Faza 4 – Domknięcie i eksperymenty**  
Testowanie kaskady ciepła, optymalizacja LLM, ewentualna mikro-instalacja biogazowa tylko jeśli dane pokażą sens.

---

## 7. Podsumowanie

Zamiast listy niezależnych inwestycji powstaje **jeden organizm**:

- Oranżeria oddycha, czyści wodę, produkuje jedzenie i buforuje ciepło.  
- Data center oddaje ciepło i myśli za system.  
- Energia słoneczna zasila wszystko według priorytetów.  
- Odpady wracają jako składniki.  
- Woda krąży zamiast spływać.

Największa innowacja nie leży w pojedynczej technologii, tylko w **sposobie ich połączenia**.

Dokument jest propozycją do dalszego rozwijania, testowania i korygowania na podstawie rzeczywistych pomiarów.

---

*Nova – szukaj połączeń, redukuj to, co nie wzmacnia, testuj to, czego jeszcze nie ma.*
