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

**[⬇️ Pobierz najnowszy APK — v1.7.8](https://github.com/malin-radek/keto-scanner/releases/tag/v1.7.8)**

[📋 Wszystkie wydania →](https://github.com/malin-radek/keto-scanner/releases)

## 📋 Changelog

### v1.7.0 (2026-06-24)

- ⚖️ Obsługa wagi kuchennej HOTO — waż składniki bezpośrednio podczas budowania posiłku; waga pokazuje się na kamerze w czasie rzeczywistym
- ⚖️ Automatyczne uzupełnianie wagi składnika — gdy waga HOTO jest stabilna, gramatura sama wpisuje się w edytorze
- ⚖️ Przycisk ⚖️ przy każdym składniku — jednym kliknięciem ustawiasz wagę z HOTO bez ręcznego wpisywania
- ⚖️ Dedykowany ekran wagi kuchennej z karuzelą cyfr — osobny widok do ważenia bez skanowania
- 🧠 AI rzadziej zgaduje nazwę dania — nowe reguły w prompcie wymuszają wypisywanie składników zamiast wymyślania potraw (np. "pomidorki koktajlowe" zamiast "sushi")
- ⚖️ Wielkość porcji w opisie wyniku AI — opis każdego składnika zawiera teraz informację o szacunkowej porcji (np. "pomidorki koktajlowe, porcja ok. 150g")
- 🔢 Płynniejsza animacja cyfr na wadze ciała (AnimatedNumber) — ta sama karuzela co w HOTO, ale w trzech rozmiarach

### v1.6.0 (2026-06-12)

- 🔒 Nowy tryb "Rozpoznaj produkt" działa W PEŁNI OFFLINE — ML Kit Text Recognition (OCR) czyta nazwę produktu z opakowania, a Image Labeling rozpoznaje kategorię (jogurt, ser, pomidory itp.)
- 🧠 Potrójne rozpoznawanie: (1) OCR z opakowania → konkretna nazwa np. "Jogurt Pilos", (2) kategoryzacja obrazu → typ produktu np. "jogurt", (3) Gemini AI jako fallback gdy offline nie da rady
- 📸 Automatyczne zapisywanie zdjęcia produktu — przy wyborze z listy zdjęcie jest zapisywane i wyświetlane na karcie wyniku
- 🖼️ Zdjęcia produktów widoczne na kartach wyników, w "Moich produktach" i w szczegółach
- 📦 Ponad 13 000 produktów w lokalnej bazie — wyszukiwanie offline po nazwie i kategorii, bez potrzeby internetu
- 🖼️ Brandowany splash screen z paskiem postępu — logo i wersja automatycznie dobierana; inicjalizacja bazy danych i konfiguracji pokazana krok po kroku
- 🧊 Skan lodówki można zapisać bez produktów — zdjęcia i typ posiłku wystarczą; kliknięcie w skan otwiera edytor do późniejszej poprawy
- 🧊 Analiza AI w edytorze lodówki działa jak w posiłkach — wybór modelu (Gemini, ChatGPT, OpenRouter, NVIDIA) i szczegółowa diagnostyka błędów z przyciskami kopiowania
- 🧊 Nowy przycisk "Lodówka" na ekranie głównym — szybki dostęp do skanowania lodówki z wyborem modelu AI przed pierwszą analizą
- 🧊 Przesuwanie kropki przez długie przytrzymanie (long-press) z auto-panem — gdy palec dosięga krawędzi, zdjęcie delikatnie przesuwa się odsłaniając ukryte obszary
- 🧊 Precyzyjne przybliżanie zdjęcia lodówki i posiłku — płynny pinch-to-zoom z kropkami stałego rozmiaru; tapnięcie w trybie "Dodaj produkt" wskazuje dokładne miejsce
- 🧊 Przebudowa skanowania lodówki — zdjęcia zapisują się NATYCHMIAST, analiza AI jest OPCJONALNA; automatyczny zapis draftu
- 🍽️ Nowy przycisk "Dodaj posiłek" w dzienniku — otwiera pustą kartę do ręcznego dodania składników, z opcjonalną analizą AI
- 🍽️ Dodawanie składników ręcznie bez zdjęcia — przycisk "Dodaj składnik" działa zawsze; "Analizuj przez AI" to osobna, manualna akcja
- 📱 Znak wodny kodu kreskowego w skanerze jako prawdziwy paskowy kod — nie zawija się na wąskich ekranach
- 🔢 Numerowane kropki na zdjęciach posiłków — tapnij numer na zdjęciu, a lista przewinie się do odpowiedniego składnika
- ⚠️ Inteligentne alerty dziennych limitów — przy dodawaniu produktu aplikacja ostrzega, jeśli przekroczysz dzienne limity kcal, węgli, tłuszczu, białka i cukru
- 🔍 Przeglądarka lokalnych etykiet — pełna lista zapisanych produktów z możliwością edycji, usuwania i filtrowania
- 🥑 System Nutri-Score — każdy produkt otrzymuje europejską ocenę wartości odżywczej (A–E) jako uzupełnienie oceny keto

### v1.4.0 (2026-06-11)

- 📊 Nowa infografika dnia — jednym kliknięciem generujesz profesjonalną grafikę podsumowującą cały dzień: Diet Adherence, compliance, nutrition, energy, 20+ badge\
- ,
      
- Udostępnij
- ,
      
- ,
      
- ,
      
- Wielkość porcji (g)
- ,
      
- ,
      
- ,
      
- ,
      
- em (🟢🟡🟠🔴) przy każdym produkcie
- 🍽️ Nowy przycisk "Utwórz posiłek" na ekranie wyniku skanowania — jednym kliknięciem przenosisz dane produktu do dziennika posiłków
- 🔙 Przycisk wstecz (sprzętowy Android) na szczegółach przepisu i produktu wraca do listy, a nie do ekranu głównego
- 🔧 Naprawy stabilności bazy danych — aplikacja nie traci połączenia po dłuższym przebywaniu w tle; przycisk "Spróbuj ponownie" przy błędzie faktycznie działa
- 🔧 Poprawki sumowania wartości odżywczych — podsumowanie posiłku odświeża się po powrocie z edycji; zerowe wartości są prawidłowo wliczane

### v1.3.1 (2026-06-09)

- ℹ️ Nowy ekran "O aplikacji" w menu — zobacz kod QR, link do repozytorium na GitHub i pełną historię zmian

### v1.3.0 (2026-06-09)

- 🏷️ Badge oceny na infografice posiłku — każdy składnik ma teraz kolorową kropkę i etykietę (KETO GREEN, DOBRY, OSTROŻNIE, NIE PASUJE)
- 📊 Średnia ocena całego posiłku — na dole infografiki podsumowanie z emoji i ogólnym wynikiem w skali 0–100---
_Ostatni build: 2026-06-29 01:49 · v1.7.8_