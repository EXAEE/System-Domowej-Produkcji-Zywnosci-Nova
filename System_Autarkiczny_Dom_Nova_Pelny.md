# System Autarkiczny Dom Nova – Pełna Wersja

**Wersja 2.0 – 15 sierpnia 2026**  
Rozszerzenie SDŻN o: oranżerię, przebudowę systemu grzewczo-chłodzącego, modernizację oczyszczalni ścieków, fotowoltaikę + magazyn energii, mini centrum danych (lokalne LLM), opcjonalną biogazownię.

---

## 1. Realistyczna ocena kosztów (Polska 2026, widełki średnie)

| Moduł | Orientacyjny koszt brutto | Po typowych dotacjach / ulgach | Uwagi |
|-------|---------------------------|--------------------------------|-------|
| SDŻN (żywność + szklarnia/aquaponics + automatyka) | 40–80 tys. zł | 35–70 tys. | Zależnie od skali |
| Oranżeria / ogród zimowy 20–40 m² | 80–200 tys. zł | 70–180 tys. | Aluminium + dobre przeszklenia |
| Przebudowa ogrzewania + chłodzenie (pompa ciepła powietrze-woda + instalacja) | 50–90 tys. zł | 25–55 tys. | Czyste Powietrze + ulga |
| Modernizacja przydomowej oczyszczalni (biologiczna) | 15–25 tys. zł | 10–20 tys. | Lokalne dofinansowania |
| PV 10–15 kWp + magazyn 10–20 kWh | 60–110 tys. zł | 30–70 tys. | Mój Prąd + ulga |
| Mini data center (lokalne LLM – 1–2 mocne GPU / workstation) | 15–50 tys. zł | 15–50 tys. | Brak dotacji |
| Opcjonalnie mała biogazownia (mikro) | 20–80 tys. zł | 15–60 tys. | Bardzo niski ROI |
| **Razem orientacyjnie** | **280–635 tys. zł** | **200–505 tys. zł** | Duża rozpiętość |

**Uwaga:** To nie jest wycena ofertowa. Rzeczywiste koszty zależą od stanu istniejącego budynku, działki, jakości materiałów i zakresu robót. Dotacje (Czyste Powietrze, Mój Prąd, ulga termomodernizacyjna, lokalne programy) mogą znacząco obniżyć koszt netto, ale nie pokryją wszystkiego.

---

## 2. Analiza opłacalności kredytu na całość

### Założenia przykładowe
- Kwota kredytu: 350 000 zł (po częściowym dofinansowaniu)
- RRSO: ~8,5–9,5% (kredyt gotówkowy / hipoteczny konsumpcyjny)
- Okres: 12–15 lat
- Rata miesięczna: orientacyjnie **3 800 – 5 200 zł**

### Realistyczne oszczędności roczne (po pełnym uruchomieniu)
- Energia (PV + pompa ciepła + magazyn): 6–15 tys. zł
- Żywność (częściowa): 1–3 tys. zł
- Woda / ścieki: 0,5–1,5 tys. zł
- Inne (komfort, mniej awarii): trudno policzyć
- **Razem realistycznie: 8–20 tys. zł/rok** w dobrym scenariuszu

### Wniosek finansowy
Przy racie 4–5 tys. zł miesięcznie oszczędności pokrywają tylko część raty. Czysto finansowy zwrot wychodzi **15–25+ lat** (lub dłużej przy gorszym scenariuszu).  
Dodatkowe ryzyka: wzrost stóp procentowych, awarie, niedoszacowanie kosztów, opóźnienia w dotacjach, krzywa uczenia się systemu.

**Werdykt Novy:**  
Duży kredyt na *wszystko naraz* jest ryzykowny i w większości przypadków nieoptymalny. System ma ogromną wartość odpornościową, ekologiczną i jakości życia, ale nie jest „inwestycją finansową z szybkim ROI”.

**Lepsze podejście:**  
Maksymalizuj dotacje → buduj etapami z własnych środków / małych, celowanych kredytów → priorytetyzuj moduły o najwyższym zwrocie odpornościowym i finansowym.

---

## 3. Plan etapowy (rekomendowany)

### Faza 0 – Fundamenty (0–6 miesięcy)
1. Dokładna inwentaryzacja budynku i działki (audyt energetyczny, mapa nasłonecznienia, warunki gruntowe, istniejąca oczyszczalnia).
2. Złożenie wniosków o wszystkie możliwe dotacje (Czyste Powietrze, Mój Prąd, lokalne).
3. Mapa permakulturowa + projekt oranżerii + koncepcja integracji energii.

### Faza 1 – Wysoki zwrot + odporność (6–18 miesięcy)
Priorytet:
- Fotowoltaika + magazyn energii (najszybszy zwrot finansowy + niezależność)
- Pompa ciepła + modernizacja grzania/chłodzenia (duże oszczędności + komfort)
- Modernizacja oczyszczalni ścieków (zamknięcie obiegu wody + greywater do systemu żywności)
- Podstawowy SDŻN (woda deszczowa, grządki, mały moduł aquaponics/indoor)

### Faza 2 – Produkcja żywności i przestrzeń (18–36 miesięcy)
- Oranżeria (integracja z systemem grzewczym i żywnościowym)
- Rozszerzenie SDŻN (szklarnia pasywna, food forest, większa automatyzacja)
- Mini data center (lokalne LLM) – można zacząć od mocnej stacji roboczej

### Faza 3 – Domknięcie i optymalizacja (36+ miesięcy)
- Pełna integracja automatyzacji (Home Assistant / lokalny stack)
- Opcjonalna mikro-biogazownia (tylko jeśli jest dużo odpadów organicznych i realny sens)
- Monitoring, fine-tuning, dokumentacja własnych doświadczeń

---

## 4. Innowacje i optymalizacje całego systemu

### Integracja energetyczna
- Oranżeria jako bufor cieplny i źródło pasywnego ogrzewania / chłodzenia domu.
- Nadwyżki ciepła z data center i pompy ciepła kierowane do oranżerii i aquaponics w zimie.
- Inteligentne zarządzanie obciążeniem: LLM inference w godzinach nadwyżki PV.

### Obieg wody i składników
- Greywater z domu → biofiltr → oranżeria / grządki / aquaponics.
- Osad z oczyszczalni + kompost + odpady z data center chłodzenia → wermikompost / biogaz.
- Deszczówka jako główne źródło uzupełniania systemów uprawowych.

### Lokalne LLM + automatyzacja
- Mini data center nie tylko do „zabawy z modelami”, ale jako mózg systemu:
  - Predykcja plonów i optymalizacja parametrów upraw
  - Lokalne modele do analizy obrazów z kamer (szkodniki, niedobory)
  - Sterowanie Home Assistant bez chmury
  - Prywatne asystenty do dokumentacji i planowania

### Optymalizacje konstrukcyjne
- Oranżeria zorientowana i izolowana tak, aby latem nie przegrzewała domu, a zimą oddawała ciepło.
- Podwójne / potrójne wykorzystanie przestrzeni (oranżeria = strefa 1 + buffer termiczny + przestrzeń rekreacyjna).
- Modularność data center – zaczynasz od 1 GPU, dokładasz w miarę potrzeb i nadwyżek energii.

### Biogaz (opcjonalnie)
- Tylko mikro-skala i tylko jeśli masz realny nadmiar odpadów organicznych.
- Lepiej traktować jako element edukacyjny / zamykania obiegu niż jako źródło energii.

---

## 5. Kluczowe ryzyka i zasady bezpieczeństwa

- **Finansowe**: nie łącz wszystkich inwestycji w jeden duży kredyt.
- **Techniczne**: każdy moduł musi dać się wyłączyć / obejść bez zawalenia całego systemu.
- **Operacyjne**: krzywa uczenia jest stroma – zakładaj 1–2 sezony na dojście do stabilności.
- **Prawne**: oranżeria, oczyszczalnia, przyłącza – formalności i pozwolenia.
- **Energetyczne**: data center + pompa ciepła + LED grow lights to znaczące obciążenie – magazyn i zarządzanie mocą są krytyczne.

---

## 6. Rekomendacja końcowa

Nie bierz kredytu na „wszystko naraz”.

Zrób dokładny audyt → maksymalizuj dotacje → buduj w kolejności:
1. Energia (PV + magazyn + pompa ciepła)
2. Woda i ścieki
3. Żywność + oranżeria
4. Data center i zaawansowana automatyzacja
5. Biogaz tylko jeśli ma realny sens

System ma potencjał stać się prawdziwie autarkicznym i regeneratywnym domem. Jego wartość leży bardziej w odporności, jakości życia i zamkniętych obiegach niż w szybkim zwrocie finansowym.

---

*Nova – ciekawość, realizm, zamknięte obiegi.*
