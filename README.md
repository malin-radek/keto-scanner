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

**[⬇️ Pobierz najnowszy APK — v1.0.129](https://github.com/malin-radek/keto-scanner/releases/tag/v1.0.129)**

[📋 Wszystkie wydania →](https://github.com/malin-radek/keto-scanner/releases)

## 📋 Changelog

### v1.0.130 (2026-06-06)

- 📅 Profil ciała: zamiast wieku podajesz datę urodzenia — aplikacja sama wylicza wiek, zawsze aktualny, bez konieczności ręcznej aktualizacji

### v1.0.128 (2026-06-06)

- ℹ️ Dotknij dowolnego wskaźnika składu ciała (BMI, tkanka tłuszczowa, mięśnie, woda, itd.), aby zobaczyć wyczerpujący opis: co to jest, jak jest liczone, jakie są normy i dlaczego jest ważne

### v1.0.127 (2026-06-06)

- 🧬 Naprawa liczenia składu ciała z wagi Xiaomi — wszystkie wartości (tkanka tłuszczowa, mięśnie, woda, kości, BMI, tłuszcz trzewny) są teraz zgodne z algorytmem Zepp Life / Mi Fit
- 📊 Nowe wskaźniki: BMR (podstawowa przemiana materii), wiek metaboliczny i procent białka — pełen obraz składu ciała jak w profesjonalnych wagach

### v1.0.126 (2026-06-06)

- 🧬 Nowy ekran "Profil ciała" w menu — ustaw wzrost, wiek i płeć, a waga Xiaomi Mi Scale 2 wyliczy skład ciała (tkanka tłuszczowa, mięśnie, woda, kości, BMI)
- 🔧 Naprawa wykrywania Xiaomi Mi Scale 2 przez Bluetooth — waga z nowszym firmware (kategoria 0x02/0x03) ponownie jest poprawnie rozpoznawana
- 🔧 Naprawa pętli nawigacyjnej — ekran wagi nie pojawia się już wielokrotnie po wyjściu; każdy pomiar przekierowuje tylko raz

### v1.0.124 (2026-06-06)

- 🔧 Naprawa liczenia wartości odżywczych w dzienniku posiłków — suma kalorii i makroskładników uwzględnia teraz rzeczywistą wielkość porcji (servingSizeGrams), a nie wartości na 100g---
_Ostatni build: 2026-06-06 22:27 · v1.0.129_