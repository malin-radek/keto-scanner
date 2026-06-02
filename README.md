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

**[⬇️ Pobierz najnowszy APK — v1.0.96](https://github.com/malin-radek/keto-scanner/releases/tag/v1.0.96)**

[📋 Wszystkie wydania →](https://github.com/malin-radek/keto-scanner/releases)

## 📋 Changelog

### v1.0.95 (2026-06-02)

- 📖 Baza przepisów — Keto-Szef AI zwraca przepisy w strukturalnym formacie JSON, możesz je zapisać jednym kliknięciem
- 💾 Przycisk "Zapisz przepis do bazy" — pod każdym przepisem od szefa pojawia się przycisk do zapisu w lokalnej bazie
- 📚 Przeglądarka zapisanych przepisów — nowy ekran z pełnymi szczegółami: składniki, instrukcje krok po kroku i makro na porcję

### v1.0.94 (2026-06-02)

- 🔧 Poprawa zapisywania wyboru profili — własne profile nie znikają już po zamknięciu aplikacji

### v1.0.92 (2026-06-02)

- 🔄 Automatyczny fallback AI — jeśli Gemini zawiedzie, aplikacja automatycznie przełącza się na NVIDIA (bez utraty odpowiedzi)
- ⭐ Gemini głównym dostawcą AI — gdy masz własny klucz Gemini, jest używany priorytetowo jako szybszy i stabilniejszy

### v1.0.91 (2026-06-02)

- 👨‍🍳 Keto-Szef AI naprawiony — teraz faktycznie odpowiada zamiast pisać "mały błąd"
- 🎭 Szef ma teraz zabawną nazwę dopasowaną do Twojego profilu (Boczkowy Boss, Mięsny Młot, Roślinny Czarodziej...)
- 🎯 Przepisy dopasowane do Twojego profilu — szef zna zasady diety i proponuje tylko zgodne potrawy
- 🛒 Ręczny wybór produktów — kliknij "Wybierz produkty samodzielnie" i zaznacz co masz w lodówce
- ⏰ Podpowiedzi dopasowane do pory dnia — śniadanie rano, obiad w południe, kolacja wieczorem

### v1.0.90 (2026-06-02)

- 🍽️ Rozpoznawanie jedzenia działa teraz na każdym zdjęciu — nie tylko na talerzu; AI rozpozna pojedyncze owoce, przekąski i produkty w dowolnym otoczeniu---
_Ostatni build: 2026-06-02 21:32 · v1.0.96_