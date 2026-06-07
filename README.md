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

**[⬇️ Pobierz najnowszy APK — v1.0.148](https://github.com/malin-radek/keto-scanner/releases/tag/v1.0.148)**

[📋 Wszystkie wydania →](https://github.com/malin-radek/keto-scanner/releases)

## 📋 Changelog

### v1.0.149 (2026-06-07)

- 🧠 Tekstowe AI (analiza e-sklepów) też sprawdza które modele są dostępne — pomija przeciążonego Geminiego (429) i niedziałające API, automatycznie przełącza się na działającego providera bez marnowania czasu

### v1.0.148 (2026-06-07)

- 🧠 Inteligentny wybór modelu AI — VisionAI automatycznie wykrywa które modele są aktualnie dostępne (np. Gemini nieprzeciążony) i przełącza się między nimi, zanim spróbuje użyć przeciążonego

### v1.0.147 (2026-06-07)

- 📊 Nowy suwak węglowodanów w kreatorze posiłków — intuicyjne przeciąganie zamiast ręcznego wpisywania; widać od razu % dziennego limitu

### v1.0.146 (2026-06-07)

- 📅 Keto-Szef AI — przycisk "Dodaj do kalendarza" przy każdym przepisie; jednym kliknięciem zapisujesz danie do dziennika posiłków z pełnym makro na 1 porcję

### v1.0.145 (2026-06-07)

- 🧠 Keto-Szef AI — lista produktów z lodówki trafia do promptu TYLKO gdy wybierzesz akcję "Ugotuj coś z moich produktów"; przy zwykłych pytaniach Szef nie zakłada że masz konkretne składniki
- 📋 Profile dietetyczne — AI widzi teraz pełną listę konkretnych składników dla każdej reguły (np. "Unikaj orzechów: migdał, orzech włoski, nerkowiec...") zamiast ID grup, co radykalnie poprawia rozumienie profilu przez model---
_Ostatni build: 2026-06-07 20:29 · v1.0.148_