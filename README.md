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

**[⬇️ Pobierz najnowszy APK — v1.0.140](https://github.com/malin-radek/keto-scanner/releases/tag/v1.0.140)**

[📋 Wszystkie wydania →](https://github.com/malin-radek/keto-scanner/releases)

## 📋 Changelog

### v1.0.139 (2026-06-07)

- ✋ Ręczne ustawianie wagi na ekranie Waga — przesuwaj palcem w górę/dół na każdej cyfrze, aby wprowadzić wagę bez wagi Bluetooth
- 📡 Skaner wagi Bluetooth działa tylko gdy ekran Waga jest otwarty — oszczędza baterię i nie szuka wagi w tle
- 🗑️ Usuwanie konkretnego pomiaru wagi — w dzienniku posiłków i w szczegółach posiłku kliknij kosz, aby usunąć wybrane ważenie

### v1.0.138 (2026-06-07)

- 🔥 Nowy kalkulator TDEE w Profilu ciała — wybierz tryb życia, a aplikacja wyliczy Twoje dzienne zapotrzebowanie kaloryczne (Mifflin–St Jeor) z możliwością korekty o ±25%

### v1.0.131 (2026-06-06)

- 🔧 Szczegółowe logi diagnostyczne przy nieudanym rozpoznaniu posiłku — przycisk "Kopiuj curl" kopiuje 1:1 zapytanie wysłane do AI, a "Kopiuj odpowiedź API" kopiuje surową odpowiedź z serwera, aby łatwo znaleźć przyczynę błędu

### v1.0.130 (2026-06-06)

- 📅 Profil ciała: zamiast wieku podajesz datę urodzenia — aplikacja sama wylicza wiek, zawsze aktualny, bez konieczności ręcznej aktualizacji

### v1.0.128 (2026-06-06)

- ℹ️ Dotknij dowolnego wskaźnika składu ciała (BMI, tkanka tłuszczowa, mięśnie, woda, itd.), aby zobaczyć wyczerpujący opis: co to jest, jak jest liczone, jakie są normy i dlaczego jest ważne---
_Ostatni build: 2026-06-07 01:42 · v1.0.140_