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

**[⬇️ Pobierz najnowszy APK — v1.0.153](https://github.com/malin-radek/keto-scanner/releases/tag/v1.0.153)**

[📋 Wszystkie wydania →](https://github.com/malin-radek/keto-scanner/releases)

## 📋 Changelog

### v1.0.151 (2026-06-07)

- 👆 Klikalne kropki na zdjęciu posiłku — tapnij w numer na zdjęciu, a lista przewinie się do odpowiedniego składnika i podświetli go na żółto

### v1.0.150 (2026-06-07)

- 🧊 Nowy ekran wyników skanowania lodówki — zdjęcie z ponumerowanymi punktami dla każdego produktu, z możliwością przybliżania i przesuwania; lista produktów do edycji (nazwa, ilość, kategoria, stan)
- 🔢 Numerowane kropki na zdjęciach posiłków — każdy wykryty składnik ma wyraźny numer, a pod zdjęciem lista z tymi samymi numerami do łatwej edycji
- 💾 Skan lodówki zapisywany w bazie z timestampem — tak jak posiłki w kalendarzu, możesz w każdej chwili wrócić do ostatniego skanu
- 👨‍🍳 Keto-Szef AI korzysta ze skanu lodówki — "obiad z lodówki" automatycznie sprawdza dzisiejszy skan, a jeśli brak — wczorajszy. Jeśli skan jest starszy, Szef pyta czy użyć czy zeskanować od nowa

### v1.0.149 (2026-06-07)

- 🧠 Tekstowe AI (analiza e-sklepów) też sprawdza które modele są dostępne — pomija przeciążonego Geminiego (429) i niedziałające API, automatycznie przełącza się na działającego providera bez marnowania czasu

### v1.0.148 (2026-06-07)

- 🧠 Inteligentny wybór modelu AI — VisionAI automatycznie wykrywa które modele są aktualnie dostępne (np. Gemini nieprzeciążony) i przełącza się między nimi, zanim spróbuje użyć przeciążonego

### v1.0.147 (2026-06-07)

- 📊 Nowy suwak węglowodanów w kreatorze posiłków — intuicyjne przeciąganie zamiast ręcznego wpisywania; widać od razu % dziennego limitu---
_Ostatni build: 2026-06-07 23:13 · v1.0.153_