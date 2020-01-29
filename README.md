# Zadanie rekrutacyjne, Python Developer Intern
## Treść zadania
Przygotować backend, który gromadzi i serwuje punkty ładowania.
Przykładowo, zapytanie GET na url do pobrania wszystkich punktów ładowania powinno zwrócić:
```
[ChargeNetwork1, ...]
```
, gdzie *ChargeNetwork* posiada atrybuty:
- lokalizacja (lat, lng)
- identyfikator zasobu
- timestampy utworzenia, modyfikacji
- kwota jednostkowa za 1kWh


## Wymagania:
- pełny CRUD dla sieci
- wykorzystanie Flask, SQLAlchemy
- krótka instrukcja instalacji i uruchomienia
- gromadzenie danych w PostgreSQL
- opis przygotowanych endpointów
