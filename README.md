# 🥑 Keto Scanner

Aplikacja mobilna do skanowania i oceny produktów spożywczych pod kątem wybranej diety.
Skanujesz etykietę → aplikacja sprawdza skład → dostajesz ocenę ✅ / ⚠️ / ❌

## 📱 Funkcje

- 📷 Skanowanie etykiet przez kamerę (ML Kit on-device lub AI Vision)
- 🍽️ Obsługa wielu diet: 🥑 Keto, 🥬 Wegańska, 🌾 Bezglutenowa, 🫙 Low FODMAP i inne
- 🔍 Wyszukiwanie produktów w OpenFoodFacts, Spoonacular, Nutritionix
- 👤 Własne profile dietetyczne z konfigurowalnymi regułami
- 📊 Historia skanów i dziennik posiłków
- 🏷️ Przeglądarka lokalnych etykiet i znanych produktów

## 📦 Pobierz

**[⬇️ Pobierz najnowszy APK — v1.4.7](https://github.com/malin-radek/keto-scanner/releases/tag/v1.4.7)**

[📋 Wszystkie wydania →](https://github.com/malin-radek/keto-scanner/releases)

## 📋 Changelog

### v1.5.0 (2026-06-10)

- 🧊 Przebudowa skanowania lodówki — zdjęcia zapisują się NATYCHMIAST po kliknięciu "Gotowe", bez czekania na analizę AI; nawet jeśli AI jest niedostępne, aplikacja działa w pełni
- 🧊 Analiza AI jest teraz OPCJONALNA — możesz dodać produkty ręcznie, bez używania VisionAI; przycisk "Analizuj przez AI" pojawia się gdy lista produktów jest pusta
- 🧊 Automatyczny zapis draftu — zdjęcia lodówki są automatycznie zapisywane w bazie zaraz po zrobieniu, więc nic nie ginie nawet jeśli wyjdziesz z ekranu
- 🧊 Nowy ekran wyniku działa w pełni bez AI — możesz dodać, edytować i zapisać produkty bez uruchamiania rozpoznawania obrazu

### v1.4.6 (2026-06-10)

- 🔧 Naprawa zapisu do bazy danych — aplikacja nie traci już połączenia z bazą po dłuższym przebywaniu w tle; eksport kopii zapasowej i zapis wszystkich danych działa niezawodnie
- 🔧 Usunięto błąd NullPointerException przy próbie odświeżenia połączenia z SQLite — nowe połączenie jest zawsze otwierane od nowa, bez ryzyka użycia martwego uchwytu

### v1.4.5 (2026-06-09)

- 📊 Nowa infografika dnia — jednym kliknięciem w dzienniku posiłków generujesz profesjonalną grafikę podsumowującą cały dzień: Diet Adherence, compliance, nutrition, energy, badge\
- ,
      
- ,
      
- ów osiągnięć — automatycznie przyznawane za zgodność z aktywnymi dietami (Sugar Free, Low Carb, Protein Goal, Heart Friendly i wiele innych) — max 5 najważniejszych na grafice
- 📤 Przycisk "Udostępnij" w widoku dnia — wygeneruj infografikę i podziel się nią przez systemowy arkusz udostępniania

### v1.4.4 (2026-06-09)

- 📋 Długie przytrzymanie na produkcie kopiuje go do schowka — działa na ekranie wyniku, historii, liście produktów i w szczegółach posiłku; skopiowany produkt możesz wkleić w edytorze posiłku
- 📋 Nowy przycisk "Wklej produkt" w edytorze posiłku — jeśli w schowku znajduje się skopiowany produkt, jednym kliknięciem dodajesz go do listy składników wraz z wartościami odżywczymi i oceną
- ⚖️ Nowe pole "Wielkość porcji (g)" w edytorze produktu — ustaw domyślną gramaturę (np. 30g dla plasterka sera), a przy tworzeniu posiłku gramatura zostanie automatycznie użyta
- ⚖️ W szczegółach posiłku widać gramaturę każdego produktu — wartości odżywcze są przeliczone na całą porcję, nie na 100g; jeśli produkt ma 150g, zobaczysz kalorie i makro dla całych 150g

### v1.4.3 (2026-06-09)

- 🔧 Połączenie z bazą danych nie rozłącza się już po długim przebywaniu aplikacji w tle — nawet po całej nocy kalendarz i dane dnia wczytują się bez restartu
- 🔧 Przycisk "Spróbuj ponownie" przy błędzie bazy danych faktycznie działa — każde kliknięcie ponawia próbę i pokazuje czytelny komunikat, a po 3 nieudanych próbach sugeruje restart aplikacji
- 🔧 Więcej komunikatów błędów SQLite jest teraz poprawnie wykrywanych i automatycznie naprawianych — połączenie odtwarza się bez ingerencji użytkownika---
_Ostatni build: 2026-06-10 17:11 · v1.4.7_