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

**[⬇️ Pobierz najnowszy APK — v1.4.14](https://github.com/malin-radek/keto-scanner/releases/tag/v1.4.14)**

[📋 Wszystkie wydania →](https://github.com/malin-radek/keto-scanner/releases)

## 📋 Changelog

### v1.4.13 (2026-06-11)

- 📖 88 zewnętrznych przepisów zaimportowanych do bazy — jajka faszerowane, sałatki, sosy, pasty, dania mięsne, zupy i wiele więcej; gotowe do przeglądania w zakładce „Moje przepisy” z tagami diet i kategorii
- 🏷️ Każdy przepis wyświetla tagi diet (keto, bezglutenowa, wegetariańska itp.) oraz kategorię — ułatwia to dobieranie posiłków do profili dietetycznych

### v1.5.6 (2026-06-10)

- 🖼️ Brandowany splash screen — po uruchomieniu aplikacji od razu pojawia się grafika z logiem i wersją; znika automatycznie gdy aplikacja jest gotowa, dostępna do podglądu w ekranie "O aplikacji"
- 🖼️ Automatyczny pipeline — wystarczy wrzucić plik .png z nazwą wersji (np. 1.5.0.png) do input_files/splash/, a build-apk.sh sam znajdzie najlepsze dopasowanie i wbuduje grafikę do APK; brak pliku = brak splashu, aplikacja działa normalnie

### v1.5.5 (2026-06-10)

- 🧊 Nowy przycisk "Lodówka" na ekranie głównym — dokładnie taki sam wzór jak przycisk "Jedzenie": szybki dostęp do skanowania lodówki z wyborem modelu AI i sprawdzeniem jego dostępności
- 🧊 Wybór modelu AI przed pierwszą analizą — na wzór posiłków: "Szybka analiza" (domyślny model) lub "Wybierz model AI" z listą dostępnych modeli i statusem online/offline

### v1.5.4 (2026-06-10)

- 🧊 Analiza AI w edytorze lodówki działa teraz jak w posiłkach — przycisk jest zawsze widoczny, można ponawiać rozpoznanie z wyborem modelu (Gemini, ChatGPT, OpenRouter, NVIDIA) i podglądem wyników przed zastąpieniem
- 🧊 Szczegółowe komunikaty błędów AI z przyciskami diagnostycznymi (kopiuj curl, odpowiedź API, prompt+zdjęcie) — łatwiej zgłaszać problemy i testować modele

### v1.5.3 (2026-06-10)

- 📱 Znak wodny kodu kreskowego w skanerze jest teraz rysowany jako prawdziwy paskowy kod — nie zawija się na wąskich ekranach i wygląda profesjonalnie na każdym telefonie---
_Ostatni build: 2026-06-11 00:50 · v1.4.14_