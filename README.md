# gtfs-pwik-jaroslaw
Pliki GTFS Schedule dla Jarosławskiej Komunikacji Miejskiej.

## Obsługiwane funkcje
Feed zawiera następujące elementy GTFS:
- Agency (agency.txt)
- Stops (stops.txt)
- Routes (routes.txt)
- Service Dates (calendar.txt, calendar_dates.txt)
- Trips (trips.txt)
- Stop Times (stop_times.txt)
- Feed Information (feed_info.txt)
- Route Colors (routes.txt)
- Headsigns (routes.txt)
- Stops Wheelchair Accessibility (stops.txt, *UWAGA: dane o dostępności przystanków są subiektywne i mogą okazać się błędne.)
- Trips Wheelchair Accessibility (trips.txt *Uwaga: dane o dostępności kursów zostały ustalone na podstawie informacji, że 100% obecnie eksploatowanego taboru stanowią pojazdy niskowejściowe lub niskopodłogowe)
- Fares V1 (stops.txt, fare_attributes.txt, fare_rules.txt)
  
## Dokładność lokalizacji przystanków
Lokalizacje niektórych przystanków są przybliżone i oznaczają miejsca, w których autobus zazwyczaj się zatrzymuje. W części lokalizacji nie występuje fizyczna infrastruktura przystankowa (np. słupek przystankowy).

## Dodatkowe pole `direction` w stops.txt
Plik `stops.txt` zawiera dodatkowe, niestandardowe pole `direction`, które określa stronę ulicy oraz kierunek jazdy po wsiadaniu na przystanku:

- `1` – odjazdy w kierunku Centrum Przesiadkowego
- `2` – odjazdy w kierunku przeciwnym od Centrum Przesiadkowego

Pole to ma charakter pomocniczy, służy wyłącznie do ułatwienia tworzenia i utrzymywania plików GTFS, nie jest częścią oficjalnej specyfikacji i nie powinno być wykorzystywane w aplikacjach.

## Aktualność danych
Dane zawarte w feedzie są aktualne i poprawne na dzień publikacji. Obowiązują do dnia 31 maja 2026 r., o ile wcześniej nie nastąpi zmiana rozkładu jazdy.

## Dokładność danych
Uwaga! Część danych została wygenerowana automatycznie. Ze względu na ich ilość, niemożliwe jest ich ręczne przejrzenie. Feed jest udostępniany „tak jak jest” (as is), a jego autor nie ponosi odpowiedzialności za ich kompletność, aktualnośćani poprawność.

## Status prawny
Dane zawarte w tym repozytorium stanowią ponowne wykorzystanie informacji publicznej. Zostały opracowane ręcznie na podstawie dostępnych publicznie rozkładów jazdy.
Feed jest nieoficjalny i nie jest powiązany z Urzędem Miasta Jarosławia (organizatorem) ani Przedsiębiorstwem Wodociągów i Kanalizacji w Jarosławiu Sp. z o.o. (operatorem).

## Źródła danych
- informacje o czasie odjazdów: https://pwik-jaroslaw.pl/rozklad-jazdy/
- informacje o taryfie opłat: https://pwik-jaroslaw.pl/taryfa-oplat/

## Licencja
Pliki tego repozytorium są licencjonowane na podstawie licencji Creative Commons Attribution 4.0 International (CC BY 4.0).
Kopia licencji: https://creativecommons.org/licenses/by/4.0/
