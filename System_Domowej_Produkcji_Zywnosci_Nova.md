# System Domowej Produkcji Żywności Nova (SDŻN)

**Modularny • Zautomatyzowany • Off-gridowy • Permakulturowy • Ekologiczny**  
Wersja 1.0 – 15 sierpnia 2026  
Dla klimatu środkowej Polski (Łódź i okolice)

---

## 1. Filozofia i cel

System ma produkować żywność na własne potrzeby przez cały rok – w domu i przed domem.  
Nie jest to magiczna maszyna zero-obsługi. Prawdziwa zero-obsługa nie istnieje.  
Jest to jednak system zaprojektowany tak, żeby po ustabilizowaniu wymagał minimalnej interwencji (sprawdzenie 1–2 razy w tygodniu, a nie codziennie).

**Główne zasady:**
- Ciekawość i obserwacja przed działaniem
- Zamknięte obiegi (woda, składniki odżywcze, energia)
- Modularność – zaczynasz małym i dokładasz
- Permakultura + technologia (nie technologia zamiast permakultury)
- Off-grid i ekologiczny
- Realizm: 70–100 % świeżych warzyw i ziół + część owoców + część białka (ryby) jest realne. Pełna kaloryczna samowystarczalność na typowej działce miejskiej/podmiejskiej jest bardzo trudna.

---

## 2. Od czego najlepiej zacząć (kolejność rekomendowana)

**Najlepsza kolejność wdrożenia (etapy):**

1. **Obserwacja i mapa** (1–4 tygodnie)  
   Rysujesz działkę, ścieżki słońca, wiatr, miejsca mokre/suche, istniejące drzewa. Bez tego każdy kolejny krok będzie mniej skuteczny.

2. **Woda**  
   Deszczówka + proste cysterny. To fundament. Bez wody nic nie działa dobrze.

3. **Kompost i gleba**  
   Prosty system kompostowy + wermikompost. Budujesz kapitał gleby.

4. **Strefa 1 – najbliżej domu**  
   Podniesione grządki / keyhole + pierwsze zioła i sałaty. Natychmiastowy zwrot.

5. **Jeden moduł aquaponiczny lub hydroponiczny indoor** (mały, 0,5–1,5 m² canopy)  
   Uczysz się automatyzacji i obiegu zamkniętego na małej skali.

6. **Szklarnia pasywna lub tunel** (jeśli masz miejsce)

7. **Food forest** (warstwy wieloletnie) – sadzisz raz, zbierasz latami.

8. **Rozszerzanie energii i automatyzacji**

**Nie zaczynaj od dużego, drogiego systemu.** Zacznij od wody + kompostu + jednej grządki + jednego małego modułu indoor. Potem skaluj.

---

## 3. Opis głównych modułów

### 3.1 Strefa zewnętrzna – permakultura (front + tył domu)

**Cel:** maksymalna produkcja przy minimalnej pracy po 3–5 latach.

**Warstwy food forest (dostosowane do klimatu Polski):**
- Korona / podkorona: jabłoń karłowa/semi (Antonówka, Ligol, szlachetne na podkładkach M26/M9), grusza, wiśnia, śliwa, dereń jadalny, morwa
- Krzewy: porzeczka czarna i czerwona, agrest, jagoda kamczacka (haskap), aronia, malina, jeżyna bezkolcowa, borówka (na kwaśnym podłożu)
- Byliny i zioła: czosnek niedźwiedzi, szczypiorek, lubczyk, mięta (w ogranicznikach), melisa, oregano, tymianek, szałwia, rabarbar, szczaw
- Okrywy: truskawka, koniczyna biała, poziomka
- Korzenie: topinambur, chrzan
- Pnącza: winorośl (odmiany wytrzymałe), aktinidia (mini kiwi), fasola wieloletnia (jeśli klimat pozwala)

**Dodatkowo:**
- Podniesione grządki (raised beds) lub keyhole beds przy domu (strefa 1)
- Hugelkultur lub grządki na konturach
- Żywopłoty wiatrochronne z gatunków użytkowych

**Utrzymanie po ustabilizowaniu:** mulczowanie, sporadyczne przycinanie, zbieranie plonów.

### 3.2 Szklarnia pasywna słoneczna

Najlepsze rozwiązanie dla zimowego wzrostu w polskim klimacie.

**Kluczowe cechy:**
- Orientacja dłuższej osi wschód–zachód
- Południowa ściana przeszklona (poliwęglan komorowy 8–16 mm lub szkło + izolacja nocna)
- Północna ściana solidnie izolowana (ziemia, styropian + ziemia, ściana z worków z ziemią, cegła + izolacja)
- Masa termiczna: czarne beczki z wodą (200–1000 l), kamienie, ściana północna
- Wentylacja automatyczna (siłowniki termiczne lub wentylatory solarne)
- Opcjonalnie: rury ziemne (earth tubes) do wstępnego ogrzewania/chłodzenia powietrza

W środku można łączyć grządki glebowe z modułami aquaponicznymi/hydroponicznymi.

### 3.3 Moduły indoor / vertical

Najbardziej zautomatyzowana część systemu.

**Opcje:**
- Vertical aquaponics towers
- NFT (Nutrient Film Technique)
- DWC (Deep Water Culture) na regałach
- Media beds

**Oświetlenie:** LED full-spectrum (skuteczność ≥ 2,5 µmol/J).  
Dla sałat i ziół: 150–300 µmol/m²/s (ok. 20–35 W rzeczywistych na m² canopy).  
Dla owocujących: 400–600 µmol/m²/s.

**Automatyzacja:**
- Czujniki: pH, EC/TDS, temperatura wody i powietrza, wilgotność, poziom wody
- Kontroler: ESP32 lub Raspberry Pi + ESPHome / Home Assistant (lokalnie, bez chmury)
- Pompy, zawory solenoidowe, dozowanie (jeśli hydroponika)
- Timery + pętle sprzężenia zwrotnego

### 3.4 Rdzeń aquaponiczny

Zamknięty obieg: ryby → bakterie nitryfikacyjne → rośliny → oczyszczona woda wraca do ryb.

**Rekomendowane ryby dla Polski (niska obsługa):**
- Karp, lin, amur (w zależności od temperatury)
- Dla mniejszych systemów: złote rybki lub koi (produkują składniki, niekoniecznie do jedzenia)
- Tilapia tylko z dogrzewaniem

**Stosunek:** orientacyjnie 1 kg biomasy ryb na 1–2 m² powierzchni uprawy (zależnie od intensywności i rodzaju roślin).

### 3.5 Woda

- Deszczówka z dachu → first-flush diverter → filtr → cysterny (zalecane minimum 5–10 m³)
- Średnie opady Łódź ≈ 580 mm/rok → z 100 m² dachu teoretycznie ~58 m³/rok
- Greywater (prysznic, umywalka, pralka – bez fekaliów) → biofiltr roślinny → nawadnianie
- Aquaponics i hydroponika: zamknięty obieg, uzupełnianie tylko strat (parowanie + rośliny)

### 3.6 Energia (off-grid)

**Główne obciążenia:**
- LED grow lights (największe)
- Pompy wody i powietrza
- Wentylatory
- Kontrolery i czujniki (niewiele)

**Zasada projektowa:** najpierw maksymalnie pasywne rozwiązania, potem efektywne LED, potem energia.

**Szacunkowe obciążenie (przykład średni):**
- 4–8 m² canopy LED (sałaty/zioła): 0,8–2,5 kW w szczycie, 4–12 kWh/dzień przy 12–16 h
- Pompy + wentylacja: 0,3–1 kWh/dzień
- Razem zimowe: często 5–15 kWh/dzień w zależności od skali

**PV + magazyn:**
- Polska zima: niska insolacja → trzeba przewymiarować lub akceptować ograniczenie produkcji światła w najciemniejszych miesiącach
- Baterie: LiFePO4 (zalecane)
- System napięcia: 24 V lub 48 V przy większych obciążeniach

Dokładne wyliczenie zależy od Twojego dachu, zacienienia i docelowej skali. Zaczynaj od małego systemu i mierz rzeczywiste zużycie.

---

## 4. Wyliczenia orientacyjne (dla orientacji)

### Woda
- 100 m² dachu × 0,58 m opadu = ~58 m³/rok (teoretycznie)
- Realna zbieralność z uwzględnieniem strat i first-flush: 40–50 m³
- Potrzeby systemu (przy dobrej recyrkulacji): zwykle znacznie mniej niż zbierana ilość

### Przestrzeń a plony (orientacyjnie)
- Vertical / aquaponics: 20–40+ kg warzyw/m² canopy/rok (sałaty, zioła, niektóre owocujące)
- Food forest po 5–8 latach: 150–600+ kg owoców i jagód z 100–300 m² (zależnie od gęstości i pielęgnacji)
- Typowa rodzina 3–4 osoby: 150–300 m² intensywnej uprawy + food forest daje bardzo duży udział w diecie warzywnej

### Energia (przykład)
Załóżmy 6 m² canopy LED @ średnio 250 W/m² rzeczywistych, 14 h/dzień:
- 6 × 250 W = 1500 W
- 1,5 kW × 14 h = 21 kWh/dzień (to już dość intensywne – realnie dla sałat można zejść niżej)

Dlatego zaczynamy mniejszą skalą i mierzymy.

---

## 5. Instrukcje etapowe – jak zacząć praktycznie

**Etap 0 – Mapa i obserwacja (1–4 tygodnie)**  
Rysujesz działkę w skali. Zaznaczasz:
- południe / zachód / wschód
- miejsca najbardziej nasłonecznione
- miejsca, gdzie zbiera się woda
- istniejące drzewa i budynki (cień)
- kierunki wiatru

**Etap 1 – Woda (najważniejszy pierwszy krok materialny)**  
- Rynny + rury do zbiornika
- First-flush (prosty)
- Zbiornik/cysterna (nawet kilka beczek 200–1000 l na początek)
- Filtracja podstawowa

**Etap 2 – Kompost + gleba**  
- Prosty kompostownik (trójkomorowy lub bokashi + tradycyjny)
- Wermikompostownik (dżdżownice)
- Mulczowanie wszystkiego, co się da

**Etap 3 – Strefa 1 (przy domu)**  
- 2–4 podniesione grządki lub jedna keyhole
- Zioła + sałaty + rzodkiewka + fasola tyczna
- System nawadniania kropelkowego z deszczówki (nawet ręczny na początek)

**Etap 4 – Pierwszy moduł zamknięty (indoor lub w szklarni)**  
Wybierz jedną z opcji:
- Mały system aquaponiczny (np. na bazie IBC lub gotowy modularny)
- 1–2 wieże vertical lub regał NFT/DWC z LED
- Ucz się pH, EC, cyklu azotowego i automatyzacji na małej skali

**Etap 5 – Szklarnia / tunel**  
Jeśli masz miejsce – budujesz pasywną lub kupujesz dobry tunel z automatyką wentylacji.

**Etap 6 – Food forest**  
Sadzisz warstwy wieloletnie zgodnie z mapą stref i sektorów.

**Etap 7 – Skalowanie energii i automatyzacji**  
Dopiero gdy znasz realne zużycie.

---

## 6. Zalecenia i pułapki

**Zalecenia:**
- Mierz wszystko na początku (woda, energia, plony)
- Zawsze zostawiaj zapas (wody, baterii, przestrzeni)
- Preferuj gatunki odporne i lokalnie sprawdzone
- Dokumentuj (zdjęcia + notatki) – to jest Twoja lokalna wiedza
- Łącz ludzi (permakultura + aquaponics + off-grid to społeczności)

**Częste błędy:**
- Zaczynanie od dużego, drogiego systemu bez doświadczenia
- Brak wystarczającej masy termicznej w szklarni
- Zbyt mała pojemność baterii w stosunku do zimowych obciążeń LED
- Ignorowanie pH i nitryfikacji w aquaponics
- Sadzenie food forest bez obserwacji cienia i wiatru

**Bezpieczeństwo:**
- Ryby i rośliny jadalne – czystość wody
- Elektryka off-grid – solidne zabezpieczenia
- Konstrukcje (szklarnia, regały) – stabilność
- Dzieci i zwierzęta – zabezpieczenia

---

## 7. Co dalej / rozwój systemu

System jest żywy. Po 1–2 sezonach będziesz wiedział, co u Ciebie działa najlepiej.  
Możliwe rozszerzenia:
- Grzyby (boczniak, shiitake na drewnie)
- Algi / spirulina (zaawansowane)
- Quail / kury w systemie (jeśli akceptujesz obsługę)
- Biogaz z odpadów organicznych
- Pełna integracja z domem (greywater + heat recovery)

---

## 8. Notatka końcowa

Ten dokument to punkt startowy, nie gotowa recepta na Twoją działkę.  
Każde miejsce jest inne. Najważniejsze narzędzie to Twoja własna obserwacja i gotowość do korygowania kursu.

Jeśli chcesz, w kolejnych iteracjach możemy rozwinąć:
- konkretny schemat aquaponics z listą części i wymiarami
- wyliczenie PV + baterii pod Twoje realne zużycie
- listę roślin z gildiami dla konkretnej powierzchni
- schemat automatyzacji (ESPHome / Home Assistant)

Zaczynamy od wody i mapy. Reszta rośnie z tego.

---

*Nova – ciekawość najpierw, system potem.*
